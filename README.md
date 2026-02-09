# Threefold Credit Union - Website & Prototype

A modern, Mercury-inspired banking interface for the anthroposophic health movement.

## Files
- `index.html` - Landing page
- `prototype.html` - Interactive dashboard prototype

## Quick Start - Local Preview

```bash
cd /Users/nathanielsteinrueck/threefold-credit-union
python3 -m http.server 8000
```

Then open: http://localhost:8000

## Deploy to Netlify (Easiest Option)

### Option 1: Drag & Drop
1. Go to https://app.netlify.com/drop
2. Drag the `threefold-credit-union` folder onto the page
3. Get instant URL like: `https://threefold-credit-union.netlify.app`

### Option 2: Git Deploy
```bash
cd /Users/nathanielsteinrueck/threefold-credit-union
git init
git add .
git commit -m "Initial commit"
gh repo create threefold-credit-union --public --source=. --remote=origin --push
```

Then connect to Netlify via GitHub.

## Deploy to Vercel

```bash
cd /Users/nathanielsteinrueck/threefold-credit-union
npx vercel --prod
```

## Deploy to GitHub Pages

```bash
cd /Users/nathanielsteinrueck/threefold-credit-union
git init
git add .
git commit -m "Initial commit"
gh repo create threefold-credit-union --public --source=. --remote=origin --push
```

Then enable GitHub Pages in repo settings.

## Features

### Landing Page
- Modern fintech design inspired by Mercury
- Comprehensive explanation of USD and Anthrobucks accounts
- Anthrobucks lifecycle visualization
- Timeline and team sections

### Prototype Dashboard
- Account overview (Checking, Savings, Anthrobucks)
- Recent transaction history
- Quick actions (send, buy AB, donate Leaven)
- Network directory showing AB-accepting businesses
- Impact metrics showing community contribution
