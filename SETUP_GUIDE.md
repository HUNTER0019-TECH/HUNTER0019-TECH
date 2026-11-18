# 🍥 Hunter's Naruto Arc GitHub Profile — Setup Guide

Yeh wahi viral Naruto-themed GitHub Profile hai jo Instagram reel mein dikhaya gaya tha, jisme animated Shinobi hero banner, Team 7 dance animation, Ninja ID card, Jutsu arsenal tech stack, 3D contribution village, aur Chakra Snake animation shamil hain — sab kuch **Hunter** ke naam se customize kiya gaya hai!

---

## 📁 Repository Files Overview

- **`README.md`**: Main profile file jisme saare animated banners, badges, tables aur gifs set hain.
- **`hero.svg`**: Animated Hero Shinobi banner customized with **Hunter** & cycling tech titles.
- **`ninja-id.svg`**: Konoha Ninja Registration Card & Live Field Stats dashboard.
- **`ninja-way.svg`**: "My Ninja Way" philosophy & architecture showcase banner.
- **`jutsu-stack.svg`**: Jutsu Arsenal / Tech stack badges banner.
- **`connect.svg`**: Join the Squad / Social connect banner.
- **`team7-dance.gif`, `rasengan-run.gif`, `chibi-walk.gif`**: Animated Naruto stickers & GIFs.
- **`.github/workflows/profile-3d.yml`**: Roz raat ko aapka 3D contribution city automatically render karega.
- **`.github/workflows/github-snake.yml`**: Contribution grid par chakra snake animated game chalayega.

---

## 🚀 Setup Kaise Karein (Step-by-Step)

### Step 1: GitHub par Special Repository banayein
1. Apne GitHub account mein login karein: [github.com](https://github.com).
2. Top right mein **`+`** icon par click karein aur **"New repository"** select karein.
3. **Repository Name** mein apna **exact GitHub Username** dalein.
   *(Jaise agar aapka username `hunter` hai, toh repository ka naam bhi `hunter` hoga. GitHub ek special message dikhayega: "You found a secret!").*
4. Repository ko **Public** select karein.
5. "Add a README file" ko **UNCHECK** rehne dein (kyunki hamare paas already customized README hai).
6. **"Create repository"** par click karein.

---

### Step 2: Files Upload Karein

#### Tarika 1: Git Command Line Se (Fastest & Best)
Apne terminal ya powershell mein yeh commands chalayein:

```bash
cd "C:\Users\black\.gemini\antigravity\scratch\hunter-naruto-github-profile"
git init
git add .
git commit -m "feat: naruto shinobi profile for hunter"
git branch -M main
git remote add origin https://github.com/<AAPKA_GITHUB_USERNAME>/<AAPKA_GITHUB_USERNAME>.git
git push -u origin main
```
*(Note: `<AAPKA_GITHUB_USERNAME>` ko apne actual GitHub username se replace karein).*

#### Tarika 2: GitHub Web Interface Se
1. Apni nayi banayi hui repository page par jayein.
2. **"uploading an existing file"** link par click karein.
3. Is folder (`C:\Users\black\.gemini\antigravity\scratch\hunter-naruto-github-profile`) ki saari files aur folders (`.github`, `profile-3d-contrib`, saare `.svg`, `.gif`, aur `README.md`) drag & drop karein.
4. **"Commit changes"** par click karein.

---

### Step 3: GitHub Actions Permissions Enable Karein (3D Village & Snake ke liye)
1. Apni repository ke **Settings** tab mein jayein.
2. Left sidebar mein **Actions** -> **General** par click karein.
3. Niche scroll karein aur **"Workflow permissions"** section dhundhein.
4. **"Read and write permissions"** select karein aur **Save** par click karein.
5. Ab repository ke **Actions** tab mein jakar:
   - **"3D contribution city 🌃"** select karein -> **Run workflow** par click karein.
   - **"Generate contribution snake 🐍"** select karein -> **Run workflow** par click karein.

---

### Step 4: Social Links & Username Customize Karein (Optional)
Agar aapko apne real links lagane hain toh `README.md` mein:
- `username=hunter` ko apne GitHub username se replace karein.
- `hunter.dev@example.com` ko apni email se replace karein.
- Apne LinkedIn/Instagram/Twitter links paste kar dein.

**Dattebayo! Aapka profile live aur animated ho jayega! 🍥🔥**
