# QyLamp

> 你好我叫秋雨，请用秋雨唤醒我

## 功能

- [x] 语音识别
- [x] 接入小爱同学
- [ ] WIFI控制
- [ ] MQTT远程控制
- [x] 多种颜色任意切换(红，橙，黄，绿，青，蓝，紫，白，粉)
- [x] 亮度控制
- [x] 音量控制
- [ ] 呼吸模式
- [x] 跑马灯模式
- [x] 爆闪模式(白灯持续闪烁)
- [x] 救援模式(红灯持续闪烁发出SOS救援信号)

## 渲染图

![](img/rendering.png)

## 注意

**Releases**中仅提供esp8266的单机版固件，请自行下载asrpro源码在[天问Block](http://www.twen51.com/new/twen51/index.php)中生成模型并编译上传，如有联网需求请自行下载esp8266源码修改[巴法](https://cloud.bemfa.com/)私钥、主题以及WiFi信息，二次开发请注明我的**GitHub**仓库链接，谢谢合作！

## 更新日志

**2024-11-28**

- 接入[巴法开放平台](https://cloud.bemfa.com/)(可用小爱同学控制开关灯)
- 优化PCB布局、走线，更改扬声器接口底座(1.25mm间距弯针)
- 新增音量控制、亮度调节、跑马灯、爆闪模式、救援模式
- 优化切换颜色时的动画

