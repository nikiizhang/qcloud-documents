## 什么是 DDoS 高防 IP？
DDoS 高防 IP 是腾讯云面向所有云服务器（含非腾讯云服务器）推出的防 DDoS 攻击的付费产品，能够有效地应对大流量的 DDoS 攻击。目前支持电信、联通、移动、BGP 线路防护，您可直接购买单线路 IP 或套餐（多线路 IP）防护。

## 使用场景
DDoS 高防 IP 服务于腾讯云以及腾讯云以外的所有云服务器。

## 防护原理
DDoS 高防 IP 通过代理转发模式防护源站服务器，业务流量直接访问高防 IP，然后回源到源站服务器。如果发生 DDoS 攻击，攻击流量在经过高防 IP 时，防护系统会进行过滤清洗，并将清洁业务流量转发回源到业务服务端，以保障业务在 DDoS 攻击场景下的可用性。

## 为什么选择 DDoS 高防 IP？
- 隐藏真实源站 IP
DDoS 高防 IP 通过代理转发模式，将业务流量转发给源站 IP，以隐藏源 IP，攻击流量被清洗，保护源站业务。
- 超大带宽防护
DDoS 高防 IP 可针对云内外服务器提供 T 级防护，轻松抵御大流量 DDoS 攻击和 CC 攻击。
>**注意：**
>如需配置更高带宽防护，请联系客服咨询。
- 支持单 IP、套餐购买
DDoS 高防 IP 支持一次性购买一条或多条不同线路 IP，灵活选购，适用各种业务场景使用。业务需求如果主要是某一个运营商线路，可以直接选购单 IP 防护。而套餐提供多线路防护，避免用户跨网访问。
- 灵活计费
按月预付费的保底防护 + 按天后付费的弹性防护，按实际攻击量计费，为您节约成本。详情请参见 [计费说明](https://cloud.tencent.com/document/product/685/15263)。

## 使用时需要注意什么？
DDoS 高防 IP 通过将高防 IP 作为业务 IP 对外发布的方式来隐藏源站 IP，以达到防护目的，若用户源站曾被攻击过且源站 IP 已暴露，那么建议购买 DDoS高防 IP 服务后更换源站 IP，以确保源站 IP 的隐秘性，让攻击者无法直接攻击源站。如果是腾讯云服务器 IP，请参见 [如何更换腾讯云服务器 IP 地址](https://cloud.tencent.com/document/product/685/18802)。

## 如何配置 DDoS 高防 IP？
登录 [宙斯盾安全防护控制台](https://cloud.tencent.com/login?s_url=https%3A%2F%2Fconsole.cloud.tencent.com%2Fgamesec)，在左侧目录单击【DDos 高防 IP】，选择【购买高防 IP】。操作详情请参见 [DDoS 高防 IP](https://cloud.tencent.com/document/product/685/15264)。
