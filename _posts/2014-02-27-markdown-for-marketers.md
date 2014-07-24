---
layout: post
title: Reduce Costs of Marketing Content with Markdown
subtitle: A Marketer's Experience with the Popular Markup Language
date: 2014-02-27
comments: false
author: Craig Oda
tags:
  - marketing tools
---
<img src = "/img/blog/2014/02/GitHub_head.png" height = "50" hspace="3" align="left">
	     Markdown is a popular formatting language often 
	     used by developers for documentation or to communicate 
	     with each other.  Marketers need to learn it too.
{{ excerpt_separator}}

---
![StackEdit Online Markdown Editor](/img/blog/2014/02/2014-02-27-stackedit.png "StackEdit"){:.pull-right .img-responsive}

![mdcharm.png](/img/blog/2014/02/mdcharm.png "MdCharm Markup Editor")

[Markdown](http://en.wikipedia.org/wiki/Markdown "Markdown Wikipedia Entry") is often used in by developers and product marketing teams to write readme files, blogs, forums, and question and answer sites.  The primary advantage of Markdown is that it is easy to include code snippets.  Since developers often use code snippets to communicate ideas, marketers need to become more efficient at communicating with code snippets pulled from a forum or the engineering team if they want to effectively reach developers.

GitHub, reddit, Diaspora, [Stack Overflow][1], and [SourceForge](http://sourceforge.net/p/forge/documentation/markdown_syntax/) use Markdown.  It is also the common format for documentation engines or static web site generators such as [Jekyll](http://jekyllrb.com/ "Jekyll").  

To quickly and cheaply publish useful information to developers, marketers should learn to use a Markdown editor at some point.  There are too many Markdown editors to choose from.  Mashable has a list of [78 Markdown tools](http://mashable.com/2013/06/24/markdown-tools/).  It is overwhelming.
 
Knowing that Mashable is not site that specifically targets developers, I realized that using a Markdown editor was getting close to mass adoption by non-technical people.  Although there are many alternatives to Markdown and it is easy to avoid using it, Markdown is very popular. You can either fight the trend or use it to your advantage.

One of the really common uses of Markdown is to include a snippet of code into the email, forum post, blog post, response on a QA site, or short piece of documentation.  This may not be a problem for the older generation of marketers that are not putting code snippets into their marketing material, but there's a new crop of marketers, often from product marketing, that are engaging with the community of developers.  This type of marketing often involves sending some level of short configuration or code snippets to people. 

As I marketer, I was pretty happy with using MS Word to write marketing material.  The world changed around me as I found groups in my target audience audience using these tools:

![GitHub.png](/img/blog/2014/02/GitHub.png "GitHub Cats")
![StackOverflow.png](/img/blog/2014/02/StackOverflow.png "Stack Overflow Answers")
![Discourse.png](/img/blog/2014/02/Discourse.png "Discourse")
![jekyll.png](/img/blog/2014/02/jekyll.png "Jekyll")
![octopress.png](/img/blog/2014/02/octopress.png "Octopress")

Kunalo recently moved our blog over to Jekyll and I'm writing this blog post in Markdown using a graphic editor called [MdCharm](http://www.mdcharm.com/ "MdCharm main site").  It's not quite as easy as writing a press release in MS Word, but it's easier for me than using a text editor like Emacs.

Images are a bit tricky as I haven't figured out how to get them to display properly in the editor.

![mdcharm_screenshot.png](/img/blog/2014/02/mdcharm_screenshot.png " MdCharm Screenshot")

The images looks fine in a web browser and can be tested on the same computer with Jekyll using 
```$
jekyll --server --auto
```

You can then preview the blog post run through Jekyll at: 
```
http://localhost:4000
```

Mashable compiled a great list of Markdown editors called [78 Tools for Writing and Previewing Markdown](http://mashable.com/2013/06/24/markdown-tools/ "Mashable article on Markdown tools").


There were a number of online editors including:

* Dillinger
* StackEdit
* Mou

A friend of mine also recommended [MultiMarkdown for Mac](http://multimarkdown.com/ "MultiMarkdown editor for Mac")

People on the Ubuntu Discourse forum pointed me to [Sublime Text](http://www.sublimetext.com/ "main sublime site") and [Light Table](http://www.lighttable.com/ "Light Table editor").  Although these look great, I wasn't able to get Light Table to work properly and Sublime is a bit pricey for me.  

For now, MdCharm does the job.

Here's an example of an email I sent to a developer about our corporate blog.  I'm trying to figure out how to get help changing the look of our blog so that it has better formatting of excerpts.  In most companies, managing the blog is the responsibility of marketing.  So, this is applicable to a wide range of marketers.  I'm using Gmail, Google enterprise apps to send the email is Firefox. 

In the first picture, I just copied and pasted a configuration snippet into the body of the email.

![markdown_raw.png](/img/blog/2014/02/markdown_raw.png "Raw markdown before sending")

Using the browser plug-in, [Markdown Here](http://markdown-here.com/ "Markdown Here") I simply right-click and select Markdown Toggle, making the configuration snippet and marketing question easier to understand.

![markdown_rendered.png](/img/blog/2014/02/markdown_rendered.png "Markdown format rendered with Markdown Here")

The Markdown Here site has several other [great examples](http://markdown-here.com/features.html "great examples of markdown use"). 

---

**Update 2014 March 4**

- wrote a blogger post with [StackEdit.io](https://stackedit.io/) and pubished the post to blogger from within StackEdit.  The blog post contained a section of Python code.  The formatting was preserved.
- I'm updating this post directly inside of the Jekyll git repository on my local Linux machine with [ReText](http://sourceforge.net/projects/retext/), a package that primarily works on Linux, but can work on Mac OS X with homebrew.
- I attempted to write a new blog post on blogger with Markdown Here and failed.  The formatting of the Python code got messed up.





[1]: http://stackoverflow.com/editing-help
 

 
