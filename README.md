# 🏡 Rental Flow — Vendor-Customer Marketplace

A full-stack rental marketplace built during the **Odoo Hackathon Finals (Gandhinagar, India)**.  
The platform enables vendors to register, list products, manage inventory, and accept rental payments — while customers can browse, add items to cart, pay securely, and track orders.

---

## 🚀 Features

### 👤 User System
- 🔐 Separate login portals for **Vendors** and **Customers**
- Role-based access and dashboard views
- Secure authentication and session handling

### 🛍 Customer side
- Browse rental items with detailed listings
- Add/remove items to/from cart
- Checkout with secure payment flow
- Booking timeline and order history

### 🏪 Vendor side
- Create and manage product listings
- Upload product images (stored on AWS S3)
- View rental status and revenue reports

### 💳 Payments
- Integrated with **Razorpay** for secure payments and order verification

---

## 🧰 Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | **Next.js**, **ShadCN UI** |
| Backend | **Hono.js**, **Bun Runtime** |
| Database | **MongoDB** |
| Storage | **AWS S3** (Image uploads & media storage) |
| Payments | **Razorpay API** |
| Deployment | *(Add if applicable: Vercel / AWS / Render)* |

---

## 📦 Project Structure
/src
├── app/ # Pages and routing (Next.js)
├── components/ # UI components (ShadCN)
├── server/ # Hono backend routes
├── db/ # MongoDB models & connection helpers
└── utils/ # Helpers (auth, validations, uploads, etc.)
## 🛠 Installation & Setup

```sh
# Clone the repo
git clone <repo-url>

# Install dependencies
bun install

# Run locally
bun dev
