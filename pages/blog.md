---
layout: page
title: "Blog"
description: "Blog"
group: navigation
---
{% include JB/setup %}

## Recently Post
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Misc
### [Search]
[Google](http://www.google.com)<br>
[百Google度](http://www.baigoogledu.com)<br>
[Google Scholar](http://scholar.google.com/)<br>
[IEEExplore](http://ieeexplore.ieee.org/Xplore/home.jsp)<br>
[MS Academic Search](http://academic.research.microsoft.com/Default.aspx)<br>
[ACM PKU](http://acm.lib.tsinghua.edu.cn/acm/)<br>
[Wiley Online](http://onlinelibrary.wiley.com/)<br>
[ScienceDirect](http://www.sciencedirect.com/)<br>
[DBLP](http://www.informatik.uni-trier.de/~ley/db/) (Computer Science Bibliography)<br>
[MedSci](http://www.medsci.cn/sciif.asp?action=search) (影响因子)<br>
[SCI](http://www.thomsonscientific.com/cgi-bin/jrnlst/jlresults.cgi?PC=K) (Science Citation Index)<br>
[SCIE](http://www.thomsonscientific.com/cgi-bin/jrnlst/jlresults.cgi?PC=D) (Science Citation Index Expanded)<br>
[EI](http://www.engineeringvillage.com/search/quick.url)<br>
[arXiv.org](http://arxiv.org/)<br>
[Computer Science Bibliographies](http://liinwww.ira.uka.de/bibliography/index.html)<br>
[ProQuest](http://search.proquest.com/index) (国外高质量学位论文全文的数据库)<br>
[国家自然科学基金委员会](http://www.nsfc.gov.cn/Portal0/default152.htm)<br>
[CALIS高校学位论文库](http://etd.calis.edu.cn/)<br>

### [Conference]
CVPR: [2013](http://www.cvpapers.com/cvpr2013.html), [2012](http://www.cvpapers.com/cvpr2012.html), 2011, 2010, 2009<br>
ICCV:<br>
ECCV:<br>
ICASSP:<br>
InterSpeech:<br>

### [Next Coming]
[CVPR 2014, Columbus, Ohio](http://www.pamitc.org/cvpr14/) > Deadline: Nov. 1, 2013<br>
[ECCV 2014, Zurich](http://eccv2014.org/) > Deadline: Mar. 7, 2014 <br>
[ICASSP 2014, Florence, Italy](http://www.icassp2014.org/home.html) > Deadline: Oct. 27, 2013<br>
[Interspeech 2014, Singapore](http://www.interspeech2014.org/public.asp?page=home.html) > ??
## Refs

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)<br>
Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)<br>
[Liquid](https://github.com/Shopify/liquid/wiki/Liquid-for-Designers)<br>
[Markdown 语法说明 (简体中文版)](http://wowubuntu.com/markdown/#precode)<br>
[Jekyll 中的语法高亮：Pygments](http://havee.me/internet/2013-08/support-pygments-in-jekyll.html)<br>
[利用Jekyll搭建个人博客](http://www.mceiba.com/develop/jekyll-introduction.html)<br>
[写作环境搭建(git+github+markdown+jekyll)](http://site.douban.com/196781/widget/notes/12161495/note/264946576/)<br>
[Jekyll - Syntax highlighting](http://truongtx.me/2012/12/28/jekyll-bootstrap-syntax-highlighting/)<br>

## ToDo List
{% highlight c %}
#include <stdio.h>
int main(int argc, char **argv)
{
	printf("Hello, World!\n");
	return 0;
}
{% endhighlight %}
{% highlight c %}
#include <stdio.h>
int main(int argc, char **argv)
{
	printf("Hello, World!\n");
	return 0;
}
{% endhighlight %}
{% highlight tex %}
\documentclass{article}
\usepackage[koi8-r]{inputenc}
\hoffset=0pt
\voffset=.3em
\tolerance=400
\newcommand{\eTiX}{\TeX}
\begin{document}
\section*{Highlight.js}
\begin{table}[c|c]
$\frac 12\, + \, \frac 1{x^3}\text{Hello \! world}$ & \textbf{Goodbye\~ world} \\\eTiX $ \pi=400 $
\end{table}
Ch\'erie, \c{c}a ne me pla\^\i t pas! % comment \b
G\"otterd\"ammerung~45\%=34.
$$
    \int\limits_{0}^{\pi}\frac{4}{x-7}=3
$$
\end{document}
{% endhighlight %}