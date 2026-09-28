# Hassan AI

A modern, dark-themed AI chat assistant with secure PIN-protected video generation.

![Hassan AI](https://img.shields.io/badge/Hassan%20AI-v1.0-3b82f6?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Deploy](https://img.shields.io/badge/Deploy-Vercel-black?style=for-the-badge)

---

## Features

- Clean chat interface inspired by modern AI assistants
- Helpful responses for explanations, coding, research, and general questions
- **PIN-protected video generation** (PIN: `67890`)
- Fully responsive (works on desktop and mobile)
- Zero dependencies — pure HTML, CSS & JavaScript
- Ready for GitHub + Vercel deployment

## Live Demo

After deploying to Vercel, your site will be available at:

```
https://your-repo-name.vercel.app
```

## How Video Protection Works

1. User asks to create/generate a video (e.g. “Create a video about space”)
2. A PIN modal appears
3. Correct PIN (`67890`) → video is generated
4. Wrong PIN or cancel → access denied, no video is created

## Getting Started

### Option 1: Open locally
Just open `index.html` in any modern browser.

### Option 2: Deploy to Vercel (Recommended)

1. Push this repository to GitHub
2. Go to [vercel.com](https://vercel.com) and sign in with GitHub
3. Click **Add New Project** → Import this repository
4. Click **Deploy**

Done! You’ll get a free public URL in under a minute.

### Option 3: Deploy with Vercel CLI
```bash
npm i -g vercel
vercel
```

## Project Structure

```
hassan-ai/
├── index.html      # Main application (self-contained)
├── README.md       # This file
├── .gitignore
└── vercel.json     # Optional Vercel config
```

## Customization

- Change the PIN in `index.html` → look for `const CORRECT_PIN = '67890';`
- Update the AI name, colors, or responses inside the same file
- All styles and logic are embedded — no build step required

## License

MIT — feel free to use and modify.
