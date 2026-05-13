# 🎯 AQL Sampling Dashboard

**Universal Acceptance Quality Level (AQL) Sampling Calculator**

An interactive, offline-capable web tool for quality inspectors across all manufacturing industries. Based on **ANSI/ASQ Z1.4 (ISO 2859-1)** standard.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![HTML5](https://img.shields.io/badge/HTML5-single%20file-orange)
![No Dependencies](https://img.shields.io/badge/dependencies-zero-brightgreen)

---

## 🌐 Live Demo

👉 **[https://YOUR-USERNAME.github.io/aql-sampling-dashboard/](https://YOUR-USERNAME.github.io/aql-sampling-dashboard/)**

> Replace `YOUR-USERNAME` with your GitHub username after deployment.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| **11 AQL Levels** | 0.065, 0.10, 0.15, 0.25, 0.40, 0.65, 1.0, 1.5, 2.5, 4.0, 6.5 |
| **7 Inspection Levels** | S-1, S-2, S-3, S-4, Level I, II, III |
| **15 Lot Size Ranges** | 2–8 up to 500,001+ |
| **Quick Presets** | Food/Pharma, Automotive, Consumer, Cosmetic |
| **Industry Guide** | 15 industries with recommended AQL levels |
| **Arrow Resolution** | Automatic code-letter resolution per Z1.4 standard |
| **100% Inspection Alert** | Warns when sample size ≥ lot size |
| **Accept/Reject Decision** | Real-time pass/fail with color indicators |
| **Offline Ready** | Single HTML file, no internet required |
| **Responsive** | Works on desktop, tablet, and mobile |

---

## 🏭 Supported Industries

| Industry | Critical | Major | Minor |
|----------|----------|-------|-------|
| 🍱 Food & Beverage | 0.065 | 0.40 | 2.5 |
| 💊 Pharmaceutical | 0.065 | 0.25 | 1.0 |
| 🚗 Automotive | 0.065 | 0.25 | 1.0 |
| ✈️ Aerospace | 0.065 | 0.10 | 0.65 |
| 📱 Electronics | 0.065 | 0.40 | 2.5 |
| 🧱 Plastic Injection | 0.065 | 0.40 | 2.5 |
| 👕 Textile / Garment | 0.065 | 1.0 | 2.5 |
| 📦 Consumer Goods | 0.065 | 1.0 | 4.0 |
| ...and 7 more | | | |

---

## 🚀 Quick Start

### Option 1: Download and Open
1. Download `index.html`
2. Double-click to open in any browser
3. Start inspecting!

### Option 2: Host on GitHub Pages
See [Deployment Guide](#-deployment-to-github-pages) below.

---

## 📖 How to Use

```
1. Select AQL Level (or use Quick Preset)
2. Choose Inspection Level (default: Level II)
3. Enter Lot Size (e.g., 1000)
4. Enter number of defects found
5. Click "Calculate" or press Enter
6. Read the Accept/Reject decision
```

### Example

| Input | Value |
|-------|-------|
| AQL Level | 0.40 (Strict) |
| Inspection Level | Level II |
| Lot Size | 1,000 |
| Defects Found | 1 |

**Result:** Sample Size = 125, Ac = 1, Re = 2 → ✅ **ACCEPT**

---

## 🌍 Deployment to GitHub Pages

### Step 1: Create Repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `aql-sampling-dashboard`
3. Set to **Public**
4. Click **Create repository**

### Step 2: Upload Files

**Option A — Web Upload (Easy)**

1. Click **"Add file"** → **"Upload files"**
2. Drag & drop `index.html`, `README.md`, `LICENSE`
3. Click **"Commit changes"**

**Option B — Git Command Line**

```bash
git init
git add .
git commit -m "Initial commit: AQL Sampling Dashboard"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/aql-sampling-dashboard.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / **/ (root)**
4. Click **Save**
5. Wait 1-2 minutes

### Step 4: Access Your Site

Your dashboard is now live at:

```
https://YOUR-USERNAME.github.io/aql-sampling-dashboard/
```

---

## 📐 Standards Reference

- **ANSI/ASQ Z1.4** — Sampling Procedures and Tables for Inspection by Attributes
- **ISO 2859-1:2023** — Sampling procedures for inspection by attributes (international equivalent)
- **MIL-STD-1916** — Department of Defense preferred methods

---

## 🛠️ Technical Details

- **Single file** — Everything in one `index.html` (HTML + CSS + JS)
- **Zero dependencies** — No frameworks, no build tools, no npm
- **Fonts** — DM Sans + JetBrains Mono (Google Fonts CDN)
- **Browser support** — Chrome, Firefox, Safari, Edge (all modern browsers)
- **File size** — ~25 KB

---

## 📄 License

MIT License — free for personal and commercial use.

---

## 🙏 Credits

Created for **Salee Industry Public Company Limited** Quality Control Department.

Data based on ANSI/ASQ Z1.4-1993 / ISO 2859-1:2023 standard tables.
