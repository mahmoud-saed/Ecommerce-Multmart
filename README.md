# 🛒 Ecommerce-Multmart

A responsive furniture e-commerce website built with React.js and Firebase, offering a seamless shopping experience.

## 🔗 Live Demo

Explore the live application: [multimart-e-commerce.netlify.app](https://multimart-e-commerce.netlify.app/)

(Note: Registration required. You can use: demouser@gmail.com / Password: Demo123) 

## 📋 Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## 📖 Introduction

Ecommerce-Multmart is a front-end project that simulates a furniture e-commerce platform. It leverages React.js for building interactive user interfaces and Firebase for backend services.

## ✨ Features

- Product listing with images and details
- Shopping cart functionality
- User authentication using Firebase
- Responsive design for various devices
- Real-time database updates

## 🛠️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mahmoud-saed/Ecommerce-Multmart.git
   cd Ecommerce-Multmart
   ```



2. **Install dependencies:**

   ```bash
   npm install
   ```



3. **Start the development server:**

   ```bash
   npm start
   ```



   The application will run at `http://localhost:3000`.

## 🚀 Usage

- Browse through the furniture products.
- Add desired items to the shopping cart.
- Register or log in to proceed with purchases.
- View and manage items in the cart.

## ⚙️ Configuration

To connect the application with your Firebase project:

1. Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
2. In the project settings, locate your Firebase configuration.
3. Create a `.env` file in the root directory and add your Firebase credentials:

   ```env
   REACT_APP_FIREBASE_API_KEY=your_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
   REACT_APP_FIREBASE_PROJECT_ID=your_project_id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
   REACT_APP_FIREBASE_APP_ID=your_app_id
   ```



## 📦 Dependencies

- React.js
- Firebase
- React Router
- Other dependencies as listed in `package.json`

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.
