# 1Gbps VPS推荐：月付十几块的千兆口能用吗？超流量限速多少、退款怎么扣、哪档才够用（附全部机房套餐与价格表）

如果你的用途是放一个小站、跑点轻量业务，或者只想要个便宜的千兆口跑国际流量，Akile 香港的 HKLite-Mini 是这批套餐里最省事的一台：1 核 1G 内存配 10GB 硬盘，每月 2.5TB 流量，1Gbps 端口，¥24.99。它不适合的场景也很明确——指望中国大陆三网直连、晚高峰不掉速的，这台给不了。

预算再压一压，日本 JPHyper-Lite 给到 2.5Gbps 端口和 2GB 内存，只要 ¥14.99，代价是硬盘只有 10GB，官方也没写明这个型号走哪条路由。

下面把 Akile 各机房在售的套餐全部列出来，再讲三件套餐表上看不到的事：端口标称和实际速度差在哪、流量跑完是限速还是停机、退款到底怎么扣。

## 选购速览

> **大多数人的答案：香港 HKLite-Mini**，1 核 1G / 10GB SSD / 2.5TB 月流量 / 1Gbps，**¥24.99/月**。同价位的新加坡 SGLite-Mini 配置一模一样，流量却只有 1TB，香港这台多给 1.5TB。硬盘 10GB 是硬约束，要跑数据库或装大应用得往上选 HKLite-Starter（5TB，¥43.74）。
>
> **只想花最少的钱摸到千兆口：洛杉矶 LAXLite-One**，1 核 1G / 5GB / 1TB / 5Gbps，年付 ¥106.56，折合 ¥8.88/月。

👉 [查看 Akile 香港机房套餐与当前价格](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)

## Akile 全部在售套餐与价格

Akile 的产品分三条线：**流量型**（大流量、高带宽、低价格，主打流媒体和国际流量）、**轻量型**（流量少、带宽低，但更稳，适合建站）、**独立服务器**（目前只有香港，起步 3349 元/月）。下表是流量型各机房在售的套餐，也是搜「1Gbps VPS」时真正该看的那一批。

以下价格整理自公开测评资料与产品页，商家会随活动调整，下单前以结账页金额为准。

### 香港 HKLite

| 套餐 | 配置（CPU·内存·硬盘） | 月流量 | 端口 | 月付 | 购买 |
| --- | --- | --- | --- | --- | --- |
| HKLite-One | 1核 · 1GB · 5GB SSD | 1TB | 5Gbps | ¥9.9（常年缺货） | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| HKLite-Mini | 1核 · 1GB · 10GB SSD | 2.5TB | 1Gbps | ¥24.99 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| HKLite-Pre-Mini | 2核 · 4GB · 30GB SSD | 2.5TB | 5Gbps | ¥39.99 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| HKLite-Starter | 1核 · 1GB · 10GB SSD | 5TB | 1Gbps | ¥43.74 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| HKLite-Standard | 2核 · 1GB · 20GB SSD | 10TB | 2Gbps | ¥99.99 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| HKLite-Pro | 2核 · 2GB · 20GB SSD | 30TB | 2Gbps | ¥237.49 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |

香港这条线的价格阶梯基本按流量走：2.5TB、5TB、10TB、30TB 拉开四档。¥9.9 的 HKLite-One 经常没货，实际能买到的最低档是 ¥24.99 的 Mini。

### 新加坡 SGLite

| 套餐 | 配置（CPU·内存·硬盘） | 月流量 | 端口 | 月付 | 购买 |
| --- | --- | --- | --- | --- | --- |
| SGLite-One | 1核 · 1GB · 5GB SSD | 1TB | 500Mbps | ¥10.42 起 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SGLite-Mini | 1核 · 1GB · 5GB SSD | 1TB | 1Gbps | ¥24.99 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SGLite-Starter | 1核 · 1GB · 10GB SSD | 3TB | 1Gbps | ¥43.74 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SGLite-Standard | 1核 · 1GB · 10GB SSD | 6TB | 1.5Gbps | ¥87.49 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |

新加坡的定价和香港咬得很紧，但配置上的诚意差一截：同样是 ¥24.99，香港给 10GB 硬盘和 2.5TB 流量，新加坡只有 5GB 和 1TB；同样是 ¥43.74，香港 5TB，新加坡 3TB。除非你的用户在东南亚，否则香港更划算。

### 日本 JPHyper 与 JPPro

| 套餐 | 配置（CPU·内存·硬盘） | 月流量 | 端口 | 月付 | 购买 |
| --- | --- | --- | --- | --- | --- |
| JPHyper-Lite | 1核 · 2GB · 10GB SSD | 1TB | 2.5Gbps | ¥14.99 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPHyper-Mini | 2核 · 2GB · 10GB SSD | 2.5TB | 2.5Gbps | ¥25.99 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPPro-Light | 1核 · 1GB · 10GB SSD | 700GB | 300Mbps | ¥24.99 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPPro-Starter | 1核 · 1GB · 20GB SSD | 500GB | 1Gbps | ¥37.35 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPPro-Standard | 1核 · 1GB · 20GB SSD | 1TB | 1.2Gbps | ¥62.25 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |

日本这条线有个反直觉的地方：**JPPro 全线比 JPHyper 贵、带宽低、流量少**。JPPro-Light 卖 ¥24.99 只给 300Mbps 和 700GB，比 ¥14.99 的 JPHyper-Lite（2.5Gbps、1TB）差了一大截。官方套餐说明写日本系列「包含直连和路由调优型号」，但没写清哪个型号对应哪种路由。如果 JPPro 的高价买的是线路，那官网该说明白；只按带宽和流量看，JPHyper 完胜。

### 洛杉矶 LAXLite 与 LAXPro

| 套餐 | 配置（CPU·内存·硬盘） | 月流量 | 端口 | 月付 | 购买 |
| --- | --- | --- | --- | --- | --- |
| LAXLite-One | 1核 · 1GB · 5GB SSD | 1TB | 5Gbps | ¥8.88 起（年付 ¥106.56） | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| LAXLite-Mini | 1核 · 2GB · 10GB SSD | 2TB | 5Gbps | ¥15.99 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| LAXLite-Starter | 2核 · 2GB · 10GB SSD | 5TB | 5Gbps | ¥34.99 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| LAXPro-Light | 1核 · 1GB · 20GB SSD | 300GB | 300Mbps | ¥43.74 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| LAXPro-Standard | 1核 · 1GB · 20GB SSD | 1TB | 500Mbps | ¥74.99 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |

洛杉矶是 Akile 最便宜的机房。LAXLite-One 的 ¥8.88 是年付 ¥106.56 折算出来的月价，月付实际金额要按结账页看。LAXPro 两档同样是「贵、慢、流量少」，官方资料没写它和 LAXLite 在网络上的差别，买之前务必确认。

### 英国与美国住宅双 ISP

这两个系列的资料来自较早的公开测评，价格变动概率比上面几个机房大。

| 套餐 | 配置（CPU·内存·硬盘） | 月流量 | 端口 | 月付 | 购买 |
| --- | --- | --- | --- | --- | --- |
| UK Lite2 入门 | 1核 · 1GB · 10GB SSD | 1TB | 500Mbps | ¥19.99 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| UK Lite2 高配 | 2核 · 2GB · — | — | 1Gbps | ¥87.49 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| LAX 住宅双ISP 入门 | 1核 · 2GB · 10GB SSD | 500GB | 1Gbps | ¥49.99 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| LAX 住宅双ISP 中档 | 2核 · 2GB · 20GB SSD | 1TB | 1Gbps | ¥89.99 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| LAX 住宅双ISP 高档 | 2核 · 4GB · 20GB SSD | 2TB | 1Gbps | ¥169.99 | [查看](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |

两处需要留意。英国 1Gbps 档的硬盘和流量没有公开列出，得在结账页确认。美国住宅双 ISP 系列的带宽描述在同一份资料里出现过 1Gbps 和 10Gbps 两种写法，下单前请核对清楚到底是哪个。

## 1Gbps 端口能跑多快，取决于两段链路

1Gbps 的理论峰值约 125MB/s，这是端口规格决定的，和商家无关。能不能跑到，要拆成两段看。

**机器出口这一段，Akile 给的是真货。** 一份针对英国 500Mbps 档的第三方测评里，speedtest 下载跑到 475.79Mbps、上传 499.09Mbps，基本贴着端口标称值。端口没有虚标。

**跨境这一段，就不是端口能决定的了。** 同一份测评测了大陆三网的去程：上海电信绕美国、德国、比利时才到英国，广东移动绕香港和日本。这就是低价大带宽的常态——机房给足了国际出口，但没为大陆访问买优化线路。

所以「标 1Gbps 实际跑 50Mbps」这种事，原因通常在路径上，不在端口上。白天测速漂亮、晚上八点腰斩，也是同一个道理。资料里没有任何测试数据能说明 Akile 各机房在晚高峰的具体表现，这个只能你自己测。

另外，Akile 没有公开标注各套餐的带宽是独享还是共享。端口规格之外的那部分，要靠实测。

## 流量跑完不会停机，会降到 10Mbps

这是 Akile 设计里比较务实的一点，也是很多套餐表不写的地方。

流量超出后，机器继续跑，速度被限制到 **10Mbps**，约 1.25MB/s。香港的流量型是这样，英国的档位也是这样。1.25MB/s 跑一个纯文字博客、收发邮件、SSH 管理完全够用；跑视频、做大文件分发、给多人共用，基本废掉。

想恢复满速得买流量重置包。英国档 ¥14，美国住宅档 ¥24.99，各产品定价不同，超量前先看清楚自己那条线的重置价。

作为对照，市面上有新加坡商家在流量超限后直接把速度压到 20KB/s，约 0.16Mbps，那已经等于断网。Akile 的 10Mbps 至少还能维持基本的网页访问和后台操作，这个差别在实际使用里很明显。

## 退款不是「24 小时无条件」，是阶梯扣费

这一节值得逐字看完，它直接决定你的试错成本。

Akile 轻量型服务器的退款规则按购买天数分档：

1. 新购 3 天内，按购买价格退 80%
2. 3 天到 7 天，退 50%
3. 7 天到 10 天，退 20%
4. 超过 10 天，无法退款

另外还有三条限制：退款**只退到账户余额**，不原路退回支付渠道；一个自然月内最多退 3 台；同一节点一个自然月内最多退 1 台。删除服务器会自动按上述规则退到余额。

这个条款的含义很直接：买一台 ¥24.99 的 HKLite-Mini，第二天不满意申请退，拿回的是 ¥19.99 的余额，不是现金。想「买来测一晚，不行就全额退」的玩法在 Akile 这里行不通。

需要说明的是，另有一份较早的测评把退款条件写成「开通 24 小时内且已用流量不超过 5GB 全额退款」，和上面的阶梯口径不一致。条款可能调整过，最终以你下单时订单页显示的那一版为准。买之前花三十秒看完那段文字，比事后争论有用。

## 低价的另一面：广播 IP 与 DNS 解锁

Akile 流量型服务器的订单页上有一句原话：**「我们此节点都是广播ip，谢绝以ip位置为理由退款」**。

这句话解释了它为什么便宜，也解释了它的流媒体解锁是怎么做的。Akile 不给你一个当地原生 IP，而是在网络层内置自己的 DNS，把流媒体请求拦下来转发，流媒体网站看到的是 Akile 提供的原生 IP，不是你服务器上那个 IP。

两个后果值得提前知道：

- 你自己改 DNS、或者用加密 DNS，解锁可能失效。
- 你需要 IP 本身具备住宅或原生属性（做账号运营、电商后台、社交平台登录），广播 IP 满足不了，这类需求得看美国住宅双 ISP 那条线，¥49.99 起。

把「能解锁 Netflix」和「IP 是原生 IP」当成一回事，是买这类机器最常见的误判。

## 按用途选档：哪档够用，哪档纯属浪费

**个人博客 / 静态站。** 香港 HKLite-Mini ¥24.99。WordPress 加几十张图片，10GB 硬盘要省着用，2.5TB 流量对日 PV 几千的站绰绰有余。图片多的站直接跳过 5GB 和 10GB 硬盘的档位，硬盘会是第一个瓶颈。

**外贸站 / 面向东南亚的业务。** 新加坡 SGLite-Starter ¥43.74（3TB / 1Gbps），流量再大往上选 SGLite-Standard ¥87.49（6TB / 1.5Gbps）。如果你的客户主要在中国大陆，这两档的跨境路径不占优势，先测再买。

**日区内容 / 日本业务。** JPHyper-Lite ¥14.99 是全部套餐里参数最漂亮的一台：2.5Gbps 端口、2GB 内存、1TB 流量。硬盘只有 10GB，装系统加环境就去了大半。

**跑量下载 / 中转 / 多人共用。** 按流量选，别看 CPU。5TB 用 HKLite-Starter ¥43.74，10TB 用 HKLite-Standard ¥99.99，30TB 用 HKLite-Pro ¥237.49。

**明显过剩的一档：HKLite-Pro。** 2 核 2G 内存配 30TB 流量，这个组合本身就矛盾——真正每月跑十几 TB 的业务，2GB 内存早就撑不住了。除非你只拿它做纯中转，不跑任何应用。

**明显不够用的一档：所有 5GB 硬盘的入门款。** SGLite-One、SGLite-Mini、LAXLite-One 都是 5GB。装完系统剩不了多少，放个静态页可以，建站会很快撞墙。

## 和另外两家 1Gbps 方案比，Akile 站在哪个位置

同为 1Gbps，价差能到二十几倍，原因在线路和流量额度，不在端口。

| 方案 | 配置 | 端口 | 月流量 | 月付价 |
| --- | --- | --- | --- | --- |
| Akile 香港 HKLite-Mini | 1核 · 1GB · 10GB | 1Gbps | 2.5TB | ¥24.99 |
| LisaHost 新加坡豪华 | 4核 · 4GB · 80GB | 1Gbps | 20TB | ¥188 |
| LisaHost 美国 4837 豪华 | 4核 · 4GB · 80GB | 1Gbps | 20TB | ¥300 |
| GoMami 新加坡 Air | 4核 · 8GB · 80GB | 1Gbps | 2TB | $89 |

以上为公开资料中的历史报价，未在今日复核，可能已经变动。

配置差距摆在那，但真正的分野是线路定位。LisaHost 新加坡线官方写的是「非大陆直连优化」，靠香港或日本中转；GoMami 新加坡走三网各自精品回程。Akile 的低价档不承诺大陆优化，走广播 IP 加国际 BGP。

选择就变得很简单：**要中国大陆访问稳定，加预算买线路；要便宜的端口和流量跑国际业务，Akile 这一档更合适。** 拿 Akile 的 ¥24.99 去比 LisaHost 的 ¥188，比的是两个不同品类的东西。

Akile 在这批里的独特之处是香港和洛杉矶给到 2Gbps、5Gbps 端口，价格还在两位数。想用千兆以上端口又不想付优化线路的钱，可选项不多。

👉 [在 Akile 挑一台香港或洛杉矶的 5Gbps 档试试](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)

## 常见问题

**1Gbps 端口能跑满吗？**

机器出口这一段通常能给足，第三方测评里 500Mbps 档跑出过 475.79Mbps 下载、499.09Mbps 上传。中国大陆访问时，瓶颈在跨境路由，不在端口。你的城市、你的运营商、你打开的时间，三个变量里有两个是商家控制不了的。

**月流量 1TB 够建站吗？**

日 PV 两千的文字博客，一个月大概几十 GB，1TB 够用很久。吃流量的是图片、视频和下载文件。比起流量，5GB 硬盘更容易先出问题。

**便宜的 1Gbps 为什么不能建面向国内的站？**

这个价格买的是端口和流量。回程线路是另一笔成本，商家没在这上面花钱，路径就会绕。要国内访问快，得找明确承诺三网优化回程的产品，价格通常高一个数量级。

**年付一定比月付划算吗？**

资料里唯一给出年付总价的是洛杉矶 LAXLite-One（¥106.56/年，折合 ¥8.88/月），其余档位的年付价和续费价都没有公开标注。年付前请在结账页确认两件事：年付总额是多少，第二年续费按什么价。

**流量跑完会停机吗？**

不停机，限速 10Mbps，约 1.25MB/s。想恢复满速买流量重置包，英国档 ¥14、美国住宅档 ¥24.99，各产品不同。

## 下单前的两条规则

按需求对号：

- 只放一个博客或小站，想要香港低延迟 → 香港 HKLite-Mini，¥24.99
- 跑日区内容，预算第一位 → 日本 JPHyper-Lite，¥14.99
- 每月跑几 TB 下载或中转 → 5TB 选 HKLite-Starter ¥43.74，10TB 选 HKLite-Standard ¥99.99
- 需要 IP 本身是原生美国住宅 → LAX 住宅双 ISP，¥49.99 起
- 需要中国大陆三网直连的稳定访问 → Akile 这几档不合适，别在这上面省钱

下单前还有两件事：确认跳转后的地址里 `aff_code` 参数完整带到了结账页；先买最短周期，用商家给的测试 IP 在你所在城市晚上八点到十一点测一轮，跑不满就按退款规则处理，别直接上年付。

👉 [打开 Akile 挑一台最短周期，测完晚高峰再决定续不续](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)
