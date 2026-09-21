# Aarti — Personal Portfolio Website

An ultra-modern, high-performance portfolio website built for **Aarti** (B.Tech Computer Science Core, Lovely Professional University).

Inspired by the design of [puskar-kumar-portifolio.vercel.app](https://puskar-kumar-portifolio.vercel.app/), featuring:
- Custom dark-theme ambient mesh gradient background with glowing aura accents
- Focused high-resolution portrait frame featuring Aarti's uploaded photo
- **CampusSwap** (Live student notes and books sharing platform)
- **Arduino & ESP32 Smart Home Automation System**
- Full skills matrix (AI tools, web development, core CS, and leadership)
- Academic credentials (CGPA 9.24 at LPU)
- Fully responsive across desktop, tablet, and mobile devices

## Structure

```
aarti-portfolio/
├── index.html                  # Main website
├── assets/
│   ├── aarti-portrait.jpg      # High-res 4:5 framed portrait
│   ├── aarti-square.jpg        # Centered square avatar
│   └── aarti.jpg               # Original uploaded photo
└── README.md                   # Documentation
```

## How to View Locally

Simply double-click `index.html` to open it in any web browser (Chrome, Safari, Edge, Firefox), or run a lightweight local server:

```bash
cd /Users/puskarkumar/.gemini/antigravity/scratch/aarti-portfolio
python3 -m http.server 3000
```
Then visit: `http://localhost:3000`

## How to Deploy to Vercel

You can deploy this portfolio to Vercel for free in seconds:

1. Install the Vercel CLI (if not already installed):
   ```bash
   npm i -g vercel
   ```
2. In this directory, run:
   ```bash
   vercel
   ```
3. Follow the CLI prompts to link and deploy!
