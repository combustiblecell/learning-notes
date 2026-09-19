# learning-notes

按原书目录组织的中文提炼版学习笔记。仓库同时保存 LaTeX 源文件、可直接阅读的 PDF，以及有信息量的原书图（放在各书 `figures/`）。原书 PDF/全文不入库。

## 书目

- 数值线性代数
  - 状态：试作版；绪论与第 1.1 节（三角形方程组和三角分解/LU）已充实；第 1.2 节起及第 2–7 章仅保留原书目录
  - 原书版本：徐树方、高立、张平文《数值线性代数》第二版，北京大学出版社，2011 年修订
  - 原书源：本地扫描 PDF（原书不入库）
  - LaTeX：`books/数值线性代数/main.tex`
  - PDF：`books/数值线性代数/数值线性代数-学习笔记.pdf`

- 计算方法与优化
  - 状态：试作版；第 1 章「基础知识」按定义加案例提炼（学期安排保留，导论其余页不记）；后续各讲待课件
  - 原书版本：武汉大学数学与统计学院戴书洋《计算方法与优化》2026–2027 秋季第 1 讲课件
  - 原书源：本地 `C:\Users\Lenovo\Desktop\CM+Opt_ch1.pdf`（原课件不入库）
  - LaTeX：`books/计算方法与优化/main.tex`
  - PDF：`books/计算方法与优化/计算方法与优化-学习笔记.pdf`

- 计算机系统导论下
  - 状态：试作版；第 7 章已充实至库打桩（第 7.10、7.11、7.13、7.15 节）并在小结后收录「练习」；第 7.12、7.14 节与第 8–12 章仅保留原书目录
  - 原书版本：*Computer Systems: A Programmer's Perspective* 第三版（Bryant & O'Hallaron, 2015）；中文章节名依机械工业出版社《深入理解计算机系统》第三版
  - 原书源：CSAPP 第三版目录（官方前言 PDF `csapp.cs.cmu.edu/3e/pieces/preface3e.pdf` 与正文第 7 章）；课堂材料为 15-213 Lecture 13 Linking（2015-10-13）
  - LaTeX：`books/计算机系统导论下/main.tex`
  - PDF：`books/计算机系统导论下/计算机系统导论下-学习笔记.pdf`

- 《动手学深度学习》PyTorch 版
  - 状态：全书提炼（前言、安装、符号、第 1–15 章与附录）；已按原书插入有信息量的图，图号沿用原书并在图下注释符号
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
