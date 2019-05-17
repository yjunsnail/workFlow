## substance 学习资料
![Substance_Painter_Orc](https://support.allegorithmic.com/documentation/spdoc/files/20316164/170459743/2/1536351466340/Substance_Painter_Orc.jpg)
1. https://academy.substance3d.com/ 中文教材(点右上角中文)
2. prb引导文档(点右上角中文)
>* https://academy.substance3d.com/courses/the-pbr-guide-part-1
>* https://academy.substance3d.com/courses/the-pbr-guide-part-2


## 换肤捏脸调色 换装(包含顶点mask)
1. uma方案 
> https://www.youtube.com/playlist?list=PLkDHFObfS19zFVfbrfB14P-u5QJJQyvtP
2. 皮肤
>油脂层 透光性 皮肤泛红 SSS
3. 头发
>高光切线法 双层高光 透明度 AlphaTest 做多次的pass
4. 眼睛
>分层 瞳孔 眼白 泪腺 角膜(高光) 睫毛


## 水
##### [flowmap](https://mp.weixin.qq.com/s?__biz=MzIyMzQzNDAyNg==&mid=2247484087&idx=1&sn=b2fa7f5af318785e72cd9428776093f8&chksm=e81f06f2df688fe441a4c7a6db229b69bbcd3de23a07e59670e8a97d41765b1be099e2e7a6cd&scene=21#wechat_redirect)

## ik
##### [约束](https://docs.unity3d.com/Packages/com.unity.animation.rigging@0.2/manual/index.html)
##### 动作状态机

##### 爬墙
>https://www.youtube.com/playlist?list=PL47vwJBRNh1xzEvcLvXoJvjLcr1h0j-1O
##### 游泳

## [镜头](https://docs.unity3d.com/Packages/com.unity.cinemachine@2.3/manual/index.html) 角色控制器
1. [基本 镜头](https://docs.unity3d.com/Packages/com.unity.cinemachine@2.3/manual/CinemachineFreeLook.html) CinemachineFreeLook 可设置穿透遮挡体
2. [状态 镜头](https://docs.unity3d.com/Packages/com.unity.cinemachine@2.3/manual/CinemachineStateDrivenCamera.html) (由于动作的不同镜头的推进拉远等)

## 场景
1. navmesh
2. collide

## 场景效果
1. linear space
2. 烘培
3. HDR 天空球
4. Reflection Probe 来增加反射效果，也可用它来区分环境
5. Light Probe 来做动态物体的间接光
6. emission 调hdr色
7. [PostEffect](https://docs.unity3d.com/Packages/com.unity.postprocessing@2.1/manual/index.html) 主要为(bloom/Lut) 
>1. [光照介绍](https://unity3d.com/learn/tutorials/topics/graphics/introduction-lighting-and-rendering?playlist=17102&_ga=2.257319819.1060887464.1557711885-1438279476.1522757191)
>2. 一个铁道的[demo内含源码](https://unity3d.com/learn/tutorials/s/creating-believable-visuals?_ga=2.257319819.1060887464.1557711885-1438279476.1522757191)
>3. [更好光线的7个小提示](https://lmhpoly.com/7-tips-for-better-lighting-in-unity/) 

## 场景优化方案
1. 遮蔽
2. subScene


## 角色打光
1. 镜头光
2. Light Probe 动态取改
3. sh9/vertexLight


## 扩展编辑器
>https://www.youtube.com/playlist?list=PLs023Yclit4nom70pyx0wIxQLWf4Q7nIU
