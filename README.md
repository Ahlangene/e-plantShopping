# 🌿 Paradise Nursery - Plant Shopping Application

An interactive e-commerce web application for purchasing various indoor plants, built with React and Redux Toolkit.

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Components](#components)
- [Redux State Management](#redux-state-management)
- [Features in Detail](#features-in-detail)
- [Screenshots](#screenshots)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

Paradise Nursery is a responsive web application that allows users to browse through different categories of plants, view detailed information about each plant, and manage their shopping cart. The application provides a seamless shopping experience with real-time cart updates and total price calculations.

## ✨ Features

### Current Features
- **Product Browsing**: Browse plants across 5 different categories
  - Air Purifying Plants
  - Aromatic Fragrant Plants
  - Insect Repellent Plants
  - Medicinal Plants
  - Low Maintenance Plants

- **Shopping Cart Functionality**
  - Add items to cart
  - Remove items from cart
  - Update item quantities
  - Real-time total price calculation
  - Individual item total calculation

- **User Interface**
  - Responsive design
  - Visual feedback when adding items to cart
  - Clean and intuitive navigation
  - Plant information page

### Planned Features
- Checkout functionality
- User authentication
- Order history
- Plant reviews and ratings
- Search and filter options

## 🛠 Tech Stack

- **Frontend Framework**: React.js
- **State Management**: Redux Toolkit
- **Styling**: CSS Modules
- **Icons**: SVG icons
- **Build Tool**: Create React App

## 📁 Project Structure
paradise-nursery/
├── src/
│ ├── components/
│ ├── CartItem.jsx
│ ├── CartItem.css
│ ├── ProductList.jsx
│ ├── ProductList.css
│ ├── CartSlice.jsx
│ └── App.js
├── public/
│ └── vite.svg
├── package.json
├── README.md
└── .gitignore

## 🚀 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### Step-by-step Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/paradise-nursery.git
cd paradise-nursery
Install dependencies

bash
npm install
# or
yarn install
Install Redux dependencies

bash
npm install @reduxjs/toolkit react-redux
# or
yarn add @reduxjs/toolkit react-redux
Start the development server

bash
npm start
# or
yarn start
Open your browser
Navigate to http://localhost:3000 to view the application