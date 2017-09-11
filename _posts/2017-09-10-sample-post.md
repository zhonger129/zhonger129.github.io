---
layout: post
title: Build website with github page + Jekyll
excerpt: "The blog is my experience regard to build a website with github page and Jekyll on MacOS. Inculding install ruby, Jekyll, bundler...examples for post a blog with Jekyll theme"
categories: [guide]
comments: true
---

# Build github website with Jekyll

## 1. Update ruby to latest version

### Current status
* macOS Seirra version 10.12.6<br>
* ruby 2.0.0 already installed with system defualt

### Target to update ruby to latest version

Install latest version ruby using brew <br>
simons-mbp:~ Simon$ brew install ruby

**problem**  <br>
Use "ruby -v" to check the version, it's still system default version 2.0.0

simons-mbp:~ Simon$ which -a ruby <br>
/usr/bin/ruby # default is still the system default version for ruby <br>
/usr/local/bin/ruby

**Resolution** <br>
after installing ruby via homebrew just do this:<br>
brew link --overwrite ruby <br>
and restart or reopen your Terminal <br>

restart terminal <br>
simons-mbp:~ Simon$ which -a ruby <br>
/usr/local/bin/ruby <br>
/usr/bin/ruby

## 2. setup GitHub page + Jekyll

refer to [blog -> ref1][blog1]
refer to [blog -> ref2][blog2]

[blog1]:      https://blog.r3bl.me/en/jekyll-blogging-like-a-pro/
[blog2]:      https://devblast.com/b/create-a-static-websiteblog-with-jekyll-and-github-pages

