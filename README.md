# English Fluency Sprint 🚀

A 7-day bilingual English immersion plan for Arabic speakers. Installs as a Progressive Web App on any phone — works offline, syncs progress, no app store needed.

**Features:**
- 20 essential phrases for daily conversation
- 15 vocabulary words (work, relationships, travel)
- 5 grammar rules with examples
- 7 conversation scripts with audio-ready dialogue
- Daily quizzes
- Spaced repetition (Quick Recall on Days 2–7)
- Progress tracking that persists across sessions
- Dark theme, mobile-optimized
- Works offline after first load

---

## 📂 Files in this package

| File | Purpose |
|------|---------|
| `index.html` | Main app — the actual learning plan |
| `manifest.json` | PWA metadata (name, icons, theme) |
| `sw.js` | Service worker for offline support |
| `icon-192.png` | App icon (small) |
| `icon-512.png` | App icon (large) |
| `icon-maskable-512.png` | Android adaptive icon |
| `README.md` | This file |

---

## 🚀 Deploy to GitHub Pages (free, ~10 minutes)

### Step 1: Create a GitHub account
If you don't have one, sign up at [github.com](https://github.com). Free.

### Step 2: Create a new repository
1. Click the **+** icon (top right) → **New repository**
2. Name it: `english-sprint` (or any name you like)
3. Set it to **Public** (required for free Pages hosting)
4. Check ✅ **Add a README file**
5. Click **Create repository**

### Step 3: Upload all the files
1. On the repo page, click **Add file** → **Upload files**
2. Drag and drop ALL files from this package:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `icon-maskable-512.png`
3. Scroll down, click **Commit changes**

### Step 4: Enable GitHub Pages
1. Click the **Settings** tab (top of the repo)
2. In the left sidebar, click **Pages**
3. Under "Source", select **Deploy from a branch**
4. Branch: `main`, Folder: `/ (root)`
5. Click **Save**
6. Wait 1–3 minutes. Refresh the Pages settings page.
7. You'll see: ✅ **Your site is live at `https://YOUR-USERNAME.github.io/english-sprint/`**

### Step 5: Share it 🎉
Copy that URL and share it with anyone — on WhatsApp, Twitter, anywhere.

---

## 📱 How users install it as an app

Send them the URL. Then they:

**iPhone (Safari):**
1. Open the URL
2. Tap the Share button (square with arrow up)
3. Scroll down → **Add to Home Screen**
4. Tap **Add**

**Android (Chrome):**
1. Open the URL
2. Tap the menu (⋮) in the top right
3. Tap **Install app** or **Add to Home screen**
4. Confirm

The app opens fullscreen like any other native app. Works offline. Each user's progress is saved on their own device.

---

## 🔧 Customizing the app

Want to change content, add your own phrases, or rebrand it? Open `index.html` in any text editor — everything is in one file (HTML, CSS, JavaScript). Edit, save, re-upload to GitHub.

**Common changes:**
- **Title/brand name:** Search for `English Sprint` in `index.html` and `manifest.json`
- **Colors:** Change the `--accent: #f97316;` line at the top of the `<style>` section
- **Content:** Each day is a `<section class="day">` block — edit phrases, vocab, conversations directly

---

## ❓ Troubleshooting

**"My site shows a 404 error after I push"**
- Wait 5–10 minutes. GitHub Pages takes time to deploy on first setup.
- Make sure the repo is **Public**, not Private.

**"The PWA install option doesn't show up"**
- The site must be served over HTTPS (GitHub Pages does this automatically).
- Try a different browser. Safari/Chrome have the best PWA support.

**"Progress isn't saving"**
- The user's browser may be in private/incognito mode. localStorage doesn't persist there.
- Try a regular browser tab.

---

## 📜 License

Free to use, modify, and share. Built with care for Arabic-speaking English learners.

---

## 🇪🇬 بالعربي — خطوات النشر بسرعة

1. اعمل حساب على [github.com](https://github.com) (مجاناً)
2. أنشئ repository جديد، اسمه `english-sprint`، خليه **Public**
3. ارفع كل الملفات اللي في الحزمة دي
4. روح **Settings → Pages**
5. اختار branch: `main`، folder: `/ (root)`، واحفظ
6. استنى دقيقتين، وهتلاقي الموقع شغال على:
   `https://اسم-حسابك.github.io/english-sprint/`
7. ابعت اللينك لأي حد، وهيقدر يثبته كتطبيق على موبايله

**التثبيت على الموبايل:**
- iPhone: افتح اللينك في Safari → زر المشاركة → "Add to Home Screen"
- Android: افتح اللينك في Chrome → القائمة (⋮) → "Install app"

التطبيق هيشتغل offline بعد أول مرة، وكل واحد بيستخدمه هيلاقي تقدمه محفوظ على موبايله.
