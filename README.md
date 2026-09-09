# learning-notes

按原书目录组织的中文提炼版学习笔记。仓库同时保存 LaTeX 源文件和可直接阅读的 PDF；原书文件不入库。

## 书目

- 计算机系统导论下
  - 状态：试作版；已充实第 7 章课堂已授部分（至静态库扫描），第 7.10–7.15 节与第 8–12 章仅保留原书目录
  - 原书版本：*Computer Systems: A Programmer's Perspective* 第三版（Bryant & O'Hallaron, 2015）；中文章节名依机械工业出版社《深入理解计算机系统》第三版
  - 原书源：CSAPP 第三版目录（官方前言 PDF `csapp.cs.cmu.edu/3e/pieces/preface3e.pdf` 与正文第 7 章）；课堂材料为 15-213 Lecture 13 Linking（2015-10-13）
  - LaTeX：`books/计算机系统导论下/main.tex`
  - PDF：`books/计算机系统导论下/计算机系统导论下-学习笔记.pdf`

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
