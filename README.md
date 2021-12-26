# STM32 Mega Mini based on STM32F10xCxTx

⭐ 基于 STM32F10xCxTx 系列单片机的 STM32 Mega Mini 开发板 ⭐

[GitLab (Homepage)](https://gitlab.soraharu.com/XiaoXi/STM32-Mega-Mini-based-on-STM32F10xCxTx) | [OSHWHub](https://oshwhub.com/yanranxiaoxi/STM32-Mega-Mini-based-on-STM32F10xCxTx)

![实拍图](https://downloadserver.soraharu.com:7000/STM32%20Mega%20Mini%20based%20on%20STM32F10xCxTx/Image/Product_quality_3.jpg)

## 🤔 这是什么

这是一个基于 STM32F0xxKxTx 系列单片机的 STM32 Mega Mini 开发板，使用 [立创 EDA](https://lceda.cn/) 进行开发。

所有支持的 MCU 型号已在下方列出，列出的未经测试的 MCU 仅为理论可以支持，不作兼容性保证。

在焊接过程中，按照官方文档要求，VBAT 引脚为备用电源引脚，正常情况下不需要连接，即 `JUMP1` `D1` `C10` 均无需焊接。`JUMP2` 为主 MCU 电源跳线，请直接短接以确保 MCU 拥有正常供电。

本 PCB 设计已通过完整功能性测试，且已添加 [嘉立创](https://www.jlc.com/) SMT 定位孔，可直接进行 SMT 贴片生产。但请注意，本设计完整开源并遵循 [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/) 开源协议，开源作者不对作品的安全性、完整性作任何承诺，且不对因此产生的任何损失承担后果。

你可以使用本项目的 [焊接助手](https://htmlpreview.soraharu.com/?https://gitlab.soraharu.com/XiaoXi/STM32-Mega-Mini-based-on-STM32F10xCxTx/-/raw/master/InteractiveHtmlBom/index.html) 有效地提升手工焊接效率，本助手通过 [InteractiveHtmlBom](https://gitlab.soraharu.com/XiaoXi/InteractiveHtmlBom) 自动生成。

## 🛠️ 生产电路板

本项目的 Gerber 文件可以从 [Releases](https://gitlab.soraharu.com/XiaoXi/STM32-Mega-Mini-based-on-STM32F10xCxTx/-/releases) 页面获取，并允许在开源许可范围内的商业目的使用。

*建议使用 [嘉立创](https://www.jlc.com/) 生产高品质电路板。

*It is recommended to use [JLCPCB](https://jlcpcb.com/) to produce high-quality circuit boards.

## ⚙️ 部署至 EasyEDA

1. 克隆本项目 [源代码](https://gitlab.soraharu.com/XiaoXi/STM32-Mega-Mini-based-on-STM32F10xCxTx/-/archive/master/STM32-Mega-Mini-based-on-STM32F10xCxTx-master.zip) 到本地
2. 在立创 EDA 标准版编辑器中选择 `文件` -> `打开` -> `立创EDA...`
3. 选择本项目源代码中的 `/EasyEDA/*.json` 文件并分别导入

## 📄 支持 MCU

| Model          | Test   | Remark    |
| -------------- | ------ | --------- |
| STM32F101C6T6  |        |           |
| STM32F101C8T6  |        |           |
| STM32F101CBT6  |        |           |
| STM32F102C4T6  |        |           |
| STM32F102C6T6  |        |           |
| STM32F102C8T6  |        |           |
| STM32F102CBT6  |        |           |
| STM32F103C4T6  |        |           |
| STM32F103C6T6  |        |           |
| STM32F103C6T6A | Tested | Recommend |
| STM32F103C6T7  |        |           |
| STM32F103C6T7A | Tested |           |
| STM32F103C8T6  | Tested | Recommend |
| STM32F103C8T7  |        |           |
| STM32F103CBT6  |        | Recommend |
| STM32F103CBT7  |        |           |

## 📜 开源许可

基于 [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/) 许可进行开源。

本设计已在 [中国版权保护中心](https://www.ccopyright.com.cn/) 登记注册。
