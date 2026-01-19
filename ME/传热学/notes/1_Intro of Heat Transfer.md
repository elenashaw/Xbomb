:smile: More Information: https://www.engr.colostate.edu/CBE101/topics/heat_transfer.html

# Intro of Heat Transfer

### What is heat transfer

The movement of heat across the border of the system due to a difference in temperature between the system and its surroundings

___

#### concepts

* thermal energy in transit
  * unit: J
* spatial temperature difference
  * unit: K, $^{\circ}$​C
* heat
  * unit: J
* $E=f(t,T)$​

___

#### basic topics

* 物体内部的温度分布
* 热量的传递速率
* 强化或消弱热量传递的方法





### 传热学和热力学的区别

传热学

​	重点在于热传递的过程： 温度分布，热量传递速率

​	t(x,y,z,$\tau$​)

​	$\Phi=f(\tau)$​

![image-20240219083325674](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240219083325674.png)

热力学

​	重点在于系统总体的热平衡变换

​	$Q=\Delta U+W$​

![image-20240219083150379](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240219083150379.png)

### theory basics

#### 1st thermal dynamics law

#### 2nd thermal dynamics law



### basic assumptions

* 连续介质假设
* 稳态与非稳态传热





# CCR（3 ways of heat transfer)

___

## Conduction

### def

**Conduction**: Heat transfer in a solid or a stationary fluid (gas or liquid) due to the random motion of its constituent atoms, molecules and /or electrons.
传导：固体或静止流体（气体或液体）由于其组成原子、分子和/或电子的随机运动而产生的传热。

### 思想实验与定量描述

### 傅里叶定律

![image-20240219091049916](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240219091049916.png)

#### thermal conductivity

![image-20240219091536913](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240219091536913.png)

___

## Convection

### def

**Convection**: Heat transfer due to the combined influence of bulk (advection) and random motion for fluid flow over a surface.
对流：由于体积（平流）和流体在表面上流动的随机运动的共同影响而产生的传热。

### 定量描述-Newton's Law of Cooling

![image-20240219091903361](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240219091903361.png)

#### The heat transfer coefficient

Like the mass transfer coefficient, the heat transfer coefficient in strongly influenced by the boundary layer. In particular, it depends on the geometry, flow conditions, fluid, and process.
与传质系数一样，传热系数受边界层的强烈影响。具体而言，它取决于几何形状、流动条件、流体和工艺。

### boundary layers related

* diffusion
* advection

___

## Radiation

### def

**Radiation**: Energy that is emitted by matter due to changes in the electron configurations of its atoms or molecules and is transported as electromagnetic waves (or photons).
辐射：由于物质的原子或分子的电子构型发生变化而发出的能量，并以电磁波（或光子）的形式传输。

There is no mass transfer analogue to radiation.
没有辐射的传质类似物。\

### 三种形式

![image-20240219092401408](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240219092401408.png)

### 定量描述-Radiation rate equation

![image-20240219092555220](../../../../Users/eleev/AppData/Roaming/Typora/typora-user-images/image-20240219092555220.png)

___

# Thermodynamics Laws

## 1st law

### Energy in the system

* ![image-20240221102610529](C:\Users\eleev\AppData\Roaming\Typora\typora-user-images\image-20240221102610529.png)

* ![image-20240221103056582](C:\Users\eleev\AppData\Roaming\Typora\typora-user-images\image-20240221103056582.png)

* $E_{in}$:
  *  进入系统的能量
  * input
* $E_g$
  * 系统内生成的能量
* $E_{out}$
* $E_{st}$
  * storage
  * 系统保存的能量(Stored thermal and mechanical energy)
  * 稳态时，Est=0

* system type
  * control volume
  * closed system
* time basis 
  * t
    * instant
    * W(J/s)
    * The rate of increase of thermal and mechanical energy stored in the control volume must equal the rate at which thermal and mechanical energy enters the control volume, minus the rate at which thermal and mechanical energy leaves the control volume, plus the rate at which thermal and mechanical energy is generated within the control volume.
  * $\Delta t$
    * time interval
    * E(J)
    * The increase in the amount of thermal and mechanical energy stored in the control volume must equal the amount of thermal and mechanical energy that enters the control volume, minus the* amount of thermal and mechanical energy that leaves the control volume, plus the amount of thermal and mechanical energy that is generated within the control volume.

### Energy - heat and work

* formula
  * ![image-20240221103842825](C:\Users\eleev\AppData\Roaming\Typora\typora-user-images\image-20240221103842825.png)

* signal convention





# questions

* Ut
* Usen: sensible energy
* Ulat: latent enegy