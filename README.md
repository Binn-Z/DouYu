# DouYu
抓取斗鱼所有房间带有人脸的预览图并下载
使用redis作为队列，使用了多线程
调用face++的API实现人脸的检测
分为3个模块，抓取图片url、检测图片是否有人脸、对有人脸的图片进行下载
