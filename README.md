# LUMERA Manufacturing Studio

An Arabic RTL, mobile-friendly static manufacturing and costing studio for LUMERA metal-and-wood furniture.

## Features

- Browse and search **150 furniture models**, with photos and model codes `LUM-001` through `LUM-150`.
- Change dimensions, steel section and sheet sizes, kerf, labor/material prices, contingency and profit margin.
- View estimated steel and wood BOMs, steel stock cutting plans, material utilization, and BHD estimates.
- Export the workshop cutting list to CSV or save a six-page manufacturing report as PDF using the browser's print dialog.
- **v2 improvements:** cleaner responsive interface, filtered-model count, keyboard-friendly catalog, per-model local save/restore, shareable model URLs, instant calculations and input/cutting-size validation.

## Launch

Open `index.html` in a modern browser or publish this repository on GitHub Pages: **Settings → Pages → Build and deployment → Deploy from a branch → main → / (root)**.

The saved drafts use browser `localStorage` and exist on that device/browser only. This is **not** server-side project storage or an account login.

## Manufacturing and privacy limitations

- The workshop cutting lists and dimensions for designs other than the washer-reference model are **estimates**, not approved engineering drawings.
- The wood nesting and steel optimization are heuristic estimates. Review all cuts and joins before manufacturing.
- Demo prices are illustrative, not current supplier quotations.
- This is a **public static repository and frontend**, and therefore **not a secure place for confidential factory costing or customer records**. Any values embedded in the HTML/JavaScript can be viewed by visitors. Keep sensitive company data in a private, authenticated back-office app.
- PDF export invokes the browser print-to-PDF dialog; no server-side PDF engine is configured.

## Example checked

The reference washer shelf design `REF-WASHER` produces an estimated steel net length of **15.880 m** and wood area **0.840 m²** with its default dimensions; verify the actual cutting plan on-site.

## Updates

v2 delivered with UX, responsiveness, validation, draft and PDF-print improvements.
