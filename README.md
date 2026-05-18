# NFPA 13 Sprinkler Demand Calculator

A field-ready web application for calculating fire sprinkler system demand per **NFPA 13-2022** and **NFPA 13R-2022**.

## 🔗 Live Tool
**[Open Calculator →](https://[your-username].github.io/nfpa13-calc/)**

---

## Features

### ⚡ Field Input Tab
- System type selection: **Wet/Dry/Pre-Action Density-Area, ESFR (wet/dry), CMDA, CMSA, Residential 13R**
- **Dynamic panels** — ESFR shows number-of-heads × pressure demand; D/A shows density/area inputs; CMSA shows specific application inputs
- Hydraulic data plate entry (density, area, K-factor, flow/pressure at remote sprinkler and base of riser, hose allowances)
- Water supply flow test entry (static, residual, pitot flow, elevation adjustment)
- **Demand Adequacy Analysis** — N^1.85 extrapolation, % adequacy meter, color-coded pass/fail

### 🏢 Occupancy Hazard Calculator
- Light, Ordinary I/II, Extra I/II classifications
- Auto-populated hose stream allowances per NFPA 13 §19.3.3
- Density × Area demand calculation

### 📦 Storage Commodity Calculator
- Class I–IV + Group A Plastics (Cartoned/Exposed × Unexpanded/Expanded)
- **Automatic plastic pallet upgrade** per NFPA 13 §20.3.3
- Ceiling sprinkler + in-rack sprinkler demand
- ESFR quick reference

### 🏠 Residential Calculator (NFPA 13R)
- One- or two-sprinkler design basis
- Pressure check against minimum listed pressure

### 📋 Commodity Reference
- Searchable, filterable table of commodity examples per **NFPA 13-2022 Annex A**
- 55+ commodity examples across all classes

---

## Deploying to GitHub Pages

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your tool will be live at `https://[username].github.io/[repo-name]/`

---

## Code Structure

```
index.html      ← Entire application (single file, no dependencies)
README.md       ← This file
```

No build tools, no npm, no frameworks. Pure HTML/CSS/JS. Works offline once cached.

---

## Disclaimer

> This tool is a **design aid only**. All results must be verified by a licensed fire protection engineer against the full NFPA 13/13R standard. Hydraulic calculations per NFPA 13 §28 are required to confirm system adequacy. The authors make no warranty as to the accuracy or completeness of this tool.

**Reference Standard:** NFPA 13-2022, *Standard for the Installation of Sprinkler Systems* and NFPA 13R-2022.

---

## Contributing

Pull requests welcome. Please include the NFPA section reference for any code changes affecting calculations.
