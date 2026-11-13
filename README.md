# 日本vps怎么选：一个月到底多少钱、1GB 够不够跑 WordPress、续费会不会涨？（附 JustHost 全套餐价格表）

日本 VPS 的月付下限，日元计价是 ConoHa VPS 的 460 円/月（512MB 档）和 DDPS 的 740 円/月（2GB 档），美元计价的 JustHost 最低 $1.99/月，2GB 内存档落在 $5.53–$7.08/月。多数人不用在最低档上省那几美元——2GB 内存、1–2 核、20–30GB NVMe 这一档，足够跑一个 WordPress 站、几个小服务，或者一台长期在线的中转机。

下面把 JustHost 官网当前展示的全部套餐列全，再讲清日本 VPS 报价里最容易踩的三个口径问题，最后按用途给出选档规则。

> **选购速览**
> 单个网站、测试环境：JustHost Arcturus，1 核 / 2GB / 30GB NVMe，月付 $6.92，一次性付 12 个月折到 $5.53/月。
> 要同时跑几个进程、并发高一点：Double Star，2 核 / 2GB / 20GB NVMe，月付 $7.08，年付 $5.67/月，比 Arcturus 每月只多 16 美分。
> [👉 查看 Arcturus 套餐当前价格](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392)

## JustHost 当前全部 VPS 套餐

JustHost 的套餐命名走的是星名路线，同内存档往往有两三个版本，差别在 CPU 核数、硬盘容量和端口速率上。下表是 tariffs-all 页面上展示的全部套餐，价格单位为美元。

| 套餐 | CPU · 内存 · NVMe | 端口（官网标注的月流量换算） | 月付 | 一次性付 12 个月 | 购买 |
| --- | --- | --- | --- | --- | --- |
| VPS Promo | 1 核 · 512MB · 5GB | 10 Mbps 共享（≈4+TB/月） | $1.99 | 以结账页为准 | [ 选 Promo 档](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1 核 · 1GB · 10GB | 100 Mbps 共享（≈31+TB/月） | $3.81 | $3.05（-20%） | [ 选 New Star](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Double Star | 2 核 · 2GB · 20GB | 200 Mbps 共享（≈62+TB/月） | $7.08 | $5.67（-20%） | [ 选 Double Star](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Bright Star | 4 核 · 4GB · 30GB | 300 Mbps 共享（≈93+TB/月） | $9.80 | $7.84（-20%） | [ 选 Bright Star](https://justhost.asia/en/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Sirius | 1 核 · 1GB · 20GB | 300 Mbps 共享（≈93+TB/月） | $4.85 | $3.88（-20%） | [ 选 Sirius](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 1 核 · 2GB · 30GB | 300 Mbps 共享（≈93+TB/月） | $6.92 | $5.53（-20%） | [ 选 Arcturus](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392) |
| Alpha Centauri | 2 核 · 2GB · 40GB | 400 Mbps 共享（≈124+TB/月） | $8.99 | $7.19（-20%） | [ 选 Alpha Centauri](https://justhost.asia/en/services/vps/tariffs/alpha_centauri?ref=196392) |
| Vega | 2 核 · 4GB · 80GB | 500 Mbps 共享（≈155+TB/月） | $13.44 | $10.75（-20%） | [ 选 Vega](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392) |
| Capella | 4 核 · 4GB · 120GB | 750 Mbps 共享（≈232+TB/月） | $18.30 | $14.64（-20%） | [ 选 Capella](https://justhost.asia/en/services/vps/tariffs/capella?ref=196392) |
| Rigel | 4 核 · 8GB · 200GB | 750 Mbps 共享（≈232+TB/月） | 按页面配置显示 | 按页面配置显示 | [ 查看 Rigel 配置与价格](https://justhost.asia/en/services/vps/tariffs-all?ref=196392) |

New Star、Double Star、Bright Star 这三档的 12 个月折后价，官网注明需要一次订购 3 个月以上才成立。全部价格为美元，结算币种和是否加税以结账页为准。

这张表之外，justhost.asia 的 VPS 主页面还挂着另一组同配置的 “Special” 套餐，标价明显低于表里同名的：“Sirius Special” 1 核 / 1GB / 20GB 报 $2.81/月、年付 $2.25/月；“Arcturus Special” 1 核 / 2GB / 30GB 报 $4.01/月、年付 $3.21/月；“Vega Special” 2 核 / 4GB / 80GB 报 $7.79/月、年付 $6.23/月。同一个品牌两个页面同配置不同价，下单前先看清楚结账页显示的是哪一套。

另外该站还提供自选存储类型的 KVM 套餐，HDD/NVMe/SSD 三种盘可选，IPv4+IPv6 版本从 $2.60/月起（1 核 / 512MB / 5GB HDD，月付 $3.25）；只给 IPv6 地址的版本最低 $1.60/月起。这两类适合有明确 IPv6 需求或者只做内网穿透的人，常规建站不用绕这一圈。

## “不限流量”和“年付 8 折”，日本 VPS 报价的三个口径问题

把日本几家 VPS 的月额直接并排比较，几乎一定会错。原因各不相同。

**さくらのVPS 的 590 円/月，是 12 个月一次性付款折算出来的月额，而且分区。** 官网标的是“月額換算590円/月（年額7,078円）”，同一档 512MB 在页面切换区域时会出现 590、616、641、643、671、698 円等多组数字，2GB 档从 1,594 円到 1,958 円不等，平台没有在页面上把每组数字和东京、大阪、石狩三个区域一一对应。引用时只能说“年付折算、不同区域价格不同，以官网当前显示为准”，不能挑一组当东京价。它的一次性付 12 个月大约省一个月月额，力度和 JustHost 的 -20% 差不多量级，只是计法不同。

**XServer VPS 的 1,265 円〜，是 36 个月契约下的月额。** 官网脚注写得很清楚：XServer VPS 为 36 个月契约时、XServer VPS クラウド为 12 个月契约时的月额。拿这个数字去和月付产品并列，差距会被放大。它对应的配置是 2GB / 3 核 / 50GB NVMe，同页 4GB 档是 2,035 円〜、8GB 档 3,850 円〜，全部含税。

**ConoHa VPS 的 460 円/月，标着“时间课金 38% OFF”。** 同一页面上还挂着多组更低的数字，512MB 档最低到 326 円、2GB 档到 1,741 円，对应更长的计费周期或更大的折扣档。按标称月额引用没问题，但别把 326 円当成月付价。

JustHost 的低价挂在“一次性付 12 个月”这个条件上，属于付款周期折扣。官网套餐页没有单列续费价，续费时按什么价格扣款，要在结账页确认账单周期和金额。想先把年付的账算清楚，可以直接看对应套餐页面：

[👉 用 12 个月年付价开通 Double Star](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392)

还要提醒一句“不限流量”。JustHost 各档写的是 Unmetered port，括号里注明 fair-share，也就是端口速率共享、不按流量计费，官网自己给出的换算是 100 Mbps 约 31+TB/月、300 Mbps 约 93+TB/月。这跟“带宽随便跑满”不是一回事：Promo 档那个 10 Mbps 端口，按满速跑一个月也就 4TB 出头，跑网站会明显慢。

## 1GB、2GB、4GB 分别能干什么

判断标准其实很简单，看内存而不是看核数。

**512MB：只适合测试和轻量脚本。** Promo 档 5GB 盘，装完系统剩不下多少，跑个静态页、做个跳板、验证一下机房线路就到顶了。10 Mbps 端口决定了它不适合对外提供网页服务。

**1GB：静态站和小型动态站。** New Star（10GB 盘）和 Sirius（20GB 盘）都在这档。10GB 盘是硬约束：主流 Linux 发行版装完占 3–5GB，再装个数据库和运行环境就紧张了。同样 1GB 内存，Sirius 多 10GB 盘、端口从 100 Mbps 提到 300 Mbps，月付只贵 $1.04，除非预算卡死在 $3 出头，否则没必要选 New Star。

**2GB：单个 WordPress 站、轻量 API、小型数据库。** 这是最实用的分界线。Arcturus（1 核 / 2GB / 30GB，$6.92）和 Double Star（2 核 / 2GB / 20GB，$7.08）差 16 美分，一个多一核、一个多 10GB 盘。跑 WordPress 且装了缓存插件，1 核够用，30GB 盘更值；要同时跑 PHP-FPM、数据库和定时任务，多一个核更稳。Alpha Centauri（2 核 / 2GB / 40GB，$8.99）是这两者的合并版，多花不到 2 美元把核和盘都补齐。

**4GB 及以上：多站点、容器、编译和构建。** Bright Star（4 核 / 4GB / 30GB，$9.80）核多盘小，适合 CPU 密集但数据不多的场景；Vega（2 核 / 4GB / 80GB，$13.44）盘大，适合跑数据库或者放素材；Capella（4 核 / 4GB / 120GB，$18.30）才算真正宽裕。8GB 的 Rigel 已经超出个人建站的需求范围，除非要跑 Elasticsearch、多个 Docker 容器或者做数据处理。

一句话规则：只放静态文件，1GB 起步；跑 WordPress 或有数据库，2GB 起步；一台机器上要跑三个以上服务，直接看 4GB。核数比内存更不值钱，同价位优先选内存大的。

## 机房、线路与虚拟化

JustHost 官网页面标注的是 KVM 虚拟化、NVMe 阵列，以及防护主要类型 DDoS 攻击，页面上没有逐项列出机房清单。

第三方测评（2026 年 4 月发布）测的是东京 TYO2 机房，硬件为 Intel Xeon Silver 4210R、KVM 虚拟化、同时给 IPv4 和 IPv6，Geekbench 6 单核 689–750、多核 1185–1271，4K 随机读写约 40MB/s、IOPS 约 1 万。测评作者还提到支持一键切换数据中心和一键切换 IP，并把三网回程描述为走国际线路、部分绕美国，高峰期表现一般，建议配合中转使用。这些是第三方实测结论，不是官方承诺，线路和服务方策略都会变，只能当参考。

作为对照，日本本土几家在机房上是明牌：さくらのVPS 有东京、大阪、北海道石狩三个区域，数据中心全部自社运营，技术人员 24 小时 365 天驻场，国内主要 IX 和大型 ISP 直连，回线是 100 Mbps 共享、转送量无制限；DDPS 的 VPS 落在东京 Equinix TY8，配专用 IPv4 一个，追加 IPv4 每月 175 円；ConoHa VPS 提供私有网络 VLAN、DSR 方式负载均衡器（1,100 円/月）和自动 failover，适合把 WEB 和 DB 拆开部署。

多台分离部署这件事，JustHost 的资料里没有对应的私有网络或负载均衡说明，需要多机内网互联的话要单独向客服确认。先看清全部套餐再决定：

[👉 查看 JustHost 全部 VPS 套餐](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)

## 和日本本土几家摆在一起看

| 品牌 | 最低月额 | 最低配 | 存储 | 转送量 | 试用 / 最低期间 |
| --- | --- | --- | --- | --- | --- |
| さくらのVPS | 590 円/月（12 个月一括的月额换算） | 512MB / 1 核 | SSD 25GB | 无制限 | 信用卡支付 2 周免费（上限 2 台）；最低利用 3 个月 |
| XServer VPS | 1,265 円〜（36 个月契约月额） | 2GB / 3 核 | NVMe 50GB | — | — |
| ConoHa VPS | 460 円/月 | 512MB / 1 核 | SSD 30GB | 0 円・无制限 | — |
| DDPS | 740 円/月 | 2GB / 1 核 | NVMe 40GB | — | — |

几个值得注意的差别。さくらのVPS 的 SLA 只对 4GB 以上套餐生效，512MB、1GB、2GB 三档不提供品质保证，而且要留意它最低利用 3 个月，加上信用卡 2 周免费试用最多 2 台——试错成本比看上去低，但中途退出不划算。XServer VPS 全系 AMD EPYC + NVMe，官方自社调价（2024 年 11 月 18 日）称 CPU 处理性能是第二名的约 3.7 倍、随机读约 5.8 倍，这是厂商自测口径；另有第三方媒体在 2026 年 9 月 9 日逐家核对官网后指出，XServer VPS 与シンVPS 已于 2026 年 9 月 1 日调价，实际价格以官网当前页为准。ConoHa 的强项是网络功能齐全，LB 单独计费 1,100 円/月，官方给的构成例是 WEB 2GB×2 + DB 2GB×2 + LB×1 合计月额 6,136 円。

JustHost 的位置在中间偏低价一段：$5.53/月（约 2GB 档年付折算）对 460–740 円这一档的日本本土最低配，内存给得更多；但它没有本土厂商那种自营机房和 SLA 承诺的叙事，硬盘也偏小，20–30GB 是常态。

## 常见问题

**日本 VPS 最低多少钱一个月？**
已核验的最低月付：ConoHa VPS 512MB 档 460 円/月、さくらのVPS 512MB 档年付折算 590 円/月、DDPS 2GB 档 740 円/月；美元计价的 JustHost Promo 档 $1.99/月。这些是不同计费口径下的标价，不能直接排序。

**月付和年付差多少？**
JustHost 一次性付 12 个月比月付低 20%，Arcturus 从 $6.92 降到 $5.53。さくらのVPS 一次性付 12 个月大约省一个月月额（512MB 档年额 7,078 円，折算 590 円/月）。XServer VPS 的 1,265 円是 36 个月契约价，月付价会更高。

**1GB 够不够跑 WordPress？**
能跑，但盘要先看清楚。New Star 只有 10GB，装完系统和运行环境后空间很紧；Sirius 给到 20GB，同内存贵 $1.04，更适合实际建站。有插件、有图片、数据库还会长，2GB 档更省心。

**最低利用期间和试用怎么算？**
さくらのVPS 最低利用 3 个月，信用卡支付可先免费试用 2 周、上限 2 台。JustHost 的 12 个月折扣价要求一次订购 12 个月，New Star、Double Star、Bright Star 另有“订购 3 个月以上”的前置条件；页面没有标注免费试用。

**续费会不会涨？**
JustHost 套餐页只列当前价格，没有单列续费价，续费金额需要在结账页确认。日本本土几家里，ConoHa 页面上“更新時”的价格与标价一致，XServer 和シンVPS 已在 2026 年 9 月调过一次价，长期项目最好把“可能涨价”写进预算。

## 按场景选，别按参数选

只做测试、放静态页面、当跳板：JustHost Promo（$1.99/月）够用，但 10 Mbps 端口别指望它扛访问；想要快一点就上 Sirius，$3.88/月的年付价换 300 Mbps 端口和 20GB 盘。

跑一个 WordPress 站、小型 API：Arcturus，$6.92/月，年付 $5.53/月。要多一点并发就加 16 美分上 Double Star，要盘更大就上 Alpha Centauri。

多站点、容器、构建环境：Vega（2 核 / 4GB / 80GB，$13.44）起步，Capella（4 核 / 4GB / 120GB，$18.30）更宽裕。需要 WEB/DB 分离和负载均衡，这一层 JustHost 没有公开方案，去看 ConoHa 那类提供私有网络和 LB 的产品更合适。

下单前确认两件事：结账页显示的是哪一套价格（tariffs-all 页还是 Special 促销页），以及账单周期与续费金额。这两项都确认了，再付款。

[👉 按年付价开通 Arcturus](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392)
