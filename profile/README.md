<div align="center">

# JavRanking
### 东半球最好的成人影片和女优排行榜 · The Ultimate JAV & Actress Ranking Platform

[![Official Site](https://img.shields.io/badge/Official%20Site-javranking.cc-orange?style=for-the-badge&logo=safari&logoColor=white)](https://javranking.cc)
[![Permanent Status](https://img.shields.io/badge/Status%20Center-Operational-green?style=for-the-badge&logo=statuspal&logoColor=white)](https://javranking.github.io/status/)
[![Relay Gateway](https://img.shields.io/badge/Clean%20Relay-javranking.top-blue?style=for-the-badge)](https://javranking.top)
[![License](https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge)](LICENSE)

<br/>

> **JavRanking** 是一个以排行榜为入口的高品质影视资料展示与探索平台。  
> 致力于将优质、可策展的榜单与精选片库做成**加载极快、易于浏览、体验体面、零流氓弹窗**的技术驱动型产品。

<br/>

</div>

---

### 🌐 官方生态全景图 (Official Ecosystem Matrix)

JavRanking 采用**“核心主站 + 开源周边生态”**的矩阵化架构，将探索与检索能力深度融入用户的浏览器与操作系统高频工作流：

| 项目 / Project | 定位与能力 / Role & Highlights | 技术栈 / Stack | 仓库与文档 / Links |
| :--- | :--- | :--- | :--- |
| **[JavRanking Main Site](https://javranking.cc)** | **核心数据与探索主站**<br>• JavDB 历年 Top 250 / DMM 官方通贩周榜与月榜<br>• 独家综合战力评分加权算法<br>• 4K/1080p 超清预告片库与多维标签探索<br>• 零个人隐私（Zero-PII）跨端观影标记（想看/已冲） | Astro v7 SSG<br>Cloudflare Pages<br>SQLite / D1 | 🚀 **[javranking.cc](https://javranking.cc)**<br>[中文版](https://javranking.cc/zh-hans/) · [English](https://javranking.cc/en/) |
| **[javranking-extension](https://github.com/javranking/javranking-extension)** | **官方浏览器伴侣扩展** (Chrome / Edge / Firefox)<br>• 划词或工具栏一键识别当前页面所有番号候选<br>• 即时调出 JavRanking 榜单、评分与精选热评<br>• 无缝绑定 8 位冲码（Chong Code），跨设备实时同步 | WXT<br>TypeScript<br>Manifest V3 | ⭐️ **[GitHub 仓库](https://github.com/javranking/javranking-extension)**<br>[安装指南](https://github.com/javranking/javranking-extension#%E5%AE%89%E8%A3%85-chrome-%E6%88%96-edge-%E7%89%88%E6%9C%AC) |
| **[javranking-popclip-extension](https://github.com/javranking/javranking-popclip-extension)** | **macOS 划词即搜扩展** (PopClip Extension)<br>• 系统全局鼠标划选番号、女优、片商，1 秒直达搜索<br>• 自动空格与换行清洗，支持 `⌥ Option` 键精准搜索<br>• 手工绘制适配 macOS 深浅双色模式的品牌矢量图标 | PopClip Snippet<br>YAML / SVG | ⚡️ **[GitHub 仓库](https://github.com/javranking/javranking-popclip-extension)**<br>[划选一键安装](https://github.com/javranking/javranking-popclip-extension#%E6%96%B9%E6%B3%95%E4%B8%80%E9%80%89%E4%B8%AD%E6%96%87%E6%9C%AC%E4%B8%80%E9%94%AE%E5%AE%89%E8%A3%85popclip-snippet---%E6%9C%80%E6%8E%A8%E8%8D%90-) |
| **[status](https://github.com/javranking/status)** | **官方可用状态与防失联中心**<br>• 全节点健康度监测与连通性自测（GitHub Pages 托管）<br>• 官方最高公信力可用域名单点发布源，长期抗封<br>• DNS 劫持排查与免翻墙 DoH 加密配置指南 | Single-file HTML<br>GitHub Pages | 🟢 **[在线状态看板](https://javranking.github.io/status/)**<br>[GitHub 仓库](https://github.com/javranking/status) |
| **[javranking-top](https://github.com/javranking/javranking-top)** | **官方常青中转站与全路由 301 迁移网关**<br>• 纯净合规无敏感内容，永久中立重定向哨所<br>• Cloudflare Pages 原生 `_redirects` 引擎全路由权重移交<br>• 引导访客安全直达主站，支持 DoH 连通排障与离线找回 | HTML5 / CSS3<br>Cloudflare Pages | 🔗 **[常青中转站](https://javranking.top)**<br>[GitHub 仓库](https://github.com/javranking/javranking-top) |

---

### 🛡️ 核心安全与隐私宣言 (Security & Privacy First)

成人影视领域充斥着恶意弹窗、强制跳转、隐私窥探和捆绑脚本。JavRanking 自创立之日起就将“尊重用户、体面克制”作为绝对底线：

1. **零第三方追踪（Zero Third-Party Trackers）**  
   主站及所有开源客户端工具 **100% 不含** 任何第三方广告追踪代码、设备指纹脚本或流氓弹窗。
2. **零个人隐私凭证（Zero PII - Personally Identifiable Information）**  
   观影标记与跨端同步基于纯匿名的 **8 位冲码（Chong Code）**。无需手机号、无需电子邮箱、无需设置密码，从根源上杜绝任何个人数据泄露的可能。
3. **完全开源透明可审计（Fully Auditable Codebase）**  
   所有周边工具与扩展均在 GitHub 官方组织开源，发布物附带 `SHA256SUMS.txt` 校验和，接受社区随时审查。

---

### ⚡️ 官方抗封锁与找回指南 (Anti-Lost Gateway)

无论局部网络受到何种程度的干扰，您都可以通过以下多级冗余通道随时找回 JavRanking：

* 🟢 **首选主站**：`https://javranking.cc`
* 🟢 **常青中转站**：`https://javranking.top`（纯净无敏感内容，专职全路由安全重定向）
* 🟢 **官方防失联中心**：`https://javranking.github.io/status`（脱离商业域名体系的永久哨所）
* 🟢 **应急找回邮箱**：发送任意内容至 `contact@javranking.cc`，系统秒级自动回复最新可用网址。

---

<div align="center">

**Built with passion & precision by the JavRanking Team.**  
*Clean. Fast. Curated.*

</div>
