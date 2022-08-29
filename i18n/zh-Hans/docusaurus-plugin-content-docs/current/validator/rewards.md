# 奖励

验证人通过质押一定数量的BTT代币来确保BTTC网络的安全运行，作为激励，验证人也能获得一定的奖励。同时为了BTTC网络的生态发展，任何委托人都可以投票给验证人并获取委托奖励。

如果想要获取奖励，您可以考虑成为验证人或者委托人：

* 如果想要成为验证人，您需要运行一个完整的验证人节点，并质押一定数量的BTT。
* 委托人只需要将BTT代币委托给任意一个验证人。

## 谁能得到奖励？

运行验证者节点的验证人和质押BTT并委托给他们喜欢的验证者的委托人。

验证者可以选择对委托人获得的奖励收取佣金。

属于所有委托人的资金被锁定在部署在 TRON 主网上的合约中，验证人没有权限控制这部分资金。

## 奖励计算

BTTC网络每年的奖励总额是7,041,208,483,000 BTT，其中10%用于激励验证人提交检查点，90%用于激励质押者，根据质押量占全网质押量的比例来分配奖励。

委托人收益计算：
```
年奖励总额*90% *（委托人的委托量 / 全网质押量）
```

验证人年收益计算公式如下：
```
年奖励总额 * 10% / 验证人数量 + 年奖励总额*90% *（验证人的质押量 / 全网质押量）
```
