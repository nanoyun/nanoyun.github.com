---
layout: page
title: Nano云存储SDK简介
tagline: Supporting tagline
---

{% include JB/setup %}

<a href="http://www.nanoyun.com" target="_blank"><image src="{{ BASE_PATH }}/assets/images/nanoyun_logo.jpg" /></a>

Nano云存储是通用的大规模存储服务。开放高度可扩展的API，开发人员可轻松使用，帮助互联网企业以极其低的价格，获得可靠、安全、快速的基础存储系统。

## 如何成为Nano云存储开发者？

### 官网[注册账号](http://www.nanoyun.com/user/register.html)

简单填写一些注册信息，开启云端的日子吧~

### [登陆](http://www.nanoyun.com/user/login.html)管理中心，[点击账号设置](http://www.nanoyun.com/user/setting.html)获取APPKEY和APPSECRET

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:
    
    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


