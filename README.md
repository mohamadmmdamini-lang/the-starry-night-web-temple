# 🌌 The Starry Night — Interactive Portfolio

An immersive and interactive portfolio website inspired by Vincent van Gogh's *The Starry Night*. Built with modern web technologies, featuring animated artwork, layered visual scenes, smooth scrolling, and a bilingual experience.

## ✨ Features

- **Interactive Experience:** A cinematic, scroll-based exhibition.
- **Animated Scenes:** Dynamic clouds, glowing windows, and animated illustrations.
- **Responsive Design:** Optimized for desktop and mobile devices.
- **Bilingual Support:** English and Persian (RTL) language switching.
- **Modern UI:** Glassmorphism panels, elegant typography, and smooth transitions.
- **Contact Section:** Dedicated section for social media and email connections.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| React 19 | UI development |
| TypeScript | Type-safe development |
| HTML5 | Web structure |
| CSS3 | Styling and animations |
| Tailwind CSS 4 | Utility-first styling |
| JavaScript | Interactive functionality |
| GSAP | Advanced animations |
| Node.js | Development and server runtime |
| Vite | Development server and build tool |
| TanStack Start | Application routing and server rendering |
| Radix UI | Accessible UI components |

## 📁 Project Structure

```text
the-starry-night/
│
├── public/
│   ├── favicon.ico
│   └── robots.txt
│
├── src/
│   ├── assets/
│   │   ├── clouds-front.webp
│   │   ├── clouds-mid.webp
│   │   ├── starry-night.webp
│   │   └── village-night.webp
│   │
│   ├── components/
│   │   ├── exhibition/
│   │   │   ├── AnimatedCloudLayers.tsx
│   │   │   ├── AnimatedHands.tsx
│   │   │   ├── AnimatedWindows.tsx
│   │   │   ├── CloudScene.tsx
│   │   │   ├── OpeningScene.tsx
│   │   │   ├── VillageScene.tsx
│   │   │   └── ExhibitionStage.tsx
│   │   │
│   │   └── ui/
│   │
│   ├── content/
│   │   └── site.ts
│   │
│   ├── hooks/
│   ├── lib/
│   ├── routes/
│   ├── styles.css
│   ├── router.tsx
│   ├── server.ts
│   └── start.ts
│
├── package.json
├── package-lock.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

## ⚙️ Installation & Setup

### 1. Install Requirements

Make sure you have the following installed:

- Node.js (20.19+ or 22.12+)
- npm
- Visual Studio Code (recommended)

Check your installed versions:

```bash
node -v
npm -v
```

### 2. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 3. Open the Project

```bash
cd the-starry-night
```

### 4. Install Dependencies

The `node_modules` folder is not included in the repository.

Install all required packages using:

```bash
npm install
```

This command reads `package.json` and `package-lock.json` and automatically downloads the required dependencies into `node_modules`.

### 5. Start the Development Server

```bash
npm run dev
```

Open the local URL displayed in your terminal (usually):

```text
http://localhost:3000
```

## 🚀 Production Build

To create an optimized production build:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run build:dev` | Development-mode build |
| `npm run preview` | Preview production build |
| `npm run lint` | Run ESLint |
| `npm run format` | Format source files |
| `npm run test` | Run tests |
| `npm run test:watch` | Run tests in watch mode |

## 🎨 Design & Experience

The website is organized into four main chapters:

**01 — The Creation of Light**
- Cinematic opening scene
- Starry Night artwork
- Animated visual introduction

**02 — The Breathing Sky**
- Animated cloud layers
- About section
- Personal story and philosophy
- Skills showcase

**03 — The City That Never Sleeps**
- Interactive village scene
- Project showcase
- Selected works
- Experience and achievements

**04 — The Final Connection**
- Contact information
- Social media links
- Email connection

## 🌍 Customization

Most portfolio content is managed in:

```text
src/content/site.ts
```

You can customize:
- Your name and brand
- About section
- Skills and technologies
- Project descriptions
- Work experience
- Social media links
- English and Persian content

Remember to replace the placeholder contact information with your own details before publishing.

## 📌 Notes

- Do not upload `node_modules` to GitHub.
- Keep your `package-lock.json` in the repository.
- Never commit API keys, passwords, or private environment variables.
- Replace all placeholder content before deployment.

## 👨‍💻 Developer

**MN — Web Developer & UI/UX Designer**

Technologies: React.js • Node.js • JavaScript • PHP • HTML • CSS

📧 Email: oev.sites@gmail.com

💬 Telegram: https://t.me/oevproduct

---

*Designed and developed with creativity, code, and a little inspiration from the stars.*
