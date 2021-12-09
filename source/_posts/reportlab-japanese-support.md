---
title: ReportLab Japanese Support
date: 2021-12-09 16:34:50
tags:
---

ReportLab输出PDF文件中如果需要用到其他语言，例如，日文，只需要添加必要的字体即可。Python 3编程中不需要考虑字符串编码问题。

```
# registerFont
pdfmetrics.registerFont(UnicodeCIDFont('HeiseiMin-W3'))
```

字体文件HeiseiMin-W3只要安装在系统默认的路径即可。