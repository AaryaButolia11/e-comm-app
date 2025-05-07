# Simple E-Commerce Web Application



## Overview

This is a **simple e-commerce web application** that allows users to browse a list of products, add them to their shopping cart, and proceed to checkout. The app also provides the ability to toggle between **light** and **dark themes**.

The shopping cart allows users to:
- Add items to the cart
- View the cart contents and the total price
- Checkout and clear the cart
- Switch between themes for a personalized shopping experience

The cart is persistent using **localStorage**, so the contents are maintained even after a page reload.

## Key Features

- **Product List**: Display a list of products with their prices.
- **Add to Cart**: Users can add products to the cart with a button click.
- **Remove from Cart**: Users can remove items from the cart.
- **Persistent Cart**: The cart data persists in `localStorage` even after refreshing the page.
- **Checkout**: Once the user is ready, they can checkout to finalize their order.
- **Theme Toggle**: Switch between **light** and **dark themes** with a button click.
- **Responsive**: The app is mobile-friendly, ensuring a great experience on all devices.

---
## Screenshots

![Screenshot 2025-05-07 224220](https://github.com/user-attachments/assets/bf4baa40-3b97-4110-9f46-e5e9956a8de8)

![Screenshot 2025-05-07 224227](https://github.com/user-attachments/assets/3600b552-18b7-4a01-8021-dd0506338575)


![Screenshot 2025-05-07 224240](https://github.com/user-attachments/assets/97d9f68c-a1d4-4caf-b631-2601a0df9ba0)

---

## Demo

You can view a live demo by cloning the repository and opening the `index.html` file in your browser.

---

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Features](#features)
4. [Technologies Used](#technologies-used)
5. [Project Structure](#project-structure)
6. [Contributing](#contributing)
7. [License](#license)

---

## Installation

To get started, follow these steps to clone and set up the project locally:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/simple-e-commerce.git
    ```

2. **Navigate to the project folder**:
    ```bash
    cd simple-e-commerce
    ```

3. **Open the `index.html` file** in your preferred browser.

No additional installation steps are needed, as this is a static web application.

---

## Usage

1. Open `index.html` in any modern browser (Chrome, Firefox, Safari).
2. Browse through the **product list** and click "Add to cart" to add items.
3. Once you add items to the cart, you can view the cart contents below.
4. You can checkout by clicking the **Checkout** button, which will alert the total and clear the cart.
5. Toggle between the **light** and **dark themes** by clicking the "Change Theme" button.

---

## Features

### 1. **Product List**
   - A simple, scrollable list of available products, with their names and prices.
   - **Add to Cart** button to add products to the cart.

### 2. **Shopping Cart**
   - Users can view the items they added to the cart.
   - Shows the **total price** of all items in the cart.
   - **Empty Cart** message when the cart is empty.

### 3. **Checkout**
   - Displays an alert with the total price upon checkout and clears the cart.

### 4. **Theme Toggle**
   - **Dark theme** is applied by default.
   - Users can switch to the **light theme** and vice versa by clicking the "Change Theme" button.

### 5. **Persistence**
   - The shopping cart data is stored in `localStorage`, ensuring that cart items are preserved even after page reloads.

---

## Technologies Used

- **HTML5**: The basic structure of the web application.
- **CSS3**: Styling for both **dark** and **light themes**.
- **JavaScript (ES6)**: Handling cart functionality, theme toggling, and localStorage persistence.

---

## Project Structure

```plaintext
simple-e-commerce/
├── index.html         # Main HTML structure
├── styles.css         # Styling for both themes and layout
├── script.js          # JavaScript for app logic, cart, theme toggling
└── README.md          # This file, project documentation
