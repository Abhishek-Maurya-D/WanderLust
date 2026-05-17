<div align="center">

# 🌍 WanderLust

### *Because the world is too beautiful to stay in one place.*

[![Node.js](https://img.shields.io/badge/Node.js-20.x-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-4.x-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Mongoose-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Cloudinary](https://img.shields.io/badge/Cloudinary-Image_CDN-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)](https://cloudinary.com/)
[![Mapbox](https://img.shields.io/badge/Mapbox-Maps_API-000000?style=for-the-badge&logo=mapbox&logoColor=white)](https://www.mapbox.com/)
[![License: ISC](https://img.shields.io/badge/License-ISC-blue?style=for-the-badge)](LICENSE)

**A production-grade, full-stack travel accommodation platform — built from scratch, deployed with purpose.**

[🔗 Live Demo](#) · [🐛 Report Bug](https://github.com/Abhishek-Maurya-D/WanderLust/issues) · [💡 Request Feature](https://github.com/Abhishek-Maurya-D/WanderLust/issues)

</div>

---

## 🚀 What Is WanderLust?

WanderLust is a **full-stack Airbnb-inspired travel accommodation platform** that lets users discover, list, and review unique stays from around the world. This isn't a tutorial clone — it's a real-world application engineered with clean architecture, secure authentication, live map integration, and cloud-powered media management.

> Built to solve real problems. Designed to impress. Engineered to scale.

---

## ✨ Features That Matter

| Feature | What It Does |
|---|---|
| 🔐 **Secure Auth** | Passport.js local strategy with session persistence via MongoDB |
| 🗺️ **Interactive Maps** | Real-time listing locations powered by Mapbox GL |
| ☁️ **Cloud Image Uploads** | Drag-and-drop photos stored & served via Cloudinary CDN |
| ✅ **Server-side Validation** | Robust Joi schema validation — no bad data gets through |
| 🧩 **MVC Architecture** | Clean separation of Models, Views, Controllers |
| 🔁 **RESTful Routing** | Industry-standard REST API with method-override support |
| 💬 **Flash Messages** | Instant user feedback on every action |
| 🛡️ **Middleware Guards** | Custom auth middleware protecting every sensitive route |

---

## 🛠️ Tech Stack — Skills on Display

```
Backend        →  Node.js · Express.js · RESTful API design
Database       →  MongoDB · Mongoose ODM · connect-mongo sessions
Auth           →  Passport.js · passport-local · passport-local-mongoose
Templating     →  EJS · ejs-mate (layouts & partials)
File Uploads   →  Multer · multer-storage-cloudinary · Cloudinary SDK
Maps           →  Mapbox SDK (@mapbox/mapbox-sdk)
Validation     →  Joi (server-side schema validation)
Security       →  dotenv · express-session · connect-flash
```

This stack reflects **real industry demand** — the exact tools used by startups and scale-ups to ship fast without cutting corners.

---

## 🗂️ Project Structure

```
WanderLust/
├── controllers/        # Business logic — clean, separated, testable
├── models/             # Mongoose schemas (Listings, Reviews, Users)
├── routes/             # RESTful route definitions
├── views/              # EJS templates with ejs-mate layouts
├── public/             # Static assets (CSS, JS, images)
├── utils/              # Custom error handling & async wrappers
├── init/               # DB seed data
├── middleware.js        # Auth guards & permission checks
├── cloudConfig.js       # Cloudinary + Multer configuration
├── schema.js            # Joi validation schemas
└── app.js              # App entry point & middleware chain
```

---

## ⚡ Quick Start

### Prerequisites
- Node.js `v20.x`
- MongoDB (local or Atlas)
- Cloudinary account
- Mapbox account

### Installation

```bash
# 1. Clone the repo
git clone https://github.com/Abhishek-Maurya-D/WanderLust.git
cd WanderLust

# 2. Install dependencies
npm install

# 3. Set up environment variables
touch .env
```

Add the following to your `.env`:

```env
ATLASDB_URL=your_mongodb_connection_string
SECRET=your_session_secret

CLOUD_NAME=your_cloudinary_cloud_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret

MAP_TOKEN=your_mapbox_public_token
```

```bash
# 4. Seed the database (optional)
node init/index.js

# 5. Start the server
node app.js
```

Navigate to `http://localhost:8080` — you're live. 🚀

---

## 🎯 Why This Project Stands Out

Most developers build todo apps. I built a **platform**.

Every architectural decision here mirrors what you'd find in a production environment:

- **No raw SQL** — Mongoose ODM for clean, schema-enforced data interactions
- **No plain passwords** — passport-local-mongoose handles hashing automatically
- **No local file storage** — Cloudinary ensures images are CDN-delivered worldwide
- **No hardcoded secrets** — dotenv keeps credentials environment-safe
- **No bloated controllers** — async/await wrappers keep error handling DRY

This is what **serious full-stack development** looks like.

---

## 📸 Screenshots

> *(Add your app screenshots here — listings page, map view, listing detail, auth pages)*

---

## 🤝 Contributing

Found something worth improving? PRs are welcome.

```bash
git checkout -b feature/your-feature-name
git commit -m "feat: add your feature"
git push origin feature/your-feature-name
```

Then open a Pull Request — let's make it better together.

---

## 📬 Connect With Me

**Abhishek Maurya** — Full Stack Developer

[![GitHub](https://img.shields.io/badge/GitHub-Abhishek--Maurya--D-181717?style=flat-square&logo=github)](https://github.com/Abhishek-Maurya-D)

---

<div align="center">

**⭐ If this project helped you or impressed you — drop a star. It means more than you think.**

*Built with passion. Shipped with precision.*

</div>
