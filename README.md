# beitoftruth.org — Website Source

A static website for **Beit of Truth**, sharing teachings, resources, and scriptural studies.  
This repository contains the HTML, CSS, JavaScript, and media files that power the live site.

---

## 📍 Live Site
https://beitoftruth.org

---

## 📄 About This Project
This site is built as a **fully static website**, using:

- HTML  
- CSS  
- JavaScript  
- Static JSON data (e.g., `parshiot.json`)  

There is no backend, database, or server-side code.  
This keeps the site fast, secure, and easy to maintain.

---

## 📁 Repository Structure

- `/index.html` — Main homepage  
- `/assets/` — Images, CSS, JS, fonts  
- `/parsha/` — Parasha pages and teaching layouts  
- `/404.html` — Custom error page  
- Additional pages and sections as needed  

---

## 🚀 Deployment

The site is deployed using **GitHub Pages** from the `main` branch.

### Deployment Flow
1. Push changes to `main`  
2. GitHub Pages builds and deploys automatically  
3. Cloudflare handles DNS and HTTPS for the domain  

### DNS Notes
Cloudflare DNS should include:

- `A` records pointing to GitHub Pages IPs  
- `CNAME` for `www` → `beitoftruth.github.io` (if used)  
- Proxy (orange cloud) enabled for caching and security  

---

## 🛠 Development Notes

- All content is static; no build tools required  
- Edit files directly or use any code editor  
- Changes appear instantly after deployment  
- JSON files (like `parshiot.json`) can be updated without modifying HTML  

---

## 📜 Purpose

Beit of Truth exists to:

- Share scriptural teachings  
- Provide study resources  
- Offer structured parasha readings  
- Present ministry content in a clean, accessible format  

This repository keeps the site organized, version-controlled, and easy to update.

---

## 🤝 Contributions

This is a personal/ministry project.  
If collaboration is needed in the future, contribution guidelines can be added here.

---

## 📬 Contact

For updates or questions, contact the site owner.