# 去广告精简版

## 前言

本项目的去广告精简版分流规则由爬虫程序自动维护。

定时爬取互联网上开源的去广告精简版分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。

本分流规则不包含任何知乎去广告规则。可能存在部分误拦截，建议搭配WhiteList分流规则进行修正，将其置于本分流规则之前，并进行放行。



最后检查时间：2020-12-17 21:15:50。

## 规则统计

总计规则：24619 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN-KEYWORD | 28 |
| DOMAIN-SUFFIX | 15241 |
| DOMAIN | 9158 |
| IP-CIDR | 192 |
## 重复统计

去广告精简版分流规则，与本项目其他分流规则重复情况统计。

点击重复数量可以查看重复规则明细。

| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [Adobe](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Adobe)    | 34   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   11.76% |
|  [Advertising](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Advertising)    | 55223   | [15746](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   28.51% |
|  [AdvertisingTest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/AdvertisingTest)    | 72900   | [15483](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   21.24% |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Apple)    | 33   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   3.03% |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/BlackList)    | 768   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   1.17% |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/China)    | 597   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   1.01% |
|  [ChinaTest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/ChinaTest)    | 73028   | [662](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   0.91% |
|  [ChinaMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/ChinaMedia)    | 48   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   2.08% |
|  [WhiteList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/WhiteList)    | 15   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   6.67% |
|  [Google](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Google)    | 121   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   7.44% |
|  [YouTube](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/YouTube)    | 9   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   11.11% |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Microsoft)    | 89   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   1.12% |
|  [Niconico](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Niconico)    | 4   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   25.0% |
|  [Global](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global)    | 778   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   0.26% |
|  [GlobalMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/GlobalMedia)    | 226   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   1.33% |
|  [Hijacking](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Hijacking)    | 208   | [195](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   93.75% |
|  [Privacy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Privacy)    | 2764   | [2352](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   85.09% |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Proxy)    | 6008   | [30](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   0.5% |
|  [Tencent](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Tencent)    | 19   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   5.26% |
|  [Alibaba](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Alibaba)    | 34   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   2.94% |
|  [Baidu](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Baidu)    | 12   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/Repeat.list)   |   8.33% |
### 特别说明
程序在实际运算时，会根据DOMAIN、DOMAIN-SUFFIX、IP-CIDR、IP-CIDR6间的包含关系进行去重，而出于运行效率考虑，重复规则只统计纯文本匹配，所以可能与实际效果有所出入，仅供参考。

## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Clash 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/AdvertisingLite/AdvertisingLite.yaml

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/AdvertisingLite/AdvertisingLite.yaml

## 数据来源

本项目的去广告精简版分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，建议不要与本项目的去广告精简版分流规则混合使用，以免造成规则重复。

- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanAD.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Guard/Advertising.list
- https://raw.githubusercontent.com/NobyDa/ND-AD/master/Surge/AD_Block.txt
- https://raw.githubusercontent.com/NobyDa/Script/master/Surge/AdRule.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/Advertising/Advertising.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/Advertising/LianXiangJia/LianXiangJia.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/Liby.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/Tide.list
- https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Reject.list


感谢以上分流规则作者的辛勤付出（排名不分先后）。

如果您有更好的分流规则，欢迎提交给我，我会将它加到数据源中继续完善。

## 最后

### 去广告问题

本项目的去广告精简版规则仅是将网络上开源的去广告规则整合去重，**非实际规则维护者**。数据源规则无法去除的广告，本项目的去广告精简版规则也无能为力。

所以很抱歉，没办法处理关于某个APP无法去除广告的反馈，除非您能明确数据源的规则可以去除，而整合后的规则无法去除。同样，也没办法协助您处理去广告精简版规则误拦截的问题，除非您能明确告知哪条规则存在问题，我会将其加入规则黑名单，下次爬虫程序更新时将其去除。

### 特定APP去广告

#### 知乎

本规则不包含知乎去广告，知乎去广告请移步：https://github.com/blackmatrix7/ios_rule_script/tree/master/script/zhihu

#### 哔哩哔哩

如需更完整的哔哩哔哩去广告，请移步：https://github.com/blackmatrix7/ios_rule_script/tree/master/script/bilibili

#### YouTube

本规则不包含YouTube去广告，请自行寻找其他解决方案。

### 正则过滤

爬虫程序在清洗原始规则数据时，可根据正则定向过滤规则，以达到保留特定规则的目的。经过正则过滤的规则，无法100%涵盖原始规则数据，请知悉。

### 正则校验

从2020年11月25日开始，爬虫程序加入对正则合法性的校验。对于无法校验通过，且不明作用的正则，直接抛弃。如果对比数据源发现正则类型的规则较少，则很大可能是错误的正则都已被过滤掉。

### 黑名单

爬虫程序内置部分规则黑名单，在对原始数据进行清洗时，自动将可能引起异常的黑名单规则去除。经过黑名单去除的规则，无法100%涵盖原始规则数据，请知悉。

### 完善规则

如果您：

1. 有更优的原始规则数据
2. 有更多的黑名单规则数据
3. 有更好的优化建议
4. 在使用分流规则时出现异常
5. 有其他问题

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的去广告精简版分流规则。

感谢

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) 

提供规则数据源及改进建议

### 其他问题

爬虫开发的初衷是为满足自己几方面需求：

1. 去除混用多个去广告规则造成的重复
2. 去除多个去广告规则中某些规则
3. 多个分流规则间重复情况检查
4. 定时同步数据源更新

本项目的分流规则还是以自用为主，请不要对外宣传此分流规则。所以，还是请低调使用吧。