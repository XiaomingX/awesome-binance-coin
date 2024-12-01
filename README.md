# awesome-coins

加密货币使用了多种算法。本文将介绍不同加密货币所使用的算法，并提供一些管理虚拟货币的实用工具和服务。

## 了解加密货币之前的一些基本概念

加密货币中的“币”可能对不了解算法和数据结构的人来说有些混乱。让我为你简单解释一下：

加密货币有很多种，被称为[“币”](http://coinbin.org/coins)。人们像交易股票或集换卡一样喜欢[交易](https://www.cryptopia.co.nz/Register?referrer=kennethreitz)这些币；他们也[挖矿](https://www.nicehash.com/?refby=386829)，使用家用电脑或专业硬件进行矿产开采。

这些币通常保存在“钱包”中，钱包可以是在线的、本地存储的，或者纸质钱包。

由于单独挖矿非常困难，并且类似赌博，因此大多数人选择加入“矿池”（通常使用`stratum`协议进行协调），在这些矿池中，即便没有找到新块，你也能因参与贡献而获得奖励。通过矿池，参与者集体努力，成功找到区块后，按照矿池的规则分配奖励。

此外，有些人选择[租用算力](https://www.nicehash.com/?refby=386829)，即租用大型矿场的算力，要么尝试独立挖矿，要么将算力指向矿池，类似家庭矿工，但算力更强大，当然需要支付更多费用。

希望这些解释能帮助你理解加密货币的基本概念。

## 加密货币市场工具与服务

- **[Coinbin.org](http://coinbin.org)** — 提供人性化API，快速获取加密货币数据（汇率、预测等）
    * [所有已知的币种](http://coinbin.org/coins)
    * [比特币实时价值](http://coinbin.org/btc)
    * [比特币历史数据](http://coinbin.org/btc/history)
    * [比特币与以太坊汇率](http://coinbin.org/btc/to/eth)
    * 支持所有加密货币。
- **[CoinMarketCap](https://coinmarketcap.com)** — 提供实时的加密货币价格信息。
- **[The Coin Perspective](https://thecoinperspective.com)** — 帮助你比较不同币种的市值、供应量和价格。

## 学习资料

- [加密货币概述](https://github.com/kilimchoi/cryptocurrency) — GitHub上的项目。
- [币种地图](http://mapofcoins.com) — 可视化展示各大加密货币的历史，展示从白皮书到现在的发展过程。
- [比特币开发参考](https://bitcoin.org/en/developer-reference)
- [币安学院](https://www.binance.vision) — 币安提供的开放教育资源。
- [r/CryptoCurrency](https://www.reddit.com/r/CryptoCurrency/) — 加密货币和资产的官方社区。

## 加密货币挖矿池

- **[NiceHash](https://www.nicehash.com/)** — 允许你挖掘任何算法（针对GPU优化），并获得比特币支付。
- **比特币矿池**：[https://pool.bitcoin.com/](https://pool.bitcoin.com/)
- **以太坊矿池**：[https://eth.nanopool.org/](https://eth.nanopool.org/)

## 加密货币钱包

### 托管钱包

**注意：** 加密社区一般不推荐使用托管钱包，因为它们实际上并不让你完全控制你的币——就像银行一样，托管方才是币的真正所有者。

- [Coinbase **比特币**](https://www.coinbase.com/join/516f7e9a929bda3e06000001)
- [MyEtherWallet **以太坊**](https://www.myetherwallet.com/)

### 加密货币银行卡

- [Cryptopay **比特币** 银行卡](https://cryptopay.me/join/03db9c17)

### 纸质钱包

- [**Sia** 纸质钱包](https://siapaperwallet.co)

## 加密货币交易所

- [Binance](https://www.binance.com) — 全球最大的加密货币交易平台。
- [Cryptopia](https://www.cryptopia.co.nz/Register?referrer=kennethreitz) — 提供多种币种的交易，支持法币与加密货币之间的兑换。
- [Shapeshift](https://shapeshift.io/#/coins) — 世界上最快的加密货币交易平台。
- [Bittrex](https://bittrex.com) — 支持多种币种的交易。

## 推荐硬件

- [NVidia GTX 1080 TI OC](http://amzn.to/2wl1c9j) — 市面上最强大的消费级显卡。
- [Asrock H110 Pro BTC+ 挖矿主板](http://amzn.to/2xadkYk) — 支持最多12个GPU的挖矿主板。

## 有趣的区块链项目

- [Bit](https://github.com/ofek/bit) — Python的最快比特币库，支持简单的交易。
- [bcoin](http://bcoin.io) — 用Node.js编写的比特币全节点实现，甚至可以在浏览器中运行。

## 挖矿算法（支持的算法）

- `Scrypt` (莱特币)
- `SHA256` (比特币)
- `Equihash` (Zcash)

更多算法支持见[NiceHash Stratum Proxy](https://www.nicehash.com/?refby=386829)。

为了进一步拓展加密货币的多样性和创新性，这里补充一些新颖的加密货币项目和技术特点：

## 新兴创新加密货币

### 1. **Chia (XCH)**  
- **算法**：Proof of Space and Time  
- **特点**：与传统的Proof of Work（PoW）或Proof of Stake（PoS）不同，Chia采用的是硬盘存储空间的证明，旨在减少能源消耗和提高可持续性。用户通过“耕种”硬盘来获得奖励，而不是像矿工那样使用电力进行高强度计算。

### 2. **Helium (HNT)**  
- **算法**：Proof of Coverage  
- **特点**：Helium创建了一个基于无线网络的分布式网络，通过无线设备提供低功耗无线覆盖，并奖励网络节点HNT代币。它主要用于物联网设备之间的通信，推动了边缘计算的发展。

### 3. **Filecoin (FIL)**  
- **算法**：Proof of Replication and Proof of SpaceTime  
- **特点**：Filecoin是一个去中心化存储网络，允许用户存储和检索数据，矿工通过提供存储空间并验证数据存储的有效性获得FIL代币奖励。它不仅有助于减少对大型数据中心的依赖，还能推动数据去中心化存储的普及。

### 4. **Flow (FLOW)**  
- **算法**：Proof of Stake  
- **特点**：Flow是一个专为去中心化应用和智能合约设计的区块链，其低延迟、高吞吐量的特点使得它特别适合用于游戏、NFT和大规模应用开发。Flow通过将节点分为验证节点、共识节点和执行节点来提高可扩展性。

### 5. **Algorand (ALGO)**  
- **算法**：Pure Proof of Stake (PPoS)  
- **特点**：Algorand通过“纯粹的权益证明”机制，消除了传统PoW和PoS系统中的一些瓶颈，旨在提供更高效和安全的区块链解决方案。它支持即时交易结算，适用于快速支付和高频交易场景。

### 6. **Celo (CELO)**  
- **算法**：Proof of Stake (PoS)  
- **特点**：Celo专注于通过区块链技术实现金融普惠，特别是在发展中国家。它通过使用手机号码作为地址标识，简化了加密货币的使用，提升了用户的接触和使用门槛。

### 7. **The Graph (GRT)**  
- **算法**：Proof of Stake  
- **特点**：The Graph是一个去中心化的数据索引协议，允许开发者使用GraphQL查询在以太坊、IPFS等区块链上存储的数据。其目的是通过去中心化的网络提供高效、透明的搜索和数据索引服务。

### 8. **Zilliqa (ZIL)**  
- **算法**：Sharding + Proof of Stake  
- **特点**：Zilliqa通过分片技术（Sharding）解决了区块链扩展性的问题。它能够实现高吞吐量，适合于大规模应用，尤其是去中心化金融（DeFi）和游戏行业。

### 9. **Ravencoin (RVN)**  
- **算法**：KawPow  
- **特点**：Ravencoin是一个开源项目，旨在让用户能快速、简单地创建和转移资产。它采用了与比特币类似的算法，但特别针对资产创建和发行进行了优化。Ravencoin通过去中心化的方式实现了资产的发行和传输，支持多种不同类型的资产。

### 10. **Bitcoin Cash (BCH)**  
- **算法**：SHA256  
- **特点**：比特币现金是比特币的一个分叉，旨在解决比特币的扩展性问题。通过增加区块大小（从1MB提升到8MB），提高了交易处理能力，适用于日常支付和微支付应用。

---

## 额外的创新性区块链工具与服务

### 1. **Uniswap**  
- **类型**：去中心化交易平台（DEX）  
- **特点**：Uniswap是基于以太坊的去中心化交易平台，允许用户无须通过中介就能直接交换代币。通过自动化市场做市（AMM）机制，Uniswap简化了交易过程。

### 2. **Chainlink**  
- **类型**：去中心化预言机网络  
- **特点**：Chainlink为智能合约提供外部数据源，确保智能合约能够与现实世界进行交互。它是区块链世界中去中心化预言机的重要组成部分。

### 3. **Polkadot**  
- **类型**：多链协议  
- **特点**：Polkadot使得多个不同的区块链能够互操作，并共享信息。这种互联互通的能力为多种区块链应用提供了无限的扩展性。

### 4. **Aave**  
- **类型**：去中心化借贷平台  
- **特点**：Aave是一个去中心化借贷平台，允许用户借入或贷出加密货币，同时支持无担保贷款。Aave通过算法和智能合约降低了中介成本。

这些加密货币和区块链项目代表了区块链技术的多样化创新趋势，并为解决传统系统中的一系列问题（如能源效率、隐私、安全性等）提供了新的解决方案。如果你对某个项目特别感兴趣，或希望进一步了解某种技术的实现，我可以为你提供更多的细节。
