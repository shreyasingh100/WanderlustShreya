# 🏡 Wanderlust Shreya

### Full-Stack Property Rental Platform

Wanderlust Shreya is a full-stack property rental web application inspired by platforms like Airbnb. It allows users to explore, create, manage, and review property listings with secure authentication, location-based services, and cloud image storage.

---

## ✨ Features

- 🏡 **Property Listings** — Create, view, edit, and delete listings
- 🔐 **Authentication & Authorization** — Passport.js, sessions, cookies, and RBAC
- ⭐ **Reviews & Ratings** — Add and manage property reviews
- 🗺️ **Interactive Maps** — Mapbox integration for property locations
- ☁️ **Image Uploads** — Cloudinary integration for image storage
- ✅ **Data Validation** — Joi schema validation
- 🛡️ **Error Handling** — Centralized error handling and reusable middleware
- 🔄 **REST APIs** — Structured backend APIs following MVC architecture
- 🌐 **Deployment** — Deployed using Render with MongoDB Atlas

---

## 🛠️ Tech Stack

**Frontend:** HTML • CSS • JavaScript • EJS

**Backend:** Node.js • Express.js • REST APIs • MVC

**Database:** MongoDB • MongoDB Atlas

**Authentication:** Passport.js • Express Sessions • Cookies • RBAC

**Services:** Cloudinary • Mapbox

**Validation & Tools:** Joi • Git • GitHub • VS Code • Render

---

## 🏗️ Application Structure

```text
Wanderlust Shreya
│
├── 🏠 Home
│   └── Browse Listings
│
├── 🏡 Listings
│   ├── Create
│   ├── View
│   ├── Edit
│   └── Delete
│
├── 👤 Authentication
│   ├── Register
│   ├── Login
│   └── Logout
│
├── ⭐ Reviews & Ratings
│
├── 🗺️ Mapbox
│   └── Property Locations
│
└── ⚙️ Backend
    ├── REST APIs
    ├── MVC Architecture
    ├── Middleware
    ├── Validation
    └── Error Handling

🔑 Key Highlights
- Built a complete full-stack property rental platform
- Designed backend using MVC architecture
- Developed RESTful APIs with Express.js
- Implemented authentication, authorization, and RBAC
- Used MongoDB Atlas for database management
- Integrated Cloudinary for image storage
- Integrated Mapbox for interactive property locations
- Implemented Joi validation and centralized error handling
- Deployed the application using Render

🚀 Getting Started
Requirements
- Node.js
- MongoDB / MongoDB Atlas
- Git
Installation
git clone https://github.com/shreyasingh100/WanderlustShreya.git
cd WanderlustShreya
npm install

Create a .env file and add the required credentials:
ATLASDB_URL=your_mongodb_connection_string
SECRET=your_session_secret
MAP_TOKEN=your_mapbox_token
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_KEY=your_cloudinary_key
CLOUDINARY_SECRET=your_cloudinary_secret

Run the application:
node app.js

Note: Never commit API keys, database credentials, or other sensitive information.

👩‍💻 Developer
Shreya Singh
💻 GitHub: https://github.com/shreyasingh100
💼 LinkedIn: https://www.linkedin.com/in/shreya-singh-s123/
📧 Email: singhshreya0422@gmail.com
🏡 Explore. Discover. Wander.
