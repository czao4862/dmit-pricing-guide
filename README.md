# DMIT 多少钱？洛杉矶 / 香港 / 东京三机房完整套餐价格表：Premium、Eyeball、Tier 1 怎么区分，谁最适合你，最低多少起步（附全配置对比）

VPS 圈子里搜 DMIT，很多人就想知道一件事：**这东西到底多少钱？**

进官网一看，三个机房，每个机房三条线，每条线七八个配置……TINY、Pocket、WEE，命名风格偏理工男，看完比进去之前更晕。

我把三大机房所有套餐价格都整理出来了，顺便说说几个容易踩的判断误区，帮你跳过那些"看了也没用"的信息，直接找到适合自己的方案。

---

## DMIT 是什么——两句话说完

DMIT（dmit.io）是 2018 年开始运营的 VPS 商家，美国纽约注册，目前主要跑三个数据中心：**洛杉矶（LAX）、香港（HKG）、东京（TYO）**。全系 KVM 虚拟化，AMD EPYC 处理器，企业级 SSD，支持支付宝、微信和 PayPal 付款。

国内用户关注它的理由其实很简单：CN2 GIA、CMIN2、AS9929 这些对中国大陆友好的线路，它是认真走的，不是贴标签糊弄人。

---

## 产品线逻辑：三系列的区别是什么

三个机房各有三条线，搞懂这个，价格表才看得明白：

| 系列 | 网络质量定位 | 适合谁 |
|------|------------|--------|
| **Premium** | CN2 GIA + 三网优化，旗舰级线路 | 对国内访问速度有硬要求的用户 |
| **Eyeball** | CMIN2 为主，均衡中国优化 | 同价格但想要更多流量的用户 |
| **Tier 1** | 国际线路，无中国特殊优化 | 纯国际用途，或预算最优先的用户 |

顺便提一嘴：Premium 和 Eyeball 在洛杉矶是同价的。区别是 Premium 流量少一点但线路更好，Eyeball 流量多出一截但线路差一档。晚高峰体验的差异，比平时明显。

硬件这块三条线差不多：全系 AMD EPYC，不是那种跑个宝塔面板都要卡半天的老 Intel E5。

---

## 洛杉矶套餐价格（最全整理）

洛杉矶是 DMIT 的主力机房，套餐最全，也是大多数人第一次选的出发点。

### Premium — 三网 CN2 GIA

电信联通去程 CN2 GIA，移动走 CMIN2，三网回程 CN2 GIA。实测晚高峰延迟稳在 150ms 上下，不会出现那种夜里开个网页像在走老式拨号的情况。

| 套餐 | CPU / 内存 | 存储 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----------|------|--------|------|------|------|
| TINY | 1核 2GB | 20GB SSD | 1000GB | 1Gbps | $37.99/季 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=100) |
| Pocket | 2核 2GB | 40GB SSD | 1500GB | 4Gbps | $56.70/季 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=137) |
| STARTER | 2核 2GB | 80GB SSD | 3000GB | 10Gbps | $38.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=56) |
| MINI | 4核 4GB | 80GB SSD | 5000GB | 10Gbps | $76.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=58) |
| MICRO | 4核 4GB | 160GB SSD | 7000GB | 10Gbps | $99.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=81) |
| MEDIUM | 6核 8GB | 160GB SSD | 15000GB | 10Gbps | $219.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=82) |
| LARGE | 8核 16GB | 320GB SSD | 25000GB | 10Gbps | $2759.40/半年 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=61) |
| GIANT | 12核 24GB | 640GB SSD | 50000GB | 10Gbps | $839.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=98) |

还有不限流量版，带宽锁死，适合长期跑小流量服务：

| 套餐 | CPU / 内存 | 存储 | 独享带宽 | 价格 | 购买 |
|------|-----------|------|---------|------|------|
| uMINI | 2核 2GB | 40GB SSD | 30Mbps | $239.99/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=62) |
| uMICRO | 4核 8GB | 80GB SSD | 50Mbps | $399.99/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=64) |
| uMEDIUM | 4核 8GB | 120GB SSD | 100Mbps | $799.99/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=65) |
| uLARGE | 8核 16GB | 240GB SSD | 200Mbps | $1399.99/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=66) |

### Eyeball — CMIN2 三网回程

价格和 Premium 完全一样，但流量给得更多（比如 STARTER 是 5000GB，Premium 是 3000GB）。对不追求晚高峰极致稳定的场景，Eyeball 更划算一点。

| 套餐 | CPU / 内存 | 存储 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----------|------|--------|------|------|------|
| TINY | 1核 2GB | 20GB SSD | 1500GB | 2Gbps | $37.99/季 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=189) |
| Pocket | 2核 2GB | 40GB SSD | 3000GB | 4Gbps | $56.70/季 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=190) |
| STARTER | 2核 2GB | 80GB SSD | 5000GB | 10Gbps | $38.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=191) |
| MINI | 4核 4GB | 80GB SSD | 10000GB | 10Gbps | $76.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=192) |
| MICRO | 4核 4GB | 160GB SSD | 14000GB | 10Gbps | $99.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=193) |
| MEDIUM | 6核 8GB | 160GB SSD | 30000GB | 10Gbps | $219.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=194) |

### Tier 1 — 国际线路，$6.90/月起

没有中国方向优化，但流量给得很大方，$6.90/月进门。圈内口碑里被提到最多的就是这个价位——跑个人代理节点或者小站，成本够低、机器够稳。

| 套餐 | CPU / 内存 | 存储 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----------|------|--------|------|------|------|
| WEE | 1核 1GB | 20GB SSD | 1000GB | 1Gbps | $36.90/年 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=71) |
| TINY | 1核 1GB | 20GB SSD | 2000GB | 1Gbps | $6.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=116) |
| STARTER | 1核 2GB | 40GB SSD | 4000GB | 1Gbps | $12.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=117) |
| MINI | 2核 2GB | 60GB SSD | 8000GB | 1Gbps | $21.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=118) |
| MICRO | 4核 4GB | 80GB SSD | 16000GB | 1Gbps | $32.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=119) |
| MEDIUM | 4核 8GB | 160GB SSD | 32000GB | 1Gbps | $49.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=120) |
| LARGE | 8核 16GB | 320GB SSD | 64000GB | 1Gbps | $99.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=121) |
| GIANT | 8核 24GB | 640GB SSD | 128000GB | 1Gbps | $199.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=122) |

👉 [以当前优惠价直接购买 DMIT 洛杉矶套餐](https://www.dmit.io/aff.php?aff=13832)

---

## 香港机房价格表（HKG）

香港机房的核心卖点就是延迟。到国内大城市基本在 30-60ms，这个数字洛杉矶是做不到的。

代价也很直接：同配置香港比洛杉矶贵 3-5 倍，流量也少不少。如果你的用户不集中在国内，或者延迟 150ms 完全够用，香港机房溢价对你意义不大。

### Premium — 香港 CN2 GIA

电信双向 CN2 GIA，联通 AS9929，移动 CMI。三个机房里线路体验最好的一条，价格也是最贵的。

| 套餐 | CPU / 内存 | 存储 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----------|------|--------|------|------|------|
| TINY | 1核 1GB | 20GB SSD | 500GB | 1Gbps | $39.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=123) |
| STARTER | 1核 2GB | 40GB SSD | 1000GB | 1Gbps | $79.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=124) |
| MINI | 2核 2GB | 60GB SSD | 1500GB | 1Gbps | $119.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=125) |
| MICRO | 4核 4GB | 80GB SSD | 2000GB | 1Gbps | $159.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=126) |
| MEDIUM | 4核 8GB | 160GB SSD | 2500GB | 1Gbps | $179.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=127) |
| LARGE | 8核 16GB | 320GB SSD | 3000GB | 1Gbps | $239.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=128) |
| GIANT | 8核 24GB | 640GB SSD | 6000GB | 1Gbps | $499.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=129) |

### Eyeball — 香港 CMI 直连

移动双程 CMI，联通电信绕日回程。移动用户体验好，电信用户买之前建议先 ping 一下到自己城市的延迟。

| 套餐 | CPU / 内存 | 存储 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----------|------|--------|------|------|------|
| TINYv2 | 1核 1GB | 20GB SSD | 1000GB | 1Gbps | $29.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=210) |
| STARTERv2 | 1核 2GB | 40GB SSD | 2000GB | 2Gbps | $59.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=211) |
| MINIv2 | 2核 2GB | 60GB SSD | 3000GB | 2Gbps | $89.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=212) |
| MICROv2 | 4核 4GB | 80GB SSD | 4000GB | 4Gbps | $129.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=213) |
| MEDIUMv2 | 4核 8GB | 160GB SSD | 6000GB | 4Gbps | $199.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=214) |
| LARGEv2 | 8核 16GB | 320GB SSD | 12000GB | 4Gbps | $389.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=215) |
| GIANTv2 | 8核 24GB | 640GB SSD | 24000GB | 4Gbps | $789.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=216) |

### Tier 1 — 香港国际线路

和洛杉矶 Tier 1 同价，机房在香港。适合单纯要个香港 IP，不在乎线路质量的场景。

| 套餐 | CPU / 内存 | 存储 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----------|------|--------|------|------|------|
| WEE | 1核 1GB | 20GB SSD | 1000GB | 1Gbps | $36.90/年 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=197) |
| TINY | 1核 1GB | 20GB SSD | 2000GB | 1Gbps | $6.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=198) |
| STARTER | 1核 2GB | 40GB SSD | 4000GB | 1Gbps | $12.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=199) |
| MINI | 2核 2GB | 60GB SSD | 8000GB | 1Gbps | $21.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=200) |
| MICRO | 4核 4GB | 80GB SSD | 16000GB | 1Gbps | $32.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=201) |
| MEDIUM | 4核 8GB | 160GB SSD | 32000GB | 1Gbps | $49.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=202) |
| LARGE | 8核 16GB | 320GB SSD | 64000GB | 1Gbps | $99.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=203) |
| GIANT | 8核 24GB | 640GB SSD | 128000GB | 1Gbps | $199.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=204) |

---

## 东京机房价格表（TYO）

东京是三个机房里最晚出来的，主要场景是需要日本 IP，或者做面向日韩用户业务的人。到国内延迟大概 60-100ms，介于洛杉矶和香港之间。

### Premium — 东京 CN2 GIA

电信 CN2 GIA、联通 AS9929、移动 CMI。亚太方向延迟表现不错，想解锁 NHK、AbemaTV 这类日本内容也有人在用这套配置。

| 套餐 | CPU / 内存 | 存储 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----------|------|--------|------|------|------|
| TINY | 1核 1GB | 20GB SSD | 500GB | 1Gbps | $21.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=138) |
| STARTER | 1核 2GB | 40GB SSD | 1000GB | 1Gbps | $39.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=139) |
| MINI | 2核 2GB | 60GB SSD | 2000GB | 1Gbps | $79.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=140) |
| MICRO | 4核 4GB | 80GB SSD | 4000GB | 1Gbps | $159.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=141) |
| MEDIUM | 4核 8GB | 160GB SSD | 5000GB | 1Gbps | $259.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=142) |
| LARGE | 8核 16GB | 320GB SSD | 8000GB | 1Gbps | $429.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=143) |
| GIANT | 8核 24GB | 640GB SSD | 15000GB | 1Gbps | $799.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=144) |

### Eyeball — 东京均衡线路

| 套餐 | CPU / 内存 | 存储 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----------|------|--------|------|------|------|
| TINY | 1核 1GB | 20GB SSD | 1000GB | 1Gbps | $25.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=221) |
| STARTER | 1核 2GB | 40GB SSD | 2000GB | 2Gbps | $55.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=222) |
| MINI | 2核 2GB | 60GB SSD | 3000GB | 2Gbps | $85.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=223) |
| MICRO | 4核 4GB | 80GB SSD | 4000GB | 4Gbps | $119.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=224) |
| MEDIUM | 4核 8GB | 160GB SSD | 6000GB | 4Gbps | $179.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=225) |
| LARGE | 8核 16GB | 320GB SSD | 12000GB | 4Gbps | $369.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=226) |
| GIANT | 8核 24GB | 640GB SSD | 24000GB | 4Gbps | $749.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=227) |

### Tier 1 — 东京国际线路

| 套餐 | CPU / 内存 | 存储 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----------|------|--------|------|------|------|
| WEE | 1核 1GB | 20GB SSD | 1000GB | 1Gbps | $36.90/年 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=228) |
| TINY | 1核 1GB | 20GB SSD | 2000GB | 1Gbps | $6.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=131) |
| STARTER | 1核 2GB | 40GB SSD | 4000GB | 1Gbps | $12.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=132) |
| MINI | 2核 2GB | 60GB SSD | 8000GB | 1Gbps | $21.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=133) |
| MICRO | 4核 4GB | 80GB SSD | 16000GB | 1Gbps | $32.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=134) |
| MEDIUM | 4核 8GB | 160GB SSD | 32000GB | 1Gbps | $49.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=135) |
| LARGE | 8核 16GB | 320GB SSD | 64000GB | 1Gbps | $99.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=136) |
| GIANT | 8核 24GB | 640GB SSD | 128000GB | 1Gbps | $199.90/月 | [ 选择此方案](https://www.dmit.io/aff.php?aff=13832&pid=229) |

---

## 选哪个？按场景直接给结论

把场景分开说更有用：

**个人小站 / 博客**：洛杉矶 Tier 1 TINY，$6.90/月，1核1GB，2TB流量，完全够用。

**科学上网节点**：洛杉矶 Premium TINY 或 Pocket，$37.99/季起，CN2 GIA 线路，晚高峰稳定性好不少。价格算下来约 $12-18/月。

**面向中国用户的商业站**：香港 Premium TINY，$39.90/月，延迟 30-60ms，体验最直接。预算有限的话香港 Eyeball TINYv2 是 $29.90/月的平衡方案。

**日本 IP / 日韩业务**：东京 Premium TINY，$21.90/月起，日本 IP，CN2 GIA 线路，亚太延迟低。

**外贸建站**：洛杉矶 Premium，兼顾国内访问速度和海外连通性，STARTER（$38.90/月）是常见起步配置。

---

一个实用细节：新注册账号有 7 天等待期才能下单，如果有需要记得提前注册好账号。

IP 被墙的处理方式：Premium 系列 15 天内可以申请免费换 IP，其他情况收 $5 一次。

退款政策：购买后 3 天内、流量消耗不超过 30GB 可申请全额退款（扣支付手续费）；30 天内按剩余时间比例部分退款。不确定要不要买的，可以先选最便宜的套餐测一下线路，不合适退款损失不大。

---

## 常见问题

**Q：DMIT 各系列价格一样，Premium 和 Eyeball 怎么选？**

看你最在意什么。如果晚上 8-11 点是你的主要使用时段，Premium 的线路优先级高，这个时段体验差异最明显。如果你用的时间比较分散，Eyeball 流量更多，同价之下更划算。

**Q：香港机房比洛杉矶贵这么多，真的值吗？**

对于主要服务中国用户的业务，香港机房的延迟差异会直接影响用户体验。延迟 30ms vs 150ms，在页面加载和实时交互上感觉是不一样的。如果你的业务不在意延迟，或者用户在海外，香港的溢价就意义不大了。

**Q：流量超了会怎样？**

DMIT 超量后会限速或暂停，不是按量计费追加收费。选套餐时留一点余量，或者关注月流量使用情况及时升级。Unmetered 系列不限流量但带宽固定，适合持续性小流量业务。

**Q：可以中途换机房吗？**

不支持直接换机房，需要重新购买。建议购买前先想清楚机房需求，不确定可以先用最便宜的套餐测线路，确认合适再入正式方案。

**Q：支持哪些支付方式？**

支持支付宝、微信支付、PayPal。国内用户付款不是问题。

👉 [前往 DMIT 官网查看所有套餐当前价格](https://www.dmit.io/aff.php?aff=13832)
