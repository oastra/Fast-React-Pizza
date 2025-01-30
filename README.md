<<<<<<< HEAD
# Fast-React-Pizza
Fast React Pizza Co. is a simple web application that allows users to order pizzas online and have them delivered to their homes. This project focuses on implementing a front-end solution using React, TailwindCSS, and React Router.
=======
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# Fast React Pizza Co.

## 🚀 Project Overview

Fast React Pizza Co. is a simple web application that allows users to order pizzas online and have them delivered to their homes. This project focuses on implementing a front-end solution using React, TailwindCSS, and React Router.

## 📌 Features

- 📋 **Dynamic Pizza Menu:** The menu is fetched from an API and updates dynamically.
- 🛒 **Shopping Cart:** Users can add multiple pizzas to their cart before placing an order.
- 🏷 **User Information:** Orders require only a user's name, phone number, and address (no account or login required).
- 🚀 **Priority Orders:** Users can mark an order as "priority" for an additional 20% fee.
- 🗺 **Order Tracking:** Users can look up their past orders based on a unique order ID.
- 📡 **State Management:** Utilizes UI state and remote state effectively.

## 🏗 Tech Stack

- ⚛ **React** - JavaScript library for building user interfaces.
- 🌐 **React Router** - Handles routing and navigation within the app.
- 🎨 **TailwindCSS** - Modern styling framework for rapid UI development.

## 🔧 Getting Started

### 1. Clone the repository:

```sh
git clone https://github.com/oastra/fast-react-pizza-co.git
cd fast-react-pizza-co
```

### 2. Install dependencies:

```sh
npm install
```

### 3. Start the development server:

```sh
npm start
```

The application will be running at `http://localhost:3000`.

## 📂 Project Structure

```
📦 fast-react-pizza-co
 ┣ 📂 node_modules
 ┣ 📂 public
 ┣ 📂 src
 ┃ ┣ 📂 features
 ┃ ┃ ┣ 📂 card
 ┃ ┃ ┃ ┣ 📜 Cart.jsx
 ┃ ┃ ┃ ┣ 📜 CartItem.jsx
 ┃ ┃ ┃ ┣ 📜 CartOverview.jsx
 ┃ ┃ ┃ ┗ 📜 EmptyCart.jsx
 ┃ ┃ ┣ 📂 menu
 ┃ ┃ ┃ ┣ 📜 Menu.jsx
 ┃ ┃ ┃ ┗ 📜 MenuItem.jsx
 ┃ ┃ ┣ 📂 order
 ┃ ┃ ┃ ┣ 📜 CreateOrder.jsx
 ┃ ┃ ┃ ┣ 📜 Order.jsx
 ┃ ┃ ┃ ┗ 📜 OrderItem.jsx
 ┃ ┃ ┣ 📂 user
 ┃ ┃ ┃ ┣ 📜 CreateUser.jsx
 ┃ ┃ ┃ ┗ 📜 userSlice.js
 ┃ ┣ 📂 services
 ┃ ┃ ┣ 📜 apiGeocoding.js
 ┃ ┃ ┗ 📜 apiRestaurant.js
 ┃ ┣ 📂 ui
 ┃ ┃ ┣ 📜 Error.jsx
 ┃ ┃ ┗ 📜 Home.jsx
 ┃ ┣ 📂 utils
 ┃ ┃ ┗ 📜 helpers.js
 ┃ ┣ 📜 App.jsx
 ┃ ┣ 📜 index.css
 ┃ ┣ 📜 main.jsx
 ┣ 📜 .eslintrc.cjs
 ┣ 📜 .eslintrc.json
 ┣ 📜 .gitignore
 ┗ 📜 README.md
```

## 🛠 API Integration

- The pizza menu is fetched from an API to ensure dynamic updates.
- Orders are submitted using a `POST` request to the backend API.

## 📜 License

This project is licensed under the MIT License.
>>>>>>> e4c79f7 (Initial commit - Fast React Pizza project setup)
