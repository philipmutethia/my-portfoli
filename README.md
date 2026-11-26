# Mutethia Phillip — Premium Personal Portfolio (v2.0)

> **"Crafting Timeless Designs With Precision and Accuracy."**

A world-class, modern, minimalist personal portfolio crafted for **Mutethia Phillip** — Graphic Designer, Creative Designer, Web Designer & Digital Creative.

---

## 💎 Design Highlights

- **Aesthetic**: Apple-inspired minimalism meeting high-end creative studio aesthetics.
- **Color Palette**:
  - Deep Black Background (`#050505`)
  - Crisp White Typography
  - Subtle Grey Structural Surfaces (`#0d0d11`, `#1e1e28`)
  - Electric Blue Accents (`#0066FF`, `#00F0FF`) with subtle neon glow
- **Typography & Layout**: Generous spacing, micro-badges, clean optical balance, and strong visual hierarchy.
- **Interactivity**: Framer Motion entrance reveals, smooth tab transitions, full-screen project case study modal, and live photo replacement.

---

## 🚀 Sections Overview

1. **Navigation**: Fixed top bar with initials `MP.`, glassmorphism backdrop blur on scroll, section spy indicator, quick CTA button, and responsive mobile slide-in menu.
2. **Hero Section**:
   - Main headline: *"Designing Ideas Into Timeless Visual Experiences."*
   - Supporting text highlighting personal brand identity.
   - Dual CTAs: *Explore My Work* & *Let's Work Together*.
   - Professional studio portrait area with interactive preview & upload feature.
3. **Portfolio Section**:
   - Category filtering across 7 areas:
     - `All Projects`
     - `Logo Design`
     - `Branding`
     - `Social Media Design`
     - `Posters`
     - `UI/UX Design`
     - `Web Design`
   - Preserves all 4 authentic works from Mutethia Philip's live site:
     - *Abstract Dynamic Banner Design* (Branding)
     - *Crispy Samosa Promotional Campaign* (Social Media Design)
     - *Heineken Premium Beverage Showcase* (Posters)
     - *Levitating Gourmet Burger Visuals* (Social Media Design)
   - Additional curated case study showcases with clear `[Editable Placeholder]` markings.
   - Interactive Project Modal detailing process, deliverables, tools used, and final outcome.
4. **About Me**:
   - Creative Journey
   - Design Philosophy
   - Professional Interests
   - Problem-Solving Methodology
   - Visual progress indicators and verified software credentials (Adobe Photoshop, Illustrator, InDesign, Figma).
5. **Services**:
   - 7 Core Offerings:
     1. Graphic Design
     2. Logo Design and Brand Identity
     3. Social Media Design
     4. Poster & Promotional Design
     5. UI/UX Design
     6. Website Design
     7. Digital Branding
   - Each with dedicated icon, description, deliverables checklist, and "Start a Project" quick link.
6. **Creative Process**:
   - 5-stage timeline: `01 Discover` → `02 Concept` → `03 Design` → `04 Refine` → `05 Deliver`.
7. **Contact Section**:
   - Functional form: Name, Email, Project Type selector, and Brief message.
   - Direct connection via API or automated mail client dispatch to `phillipmutethia004@gmail.com`.
   - Direct WhatsApp instant chat button (+254 707 032 901).
   - One-click copy for email and phone.
   - Strong closing statement: *"Have an idea? Let's create something extraordinary."*
8. **Footer**:
   - Brand summary, quick navigation links, GMT+3 Nairobi timezone notice, and copyright.

---

## 🛠️ How to Customize

### Adding or Replacing Projects
All projects are defined in:
```
src/data/projects.ts
```
To add a new project, simply append an object to the `PROJECTS_DATA` array:
```ts
{
  id: "my-new-project",
  title: "Brand Name Campaign",
  category: "Branding",
  categorySlug: "branding",
  shortDescription: "Short summary...",
  image: "https://your-image-url.jpg",
  gallery: ["https://your-image-url.jpg"],
  toolsUsed: ["Adobe Illustrator", "Photoshop"],
  deliverables: ["Logomark", "Style Guide"],
  processSummary: "How you approached it...",
  outcome: "Results and impact..."
}
```

### Enabling Direct Email Forwarding
By default, the contact form pre-composes an email to `phillipmutethia004@gmail.com` without any setup needed.

If you want automated background email delivery without opening a mail client:
1. Get a free Access Key from [Web3Forms](https://web3forms.com).
2. Create a `.env.local` file in the project root:
   ```env
   WEB3FORMS_ACCESS_KEY=your_key_here
   ```
3. Restart or redeploy to Vercel.

---

## 💻 Local Development

```bash
# Navigate to project directory
cd "C:\Users\ADMIN\.gemini\antigravity\scratch\mutethia-philip-portfolio"

# Start the development server
npm run dev

# Open in your browser
http://localhost:3000
```

## 🚢 Deploy to Vercel

```bash
# Using Vercel CLI or connecting your GitHub repository
npx vercel
```
