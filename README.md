# Dyslexia Reader Landing Page

This repository contains the single-page, conversion-optimized marketing site for **Dyslexia Reader** (`dyslexiareader.com`). It serves as the primary landing page for cold emails, ad campaigns, outreach materials, and conference handouts.

The site is designed to feel welcoming, direct, and focused on empowering children with dyslexia to develop literacy and independent reading skills. 

## 🛠 Tech Stack

- **Framework**: [Astro](https://astro.build) (Static Site Generation)
- **Styling**: Standard CSS (Custom properties based on Samartya Apps brand guidelines)
- **Deployment**: Configured for Cloudflare Pages via `@astrojs/cloudflare` adapter
- **Integrations**: Kit/ConvertKit API (v4) for waitlist signups

## 🏗 Project Structure

```text
/
├── public/
│   └── img/           # Logos, icons, and placeholder media
├── src/
│   ├── components/    # Reusable page sections (Hero, Features, Pricing, etc.)
│   ├── layouts/       # Base HTML layout including SEO and Schema markup
│   ├── pages/         # Main application routes (index.astro)
│   └── styles/        # Global CSS variables and utility classes
└── astro.config.mjs   # Astro configuration (Cloudflare adapter)
```

## 🚀 Running Locally

1. **Install Dependencies**
   ```sh
   npm install
   ```

2. **Start the Development Server**
   ```sh
   npm run dev
   ```
   The site will be available at `http://localhost:4321`.

3. **Build for Production**
   ```sh
   npm run build
   ```
   The production-ready site will be generated in the `dist/` directory.

## 🔑 Key Features & Components

- **Empathy-First Copy**: Focuses on equity and advocacy rather than disability pity.
- **Scannable Features**: 11 core app capabilities categorized logically for quick reading.
- **Kit API Waitlist**: A functional waitlist form that connects directly to Kit's v4 API (no server-side proxy needed).
- **Pricing Toggle**: A vanilla JavaScript toggle to switch pricing views between USD and INR.
- **SEO Optimized**: Includes canonical URLs, Open Graph tags, Twitter card tags, and detailed `SoftwareApplication` Schema.org JSON-LD.
- **Native Accordions**: The FAQ section utilizes native HTML `<details>` and `<summary>` tags for lightweight, accessible interactivity without massive JS payloads.
