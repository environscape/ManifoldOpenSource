# Manifold 固件移植：O_C / EuroPi 平台说明

Coding Inspire 编码灵感模块化已经将 Manifold 的固件移植到了 EuroPi 和 Ornament & Crime 两个开源模块之上，以便于创造更好的模块生态，以及促进模块玩家间的交流与体验。

## Manifold 固件在三个设备上的运行对比

| 项目 | O_C | EuroPi | Manifold |
| --- | --- | --- | --- |
| 操作逻辑 | 2x 按钮、2x 编码器 | 2x 按钮、2x 电位器 | 4x 按钮、4x 编码器 |
| 显示屏幕 | 128x64 像素 | 128x32 像素 | 128x64 像素 |
| 输入接口 | 4x CV、4x Trigger | 1x CV、1x Gate | 3x CV、3x Gate |
| 输入 CV 范围 | 0-6V | 0-10V | 0-10V |
| 输出接口 | 4x CV | 6x CV | 6x CV |
| 输出电压 | 0-6V | 0-10V | 0-10V |
| 输出信号显示 | 无 LED | 有 LED | 有 LED |
| 预设存储数量 | 8（EEPROM 限制） | 8 | 16 |
| 同时运行模块数量 | 8 | 12 | 12 |
| 模块种类 | 20 | 20 | 20 |
| 预设生成功能 | 支持 | 支持 | 支持 |
| i2c 扩展板支持 | 不支持 | 暂不支持 | 已经支持 |
| 升级固件方式 | 需要 Teensy 上传工具 | 直接 UF2 文件上传 | 直接 UF2 文件上传 |

## 操作示意图

**EuroPi 操作示意图**

**O_C 操作示意图**

## 说明

不过由于 EuroPi 和 Ornament & Crime 并非为了 Manifold 固件设计，操作上可能不是那么顺手，因此也不能百分百发挥 Manifold 固件的所有使用潜力；同时，由于大量 DIY 产品采用的零件以及制造上的标准不一，可能导致在 EuroPi 与 O_C 本身模块上处理的信号存在干扰与波纹。因此如果您需要完美完整体验功能还需前往了解原版 Manifold 模块合成器。

---

# Manifold Firmware Port: Platform Notes for O_C and EuroPi

Coding Inspire has ported the Manifold firmware to two open-source modules, EuroPi and Ornament & Crime, in order to build a better module ecosystem and to encourage exchange and shared experience among modular players.

## Running Manifold Firmware on Three Devices: Comparison

| Item | O_C | EuroPi | Manifold |
| --- | --- | --- | --- |
| Controls | 2x buttons, 2x encoders | 2x buttons, 2x potentiometers | 4x buttons, 4x encoders |
| Display | 128x64 pixels | 128x32 pixels | 128x64 pixels |
| Inputs | 4x CV, 4x Trigger | 1x CV, 1x Gate | 3x CV, 3x Gate |
| Input CV range | 0-6V | 0-10V | 0-10V |
| Outputs | 4x CV | 6x CV | 6x CV |
| Output voltage | 0-6V | 0-10V | 0-10V |
| Output signal indication | No LED | LED | LED |
| Stored presets | 8 (EEPROM limited) | 8 | 16 |
| Modules running simultaneously | 8 | 12 | 12 |
| Module types | 20 | 20 | 20 |
| Preset generation | Supported | Supported | Supported |
| i2c expander support | Not supported | Not yet supported | Supported |
| Firmware upgrade method | Requires Teensy upload tool | Direct UF2 file upload | Direct UF2 file upload |

## Control Diagrams

**EuroPi control diagram**

**O_C control diagram**

## Notes

However, since EuroPi and Ornament & Crime were not designed for the Manifold firmware, the controls may not feel as natural, and the full potential of the Manifold firmware cannot be fully realized. In addition, because DIY products vary widely in the parts and manufacturing standards they use, signals processed on EuroPi and O_C modules themselves may suffer from interference and ripple. So if you want a perfect, complete experience of all the features, please look into the original Manifold modular synthesizer.
