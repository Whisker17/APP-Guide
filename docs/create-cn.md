# 创建市场

作为一个 Permissionless 的预测市场 APP ，我们支持用户自己创建市场并注入流动性。

1. 点击左边 `Create Market`

   <img src="https://raw.githubusercontent.com/Whisker17/ImageStoreService/main/image-20211019110305148.png" style="zoom:67%;" />

2. 填写具体信息，需要注意的点包括：

   - `Market ends` 时间是该市场关闭时间，在市场关闭后，需要 `Oracle` 提交结果
   - `Outcomes` 中的 `Ticker` 指的是你的结果代币的名称，自己定义，例如 `ABCYES` 和 `ABCNO` 
   - `Oracle` 这一栏填写的是最终通报结果的人的地址，可以是非创建市场的人，但是还是推荐写自己的地址
   - 如果最终 `Oracle` 没能通报结果，您将会失去一部分质押的 token
   - 可以选择市场的属性：`Permissionless` 或者 `Advised`，`Advised` 的市场需要通过我们的审核才能生效，同时，这样的市场所需要的质押金额也会比较少

<img src="https://raw.githubusercontent.com/Whisker17/ImageStoreService/main/image-20211019113534808.png" style="zoom:80%;" />

3. 关于最后一条 `Depoly Liquidity Pool`，所有创建市场的参与者都需要为自己的市场注入流动性，即至少 100 枚各个结果代币以及 100 ZBS。

   <img src="https://raw.githubusercontent.com/Whisker17/ImageStoreService/main/image-20211019115334514.png" style="zoom:80%;" />

**Tips**

目前大家都没有这么多的 ZBS 来提供流动性，所以在 BetaNet 测试网活动中，大家可以在 Discord 群中联系团队成员以寻求团队帮忙注入流动性。所以推荐大家在上面的 `Depoly Liquidity Pool` 中选择 `OFF`

4. 完成以上步骤后签署交易即可完成创建市场