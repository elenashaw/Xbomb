# intro

* external/internal forced
* natural convection
* phase change
* heat exchanger



# fundamentals 

## outline

* convective heat transfer equation
* 边界层理论
* 相似理论
* 边界层模拟



## basic concepts

### 与导热的比较

* 都需要medium

* differently: convection needs **fluid motion**

* model compare

* ![image-20240318081540448](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240318081540448.png)

  > [!caution]
  >
  > * convection: superposition of transport by **random motion** of the molecules and by the **bulk motion** of the fluid.
  > * Advection: transport due to bulk liquid motion.



## Newton's law of cooling

### heat flux formula

$$
q"=h(T_s-T_\infty)
$$

* q": local heat flux(W/m2) at one point
* h: local convection heat transfer coefficient (W/m2/K)

### heat transfer rate formula

$$
q=\int_{As}q"dA_s=(Ts-T_\infty)\int_{As}hdA_s
$$
* average convection heat transfer coefficient
  * ![image-20240318082258863](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240318082258863.png)
> [!NOTE]
>
> * 得到h是一个重要的点



## governing equation of a simple model

### Fluid Mechanisms

#### :sparkles:simple model

* For steady (laminar flow）
*  two-dimensional
* incompressible flow 
* with constant fluid properties

#### :sparkles: mass conservation

![image-20240318082610214](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240318082610214.png)

* control volume analysis

#### :sparkles:momentum conservation

![image-20240318082629524](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240318082629524.png)

#### :sparkles: energy conservation

![image-20240318082702537](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240318082702537.png)

* $\Phi$对于粘性低的流体，很小，可以忽略
* $\dot q$: inner heat sources



## Boundary layer theory

### base of our analysis

![image-20240318091657271](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240318091657271.png)

### boundary layer model

#### fluid model

![image-20240318091723016](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240318091723016.png)

* **non-slip condition:** the fluid in motion comes to a complete stop at the surface and assumes **a zero velocity relative to the surface**

##### parameters:

* **Surface shear stress**
* **viscosity**
  * dynamic viscosity:	$\mu$
  * kinematic viscosity:     $\nu=\mu/\rho$

* **Local friction coefficient**



#### thermal model

![image-20240318092908778](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240318092908778.png)

***non-temperature jump condition:** When two bodies at different temperatures are brought into contact, heat transfer occurs until both bodies assume the same temperature at the point of contact. Therefore, a fluid and a solid surface will have the same temperature at the point of contact. This is known as no-temperature-jump condition

当两个不同温度的物体接触时，会发生热传递，直到两个物体在接触点具有相同的温度。因此，流体和固体表面在接触点处将具有相同的温度。这被称为无温度跳跃条件





## Laminar and turbulent flow

### 层流和湍流的传热比较

* 层流在边界处的传热是导热，湍流的还包括bulk motion



### Reynold's Number

#### definition

$$
Re=\frac{Inertial \ Force}{Viscous}
$$

#### formula

* for flow on a plate

#### 特征长度

* 圆管
  * 直径

#### values in 3 flows

* 分布图![image-20240320101801420](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240320101801420.png)

  * > [!note]
    >
    > 湍流中，Fluid motion is highly irregular，增强了动量和能量的传递

* 值
  * transition
  * laminar
  * turbulent
