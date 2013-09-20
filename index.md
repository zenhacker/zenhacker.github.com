---
layout: page
title: ZenHacker
tagline: 
---
{% include JB/setup %}



## Recently Post
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
    
## Common Link
### Search
* [Google](http://www.google.com)
* [百Google度](http://www.baigoogledu.com)

## Refs

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

[Liquid](https://github.com/Shopify/liquid/wiki/Liquid-for-Designers)

[Markdown 语法说明 (简体中文版)](http://wowubuntu.com/markdown/#precode)

[Jekyll 中的语法高亮：Pygments](http://havee.me/internet/2013-08/support-pygments-in-jekyll.html)

[利用Jekyll搭建个人博客](http://www.mceiba.com/develop/jekyll-introduction.html)

[写作环境搭建(git+github+markdown+jekyll)](http://site.douban.com/196781/widget/notes/12161495/note/264946576/)

[Jekyll - Syntax highlighting](http://truongtx.me/2012/12/28/jekyll-bootstrap-syntax-highlighting/)
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
