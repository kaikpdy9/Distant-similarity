
Distant similarity
=========================
<p align="left">
    <img src='https://img.shields.io/badge/-%E8%AE%B0%E5%BD%95-yellow.svg' alt="Build Status">  
    <img src='https://img.shields.io/badge/-%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%A8%8B%E5%BA%8F-blue.svg'>
    <img src='https://img.shields.io/badge/-%E8%BD%BB%E7%A4%BE%E4%BA%A4-green.svg'>
    <img src='https://img.shields.io/badge/-%E6%B2%BB%E6%84%88-orange.svg'>
</p>

软件的功能介绍
=========================
![](https://github.com/Zr3Lm9Yh/Distant-similarity/blob/master/img/app%E5%8A%9F%E8%83%BD.png)

- recording

- Landmark identification 1：地标识别-1阶段，这个识别先根据app的用户人数决定，软件开发初期，手动对小地标拍照（重邮），手动做特征工程的提取，最开始先从10分类，20分类，30分类慢慢做起，10分类，即选取重邮10个具有特点的地标，如重邮的新校门，通过对新校门的大量拍照，通过算法提取到特征，同理，对其他的的九个地标做特征提取，最后通过用户对这个地方拍照，识别这是重邮的哪里
- Landmark identification2：地标识别-2阶段，用户上传自己的图片进服务器，上传图片的地标名字到服务器，该名字唯一（即相册以名字妇存取分类）
- pix match : 图像匹配 ,在服务器空间里存储用户的相册，服务器会创建两个一模一样的相册，一个相册以名字存取分类，另一个以特征存取分类
关于匹配，
- music match ————根据服务器存储的music id名字进行匹配
- movie match ————根据服务器存储的moive id名字进行匹配
- book match ————根据服务器存储的book id名字进行匹配



软件的数据库介绍
=========================

#### (数据库可视化还是用access，最后服务器用mysql存储，这个只是个大概的包含)
![](https://github.com/Zr3Lm9Yh/Distant-similarity/blob/master/img/database.png)


