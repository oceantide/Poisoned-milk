
## 更新 04.08.2020

如大家需要使用 JS ，建议大家转移使用 Unzip 版本（简单轻松快乐版）https://github.com/limbopro/Profiles/blob/master/limbopro/Gift/Without/unzip/README.MD 

---

# 预配置文件说明

![img](https://raw.githubusercontent.com/limbopro/Profiles/master/limbopro/Gift/QuantumultX4limbopro.conf.PNG)

0. [点此](https://t.me/limboprossr/924)查看 QuantumultX策略图标效果预览

1. 本预配置文件，相当于提前为QuantumultX`预设策略`（8个策略）及其`策略图标`，`去广告规则`，`主流站点`分流规则，以及无需拔卡看，`Tiktok`，解锁`VSCO`会员；务必遵循教程步骤前后顺序，以确保其可用性；

2. 如需解锁Tiktok，但不想使用预配置文件：可单独参考设置：[iOS 使用 Surge/Quantumult/Shadowrocket /QuantumultX 解锁 TikTok 区域限制（免拔卡）10.10.2019](https://limbopro.xyz/archives/3629.html)  ；

以下为教程详细步骤：

## 1.备份你的机场订阅链接
0. **针对有多个机场订阅链接的小伙伴，这会是一个快捷备份方法**
1. 进入`QuantumultX`，点击右下角`三菱`按钮；
2. 找到`配置文件`模块下`编辑`，点击；
3. 找到`[server-remote]`，下方就是你已经配置好的机场`订阅链接`；
4. 复制，粘贴到某处，留作备用（不然等下又要一个个添加（如果持有机场多的话））；
5. 如果你只订阅了一个机场，进入`QuantumultX`，点击右下角`三菱`按钮，找到`节点`模块，`引用（订阅）`处复制；


## 2.下载预设配置文件
0. 复制`https://raw.githubusercontent.com/limbopro/Profiles/master/limbopro/Gift/Without/QuantumultX4limbopro.conf`预配置文件链接；
1. 进入`QuantumultX`，点击右下角`三菱`按钮；
2. 找到`配置文件`模块下的`下载`，点击；
3. 粘贴刚刚复制的配置链接，点击右上角`确定`按钮；
4. 保存完毕，回到`QuantumultX`主界面，就可以看到配置好的8个`策略`图标了；

## 3.配置你的节点，删除红色感叹号标注的节点（如有）
*操作步骤务必遵循先后顺序*

0. 订阅你的节点；
1. 复制之前备份的机场`订阅链接`粘贴到`[server-remote]`后或点击从`节点`模块>`订阅/引用`处添加订阅链接；
2. 务必`删除`策略图标下`被三角红色感叹号标注`的`节点`，并`配置自己的节点`；否则将会出现错误提示如“未知策略或节点`无用节点1`<-`负载均衡`”，其中`负载均衡`为`策略`名字，`无用节点1`为该策略下不可用的节点，需要长按相应`策略`图标并删除，并配置自己有效节点即可；
