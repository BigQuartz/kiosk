# Modern Coffee Shop POS & Kiosk System

*[🇮🇷 برای مطالعه توضیحات به زبان فارسی اینجا کلیک کنید (Persian)](README-fa.md)*

A sleek, fully-featured Point of Sale (POS) and self-service Kiosk application designed specifically for coffee shops and cafes. This repository serves as a **portfolio showcase** of my frontend UI/UX design and full-stack development capabilities. 

Built with React, TypeScript, and Tailwind CSS, this system features a beautiful glassmorphism UI, a comprehensive admin dashboard, and robust order customization handling.

## 🌟 Key Features

- **Bilingual Support:** Seamlessly switch between English and Persian (RTL support) across the entire application.
- **Advanced Product Variations:** Support for complex coffee configurations (Single/Double/Both shots, alternative milks, syrups) with intelligent dropdown toggles and cascading options.
- **Real-time Inventory Management:** Track stock levels for individual items and add-on options, automatically preventing orders when items or ingredients run out.
- **Glassmorphism UI:** A modern, highly responsive design with elegant animations and multiple thematic color palettes.
- **Self-Service Kiosk Mode:** Includes idle screensavers and promotional advertisement loops when the system is inactive.

---

## 🎛️ The Admin Dashboard

The application includes a highly sophisticated, password-protected admin dashboard designed for cafe managers to completely control the system without touching code:

- **Live Order Tracking:** Real-time monitoring of incoming orders, payment statuses, and fulfillment tracking.
- **Market Analytics & Performance:** 
  - Visual KPI charts tracking total revenue and sales volume over custom date ranges. 
  - Granular breakdown tables showing exactly how individual sub-items, options, and coffee types are performing.
- **Menu & Inventory Manager:** A fully dynamic editor to create and reorder categories, items, and global options. Managers can set complex rules like requiring specific coffee types, adding sub-options, and setting exact inventory limits.
- **System & Device Configuration:** Manage kiosk idle screensaver timeouts, advertisement media, add and configure network thermal receipt printers (set IP addresses, enable/disable multiple printers), design receipt layouts, and control global application themes.

---

## 🛠️ Tech Stack

- **Frontend:** React 18, TypeScript, Vite
- **Styling:** Tailwind CSS (Custom glassmorphism & responsive design)
- **Backend/State:** Node.js, Express (API routing and persistent state handling)
- **Icons:** Lucide React
- **Hardware Integration:** Python scripts bridging web interactions with local ESC/POS network thermal printers.

---

## 📸 Screenshots

> *(Drag and drop your screenshots here to showcase the app!)*

### Customer Kiosk & Ordering Flow
| Kiosk Menu | Item Customization |
| :---: | :---: |
| <img src="screenshots/menu-view.png" width="400" alt="Menu View"/> | <img src="screenshots/customization.png" width="400" alt="Item Customization"/> |

### Manager Admin Dashboard
| Analytics & Market Performance | Menu Configuration |
| :---: | :---: |
| <img src="screenshots/analytics.png" width="400" alt="Analytics Dashboard"/> | <img src="screenshots/menu-editor.png" width="400" alt="Menu Editor"/> |
