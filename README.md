# E-Commerce React App

A responsive React e-commerce storefront built with Vite, Bootstrap, and React Router. The application includes product browsing, wishlist management, shopping cart functionality, and product detail pages.

## Key Features

- Product catalog with multiple product sources
- Wishlist management with localStorage persistence
- Shopping cart operations including add, increment, decrement, and delete
- Product details and dynamic routing
- Responsive UI powered by Bootstrap and React components
- Alerts and feedback using SweetAlert2

## Technologies

- React 18
- Vite
- Bootstrap 5
- React Router DOM
- Axios
- React Slick + Slick Carousel
- SweetAlert2

## Project Structure

- `src/` – main application code
- `src/components/` – reusable UI components
- `src/App.jsx` – app routing and global state management
- `src/main.jsx` – React entry point

## Getting Started

### Prerequisites

- Node.js 18+ or compatible version
- npm or yarn

### Install dependencies

```bash
npm install
```

### Run the app locally

```bash
npm run dev
```

Then open the local URL shown in the terminal, usually `http://localhost:5173`.

## Notes

- The application expects a backend API at `http://localhost:3001`.
- The front-end code references endpoint paths:
  - `/products1`
  - `/products2`
  - `/products3`

If you are using a JSON server, make sure it is running on port `3001` and that the expected routes are available.

## Available Scripts

- `npm run dev` – start development server
- `npm run build` – build production assets
- `npm run preview` – preview production build
- `npm run lint` – run ESLint

## Recommendations

- Use a separate JSON server or API service for product data
- Keep product data persisted in localStorage for wishlist and cart state
- Improve accessibility and mobile usability by reviewing component layouts

## License

This project is currently private and available for customization.
