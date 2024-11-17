# Blockchain Address Viewer - PopClip Extension

一个用于快速查看区块链地址信息的 PopClip 扩展。支持 EVM 和 Solana 地址在gmgn中的快速查看，并提供 Debank 快捷访问。

## 功能

- 支持 EVM 地址（以太坊等）和 Solana 地址的识别
- 提供三个快捷按钮：
  - Token：查看代币持仓信息
  - Wallet：查看钱包地址详情
  - Debank：直接跳转到 Debank 查看 EVM 地址信息（仅支持 EVM 地址）

## 支持的地址格式

- EVM 地址：以 "0x" 开头的 40 位十六进制字符（例如：`0x1234...abcd`）
- Solana 地址：32-44 位的 Base58 字符（例如：`6atDedbXPX1qvb5fEjKpw8Seyow21ox3LXrRXaCvpump`）

## 安装方法

1. 下载 `BlockchainAddressViewer.popclipext` 文件夹
2. 双击该文件夹安装扩展
3. 在 PopClip 的扩展管理中确认启用该扩展

## 使用方法

1. 选中任意区块链地址
2. PopClip 菜单会显示相应按钮：
   - Token：查看代币信息
   - Wallet：查看钱包信息
   - Debank：查看 Debank 信息（仅 EVM 地址显示）

## 跳转链接

### EVM 地址
- Token 页面：`https://gmgn.ai/eth/token/<address>`
- Wallet 页面：`https://gmgn.ai/eth/address/<address>`
- Debank 页面：`https://debank.com/profile/<address>`

### Solana 地址
- Token 页面：`https://gmgn.ai/sol/token/<address>`
- Wallet 页面：`https://gmgn.ai/sol/address/<address>`

## 开发信息

- 扩展标识符：`blockchain.address.viewer`
- 开发框架：PopClip Extension
- 配置文件：`config.json`

## 许可证

MIT License

## 贡献

欢迎提交 Issues 和 Pull Requests 来改进这个扩展。

## 更新日志

### v1.0.0
- 初始版本发布
- 支持 EVM 和 Solana 地址识别
- 提供 Token 和 Wallet 查看功能
- 添加 Debank 快捷访问（仅 EVM 地址） 