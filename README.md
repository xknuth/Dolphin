# Dolphin白皮书
## 概述
### 什么是Dolphin
Dolphin是基于区块链技术的聊天网络。有别于传统IM，Dolphin利用区块链技术实现了基于Dolpin网络的IM的互联互通。而Dolphin本身是一个去中心化网络，存在在Dolphin网络里面的好友关系和用户数据，永远属于用户，用户可以授权给任何服务使用，并通过Dolphin保证IM的互联互通。
我们不需要在担心切换IM客户端，会让好友失联，我们也有权利用我们的自己的数据，得到我们想要的体验。

### Dolpin构建的社交网络
#### 对于个人数据的尊重
个人数据，无论好友关系还是文件、照片等，所有权永远属于个人，任何服务的提供方在未经授权的下无法查看。这个由区块链的智能合约的隐私保护技术保证。而且，通过去中心化的网络，这些数据不属于任何运营商，也不存在丢失的可能。
第三方应用无法在分析用户数据，从而得到我们的习惯，做精准营销，这让我们的生活更加安全可靠。
#### 对于个人使用习惯的尊重
现在社交网络是割裂的，我们用了钉钉就无法跟微信交流。我们希望Dolpin所构建的通讯网络里面，所有的IM能够实现互联互通，就像IPhone能给HUAWEI Mate20打电话一样，用户有权选择通讯的终端程序和体验，我们不应该被微信所绑架。
#### 对于细分场景的支持
我们在任何细分场合，无论是淘宝购物还是小红书看网红，我们都能通过Dophin理解世界，我们不在频繁切换IM聊天工具，因为通讯是一个基础能力，被所有App所支持。

### Dolpin的特点
它是一个标准化的通讯区块链网络，区块链的智能合约机制保证了Dolpin承诺的，1）数据还给个人；2）标准化互联互通网络；
它提供了标准通讯协议，兼容XMPP，允许任意遵循协议的IM接入，并在用户授权的前提下使用数据

## Dolphin网络
### 用户系统
#### 账户系统
我们采用逻辑账号系统，并记录对应的公钥，持有公钥的私钥才能操作用户账号和数据。如果私钥丢失，我们通过社区治理手段可以找回。
#### 用户数据
在整个区块链网络里面，核心存储两份数据
1、账号在哪里登录
2、账号对应的好友数据
在网络存储的两份数据，都通过公钥做非对称加密，只有持有私钥方能解开
### IM运营商
IM运营商定义：想介入Dolphin网络的IM服务提供方。我们为这些服务提供方提供四套标准解决方案Client、Server、GateWay、dolphin-BlockChain
#### client
连接网络的客户端SDK
#### gateway
#### dolphin-Blockchain
### 网络激励

### Dolphin运营计划
