# SHADYI — High-Retention Video Editor Portfolio & CMS

A high-performance cyberpunk-themed portfolio with 3D canvas visuals, 86-frame cyber visor sequence, 3D tunnel project showcase, and a complete **Firebase-powered Admin Panel (Control Center)**.

---

## 🚀 Features

- **Cyber Visor Scroll Animation**: 86-frame dynamic canvas sequence.
- **3D Tunnel Selected Work**: Dynamic project cards with video preview modal.
- **Complete Admin Panel (Control Center)**:
  - Accessible via the **LOGIN** button in navbar.
  - Customize Hero text, branding, CTAs, HUD status, and badge.
  - Manage Projects (Add, Edit, Delete, Reorder, Video links).
  - Manage About, Bio, Experience pillars, Skills & Tools.
  - Switch & customize themes (Cyan, Purple, Emerald, Gold, Crimson, Custom RGB).
  - Inquiries Inbox to capture and manage client contact form messages.
  - Site backup export & import (JSON).
- **Firebase Cloud Integration**:
  - **Firebase Authentication**: Secure Email/Password admin login.
  - **Cloud Firestore**: Real-time cloud sync. Any edit made in the admin panel instantly updates live on the website for all visitors across the globe.

---

## 📁 File Structure

```text
├── index.html           # Main website markup & layout
├── styles.css           # Core styling, responsive design & cyber effects
├── script.js            # Visor canvas, 3D tunnel, navigation & audio
├── admin.css            # Admin panel design, dark glassmorphism & controls
├── admin.js             # Admin CMS controller & live site renderer
├── firebase-config.js   # Firebase project configuration keys
├── server.js            # Simple zero-dependency local HTTP preview server
├── hero-man.png         # Fallback portrait art
└── frames/              # 86-frame visor sequence images (0001.webp - 0086.webp)
```

---

## 💻 How to Run Locally

### Option 1: Double Click / Browser
Simply open `index.html` in any modern web browser.

### Option 2: Using Node.js
Open your terminal inside this folder and run:
```bash
node server.js
```
Then visit: `http://localhost:3000`

---

## 🌐 How to Deploy to GitHub Pages (Free)

1. Create a new repository on GitHub (e.g. `shadyi-portfolio`).
2. Upload all the files in this folder into the repository.
3. In GitHub, go to **Settings** > **Pages**.
4. Under **Branch**, select `main` (or `master`) and folder `/ (root)`, then click **Save**.
5. Your live portfolio URL will be ready at: `https://<your-username>.github.io/<repo-name>/`!

---

## 🔐 Admin Panel Access

1. Visit your portfolio and click **LOGIN** in the top navigation bar.
2. Enter your Firebase Admin Email and Password.
3. The Admin Dock and Control Center will open automatically.
4. Any changes you make will be saved immediately to Firebase and displayed to all visitors!
