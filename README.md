# High-Converting Cleaning Service Landing Pages

A collection of professional, mobile-first, and highly optimized landing pages designed specifically for US-based home service businesses (Cleaning, Detailing, etc.).

These templates are built around the **PAS (Problem-Agitate-Solve) psychological framework** to maximize lead generation, reduce bounce rates, and ensure ADA compliance.

## 🚀 Live Demos

* **[Portfolio Hub (index.html)](#)** - The main hub showcasing all templates.
* **[FreshSpace Cleaning](freshspace.html)** - Clean, high-energy layout focused on immediate trust building.
* **[Austin Spotless](austin-spotless.html)** - Soft UI tailored for eco-friendly and family-oriented cleaning services.
* **[Seattle Sparkle](seattle-sparkle.html)** - Sophisticated design ideal for premium deep cleaning and detailing packages.

---

## 🛠 Tech Stack

* **HTML5 Semantic Markup**
* **Tailwind CSS** (via CDN with custom tailwind.config for typography and brand colors)
* **Vanilla JavaScript** (IntersectionObservers for scroll animations and minimal DOM manipulation)
* **Google Fonts** (Inter & Outfit)

## 💡 Key Features & Best Practices

1. **Mobile-First Layout:**
   - Thumb-zone friendly CTA buttons (min 44x44px).
   - "Photo top, text bottom" order on mobile for maximum readability.
   - Hidden desktop elements correctly collapse into burger menus.
   
2. **High Conversion Architecture:**
   - Single dominant Call to Action.
   - Prominent trust signals ("Insured & Bonded", "5-Star Rated") placed strategically above the fold.
   - Form abandonment reduced through minimal input fields and risk-reversal subtext.
   - Click-to-call active links in the navigation bar.

3. **Accessibility (ADA) & Compliance (CCPA):**
   - High contrast text.
   - Semantic tags (`<main>`, `<section>`, `<nav>`).
   - Placeholder and `<label>` pairs on input fields.
   - Footer links addressing standard US privacy policies.

4. **Performance:**
   - Native lazy loading (`loading="lazy"`) for images below the fold.
   - No jQuery or heavy JS frameworks.

## 📁 Repository Structure

```
.
├── index.html               # Main portfolio showcase
├── freshspace.html          # Setup 1 (FreshSpace)
├── austin-spotless.html     # Setup 2 (Austin Spotless)
├── seattle-sparkle.html     # Setup 3 (Seattle Sparkle)
├── images/                  # Local optimized image assets
├── AI_PROMPT_GUIDELINES.md  # The exact prompts & rules used to generate these
└── README.md                # This documentation
```

## 📝 Usage

Simply clone the repository and open `index.html` in your browser. All assets are styled with Tailwind CDN and native assets, meaning no build step (`npm start` or build tools) is required to view or deploy these templates.

Deploy instantly to GitHub Pages, Netlify, or Vercel.

## 🤖 Prompt Guidelines

This repository includes a powerful `AI_PROMPT_GUIDELINES.md` document. It contains the exact prompt architecture that was used to instruct an LLM as a "Senior Frontend Developer & US Conversion Rate Expert" to output these highly specific, conversion-focused templates. Feel free to use it to generate infinite variations of these landing pages.

---
_Developed with a focus on conversion rate optimization for local service businesses._
