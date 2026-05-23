# SubSwap — AI School Scheduling

## Deploy to Render (Free)

### Step 1 — Push to GitHub
1. Create a new repo on [github.com](https://github.com/new)
2. Run these commands in this folder:
```bash
git init
git add .
git commit -m "Initial deploy"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/subswap.git
git push -u origin main
```

### Step 2 — Deploy on Render
1. Go to [render.com](https://render.com) and sign up / log in
2. Click **"New +"** → **"Web Service"**
3. Connect your GitHub account and select the `subswap` repo
4. Render auto-detects the settings from `render.yaml`, but confirm:
   - **Environment:** `Node`
   - **Build Command:** `npm install`
   - **Start Command:** `npm start`
   - **Plan:** Free
5. Click **"Create Web Service"**
6. Wait ~2 minutes for the build to finish
7. Your site will be live at `https://subswap.onrender.com` (or similar)

## Local Development
```bash
npm install
npm start
# Open http://localhost:3000
```
