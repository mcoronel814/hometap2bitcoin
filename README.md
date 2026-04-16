# Mom & Dad’s Bitcoin Move

**A simple, interactive tool comparing three ways to unlock home equity for Bitcoin: HomeTap, HELOC, or Do Nothing.**

Built as a personal pitch for my parents in April 2026. It uses real-time Bitcoin pricing, home appreciation sliders, and **Giovanni Santostasi’s Bitcoin Power Law model** to project wealth outcomes through 2040.

This is **v1** — a heartfelt, single-file HTML presentation made specifically for my mom and dad. Future versions will be more generic (no “Mom & Dad” branding) and add flexible loan terms (custom end dates instead of being locked to 2036/10 years).

---

## Features

- **Interactive sliders** for home value, cash pulled, appreciation rate, HELOC rate, and current BTC price
- **Live Bitcoin price** from CoinGecko (with refresh button)
- **Three Bitcoin scenarios** powered by Santostasi’s Power Law model:
  - Worst Case — $800k in 2036
  - **Base Case** — $1.8M (Power Law fair-value trend)
  - Bull Case — $2.5M
- **Clear side-by-side comparison** of HomeTap vs HELOC vs Do Nothing
- **Wealth-over-time chart** (2026–2040) using Chart.js
- **Fully responsive** design (works great on phones)
- **Dark/light mode** toggle with persistence-ready code
- **Zero dependencies** — single HTML file, no build step

---

## How to Run

1. Download `index.html`
2. Open it in any browser (Chrome, Safari, Firefox, etc.)
3. No server needed — everything runs locally

Or deploy instantly:
- Push to GitHub → enable **GitHub Pages** (Settings → Pages → Deploy from main branch)

---

## Financial Assumptions & Disclosures

**This is for educational and illustrative purposes only.** It is **not financial advice**.

### HomeTap Model
- 4.5% origination fee (deducted upfront — matches Hometap’s actual 2026 rate)
- 40% equity share paid back at end of 10-year term (conservative/simplified estimate)
- No monthly payments

### HELOC Model
- Standard amortizing 10-year loan with monthly payments
- Interest rate set by slider

### Bitcoin Power Law
- Uses Giovanni Santostasi’s long-term power-law trend as the foundation
- The “Base Case” ($1.8M in 2036) closely aligns with current public projections of the fair-value line
- Post-2036 growth is approximated to keep the model simple and visual

All numbers are projections based on your inputs. Past performance and power-law trends do not guarantee future results.

---

## Tech Stack

- **HTML + Tailwind CSS** (via CDN)
- **Chart.js** for the wealth projection chart
- Vanilla JavaScript (no frameworks)
- Fully self-contained in one file

---

## Roadmap / Future Versions

This v1 was intentionally personal and focused on my parents. Planned improvements for public/generic versions:

- Remove “Mom & Dad” branding → make it neutral (“Home Equity + Bitcoin Calculator”)
- Flexible loan term (choose any end year instead of fixed 2036/10 years)
- More home equity products (Unison, Point, etc.)
- Custom Bitcoin scenarios + full power-law formula input
- Export results as PDF or image
- LocalStorage saving of inputs
- Mobile-first enhancements and accessibility polish

---

## Credits

- Bitcoin Power Law model → Giovanni Santostasi
- Tailwind CSS via CDN
- Chart.js
- CoinGecko API for live BTC price
- Built with love for my parents ❤️

---

## License

MIT License — feel free to fork, modify, and use however you like.  
If you make a cooler version, I’d love to see it!

---

**Made in April 2026**  
If this helped spark a conversation with your own family, that’s the real win.