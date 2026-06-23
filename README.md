<div align="center">

<!-- Header with left text and right logo -->
<div style="display: flex; align-items: center; justify-content: space-between; width: 100%;">
  <div style="text-align: left;">
    <strong style="font-size: 1.2em;">Data speaks, you publish</strong><br>
    <strong style="font-size: 1em;">Mantra:</strong> From data, printed paper.<br>
    <strong style="font-size: 1em;">Tagline:</strong> QuickReport Heritage.
  </div>
  <div>
    <img src="https://www.protee.org/images/wqr_QuickReport/wqr_QuickReport.png" alt="wqr_QuickReport Logo" width="120" style="border-radius: 12px;">
  </div>
</div>

<!-- Title and badges -->
# wqr_Quickreport

[![4D Component](https://img.shields.io/badge/4D-Component-blue)](#)
[![License: Commercial](https://img.shields.io/badge/License-Commercial-red.svg)](#license)
[![Platform: macOS & Windows](https://img.shields.io/badge/Platform-macOS%20%7C%20Windows-lightgrey)](#)
[![4D v21+](https://img.shields.io/badge/4D-v21%2B-brightgreen)](#)

</div>

## Overview

wqr_Quickreport is a modern fork of the original 4D QuickReport, specifically enhanced to integrate seamlessly with ORDA‑based architectures. It brings the power of ORDA to your reporting workflow, making printed reports easier, faster, and more intuitive.

---

## Key Features

- **ORDA‑Like Interface**: Provides methods and a workflow designed for the ORDA model, allowing you to pass an Entity Selection directly for reporting[reference:0].
- **Backward Compatibility**: Internally, the Entity Selection is efficiently converted to a classic selection, ensuring full compatibility with the underlying 4D QuickReport engine[reference:1].
- **Enhanced User Interface**: Includes various UI improvements over the original for a more modern and user‑friendly experience[reference:2].
- **Maintenance & Stability**: Incorporates essential bug fixes from the original codebase for increased reliability[reference:3].
- **Multi‑Language Support**: Fully localized in **English (EN)**, **French (FR)**, **Spanish (ES)**, and **German (DE)**.

---

## Installation & Dependencies

### Prerequisites
- **4D v21** or higher (Project mode recommended).
- [**wok_Krolific**](https://github.com/protee/wok_Krolific) – Licensing component (mandatory dependency).
- [**wox_Xlibrary**](https://github.com/protee/wox_Xlibrary) – Core utilities (mandatory dependency).
- [**woc_Colours**](https://github.com/protee/woc_Colours) – Color management engine (mandatory dependency).
- [**waz_Wazar**](https://github.com/protee/waz_Wazar) – UI widgets (mandatory dependency).

### Installation via Dependencies Manager (GitHub)

Starting with 4D v21, the recommended way to install wqr_Quickreport (and any ogTools component) is through the **Dependencies Manager** using the **GitHub repository**:

1. In your 4D project, open the **Dependencies Manager** (`Project > Dependencies`).
2. Click the `+` button and select **Add a dependency from a Git URL**.
3. Enter the following Git URL:`protee/wqr_Quickreport`
4. Choose the desired version (e.g., `main`, `latest`, or a specific release tag).
5. Confirm the installation – the component will be automatically fetched from GitHub, placed in the `Components` folder, and linked to your project.

> **Note**: For team development, commit the dependency configuration file (`dependencies.json`) to your source control so all team members automatically fetch the same version from GitHub.

---

## How It Works

1. **ORDA Integration**: You pass an Entity Selection directly to the component using its ORDA‑like methods.
2. **Legacy Conversion**: Internally, the component converts the Entity Selection to a classic selection, ensuring full compatibility with the underlying QuickReport engine.
3. **Report Generation**: The report is generated using the enhanced UI and the stable, bug‑fixed engine.
4. **Output**: The final printed report is produced, ready for distribution or archiving.

---

## ogTools Suite – Dependencies

wqr_Quickreport is the reporting pillar of the comprehensive **ogTools suite** – an integrated development ecosystem for 4D. Dependencies:

| Icon | Component | Description |
|------|-----------|-------------|
| <img src="https://www.protee.org/images/wok_Krolific/wok_Krolific.png" alt="wok_Krolific Logo" width="60" style="border-radius: 12px;"> | **wok_Krolific** | License manager. |
| <img src="https://www.protee.org/images/wox_Xlibrary/wox_Xlibrary.png" alt="wox_Xlibrary Logo" width="60" style="border-radius: 12px;"> | **wox_Xlibrary** | Core utilities for everyday development tasks. |
| <img src="https://www.protee.org/images/woc_Colours/woc_Colours.png" alt="woc_Colours Logo" width="60" style="border-radius: 12px;"> | **woc_Colours** | Advanced, indexed color management engine. |
| <img src="https://www.protee.org/images/waz_Wazar/waz_Wazar.png" alt="waz_Wazar Logo" width="60" style="border-radius: 12px;"> | **waz_Wazar** | Intelligent UI widgets for modern interfaces. |

---

## License

wqr_Quickreport is a **commercial component** and is part of the paid ogTools suite. A valid license is required for use. For licensing options and trial requests, please contact the sales team directly.

---

## Localization

wqr_Quickreport supports the following languages out‑of‑the‑box:

- 🇺🇸 English (EN), 🇫🇷 French (FR), 🇪🇸 Spanish (ES), 🇩🇪 German (DE)
- More on demand

Localization affects error messages, UI prompts, and built‑in pane texts.

---

## Support & Resources

- **Official Website**: [https://www.protee.org](https://www.protee.org)
- **Documentation**: Full documentation and HDI (Host Database Interface) demos are included with your purchase.

For direct inquiries:
- **Email**: [og@protee.org](mailto:og@protee.org)
- **Phone**: +33 6 3718 5941

---

## About the Creator

wqr_Quickreport and the ogToolsSuite are developed by **Protée sarl**, a company with over 30 years of expertise in 4D development. Led by Olivier Grimbert, the team focuses on delivering high‑quality, production‑grade tools that enhance developer productivity and application reliability.

---

<div align="center">
  <sub>Built with ❤️ for the 4D community by Protée sarl. © 2016 - Present</sub>
</div>