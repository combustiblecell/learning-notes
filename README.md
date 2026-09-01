# learning-notes

按原书目录组织的中文提炼版学习笔记。仓库同时保存 LaTeX 源文件和可直接阅读的 PDF；原书文件不入库。

## 书目

- 《动手学深度学习》PyTorch 版
  - 状态：全书提炼（前言、安装、符号、第 1–15 章与附录）
  - 原书版本：`d2l-zh 2.0.0`
  - 原书源：本地 `d2l-zh/pytorch` Jupyter Notebook（PyTorch 1.12.0）
  - 源文件说明：该本地副本的前五章位于 `000chapter_*`，但全书索引仍使用标准 `chapter_*` 名称；笔记以索引中的原书目录顺序为准
  - LaTeX：`books/《动手学深度学习》PyTorch版/main.tex`
  - PDF：`books/《动手学深度学习》PyTorch版/《动手学深度学习》PyTorch版-学习笔记.pdf`

## 编译

在书籍目录运行：

```powershell
& "D:/Miniconda/envs/latex/python.exe" `
  "C:/Users/Lenovo/.cursor/skills/learning-notes/compile-book.py" `
  "main.tex"
```

与 `/english-learning` 相同：只编辑 `.tex`，由 XeLaTeX 编译并覆盖固定 PDF；若 PDF 正被占用，则保留 `*-build.pdf`。
