# BSC链标准代币合约开发教程
- 合约没有权限，支持AVE、DEXTOOL、Go Plus检测全绿
- 合约支持PancakeSwap等所有swap的V2和V3版本
- 合约支持BNB交易对、USDT交易对等所有交易对
- 合约没有税点、黑名单、白名单等功能
- 钱包预留至少0.2BNB

# 视频实战讲解
- https://youtu.be/WMOKl3gFLiw

# BEP20合约
- https://github.com/pandatoolcode/bep20/blob/main/bep20.sol

# 合约编译/开源
```
COMPILER: v0.8.0+commit.e28d00a7.js
Enable optimization: 不开启
Other Settings: default evmVersion, MIT license
```

# 合约部署
```
ENVIRONMENT：Injecte Provider-MetaMask
Gas LIMIT：3000000（默认）
Value：50000000000000000（必须是16个0，不然容易报错导致发布不成功）
CONTRACT：Mytoken（选择这个合约）
Initialsupply：代币数量，需要多少填多少
Name：代币全称（如Ethereum）
Symbol：代币简称（如ETH）全称和简称可以一样
```

# Telegram交流群
- https://t.me/pandatool

# BSC测试链配置
- 网络名称（自定义）：bsc-testnet
- 新增RPC URL：https://data-seed-prebsc-2-s2.binance.org:8545/
- 链ID：97
- 符号（选填）：tBNB
- 测试链浏览器：https://testnet.bscscan.com
- 测试币购买：https://bisell.site/buy/3
