# QPlayer2



Qplayer2是一款跨平台的播放器SDK,除了基础的播放器能力外，更致力于各种应用场景的对接。

### 支持的平台

 Platform | Build Status
 -------- | ------------
 Android | https://github.com/pili-engineering/QPlayer2-Android 
 IOS | 正式版已发布 
 Windows | 敬请期待 
 Mac | 敬请期待 
### qplayer2-core 功能列表

| 能力                  | 亮点                                                         | 备注                             |
| --------------------- | ------------------------------------------------------------ | -------------------------------- |
| 媒体资源组成形式      | 一个媒体资源支持多url，比如一个音频url和一个视频url组成一个媒体资源,提升拉流速度和解封装速度 |                                  |
| 播放协议及视频类型    | http/https/srt/rtmp flv/m3u8/mp4/flac/wav(PCM_S24LE)         | 新增协议和视频类型请联系技术支持 |
| 解码                  | 软解/硬解/自动解码                                           |                                  |
| 色盲模式              | 能在业务场景中更好的服务视觉有障碍的客户                     |                                  |
| 倍速                  | 变速不变调                                                   |                                  |
| 清晰度切换            | 通用清晰度切换方案，无缝切换，即使媒体资源gop不对齐          |                                  |
| seek                  | 支持精准/关键帧 seek 两种方式                                |                                  |
| 指定起播位置          | 从指定位置开始播放                                           |                                  |
| 起播方式              | 起播播放/起播暂停 设置起播暂停时，起播后首帧渲染出来就停止画面 |                                  |
| SEI数据回调           | 所有解码方式都支持                                           |                                  |
| 纯音频播放/纯视频播放 | 播放只有单音频流或者只有单视频流的视频                       |                                  |
| APM埋点上报           | 用于整体大盘的性能监测                                       |                                  |
| VR视频                | 支持Equirect-Angular类型的vr视频播放                         |                                  |
| 后台播放              | 支持设置是否开启后台播放                                     |                                  |



### 



### iOS

##### 引入依赖

```groovy
pod 'qplayer2-core'
```



##### 鉴权

如需使用该套sdk到其他工程中，请联系我们的技术支持开通帐号。



##### API文档

请查阅document目录下的api文档



##### Demo介绍

1. demo工程内的 长视频播放页 是基于 qplayer2-core来实现的
3. 体验demo下载：http://fir.qnsdk.com/bfzl?release_id=630d7e1af945486a377cb045



#### 技术支持与交流

产品及服务咨询：400-808-9176

问题反馈：如有问题请提交issue

