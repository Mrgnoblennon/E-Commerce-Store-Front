# 🛍 E-Commerce Frontend

Welcome to the E-Commerce Frontend project! This is a modern, interactive front-end for an e-commerce platform, built using Next.js and TypeScript, and designed to work seamlessly with a separate backend web application. Please make sure you have setup the [E-Commerce-Admin](https://github.com/Mrgnoblennon/E-Commerce-Admin) and it is running correctly.

## 🚀 Features

- **Product Browsing**: View and search for products.
- **Cart Management**: Add, remove, and update items in the shopping cart.
- **User Authentication**: Secure login and signup with Clerk.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Checkout**: Integration with backend for payment processing.

## 📦 Dependencies

Here’s a list of the main dependencies used in this project:

- 🎨 `@headlessui/react`: UI component library
- 🌐 `axios`: HTTP client for making API requests
- 🔗 `clsx`: Utility for conditionally joining classNames
- 🖼 `lucide-react`: Icon library for React
- ⚡ `next`: React framework for server-side rendering and static site generation
- 🔍 `query-string`: Utility for parsing and stringifying URL query strings
- ⚛️ `react`: JavaScript library for building user interfaces
- 🌍 `react-dom`: Entry point to the DOM for React applications
- 🍞 `react-hot-toast`: Toast notification library for React
- 🌀 `tailwind-merge`: Utility for merging Tailwind CSS classes
- 🐻 `zustand`: State management library

## 🛠 DevDependencies

- 🛠️ `@types/node`: TypeScript types for Node.js
- 🔧 `@types/react`: TypeScript types for React
- 🔩 `@types/react-dom`: TypeScript types for React DOM
- 🧹 `eslint`: Linting tool for identifying and fixing code quality issues
- 🧭 `eslint-config-next`: ESLint configuration for Next.js
- ✂️ `postcss`: CSS post-processor for transforming styles
- 🌈 `tailwindcss`: Utility-first CSS framework
- 📘 `typescript`: Superset of JavaScript that adds static types

## 📑 Installation

To set up this project locally, follow these steps:


1. **Clone the repositry:**

  ```bash
  git clone https://github.com/Mrgnoblennon/E-Commerce-Store-Front.git
  cd ecommerce-frontend
  ```

2. **Install dependencies:**

  ```bash
  npm install
  ```

3. **Create a '.env' file and add this line**

  ```bash
  NEXT_PUBLIC_API_URL=http://localhost:"port"/api/"storeId"
  ```
  Make sure the port number matches the backend app and an existing store id is given.

4. **Change line in home page component**

  ```bash
  const billboard = await getBillboard("billboardId");
  ```
  The string value needs to match an existing billboard id or an error will be thrown.

5. **Run the development server:**

  ```bash
  npm run dev
  ```

## 🌟 Usage

- Home Page: Browse featured products and navigate through categories.
- Product Page: View detailed information about a product, including images, descriptions, and reviews.
- Cart: Manage items in your cart with real-time updates.
- Checkout: Proceed with purchasing items in the cart, including payment processing.

## 📦 API Integration

This frontend application communicates with a separate backend API for data retrieval and processing. Ensure the backend API is running and accessible from this frontend application.

## 🧩 Components

- Navbar: Provides navigation links and user authentication controls.
- ProductList: Displays a list of products fetched from the backend.
- ProductDetails: Shows detailed information about a specific product.
- Cart: Manages the user's cart items.
- Checkout: Handles the checkout process and integrates with the payment gateway.

## 🎨 Styling

Styling is handled using Tailwind CSS, with custom utilities merged via tailwind-merge. The design is responsive and adheres to modern UI/UX principles.

## 📧 Contact
For questions or feedback, please contact chasebarrettbrown@hotmail.com or checkout my [Github](https://github.com/Mrgnoblennon).