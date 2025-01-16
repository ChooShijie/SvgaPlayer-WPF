
 # SvgaPlayer-WPF


#### 介绍
Wpf版本的SVGA[https://svga.dev/integrated.html] 特效文件播放器

#### 软件架构
根据svga官网文档[https://svga.dev/integrated.html] 以及 github[https://github.com/svga] ，采用C#+WPF开发。<br />
实现Windows端的SVGA文件播放

#### 提示
需要WPF源码可Wx联系我<br />
Avalonia 版本已经研发出来，经测试Windows、MacOS、Web、Andorid、IOS均可使用<br />

腾讯Vap [https://github.com/Tencent/vap] 动画特效融合解码也有WPF版本。跨平台还在研发中

 
#### 支持本仓库
轻点 GitHub Star，让更多人看到该项目。

#### 使用说明

1.下载AnimationPlay.dll就可以直接使用<br />
2.项目引用AnimationPlay.dll<br />
3.
```c#
 using AnimationPlay.Special;
 AnimationPlayerControl svga = new AnimationPlayerControl();
 svga.SourceUri = "pack://application:,,,/wpfapp1;Component/333333333333333.svga";
```

#### 感谢或联系作者

![13ac0ef060d2116254952f5ad5ac207](https://github.com/user-attachments/assets/798b819a-8757-4a27-ada1-3d72be5e89d7)



