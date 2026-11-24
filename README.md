# 🌌 NyteHawk — Nearby Services Full-Stack Web Application

NyteHawk is a **full-stack web application** built using **React (Frontend)** and **Node.js + Express (Backend)**.  
It helps users explore nearby services such as ATMs, pharmacies, and food outlets, with added features like secure login/signup, contact form email handling, QR code payment generation, and newsletter subscriptions.

---

## 🚀 Features

### 🖥️ Frontend (React)
- Modern, responsive design with split-screen layout
- Interactive carousels using **Swiper.js**
- Dynamic routing with **React Router DOM**
- Service location via **React Leaflet** (maps)
- Newsletter subscription form
- Axios-based API integration with backend

### ⚙️ Backend (Node.js + Express)
- **Nodemailer** for sending emails (contact form, newsletter)
- **QR code generation** for medicine and food payment
- RESTful API endpoints for secure data flow
- **CORS**, **dotenv**, and **body-parser** for configuration and security

---

## 🧩 Tech Stack

| Layer | Technology |
|--------|-------------|
| **Frontend** | HTML, CSS, JavaScript, React, React Router DOM, Swiper, Axios, React Icons, React Leaflet, Leaflet |
| **Backend** | Node.js, Express.js, Nodemailer, QRCode |
| **Database (optional)** | MongoDB |
| **Styling** | CSS / TailwindCSS |

---

## 🛠️ Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/Krish-zinzuvadiya/Nytehawk.git
```

### 2. Navigate to the Project Directory

```bash
cd Nytehawk
```

### 3. Install Frontend Dependencies
- Run the following command to install all required packages:
```bash
npm install
```

- If you encounter missing module errors, install them manually:
```bash
npm install react-router-dom swiper react-icons axios react-leaflet leaflet
```

### 4. Install Backend Dependencies 
- Open a new terminal and run:
```bash
cd ../backend
npm install express nodemailer qrcode cors body-parser axios dotenv
```

### 5. Start The Development Server
- Frontend:
```bash
npm start
```
Your app will start at: 👉 http://localhost:3000

- Backend:
```bash
node server.js
```
Backend runs on: 👉 http://localhost:5000
