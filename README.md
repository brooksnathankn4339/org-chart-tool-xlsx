# Org Chart Tool - Organizational Charting 2026

> **Org Chart Tool is a browser-based editor that turns Workday XLSX exports into editable organizational charts. Modify hierarchy views, save your work, and export finished charts without installing software or running a backend.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/brooksnathankn4339/org-chart-tool-xlsx?style=flat-square)](https://github.com/brooksnathankn4339/org-chart-tool-xlsx)

---

<p align="center">
  <a href="https://brooksnathankn4339.github.io/org-chart-tool-xlsx/">
    <img src="https://img.shields.io/badge/Download-Org%20Chart%20Tool%20Latest-brightgreen?style=for-the-badge" alt="Download Org Chart Tool">
  </a>
</p>

> **[Download Org Chart Tool](https://brooksnathankn4339.github.io/org-chart-tool-xlsx/)**

---

[Download Latest Build](https://brooksnathankn4339.github.io/org-chart-tool-xlsx/)

---

## Overview

Org Chart Tool provides a practical way to convert organizational data into hierarchy diagrams that can be reviewed and edited. By accepting Workday XLSX exports, it lets teams start from existing personnel data instead of recreating their structure from scratch.

Everything runs in the browser, with no application installation and no backend service involved. Once a chart is created, you can refine its appearance, keep it in browser storage, move the editable data through JSON, or generate a PNG for documents and presentations.

---

## What It Can Do

- Read organizational information from Workday XLSX exports
- Create and modify organization charts directly in a browser
- Keep chart projects saved in browser storage
- Import chart data from JSON and export it back to JSON
- Produce PNG versions of completed charts
- Switch between available chart layouts and orientations
- Tune zoom and spacing to make structures easier to read
- Operate without a local application install or backend

---

## Getting Started

### Hosted version

Use a supported modern browser to open the current hosted build:

[Launch Org Chart Tool](https://brooksnathankn4339.github.io/org-chart-tool-xlsx/)

### Local checkout

To run the project from a repository checkout, clone it and serve the included web files through a static server:

```bash
git clone https://github.com/brooksnathankn4339/org-chart-tool-xlsx.git
cd REPO
```

After starting your preferred local web server, open the project's main HTML page in a browser.

---

## Workflow

1. Launch Org Chart Tool in your browser.
2. Load a Workday XLSX export to generate the starting hierarchy.
3. Inspect the resulting chart and make any required structural edits.
4. Select the desired orientation and layout, then tune spacing and zoom.
5. Save the current chart in the browser.
6. Create a JSON export when the editable chart data needs to be archived or transferred.
7. Generate a PNG export for sharing, reports, or other documentation.

---

## Browser Configuration

There is no server-side configuration file. Instead, chart settings are managed through the controls in the browser, including:

- Chart layout and orientation
- Spacing between nodes
- Zoom level
- Chart data imported from or exported to JSON

Charts saved during a session are stored in the browser. JSON exports serve as a portable copy for retaining chart data or moving it to another environment.

---

## Requirements

- A current web browser
- XLSX files when using the Workday import workflow
- Enabled browser storage for in-browser saving
- Enough browser memory for the organization chart being displayed
- No separate runtime, installer, or backend service

---

## Frequently Asked Questions

### Is an installation required?

No. Org Chart Tool is intended to run directly in a web browser and does not need a separate installation.

### Does it support Workday exports?

Yes. Workday XLSX exports can be imported to create the initial organizational chart.

### What are my options for saving a chart?

You can save the chart in browser storage. To keep a portable version of the editable data, export it as JSON.

### Can the chart be shared as an image?

Yes. The PNG export creates an image version suitable for sharing or including in documentation.

### Are the layout settings adjustable?

Yes. The chart controls let you modify layout, orientation, spacing, and zoom.

### What if the imported hierarchy is incorrect?

First check the source XLSX export and verify that it contains the organizational fields expected by the tool. Inspect the generated chart, then correct the hierarchy and use the layout controls as needed.

### Where can I find the newest version?

Open the latest hosted build here:

[Open the Latest Build](https://brooksnathankn4339.github.io/org-chart-tool-xlsx/)

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
