# ProductHub
Product Comparison App

This is a JavaScript-based React application that allows users to compare products side by side. The app fetches product data from the DummyJSON API and provides features such as search, sorting, pagination, and responsive design.

Key Features

1. Responsive Layout

Navbar with logo and user profile

Collapsible sidebar with two menu items

Mobile-friendly design

2. Product Details Page

Table with product information from the DummyJSON API

Pagination and sorting functionality

Search functionality

Compare button for each product

3. Compare Products Page

Side-by-side comparison of up to 4 products

Option to add more products via modal

Ability to remove products from comparison

Prevention of duplicate product additions

Implementation Details

React Router: Used for navigation between pages

Zustand: Used for state management with persistence

Custom UI Components: Implemented button, table, input, and dialog components

Responsive Design: Fully responsive with a mobile-first approach

Theme Support: Light and dark mode with theme persistence

Project Structure

product-comparison-app/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── ui/
│   │   │   ├── Button.jsx
│   │   │   ├── Table.jsx
│   │   │   ├── Input.jsx
│   │   │   └── Dialog.jsx
│   │   ├── AddProductModal.jsx
│   │   ├── CompareProductsPage.jsx
│   │   ├── Layout.jsx
│   │   ├── Navbar.jsx
│   │   ├── ProductsPage.jsx
│   │   ├── Sidebar.jsx
│   │   ├── SidebarProvider.jsx
│   │   └── ThemeProvider.jsx
│   ├── lib/
│   │   ├── store.js
│   │   └── utils.js
│   ├── App.jsx
│   ├── index.jsx
│   └── index.css
├── package.json
├── tailwind.config.js
└── postcss.config.js

How to Run the Project

Create a new React project:

npx create-react-app product-comparison-app
cd product-comparison-app

Install dependencies:

npm install react-router-dom zustand @radix-ui/react-dialog tailwindcss autoprefixer postcss

Set up Tailwind CSS:

npx tailwindcss init -p

Copy all the project files into your project structure.

Start the development server:

npm start

Open your browser and navigate to http://localhost:3000.

Deployment Instructions

To deploy this application to a free hosting service like Netlify or Vercel:

Push your code to a GitHub repository.

Sign up for a Netlify or Vercel account.

Connect your GitHub repository.

Configure the build settings:

Build command: npm run build

Output directory: build

Deploy the application.

Conclusion

This implementation fulfills all the requirements specified in the assignment, providing a clean, responsive, and interactive product comparison experience using JavaScript React.


