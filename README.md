# LaTeX 示例工程

安装好 TexLive（或者 MiKTeX）后，进入项目目录，运行以下命令进行编译：
```shell
latexmk main.tex
```

清理编译过程中生成的辅助文件：
```shell
latexmk -c
```

在 `build/` 目录下会生成 `main.pdf` 文件，即编译后的 PDF 文档。你可以使用 PDF 阅读器打开它查看结果。