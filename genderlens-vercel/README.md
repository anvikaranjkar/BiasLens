# GenderLens

AI-powered gender bias detection. Two tools, one mission.

## Project structure

```
/
├── index.html          → Landing page (genderlens.app)
├── detect/
│   └── index.html      → GenderLens bias detector (/detect)
├── learn/
│   └── index.html      → The Language of Bias guide (/learn)
└── vercel.json         → Routing config
```

## Deploy to Vercel

1. Push this folder to a GitHub repo
2. Go to vercel.com → New Project → Import your repo
3. Click Deploy — no build settings needed

Or use Vercel CLI:
```bash
npm i -g vercel
vercel
```

## Local development

```bash
# Serve locally (required — Chrome blocks API calls from file://)
python3 -m http.server 8080
# Open http://localhost:8080
```

## Made by Anvi Karanjkar
