# Manifold4Europi 固件升级指南（v1.1）

## 一、准备

- 电脑（Windows / macOS）
- 一根能传数据的 USB 线
- EuroPi 模块

## 二、下载升级文件

<https://environscape.github.io/CodingInspire/support/firmware/Manifold4Europi_v1.1.uf2>

下载后得到 `Manifold4Europi_v1.1.uf2`，放桌面即可。

## 三、升级步骤

1. 先拔掉模块上的 USB 线。
2. 按住模块背面 Pico 上的 **BOOT** 键不放。
3. 保持按住，把 USB 线插到模块的 USB 口，另一头连电脑。
4. 电脑上出现名为 **RPI-RP2** 的磁盘后，松开 BOOT 键。
5. 把 `Manifold4Europi_v1.1.uf2` 拖进这个磁盘。
6. 磁盘会自动消失，模块自动重启。等 1 分钟后拔掉 USB，升级完成。

## 四、常见问题

| 问题 | 怎么办 |
| --- | --- |
| 电脑没出现 RPI-RP2 磁盘 | 确认 BOOT 键是在插 USB 之前就按住；换一根数据线；换一个 USB 口 |
| 拖入 UF2 没反应 | 重新按住 BOOT 插 USB，再拖一次 |
| 升级后屏幕不亮 | 拔掉 USB 再插一次；不行就重新升级 |
| 升级会不会丢预设 | 正常升级不会 |

---

# Manifold4Europi Firmware Upgrade Guide (v1.1)

## 1. Preparation

- A computer (Windows / macOS)
- A USB cable that can transfer data
- The EuroPi module

## 2. Download the Update File

<https://environscape.github.io/CodingInspire/support/firmware/Manifold4Europi_v1.1.uf2>

After downloading you will get `Manifold4Europi_v1.1.uf2`. Just put it on your desktop.

## 3. Upgrade Steps

1. First unplug the USB cable from the module.
2. Press and hold the **BOOT** button on the Pico on the back of the module.
3. While still holding it, plug the USB cable into the module's USB port and connect the other end to the computer.
4. When a drive named **RPI-RP2** appears on the computer, release the BOOT button.
5. Drag `Manifold4Europi_v1.1.uf2` into that drive.
6. The drive will disappear automatically and the module will restart. After about 1 minute, unplug the USB cable and the upgrade is complete.

## 4. FAQ

| Question | What to do |
| --- | --- |
| The RPI-RP2 drive does not appear on the computer | Make sure BOOT is held down before plugging in the USB cable; try another data cable; try another USB port |
| Nothing happens after dragging in the UF2 file | Hold BOOT and plug in the USB again, then drag it in once more |
| The screen stays dark after the upgrade | Unplug the USB cable and plug it in again; if that doesn't help, redo the upgrade |
| Will the upgrade erase my presets? | A normal upgrade will not |
