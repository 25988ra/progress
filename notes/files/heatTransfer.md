> これは日本語での伝熱工学　学習ノート

[toc]

###  1. 伝導伝熱$_{でんどうでんねつ}$
#### 1.1 フーリエ法則$_{ほうそく}$

> 相変化ない場合で、熱の移動
> * 温度こう配がある
> * 高温部分から、低温部分まで 

熱流束$_{ねつりゅうそく}$の（三次元）方程式

$$
q = -k \nabla T\\
\rho c \frac{\partial T}{\partial t}  = 
k \nabla^2 T + \dot q_w\\
$$

|シンボル|意味|
|---|---|
|ｑ|熱流束（$W/m^2$）|
|k|熱伝導率（$W/(m・K)$）----　物質$_{ぶっしつ}$の物性値|
|c|比熱（J/(Kg・K)）|
|$\rho$|物質の密度（$Kg/m^3$）|
|$\dot q_w$|内部単位時間、単位体積の発熱量($W/m^3$)|

**座標系$_{ざひょうけい}$変化**

* 円筒座標系
$\begin{cases}
x = rcos(\theta) \\
y = rsin(\theta)　\\
z = z 
\end{cases} \\
\rightarrow \nabla_{x,y,z}^2 T = \frac{1}{r}\frac{\partial }{\partial r}(kr\frac{\partial T}{\partial r}) + \frac{1}{r^2}\frac{\partial }{\partial \theta}(k\frac{\partial T}{\partial \theta}) + \frac{\partial}{\partial z}(k\frac{\partial T}{\partial z}) $
* 球座標系
$\begin{cases}
x = rsin(\theta)cos(\phi) \\
y = rsin(\theta)sin(\phi)\\
z = rcos(\theta)
\end{cases} \\
\rightarrow \nabla_{x,y,z}^2 T = \frac{1}{r^2} \frac{\partial }{\partial r}(kr^2\frac{\partial T}{\partial r}) + \frac{1}{r^2 sin(\phi)}\frac{\partial }{\partial \theta}(k\frac{\partial T}{\partial \theta})  + \frac{1}{r^2 sin(\phi)}\frac{\partial }{\partial \phi} (ksin(\phi)\frac{\partial T}{\partial \phi}) $

