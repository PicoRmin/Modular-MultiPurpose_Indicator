# Modular MultiPurpose Indicator (TradingView • Pine v5)

<div align="center">

<img src="assets/logo.png" alt="Project Logo" width="96" />

<br/>
<br/>

<img src="assets/cover.png" alt="Project Cover" width="820" />

</div>

## Overview
A modular, all‑in‑one TradingView indicator that overlays three systems on a single chart with full visual controls:

- Ichimoku Cloud (configurable lines, cloud colors, opacity)
- SMC Suite (BOS / CHoCH labels and structure lines)
- Volumized Order Blocks (zones, borders, extension)

Designed to be clean, readable, and fully toggleable per module with color/opacity controls.

## File
- `Combined_Indicator.pine`

## Features
- Toggle modules on/off independently
- Customize colors, opacities, line widths, and label sizes
- Layering optimized: OB zones under, Ichimoku mid, SMC labels on top
- Built‑in alerts for Ichimoku, SMC (BOS/CHoCH), and OB events
- Live info table showing module statuses and cloud state

## Quick Start (TradingView)
1. Open TradingView Pine Editor
2. Create new script and paste `Combined_Indicator.pine`
3. Click “Add to chart”
4. Adjust inputs under: Module Controls, Ichimoku, SMC, Order Blocks

## Inputs Snapshot
- Module toggles: Show Ichimoku, Show SMC, Show Order Blocks
- Ichimoku: periods, displacement, colors (Tenkan, Kijun, SpanA/B, Chikou), cloud colors
- SMC: lookback, sensitivity, labels/lines, label size, colors
- OB: lookback, volume threshold, extend bars, colors, border options

## Repository Structure
- `Combined_Indicator.pine` — main indicator
- `assets/logo.png` — small square logo used in README (add your image)
- `assets/cover.png` — wide cover banner used in README (add your image)

> Note: Add your actual images at the specified paths. Placeholders are not included.

## License
This project is licensed under the MIT License — see `LICENSE` for details.

## Credits
© 2025 آرمین البرزی — `rmin.alborzi@gmail.com`


