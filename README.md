# MDCx-diy

![python](https://img.shields.io/badge/Python-3.13+-3776AB.svg?style=flat&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-GPLv3-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)
![Crawlers](https://img.shields.io/badge/Sites-37-brightgreen.svg)

> 2026 年 9 月起，本项目的日常开发转入私有仓库进行；本仓库作为官方发布门面，持续提供正式发布（Releases）与 Issue 反馈。
>
> **MDCx 是公益免费项目：所有功能永久免费，没有「付费授权」，没有「绑定机器」，没有「付费进群」，也没有任何「付费优先支持」。** 唯一的下载入口是本仓库 Releases 页（文件名带完整 SHA 校验串）；页面中的打赏纯属自愿，与否不影响任何功能、更新与反馈待遇。

## 关于个别收费「授权」的修改版，想对用户说的话

我们注意到有个别修改版项目，在沿用本软件代码与文档框架分发时未保留版权声明与上游出处，且开始以数百元的价格出售「机器绑定授权」，并以「随时下架」「源码在我手里」等说法回应质疑。这里澄清三点：

1. **对 GPLv3 许可的代码出售「独家授权」，违背的正是售卖者自己声明的许可证。** GPLv3 之下，软件源码属于每一位接收者，任何人都无权宣称对它的「独占」，也无权用它向公众收费设门槛。
2. **如果您已在这样的渠道付费：请向售卖者索取与您所用版本完整对应的构建源码。** 这是 GPLv3 第 6 条赋予您的正当权利，对方若提供不了，本身即构成违约——您可以据此退款止损。
3. 相关事实我方已留存证据，保留依法追索的权利。我们不在这里点名任何项目，是非留待许可证与社区公论。

对本软件而言，开发与更新的成本由维护者自行承担，公益属性是选择而非权宜——这也是我们拒绝把用户变成「授权」的原因。

## GPLv3 与对应源码

本软件基于 GPLv3 许可的上游项目演进而来，我们尊重并遵守开源许可证。依据 GPLv3 第 6 条，凡获取到本仓库发布产物（二进制包）者，均可索取与之对应的完整构建源码：请在任意 Issue 或邮件（见个人主页联系方式）中提出获取请求，我们将在产物发布后三年内应请求提供，该要约随每个发布产物长期有效。

<p align="center"><b>如果你觉得不错可否赏我杯奶茶费，谢谢！ 😊</b></p>

<table align="center">
  <tr>
    <td align="center"><img src="resources/Img/donate-wechat.jpg" width="180" alt="微信"><br><sub>微信</sub></td>
    <td width="40"></td>
    <td align="center"><img src="resources/Img/donate-alipay.jpg" width="180" alt="支付宝"><br><sub>支付宝</sub></td>
  </tr>
</table>

## MDCx-diy 是什么

MDCx-diy 是一个桌面工具，自动从 37 个网站抓取视频文件的元数据（标题、演员、封面、简介等），生成标准的 .nfo 文件和整理好的文件夹，给 Emby、Jellyfin、Kodi 这类媒体服务器直接用。

一句话：把一堆乱七八糟的视频文件，变成媒体服务器能认的整齐资料库。

## 使用与帮助

- 下载地址：本仓库 [Releases](../../releases) 页，认准文件名中的完整 SHA 校验串。
- 使用说明与常见问题：见本仓库 [Wiki](../../wiki)。
- 问题反馈：请使用 [Issue 模板](../../issues/new/choose)，一个议题说一件事，附现象、影响与复现步骤。
- 使用 AI 工具辅助撰写 Issue 或 PR 的，请阅读并按 [.github/AI_POLICY.md](.github/AI_POLICY.md) 披露使用程度；是否采纳以代码与复现证据为准。

## 上游项目

* [sqzw-x/mdcx](https://github.com/sqzw-x/mdcx) — mdcx 项目前身，当前维护状态见其原仓库
* [Hazard804/mdcx](https://github.com/Hazard804/mdcx) — 基于 sqzw-x/mdcx 继续维护及优化
* [ZiPenOk/mdcx](https://github.com/ZiPenOk/mdcx) — 基于 Hazard804/mdcx 优化改进

本项目在 GPLv3 框架下继承并感谢上述工作；向相关开发者表示敬意。
