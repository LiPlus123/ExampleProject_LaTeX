# LaTeX 示例工程

极简的中文 LaTeX Book 项目示例，包含常用的数学环境、参考文献、术语索引等功能，适合初学者参考和使用。

## 构建方式

安装好 TexLive（或者 MiKTeX）后，进入项目目录，命令行运行命令：
```shell
latexmk main.tex
```

在 `build/` 目录下会生成 `main.pdf` 文件，即编译后的 PDF 文档。可以使用 PDF 阅读器打开它查看结果。

命令行运行命令：
```shell
latexmk -c
```

清理 `build/` 目录下编译过程中生成的辅助文件。