# FELDOR_HEALTH Frontend

Modern AI Cancer Detection Platform — Frontend

## Tech Stack
- Vanilla JavaScript (no framework)
- Tailwind CSS (via CDN)
- Font Awesome Icons
- Google Fonts (Plus Jakarta Sans, JetBrains Mono)

## Deployment

### 1. Update Backend URL

Edit `index.html` line 155:
```html
<script>
    window.API_URL = 'https://your-backend.vercel.app';
</script>
```

Or set environment variable in Vercel:
```
VITE_API_URL = https://your-backend.vercel.app
```

### 2. Deploy to Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Login
vercel login

# Deploy
vercel --prod
```

### 3. Or deploy via GitHub

1. Push this folder to a GitHub repo
2. Import repo in [vercel.com](https://vercel.com)
3. Framework preset: **Other**
4. Deploy

## File Structure
```
├── index.html          # Main HTML shell
├── app.js              # Complete SPA application
├── vercel.json         # Vercel routing config
├── .env.example        # Environment template
└── README.md           # This file
```

## Features
- Dashboard with stats & recent activity
- Breast & Cervical cancer upload modules
- AI report viewer with heatmaps
- Case history table with filters
- Review queue for clinicians
- AI model management page
