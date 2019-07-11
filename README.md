# LaTeX文档导言配置

我的LaTeX导言配置是适用使用XeLaTeX引擎进行文档编译。

使用latexmk作为编译脚本时，需要指定参数-xelatex。

如果是在Visual Source Code中使用latex workshop扩展，需要进行配置修改，因为其默认采用-pdf参数，也就是用pdflatex引擎进行文档编译的。

```
latexmk -xelatex 
```

