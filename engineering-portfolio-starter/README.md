# Engineering Project Portfolio

A curated archive of my hands-on engineering projects — from CAD explorations to full mechanical builds — presented with **clear process photos, technical notes, and CPD-ready reflections**.

> **How to view**: Browse the project cards below or open the `/projects` folder. Each project has its own `README.md` with images, video links, parts lists, and STAR-style reflections.

---

## 📌 Highlights

- **Motorised Bike Build** — 2-stroke 89cc install, alignment & mounting, troubleshooting & safety.  
  → [`/projects/motorised-bike`](projects/motorised-bike/README.md)
- **Bluetooth Speaker** — driver selection, enclosure design, crossover basics, finish.  
  → [`/projects/bluetooth-speaker`](projects/bluetooth-speaker/README.md)
- **CAD Gallery (SolidWorks)** — parametric parts, assemblies, drawings, tolerancing.  
  → [`/projects/cad-gallery-solidworks`](projects/cad-gallery-solidworks/README.md)

---

## 🧭 Repository Map

```
/projects
  /motorised-bike
  /bluetooth-speaker
  /cad-gallery-solidworks
  /_template-project
/assets
```

---

## 📸 Media & Video

- Place images inside each project's `media/` folder.
- For **videos**, either:
  1. Upload short clips (`.mp4`) with Git LFS (recommended), or  
  2. Host on Drive/YouTube and link in the project `README`.

**Enable Git LFS** (once per machine):
```bash
git lfs install
git lfs track "*.mp4" "*.mov" "*.mkv" "*.zip"
git add .gitattributes
git commit -m "Enable Git LFS for media"
```

---

## ✍️ CPD-ready Structure

Each project README follows: **Overview → Process → Challenges → Results → Reflection (STAR)**.  
This makes it easy to reuse text in CPD logs.

---

## 🔗 Site Front-End (Optional)

You can pair this repo with a simple portfolio front-end (Carrd / Notion / Super.so) and deep-link into these project pages.
