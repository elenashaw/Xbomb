heat transfer-conduction(fundamaentals)

# Temperature distribution

##  Temperature Field

### def

instantaneous temperature distribution of conductive object

### math expressions

* Steady-state temperature field 
  * <img src="../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240226080643425.png" alt="image-20240226080643425" style="zoom:50%;" />
* Transient temperature field
  * <img src="../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240226080655650.png" alt="image-20240226080655650" style="zoom:50%;" />
* 补充<img src="../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240226081529392.png" alt="image-20240226081529392" style="zoom:50%;" />

### graphs-isothermal curve

* rules

  * 等温线不会交叉

  * 完全闭合或者在边界处中断

  * 沿着一条线不会有热量传递，没有温度梯度

  * 越密集，温度梯度越大
  * 等温线和界面的夹角可以判断界面是否绝热（绝热界面与等温线垂直）

## temperature gradient

### def 

Temperature gradient is the temperature rate in a direction perpendicular to the 
isothermal curves (surfaces) , and changes relative to change in normal distance

### graph

<img src="../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240226081324355.png" alt="image-20240226081324355" style="zoom:50%;" />

* 向量：
  * 方向： 垂直于等温线，**指向温度增加的方向**
    * 传热方向指向温度减小的方向

### math expressions

<img src="../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240226081714172.png" alt="image-20240226081714172" style="zoom:50%;" />

### 温度梯度是传热的动力

# 导热率方程（The Conduction Rate Equation — Fourier’s Law）

## 导热

### 传热方式

* Transfer of heat takes place through direct contact.
  热量通过直接接触传递。

### 导热机制

* Occurs in solids, due to molecular collisions.
  由于分子碰撞，发生在固体中。

## 傅里叶定律

### 方程

* 导热率方程(heat transfer rate)
  * $q=-kA\nabla T=-kA\frac{\partial T}{\partial n}\vec{n}$​
  * 单位（q): W
  * 注意这不是Q，是q
* 热通量方程(heat flux)
  * $q\prime \prime=-k\nabla T=-k\frac{\partial T}{\partial n}\vec{n}$​
  * 单位(q``):$W/m^2$

### 维度

* 方程
* K系数与各向同/异性

* * 

### 傅里叶导热解释

* 温度梯度是热量传递的动力
* 热量传递的方向：垂直于等温线，指向温度低的方向
* 热量传递的大小q,q``：取决于温度分布/温度梯度的大小
* 普适性：傅立叶导热是实验定律，基本定律普遍适用（变物性、内热源、非稳态、固液气）适用条件

### 傅里叶定律不适用的条件

* 传导物体的温度接近0K
* 热传导在很短的时间内（$10^{-8}-10^{-10}s$）。
* 微纳米尺度上的传热

## 导热系数（thermal conductivity)

#### 特性

* 材料相
  * $K_{solid}>K_{liquid}>K_{gas}$
* 材料种类
  * $K_{metal}>K{nonmerallic \ solid}$
* 各向异性和各向同性
  * 石墨，木材这些的导热性具有各向异性

#### 单位

* W/(m·K)]

#### 数量级

* 由实验测定值
* 常见值
  * Copper *k*＝399 [W/(m·K)]
  * Iron *k*＝80 [W/(m·K)]
  * Water *k*＝0.599 [W/(m·K)] 
  * Air *k*＝0.0259 [W/(m·K)]

#### 热传导系数的变化

* 对于工程材料，k在正常温度和压力范围内随温度呈线性变化。
* 一般使用K((T1+T2)/2)

#### 物理意义

* Thermal conductivity indicates the ability of a material to conduct/transfer heat.

  导热系数表示材料传导/传热的能力。

# Extended Parameters

## **Volumetric Heat Capacity** （体积热容VHC）

* 定义： <img src="../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240226084010969.png" alt="image-20240226084010969" style="zoom:50%;" />
* 单位：J/(m3·K)
* 物理意义: 每单位体积上升一单位温度需要的热量（储能能力）
* 数量级：

## **Thermal Diffusivity**（热扩散率）

### 热扩散率

* 定义：<img src="../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240226084212730.png" alt="image-20240226084212730" style="zoom:50%;" />
* 单位：$m^2 /s$

* 物理意义： Larger α = less time to reach a new equilibrium condition（扩散热量的能力）
  * 热扩散率大的材料：更快达到平衡温度，测量时间更短

### 热扩散方程

#### 方程

* ![image-20240226092346821](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240226092450215.png)

#### 推导

* 建立模型

  * <img src="../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240226090900549.png" alt="image-20240226090900549" style="zoom:50%;" />

* 原理：能量守恒

  * <img src="../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240226090944200.png" alt="image-20240226090944200" style="zoom: 67%;" />

* 参数推导

  * 泰勒展开

    * <img src="../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240226091020448.png" alt="image-20240226091020448" style="zoom:67%;" />

  * $E_g=q*dx*dy*dz$

    * q is the rate at which energy is generated per unit volume of the medium (W/m3
      )

      介质单位体积产生能量的速率

  * $E_{st}=\rho c_p \frac{\partial T}{\partial t}dx \ dy \ dz$
    * 没有相变下（没有潜能的变化）
    * $\rho c_p \frac{\partial T}{\partial t}$​ is the time rate of change of the sensible (thermal) energy of the medium
      per unit volume.

#### 假设与简化

* 常数假设
* 无热源假设
* 稳态假设

#### 参数与物理解释

* $\dot{q}$: generated heat
* **热扩散率（导温系数）**
  * $\alpha=\frac{\lambda}{\rho c}$​
  * 单位： $m^2/s$​
* $\frac{\partial t}{\partial t}$=0 if steady state

#### 其他坐标系



# 稳态导热的边界与初始条件

## overview

* ![image-20240226092732144](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240226092732144.png)

## 三种类型

### 表面温度不随时间变化（类似于thermal reservoir）

* $\huge\ T(x,t)=T_s$​

### 边界表面热通量

#### 有热传递

$$\huge  -k\frac{\partial T}{\partial x} _{x=0}=q_s"$$ 

#### 无热传递（绝热）

* $$\huge  \frac{\partial T}{\partial x} _{x=0}=0$$ 



#### 对流表面热通量与导热热通量

* $$\huge  -k\frac{\partial T}{\partial x} _{x=0}=h(T_\infty -T(0,t))"$$ 



* > [!NOTE]
  >
  > * 对称的中间是绝热的

  

  

### 三类边界条件(中文课件)

* 第一类 1st B.C.
  * ![image-20240228102948582](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240228102948582.png)

* 第二类
  * ![image-20240228103019986](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240228103019986.png)

* 第三类
  * ![image-20240228103048461](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240228103048461.png)