# 🛒 E-Commerce PWA (Progressive Web App) built with React.js
-"Company": CODTECH IT SOLUTIONS -"NAME": MUZAMIL AHMED -"INTERN ID": CT04DL559 -"DOMAIN": FRONT END DEVELOPMENT -"DURATION": 4 WEEKS -"MENTOR": NEEL SANTOSH

📄 Project Description
The E-Commerce PWA is a cutting-edge web application designed to provide users with a fast, smooth, and reliable shopping experience across all devices. Developed using React.js, the app adopts a modular component-based architecture and modern frontend practices. This project was created with a strong focus on performance, user experience, and responsiveness, making it ideal for both mobile and desktop users.

One of the standout features of this e-commerce platform is that it is a Progressive Web App (PWA). This means the application can be installed on a user's device, function offline, and send push notifications—bridging the gap between web and native mobile apps. This was achieved using Vite for fast development and the vite-plugin-pwa to integrate service workers, cache static assets, and register the app for offline use.

The app includes essential e-commerce features such as a dynamic product listing, product detail pages, a shopping cart, and a checkout flow. Users can browse through various products, filter them based on categories, and add items to their cart. The cart is managed using React Context API and stored in localStorage to maintain state even when the browser is refreshed or closed.

The UI is fully responsive and designed using CSS Modules/Tailwind CSS, ensuring compatibility across smartphones, tablets, and desktops. Routing is handled using React Router, enabling seamless navigation between pages without reloading.

Another powerful aspect of this PWA is its offline functionality. If users lose internet connectivity, they can still browse cached pages and access previously loaded content. This feature greatly improves reliability and user retention, especially in areas with poor network access.

Overall, the E-Commerce PWA showcases how modern web technologies can be combined to deliver a rich, native-like shopping experience on the web. It is an ideal solution for developers or businesses looking to create scalable, user-friendly online stores that meet today’s performance and accessibility standards.

#OUTPUT
![Image](https://github.com/user-attachments/assets/17529ed9-1912-4ed3-ba51-c9e4b0e9a9d8)

![Image](https://github.com/user-attachments/assets/634a0493-1a60-4d77-943e-3327c0cf71af)

![Image](https://github.com/user-attachments/assets/e0b0cae0-2d4f-46a3-bf35-11de2f8459c4)

![Image](https://github.com/user-attachments/assets/502ae69c-9e3f-4882-8170-388e380717fc)

![Image](https://github.com/user-attachments/assets/7c3df48a-95f3-4a8e-b022-117cd4eb8440)

![Image](https://github.com/user-attachments/assets/b62b4da7-a292-4561-b1cb-93089affa1d6)

## 🚀 Features

- ⚛️ Built with React.js and Vite for fast performance
- 📦 Add to Home Screen (A2HS) capability
- 📶 Offline support via Service Workers
- 🔔 Push notifications
- 🛍️ Product listing and detailed product pages
- 🔍 Search and filter functionality
- 🛒 Add to Cart, Remove from Cart
- 🧾 Checkout flow (static or with dummy payment)
- 📱 Responsive Design for all devices
- 🌐 Clean and intuitive UI/UX
- 💾 Caching using Workbox / Cache API

## 📦 Technologies Used

- React.js
- Vite
- Vite-plugin-PWA
- React Router
- LocalStorage / IndexedDB (for cart persistence)
- Tailwind CSS / CSS Modules (optional based on your setup)
- Firebase / Mock APIs (if backend is included)
- Service Workers

## 🛠️ Getting Started

### Prerequisites

- Node.js >= 14.x
- npm or yarn

### Installation

```bash
git clone https://github.com/Qudsiya954/React-E-com.git
cd React-E-com
npm install
```

📬 Push Notifications
Push notifications are configured via Firebase or a third-party service. You may need to set up your own notification service to fully enable this feature.

💡 Future Enhancements
Full backend integration with payments and authentication

Admin dashboard for managing products

Wishlist and reviews system

Multi-language support

🙌 Author
Qudsiya Siddique

AIML Student | Web Developer | React Enthusiast






















# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
