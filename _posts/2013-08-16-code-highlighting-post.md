---
layout: post
title: Syntax Highlighting Post
description: "Demo post displaying the various ways of highlighting code in Markdown."
modified: 2013-08-20
tags: [sample post, code, highlighting]
image:
  feature: abstract-10.jpg
  credit: dargadgetz
  creditlink: http://www.dargadgetz.com/ios-7-abstract-wallpaper-pack-for-iphone-5-and-ipod-touch-retina/
comments: true
share: true  
---

Here is some text. This is a link: [Syntax highlighting](http://en.wikipedia.org/wiki/Syntax_highlighting)

### Here is a level 3 heading

blah blah blah
blah blah blah
blah blah blah
blah blah blah


# Level 2 heading

Here is an image: 
[!Alt
text](https://lh4.googleusercontent.com/-OfCrRsO9tl8/UtFgjdUR_oI/AAAAAAAAh4w/hXwEslupcXk/s400/Screen+Shot+2014-01-11+at+9.17.04+AM.png
"i am the title")


    {% raw %}
    <nav class="pagination" role="navigation">
        {% if page.previous %}
            <a href="{{ site.url }}{{ page.previous.url }}" class="btn" title="{{ page.previous.title }}">Previous article</a>
        {% endif %}
        {% if page.next %}
            <a href="{{ site.url }}{{ page.next.url }}" class="btn" title="{{ page.next.title }}">Next article</a>
        {% endif %}
    </nav><!-- /.pagination -->
    {% endraw %}

