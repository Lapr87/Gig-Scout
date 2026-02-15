# 🏠 Gig Scout

**Empowering Neighborhoods through Local Gigs.** Gig Scout is a community-driven marketplace built to bridge the gap between "Neighbors" who need tasks done and "Scouts" looking for local opportunities.

---

## 🚀 Key Features

* **Automated Revenue:** Built-in **10% platform fee** logic automatically calculated at the database level.
* **The "Chat Bouncer":** AI moderation prevents off-platform deals by detecting contact information sharing.
* **Split Payments:** Powered by Stripe Connect to ensure secure, automated payouts to Scouts.
* **Trust Ratings:** A mandatory 1-5 star feedback loop for both parties.

## 🛠️ Tech Stack

* **Frontend:** Next.js (React)
* **Database:** Supabase (PostgreSQL)
* **Payments:** Stripe API
* **Hosting:** Vercel

---

## 💻 Local Development Setup

Follow these steps to run **Gig Scout** on your own computer:

### 1. Clone the Project
```bash
git clone [https://github.com/YOUR_USERNAME/gig-scout.git](https://github.com/YOUR_USERNAME/gig-scout.git)
cd gig-scout```


###2. Install Tools (The Plumbing)
"Bash"

```npm install```

###3. Configure Secrets

Create a .env.local file in the root folder and add your keys:
"Code snippet"

```NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
STRIPE_SECRET_KEY=your_stripe_secret_key```

###4. Launch the App (Start Engine)
"Bash"

```npm run dev```

Your app will now be live at http://localhost:3000.
📜 License

This project is licensed under the MIT License. [LICENSE.md](./LICENSE.md) for details.
