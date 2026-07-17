<div align=center>

# SplitMate 🌿

### Fair bill splitting, wrapped in a playful Kamakura summer experience.

Split food costs, discounts, and delivery fees in seconds.<br>
No account, no backend, and no installation required.

**ไทย** · **English** · **日本語** · **中文**

</div>

---

## About SplitMate

SplitMate is a lightweight bill-splitting web app for shared meals. It distributes discounts proportionally, divides delivery fees equally, and produces a clear summary that is ready to copy or share with friends.

## Highlights

| | Feature |
|---|---|
| ⚖️ | Proportional discount allocation based on each person's food subtotal |
| 🧮 | Satang-level calculations with deterministic remainder distribution |
| 👥 | Support for 2–10 people and a designated upfront payer |
| 🌏 | Complete Thai, English, Japanese, and Simplified Chinese interfaces |
| 💾 | Automatic local persistence for bill data and language preference |
| 📤 | Web Share integration with a clipboard fallback |
| ♿ | Keyboard navigation, screen-reader labels, and reduced-motion support |
| 🎐 | Subtle koto and fūrin sounds with an interactive Kamakura canvas scene |

## How to use it

1. Enter each person's name and food subtotal.
2. Add the total discount and delivery fee.
3. Select the person who paid upfront.
4. Choose **Calculate**.
5. Copy or share the settlement summary with the group.

## Calculation model

- Discounts are distributed in proportion to each person's food subtotal.
- Delivery fees are divided equally among everyone.
- All calculations use integer satang values.
- Remainders are distributed deterministically so individual totals always match the net bill.
- Applied discounts are capped at the total food subtotal.

## Run locally

SplitMate is a dependency-free static single-page app with no build step.

    git clone https://github.com/panyawat56/grabsplit-kamakura.git
    cd grabsplit-kamakura

Open **index.html** in a browser or serve the folder with any static file server.

## Built with

- Semantic HTML
- Responsive CSS
- Vanilla JavaScript
- Canvas 2D
- Web Audio API
- Web Share and Clipboard APIs
- Local Storage

## Privacy

All bill data is processed and stored locally on the device. SplitMate has no backend, analytics, account system, or data collection.

## Project structure

    .
    ├── index.html   # Interface, calculation engine, translations, canvas, and audio
    └── README.md    # Project documentation

---

<div align=center>

Made for fairer meals and easier friendships.  
**Split fairly with SplitMate.**

</div>
