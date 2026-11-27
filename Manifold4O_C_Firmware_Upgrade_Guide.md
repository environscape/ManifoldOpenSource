# Manifold4O_C 固件升级指南（v1.1）

本文说明如何把 **Manifold4O_C v1.1** 固件升级到 O_C 模块。

## 一、准备

- Windows 电脑
- 一根能传数据的 micro-USB 线
- O_C 模块

## 二、下载升级文件

<https://environscape.github.io/CodingInspire/support/firmware/Manifold4O_C_v1.1.hex>

下载后得到 `Manifold4O_C_v1.1.hex`，放桌面即可。

## 三、下载 Teensy Loader

<https://www.pjrc.com/teensy/loader_win10.html>

打开页面，下载 **Teensy Loader Program**，得到 `teensy.exe`。

## 四、升级步骤

1. 双击 `teensy.exe`。
2. 菜单 `File > Open`，选中刚下载的 `.hex` 文件。
3. 菜单 `Operation > Auto`，确认 **Auto 前面有勾**。
4. USB 线接到模块背面的 USB 口，另一头插电脑。模块正常装在机箱里即可，不用断电。
5. 按一下模块背面的小按键，Teensy Loader 识别到后会自动写入，出现 **Download Complete** 就完成了。
   - 没自动开始：点 **Program**，写完再点 **Reboot**。
   - 写完屏幕没反应：点 **Reboot**。
6. 模块重启后跑约 10 秒开机动画，卡片底部显示 `v1.1`，就是升级成功。

刷完拔掉 USB 线即可。

## 五、常见问题

| 问题 | 怎么办 |
| --- | --- |
| 识别不到模块 | 换一根数据线；再按一次背面按键；换一个电脑 USB 口 |
| 按按键没反应 | 按键按到底；换一个电脑 USB 口 |
| 刷完屏幕是黑的 | 等满 10 秒开机动画；还黑就重新刷一次 |
| 需要装驱动吗 | Win10 / Win11 不需要 |
| 升级会不会丢预设 | 不会 |

---

# Manifold4O_C Firmware Upgrade Guide (v1.1)

This document explains how to upgrade the O_C module to **Manifold4O_C v1.1** firmware.

## 1. Preparation

- A Windows computer
- A micro-USB cable that can transfer data
- The O_C module

## 2. Download the Update File

<https://environscape.github.io/CodingInspire/support/firmware/Manifold4O_C_v1.1.hex>

After downloading you will get `Manifold4O_C_v1.1.hex`. Just put it on your desktop.

## 3. Download Teensy Loader

<https://www.pjrc.com/teensy/loader_win10.html>

Open the page and download the **Teensy Loader Program** to get `teensy.exe`.

## 4. Upgrade Steps

1. Double-click `teensy.exe`.
2. Go to the menu `File > Open` and select the `.hex` file you just downloaded.
3. Go to the menu `Operation > Auto` and make sure **Auto is checked**.
4. Plug the USB cable into the USB port on the back of the module and the other end into the computer. The module can stay installed in the case; no need to power it off.
5. Press the small button on the back of the module. Once Teensy Loader recognizes it, it will write automatically; when **Download Complete** appears, it is done.
   - If it does not start automatically: click **Program**, then click **Reboot** after writing finishes.
   - If the screen does nothing after writing: click **Reboot**.
6. After restarting, the module runs a boot animation of about 10 seconds; when `v1.1` shows at the bottom of the card, the upgrade is successful.

When flashing is done, just unplug the USB cable.

## 5. FAQ

| Question | What to do |
| --- | --- |
| The module is not recognized | Try another data cable; press the back button again; try another USB port on the computer |
| Nothing happens when pressing the button | Press the button all the way in; try another USB port on the computer |
| The screen is black after flashing | Wait for the full 10-second boot animation; if it is still black, flash it again |
| Do I need to install a driver? | No, not on Win10 / Win11 |
| Will the upgrade erase my presets? | No |
