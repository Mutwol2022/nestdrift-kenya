# 🏠 NestDrift Kenya

> **The most personalised way to find your next home across Kenya — built for tenants, landlords, and agents.**

[![Status](https://img.shields.io/badge/status-live-brightgreen)](https://github.com/YOUR_USERNAME/nestdrift-kenya)
[![Language](https://img.shields.io/badge/language-HTML%20%7C%20CSS%20%7C%20JavaScript-orange)](https://github.com/YOUR_USERNAME/nestdrift-kenya)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
[![Kenya](https://img.shields.io/badge/market-Kenya%20🇰🇪-red)](https://github.com/YOUR_USERNAME/nestdrift-kenya)

---

## 📋 Table of Contents

- [About NestDrift](#about-nestdrift)
- [Live Demo](#live-demo)
- [Features](#features)
- [Who It's For](#who-its-for)
- [Monetisation Model](#monetisation-model)
- [Project Structure](#project-structure)
- [How to Use](#how-to-use)
- [Login Demo Accounts](#login-demo-accounts)
- [Payment Methods](#payment-methods)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## About NestDrift

**NestDrift Kenya** is a rental apartment listing and matching platform built specifically for the Kenyan market. It connects tenants seeking homes with landlords listing properties — across all 47 Kenyan counties, with all prices displayed in **KES (Kenyan Shillings)**.

The platform borrows the best practices from global platforms like **Rightmove** (UK), **Zillow** (US), and **Apartment List** (US):

- 🔓 **Starting prices are shown publicly** — just like Rightmove, so users can browse without signing in
- 🔒 **Exact prices, deposit amounts, and landlord contacts are unlocked after sign-in** — protecting landlord privacy and creating a revenue stream
- 💳 **M-PESA and Card payments** are integrated for unlocking contact details (KES 300 per listing)
- 📊 **Role-based dashboards** for Tenants, Landlords, and Admins

---

## Live Demo

> 🌐 **[Open NestDrift Kenya](https://YOUR_USERNAME.github.io/nestdrift-kenya)**

*(Replace YOUR_USERNAME with your GitHub username after deploying — see [How to Use](#how-to-use))*

**Quick demo login credentials:**

| Role | How to Access |
|------|--------------|
| 🏠 Tenant | Click **Sign In** → select **Tenant** → click **Sign In** |
| 🔑 Landlord | Click **Sign In** → select **Landlord** → click **Sign In** |
| ⚙️ Admin | Click **Sign In** → select **Admin** → click **Sign In** |

---

## Features

### 🏠 For Tenants
| Feature | Public | Signed In |
|---------|--------|-----------|
| Browse all listings | ✅ | ✅ |
| See starting prices | ✅ | ✅ |
| See exact rent + deposit + service charge | ❌ | ✅ |
| View landlord contacts | ❌ | ✅ (KES 300) |
| Save/shortlist listings | ❌ | ✅ |
| Book tours | ❌ | ✅ |
| Price drop alerts | ❌ | ✅ |
| Application tracking | ❌ | ✅ |
| Verified Renter Badge | ❌ | ✅ (KES 500) |

### 🔑 For Landlords
- Upload listings with up to **10 room photos** (drag & drop supported)
- Choose listing plan: Free / KES 500 / Boost KES 1,200 / Featured KES 5,000
- Dashboard with enquiry tracking, revenue analytics, and occupancy rates
- See which tenants are **verified** (ID, CRB, phone)
- Manage all listings in one place

### ⚙️ For Admin (Restricted)
- Platform-wide revenue monitoring by stream
- Live activity feed
- User management (tenants and landlords)
- Listings moderation and flagging
- Full payment transaction history
- Analytics dashboard

---

## Who It's For

```
┌────────────────────────────────────────────────────────────┐
│                    NestDrift Kenya                          │
├────────────────┬─────────────────┬────────────────────────┤
│   TENANTS      │   LANDLORDS     │        ADMIN            │
├────────────────┼─────────────────┼────────────────────────┤
│ Browse freely  │ List properties │ Monitor platform        │
│ Pay KES 300    │ Pay listing fees│ Manage users            │
│ to contact     │ Track enquiries │ View all revenue        │
│ landlords      │ Manage photos   │ Moderate listings       │
└────────────────┴─────────────────┴────────────────────────┘
```

---

## Monetisation Model

NestDrift Kenya uses **6 revenue streams** inspired by Zillow, Rightmove, and Apartment List:

### 1. Featured & Promoted Listings (Landlords Pay)

| Product | Price | Duration |
|---------|-------|----------|
| Free listing | KES 0 | 30 days |
| Pay-per-listing | KES 500 | 30 days |
| Boost — top of search | KES 1,200 | 7 days |
| Featured banner | KES 5,000 | 30 days |

### 2. Lead Generation Fees (Landlords Pay)

| Tenant Action | Fee |
|--------------|-----|
| Taps WhatsApp | KES 150 |
| Books a tour | KES 300 |
| Submits application | KES 500 |
| Confirmed lease referral | 50% of first month's rent |

### 3. Agency Subscriptions

| Plan | Monthly Fee | Listings |
|------|------------|----------|
| Starter | Free | 1 |
| Agent Basic | KES 2,500 | 10 |
| Agency Pro | KES 7,500 | 50 |
| Enterprise | KES 18,000 | Unlimited |

### 4. Tenant-Paid Services

| Service | Price |
|---------|-------|
| Contact unlock (per listing) | KES 300 |
| Premium Search Alerts | KES 299/month |
| Background Check (CRB + ID) | KES 1,500 |
| Verified Renter Badge | KES 500 |

### 5. Affiliate & Partner Commissions

Partners include moving companies, renters insurance providers, ISPs (Safaricom, Zuku), furniture retailers, and mortgage brokers. Commissions range from **KES 300 to KES 50,000+** per referral.

### 6. Data Monetisation (B2B)

| Product | Price |
|---------|-------|
| Quarterly rental market report | KES 15,000 |
| County vacancy rate API | KES 50,000/year |
| Neighbourhood demand heatmaps | Custom |

**Projected monthly revenue (early stage): KES 550,000 – 1,620,000**

---

## Project Structure

```
nestdrift-kenya/
│
├── index.html                   ← Main application (entire app in one file)
│
├── README.md                    ← This file
├── LICENSE                      ← MIT open source license
├── CONTRIBUTING.md              ← Contribution guidelines
│
├── docs/
│   ├── MONETISATION.md          ← Full monetisation strategy
│   ├── USER_GUIDE_TENANT.md     ← Tenant user guide
│   ├── USER_GUIDE_LANDLORD.md   ← Landlord user guide
│   └── DEPLOYMENT.md            ← Production deployment guide
│
└── assets/
    └── screenshots/
        ├── home-public.png       ← Homepage public view
        ├── home-loggedin.png     ← Homepage logged-in view
        ├── tenant-dashboard.png  ← Tenant dashboard
        ├── landlord-portal.png   ← Landlord portal
        ├── admin-panel.png       ← Admin dashboard
        └── pricing-page.png      ← Pricing page
```

> The entire app runs from a single `index.html` file. No server, no database, no installation needed — just open in any browser.

---

## How to Use

### Open Directly (Offline)

1. Download `index.html` from this repository
2. Double-click to open in your browser
3. Done — no internet required after download

### Deploy to GitHub Pages (Free Public Link)

1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Scroll to **Pages** in the left sidebar
4. Under Source, choose **Deploy from a branch**
5. Select branch `main` and folder `/ (root)` then click **Save**
6. Wait about 2 minutes — your app is now live at:

```
https://YOUR_USERNAME.github.io/nestdrift-kenya
```

### Share the File

Simply send `index.html` via WhatsApp, email, or Google Drive. Anyone can open it in a browser — nothing to install.

---

## Login Demo Accounts

The demo uses simulated logins. To test different roles:

| Role | Steps | What You See |
|------|-------|-------------|
| **Tenant** | Sign In → Tenant → Sign In | Browse listings, save, apply, pay, dashboard |
| **Landlord** | Sign In → Landlord → Sign In | Add listings, upload photos, see enquiries |
| **Admin** | Sign In → Admin → Sign In | Full platform control, all revenue, all users |

---

## Payment Methods

### M-PESA (Primary)

1. Tenant clicks **Contact Landlord** on a listing
2. Enters M-PESA phone number
3. STK push sent to phone (simulated in demo with 2-second delay)
4. On confirmation — landlord contacts revealed

### Card (Visa / Mastercard)

1. Select **Card** at payment
2. Enter card details
3. Payment processes — contacts revealed

> **Production integration:** M-PESA via Safaricom Daraja API, Cards via Stripe or Pesapal Kenya.

---

## Roadmap

### Version 1.0 — Current

- [x] Public listings with starting prices (Rightmove-style)
- [x] Role-based login (Tenant / Landlord / Admin)
- [x] M-PESA + Card payment simulation
- [x] Photo upload with drag-and-drop and previews
- [x] Tenant dashboard (saved, applications, payments, alerts)
- [x] Landlord dashboard (listings, enquiries, revenue, analytics)
- [x] Admin control panel with revenue by stream
- [x] All prices in KES
- [x] Kenya county and area filters (47 counties)

### Version 2.0 — Planned

- [ ] Real backend (Firebase or Supabase)
- [ ] Live M-PESA Daraja API
- [ ] Push notifications for price alerts
- [ ] Google Maps integration
- [ ] CRB check via Metropol Kenya API
- [ ] Progressive Web App (PWA) for mobile
- [ ] In-app tenant–landlord messaging
- [ ] Email notifications

### Version 3.0 — Future

- [ ] AI Rental Matchmaker quiz
- [ ] Rental market data API (county vacancy rates)
- [ ] Mortgage and loan partner integrations
- [ ] Kiswahili language support

---

## Contributing

1. Fork this repository
2. Create a branch: `git checkout -b feature/your-feature-name`
3. Make your changes
4. Commit: `git commit -m "Add: description of what you did"`
5. Push: `git push origin feature/your-feature-name`
6. Open a Pull Request on GitHub

See [CONTRIBUTING.md](CONTRIBUTING.md) for more detail.

---

## License

MIT License — see [LICENSE](LICENSE). Free to use, copy, and modify with attribution.

---

## Contact

- Email: hello@nestdrift.co.ke
- Twitter/X: @NestDriftKE
- Website: nestdrift.co.ke

---

*Built for the Kenyan rental market · © 2026 NestDrift Kenya*
