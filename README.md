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
- **Dark/light mode** toggle
- **Built-in transparency notes** so everything is easy to understand

---

## How to Run

1. Download `index.html`
2. Open it in any browser (no server needed)
3. Or push to GitHub and enable **GitHub Pages**

---

## Financial Assumptions & Disclosures

**This is for educational and illustrative purposes only.** It is **not financial advice**.

### HomeTap (full transparency)
- **4.5% origination fee** deducted upfront — matches Hometap’s actual 2026 rate
- **40% equity share** repaid at end of 10-year term (**conservative/simplified estimate**)
  - Real HomeTap offers are typically 25–35% for a pull of this size, which would mean **even higher profit** than shown
- **No monthly payments** required
- You can settle early (sell or refinance) at any time

> *Note on the page: “We used a conservative 40% share (real HomeTap offers are typically 25–35% for this size pull, which would give you even more profit).”*

### HELOC
- Standard 10-year amortizing loan with monthly payments
- Interest rate set by slider

### Bitcoin Power Law
- Based on Giovanni Santostasi’s long-term power-law trend
- Base case ($1.8M in 2036) closely matches current fair-value projections
- Post-2036 growth is a simple approximation for clarity

All numbers are projections based on your inputs. Past performance is not indicative of future results.

---

## Tech Stack

- HTML + Tailwind CSS (via CDN)
- Chart.js
- Vanilla JavaScript
- Fully self-contained single file

---

## Roadmap / Future Versions

This v1 was intentionally personal. Planned improvements:

- Remove “Mom & Dad” branding → neutral “Home Equity + Bitcoin Calculator”
- Flexible loan term (choose any end year)
- Support for more products (Unison, Point, etc.)
- Export results as PDF/image
- LocalStorage for saving inputs
- Even more transparency and accessibility features

---

## Credits

- Bitcoin Power Law model → Giovanni Santostasi
- Tailwind CSS via CDN
- Chart.js
- CoinGecko API
- Built with love for my parents ❤️

---

## License

MIT License — feel free to fork, modify, and use however you like.

---

**Made in April 2026**  
If this helps spark a good conversation with your own family, that’s the real win.