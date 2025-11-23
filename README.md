# kHP-AI VIP Investment Platform 🚀

A premium cryptocurrency investment simulation platform built with React, TypeScript, and Tailwind CSS. This application features a complete VIP hierarchy, referral system, and a comprehensive admin dashboard.

## ✨ Features

### 👤 User Features
- **Secure Authentication:** Login and Registration with invite code validation.
- **Dashboard:** Real-time visualization of total assets, locked principal, and accumulated profits.
- **VIP System:** 6 Tiered VIP levels with automatic upgrades based on balance.
  - **VIP1:** 10.8% Daily Profit
  - **VIP6:** Up to 30% Daily Profit
- **Financial Operations:** 
  - Deposit simulation (USDT - BEP20, TRC20, Polygon).
  - Withdrawal requests with status tracking.
- **Referral System:** 3-Level automated commission system (Level 1: 10%, Level 2: 5%, Level 3: 2%).
- **Notifications:** In-app and browser notifications for profits and transaction updates.
- **Localization:** Primary Arabic interface (RTL) with English toggle support.

### 🛡️ Admin Features
- **Dashboard Overview:** Statistics for total users, pending requests, and net cash flow.
- **Transaction Management:** Approve or Reject deposit and withdrawal requests.
- **User Management:** View user details, team stats, ban/unban users.
- **Impersonation:** Ability to log in as any user for support purposes.
- **Balance Control:** Manual addition/deduction of funds.

## 🛠️ Tech Stack
- **Frontend:** React 19
- **Language:** TypeScript
- **Styling:** Tailwind CSS (via CDN & Config)
- **Icons:** Lucide React
- **State/Persistence:** LocalStorage (Mock Database Service)

## 🚀 Getting Started

### Default Admin Credentials
To access the admin panel, use the following credentials on the login screen:
- **Phone:** `admin`
- **Password:** `admin`

### Installation
1. Clone the repository.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm start
   ```

## ⚠️ Disclaimer
This project is a **simulation** intended for educational or demonstration purposes. It does not process real financial transactions or interact with real blockchains. All data is stored locally in the browser.
