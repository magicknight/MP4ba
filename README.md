# MP4ba
> 一个自动搜索并下载MP4ba站点上种子的工具

实测过，掏空100多页的种子大概需要两三个小时，总共400多兆的种子啊，够看很久很久的了（有空补截图）

PS：
1. MP4ba是一个良心的网站，没有辣么多繁琐的注册流程，没有满屏的小广告，下载简单直接粗暴，现在我想做的就是让这个过程变的更加的简单粗暴
2. 前段时间，MP4ba似乎发现我在爬种子的劣迹，服务器总是重置我的链接，所以在最新的代码里面我加了一些重试的机制，可以算暂时解决了这个问题，但是下载速度受到了一些影响

##依赖库：
1. 本脚本使用python2.7开发
2. 请下载python第三方库requests 

##使用方式：
###Windows端：
1. 修改demo.py中 循环的起始和末端值，运行即可
2. 起始和末端的值代表mp4ba主页上的页。1，9 即第一页到第9页

##建议使用方式：
1. 使用jenkins或windows计划任务每天扒第一页的种子，这样速度会很快，片源也会比较新
2. 如果想体验一下掏空MP4ba的感觉，可以找一个夜黑风高的深夜，一次行爬完所有页面，整个过程大概耗时2，3个小时吧，MP4ba的资源实在太丰富了

> 最后深深的感谢制作MP4ba的开发者们，分享无价，珍惜版权意识，遇到自己真正喜欢的电影还是去影院支持一下吧
