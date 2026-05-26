# 🚗 VehicleInfo Blog - Setup Guide

## ✅ What's Included
- `index.html` → Your public blog website
- `admin.html` → Admin panel (AI generate + WhatsApp alerts)
- `.github/workflows/deploy.yml` → Auto deploy to GitHub Pages

---

## 🚀 Step-by-Step GitHub Pages Setup

### Step 1 — Create Repository
1. Go to [github.com](https://github.com) and login
2. Click **"New repository"** (green button)
3. Name it: `vehicleinfo-blog`
4. Set to **Public**
5. Click **"Create repository"**

### Step 2 — Upload Files
1. Click **"uploading an existing file"** link
2. Drag and drop ALL files from this folder
3. Click **"Commit changes"**

### Step 3 — Enable GitHub Pages
1. Go to your repo → **Settings**
2. Click **Pages** (left sidebar)
3. Under "Source" → select **GitHub Actions**
4. Wait 2-3 minutes

### Step 4 — Your Website is Live! 🎉
- Blog: `https://YOUR-USERNAME.github.io/vehicleinfo-blog/`
- Admin: `https://YOUR-USERNAME.github.io/vehicleinfo-blog/admin.html`

---

## 🤖 AI Blog Generation Setup

1. Open **admin.html** on your website
2. Go to **Settings** → Enter your Anthropic API key
   - Get free key at: [console.anthropic.com](https://console.anthropic.com)
3. Go to **AI Generate Blog**
4. Pick a topic → Click **Generate Blog with AI**
5. Click **Publish + WhatsApp** → Done!

---

## 📱 WhatsApp Alert Setup

### Option A — Manual (Click to Send)
1. Admin panel → **WhatsApp Setup**
2. Enter your phone number with country code (e.g. `919876543210`)
3. Click **Save Settings**
4. When you publish → click **Send WhatsApp Alert** → WhatsApp opens → Send!

### Option B — Auto Send (CallMeBot - Free)
1. Send WhatsApp to `+34 644 63 20 91` with message: `I allow callmebot to send me messages`
2. You'll receive an API key
3. Admin panel → WhatsApp Setup → Enter API key
4. Now WhatsApp sends automatically on publish! ✅

---

## 📝 How to Post a New Blog

1. Open your admin panel
2. Click **AI Generate Blog**
3. Pick topic or type your own
4. Click **Generate Blog with AI** (takes 10-20 seconds)
5. Review and edit if needed
6. Click **Publish + WhatsApp** 🚀

Your blog is live + WhatsApp sent automatically!
