# Threefold Credit Union - Deployment Instructions

## Quick View (Local)

Open the files directly in your browser:

```bash
cd /Users/nathanielsteinrueck/threefold-credit-union
open index.html
```

Or start a local server:

```bash
python3 -m http.server 8000
# Then visit: http://localhost:8000
```

## Share via GitHub

### Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. Repository name: `threefold-credit-union`
3. Description: "Banking for the Anthroposophic Health Movement - Website & Prototype"
4. Make it **Public**
5. **Do NOT** initialize with README, .gitignore, or license
6. Click "Create repository"

### Step 2: Push Your Code

The repo is already initialized locally. Just run:

```bash
cd /Users/nathanielsteinrueck/threefold-credit-union

# Update the remote URL with your actual GitHub username
git remote set-url origin https://github.com/YOUR-USERNAME/threefold-credit-union.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repo: `https://github.com/YOUR-USERNAME/threefold-credit-union`
2. Click **Settings** tab
3. Scroll to **Pages** section (left sidebar)
4. Under "Source", select **main** branch
5. Click **Save**
6. Your site will be live at: `https://YOUR-USERNAME.github.io/threefold-credit-union/`

Share this URL with Mark!

## Alternative: Netlify Drag & Drop (Even Easier!)

1. Go to https://app.netlify.com/drop
2. Drag the entire `threefold-credit-union` folder onto the page
3. Get instant URL like: `https://threefold-credit-union.netlify.app`
4. Share with Mark immediately!

---

## What's Included

### Landing Page (`index.html`)
- Modern Mercury-inspired fintech design
- Vision, features, timeline sections
- USD accounts and Anthrobucks explanation
- Team section
- Responsive design

### Prototype Dashboard (`prototype.html`)
- Account overview (Checking, Savings, Anthrobucks)
- Impact metrics banner
- Quick actions (Send, Buy AB, Donate Leaven)
- Transaction history with SVG icons
- **AI Business Intelligence Chat** - Fixed chat widget in bottom right
  - Answers questions about payroll, staff, expenses
  - Shows Anthrobucks circulation trends
  - Provides financial insights
  - Smart contextual responses

### Features Demonstrated

**AI Chat Can Answer:**
- "What was my total payroll last month?" → Detailed staff breakdown
- "Show me my Anthrobucks circulation trends" → Velocity and network stats
- "How much have I earned from patient AB payments?" → Revenue breakdown
- Custom questions about staff, expenses, Leaven donations

**Icons:**
- All emojis replaced with clean SVG icons
- Consistent design system
- Professional fintech look

---

## File Structure

```
threefold-credit-union/
├── index.html           # Landing page
├── prototype.html       # Dashboard with AI chat
├── netlify.toml        # Netlify config
├── README.md           # Project overview
└── DEPLOYMENT.md       # This file
```

---

## Quick Test Locally

```bash
cd /Users/nathanielsteinrueck/threefold-credit-union
open prototype.html
```

Click the chat bubble in the bottom-right corner to test the AI assistant!
