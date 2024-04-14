<div align=center><img width="100" src="/source/diversion.png"/></div>

<h1 align=center> Proxy Rules - Custom </h1>

部分代理工具的个人自定义分流规则集以及自用的配置模板<br />

各个代理工具的规则集参考于 [ACL4SSR](https://github.com/ACL4SSR/ACL4SSR/blob/master)/[ios_rule_script](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule) 并根据自己的需求修改，没有什么花里胡哨的需求，只是一些简单的需求，规则与配置提供参考，请根据自己的情况修改。如果你的需求和我大致相同，可以直接参考我的配置文件。

> 以下为我的需求：
    Google走美国，Netflix默认走新加坡且可选其他节点，Bing走代理且可选直连，OpenAI走代理且可选其他节点，Apple走直连且可选其他节点，Microsoft走直连且可选其他节点，国内网站/ip/流媒体走直连，其余走代理。

分流规则是一种实现不同的网站走不同的节点或策略组


## Repo Info
|代理工具| 配置文件 | 规则集 | 备注 |
|:---:|:---:|:---:|:---:|
|Clash Meta  |[ClashConfig.yaml](https://github.com/CarefreeMontage/proxyrules-cm/blob/main/ClashConfig.yaml)|[./Clash/](https://github.com/CarefreeMontage/proxyrules-cm/tree/main/Clash)|✔️|
|Quantumult X|[QuantumultX.conf](https://github.com/CarefreeMontage/proxyrules-cm/blob/main/QuantumultX.conf)|[./QuantumultX/](https://github.com/CarefreeMontage/proxyrules-cm/tree/main/QuantumultX)|✔️|
|Sing-Box    |待完善|[./Sing-Box/](https://github.com/CarefreeMontage/proxyrules-cm/tree/main/Sing-Box)|规则集可用|
 Shadowrocket|未计划|未计划|不怎么用，有空再搞
- [x] Clash Meta (Verge/Nyanpasu/...)
- [x] Quantumult X
- [ ] Shadowrocket
- [ ] Sing-Box

> [!TIP]
>
> **叠甲**：
>
> 分流规则是实现不同的网站走不同的节点或策略组的规则文本，其数据均收集自互联网公开信息。
>
> 本仓库中涉及的软件与本项目没有任何直接或间接的关系。本项目仅对代理分流规则进行描述于搬运，不代表支持去使用任何软件。使用任何第三方硬件、软件，所造成的一切后果由使用的个人或组织承担，与本项目无关。
>
> 本仓库中所有内容只供学习和研究使用，基于该仓库源代码进行的任何修改，为其他个人或组织的自发行为，与本项目没有任何直接或间接的关系，所造成的一切后果亦与本项目无关。


## 使用说明
<details>
<summary>Clash Meta</summary>

#### :octocat: Github Raw
- **DIRECT - 直连**<br />
国内直连： https://raw.githubusercontent.com/CarefreeMontage/proxyrules-cm/main/Clash/DIRECT/China.yaml<br />
微软：https://raw.githubusercontent.com/CarefreeMontage/proxyrules-cm/main/Clash/DIRECT/Microsoft.yaml<br />
Apple：https://raw.githubusercontent.com/CarefreeMontage/proxyrules-cm/main/Clash/DIRECT/Apple.yaml

- **PROXY - 代理**<br />
GFW-被墙：https://raw.githubusercontent.com/CarefreeMontage/proxyrules-cm/main/Clash/PROXY/GFW.yaml<br />
Google：https://raw.githubusercontent.com/CarefreeMontage/proxyrules-cm/main/Clash/PROXY/Google.yaml<br />
Bing：https://raw.githubusercontent.com/CarefreeMontage/proxyrules-cm/main/Clash/PROXY/Bing.yaml<br />
OpenAI：https://raw.githubusercontent.com/CarefreeMontage/proxyrules-cm/main/Clash/PROXY/OpenAI.yaml

- **REJECT - 屏蔽广告**<br />
广告：https://raw.githubusercontent.com/CarefreeMontage/proxyrules-cm/main/Clash/REJECT/ADBlock.yaml

#### ⚡CDN jsDelivr
- **DIRECT - 直连**<br />
国内直连：https://cdn.jsdelivr.net/gh/CarefreeMontage/proxyrules-cm@main/Clash/DIRECT/China.yaml<br />
微软：https://cdn.jsdelivr.net/gh/CarefreeMontage/proxyrules-cm@main/Clash/DIRECT/Microsoft.yaml<br />
Apple：https://cdn.jsdelivr.net/gh/CarefreeMontage/proxyrules-cm@main/Clash/DIRECT/Apple.yaml

- **PROXY - 代理**<br />
GFW-被墙：https://cdn.jsdelivr.net/gh/CarefreeMontage/proxyrules-cm@main/Clash/PROXY/GFW.yaml<br />
Google：https://cdn.jsdelivr.net/gh/CarefreeMontage/proxyrules-cm@main/Clash/PROXY/Google.yaml<br />
Bing：https://cdn.jsdelivr.net/gh/CarefreeMontage/proxyrules-cm@main/Clash/PROXY/Bing.yaml<br />
OpenAI：https://cdn.jsdelivr.net/gh/CarefreeMontage/proxyrules-cm@main/Clash/PROXY/OpenAI.yaml

- **REJECT - 屏蔽广告**<br />
广告：https://cdn.jsdelivr.net/gh/CarefreeMontage/proxyrules-cm@main/Clash/REJECT/ADBlock.yaml

</details>




## Credit

— [ACL4SSR](https://github.com/ACL4SSR/ACL4SSR/blob/master)

— [ios_rule_script](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule)