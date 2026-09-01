# learning-notes

按原书目录组织的中文提炼版学习笔记。仓库同时保存 LaTeX 源文件和可直接阅读的 PDF；原书文件不入库。

## 书目

- 《动手学深度学习》PyTorch 版
  - 状态：试作版（第二章“预备知识”）
  - 原书版本：`d2l-zh 2.0.0`
  - 原书源：本地 `d2l-zh/pytorch` Jupyter Notebook（PyTorch 1.12.0）
  - 源文件说明：该本地副本的前五章位于 `000chapter_*`，但全书索引仍使用标准 `chapter_*` 名称；笔记以索引中的原书目录顺序为准
  - LaTeX：[main.tex](books/%E3%80%8A%E5%8A%A8%E6%89%8B%E5%AD%A6%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E3%80%8BPyTorch%E7%89%88/main.tex)
  - PDF：[《动手学深度学习》PyTorch版-学习笔记.pdf](books/%E3%80%8A%E5%8A%A8%E6%89%8B%E5%AD%A6%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E3%80%8BPyTorch%E7%89%88/%E3%80%8A%E5%8A%A8%E6%89%8B%E5%AD%A6%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E3%80%8BPyTorch%E7%89%88-%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0.pdf)

## 编译

在书籍目录运行：

```powershell
latexmk -xelatex -interaction=nonstopmode -halt-on-error main.tex
```
