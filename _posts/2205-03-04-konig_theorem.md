---
layout: post
title: "柯尼希定理"
date:   2025-03-04
tags: [Physics]
comments: true
author: llz3724
---


我们知道有质点系，质点系的动量是好算的，那质点系的动能和质心有什么关系？

设$m_i,v_i$是质点系第$i$个对象的质量、相对于地面的速度，$m_c,v_c$是质心的质量、速度，显然有

$$
K_{total}=\sum_{i}^{}\frac{1}{2}m_iv_i^2 
$$

设$v_i'=v_i-v_c$是第$i$个对象相对质心的速度，代入$K_{total}$的定义式得

$$
K_{total}=\sum_{i}^{}\frac{1}{2}m_i(v_i'+v_c)^2=\sum_{i}^{}\frac{1}{2} m_iv_i'^2+v_c\sum_{i}^{}m_iv_i'+\sum_{}^{}\frac{1}{2}m_iv_c^2\\
=K_c+\sum_{i}^{}K'_i+v_c\sum_{i}^{}m_iv_i'
$$

而质心系中，质心速度的定义是

$$
\sum_{i}^{}m_iv_i=Mv_c\\
\sum_{i}^{}m_iv_i'=0
$$

所以

$$
K_{total}=K_c+\sum_{i}^{}K'_i
$$

给了我们一种新的计算总体的动能的方法。

然而和图论的柯尼希定理并没有什么关系。

一质量为$m$，半径为$R$的细圆环在地面上无摩擦以$\omega$的角速度滚动，求圆环动能。

$K_{total}=\frac{1}{2}m(\omega R)^2+\sum_{i}^{}\frac{1}{2} m_i(\omega R)^2=2\times \frac{1}{2}m\omega^2R^2=m\omega^2R^2$

