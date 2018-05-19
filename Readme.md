＃ NUAA-Beamer  
---
南航主题的LaTex Beamer模版   
初步计划在[唐磊-THUBeamer](https://github.com/tl3shi/THUBeamer)基础上进行修改  

##说明： 
demo.tex       主文件  
logo.pdf       NUAA logo文件   
thubeamer.sty  sty文件（主题颜色设置，block等）  
ref.bib        参考文献  

> * thubeamer.sty取自[唐磊-THUBeamer](https://github.com/tl3shi/THUBeamer)  
> * logo.pdf取自[nuaatug/nuaathesis](https://github.com/nuaatug/nuaathesis)的nuaa-logo.pdf  
> * 配色RGB #006aae取自NUAA官网[http://www.nuaa.edu.cn/](http://www.nuaa.edu.cn/)  
> * 在我答辩时的整体放映效果并不是很好(也有可能是投影仪的问题)  

## log:  
2018/05/19 13:17:58 增加了参考文献脚注设置，文献信息放在ref.bib中。
2018/03/01 13:53:14 修改了导言区设置，对文档中的英文使用Times字体，对数学公式使用professionalfonts字体主题  
2018/02/26 10:12:51 修改了thubeamer.sty中的配色  
\xdefinecolor{nuaa}{rgb}{0.0,0.415,0.682}  %RGB #006aae (0,106,174)  

## 编译 
我的系统--Ubuntu14.04 版本--TeXLive 2018  
xelatex demo.tex  
xelatex demo.tex  
bibtex  demo  
xelatex demo.tex  
