# 🎮 Control "Any" Switch
> One Blueprint to rule them all! 

Control switches from different brands and models with a single, powerful Home Assistant Blueprint.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fremb0%2Fblueprints%2Fblob%2Fmain%2FDifferent_switches_zigbee2mqtt.yaml)

---

## ✨ Features
*   **Universal Support**: Works with Aqara, Ikea, Philips Hue, Tuya, Paulmann, and Opple switches.
*   **Clean UI**: All inputs feature helpful icons and descriptions.
*   **Collapsible Sections**: Only see the settings for the switch you are actually using.
*   **Parallel Actions**: Supports multiple actions running simultaneously.

## 🤝 Compatibility List

| Brand | Model(s) | Notes |
| :--- | :--- | :--- |
| **Aqara** | **WXKG01LM**, **WXKG12LM** | Single Button Switches |
| | **WXKG07LM**, **WXKG15LM** | Rockers (2-gang) |
| | **E1 3-Gang (ZNQBKG31LM)** | *New!* Full support for Left, Center, Right |
| | **E1 2-Gang (QBKG39LM)** | *New!* Left, Right |
| **Ikea** | **E1743** (Tradfri On/Off) | |
| | **E1810 / E1812** | 5-Button Remote |
| | **E1524 / E2001 / E2002** | Round Remotes |
| **Philips Hue**| **Tap Dial (RDM002)** | *New!* Buttons + Dial Rotation |
| | **Dimmer V2 (929002398602)** | |
| | **Wall Switch Module** | |
| **Tuya** | **TS0042** | 2-Button Scene Switch |
| **Paulmann** | **501.34** | Remote Control |
| **Opple** | **WXCJKG12LM** (4-button) | |
| | **WXCJKG13LM** (6-button) | |
| **Lidl** | **HG08164** | Single Switch |

## ⚙️ Requirements
*   **Zigbee2MQTT**: Version 2025.1 or newer.
*   **Home Assistant**: 2024.12.0 or newer.

## 🚀 How to Update
If you already have this blueprint and want to get the latest features (Icons, New Device Support):
1.  Go to **Settings** > **Automations & Scenes** > **Blueprints**.
2.  Find the `Different_switches_zigbee2mqtt` blueprint.
3.  Click the **three dots** and select **Re-import Blueprint**.
4.  Reload your Automations.

## 📝 Roadmap
- [x] Add Icons to all inputs for better visual identification.
- [x] Make sections collapsible to declutter the UI.
- [x] Add support for Aqara E1 Series.
- [ ] Add explicit support for new Sonoff switches.

---

<a href="https://www.buymeacoffee.com/remb0" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
