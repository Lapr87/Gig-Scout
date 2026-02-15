# 🏠 Gig Scout

**Connecting Neighbors, Empowering Scouts.** Gig Scout is a hyper-local marketplace app built to simplify neighborhood gig work. Neighbors can post small tasks, and local "Scouts" can send offers to complete them. The entire process—from discovery to payment—is automated and secure.

---

## 🚀 Key Features

* **Automated Market Logic:** A built-in **10% platform fee** is automatically deducted from every task, ensuring seamless revenue for the platform owner.
* **The "Chat Bouncer":** AI-powered chat moderation that detects and blocks contact details (emails/phone numbers) to keep transactions safe and on-platform.
* **Two-Way Trust System:** A mandatory 1-5 star rating system for both Neighbors and Scouts to ensure community quality.
* **Stripe Integration:** Professional-grade payment processing using Stripe Connect for split payouts.

## 🛠️ Tech Stack

* **Frontend:** Next.js (React)
* **Database:** Supabase (PostgreSQL)
* **Payments:** Stripe API
* **Hosting:** Vercel

---

## 🛠️ Setup Instructions

1. **Clone the repository:**
   `git clone https://github.com/YOUR_USERNAME/gig-scout.git`

2. **Install dependencies:**
   `npm install`

3. **Configure Environment Variables:**
   Create a `.env.local` file with your Supabase and Stripe keys:
   ```env
   NEXT_PUBLIC_SUPABASE_URL=your_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_key
   STRIPE_SECRET_KEY=your_secret_key
