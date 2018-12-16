# pandoc-tutorials
Pandoc tutorials

pandoc --pdf-engine=xelatex -V mainfont="SimSun" -o sample.pdf sample.md
pandoc -D latex > mytemplate.tex
pandoc --pdf-engine=xelatex --template=template.latex -o sample.pdf sample.md

# How install font on Ubuntu
- Robot
- Sans

# Install pandoc filters
- pandoc-citeproc
- pandoc-attributes
- pandoc-eqnos
- pandoc-fignos
- pandoc-tablenos
- pandocfilters

https://blog.csdn.net/zhouxiaowei1120/article/details/82818295

# Tex Basics
- Tex TeX 是一种排版语言
- LaTex 在Tex指令集合的基础上定义了一整套宏集，方便用户进行排版,可以看成是Tex的一种实现
- XeTeX 相较LaTex另一种Tex的实现。支持Unicode 编码和直接访问操作系统字体。
- XeLaTex 是XeTeX中的一个命令，用来编译LaTex格式书写的tex源文件，起到兼容LaTex的作用
- TextLive Tex套件，囊括Tex周边的一些程序，类似于编译器 跨平台
- MikTex windows平台下的Tex套件，与TextLive功能相似，TextLive与MikTex相当于是Tex的两个不同发行版
- TexMaker LaTex的书写工具 IDE 用来辅助排版，不是必须的 跨平台可在linux下使用

# beamer
beamer是一个宏包，就和article差不多
直白说，PPT知道吧，beamer即PPT，找个beamer模板，直接打开，录入，编译即可。出来的是PDF，演讲时，PDF全屏和PPT差不多效果

# 中文问题
https://jingyan.baidu.com/article/ff411625e229d512e482379c.html
https://my.oschina.net/zenologo/blog/60160
[启用字体](https://blog.csdn.net/yanxiangtianji/article/details/17539571)
