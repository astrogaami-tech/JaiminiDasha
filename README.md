# Astrogaami — Jaimini Dasha Research Tool

A single-file, browser-based research tool for computing and exploring **Jaimini astrology dasha systems**. Paste in planetary longitudes (e.g. from JHora), and instantly generate South-Indian style charts, Chara Karakas, and 20+ Jaimini dasha sequences with mahadasha/antardasha breakdowns — all running locally in your browser, with no installation or backend required.

## ✨ Features

- **No installation needed** — a single `.html` file that runs entirely in your browser. No server, no build step, no dependencies to install.
- **South Indian chart display** — Rasi (D1) and Navamsa (D9) charts, with Lagna, planetary aspects, Karaka placements, Kendra/Argala highlighting, and reference-sign highlighting.
- **Multi-chart workspace** — load and compare multiple birth charts side by side in tabs.
- **JHora-compatible parser** — paste planetary "Body Longitude" output directly from JHora (or compatible formats); the parser is tolerant of common formatting variants.
- **Chara Karakas** — automatic computation of the 7/8-Karaka schemes (AK, AmK, BK, MK, PK, GK, DK, DK2), with both "degrees-first" and "minutes-first" tie-break methods.
- **20+ Jaimini Dasha systems**, including:
  - Chara, Narayana, Sthira, Mandooka, Shoola, Trikona, Brahma, Varnada
  - Atmakaraka (AK) Dasha, Yogardha, Navamsa Dasha, Trikuta, Nakshatra Dasha
  - Drig Dasha, Niryana Shoola Dasha
  - Karaka Dashas: Putra, Matri, Bhratri, Dara
  - Lagna-reference dashas: Hora Lagna, Pada (Arudha Lagna), Upapada (UL)
- **Mahadasha → Antardasha drill-down** with real calendar start/end dates.
- **Configurable computation options** — Chara Dasha sequence style, own-sign period length, Karaka tie-break method, dasha basis chart (D1/D9), and more.
- **PDF / print-ready reports** — generate a clean, shareable report with birth details, Karakas, planetary positions, and selected dasha tables, ready to print or save as PDF.
- **Astrologer/practice settings** — save your name, practice, and contact details locally (via `localStorage`) for use in generated reports.
- **Built-in sample chart** — opens with a pre-loaded example so you can explore the tool immediately.
- **Fully client-side & private** — all calculations happen in your browser. No chart data is ever sent to a server.

## 🚀 Getting Started

1. Download `Jaimini_dashas_v1.html` from this repository.
2. Open the file directly in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Use the sample chart that loads automatically to explore the interface, or click **"New Chart"** / the input panel to paste your own JHora-style planetary longitude data.
4. Switch between dasha systems using the tabs, and click any mahadasha row to expand its antardashas.
5. Use the **Print/Report** option to generate a PDF-ready research report.

No build tools, package managers, or internet connection are required after the page has loaded (aside from the optional Google Fonts import).

## 📖 How to Use

1. **Input data** — Paste the "Body Longitude" block from JHora (include the Date of Birth line if you want accurate dasha timelines; add Hora Lagna if you plan to use Varnada Dasha).
2. **Choose options** — Set the number of Karakas (7 or 8), the tie-break method (degrees-first or minutes-first), Chara Dasha sequence style, own-sign period, and whether dashas are computed from the D1 (Rasi) or D9 (Navamsa) chart.
3. **Explore charts** — View the Rasi and Navamsa charts with planetary placements, Lagna, Karakas, and aspect/argala highlighting.
4. **Explore dashas** — Select any of the available dasha systems from the dasha bar to view its full mahadasha sequence with start/end dates; click a row to view antardashas.
5. **Generate a report** — Choose which sections and dasha systems to include, then export/print a polished PDF report for research or client use.

## 🛠️ Technical Notes

- Single self-contained HTML file — all CSS and JavaScript are inline.
- Uses `localStorage` only to persist astrologer/practice settings between sessions; no chart data is stored remotely.
- Pulls the "DM Sans" font from Google Fonts via CDN `@import`; the tool will still function without internet access, with the browser falling back to system fonts.
- All dasha algorithms (Chara, Narayana, Sthira, Mandooka, Shoola, Trikona, Brahma, Varnada, Yogardha, Trikuta, Nakshatra, Drig, Niryana Shoola, the Karaka dashas, and the Lagna-reference dashas) are implemented from classical Jaimini principles in plain JavaScript.

## 📜 License & Usage

This project is **open-source for personal, educational, and research use**.

**Commercial use** (paid services, apps, or products built on this tool) **requires explicit written consent from Astrogaami.**

Contact: [astrogaami.com](https://astrogaami.com)

Built with love for the global Jaimini astrology community. 🙏

## 🤝 Contributing

Issues, suggestions, and pull requests related to dasha calculation accuracy, UI improvements, or new Jaimini techniques are welcome. Please open an issue describing the change before submitting a pull request for significant features.

## ⚠️ Disclaimer

This tool is intended for research, educational, and personal study of Jaimini astrology. It is not a substitute for consultation with a qualified, experienced Jaimini astrologer. Always cross-verify calculations against classical texts and trusted software (e.g., JHora) before relying on them for important decisions.
