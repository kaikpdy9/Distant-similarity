
Distant similarity
=========================
<p align="left">
    <img src='https://img.shields.io/badge/-%E8%AE%B0%E5%BD%95-yellow.svg' alt="Build Status">  
    <img src='https://img.shields.io/badge/-%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%A8%8B%E5%BA%8F-blue.svg'>
    <img src='https://img.shields.io/badge/-%E8%BD%BB%E7%A4%BE%E4%BA%A4-green.svg'>
    <img src='https://img.shields.io/badge/-%E6%A0%91%E6%B4%9E-brightgreen.svg'>
    <img src='https://img.shields.io/badge/-%E6%B2%BB%E6%84%88-red.svg'>
</p>

****
## 目录
* [总览](#总览)
    * 项目是做什么
    * 怎么做
    * 有什么
    * 要什么

* [软件功能介绍](#软件功能介绍)

* [用户界面交互体验](#用户界面交互体验)

* [数据介绍](#数据介绍)

* [项目进程](#项目进程)

* [组队计划](#组队计划)




### 总览
-----------
  Q:   项目是做什么?    

  A:  一款记录自己看过的电影，书，音乐，和自己走过的地方，并以良好的交互形式展示出来，另外还有探索功能，让用户走出家门，去拍下当地的地标，从而解锁成就排行，还具有轻社交功能，可以实现用户与用户之间的简单交互（受限） 
  
  Q:   怎么做?     
    
  A:   python+web+UI    

  Q：  有什么
   
  A：  写python的
  
  Q：  要什么
  
  A:   * [组队计划](#组队计划)
  
  
### 软件功能介绍
-----------

![](https://github.com/Zr3Lm9Yh/Distant-similarity/blob/master/img/app%E5%8A%9F%E8%83%BD.png)



- 记录   
     形式上来说和豆瓣一样，不过多出来记录去过的地方，以及完成的探索，每个人都是独立——distant


- 轻社交   
     独立的个体，或许会有相似性，就像平行世界以外的你一样，或许在某个角落一粒尘埃，在那晃动，如你的影子——similar


> ps:所谓轻社交，用户与用户之间的交互，就是通过以上5中匹配功能进行跳转，相似达到一定比即可跳转到对方用户主界面，即对方的记录界面，但是不能留言，只能留下脚印，或者点赞

- 探索   
     探索周围熟悉和不熟悉的东西，在线索已知的时候，在重邮的校园里，用手机，拍下那一张照片，解锁一个个地方

> 关于实现： 这是一个5分类的问题，类似于手写数字的识别，不过识别的对象是地标，前期的特征处理很重要，具体可以参照Google Landmark Retrieval Challenge https://www.kaggle.com/c/landmark-retrieval-challenge  如何对照片进行特征处理



### 用户界面交互体验 
-----------
 
-  色彩淡一点好（需要一个UI设计 ＞︿＜）


-  交互形式一起讨论比较好


-  界面就讨论后，要pix就好


-  整体调调像那种宇宙真空的感觉很棒  




![](https://github.com/Zr3Lm9Yh/Distant-similarity/blob/master/img/yuzhou.jpg)



>  丑死了对吧哈哈哈
>>  颜色淡一点吧




![](https://github.com/Zr3Lm9Yh/Distant-similarity/blob/master/img/yuzhou1.jpg)





![](https://github.com/Zr3Lm9Yh/Distant-similarity/blob/master/img/yuzhou2.jpg)




### 数据介绍
-----------


![](https://github.com/Zr3Lm9Yh/Distant-similarity/blob/master/img/database.png)


> 这只是一些数据元素，具体数据库讨论后，用access可视化和用mysql部署





### 项目进程
-----------

-  超级超级超级初期，即当产品定位吧


-  to be continued


-  to be continued


-  to be continued


-  to be continued





### 组队计划
-----------


>  打算采用MVC开发模式，也就是这个项目的话只有3人。。。
>     MVC https://baike.baidu.com/item/MVC%E6%A1%86%E6%9E%B6/9241230?fromtitle=MVC&fromid=85990&fr=aladdin

>>      但是百度的和我理解的不一样哈哈哈哈
>>      那就以我自己话来说了


>>      M 的话对应于微信小程序，我觉得就好像前端一样
>>       ,即你要展示给用户的界面的框架是什么样子
>>
>>      V的话是视图，这里的话就是指 UI 了,比如在background
>>       -image =  url 这里的背景图要设计出来
>>
>>       C 的话是算法，也就是假如你在修图网站里，使用黑白滤镜
>>       的功能，当你点击按钮后,你上传进服务器的那个照片，会
>>       在执行python 算法.py，将生成的图片传回给用户,那个p
>>       ython 算法.py 就是C的部分内容   


     当然，像我理解这种开发模式，肯定还差东西，比如，
     你将相册提交到服务器里，怎样传回来，用php? 亦或
     者其他语言，这个的话，到就大家一起写点吧哈哈哈
      






