---
layout: post
title:  "Android: View Binding"
date:   2022-11-16 02:40:00 +0800
categories: Android
---

## build.gradle配置
{% highlight ruby %}
android {
    compileSdk 32
    ...
    buildFeatures{
        viewBinding true
    }
}
{% endhighlight %}

## 对应Binding类
{% highlight ruby %}
val binding = ActivityMainBinding.inflate(layoutInflater)
//ActivityMainBinding按布局文件名，加上Binding结尾
setContentView(binding.root)
//获取跟元素实例
binding.button1.setText("change button")
{% endhighlight %}
