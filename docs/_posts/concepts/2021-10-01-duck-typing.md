---
layout: post
title:  Duck Typing
date:   2021-10-01 21:37:29 +0800
categories: concept
---

Duck typing是一个有趣的概念

大体意思可以认为，在一些弱类型语言中（比如python），你大可不必在意某个变量的实际类型，比如它是class，还是function，还是一个variable，其实都不重要。例如只要这个对象可以遍历，我们就可以当它是一个遍历序列类型，至于它是tuple、list、dict还是一个function、class，其实都不重要。

就好像这个东西，只要它走起来像鸭子、叫起来像鸭子，那就当它是个鸭子。

例如在python中，一个类型或者实体只要有__iter__和__next__方法，我们就认为它可以遍历，用就完了。

Duck typing in computer programming is an application of the duck test— "If it walks like a duck and it quacks like a duck, then it must be a duck"— to determine if an object can be used for a particular purpose. With normal typing, suitability is determined by an object's type.
