# 🚀 Deploy K-Pop Demon Hunters

## Option A — GitHub + Vercel (recommended)

### 1. Create a GitHub repo
Go to https://github.com/new and create a repo called `kpop-demon-hunters` (public or private).

### 2. Push the code
Open a terminal in this folder and run:
```bash
git remote add origin https://github.com/YOUR_USERNAME/kpop-demon-hunters.git
git push -u origin main
```

### 3. Deploy on Vercel
1. Go to https://vercel.com/new
2. Click **"Import Git Repository"**
3. Select your `kpop-demon-hunters` repo
4. Leave all settings as defaults — click **Deploy**
5. Your game will be live at `https://kpop-demon-hunters.vercel.app` 🎉

---

## Option B — Vercel Drop (fastest, no GitHub needed)
1. Go to https://vercel.com/new
2. Drag and drop this entire folder onto the page
3. Done — live in seconds!

---

## Option C — Vercel CLI
```bash
npm i -g vercel
vercel deploy --prod
```
