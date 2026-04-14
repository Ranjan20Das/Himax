# Himax — Architectural & Structural Glazing Excellence

Himax is a premium full-stack digital platform designed for a leading provider of bespoke structural and architectural glazing solutions. The project focuses on "architectural storytelling," trading dense product catalogs for an immersive, minimalist experience that mirrors the transparency and precision of the glass itself.

**live demo** :- https://himax-beta.vercel.app/

## 🌟 Overview

Himax serves as a high-end portfolio and lead-generation engine. It bridges the gap between technical engineering and aesthetic design, allowing architects and developers to visualize complex glazing integrations in prestigious residential and commercial spaces.

## 🚀 Key Features

- **Interactive Navigation Island:** A central, dynamic UI component that updates based on scroll depth and user location, providing an intuitive, friction-less browsing experience.
- **Visual Storytelling:** High-contrast layouts and evocative imagery that prioritize "materiality" and technical elegance.
- **Product-Project Linking:** A deep-linked database where specific glazing products (e.g., Slimline Sliding Doors, Glass Floors) are showcased within real-world project case studies.
- **Dynamic Quote Engine:** A bespoke "Get a Quote" feature that generates tailored requests based on technical specifications provided by the user.
- **Advanced Motion Design:** Powered by GSAP and ScrollTrigger, featuring mask-wipe transitions and SVG animations that bring the structural details to life.

## 🛠 Tech Stack

### Frontend
- **Framework:** [React.js](https://React.com/)  for Designing the web page.
- **Styling:** Tailwind CSS or SCSS with a focus on negative space and technical typography.
- **Animations:** [GSAP](https://greensock.com/gsap/) (GreenSock Animation Platform) for smooth, scroll-bound interactions.

### Backend & CMS
- **Headless CMS:** [Storyblok](https://www.storyblok.com/) to manage hierarchical content, product specifications, and project portfolios.
- **Hosting:** [Vercel](https://vercel.com/) for edge-network performance and CI/CD.

## 📂 Project Structure

```text
├── assets/          # Global styles, fonts, and static media
├── components/      # Reusable Vue components (Nav Island, Project Card)
├── layouts/         # Page templates (Default, Project, Product)
├── pages/           # Route-based views (Home, Approach, Collection)
├── plugins/         # Third-party integrations (GSAP, Analytics)
└── store/           # Global state management for quote generation

📐 Implementation Focus
Precision: Minimalist UI with technical typography to "speak the architect's language."

Transparency: Using "Liquid Glass" design principles—refractive elements and translucent layers.

Performance: Optimized asset loading and static site generation to ensure the high-res imagery doesn't compromise speed.

🛠 Installation & Development
Bash

# Install dependencies
npm install

# Run development server with hot reload
npm run dev

# Build for production
npm run build

# Lint and fix files
npm run lint
🏛 Rebranding Note
This project has been transitioned from Fluid Glass to Himax. All branding assets, internal links, and metadata have been updated to reflect the new identity.


### Strategic Recommendation for "Himax"
To truly capture the essence of the original site, ensure your CSS incorporates **Glassmorphism**—using `backdrop-filter: blur()` and subtle borders to mimic the physical properties of structural glass.


Made by Ranjan Das
if you like it give the repo a ⭐.
