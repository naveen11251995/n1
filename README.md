# FAB Bank WebXR VR Onboarding — GitHub Pages Deployment

This repository contains the complete WebXR 3D VR Onboarding Experience for **First Abu Dhabi Bank (FAB)** tailored for **Meta Quest 3**.

Hosting this project on **GitHub Pages (`github.io`)** automatically provides a **Secure HTTPS (`https://`) context**, unlocking native 6DoF WebXR VR in Meta Quest Browser without any local IP restrictions or browser flags!

---

## 🚀 How to Host on GitHub Pages (github.io)

### Step 1: Create a New GitHub Repository
1. Go to [GitHub.com](https://github.com/new) and log in.
2. Create a new repository named `fabbank-vr` (or any name you prefer).
3. Set the repository to **Public**.
4. Click **Create repository**.

### Step 2: Push Files to GitHub
Open a terminal on your computer and run:
```bash
cd C:\Users\ADMIN\.gemini\antigravity-ide\scratch\FabBank_GitHubPages

git init
git add .
git commit -m "Deploy FAB Bank WebXR VR App"
git branch -M main
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/fabbank-vr.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. On your GitHub repository page, click **Settings** (top tab).
2. On the left sidebar, click **Pages**.
3. Under **Build and deployment $\rightarrow$ Branch**, select **`main`** branch and click **Save**.
4. Wait 30 seconds. GitHub will generate your live WebXR URL:  
   👉 **`https://<YOUR_GITHUB_USERNAME>.github.io/fabbank-vr/`**

---

## 🥽 How to Open inside Meta Quest 3

1. Put on your **Meta Quest 3** headset.
2. Open the built-in **Meta Quest Browser**.
3. Type your live GitHub Pages URL:  
   👉 **`https://<YOUR_GITHUB_USERNAME>.github.io/fabbank-vr/`**
4. Tap the yellow button: **`🥽 ENTER WEBXR VR`**!

---

## 🌟 WebXR Features Included

- **Native HTTPS WebXR 6DoF VR:** Runs natively on Meta Quest Browser with full head tracking.
- **Quest 3 Controller Lasers:** Blue laser pointers emit from Touch Controllers to select 3D holograms.
- **Layla Al-Mansouri 3D Avatar:** FAB uniform, head tracking, gestures, and **out-loud speech narration**.
- **6 Story Chapters:** Welcome, Personal Info, 3D Laser Emirates ID Scan, Address Selection, Product Cards, Confetti Celebration.
