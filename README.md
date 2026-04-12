# SAHAN DATA – Data & Airtime Purchase Platform

**SAHAN DATA** waa web app isticmaalayaashu ku iibsadaan data packages iyo airtime, kana qayb galaan tartamo, leaderboard, iyo abaalmarino iyadoo la adeegsanayo referral link iyo promo code. Waxaa loo dhisay **Supabase** backend iyo frontend-ka **HTML/CSS/JS** oo leh glassmorphism design.

## ✨ Features

- 🔐 **Authentication** – Login using email/password or promo code/password + reset password
- 📝 **Registration** – Auto‑generated promo code, readonly group code, optional referral code
- 🛒 **Buyer wizard (5‑step)** – Easy purchase flow with USSD auto‑dial
- 📊 **Live dashboard** – Personal stats: referrals, bonus points, promo code, group code
- 🏆 **Leaderboard** – 6 competition types (weekly referrals, monthly promoted/seller, top districts/groups/schools) with filters & progress bars
- 🎁 **Rewards history** – Official winners stored in `rewards` table
- 👑 **Admin panel** – Manage orders & products (only for `is_admin` users)
- 📈 **Real‑time stats** – Total users, orders, districts, groups, schools on homepage
- 🔗 **Referral & promo system** – Each order generates up to 6 transaction records (buyer, district, group, school, referral, promo)
- 📱 **Mobile responsive** – Works on phones and desktops

## 🛠 Tech Stack

| Layer       | Technology                          |
|-------------|-------------------------------------|
| Frontend    | HTML5, CSS3 (Glassmorphism), JavaScript (ES6) |
| Backend     | Supabase (PostgreSQL + Auth + RLS)  |
| Database    | PostgreSQL with RPC functions, triggers, sequences |
| Hosting     | GitHub Pages / any static host      |

## 🗂 Project Structure
