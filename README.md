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

---

# 🥚 EggsSharer App

**EggsSharer** est une Progressive Web App (PWA) gratuite et synchronisée dans le cloud, 
conçue pour les propriétaires de poules pondeuses souhaitant gérer facilement la production 
d'œufs de leur poulailler, suivre leurs clients et surveiller leurs finances — depuis n'importe 
quel appareil.

URL de l'application : [EggsSharerApp](https://schramax.github.io/EggsSharerApp/EggsSharer.html)

---

## ✨ Fonctionnalités

### 🏠 Tableau de bord
- Vue d'ensemble du stock d'œufs actuel, du total des ventes et du solde net.
- Boutons d'accès rapide aux tâches les plus courantes.

### 🥚 Suivi des récoltes
- Enregistrez la collecte quotidienne d'œufs avec la date et la quantité.
- Mise à jour automatique si une récolte est déjà enregistrée pour un jour donné (pas de doublons !).
- Historique des récoltes avec possibilité de suppression.

### 👥 Gestion des clients (CRM)
- Maintenez un répertoire de clients et voisins avec nom, téléphone et notes.

### 🛒 Gestion des ventes
- Enregistrez des ventes, des dons ou des transactions à usage personnel.
- Partage WhatsApp en un clic avec un message pré-rempli pour chaque vente.
- Suivi des modes de paiement (Bancontact, Payconiq, Espèces...).

### 💶 Suivi des coûts
- Enregistrez les dépenses du poulailler par catégorie (Nourriture, Litière, Médicaments, Autres).

### 📊 Rapports & Analyses
- Graphiques interactifs alimentés par Chart.js.
- Filtrage des données par Mois dernier, 3 Mois, L'année dernière ou Toujours.
- Tendances du niveau de stock, du volume de récolte, des revenus, des coûts et du bénéfice net.
- Graphiques en camembert pour la répartition des ventes et des coûts.

### ⚙️ Paramètres
- **Langue :** Basculez instantanément entre 🇬🇧 l'anglais et 🇫🇷 le français.
- **Paramètres du compte :** Consultez votre e-mail, déconnectez-vous ou supprimez définitivement votre compte.
- **Gestion des données :** Exportez/importez les données en sauvegarde JSON, réinitialisez toutes les données.
- **Forcer la mise à jour :** Bouton en un clic pour ignorer le cache et charger la dernière version.

---

## ☁️ Synchronisation dans le cloud (Firebase)

EggsSharer utilise **Firebase Authentication** et **Firebase Realtime Database** pour 
synchroniser en toute sécurité les données de votre poulailler sur tous vos appareils en 
temps réel.

- Chaque membre de la famille se connecte avec le même e-mail et mot de passe partagés pour accéder à un ensemble de données commun.
- Les données sont stockées dans une base de données cloud privée et isolée par utilisateur — personne d'autre ne peut voir vos données.
- L'application fonctionne entièrement **hors ligne** et se synchronise automatiquement lors de la reconnexion.
- Plusieurs familles ou poulaillers indépendants peuvent chacun créer leur propre compte séparé.

---

## 📱 Installation (en tant que PWA)

**iPhone (iOS — Safari uniquement) :**
1. Visitez l'URL de l'application dans **Safari**.
2. Appuyez sur le bouton **Partager** → **Sur l'écran d'accueil**.

**Android (Chrome) :**
1. Visitez l'URL de l'application dans **Chrome**.
2. Appuyez sur le **menu à trois points** → **Installer l'application** (ou "Ajouter à l'écran d'accueil").

URL de l'application : [EggsSharerApp](https://schramax.github.io/EggsSharerApp/EggsSharer.html)

Une fois installée, l'icône de l'application apparaît sur votre écran d'accueil et se lance 
en mode plein écran, comme une application native !

---

## 🛠️ Stack Technique

| Couche | Technologie |
|---|---|
| Frontend | HTML, CSS, JavaScript Vanilla |
| Graphiques | [Chart.js](https://www.chartjs.org/) + chartjs-plugin-datalabels |
| Icônes | [Lucide Icons](https://lucide.dev/) |
| Sync Cloud | [Firebase Realtime Database](https://firebase.google.com/) |
| Authentification | [Firebase Authentication](https://firebase.google.com/) |
| Hébergement | [GitHub Pages](https://pages.github.com/) |
| Support hors ligne | Service Worker (PWA) |

---

## 🔒 Confidentialité

Toutes les données utilisateur sont stockées exclusivement dans votre compte Firebase privé, 
isolé par identifiant utilisateur authentifié. Le code source de l'application est public, 
mais **les données de votre poulailler restent toujours privées**.

---

*Créé avec 🥚 par schrammax*

