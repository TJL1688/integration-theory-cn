# 克莱松积分论

本仓库用于整理、翻译与校验 T. Claesson 和 L. Hörmander 所著《积分论》讲义的中文 LaTeX 版本。

项目采用 `ctexbook` 文档类排版，正文按章节拆分，便于后续校订、补充注释和重新编译 PDF。

> 说明：本项目主要用于个人学习、教学参考与排版校勘。原著相关版权归原作者及相应权利方所有。十分感谢感谢科学出版社的原始翻译！！

## 内容简介

目前整理内容包括：

- 前言；
- 第一章：黎曼积分；
- 第二章：勒贝格积分；
- 第三章：拉东--斯蒂尔杰斯积分；
- 附录；
- 综合练习；
- 综合练习的提示。

本讲义从 Riemann 积分出发，逐步过渡到 Lebesgue 积分、Radon--Stieltjes 积分以及测度分解等内容，适合作为学习实变函数论、积分理论和测度论的参考材料。

## 项目结构

```text
克莱松积分论/
├── 积分论.tex                         # 主文件
├── 积分论（克莱松，霍尔德曼）.pdf       # 已编译 PDF
└── body/
    ├── chapter1.tex                   # 黎曼积分
    ├── chapter2.tex                   # 勒贝格积分
    ├── chapter3.tex                   # 拉东--斯蒂尔杰斯积分
    └── chapter4.tex                   # 附录、综合练习与提示
```

## 编译方式

建议使用 XeLaTeX 编译。

在项目根目录下运行：

```bash
xelatex 积分论.tex
xelatex 积分论.tex
```

如果使用 TeXstudio、VSCode LaTeX Workshop 或 Overleaf，请将主文件设置为：

```text
积分论.tex
```

## 主要依赖

编译环境建议使用较完整的 TeX 发行版，例如 TeX Live、MacTeX 或 MiKTeX。项目中用到的主要宏包包括：

- `ctexbook`
- `amsmath`, `amsthm`, `amssymb`
- `mathtools`
- `physics`
- `tikz`, `tikz-3dplot`
- `pgfplots`
- `hyperref`
- `makeidx`
- `listings`
- `xy`
- `esdiff`
- `diagbox`

## 版本状态

当前版本为校验版，后续可能继续进行：

- 文字校对；
- 术语统一；
- 公式与编号检查；
- 练习与提示的对照校订；
- 排版细节优化；
- 补充注释或学习说明。


## 版权说明

本项目仅作学习、研究、教学参考和 LaTeX 排版校勘之用。若涉及原著版权问题，请以原书及相关权利方要求为准。
