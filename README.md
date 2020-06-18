# M3U8-Downloader
HLS Downloader，一个Electron App，可以下载、播放HLS视频流。

![HLSDownload Show](https://github.com/HeiSir2014/M3U8-Downloader/blob/master/resource/HLSDownloadShow-2.gif?raw=true)

# 官网
[M3U8-Downloader 官网](https://tools.heisir.cn/HLSDownload)

QQ交流群：341972319

[点我加QQ交流群](https://jq.qq.com/?_wv=1027&k=nhFrZBS0)

# 获取视频流地址
在chrome浏览器打开视频网页，按下F12,页签点击到Network页面，在Filter框里输入"m3u8",然后按F5刷新页面，如果网页里的视频使用的是HLS源，就可以在这里捕获到视频流地址，然后选中右键 Copy -> Copy Link Address.
提供m3u8源地址，下载并无损转码Mp4文件

# Windows下载
目前仅编译了Windows Release. 

下载地址：[Release](https://github.com/HeiSir2014/M3U8-Downloader/releases)

# 运行源码
### 1.NodeJS开发环境搭建

安装NodeJs最新版，[NodeJs Download](http://nodejs.cn/download/)

### 2.Clone 代码

在任意文件夹下新建一个文件夹存放代码，并执行以下命令
```
cd newdir

git clone https://github.com/HeiSir2014/M3U8-Downloader.git .
```

### 3.环境初始化

```
npm install
```

### 4.运行M3U8-Downloader

```
npm run start2
```

### 5.Enjoy it