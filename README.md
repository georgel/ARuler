<p align="center">
  <img src="./Design/logo.png" width="100%"/>
</p>

# ARuler
Mesure distance using apple ARKit

## 预览
  <img src="./Design/preview.gif" width="320"/>
  
## 安装
因为ARKit使用限制，设备要求为6s以上，系统最低要求为iOS11

测量时需保证光线充足

## 问题
<del>ARKit目前只能识别水平的平面，所以只能测量水平面的长度，不能测量垂直平面上的长度，不知道视频里的是怎么实现的，有知道的小伙伴可以一起交流一下</del>
去除了识别平面后才进行测量的逻辑，采用最近的特征点，可以测量垂直的物体啦

## 参考
看到微博上[AR虚拟尺子视频](https://m.weibo.cn/1652421612/4122791333240092)，就想试着模仿着实现一下

部分代码来自[苹果ARKitDemo](https://developer.apple.com/sample-code/wwdc/2017/PlacingObjects.zip)

## 建议
有任何建议或问题请提issue

## 开源协议
ARuler开源在 GPL 协议下，详细请查看 LICENSE 文件


