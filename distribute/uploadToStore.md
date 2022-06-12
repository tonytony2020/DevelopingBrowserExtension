# 应用商店上架

截至 2022 年 6 月，理论上，所有基于 Chromium 按 MV2 规范构建的插件，在同类国产基于 Chromium 包皮浏览器之间通用。

但从 2010 年移动互联网兴起后，移动端逐步取代桌面端作为互联网流量主要入口，各大厂商国产包皮桌面浏览器均已停止更新或下架。
国产包皮浏览器里除了 360 极速和 360 安全还能提交插件到官网商店审核上架外，都不支持。如果要分发应用，只能将构建目录打包为压缩包，手动分发给用户自行解压手动安装。

[statcounter CN 2022-5](https://gs.statcounter.com/browser-market-share/desktop/china) 统计中国桌面端各个浏览器市场份额

| 浏览器         | 份额   |
| -------------- | ------ |
| Chrome         | 36.82% |
| 360 Safe       | 23.17% |
| Edge           | 14.97% |
| QQ Browser     | 7.28%  |
| Firefox        | 6.23%  |
| Sogou Explorer | 4.45%  |

[statcounter worldwide 2022-5](https://gs.statcounter.com/browser-market-share/desktop/worldwide) 统计全球桌面端各个浏览器市场份额

| 浏览器  | 份额   |
| ------- | ------ |
| Chrome  | 66.16% |
| Edge    | 10.12% |
| Safari  | 9.14   |
| Firefox | 7.66%  |
| Opera   | 2.8%   |
| IE      | 1.65%  |

综上，无论插件的用户定位是全球还是中国地区，只需上架市场份额排名前 5 浏览器 Chrome、Edge、Safari、Firefox 和 360 系列的插件商店，即可覆盖 95% 以上用户。

**各商店审核情况汇总**

| 应用商店                       | 费用       | 审核耗时    | 需上传源码 |
| ------------------------------ | ---------- | ----------- | ---------- |
| Chrome                         | 无         | 3 个工作日  | 否         |
| Edge                           | 无         | 7 个工作日  | 否         |
| Safari                         | 99 美元/年 | 2 个工作日  | 否         |
| Firefox                        | 无         | 1 个工作日  | 是         |
| <p>360 极速</p><p>360 安全</p> | 无         | 10 个工作日 | 否         |

Safari 插件上架应用商店，需申请苹果开发者计划(Apple Developer Program)，缴纳 99 美元/年。
参与计划后，不仅可以提交 Safari 浏览器扩展应用，也可提交电脑 macOS、手机 iOS、电视 tvOS、平板电脑 iPadOS 和手表 watchOS 应用，如果有多个苹果生态应用分发很划算，但仅一个轻量插件就不划算。

---
