---
layout: post
title: "Jekyll+Github博客系统的构建"
description: ""
category: 
tags: [Jekyll, GitHub]
---
{% include JB/setup %}

## 搭建Jekyll Blog
#### 安装ruby和ruby的DevKit
{% highlight bash %}
$ sudo apt-get install ruby
$ sudo apt-get install ruby-devkit
{% endhighlight %}
#### 安装Jekyll
{% highlight bash %}
$ sudo gem install jekyll
{% endhighlight %}
#### 安装Rdiscount
{% highlight bash %}
$ sudo gem install rdiscount
{% endhighlight %}
#### 安装Python
#### 安装pygments
{% highlight bash %}
$ easy_install pygments
{% endhighlight %}
#### 安装Jekyll引导程序（Jekyll-Bootstrap）
{% highlight bash %}
$ git clone https://github.com/plusjade/jekyll-bootstrap.git USERNAME.github.com
$ cd USERNAME.github.com
$ git remote set-url origin git@github.com:USERNAME/USERNAME.github.com.git
$ git push origin masters
{% endhighlight %}
#### Enjoy

	两分钟后你的Blog神奇的出现在 http://USERNAME.github.com

## 快速开始
#### 本地启动Jekyll服务
{% highlight bash %}
$ cd USERNAME.github.com 
$ jekyll serve
# 别忘了把USERNAME换成你的GitHub用户名。
{% endhighlight %}

#### 创建博文
{% highlight bash %}
$ rake post title="Hello World"
{% endhighlight %}

#### 创建页面
{% highlight bash %}
# 根目录下创建页面
$ rake page name="about.md"
# 自定义目录下创建页面
$ rake page name="pages/about.md"
{% endhighlight %}

#### 发布
{% highlight bash %}
$ git add .
$ git commit -m "one commit"
$ git push origin master
{% endhighlight %}
