# LHSP — Luan's Homebrewed Switch Pack

> **Lightweight and clean pack for Nintendo Switch.**
> Simple, no bloat, always up-to-date.

![Pack](https://img.shields.io/badge/Pack-v2.4.0-2ea44f?style=flat-square)
![Firmware](https://img.shields.io/badge/Firmware-23.5.0-blue?style=flat-square)
![Atmosphère](https://img.shields.io/badge/Atmosph%C3%A8re-1.12.2-orange?style=flat-square)
![Hekate](https://img.shields.io/badge/Hekate-6.5.5-8957e5?style=flat-square)
![License](https://img.shields.io/badge/License-GPL--3.0-lightgrey?style=flat-square)

---

## 📦 Contents

| Item                | Version                |
|---------------------|------------------------|
| Pack                | `2.4.0`                |
| Supported Firmware  | `23.5.0`               |
| Atmosphère          | `1.12.2` *(basic support)* |
| Hekate              | `6.5.5` *(Nyx 1.9.5)*  |

## 🧩 Included Homebrews

| Homebrew                  | Version              |
|---------------------------|----------------------|
| Hekate                    | `6.5.5`              |
| Atmosphère                | `1.12.2`             |
| sys-patch *(sigpatches)*  | `1.6.3.0`            |
| Ultrahand Overlay         | `2.5.4`              |
| nx-ovlloader              | `2.0.3`              |
| Horizon-OC *(hoc-clk)*    | `2.6.1`              |
| CyberFoil *(installer)*   | `1.5.1`              |
| Sphaira                   | `1.0.9`              |
| JKSV *(save manager)*     | `2025-12-02`         |

<sub>🔧 **Bundled tools** (ship with Atmosphère / nx-ovlloader): Daybreak · Haze (USB MTP) · Reboot to Payload · Ultrahand-Reload.</sub>

---

## 🚀 Install

1. Download the latest version **[here](https://github.com/LuanBogoqb/LHSP/releases)**
2. Extract the `.zip` directly to the **root of your SD card**
3. Boot the console with **Hekate** (payload)
4. Choose **EmuMMC** (default)

That's it. ✅

## ⚙️ Hekate Boot Options

| Option      | Status                       |
|-------------|------------------------------|
| **EmuMMC**  | Default *(recommended)*      |
| **SysMMC**  | Not configured by default    |

> To boot into SysMMC, edit `/bootloader/hekate_ipl.ini`.

---

## 🛡️ Anti-Ban (Exosphere)

Your EmuMMC ships with **serial and product info blanked** for safety — this significantly reduces ban risk when using sigpatches.

> To disable this protection, edit `/exosphere.ini`.

---

## 📝 Notes

- Atmosphère is in **basic support** on FW `23.0.0` / `23.5.0` — use at your own risk.
- This pack **does not include themes** (HEKATE ones included), extra overlays, or unnecessary homebrews.
- **Horizon-OC** replaces sys-clk for overclocking. It loads through `atmosphere/kips/hoc.kip` and boots automatically with this pack's Fusée payload, so no `hekate_ipl.ini` edit is needed. Configure it from the Horizon-OC overlay and use **Save KIP Settings**.
- ⚠️ Overclocking RAM can corrupt NAND or SD. Back up NAND, PRODINFO and your SD before pushing memory clocks.
- I **do not condone piracy**.

---

<sub>📄 Licensed under **[GPL-3.0](LICENSE)**.</sub>
