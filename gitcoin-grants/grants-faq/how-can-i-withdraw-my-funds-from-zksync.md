# 我如何从 zksync 取款?

如果您的地址是一个账户，请前往 [http://wallet.zksync.io/](http://wallet.zksync.io) 使用浏览器钱包进行取款。

如果不是账户而是合约，请阅读以下内容：

如果您的合约可以执行任意交易，您可以给 Matter Labs 发邮件（hello@matter-labs.io），或者去到他们的 [Discord](https://discord.gg/px2aR7w)，询问将其连接到 zkSync 最佳方式（假设您不能从 [https://wallet.zksync.io/](https://wallet.zksync.io) 进行链接）。

另外，如果您只是想提取资金到 L1，最简单的方法是使用他们的 npm 包，它可以让任何没有和 zkSync 账户交互过的地址强制推送资金到 L1。

您可以按以下来操作：

```
npm install -g zksync-force-exit-cli
zksync-force-exit -k <privateKeyOfAddressToSendTxFrom> -a 
<addressToWithdrawZkSyncFundsFrom> -t <tokenSymbol> -n mainnet
```
