
Distant similarity
=========================
<p align="left">
    <img src='https://img.shields.io/badge/-%E5%9B%BE%E5%83%8F%E8%AF%86%E5%88%AB-yellow.svg'>  
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
    * 目前有什么
    * 目前需要什么

* [软件功能介绍](#软件功能介绍)

* [用户界面交互体验](#用户界面交互体验)

* [数据介绍](#数据介绍)

* [项目进程](#项目进程)

|`这是一个 ~~删除线~~`|这是一个 ~~删除线~~|

* [app策划书版](#app策划书版)

* [最后](#最后)


### 总览
-----------
  Q:   项目是做什么?    

  A:  一款记录自己看过的电影，书，音乐，和自己走过的地方，并以良好的交互形式展示出来，另外还有探索功能，让用户走出家门，去拍下当地的地标，从而解锁成就排行，还具有轻社交功能，可以实现用户与用户之间的简单交互的微信小程序（[受限](#受限)） 
  
  Q:   怎么做?     
    
  A:   python+web+UI    

  Q：  目前有什么
   
  A：  写python的
  
  Q：  目前需要什么
  
  A:  [组队计划](#组队计划)
 
  
### 软件功能介绍
-----------

![](https://github.com/Zr3Lm9Yh/Distant-similarity/blob/master/img/app%E5%8A%9F%E8%83%BD.png)



- 记录   
     形式上来说和豆瓣一样，不过多出来记录去过的地方，以及完成的探索，每个人的爱好都是不一样的  ——distant


- 轻社交   
     独立的个体，或许会有相似性，——similar


> ps:所谓轻社交，用户与用户之间的交互，就是通过以上5中匹配功能进行跳转，相似达到一定比即可跳转到对方用户主界面，即对方的记录界面，但是不能留言，只能留下脚印，或者点赞， 

  ###### 受限 
  关于软件的社交功能，其实我还是有点纠结，本意还是不要太社交化，遥远性，所以关于用户与用户是否可以交流暂时先否定吧(对对对，就是实现不了哈哈哈)  


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

 但是百度的和我理解的不一样哈哈哈哈，那就以我自己话来说了
      


-   M 的话对应于微信小程序，我觉得就好像前端一样
   ,即你要展示给用户的界面的框架是什么样子

-   V的话是视图，这里的话就是指 UI 了,比如在background
   -image =  url 这里的背景图要设计出来

 -  C 的话是算法，也就是假如你在修图网站里，使用黑白滤镜
    的功能，当你点击按钮后,你上传进服务器的那个照片，会
    在执行python 算法.py，将生成的图片传回给用户,那个p
    ython 算法.py 就是C的部分内容   


     当然，像我理解这种开发模式，肯定还差东西，比如，
     你将相册提交到服务器里，怎样传回来，用php? 亦或
     者其他语言，这个的话，到就大家一起写点吧哈哈哈


 总结下   :   
-  需要一个写微信小程序前端的 ，不过可能还要写点后端代码
   （包含一起设计数据库）
   
-  需要一个UI设计 


### app策划书版
-----------

> 以下内容全是瞎写的，这边建议不要看了


关于这次互联网创新创业大赛，第一次参加，参加之前，还满有信心的，但是写了好多项目的介绍后，才发现这个真的有好多问题。

首先，不得不说，真的感觉有好多，外包进学校来参加比赛的公司，这些项目也就是所谓的大项目吧，手里拿着好多好多的原始数据，它原本的销售数据，用户注册数据，本身从一开始，就不能和他们相比，更别提像这样连code都没写好的项目了，我还开始想着造假数据哈哈哈哈~可是连代码都没开始写，这样来的数据谁信呀
哈哈哈哈。 那就加创意组吧，可是自己当然不甘心，因为我觉得我真的为了能够实现这个项目，将自己好多好多想法都扼杀了。然后才写了这个看着。貌似能够实现的东西(。・∀・)ノ，哈哈也只能说应该，当然关于策划书的部分，我还是决定，打算不要脸的写下去，乱编也要把我的想法给编上去

> 以下吹牛



其实这个项目的主要目的是建立一个地标检索的数据库

你可以通过这个api接口，识别全世界的名胜古迹

等等这不是google的项目吗，你干嘛去抄袭别人的想法，丢人

https://firebase.google.com/docs/ml-kit/recognize-landmarks?hl=zh-cn

但是，我这个还加入了人文进去

人文+地理=完美
 
可以在地标图片里多放些特征在里面

比如这个地方的历史（eg.埃菲尔铁塔建成的历代历史照片，以及它的故事）

亦或者像项目里那样的游戏，找到对应的地标进行拍照完成解锁，并在个人页面的足迹mark

并且还调用google map api接口（那谷歌不得气死）

那就调用baidu map api接口，当你在外面逛街的时候

就好比你在南岸区瞎逛的时候

app通过baidu map api识别到你的位置

并且从服务器相册里随机生成一张你周围的地标照片

由于角度问题，你需要找到一个大概吻合的角度进行拍照

从而完成任务

通过这个api接口还可以实现社交的交互

比如你可以对一个从来没有上传进服务器的地标，拍照

并上传到，输入它的名字，服务器记录是谁上传的，在哪个时间上传的，并且记录你目前的位置
当有第二个人上传的时候输入它的名字，和上传照片

服务器一旦发现，两者匹配（三方面匹配 名字和照片内容还有以及调用baidu map api的大概位置，三者进行权重）

第二个即可查看第一个人的足迹，随着人越来越多，这个地方被越来越多的人发现

慢慢地，这一个个的足迹何尝不是这个地标建筑的历史呢

慢慢地人们开始尝试去探索

去探索那些未经发现的美好

最后岂不是我们地球上的所有地方都有这么多特征数据了

hahahah

那以后用地图的时候，是不是可以显示那些数据呢，

显示那些陌生人的足迹了呢

去看他们的精神世界是不是更方便了呢

在地球上的一个个小点点，仿似独立地漂浮在地球上

或许两个点走过的足迹正好，正好在听同一首歌呢




### 最后 
-----------

关于这个应用的名字

- 遥远的相似性

灵感来自霍金曾在采访里说过的一句话

>What are the things you find most beautiful in science?

>Science is beautiful when it makes simple explanations of phenomena or connections between different observations. Examples include the double helix in biology, and the fundamental equations of physics.

不知道是谁意译的

总之很美好












