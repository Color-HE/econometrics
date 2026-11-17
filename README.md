# 计量经济学

计量经济学课程作业整理，提供 PDF 与 LaTeX 源码。

## 作业目录

| 内容 | 题目 | PDF | LaTeX |
| --- | --- | --- | --- |
| 伍德里奇《计量经济学导论》第七章：虚拟变量与交互项 | 第 1—13 题 | [查看解答](assignments/wooldridge/chapter-07/solutions.pdf) | [查看源码](assignments/wooldridge/chapter-07/main.tex) |

本次作业包含完整原题、按顺序编排的解答、必要的推导与计算，以及原题中的数字和符号勘误。

## 编译

使用支持中文排版的 TeX 发行版，以 XeLaTeX 编译：

```bash
cd assignments/wooldridge/chapter-07
xelatex -jobname=solutions main.tex
```

编译结果保存在当前目录的 `solutions.pdf`。
