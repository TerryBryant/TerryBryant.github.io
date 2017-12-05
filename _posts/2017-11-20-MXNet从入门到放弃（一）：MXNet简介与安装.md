---
layout: post
title: "MXNet从入门到放弃（一）：MXNet简介与安装"
image: 'https://raw.githubusercontent.com/dmlc/web-data/master/mxnet/image/mxnet_logo.png'
category: '博客'
tags:
- deep learning
- MXNet

introduction: 技术类博客的第一篇，从零开始学习MXNet，希望能坚持下去
---

> 与Tensorflow的庞大而缓慢、caffe复杂的依赖环境不同，MXNet具有轻量级、省显存的特点。

# 一、MXNet简介

某度目前还没有MXNet的词条，这里总结下wiki上的内容，并结合自己的见解，简单介绍下MXNet框架。MXNet是一个较新的深度学习框架，它的特点包括支持多种语言接口（例如C++、Python、Matlab），支持多机器多GPU等等。与Tensorflow的庞大而缓慢、caffe复杂的依赖环境不同，MXNet具有轻量级、省显存的特点。

前几个月，MXNet还增加了gluon接口，使得构建深度学习模型更加方便和灵活。目前在tensoflow越来越强势的情况下，MXNet获得了亚马逊、微软、英特尔等大量企业的支持，未来应该可以和tensoflow打个平手，另外facebook推出的caffe2和pytroch结合起来，和前面两者应该会形成三足鼎立的局面。

# 二、为什么学MXNet

随着Theano不再更新，渐渐地许多深度学习框架都会被淘汰，个人感觉最终只会剩下前面提到的几个巨头。tensorflow太大太笨重（不过最近试了下新出的eager模式，还比较灵活），caffe2目前还很不完善（caffe配置太麻烦），pytorch线上部署不友好。综合以上，我选择MXNet。

# 三、如何学MXNet

目前MXNet的作者之一李沐大神在大力推进MXNet的普及，总结如下几个学习资源网站：
1、MXNet中文教程：http://zh.gluon.ai/index.html
2、MXNet中文论坛：https://discuss.gluon.ai/
3、李沐大神不定期（一般是周六）在斗鱼上会进行直播：https://www.douyu.com/1086863
纸上得来终觉浅，绝知此事要躬行！

# 四、MXNet安装

MXNet的安装还是很简单的，参考<a href="http://mxnet.incubator.apache.org/install/index.html">官网</a>
GPU版本的安装稍复杂一些，但其实配置好CUDA和Cudnn就行了。


-----
