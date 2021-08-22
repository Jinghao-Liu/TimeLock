<p align="center"><a href="https://github.com/Jinghao-Liu/TimeLock"><img width="200" src="https://github.com/Jinghao-Liu/TimeLock/blob/main/images/lock.png" alt="TimeLock logo"></a></p>

<p align="center">
  <a href="https://github.com/Jinghao-Liu/TimeLock/releases/"><img src="https://img.shields.io/github/release/Jinghao-Liu/TimeLock" alt="Release version"></a>
  <a href="https://github.com/Jinghao-Liu/TimeLock/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-red.svg?style=flat-square" alt="License"></a>
 </p> 
 
<h2 align="center">TimeLock 时间锁（For Windows）</h2>
 
TimeLock 时间锁是一款可以让您时刻保持专注的软件，您可以通过有限时间的解锁减少使用计算机或特定应用程序的时间。

## 下载和安装

- [ 最新版下载地址](https://github.com/Jinghao-Liu/TimeLock/releases/download/1.1.2/TimeLocksetup1.1.3.exe)
- [ 备用地址（密码:8rlg）](https://wws.lanzoui.com/b01zuv93a)
- [ 历史版本地址](https://github.com/Jinghao-Liu/TimeLock/releases/)

## 使用说明

### 环境要求

- Windows操作系统
- [ .NET 4.0](https://www.microsoft.com/zh-cn/download/details.aspx?id=17718)

### 主要功能
### TimeLock 时间锁包含强时间锁管理、弱时间锁管理两种模式
+ #### 强时间锁管理
TimeLock 时间锁处于『强时间锁管理』模式时，将会强制置于页面顶层，您无法操控鼠标运行任何程序，除非解锁。

![avatar](https://github.com/Jinghao-Liu/TimeLock/blob/main/images/strong.gif)

+ #### 弱时间锁管理
TimeLock 时间锁处于『弱时间锁管理』模式时，只有您选择加入『限额列表』的程序会被监管，其他程序不受影响。第一次使用时，您需要在『设置』中选择『弱时间锁管理』模式，并在『限额列表』中添加需要监管的程序，重新启动TimeLock即可开启弱时间锁管理模式。弱时间锁管理模式下TimeLock主界面会一直隐藏，除非您运行了被监管软件触发了监管模式，同时您可以在托盘中找到TimeLock图标打开『设置』窗口。

![avatar](https://github.com/Jinghao-Liu/TimeLock/blob/main/images/weak.gif)

※为实时监听打开程序动作，TimeLock在弱时间锁管理模式下使用了消息钩子技术(hook)，这可能会影响您系统的稳定运行。
### 其他功能
+ ####  背景透明度
您可根据需要在设置中调节主界面背景透明度。
+ ####  开机自启动
您可以设置开机自启动，这需要系统管理员权限控制器（UAC）支持。
+ ####  自动更新背景壁纸
您可以选择是否使用动态背景，开启动态背景TimeLock 时间锁在每次启动时都会更新背景图片，如果您不满意壁纸库风格，可以在设置中取消勾选动态背景并自行替换`/image/background.png`
### 联系
TimeLock 时间锁依然存在一些潜在的错误，如果您发现了bug或有任何建议可以issue留言或发送[邮件](mailto:jinghaoliu@Hotmail.com)给我。TimeLock 时间锁遵循MIT协议，我会在近期发布完整的代码。

灵感来自**请叫我何同学**——“[这视频能让你戒手机](https://www.bilibili.com/video/BV1ev411x7en)”。
