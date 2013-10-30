---
layout: post
title: "2，实现一次真实调用"
category : "php-sdk-doc"
tagline: "nanoyun存储"
tags : [配置]
---
{% include JB/setup %}

1, 打开writeFile.php程序，在程序的第9行，打开一个本地的文件流，这就是你要指定的将要存储到Nano云存储中的文件

<img src="{{ BASE_PATH }}/assets/images/php-sdk-filehandle.jpg" style="width:600px;" />

2，程序第10行，指定上传到Nano云存储中的文件位置

3，运行程序后的返回结果为JSON串

	上传成功后，返回：
	success：上传成功，结果为true
	size：上传文件的大小，单位为字节

 <img src="{{ BASE_PATH }}/assets/images/php-sdk-execute.jpg" style="width:600px;" />


#注意

demos文件夹中的程序都可以采用本示例的方法进行执行。