# 区块链

分布式存储某段时间内所有数据运动过程的集合，然后把每一段时间连接起来，就是一个完整的区块链

## 概念

### 信任体系

传统的信任体系：熟人信任-第三方担保-区块链

人是有情感的，可以破坏合约。区块链是物质的，客观的，程序的，基于算法的，所以区块链可以解决旧信任体系的问题

## 区块

某段时间内，所有账户改变指令的集合，对数据运动过程的记录

每个区块头含有一个哈希值，如果这个值确认正确，才可以继续写入

### 哈希算法

将原始数据经过哈希算法，可以得到一个固定长度的哈希码，如果原始数据改变，重新获得的哈希码就会不一样。哈希码不能反译成原始数据，所以哈希码的作用是对数据完整性的校验（数据认证）

## 共识

谁来记账？矿工，挖矿能产生区块，奖励机制同时是发币机制，挖矿同时能获得一定的交易手续费

* 工作量证明（PoW）

* 权益证明

* 股份授权证明

* PooI验证池

* 实用拜占庭 PBFT

## 分布式账本

去中心化，分布式存储数据

### P2P

### IPFS

## 加密

### 密码

* 密文

    信息，通过算法将明文加密成不可读的暗文

* 密钥

    钥匙，开启装有明文的箱子的锁的身份认证（口令），例如压缩包加密

### 对称加密

加密解密使用同一把钥匙

### 非对称加密

* 公钥加密，私钥解密（解决密钥分发问题）

    公钥加密，只能由对应的私钥解密。所以解密的私钥不需要被加密的人知道，只需要将公钥给加密的人知道

* 私钥加密，公钥解密（解决身份认证问题，数字签名）

    私钥加密，只能有对应的公钥解密。所以如果使用你的公钥能解密，就说明加密的人一定是你，身份唯一。

## 智能合约

## 应用

### 比特币

#### 历史

* 2008.11

    中本聪发布比特币白皮书

* 2009.1

    中本聪挖出第一个区块，获得50个比特币，向其他人转账10个比特币

* 2010.5

    有人花1万比特币买了2个披萨

* 2010.7

    东京出现第一个比特币交易所

* 2011.2

    1比特币=1美元

* 2017.12

    1比特币=2万美元

### 账本，数字货币，身份认证，版权，捐款，博彩，选举

## 参考

> [mooc-陆军工程大学](https://www.icourse163.org/course/PAEU-1003640007)

## 思考

基于溯源，应用版权，构建知识网，学习是创造个人价值，分享是创造社会价值，盈利点，数字货币交易佣金，广告
学习知识，满足自己的求知欲，使自己快乐，就是创造个人价值
分享知识，满足他人的求知欲，使他人快乐，就是创造社会价值

基于不可篡改，应用博彩，十次一开彩，百次，千次，万次，十万，百万

账户改变指令