---
title: "이 블로그 설명서"
permalink: /about/
toc_sticky: true
toc_ads : true
author_profile: true
layout: single 
---

## devinlife.github.io 블로그







# 모아모아



일단 여기다가 모두 정리 해놓고 나중에 분류 하도록 합시다.



##### git

------



```
git config --global user.email "you@example.com"
git config --global user.name "내 이름"
```



```
git add .
```



```
git commit --amend --no-edit
```



commit 이후 아래 명령으로 서버로 올리기.

```
git push origin master
```





##### ruby

------

에러 발생

```
current directory: /tmp/bundler20191031-6425-18owzvbeventmachine-1.2.7/gems/eventmachine-1.2.7/ext
/usr/bin/ruby2.5 -r ./siteconf20191031-6425-zhgvp6.rb extconf.rb
mkmf.rb can't find header files for ruby at /usr/lib/ruby/include/ruby.h
```



```
sudo apt-get install ruby-dev
```



`bundle exec jekyll serve`



```
/var/lib/gems/2.5.0/gems/jekyll-3.8.6/lib/jekyll/theme.rb:84:in `rescue in gemspec': The jekyll-theme-slate theme could not be found. (Jekyll::Errors::MissingDependencyException)
```



| vi Gemfile                                                   |
| ------------------------------------------------------------ |
| source "https://rubygems.org"<br/>gem "jekyll-theme-minimal"<br/>**gem "jekyll-theme-slate"**<br/>gemspec |



