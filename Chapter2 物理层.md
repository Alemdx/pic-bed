# 物理层的基本概念

# 数据通信的基础知识

## 数据通信系统的模型

数据通信系统可以分为三大部分：**源系统、传输系统、目的系统**

![image-20220220161541323](/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220161541323.png)

源系统一般分为两个部分：

+ 源点
+ 发送器

目的系统一般分为两个部分：

+ 接收器
+ 终点

![image-20220220162144467](/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220162144467.png)

## 有关信道的几个基本概念

信道（Channel）一般是用来表示向某个防线传送信息的媒体。因此通信电路往往包含**一条发送信道**和**一条接收信道**。

信息交互的三种基本方式：

+ 单项通信   广播这种
+ 双向交替通信    双方都可以收发，但不能同时
+ 双向同时通信     可以同时收发信息

## 信道的极致容量

传输距离远会产生噪声

![image-20220220165825734](/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220165825734.png)

限制码元在信道上传输速率的因素：

+ 信道能够通过的频率范围
+ 信噪比![image-20220220170339812](/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220170339812.png)

# 物理层下面的传输媒体

## 引导型传输媒体

### 双绞线

![image-20220220170826378](/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220170826378.png)

![image-20220220170900904](/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220170900904.png)

### 同轴电缆

<img src="/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220171006066.png" alt="image-20220220171006066" style="zoom:50%;" />

### 光缆

![image-20220220171232465](/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220171232465.png)

优点：

![image-20220220171413087](/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220171413087.png)

## 非引导型传输媒体

+ 微波通信
+ 卫星通信

# 信道复用技术

## 频分复用、分时复用和统计时分复用

![image-20220220172035503](/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220172035503.png)

**频分复用的所有用户同样的时间占用不同的带宽资源**（类似于广播频道？）

![image-20220220172441535](/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220172441535.png)

**分时复用的所有用户是在不同的时间占用同样的频带宽度**（分时间段占用）

![image-20220220172452351](/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220172452351.png)

## 波分复用

就是光的分频复用

![image-20220220192028640](/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220192028640.png)

## 码分复用

**各用户使用经过特殊挑选的不同码型，因此个用户之间不会造成干扰**

# 数字传输系统

好像没什么。。。

# 宽带接入技术

## ADSL技术

**非对称数字用户线**

**ADSL的下行（从ISP到用户端）都远远大于上行（从用户端到ISP）**

**利用已有的电话线**

## 光纤同轴混合网（HFC网）

**在原先电视网的基础上开发的居民宽带接入网。**每个用户能够共享的数据量的大小，取决于有多少个用户在这条电缆上共享数据。

![image-20220220194202995](/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220194202995.png)

**需要一个机顶盒和电缆调制解调器**。（可不可以理解为机顶盒是获取下行数据，电缆调制解调器是为了上行数据？）

## FTTx技术

Fiber to the....（光纤到。。。）

![image-20220220195156746](/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220195156746.png)

# 本章重要概念

![image-20220220200734584](/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220200734584.png)

![image-20220220200746441](/home/jackson/snap/typora/46/.config/Typora/typora-user-images/image-20220220200746441.png)