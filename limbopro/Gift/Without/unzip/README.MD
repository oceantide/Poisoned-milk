## 更新说明 
### 04.10.2020
0. 教程 **第一步** 中增加了使用 **workingcopy** 克隆GitHub仓库到手机📱本地的方法；
### 04.09.2020
1. 本次更新已精简 [Rewrite_local] 配置，并引用了 unzip适配版的 Js.conf
2. 请重复一次教程 **第二步** 的操作，并重新配置证书📄；
3. 然后进入 QuantumultX ，点击右下角 [三菱按钮] - [重写] - [引用] - 点击 [unzip适配版] 更新 
4. 未来只需执行 该操作以及 重复 **教程第一步** 即可（届时会有更新说明），无须再重新配置证书📄；

---

## 正文部分


![Quantumult x for limbopro][1]

## 毒奶预配置文件（unzip版）说明

0. 利用 Quantumult X 自带的 [配置文件] - [下载] 功能对 Quantumult X 各个模块即参数进行预配置；
1. 利用 NobyDa 贡献的脚本解锁🔓各项事务，VSCO，Termius，网易蜗牛读书会员等；
2. 另外默认配置的是 🔓 美区App Store下载的 Tiktok；届时自己进 [QuantumultX] - [配置文件] - [编辑] - 找到 Tiktok 修改参数即可 
3. Surge/Clash 用户可以使用由毒奶提供的 订阅转换 API，亦能获得相同的效果；https://limbopro.xyz/archives/subconverter.html

## 本预配置文件所引用到的仓库
0. 在此毒奶对大家的付出表示感谢
1. [NobyDa](https://github.com/NobyDa/Script/tree/master) 脚本仓库
2. [ConnersHua](https://github.com/ConnersHua/Profiles/tree/master) 神机规则
3. [limbopro](https://github.com/limbopro/Profiles/tree/master/limbopro) 机场专线
4. [Qure](https://github.com/Koolson/Qure/tree/master/IconSet) 开源图标

## 关于策略及分流的说明
- **故障切换**：该策略组自动检测组内节点可用情况（surge 会切换选中最低延迟节点）；
- **机场专线**：主流机场域名分流规则，例如 N3RO ，你可使其请求走代理，直连等；
- **社交媒体**：国外社交媒体，如Twitter/Facebook/Instagram等，**流量消耗小，但需要稳定**；
- **苹果服务**：苹果服务相关分流规则；
- **Netflix**：鉴于大家喜欢看 Netflix；
- **其他国外流媒体**：如油管，P站等一切你可以想得到国外流媒体，**流量消耗大**；
- **广告拦截**：默认选择 `Reject`，广告拦截可能会造成某些错误🙅，届时 将 **广告拦截** 的 **策略偏好** 修改为 PROXY 或 Direct 即可；
- **Final**： 排除以上已知的分流规则的其他未知；

* GEOIP,CN,DIRECT，默认中国大陆网站均走直连；

## 具体操作
💡 完整视频对照操作教程请参阅：https://t.me/limboprossr/1702 ；
或参阅 YouTube https://www.youtube.com/watch?v=4Sy0HUcOvYk&loop=0 （该视频教程不包含生成证书与信任证书📚）

### 第一步 ⏬ 下载 脚本仓库压缩包
0. 第一步 ⏬ 建议尽量使用 [WorkingCopy](https://limbopro.xyz/archives/workingcopy.html) 替代，以方便以后更新（只需在在 WorkingCopy 内下拉即可更新）；如不想使用 WorkingCopy ，继续看下文；

1. https://github.com/NobyDa/Script/archive/master.zip
2. 复制上述并在 Safari 打开下载，打开下载的文件
3. 下载成功后，进入 [文件]App - [我的iPhone] - [下载项] 找到  Script-master.zip 并解压
4. 进入解压后的 文件夹 [Script-master]
5. 右上角 点击 [选择] - [全选]
6. 点击底部 中间类似 文件夹的按钮 📂 （移动）
7. 选择 [我的iPhone] - [Quantumult X] - [Scripts]
8. 点击 右上角 的 [移动] 按钮
9. 完成

### 第二步 ⏬ 下载 毒奶自用预配置文件（unzip版）

1. 复制 https://raw.githubusercontent.com/limbopro/Profiles/master/limbopro/Gift/Without/unzip/QuantumultX4limbopro.conf 预配置文件链接；
2. 进入 QuantumultX ，点击右下角 [三菱按钮]
3. 找到 [配置文件] 模块下的 [下载] 点击
4. 粘贴 刚刚复制的配置 [链接]，点击 右上角 [确定] 按钮
5. 确认，届时 QuantumultX 已添加 8个策略

### 第三步 生成并配置证书
1. 进入 QuantumultX ，点击右下角 [三菱按钮]
2. 找到 [MitM] 模块 - 生成并配置证书📄 

- 进入QuantumultX，点击页面右下角三菱`按钮`，找到`MinM`模块，点击`生成证书`，提示生成成功，点击`安装证书`此时会跳转至` Safari`，提示`此网站...下载一个配置描述文件。您要允许吗？`，点击`允许`，网页提示`已下载描述文件`；
- 进入 iOS 系统`设置`-` 通用`-`描述文件`-`已下载的描述文件`-选中，并安装，输入密码...完成描述文件安装；
- 进入 iOS 系统`设置`-` 通用`-`关于本机`-`证书信任设置`-`针对根证书启用完全信任`-选中刚刚安装的并启用即可；

3. 找到 [重写] 模块 - 开启按钮 🔘
4. 找到 [MitM] 模块 - 开启按钮 🔘

## Faq 
### 备份你的机场订阅链接🔗
1. 进入 QuantumultX ，点击右下角 [三菱按钮]
2. 找到 [配置文件] 模块 - 点击 [编辑] - 找到 [server_remote] 
3. 复制 [server_remote] 下方的机场订阅链接🔗 存到某处备用
4. 届时 恢复时 重新再 [server_remote] 下方 粘贴即可

### 使用毒奶预配置文件后的一些检查
1. 如果出现错误提示，不要慌
2. 进入 QuantumultX 主界面 - 各个图标点一下 看一下
3. 熟悉一下

## 已知存在问题及解决办法
### 使用 unzip 版预配置文件后，微博开屏广告没有去掉
**A 两个方面**

1. 确保 Quantumult X 已安装证书📄并且信任
2. 进入 QuantumultX ，点击右下角 [三菱按钮] - 找到 [配置文件] 模块 - 点击 [编辑] - 找到 [rewrite_local] 下  `去微博应用内广告 (By yichahucha)` 被 # 号 注释的那行，删除 # 号即可；

```
#^https?://(sdk|wb)app\.uve\.weibo\.com(/interface/sdk/sdkad.php|/wbapplua/wbpullad.lua) url script-response-body QuantumultX/File/wb_launch.js
```

### Tiktok 如何换区
0. Tiktok 老是推荐美国🇺🇸用户上传的视频？换下国别代码即可；


1. 进入 QuantumultX ，点击右下角 [三菱按钮] - 找到 [配置文件] 模块 - 点击 [编辑] - 找到 [rewrite_local] 下 关于 Tiktok 部分，将 US 换成 其他国别代码即可； 国别代码参考：https://limbopro.xyz/usr/uploads/2019/10/3740990267.png

```
(?<=(carrier|sys)_region=)CN url 307 US
```

2. 换成 JP；看看日本🇯🇵妞；
2. 另外，不是换了就马上就切换到日区的，多刷几个视频就有日区用户推荐了；

### 野比去广告测试版引发的问题
1. 目前已知会导致 QQ 定位不能正常发起
2. 使用 [抖音去水印下载ios捷径](https://limbopro.xyz/archives/1560.html#h-44) 下载抖音视频时会出现断连；
3. 已默认禁用；可进入 Quantumult x，[分流] - [引用] 中 找到，并右滑开启/禁用；

## 最后 BTW
因为这个配置文件也是我自用的，会保持更新，但一般无太大问题不建议大家每次跟随更新。

### 进阶玩法
https://limbopro.xyz/archives/3846.html

### 关注频道
https://t.me/limboprossr

[1]: https://raw.githubusercontent.com/limbopro/Profiles/master/limbopro/Gift/Without/unzip/Quantumult%20X%20for%20limbopro.jpg
