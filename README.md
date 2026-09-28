# ❤️ Happy Birthday Divya — From Aditya

A beautiful, romantic single-page birthday website made with love for **Divya**.

## ✨ Features

- Elegant romantic design with soft pinks, reds & gold accents
- Floating animated hearts
- Typewriter love letter that reveals as you scroll
- Photo gallery section (ready for your personal pictures)
- Beautiful flower gallery with romantic captions
- Interactive "Send a Heart" counter
- Fully responsive (looks great on phone & desktop)
- Smooth animations & scroll effects

## 🚀 How to Host on GitHub Pages (Free)

1. **Create a new GitHub repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it something like `divya-birthday` or `happy-birthday-divya`
   - Make it **Public**
   - Click **Create repository**

2. **Upload the files**
   - Click **uploading an existing file**
   - Drag and drop **all** the files and folders from this project:
     - `index.html`
     - `css/` folder
     - `js/` folder
     - `images/` folder (optional)
     - `README.md`
   - Commit the changes

3. **Enable GitHub Pages**
   - Go to the repository **Settings** → **Pages** (left sidebar)
   - Under **Source**, select **Deploy from a branch**
   - Branch: `main` (or `master`), folder: `/ (root)`
   - Click **Save**
   - Wait 1–2 minutes. Your site will be live at:
     `https://YOUR-USERNAME.github.io/divya-birthday/`

## 📸 Adding Your Personal Photos

The gallery currently has **placeholders**. To add real photos of you and Divya:

1. Put your photos inside the `images/` folder  
   (e.g. `images/us1.jpg`, `images/us2.jpg`, etc.)

2. Open `index.html` and find the gallery section (search for `gallery-grid`).

3. Replace each placeholder like this:

```html
<!-- BEFORE (placeholder) -->
<div class="gallery-item placeholder" data-label="Our First Date">
    <div class="placeholder-content">
        <span class="placeholder-icon">📷</span>
        <p>Add our photo here</p>
        <small>Click to upload later</small>
    </div>
</div>

<!-- AFTER (with your photo) -->
<div class="gallery-item">
    <img src="images/us1.jpg" alt="Our First Date">
</div>
```

You can also add more gallery items the same way.

## 🌸 Flower Images

The flower photos are loaded from Unsplash (free & beautiful).  
They will always work as long as you have internet. No need to download them.

## ✏️ Customize the Message

Open `js/script.js` and edit the `message` variable near the top to write your own personal love letter.

## 📱 Share the Link

Once hosted, just send Divya the GitHub Pages link.  
It works perfectly on mobile too — perfect for a birthday surprise!

---

Made with ❤️ by Aditya for Divya  
September 29
