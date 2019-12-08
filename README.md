## 介绍一下你最成功的项目，包括项目目标、技术选型、技术难点以及解决方案。
```
一个小程序项目，项目目标为打造一个集课程预约，课程观看的心里咨询平台。整个项目为独立完成，前端采用小程序和web实现，web端
采用React构造项目，后端为Springboot+Restful进行实现，技术难点跨平台浏览的一致性。以及视频播放流畅问题。web端采用
bootsrap响应式布局解决跨平台问题，视频播放后端使用OSS对象存储服务以及m3u8API对视频进行分割，提高加载速度

```
##HTTP 协议中哪些部分与缓存控制相关。
```
通过响应头进行控制，包括Cache-Control，Expires，Last-Modified，以及cookies
```
##一只青蛙要跳上 n 层高的台阶，一次能跳一级，也可以跳两级，请问这只青蛙有多少种跳上这个 n 层高台阶的方法？
```
n=0 没有方法
n=1 一种方法
n=2 2种方法
n=3 关注于最后一次有两种跳法，一个台阶或两个台阶 故结果为当n=1 和当n=2 时两种之和
......
n n=f(n-1)+f(n-2)
问题本质是一个递归问题
```
