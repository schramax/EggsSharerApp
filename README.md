# 🥚 EggsSharer App

**EggsSharer** is a free, cloud-synchronized Progressive Web App (PWA) designed for backyard 
chicken owners to effortlessly manage their flock's egg production, track customers, and 
monitor poultry finances — all from any device.

App URL: [EggsSharerApp](https://schramax.github.io/EggsSharerApp/EggsSharer.html)

---

## ✨ Features

### 🏠 Dashboard
- At-a-glance overview of current egg stock, total sales, and net balance.
- Quick-action buttons for the most common tasks.

### 🥚 Harvest Tracking
- Log daily egg collection with date and count.
- Automatic update if a harvest is already recorded for a given day (no duplicates!).
- Historical harvest log with delete capability.

### 👥 Consumer Management (CRM)
- Maintain a directory of customers and neighbors with name, phone, and notes.

### 🛒 Sales Management
- Log sales, gifts, or personal use transactions.
- One-tap WhatsApp sharing with a pre-filled message for each sale.
- Track payment methods (Bancontact, Payconiq, Cash...).

### 💶 Cost Tracking
- Record poultry expenses by category (Food, Litter, Medicine, Others).

### 📊 Reports & Analytics
- Interactive charts powered by Chart.js.
- Filter data by Last Month, 3 Months, Last Year, or All Time.
- Trends for egg stock levels, harvest volume, sales revenue, costs, and net profit.
- Pie charts for sales distribution and cost breakdown.

### ⚙️ Settings
- **Language:** Switch instantly between 🇬🇧 English and 🇫🇷 French.
- **Account Settings:** View your email, log out, or permanently delete your account.
- **Data Management:** Export/Import data as JSON backup, reset all data.
- **Force App Update:** One-tap button to bypass the cache and load the latest version.

---

## ☁️ Cloud Sync (Firebase)

EggsSharer uses **Firebase Authentication** and **Firebase Realtime Database** to securely 
sync your flock's data across all your devices in real time.

- Every family member logs in with the same shared email & password to access a common dataset.
- Data is stored in a private, user-isolated cloud database — no one else can see your data.
- The app works fully **offline** and automatically syncs when reconnected.
- Multiple independent families or flocks can each create their own separate account.

---

## 📱 Installation (as a PWA)

**iPhone (iOS — Safari only):**
1. Visit the app URL in **Safari**.
2. Tap the **Share** button → **Add to Home Screen**.

**Android (Chrome):**
1. Visit the app URL in **Chrome**.
2. Tap the **three-dot menu** → **Install app** (or "Add to Home Screen").

App URL: [EggsSharerApp](https://schramax.github.io/EggsSharerApp/EggsSharer.html)

Once installed, the app icon appears on your home screen and launches in full-screen mode, 
just like a native app!

---

## 🛠️ Technical Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML, CSS, JavaScript |
| Charts | [Chart.js](https://www.chartjs.org/) + chartjs-plugin-datalabels |
| Icons | [Lucide Icons](https://lucide.dev/) |
| Cloud Sync | [Firebase Realtime Database](https://firebase.google.com/) |
| Authentication | [Firebase Authentication](https://firebase.google.com/) |
| Hosting | [GitHub Pages](https://pages.github.com/) |
| Offline Support | Service Worker (PWA) |

---

## 🔒 Privacy

All user data is stored exclusively in your private Firebase cloud account, isolated by 
authenticated user ID. The app source code is public, but **your flock data is always private**.

---

*Created with 🥚 by schrammax*
