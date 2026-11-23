<div align="center">

# 🎭 BACKSTAGE

**Arabic-first theater booking platform — shows, ticketing, receipt verification and QR entry**

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Visit_Site-success?style=for-the-badge)](https://backstage-company-eight.vercel.app)

[![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)](https://nextjs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)](https://www.mongodb.com)
[![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)](https://jwt.io)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)](https://vercel.com)

</div>

---

## 🌐 Live

- **Website:** [backstage-company-eight.vercel.app](https://backstage-company-eight.vercel.app)
- **Admin:** [backstage-company-eight.vercel.app/admin/login](https://backstage-company-eight.vercel.app/admin/login)

## ✨ Features

- 🎟️ **Show listings & ticket booking** for the troupe's productions, Arabic RTL with dark mode.
- 🧾 **Payment receipt upload** — audience members attach a transfer receipt with their booking.
- 📱 **QR-code entry** — every booking issues a QR code for door validation.
- 🛠️ **Admin dashboard** — manage shows, bookings and receipts.
- 🖼️ **Media storage in MongoDB GridFS** — no external file service needed.
- 🔎 **SEO-ready** — sitemap and social share metadata generated from the production URL.

## 🛠️ Tech Stack

| Layer | Choice |
| --- | --- |
| Framework | Next.js + TypeScript |
| Database | MongoDB Atlas (GridFS for files and images) |
| Auth | JWT |
| Hosting | Vercel |

## 🚀 Getting Started

1. Copy `.env.example` to `.env.local` and fill in your MongoDB URI and JWT secret.
2. `npm install`
3. `npm run setup-db` — creates indexes and the first admin account.
4. `npm run dev` and open `http://localhost:3000`.

### Environment variables

| Variable | Purpose |
| --- | --- |
| `MONGODB_URI` | MongoDB Atlas connection string |
| `MONGODB_DB_NAME` | Database name |
| `ADMIN_EMAIL` / `ADMIN_PASSWORD` | First admin account (setup flow) |
| `JWT_SECRET` | Token signing secret |
| `NEXT_PUBLIC_APP_URL` | Production URL for links, sitemap and share metadata |

---

<div align="center">

## 👨‍💻 Developed by [Angelo Rezq](https://github.com/angelo-rezq)

**Full-Stack Developer · Flutter · Next.js · React**

[![Portfolio](https://img.shields.io/badge/Portfolio-black?style=for-the-badge)](https://angelo-portfolio.angluosr.workers.dev)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-Chat-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/201127570256)
[![Email](https://img.shields.io/badge/Email-angelo.rezq.dev%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:angelo.rezq.dev@gmail.com)

</div>
