# Microcopy — Ship69 Day 57

UI copy generator for designers. Describe a UI moment, pick a tone, get three variations of headline, subtext, and CTA — ready to paste.

## Stack
- Vanilla HTML/CSS/JS
- Vercel serverless function (backend API route)
- Groq API (Llama 3.3)

## Local dev
No build step needed. Open `index.html` directly for UI preview (API calls will fail locally without the backend route).

## Deploy to Vercel
1. Push to GitHub
2. Import repo in Vercel
3. Add environment variable: `GROQ_API_KEY` = your Groq API key
4. Deploy

## Environment variables
| Key | Value |
|-----|-------|
| `GROQ_API_KEY` | Your Groq API key from [console.groq.com](https://console.groq.com) |

## Project structure
```
microcopy/
├── index.html        # Main UI
├── api/
│   └── microcopy.js  # Serverless API route
├── vercel.json       # Routing config
└── README.md
```
