# KiranaTally 🏪

KiranaTally is a modern, responsive web application designed to streamline operations for local Kirana stores (general stores). It provides a comprehensive suite of tools for inventory management, billing, digital ledger (Khata) tracking, and comprehensive reporting.

Built with a specialized focus on the Indian retail context, it aims to digitize daily operations and provide actionable insights to store owners.

> **Note:** This is a closed-source production project. The code provided here is for explanation and demonstration purposes only and is not intended for public deployment.

---

## ✨ Key Features

* **📊 Dashboard:** Real-time overview of store performance, sales trends, and key metrics.
* **📦 Inventory Management:** Easy-to-use interface to track stock levels, manage product details, and monitor low-stock items.
* **🧾 Billing System:** Fast and efficient billing interface for quick customer checkout.
* **📒 Khata (Digital Ledger):** Manage customer credits and debits digitally, replacing traditional paper ledgers.
* **🚚 Supplier Management:** (Admin Only) Keep track of suppliers and purchase orders.
* **📈 Reports & Analytics:** (Admin Only) Generate detailed PDF reports for sales, inventory, and financial health.
* **⚙️ Role-Based Access Control:** Secure access with separate roles for Admins and Staff members.
* **📱 Mobile-First Design:** Fully responsive interface optimized for both desktop and mobile devices.

## 🛠️ Tech Stack

### Frontend

* **[React](https://react.dev/):** The library for web and native user interfaces.
* **[Vite](https://vitejs.dev/):** Next Generation Frontend Tooling for fast development and build.
* **[Tailwind CSS](https://tailwindcss.com/):** A utility-first CSS framework for rapid UI development.
* **[Framer Motion](https://www.framer.com/motion/):** A production-ready motion library for React.
* **[Lucide React](https://lucide.dev/):** Beautiful & consistent icons.
* **[Recharts](https://recharts.org/):** A composable charting library built on React components.

### Backend / Services

* **[Supabase](https://supabase.com/):** An open source Firebase alternative for Database and Authentication.

### Utilities

* **PDF Generation:** `html2pdf.js`, `jspdf`, `jspdf-autotable`.
* **PWA Support:** `vite-plugin-pwa` for offline capabilities and app-like experience.
