# LaTeX标准模板
摘要：

"LaTeX标准模板.tex"仅使用了TeXLive自带的宏包，未使用第三方宏包，里面对每一个部分写了简略的注释，可满足日常自己写文要求，如果要求更加美观，可去寻找第三方宏包。

"refenence.bib"仅示范性引用了一篇参考文献，实际上bib文件可引用多篇文献。

“LaTeX标准模板.pdf"展示了tex文件编译出的pdf的效果。

注意本文并不面向LaTeX新手，而是为已经学过LaTeX的人提供一个快捷模板（主要是我自己），毕竟每次引用的宏包都差不多，没必要每次都输入，况且有些命令我也记不住。

---




## tex文件和bib文件

tex文件是源文件，bib文件是参考文献，注意bib文件需要放到和tex文件一个目录。

其他文件是tex文件编译后产生的，但我们需要的仅仅是pdf文件。

![](https://github.com/wsg201608/My-Articles/blob/master/LaTeX/LaTeX%E6%A0%87%E5%87%86%E6%A8%A1%E6%9D%BF/%E5%9B%BE%E7%89%87/%E6%A0%87%E5%87%86%E6%A8%A1%E6%9D%BF.png)

tex文件用texstudio或texwork打开并编辑（注意需要有texlive环境），bib文件可用文本编辑器打开，在创建bib文件时只要把后缀改为bib即可。

bib文件内部：

![](https://github.com/wsg201608/My-Articles/blob/master/LaTeX/LaTeX%E6%A0%87%E5%87%86%E6%A8%A1%E6%9D%BF/%E5%9B%BE%E7%89%87/bib%E6%96%87%E4%BB%B6%E5%86%85%E9%83%A8.png)

在tex文件中用cite命令时，是第一行的AndersonMore，格式为\cite{AndersonMore}，注意这个AndersonMore是可以更改的，其他行不可随意更改。

bib文件的撰写和引用可部分参阅[百度经验](https://jingyan.baidu.com/article/925f8cb8bce1f0c0dce0564f.html)。

texstudio界面与texwork不一样：

![](https://github.com/wsg201608/My-Articles/blob/master/LaTeX/LaTeX%E6%A0%87%E5%87%86%E6%A8%A1%E6%9D%BF/%E5%9B%BE%E7%89%87/%E7%BC%96%E8%BE%91%E5%99%A8%E7%95%8C%E9%9D%A2.png)

如图右边是pdf文件预览，左边是tex文件源码。在编译时直接点那个绿色的鱼型的按钮即可（即绿色的三角形旁边那个）。与texwork不同的是，它内置了一些快捷命令，并且没texwork麻烦。（注意编译目录时需要两次编译）

## pdf文件

pdf文件仅仅只展示了最基本的功能但不包括表格和公式及图片。

这些需要时再插入表格和公式及图片。
