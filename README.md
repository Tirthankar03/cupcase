# 🧁 Cupcase

**Cupcase** is a beautifully designed, fully customizable e-commerce platform where users can create and purchase personalized phone cases. Built using **Next.js 14**, **TypeScript**, **Tailwind CSS**, and **Prisma**, it offers a modern, smooth, and engaging user experience with powerful features like drag-and-drop uploads, authentication, payments, and an interactive configurator.

Explore the live demo 👉 [cupcase.vercel.app](https://cupcase.vercel.app)  
View the code on GitHub 👉 [GitHub Repository](https://github.com/Tirthankar03/cupcase)

---

## 📸 Project Preview

![Cupcase Preview](https://tirthankarnath.vercel.app/cupcase.png) <!-- Replace with actual image -->

---

## ✨ Features

### 🛍️ Custom E-Commerce Experience
- A fully-featured **online store** built from scratch with **Next.js 14 App Router**.
- Users can design their **own phone cases** via a unique configuration tool.
- **Apple-inspired configurator** for a premium UX feel.

### 💻 Modern UI & UX
- Sleek and responsive interface built with **Tailwind CSS** and **shadcn/ui**.
- Smooth animations and transitions with **Framer Motion**.
- Professionally illustrated **custom artworks** available for use.

### 📤 Upload & Configure
- Drag-and-drop file uploads using **react-dropzone**.
- Configurator supports resizing, rotating, and dragging using **react-rnd**.

### 🔐 Authentication
- **Google Sign-in** and session management with **NextAuth v5 (Auth.js)**.
- Custom callback flow to save user progress during sign-in for seamless navigation.

### 🧾 Secure Payments
- Seamless payment flow with **Stripe Checkout**.
- Users receive a **custom "Thank You" email** after successful purchase.

### 🛠️ Admin Tools
- A **secret admin dashboard** to manage orders and user uploads.

---

## 🧰 Tech Stack

| Category           | Tech Used                                           |
|--------------------|-----------------------------------------------------|
| Frontend           | Next.js 14 (App Router), React, Tailwind CSS, shadcn-ui |
| Animations         | Framer Motion                                       |
| Backend            | Prisma ORM, PostgreSQL                              |
| Auth               | NextAuth v5 (Auth.js), Google Provider              |
| Payments           | Stripe Checkout                                     |
| State Management   | React Query                                         |
| File Uploads       | UploadThing, react-dropzone, react-rnd              |
| Email Service      | Custom Thank You Email Integration                  |
| Hosting            | Vercel                                              |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Tirthankar03/cupcase.git
cd cupcase
```

### 2. Install Dependencies

```bash
pnpm install
# or
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory and add:

```env
DATABASE_URL=postgresql://user:password@localhost:5432/cupcase
NEXTAUTH_SECRET=your_secret
NEXTAUTH_URL=http://localhost:3000
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
STRIPE_SECRET_KEY=your_stripe_secret
STRIPE_PUBLIC_KEY=your_stripe_public
UPLOADTHING_SECRET=your_uploadthing_secret
```

### 4. Setup Prisma

```bash
npx prisma db push
npx prisma generate
```

### 5. Run the App

```bash
pnpm run dev
```

Visit `http://localhost:3000` to view the app locally.

---

## 🙌 Acknowledgements

- [shadcn/ui](https://ui.shadcn.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [UploadThing](https://uploadthing.com/)
- [Stripe](https://stripe.com/)
- [NextAuth.js](https://next-auth.js.org/)

---
