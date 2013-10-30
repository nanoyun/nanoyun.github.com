---
layout: post
title: "1，配置php-sdk中的参数"
category : "php-sdk-doc"
tagline: "nanoyun存储"
tags : [配置]
---
{% include JB/setup %}

## 编辑根目录下的config.php

    其中设定了3个参数
      APPKEY：权限校验的依据
      APPSECRET：权限校验的依据
      SPACENAME：操作的空间名称

1，获取appkey和appsecret

<img src="{{ BASE_PATH }}/assets/images/getkeys.jpg" style="width:600px;" />

2，查看要操作的空间名称

<img src="{{ BASE_PATH }}/assets/images/php-sdk-spacename.jpg" style="width:600px;" />

3，前面2步获取的值，分别替换到config.php中

<img src="{{ BASE_PATH }}/assets/images/php-sdk-config.jpg" style="width:600px;" />