# 📊 Earned Value Analysis (EVA) Dashboard | アーンド・バリュー分析ツール

A bilingual web app for real-time project performance analysis and forecasting — built to support project managers and stakeholders with visually intuitive metrics, AI-driven reporting, and printable summaries.

> 🔧 Designed with PMBOK-compliant metrics  
> 🇯🇵 Works in English and Japanese  
> 💼 Built during internal digital transformation initiatives for the PMO

---

## 🧠 What This Project Does

This tool enables users to:

- Input key project data (BAC, duration, % complete, AC)
- Automatically or manually calculate:
  - Planned Value (PV)
  - Earned Value (EV)
  - SPI, CPI, SV, CV, VAC, TCPI, PPC
  - EAC (Optimistic, Most Likely, Pessimistic)
- Generate AI-based project performance narratives and status reports
- Switch between English and Japanese interfaces
- Download print-friendly PDF reports

---

## 🎯 Why It Matters

Project managers are often overwhelmed with raw metrics and disconnected reporting formats. This dashboard provides:

- ✨ A **real-time, bilingual interface**
- 📉 Visually clear EVA performance insights
- 🤖 **Gemini-powered AI summaries and stakeholder-tailored reports**
- 🖨️ PDF export with layout optimized for print and review meetings

> Originally built for use during internal Air Liquide C-IMP (Continuous Improvement) Green Belt reporting and PMO adoption planning.

---

## 🚀 Features

| Category | Feature |
|----------|---------|
| 📈 **Metric Calculation** | EV, PV, SV, CV, SPI, CPI, VAC, ETC, TCPI, and more |
| 🔁 **Auto vs Manual PV** | Select between automated S-curve logic or manual entry |
| 🧠 **AI Narrative & Report Generator** | Powered by Gemini, with language-specific tones |
| 🌐 **Bilingual Toggle** | Instant switch between English and Japanese |
| 📊 **Chart Visualization** | Dynamic PV/EV/AC chart with currency formatting |
| 📄 **PDF Report** | Download multi-page project summary report |
| 🗂️ **Tooltip Glossary** | Hover-based definitions for every metric (in both languages) |

---

## 🛠️ Tech Stack / Tools Used

- HTML, Tailwind CSS, Vanilla JS  
- Chart.js (for EVA visualizations)  
- jsPDF + html2canvas (PDF export)  
- Google Gemini API (AI narrative + stakeholder-specific reporting)  
- Manual JSON translations (EN/JA)

---

## 🌐 Live Demo

👉 [https://khanhaissam.github.io/earned-value-dashboard/](https://khanhaissam.github.io/earned-value-dashboard/)

---

## 🧪 How to Run This Project

> No build required — this is a static HTML app. Just clone and open.

### Step 1: Download & Run

```bash
git clone https://github.com/yourusername/earned-value-dashboard.git
cd earned-value-dashboard
open index.html
