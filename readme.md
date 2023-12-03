# Tongji-CV

## 示例

<p align="center">
      <img src="https://github.com/tj-csccg/tongji-cv/blob/main/figure/demo.jpg" width="50%">
</p>


## 致谢

该项目生成自 [fky2015/resume-ng](https://github.com/fky2015/resume-ng)。原仓库的设计非常美观，借助合适的排版用最少的版面展示最多的信息，并且多而不乱。

本仓库作为补充，仅新增了以下功能：

* 左上角可放置校徽；
* 每一条经历在日期旁可放置多个 logo；
* 使用 fontawesome5 来美化个人信息。

## 原仓库部分 README

> 常用用法可参考 `main.tex` 中的示例内容。
>
> * `\ResumeName{}` 定义简历标题（一般是姓名）。
> * `\ResumeContact{}` 添加一个联系方式。
> * `\ResumeContacts{itemA, itemB, itemC}` 添加多个联系方式。
> * `\ResumeTitle` 渲染标题和联系方式。
> * `\section{}` 节标题。
> * `\ResumeItem[]{}[][]`
>   1. 可选参数，控制 PDF 书签内容。如果不提供则采用参数 2。
>   2. 项标题，左对齐。
>   3. 可选参数，右对齐，用来放置 logo，在参数 4 前显示。
>   4. 可选参数，右对齐。
> * `\GrayText{}` 改变文字内容为灰色。
> * `\ResumeUrl{}{}` 带有下划线的 `\href` 命令，与 `\href` 用法相同。
>
> `[]` 为可选参数， `{}` 为必需参数。
>
> **如果你使用 TeXLive/MiKTeX 等主流发行版，可以直接使用本项目，无需手动安装依赖。**
> 否则，请确保以下依赖安装：
>
> * geometry
> * fancyhdr
> * enumitem
> * footmisc
> * hyperref
> * xeCJKfntef
> * xcolor
> * ctex
