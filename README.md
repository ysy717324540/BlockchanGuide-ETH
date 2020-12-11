<div class="mobile-fixed">

# 区块链入门必读之以太坊钱包知多少
# 前言
回顾加密数字货币数十年的发展历程，比特币（BTC）是一位披荆斩棘的先驱，它宣扬了去中心化思想所代表的公平与正义，开创了去中心化加密数字货币的先河。中本聪的精神和比特币的设计的是伟大的，但可惜的是，由于比特币在拓展性方面的不足，使得比特币网络难以支持更高级、更复杂的应用，区块链的落地价值也难以得到体现。上述这些问题，也可以在钱包的功能方面得到印证——早期的比特币钱包只有资产管理与挖矿这两项功能。

以太坊（ETH）是一个开源的有智能合约功能的公共区块链平台，也是目前生态最为繁荣的公链之一。以太坊的初衷就是为了解决区块链网络的拓展性问题，智能合约的自动执行以及可编辑的特性，契合去中心化的思想，并极大地提升了区块链网络的效率和功能丰富性，自此各种功能的DApp基于以太坊进行开发，以太坊生态蓬勃发展。毫不夸张地说，以太坊为之后的公链发展奠定了方向，公链生态开始崛起。

在这样的背景下，作为以太坊生态中的核心组成部分，钱包的功能自然也不会局限于单一的资金管理与挖矿。随着以太坊上功能性DApp规模的发展壮大，用户可以随时通过ETH钱包与链上进行交互，进行挖矿、游戏、Staking、投票、投资DeFi等操作。ETH钱包作为链上应用的便捷入口，促进了链上生态的的发展，为公链生态带来了活力与繁荣，而生态繁荣与竞争也激励钱包必须保持极高的更新效率和舒适的使用体验，就此形成了一个良性循环。广大想要参与以太坊公链生态的用户，首先就需要了解以太坊基础知识、学习使用以太坊钱包。

<br/><br/>

# 以太坊账号与钱包
## 以太坊账户是什么？
<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605077920628.png)
</center>

在以太坊中，一个账户我们称为 一个地址。依据上图所示，
ETH地址：0xd6755E6Ac74dB436370e8a70f04195F8d6Dd6852
这个地址以0x开头，这个前缀代表这是一个十六进制的数。0x后面跟着40个字符，每个字符的取值范围为0-9及a-f这16个字符其中的一个，分别代表1-16。这是标准的以太坊账户形式。

以太坊有两种账户，分别是外部账户（externally owned accounts），和合约账户（contract accounts）。普通人使用的都是外部账户，它用私钥控制，我们每个人只要持有账户私钥，就可以进行转账、收款、授权等基本操作。合约账户由智能合约的代码控制。外部账户可以触发交易，而合约账户不能主动发起交易，只能在被触发后按预先编写的智能合约代码执行。

在日常钱包使用的过程中，除普通转账外，我们经常会进行对合约账户的授权操作，比如使用Uniswap时，我们授权某个币可以与某个合约账户进行交互。为避免资产的损失，我们需要了解清楚授权的具体范畴。如TokenPocket钱包中为了避免智能合约作恶，增加了approve时可以设置token授权数量的功能。

## 创建以太坊钱包

以太坊是智能合约的开创者，它有较为广泛的共识和社区，当前主流数字钱包基本都支持以太坊公链。用户使用钱包可以很便捷地完成以太坊账户创建。
<center>

![create](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605082288637.png)
</center>

<center>TokenPocket以太坊钱包创建页面</center> 

在 TokenPocket （以下简称TP钱包）中创建以太坊钱包时，首先需要输入钱包名称，该名称主要用于在 TP 中标识区分不同的钱包（在TP钱包中可以创建多个以太坊钱包），所以名称是可以自定义的，转账和导出私钥时需要输入钱包密码，它是对私钥的第二重保护。

创建钱包的过程中，一定要保管好私钥，大多数数字钱包为了降低用户使用门槛，一般都提供助记词，助记词一般都是由12个有序英文单词组成的，通过助记词也是可是导入钱包的。

备份助记词就像备份私钥一样，可以分别抄写在两张纸上然后分地方保管，尽量不要触网，如果一定要在互联网上备份，尽量要处理后再保存，例如插入几个自己熟悉的字母，总之尽量不要将一份完整的助记词保存在互联网上。我们完全不建议用户将私钥、助记词进行网络备份。

## 导入以太坊钱包
如果你已经创建过ETH账号，需要导入新钱包进行资产管理。你可以通过私钥、助记词和 Keystore 这三种方式导入以太坊钱包。

### 1、通过私钥导入以太坊钱包
在使用私钥导入时，需要明文输入私钥或者扫描私钥的二维码，在输入时务必注意大小写。
<center>

![siyao](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605082619100.png)
</center>

### 2、通过助记词导入以太坊钱包
除了使用私钥导入钱包之外，通过助记词导入钱包也是比较常用的导入方式。导入助记词时，要按顺序输入，注意单词之间要用空格进行分隔。
<center>

![zhujici](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605083031845.png)
</center>

### 3、通过 keystore 导入以太坊钱包
在使用 Keystore 导入钱包时，需要复制粘贴 Keystore 文件内容至输入框，然后输入密码，勾选"我已仔细阅读并同意服务及隐私条款"，完成后就可以开始导入了。
<center>

![keystore](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605083081893.png)
</center>

*钱包知识小课堂——来源[《区块链钱包从入门到精通》][1]*

*关于助记词*

由于私钥不方便记忆，因此出现了助记词，助记词只是私钥的另一种展现形式。一般由12或24个英文单词组成，为了方便国内用户，也有提供汉字版本助记词。只要你记住这些单词，按照顺序在钱包中输入，就能恢复钱包并且进行任意操作。如果别人拿到了你的助记词，就相当于拿到了你的私钥，就可以对你的资产进行掌控了。

*关于Keystore*

Keystore=卡号，**Keystore的本质是加密后的私钥，Keystore必须配合你的钱包密码来使用才有效。** Keystore、私钥、助记词是所有钱包通用的，钱包服务商可能会因为产品设计原因，仅为用户提供其中一种或多种方式，但是如果存在同一方式在某钱包无法正常恢复，则该钱包可能存在一定的问题。

*关于密码*

为了进一步增强安全性，大部分钱包会采取密码的方式对私钥做二次加密。每个钱包的加密方法和存储方式是不一样的。这也是为什么你使用钱包进行交易的时候，总需要进行授权，这背后其实涉及了钱包使用密码进行私钥解密，然后再使用私钥对交易进行签名等复杂的过程。

## 如何导出以太坊钱包
对应三种导入方式，我们可以在钱包管理设置中对账号进行助记词、私钥、keystore的导出，导出时需要输入我们创建钱包的密码。

很多新用户经常会因为遗忘自己之前设置的钱包密码，这个时候唯一的办法就是重新导入你的私钥、助记词、或Keystore，设置新的钱包密码。也可以通过助记词和私钥重置密码。去中心化钱包不保存用户的私钥、助记词、Keystore、密码，这在最大程度上保证了用户的资产安全，你的资产由你把握。因此当用户丢失这些信息时，钱包是无法给与任何帮助的，请大家务必保存好！
<center>

![daochu](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605083763867.png)
</center>

其中，私钥是一串字母，而 Keystore 则是由字符组成的文件，在备份 Keystore 时，还可以使用二维码的形式进行备份。
<center>

![key](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605083805127.png)
</center>

## 以太坊GAS
众所周知使用以太坊网络转账并不是免费的，它需要支付一笔费用，即消耗一定的 GAS 费用。手续费的存在是为了给予节点和矿工足够的补偿和激励，同时也为了阻止大量的微量、垃圾交易，用户在进行以太坊上交易时必须支付一定的手续费用，否则将无法完成交易操作。

### 手续费（GAS）是如何计算的

以太坊上的手续费又称为Gas，燃气，即交易中消耗的资源的代名词。通过查看[以太坊浏览器][2]上面显示的交易记录，你会看到Gas Limit、Gas Used by Transaction和Gas Price，即与手续费相关的专用名词。Gas Limit、Gas Used by Transaction和Gas Price则分别为这笔交易中可消耗资源量的最大值、实际消耗资源量以及资源的单价。

Gas Limit代表了交易可以使用的资源上限，是为了防止合约漏洞或者恶意程序导致用户Gas量消耗过高的情况出现。一旦消耗的Gas量超过Gas Limit，矿工就会停止执行程序，做到及时止损。Gas Limit可以看成是一道保险，实际Gas消耗超过设定的上限就会终止交易，实际消耗Gas量低于上限，多余的Gas也会退回来。交易中的实际消耗资源量Gas Used by Transaction一般与交易合约中的设定有关。

Gas Price的常用单位为Gwei，Gwei与ETH的换算关系为1ETH=10^9Gwei，即1ETH=10亿Gwei。一般来说，Gas Price的值会很小，而Gwei的设定就是为了方便表示微量的ETH，比如我们在转账是设置Gas Price为0.000000012 ETH，用Gwei为单位表示为12Gwei，很明显是后者表达得更为简单和直观。

<center>

![gas](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605084399195.png)
</center>

根据图中描述，我们可以发现，转账的手续费只与Gas Used by Transaction和Gas Price有关。交易手续费的计算公式如下：**交易手续费Fee =实际消耗资源量 Gas Used by Transaction\*资源单价Gas Price**。为了方便理解，我们举一个简单的例子：假设你需要寄一个包裹，当地的快递公司是按包裹重量收费，邮寄费用=包裹重量*每公斤邮费，即包裹越重，邮费越高。你可以发现，两者进行对比之后，这些名词都是一一对应的。邮费对应手续费，包裹重量对应使用资源量，每公斤邮费对应资源单价。

<center>

![gas](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605084448161.png)
</center>

那么我们再把这个例子延伸一下，就可以得到更多的结论。比如这个快递公司其实有陆运和空运两种业务，业务的单价是空运比陆运贵，相应的空运也会比陆运快很多。同样地，在以太坊上进行交易的时候，如果你设置的资源单价Gas Price比较高，那么矿工会倾向于优先打包你的交易，交易的确认速度自然也会快。

### 手续费（GAS）应该如何设置

一般来说，用户在进行转账的时候需要设置的参数就只有两个：Gas Limit和Gas Price。Gas Limit可以通过代码算出，Gas Price的取值以及交易速度则需要视当前网络情况而定。参数计算方面大家不用担心，如今市面上主流的钱包APP都会帮忙计算并给出推荐值。

<center>

![gas](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605084618449.png)
</center>

在TokenPocket钱包（简称为TP钱包）进行转账操作时，TP钱包会根据目前网络情况给出慢、推荐和快三档选项，对应的手续费用和预估的交易确认时间也很直观地罗列了出来，用户可以根据自身对交易快慢的需求选择合适的档位。这样的转账系统相当人性化，三档设置分配合理，大体上覆盖了用户转账的速度需求，增加用户体验感的同时也有效降低了手动输入带来的风险。

当然，如果用户需要修改Gas Limit或者设置更高的Gas Price，只需点击自定义，就可以自己设置Gas Limit和Gas Price，对应的手续费用及预估时间也会即时显示来为用户提供参考，可以说是相当方便了！

## 以太坊转账
在以太坊上发生交易是需要消耗 GAS 的，GAS 会从 ETH 地址余额中扣除，当余额不足以支付 GAS 费用时转账会失败。

<center>

![zhuanzhang](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605085109381.png)
</center>

### 以太坊加油站
当我们在转账 ETH 的过程中发现 GAS 不足时，可以使用 TokenPocket 的加油站功能。使用加油站可以小额充值，例如充值 50、100、150元等值的 ETH，从而可以充当转账时的 GAS 费用。

<center>

![jiayou](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605085187159.png)
</center>

### 以太坊交易加速
由于受到以太坊公链性能的限制，当以太坊上同时发生的交易比较多时，以太坊网络就会发生拥堵，转账时交易确认时间就会比较长，转账时交易状态通常会显示为 "pending"。
 
 <center>
 
 ![JS](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605085819509.png)
 </center>
 
处于 "pending" 状态中的交易，除了取消交易或继续等待外，还可以在 TokenPocket 中通过以太坊加速功能来加速完成转账交易，其原理其实就是多支付一些矿工费从而让矿工优先确认。在交易加速页面，TokenPocket会自动为用户选择最佳矿工费，无须调整矿工费，即可一键加速；同时用户也可以自定义调整矿工费。

### 以太坊代币授权
ETH上的DApp大都涉及到合约操作，所以在授权的时候，是授权某个合约地址可以操作地址中多少代币；在操作过程中，如果将代币转账授权都授权给一个恶意的合约，那就相当于这个合约可以把你的代币拿去做抵押或者其它恶意操作。

例如：

A账号有10000个token代币,B账号没有token代币,C账号也没有token代币！    

那么：A账号 委托 B账号 转给C账号 100个token代币 怎么来实现呢？    

首先：A账号 和 B账号建立一种委托关联,登录A账户执行approve(b,100)方法结果为：结果：_allowed[A][B] = 100token    

然后：在执行登录B账户执行transferFrom(A,C,100),这里的B就是委托账号发送者,gas从B扣,必须确保token数量小于_allowed[A][B]

<font color="red">总结来说： 就是A转入C,但是要经过B的账号来发送交易！</font>

以太坊上的DeFi已被广大用户所熟知，例如辨识度很高的Uniswap、Curve、Banlancer等工具，这类工具的操作便捷、功能强大，而且上线代币也非常方便，所以这就会导致可能会有一些恶意的人来通过这些平台作恶，所以在我们每次执行ERC20代币兑换的时候（尤其是一些新代币）都可能会存在风险。现在我们可以在TokenPocket钱包中直接看到【操作类型】和【授权数量】，提醒用户潜在风险。

<center>

![approve](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605079414561.png)
</center>

<br /><br />

# 以太坊 Token与钱包
## ETH Token
### ETH Token发行

ETH Token 是以太坊（Ethereum）的一种数字代币，以太坊生态开发者们需要支付 ETH 来支撑应用的运行，用户在进行转账时，也是需要支付一定量的 ETH 做为 GAS 转账费用。

与Bitcoin不同，Ethereum的代币发行计划在创建前并没有被设定好。Bitcoin通过限制供应量并降低新面世代币的数量来保护价值，而Ethereum则通过代币为去中心化应用程序（DApps）提供基础，目前尚未确定何种类型的代币发行计划适合此目的。

人们可以使用Ethereum的原生货币ETH来作为数字货币或抵押品，也有一些人将ETH视为与Bitcoin一样的价值存储手段。但它又与Bitcoin不同，因为Ethereum区块链的高度可编程性赋予了ETH更多效用。也就意味着Ether成为了去中心化金融应用程序，去中心化市场、交易所、游戏以及其他应用的生机之源。

### ETH Token获取

用户可以通过币币闪兑、法币购买（币买卖）和交易所交易这三种方式来获得 ETH Token。


 - 交易所交易

ETH 及发行在 ETH 公链上的 token，可以在中心化交易所购买，例如在币安、火币和 OKEx 等，都可以交易 ETH 公链上发行的优质资产。但在中心化交易所中以交易的 ETH 资产种类往往是非常有限的，一般仅限于发展比较好的优质资产才可以上线比较大的中心化交易所，而更多在 ETH 上发行的资产，是可以到 ETH 去中心化交易所进行交易的。

<center>

![eth](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605086047125.png)
</center>

目前做的最好的 ETH 去中心化交易所要属 Uniswap 了，在该平台上几乎可以交易所有的 ETH 资产。在 TokenPocket 的推荐 DApp 专区中找到 Uniswap 并打开，然后就可以进行相应 ETH 资产的交易了，还可以使用 TP 钱包自带的闪兑功能来进行 ETH 资产的交易。

<center>

![eth](https://tp-statics.tokenpocket.pro/banner/tokenpocket-20201112165619.png)
</center>

 - 币币闪兑
 
通过闪兑功能可以进行ETH链上的token兑换，如ETH 换DAi，或是将ETH兑换为 BTC\TRON\EOS，这样的跨链兑换可以方便不同链上资产之间的流通。

<center>

![swft](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605086309703.png)
</center>

 - 场外购买

除了币币交易之外，还可以通过场外交易平台来获得 ETH。

<center>

![otc](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605086399475.png)
</center>

## 以太坊上的其他Token介绍

 - 以太坊-USDT
 
在以太坊上发行的优质数字资产中，USDT 便是其中之一。USDT 是 Tether公司推出的基于稳定价值货币美元（USD）的代币Tether USD（简称USDT），每个Tether USD 也都与美元保持1比1的汇率，因此1美元始终被Tether估价为1美元。（信息来源[Tether官网][3]）

<center>

![usdt](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605086614869.png)
</center>

用户可以通过SWIFT电汇美元至Tether公司提供的银行帐户，或通过交易所换取USDT；赎回美元时，反向操作即可。用户也可在交易平台用比特币换取USDT。以太坊-USDT 是 Tether 在以太坊网络上发行 ERC20 代币，目前 Tether 已经在比特币（Omni）、EOS 以及 TRON 等公链上发行了相应版本的 USDT 代币，其中 ETH-USDT 的数量是最多的，也推动了 ETH 公链生态的发展。

 - 以太坊 NFT Token
 
NFT全称是：Non-Fungible Token（不可替代的Token），所谓不可替代，就是每一个都是独一无二，相互区别的。传统的ERC20 token可以被称为Fungible token，它们每个之间都是相同的，拥有相同的价值。例如你拥有的 1 ETH 和别人拥有的 1 ETH 是等价的。
 
其实在很多场景中，token的价值不是等价的。例如游戏中十种道具的价值相互都有区别。再如，我们将一场球赛的门票进行token化后销售，因为不同门票对应不同座位的价值不一样，因此 token之间的价值也不一样。
 
为了区别不同的token价值，以太坊网络在发行token时为每一个token设置不同的 token ID 来进行区别，这样的 token 就被称为 NFT。在以太坊中有两个标准专门来进行 NFT 的发行，一个是ERC721标准，另一个是ERC1155标准。
 
ERC721标准详细定义了NFT的接口和特性，ERC1155标准由Enjin提出，可以在一个合约中同时发行Fungible token 和 Non-Fungible token。并且可以在一个合约中发行多种token，因而更加强大。例如大家熟知的 CryptoKitties 游戏，就采用了 NFT token，不同的猫价值是不同的，因为它们都是独一无二的。

## 以太坊 Token交易平台

#### Uniswap
 
ETH 以及在以太坊上发行的其他 token，除了可以在币安、火币以及 OKEx 等中心化交易所上进行交易，还可以到 Uniswap 等去中心化交易所上进行交易。

<center>

![uni](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605086785426.png)
</center>

2018年11月，Uniswap正式上线，其定位是一个基于以太坊的去中心化交易所（DEX）。DEX虽然在用户资产安全性方面有所提升，但是受限于其资金规模，大多数DEX的资产流动性并不好，交易速度也就成了一个硬伤。为了解决这个问题，Uniswap并未采用主流的订单薄交易系统，而是选择了自动化做市商机制。Uniswap在交易机制上的创新也在DEX领域掀起一股热潮，一大批AMM项目涌现出来。

目前在Token Pocket等主流去中心化钱包APP内，均可以直接登录Uniswap进行操作。在Uniswap内进行交易，你只需要在兑换界面，选择好兑换的币种和数量，页面下方会自动显示兑换的比例和交易滑点（价格误差），如果觉得合理，点击Swap 便可一键进行兑换交易，在交易上链后就能立即取得你应得的币。即使用户需要兑换的代币没有直接的交易对，Uniswap也会自动帮助用户寻找价格最优的途径，在交互界面上，用户还是只需发出一笔交易就能完成兑换，一键Swap就完事了。

<center>

 ![uni](https://tp-statics.tokenpocket.pro/banner/tokenpocket-20201113121511.png)
</center>

对Uniwap感兴趣的用户还可以通过以下文章获得更多了解
[《人人都玩的Uniswap到底是什么？》][4]
[《最好用的Uniswap钱包和教程来啦！》][5]

#### Balancer
Balancer是一个自动化的投资组合管理程序，是流动性提供者和价格传感器。Balancer颠覆了指数基金的概念：用户无需向投资组合经理支付费，而是从交易员那里收取费用，交易员通过跟随套利机会来重新平衡投资组合。人们可以在Balancer进行ETH和ERC20代币，或ERC20代币间的兑换。

对Balancer感兴趣的用户可以[点击阅读][6]使用教程

#### Curve
curve主要是稳定币间的兑换和BTC-ERC20间的兑换，凭借低交易滑点、低手续费、高收益率和单币种存取等优势在很短的时间内就吸引了大量的用户参与。

对Curve感兴趣的用户可以[点击阅读][7]使用教程

#### AAVE
Aave是一种去中心化协议，可通过存款赚取利息，也可借贷。它是开源且无监管的，也就是说所有人都可以访问其代码。Aave是以太坊区块链上的智能合约生态系统，因此它是完全透明的、可跟踪的，且所有人都可以对其进行审计。用户可以将部分资产存入Aave储备资金池，并从中赚取利息（其回报率要高于大多数传统银行）。若用户有足够的抵押品，还可以从资金池中借用一些资产。与传统银行相比，Aave协议可以让你的资金发挥最大效用。例如，借款人可以在稳定利率和浮动利率之间进行切换，以保持市场优势并获得最佳利率。

对AAVE感兴趣的用户可以[点击阅读][8]使用教程

#### Synthetix 
Synthetix 是基于以太坊构建的合成资产（Synths）的发行协议，在Synthetix中，合成资产包括sBTC（BTC合成资产）、sETH（ETH合成资产）、iBTC（BTC反向资产，即BTC跌则iBTC涨）、iETH、sXAU（黄金合成资产）等等。Synthetix 为 DeFi 利用传统金融资产及更多样、更复杂的交易策略提供了通道。发行合成资产的过程为：先抵押 SNX 生成 sUSD，然后用sUSD 购买合成资产。

对Synthetix感兴趣的用户可以[点击阅读][9]使用教程

#### Compound
Compound是一种基于以太坊区块链的算法货币市场协议，是一种允许用户借贷代币的智能合约。它与你的银行类似，Compound把你的钱借给借款人，并随着时间的推移赚取利息。Compound于今年2月发布称，为实现Compound协议治理流程完全去中心化，开发团队决定发行治理代币「COMP」，创造由代币持有者组织的社群，社区成员可通过提案、表决对协议进行更改，取代目前由开发团队主导的中心化治理方式。

对Compound感兴趣的用户可以[点击阅读][10]使用教程

#### dForce
dForce是发行在以太坊上的去中心金融（DeFi）和货币协议平台，主要产品功能有dForce生息市场，合成型稳定币USDx铸币、稳定资产Swap闪兑和GOLGx数字黄金代币，并在8月3号晚10点正式启动流动性挖矿方案，用户可以通过在生息市场质押dToken和在Uniswap提供相应代币的流动性来进行挖矿。

对dForce感兴趣的用户可以[点击阅读][11]使用教程

<br /><br />

# 以太坊钱包使用场景
## 以太坊 Token转账
### 三种不同的转账操作

 1. 普通转账(以太坊账号互转）
普通转账指的是独立的以太坊账号之间的转账，只需输入接收方 TRON 账号以及转账数量。

 2. 从交易所账号转账到以太坊账号（钱包账号）
从交易所转账到以太坊账号（钱包账号）即从交易所把以太坊提币出来，提到自己独立的 以太坊账号中，只需输入提币地址（以太坊钱包账号）、提币数量，就可以完成提币。

 3. 从以太坊账号（钱包账号）转账到交易所账号
用户从以太坊账号（钱包账号）转到交易所，只需输入交易所地址和充币数量，就可以完成充值。

### 丰富便捷的转账形式
目前，用户可以通过直接转账、地址簿转账、扫码转账、观察钱包和冷钱包交互的方式进行快捷转账。

 1. 直接转账
 
直接转账指的是以太坊地址之间的转账。用户只需知道对方以太坊账号或想要充币的交易所地址，然后将其复制到收款地址并输入转账数量，点击确认即可。

 2. 地址簿转账
 
如果用户有常用的以太坊转账地址，可以将它添加到钱包的地址薄。地址簿相当于我们的手机通讯录，这样用户在转账时直接从地址薄选择账号，省时省力更安全。

 3. 扫码转账
 
这个方式类似微信、支付宝二维码付款，通过扫描用户的收款二维码，即可向指定账号转账，面对面转账很方便。

 4. 使用观察钱包和冷钱包进行转账
 
如果用户钱包里长期存放大额资产并有经常的转账的需求，建议使用观察钱包+冷钱包的方式进行转账，以保证资产安全。所谓冷钱包，就是用网络物理隔离的方式（例如一台完全断网的手机）让用户的私钥和助记词不触网，以保证用户的数字资产接近 100% 安全。观察钱包即可以观察其他地址中资产变化情况的钱包。它不需要导入私钥，只需导入账号或公钥，通过观察钱包，可以进行日常查看账号的交易记录。

 在进行转账时，用户先在观察钱包发送操作。与平时转账不同的是，需要授权的时候，会弹出一个二维码。这个时候拿出冷钱包扫码，扫码以后会生成另一个二维码，此时需要用观察钱包再次反向扫码冷钱包，从而完成整个转账操作流程。 

<center>

![uni](https://tp-statics.tokenpocket.pro/banner/tokenpocket-20201112220901.jpg)
</center>

## 以太坊 Token收款
在以太坊钱包内，用户还可以进行资产收款或接收来自交易所提的币。

 1. 地址收款
在收款界面，用户可以一键复制自己的收款地址，方便自己从交易所提币或对方向自己转账，方便又安全。

 2. 二维码收款
和上文扫码转账类似，对方通过扫描收款二维码即可向自己进行转账。

## 以太坊 钱包白名单设置
通常用户在体验DApp时，由于智能合约和用户的操作进行交互， 每次相同操作都需要填写密码，十分不便。白名单功能是针对DApp 内特定的智能合约操作进行免密授权，只需在开启白名单功能时需要输入密码，之后的同一操作均可免输入。（当前只支持WalletConnect）

白名单功能为用户更好地使用 DApp 提供了极大的便利，TokenPocket钱包支持白名单（WalletConnect方式）设置，方便用户进行操作。

<center>

 ![uni](https://tp-statics.tokenpocket.pro/banner/tokenpocket-20201112165646.png)
</center>

## 以太坊 浏览器使用
区块链浏览器是浏览区块链信息的主要窗口，每一个区块所记载的内容都可以从区块链浏览器上进行查阅。目前常用的以太坊浏览器有 etherscan 浏览器http://etherscan.io/和 etherchain  浏览器https://www.etherchain.org/
使用以太坊浏览器可以查询以太坊全网的基础数据:最新区块、交易数量、账户数量、代币数量等；查询账户信息:交易信息、以太坊余额和抵押信息等；还可以直接查询转账、余额、投票权。

<center>

 ![uni](https://tp-statics.tokenpocket.pro/banner/tokenpocket-20201112165603.png)
</center>

## 以太坊 钱包排序调整
很多用户会有多个以太坊账号，自己常用的钱包位置比较靠后，这样使用起来十分不便。钱包排序功能可以轻松解决这一痛点。用户通过对账号拖拉调整钱包账号顺序，把经常使用的账号位置提前，更方便日常钱包切换与资产管理。

<center>

 ![uni](https://tp-statics.tokenpocket.pro/banner/tokenpocket-20201112165658.png)
</center>

## 以太坊 相关资讯获取
对于以太坊用户来讲，要经常关注以太坊的讯息，以了解以太坊发展最新情况。这些资讯用户可以直接通过以太坊钱包来浏览资讯。例如 TokenPocket钱包，所有关于以太坊的最新消息和快讯和重要文章，都第一时间一站式收录在钱包的快讯和文章频道，优化了用户的阅读体验。

<center>

![2.0](https://tp-statics.tokenpocket.pro/banner/tokenpocket-20201112220914.jpg)
</center>

## 以太坊ENS
ENS，是Ethereum Name Service的缩写，中文名字叫“以太坊域名服务”，它是一个基于以太坊区块链的可扩展，分布式和开放式命名系统，主要服务于人类可读的映射名称。ENS将人类可读的名称，映射到机器可读的标识符，具有读取以太坊地址，内容哈希和元数据的功能的功能。

使用以太坊转账时，可以输入对应以太坊域名，钱包会自动查询对应的以太坊地址，即可实现便捷转账。

<center>

![ens](https://tp-statics.tokenpocket.pro/banner/tokenpocket-1605088099236.png)
</center>

## 以太坊 dapp体验
### DeFi与钱包
DeFi，全称为Decentralized Finance，即“去中心化金融”或者“分布式金融”。“去中心化金融”与传统中心化金融相对，指建立在开放的去中心化网络中的各类金融领域的应用，目标是建立一个多层面的金融系统，以区块链技术和密码货币为基础，重新创造并完善已有的金融体系。DeFi以区块链技术为依托，可以解决目前中心化金融中存在的不透明、效率低、单点故障等众多痛点，同时DeFi的兼容度很强，无论是去中心化交易所、去中心化借贷、支付平台、衍生品等均可以被归入DeFi的范畴，所以DeFi是一个极具潜力的金融市场，也能形成一个相对完整闭环的生态系统。

ETH生态拥有极强的生命力，其主网上多元化的ERC（ERC-20以及ERC-721）代币数量之多、应用覆盖范围之广、互通性之强是其他公链远不能及的，也为DeFi应用的爆发奠定了基础。

DeFi中DApp大部分基于网页端开发，因此对类似Metamask这样的网页钱包插件兼容性较好。在钱包网页插件中创建或者导入钱包，在对应的DApp界面使用钱包插件进行登录，即可轻松完成与合约的互动操作。然而因为交易等金融行为即时性要求较高，网页端钱包插件的弊端开始显露，移动端数字钱包开始获得用户的青睐。在解决了兼容问题之后，移动端仍然针对DeFi Dapp的使用体验进行持续的优化和更新。用户只需要在手机上安装类似TokenPocket这样主流的数字钱包，即可一键进入DeFi DApp，无需科学上网，不受地点时间限制。此外，移动端数字钱包已经开始支持Wallet Connect功能，受用手机钱包APP中的扫码功能即可实现与桌面Web端的交互，方便又安全！

<center>

![2.0](https://tp-statics.tokenpocket.pro/banner/tokenpocket-20201112220843.jpg)
</center>

### DAO与DeFi
DeFi的核心在与去中心化，中心化的特质也为DeFi拥有了公开透明、不惧单点故障等优点。然而如果只是局限于链上交易的中心化，一些的DeFi项目的管理和运行方式仍然与中心化相似，这样的项目是难以具有颠覆性的。只有将项目的管理权力分散、下放，从治理方式上做出根本的改变，才能颠覆和超越采用固有治理模式的传统上市公司，产生革命性的结果。这也是许多DeFi项目选择拥抱DAO的原因。

什么是DAO？DAO即分布式自治组织（Decentralized Autonomous Organization），是一种基于区块链技术与智能合约代码所定规则运行的组织。DAO的运行规则由开源合约中制定代码逻辑决定，这也决定了DAO不受时间地点影响、运行过程公开透明且规则不会被篡改的特点。同时，作为股东或者持币者，DAO中的每个人都可以发布提议并进行投票来做决策。可以看出，DAO的存在恰恰可以解决DeFi项目在治理上的问题。其实DeFi和DAO并不是最近才诞生的新概念，两者的合作最早也可以追溯到成立于2014年的Maker DAO。早在2014年，以太坊上自动化抵平台MakerDAO就已经作出了迈向DAO的尝试，同时它也是DeFi的项目代表之一。

### 热门的DeFi应用
DeFi领域中目前已经发展得比较好的应用形式主要有：借贷-Credit&Lending、稳定币-StableCoins、去中心化交易所-DEX、支付-payment、衍生品与预测市场-Derivative Protocols/Prediction Markets等，目前借贷和去中心化交易所因为起步较早，所以获得的关注较多，此外近期崛起的资产数据整合和流动性挖矿获得了极高的热度并吸引了大量的资金。以下为目前较为热门的ETH DeFi DApp整合(热度高不代表参与、投资建议，投资有风险）：

借贷类：Aave、Makerdao、Compound等

去中心化交易所：Uniswap、Curve Finance、Balancer、Bancor等

衍生品市场：Synthetix、Nexus Mutual等

资产数据聚合：Yearn.finance、RenVm、DForce等。

跨连类：WBTC、renBTC等

TokenPocket钱包支持当下几乎所有热门的ETH DeFi DApp，并针对Uniswap、Balancer等ETH上比较具有代表性和优化空间的DeFi进行了优化，如对推出了汉化版Uniswap、支持国内用户不翻墙即可使用Uniswap、增加Uniswap K线功能、交易行情等。

<br /><br />

# 以太坊2.0与钱包
## 以太坊2.0是什么
Eth2.0是以太坊的计划升级方案，也可以理解为Eth1.0的替代品。它的目的是使ETH更安全，在不牺牲去中心化的基础上，提高交易速度，优化编程功能。为了解决区块链中去中心化、可扩容以及安全性不可共存的“不可能三角”问题，Eth2.0会在技术层面做出很大的改动，希望通过一些先进的技术：分片技术、Casper 协议、状态租金（state rent，即向用户收取存储数据费用的机制）和以太坊新一代虚拟机项目 eWASM等，来试图解决限制区块链发展的几大问题，创建一个消除中心障碍以及维持区块链“不可能三角””权衡的框架。届时，Eth 2.0 将通过不断地更新迭代逐步成为主链，而当下的以太坊主链将会成为受其管理的分片链。
在以太坊2.0的各个阶段，用户都可以通过钱包进行参与，无论是前期的抵押还是正式上线后新链的各种功能。

## 查看以太坊2.0进度
根据以太坊 2.0 计划，上线至少要经过三个阶段：阶段 0、1 和 2。阶段 0 计划即信标链（beacon chain）计划今年12月1日启动，阶段 1 和 阶段 2 将在未来几年发布。如果在12月1日前有16,384 （2 的 14 次方）个验证人参与，2.0 的信标链就会正式开启。如果12月1日前无法达到这个标准，则将在达成这个标准之后的 7 天后才会启动主网。

<center>

![2.0](https://tp-statics.tokenpocket.pro/banner/tokenpocket-20210113121440.png)
</center>

对于万众期待的Eth 2.0信标链是否可以如约上线，大家可以通过使用以太坊钱包的观察模式，去实时查看Eth 2.0存款合约（0x00000000219ab540356cBB839Cbe05303d7705Fa）的余额情况。

<br /><br />

# 以太坊开发者与钱包
作为最早的智能合约公链，以太坊有着最为成熟的开发者生态，功能强大的IDE Remix；简单易用的智能合约开发语言Solidity和开发框架Truffle，广泛使用的NFT协议ERC721，ERC1155；同时也是各种DeFi协议爆发的公链。
钱包是开发者与用户链接的桥梁，以TokenPocket为例，会提供给开发者兼容多种协议的登录与签名方式，钱包内Webview中内置web3 和 ethereum对象兼容Metamask的web3登录协议，支持WalletConnect的扫码以及移动端浏览器的唤起操作。同时TokenPocket 还为iOS和Android原生APP 提供了Mobile SDK 可以唤起钱包进行登录授权，代币转账以及合约操作等功能。

# ETH钱包分类
## 去中心化钱包

<!-- 1 -->

<main class="tp-main">
<!-- TokenPocket -->
<a class="tp-custom" href="https://www.tokenpocket.pro" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/TokenPocket.png"/>
    <div class="tp-content">
        <h5>TokenPocket</h5>
        <p>https://www.tokenpocket.pro</p>
    </div>
</a>


<!-- Trust Wallet -->
<a class="tp-custom" href="https://www.trustwallet.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/TrustWallet.png"/>
    <div class="tp-content">
        <h5>Trust Wallet</h5>
        <p>https://www.trustwallet.com</p>
    </div>
</a>
</main>

<!-- 2 -->

<main class="tp-main">
<!-- Bitpie -->
<a class="tp-custom" href="https://bitpie.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Bitpie.png"/>
    <div class="tp-content">
        <h5>Bitpie</h5>
        <p>https://bitpie.com</p>
    </div>
</a>


<!-- imToken -->
<a class="tp-custom" href="https://token.im" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ImToken.png"/>
    <div class="tp-content">
        <h5>imToken</h5>
        <p>https://token.im</p>
    </div>
</a>
</main>

<!-- 3 -->

<main class="tp-main">
<!-- Huobi -->
<a class="tp-custom" href="https://www.huobiwallet.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/HuobiWallet.png"/>
    <div class="tp-content">
        <h5>Huobi Wallet</h5>
        <p>https://www.huobiwallet.com</p>
    </div>
</a>


<!-- AToken -->
<a class="tp-custom" href="https://www.atoken.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/AToken.png"/>
    <div class="tp-content">
        <h5>AToken</h5>
        <p>https://www.atoken.com</p>
    </div>
</a>
</main>

<!-- 4 -->

<main class="tp-main">
<!-- BPEAL Wallet -->
<a class="tp-custom" href="https://www.bepal.pro" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/BPEALWallet.png"/>
    <div class="tp-content">
        <h5>BPEAL Wallet</h5>
        <p>https://www.bepal.pro</p>
    </div>
</a>


<!-- Starteos -->
<a class="tp-custom" href="https://www.starteos.io" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Starteos.png"/>
    <div class="tp-content">
        <h5>Starteos</h5>
        <p>https://www.starteos.io</p>
    </div>
</a>
</main>

<!-- 5 -->

<main class="tp-main">
<!-- BitKeep -->
<a class="tp-custom" href="https://www.bitkeep.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Bitkeep.png"/>
    <div class="tp-content">
        <h5>BitKeep</h5>
        <p>https://www.bitkeep.com</p>
    </div>
</a>


<!-- MEET.ONE -->
<a class="tp-custom" href="https://www.meet.one" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Meetone.png"/>
    <div class="tp-content">
        <h5>MEET.ONE</h5>
        <p>https://www.meet.one</p>
    </div>
</a>
</main>

<!-- 6 -->

<main class="tp-main">
<!-- Tronlink -->
<a class="tp-custom" href="https://www.tronlink.org" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Tronlink.png"/>
    <div class="tp-content">
        <h5>Tronlink</h5>
        <p>https://www.tronlink.org</p>
    </div>
</a>


<!-- Lynx -->
<a class="tp-custom" href="https://lynxwallet.io" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Lynx.png"/>
    <div class="tp-content">
        <h5>Lynx</h5>
        <p>https://lynxwallet.io</p>
    </div>
</a>
</main>

<!-- 7 -->

<main class="tp-main">
<!-- Scatter -->
<a class="tp-custom" href="https://get-scatter.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/scatter.png"/>
    <div class="tp-content">
        <h5>Scatter</h5>
        <p>https://get-scatter.com</p>
    </div>
</a>


<!-- MetaMask -->
<a class="tp-custom" href="https://metamask.io" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/MetaMask.png"/>
    <div class="tp-content">
        <h5>MetaMask</h5>
        <p>https://metamask.io</p>
    </div>
</a>
</main>

<!-- 8 -->

<main class="tp-main">
<!-- ENJIN Wallet -->
<a class="tp-custom" href="https://enjin.io/products/wallet" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ENJINWallet.png"/>
    <div class="tp-content">
        <h5>ENJIN Wallet</h5>
        <p>https://enjin.io/products/wallet</p>
    </div>
</a>


<!-- jaxx wallet -->
<a class="tp-custom" href="https://jaxx.io" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/JaxxWallet.png"/>
    <div class="tp-content">
        <h5>jaxx wallet</h5>
        <p>https://jaxx.io</p>
    </div>
</a>
</main>

<!-- 9 -->
<main class="tp-main">
<!-- 块信 -->
<a class="tp-custom" href="https://chattle.vip/#/" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/dapp/tokenpocket-1576249499924.png" width=50 />
    <div class="tp-content">
        <h5>块信</h5>
        <p>https://chattle.vip</p>
    </div>
</a>


<!-- KCASH -->
<a class="tp-custom" href="https://www.kcash.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/KCASH.png"/>
    <div class="tp-content">
        <h5>KCASH</h5>
        <p>https://www.kcash.com</p>
    </div>
</a>
</main>


<!-- 10 -->
<main class="tp-main">
<!-- Conibase Wallet -->
<a class="tp-custom" href="https://www.coinbase.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ConibaseWallet.png"/>
    <div class="tp-content">
        <h5>Coinbase Wallet</h5>
        <p>https://www.coinbase.com</p>
    </div>
</a>

<!-- KCASH -->
<a class="tp-custom" style="border:none" target="_blank">
    <!-- <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/KCASH.png"/>
    <div class="tp-content">
        <h5>KCASH</h5>
        <p>https://www.kcash.com</p>
    </div> -->
</a>
</main>

## 中心化钱包

<!-- 1 -->

<main class="tp-main">
<!-- 币信 -->
<a class="tp-custom" href="https://bixin.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/bixin.png"/>
    <div class="tp-content">
        <h5>币信</h5>
        <p>https://bixin.com</p>
    </div>
</a>


<!-- Edge -->
<a class="tp-custom" href="https://edge.app" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Edge.png"/>
    <div class="tp-content">
        <h5>Edge</h5>
        <p>https://edge.app</p>
    </div>
</a>
</main>

<!-- 2 -->

<main class="tp-main">


<!-- Uphold -->
<a class="tp-custom" href="https://uphold.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Uphold.png"/>
    <div class="tp-content">
        <h5>Uphold</h5>
        <p>https://uphold.com</p>
    </div>
</a>

<!-- Conibase Wallet -->
<a class="tp-custom" style="border:none">
    <!-- <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ConibaseWallet.png"/>
    <div class="tp-content">
        <h5>Conibase Wallet</h5>
        <p>https://www.coinbase.com</p> -->
    <!-- </div> -->
</a>

</main>

## 硬件钱包

<!-- 1 -->

<main class="tp-main">
<!-- Ledger -->
<a class="tp-custom" href="https://www.ledger.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Ledger.png"/>
    <div class="tp-content">
        <h5>Ledger</h5>
        <p>https://www.ledger.com</p>
    </div>
</a>


<!-- Trezor -->
<a class="tp-custom" href="https://www.trezor.io" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Trezor.png"/>
    <div class="tp-content">
        <h5>Trezor</h5>
        <p>https://www.trezor.io</p>
    </div>
</a>
</main>

<!-- 2 -->

<main class="tp-main">
<!-- keep key -->
<a class="tp-custom" href="https://shapeshift.io/keepkey" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/keepkey.png"/>
    <div class="tp-content">
        <h5>keep key</h5>
        <p>https://shapeshift.io/keepkey</p>
    </div>
</a>


<!-- 库神(ColdLar） -->
<a class="tp-custom" href="https://www.coldlar.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ColdLar.png"/>
    <div class="tp-content">
        <h5>库神(ColdLar）</h5>
        <p>https://www.coldlar.com</p>
    </div>
</a>
</main>

<!-- 3 -->

<main class="tp-main">
<!-- 比特护盾（BITHD) -->
<a class="tp-custom" href="https://bithd.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/BITHD.png"/>
    <div class="tp-content">
        <h5>比特护盾（BITHD)</h5>
        <p>https://bithd.com</p>
    </div>
</a>


<!-- imKey -->
<a class="tp-custom" href="https://imkey.im" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/imKey.png"/>
    <div class="tp-content">
        <h5>imKey</h5>
        <p>https://imkey.im</p>
    </div>
</a>
</main>

<!-- 4 -->

<main class="tp-main">
<!-- Cobo金库 -->
<a class="tp-custom" href="https://cobo.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Cobo.png"/>
    <div class="tp-content">
        <h5>Cobo金库</h5>
        <p>https://cobo.com</p>
    </div>
</a>


<!-- BEPAL Pro S -->
<a class="tp-custom" href="https://www.bepal.pro/bepal-q" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/BEPALProS.png"/>
    <div class="tp-content">
        <h5>BEPAL Pro S</h5>
        <p>https://www.bepal.pro/bepal-q</p>
    </div>
</a>
</main>

<!-- 5 -->

<main class="tp-main">
<!-- 华特钱包 -->
<a class="tp-custom" href="https://www.orientwalt.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/orientwalt.png"/>
    <div class="tp-content">
        <h5>华特钱包</h5>
        <p>https://www.orientwalt.com</p>
    </div>
</a>


<!-- SafePal-->
<a class="tp-custom" href="https://safepal.io/" target="_blank">
    <img class="tp-logo" width=50 src="https://tp-statics.tokenpocket.pro/dapp/tokenpocket-1576591843263.png"/>
    <div class="tp-content">
        <h5>SafePal</h5>
        <p>https://safepal.io/</p>
    </div>
</a>
</main>



## 中心化&去中心化

<!-- 1 -->

<main class="tp-main">
<!-- Cobo -->
<a class="tp-custom" href="https://cobo.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Cobo.png"/>
    <div class="tp-content">
        <h5>Cobo</h5>
        <p>https://cobo.com</p>
    </div>
</a>


<!-- 库神 -->
<a class="tp-custom" href="https://www.coldlar.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ColdLar.png"/>
    <div class="tp-content">
        <h5>库神</h5>
        <p>https://www.coldlar.com</p>
    </div>
</a>
</main>

<!-- 2 -->

<main class="tp-main">
<!-- 虎符 -->
<a class="tp-custom" href="https://hoo.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Hoo.png"/>
    <div class="tp-content">
        <h5>虎符</h5>
        <p>https://hoo.com</p>
    </div>
</a>


<!-- RenrenBit -->
<a class="tp-custom" href="https://www.renrenbit.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Renrenbit.png"/>
    <div class="tp-content">
        <h5>RenrenBit</h5>
        <p>https://www.renrenbit.com</p>
    </div>
</a>
</main>

<!-- 3 -->

<main class="tp-main">
<!-- HyperPay -->
<a class="tp-custom" href="http://www.hyperpay.tech" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Hyperpay.png"/>
    <div class="tp-content">
        <h5>HyperPay</h5>
        <p>http://www.hyperpay.tech</p>
    </div>
</a>


<!-- Math Wallet -->
<a class="tp-custom" href="http://www.mathwallet.org" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/MathWallet.png"/>
    <div class="tp-content">
        <h5>Math Wallet</h5>
        <p>http://www.mathwallet.org</p>
    </div>
</a>
</main>

<br /><br />

# 以太坊 钱包知识自测

<br /><br />

# 以太坊钱包常见问题
https://www.yuque.com/tokenpocket/gz8u7f

![QRCode](https://tp-statics.tokenpocket.pro/banner/tokenpocket-20201112161352.png)

<br /><br />

# 以太坊联系方式

Website：https://ethereum.org

Twitter：https://twitter.com/ethereum

Youtube：https://www.youtube.com/channel/UCNOfzGXD_C9YMYmnefmPH0g

GitHub：https://github.com/ethereum

<br /><br />

# 版权申明
《区块链入门必读之以太坊钱包知多少》，又称为以太坊钱包小白书。由 TokenPocket 联合TokenPocket 社区志愿者（TP 侠：阿华、明观、币范儿）共同撰写，详细介绍了当前以太坊钱包与以太坊生态密切结合的实例，是目前市面上最为详细的以太坊数字钱包科普资料。

1.本文版权归TokenPocket所有。

2.在征得作者同意的情况下，作品允许非盈利性引用，需要注明并请注明出处和作者，以尊重作者的劳动成果。

3.出处：https://tp-lab.github.io/BlockchainGuide-ETH/

&nbsp;&nbsp;&nbsp;作者：TokenPocket。

4.未经允许，严禁转载。对非法转载者，TokenPocket和作/译者保留采用法律手段追究的权利。

5.对于本文和本声明以及其修改权、更新权及最终解释权均属TokenPocket。

6.以上声明的解释权归“TokenPocket”所有。




  [1]: https://github.tokenpocket.pro/BlockchainGuideSeries/#/
  [2]: https://cn.etherscan.com/
  [3]: https://tether.to/
  [4]: https://mp.weixin.qq.com/s?__biz=MzUyNDkzNTgwMw==&mid=2247486203&idx=1&sn=434ea663224f794f44d791fd676f0508&chksm=fa24fdefcd5374f92b28177577a505fa17c378521b3e81f70118741dab46e969d938a95a57a8&mpshare=1&scene=1&srcid=1027VMDBQhSTAdWrMgjrSnrv&sharer_sharetime=1603801690561&sharer_shareid=ece12c95b3a68df0132982297a5cb7d4&key=de438a290b06e75a68b510a7efb4db495b80145869833edda461689c73315e8d2336d096c602fb4c99ca24d19fdba85e6c879ba1b16b60d7651fcd12fd5682cc45e70eabe318591819a25252112a659618d69ff8113b8195d8722ea023025e1b46933c85525e1377957a7d2f295821f706bb0971a40379f4e991feab118ba2b4&ascene=1&uin=MTM4MTQxMjQ0MA==&devicetype=Windows%2010%20x64&version=6300002f&lang=zh_CN&exportkey=AaS4By4hmGTQY6NUQDhEqwg=&pass_ticket=Bmm69g%2bCOPf5yJELBplaiObqpwYIgmX2/BwQ2Xi8OCasskAuFSbdnrWhn5TScTGG&wx_header=0
  [5]: https://mp.weixin.qq.com/s?__biz=MzUyNDkzNTgwMw==&mid=2247486278&idx=1&sn=718170149ae5737b58e06822a4ee2ad0&chksm=fa24fc52cd537544924de9d1bfd08565eda23d248190ed501c45a30969b7631fda63585e977a&mpshare=1&scene=1&srcid=1027cIHIcIL7wbCXkq0EoCAt&sharer_sharetime=1603802686041&sharer_shareid=ece12c95b3a68df0132982297a5cb7d4&key=de438a290b06e75a4baddb7d916f0dff24cc41300cf8081dd840ce7cf2d1c76d47ae259740fde95f4541269eb84e1ed75c40cbc3c3295abaf2492ca398f6446ac33b0531d7967ffdf6f3ecd6ffc2332003d74431444d942e6b17b37d462aeeb142ea4de897364a458346451a77f18e3e8388b92f49f60cede18b9e2efb32bc55&ascene=1&uin=MTM4MTQxMjQ0MA==&devicetype=Windows%2010%20x64&version=6300002f&lang=zh_CN&exportkey=AR5WoDo64n5g/0zrejbEGuM=&pass_ticket=Bmm69g%2bCOPf5yJELBplaiObqpwYIgmX2/BwQ2Xi8OCasskAuFSbdnrWhn5TScTGG&wx_header=0
  [6]: https://www.yuque.com/tokenpocket/guzgqx/bii4g3
  [7]: https://www.yuque.com/tokenpocket/guzgqx/kxh3ky
  [8]: https://www.yuque.com/tokenpocket/guzgqx/sldy8d
  [9]: https://www.yuque.com/tokenpocket/guzgqx/pr0ucv
  [10]: https://www.yuque.com/tokenpocket/guzgqx/vedyn2
  [11]: https://www.yuque.com/tokenpocket/guzgqx/na8gxr

</div>
