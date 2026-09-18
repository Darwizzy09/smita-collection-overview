# Smita Collection 🥻✨

> **Note:** The source code for this platform is closed-source for commercial, security, and proprietary reasons. This repository serves as a technical case study and architectural overview of the production application.

A premium, full-stack e-commerce platform engineered for luxury silk sarees. It was built from scratch using the MERN stack to deliver a secure, seamless, and visually stunning digital boutique experience.

**Live Project:** [https://smita-collection.vercel.app](https://smita-collection.vercel.app)

---

## 📸 Platform Preview
*
<img width="1894" height="913" alt="Screenshot 2026-04-25 115123" src="https://github.com/user-attachments/assets/be496d9b-7db5-4cb2-9856-8712a43bfa24" />
<img width="1502" height="717" alt="Screenshot 2026-09-18 190741" src="https://github.com/user-attachments/assets/17fa5b96-4e35-4063-b03a-475898818eda" />
<img width="957" height="730" alt="Screenshot 2026-09-18 112640" src="https://github.com/user-attachments/assets/d9982203-cf2e-47f9-ad32-f5f41bd482af" />

*

---

## 🚀 Overview

Smita Collection bridges the gap between traditional artistry and modern digital commerce. Moving away from restrictive templated platforms (like Shopify), this application is a custom-engineered solution featuring a bespoke luxury dark-mode UI, bank-grade secure payments via Cashfree, automated fulfillment logistics, and a real-time Admin Command Center.

## ✨ Key Features

### 🛍️ Customer Experience
* **Custom Luxury UI:** A highly responsive, dark-themed interface built with Tailwind CSS, featuring subtle animations and glowing interactive elements.
* **Secure Authentication:** JWT-based user sessions with encrypted passwords (bcrypt).
* **Frictionless Checkout:** Multi-step cart and shipping flow capturing comprehensive delivery data (state, postal code, mandatory courier phone numbers).
* **Live Payments:** Production-ready Cashfree payment gateway integration.
* **Automated Communications:** NodeMailer triggers instant HTML-formatted luxury receipts upon payment and live tracking ID updates upon dispatch.

### 🛡️ Admin Command Center
* **Role-Based Access Control (RBAC):** Exclusive dashboard access locked securely to authorized admin emails.
* **Real-Time Analytics:** Live tracking of total revenue, average order value, conversion pipelines, and total successful transactions.
* **Order Fulfillment Engine:** Manage the master ledger, update delivery statuses, and attach tracking IDs directly from the database.

### 🔒 Security & Architecture
* **Rate Limiting:** `express-rate-limit` prevents brute-force attacks and bot swarms on API endpoints.
* **HTTP Header Masking:** `helmet.js` secures Express apps by setting various HTTP headers to hide server vulnerabilities.
* **No Stolen Data:** PCI-DSS compliant payment routing ensures zero credit card data ever touches the application server.

---

## 💻 Tech Stack

**Frontend**
* React.js (Vite)
* Tailwind CSS (Custom styling & animations)
* Lucide React (Iconography)
* React-Hot-Toast (Premium UI notifications)

**Backend**
* Node.js & Express.js
* MongoDB Atlas (Mongoose ORM)
* JSON Web Tokens (JWT) & Bcrypt (Auth)
* Nodemailer (Email Automation)

**DevOps & APIs**
* Vercel (Frontend Hosting)
* Render (Backend Hosting)
* Cashfree API (Payment Gateway)

---

## 🔮 Future Roadmap
* **Logistics Automation:** Direct Shiprocket API integration for automated courier booking and label generation.
* **WhatsApp Commerce:** Transitioning from email to the Twilio/Meta API for instant WhatsApp tracking updates.
* **AI-Driven Analytics:** Implementing a predictive model to forecast inventory depletion based on seasonal buying trends.
* **Immersive Media:** Integrating cinematic video lookbooks and AR draping visualizations.

---

## 👨‍💻 Author
**Rohit Salunke**
* Full-Stack Developer & Platform Architect
* Building scalable web technologies.
