# 概述


truffle 是世界级的以太坊开发框架

* 内置智能合约编译、连接、开发和二进制管理
* 快速开发的自动化合约测试
* 脚本、可扩展性部署和迁移框架
* 用于部署到任意数量的公网和私网的网络管理
* 为合约通信提供交互式控制台



# 创建空工程

    truffle init

* contracts: 存放合约
* migrations： 存放部署脚本
* test： 测试文件
* truffle-config.js: 配置文件，配置不同网络


# 生成build/contract 编译文件

    truffle compile

执行编译之后，会生成build文件夹，里面会有abi、bytecode、network
