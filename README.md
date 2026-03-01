

## 🌏 Overview

**Aathi** (meaning "Origin" or "Beginning" in Tamil) is a Digital Product Passport (DPP) platform designed to turn supply chain transparency into a marketing asset. It enables producers—from the lemon farmers of Puliyankudi to the silk weavers of Sankarankovil—to create verifiable, beautiful digital twins for their products.

Scanning an **Aathi QR Label** reveals the full story of a product: its ingredients, its physical journey across the Western Ghats, and the hands that made it.

## ✨ Key Features

- **🛡️ Immutable Lineage:** Track every component with a verifiable chain of custody. Link internal passports (e.g., linking a Glass Jar passport to a Honey passport) to build a navigable supply web.
- **🚚 Logistics Journey:** A visual, chronological timeline of every batch's physical movement, from the forest floor to the shop shelf.
- **🎨 Premium UI/UX:**
  - **Glassmorphism Design:** Modern, frosted-glass aesthetics with a professional finish.
  - **Mobile-First Experience:** Optimized for both field workers (adding events) and shoppers (viewing passports).
  - **Animated Micro-Interactions:** Smooth transitions and hover effects using Tailwind CSS v4.
- **📍 Localized Branding:** Full support for Tamil script (ஆதி) and localized product data focused on the specific market context of Southern Tamil Nadu.
- **🖨️ QR & NFC Labels:** Instant generation of scan-ready labels with high-resolution QR codes and product IDs.
- **📊 Admin Console:** A powerful, full-page management dashboard providing global visibility into the verifiable supply chain.

## 🛠️ Technology Stack

- **Framework:** [React 18](https://reactjs.org/) with [Vite](https://vitejs.dev/)
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com/) (using the latest `@theme` and `@apply` paradigms)
- **Icons:** [Lucide React](https://lucide.dev/)
- **QR Engine:** `qrcode.react`
- **Navigation:** [React Router 6](https://reactrouter.com/)
- **Image Generation:** [Unsplash / Picsum](https://unsplash.com/) for high-quality product visualization.

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation
1. Clone the repository:
   ```bash
   git clone [repository-url]
   cd kotravai-qr-generator
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Build for production:
   ```bash
   npm run build
   ```

## 📂 Project Structure

- `src/App.tsx`: The heart of the application, containing the multi-view architecture (Landing, Admin, Passport).
- `src/index.css`: Custom design tokens, glassmorphism utilities, and keyframe animations using Tailwind CSS v4.
- `public/`: Static assets and icons.

---

<div align="center">
  <p>© 2026 Aathi Digital Product Passport. Built for a circular, transparent future.</p>
  <p><b>ஆதி - வெளிப்படையான எதிர்காலத்திற்காக</b></p>
</div>
