# MathJax_Aurthur

MathJax是一款运行在浏览器中的开源的数学符号渲染引擎，使用MathJax可以方便的在浏览器中显示数学公式，不需要使用图片。目前，MathJax可以解析Latex、MathML和ASCIIMathML的标记语言。 MathJax项目于2009年开始，发起人有American Mathematical Society, Design Science等，还有众多的支持者，个人感觉MathJax会成为今后数学符号渲染引擎中的主流，也许现在已经是了。

可以说，对于大部分的数学公式，目前MathJax的功能和显示效果已经完全可以媲美于LaTex，而HTML/CSS对位置和格式的控制能力要比LaTex更强大。经过我们的多次测试，MathJax的兼容性还是非常棒的，这基本已经贴近我们心中所想了。

对于此项目来说，数学习题可以用LaTex语言来书写，这对于老师来说是极大的福音，因为Tex语言他们再熟悉不过了。反过来对于我们来说也是极大的福音，在MathJax将Tex语言渲染后，我们可以随心所欲的控制其样式，这样我们就可以将习题界面展现的更加优雅，更加美观。

到此我们基本已经决定使用MathJax来展现我们的数学公式，然而在使用下来发现以下几个客观不足性：

* 直接使用MathJax官方提供的CND共开库，国内访问速度并不是很理想，有时会出现 Math Processing Error 的错误。解决方案是将其JS渲染库clone到自己服务器，这种错误可以得到保障，我已经clone了一份最新版到GitHub与Git@OSC上并且去掉了一些不相关的文件，保留了JS核心库、测试文档与docs，大家有需要可以拿去。

* [MathJax官方文档](http://docs.mathjax.org/en/latest/start.html)很详细但是不提供中文版，需要大家英语水平不错才行。由于MathJax真心不错，我可能会考虑发起翻译计划，将其最新的开发文档翻译成中文，便于国人的使用。

**[Demo](http://blog.gitos.cn/2015/05/10/Mathematical-formula-demo.html)** 

