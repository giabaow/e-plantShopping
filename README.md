# e-plantShopping

## Paradise Nursery

Paradise Nursery is a React-based shopping application for houseplant enthusiasts. The app allows users to browse a curated selection of houseplants organized into categories, view plant details (thumbnail, name, and price), and add plants to a shopping cart. The shopping cart page lets users review their selected items, adjust quantities, remove items, and see the total cost — all powered by Redux for state management.

### Features

- **Landing Page** — Introduces the company with a background image, a short description of Paradise Nursery, and a "Get Started" button that takes users to the product listing.
- **Product Listing Page** — Displays houseplants grouped into multiple categories, each with a thumbnail, name, price, and an "Add to Cart" button.
- **Shopping Cart Page** — Shows all items added to the cart, including quantity controls (increase/decrease), a delete option, the total cost per item, and the overall cart total.
- **Header/Navbar** — Present on both the product listing and cart pages, with a dynamically updating cart icon and navigation links to Home, Plants, and Cart.

### Tech Stack

- React
- Redux (Redux Toolkit) for cart state management
- CSS for styling
- GitHub Pages for deployment

### Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/giabaow/e-plantShopping.git
   ```
2. Install dependencies:
   ```
   cd e-plantShopping
   npm install
   ```
3. Run the app locally:
   ```
   npm start
   ```

### Deployment

This project is deployed using GitHub Pages. The live app can be accessed at:
`https://giabaow.github.io/e-plantShopping/`

### Project Structure

- `App.jsx` — Landing page with company name and "Get Started" button
- `App.css` — Styling including the landing page background image
- `AboutUs.jsx` — Company details
- `ProductList.jsx` — Product listing page with categorized plants
- `CartItem.jsx` — Shopping cart page
- `CartSlice.jsx` — Redux slice managing cart state