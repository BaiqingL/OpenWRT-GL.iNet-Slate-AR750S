# OpenWRT GL.iNet AR750S (Slate)
![Alt text](Screenshot.png)

OpenWRT 源码: https://github.com/coolsnowwolf/lede

专门为GL.iNet AR750S (Slate) 迷你路由器编译的OpenWRT，带有特殊插件支持。

## 支持功能 (Supported Features)：
* Argon主题
* 中文 + 英文语言版本
* Dropbear SSH 控制
* SSR (SSR Plus+)
* V2Ray (SSR Plus+)
* Trojan (SSR Plus+)
* BBR (Turbo ACC 网络加速)
* 挡广告 (AdByBy Plus+)
* 解锁网易歌曲 (Unblock NetEase Music)
* 百度云网盘解锁 (BaiduPCS Web)
* Office / Windows 激活 (KMS 服务器)

### 安装步骤：
1. 将路由器电源切断，重连之前按下重置键，接通电源后等5G灯光闪烁5次后松开。
2. 访问192.168.1.1，选择在这里下载的`base.img`镜像上传，点击Update，耐心等待镜像上传。
3. 等待到路由器的三个灯光亮起为止。
4. 进入路由器网段控制板。
5. 使用`update.bin`文件来刷入完整插件集合。
6. 等待固件刷入完成。

#### 默认用户：
用户名： `root`

密码： `password`
