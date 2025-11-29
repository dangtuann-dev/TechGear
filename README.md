# TechGear — Computer Hardware E-commerce Website (Static Front-end)

This project provides the UI for an e-commerce website specialized in computer hardware and accessories (laptops, PCs, monitors, keyboards, mice, SSDs, USB‑C hubs, etc.). The codebase is pure HTML/CSS/JavaScript and can be deployed on any static hosting.

## Key Features

- Homepage sections: banner, categories, Flash Sales, Best Selling, Our Products, and Featured.
- Flash Sales countdown implemented with vanilla JavaScript (location: `index.html:1057–1093`).
- Product listings with pricing and navigation to individual product detail pages.
- Multiple product detail pages under `html/product-details/`.
- Cart page UI mock at `html/cart.html`.
- Contact (`html/contact.html`), About (`html/about.html`), Sign Up (`html/signup.html`), and Login (`html/login.html`) pages.
- Shared header and footer, Google Fonts, and Font Awesome icons.

## Tech Stack

- HTML5 and CSS3 (reset, common, and per-page styles).
- Vanilla JavaScript for simple interactions (Flash Sales countdown).
- Google Fonts: Poppins, Inter.
- Font Awesome 6 for icons.

## Folder Structure

- `index.html`: Homepage.
- `html/`: Content and product detail pages.
  - `product-details/`: 17 product detail pages for laptops, devices, and accessories.
  - `about.html`, `contact.html`, `cart.html`, `signup.html`, `login.html`, `error.html`.
- `assets/`
  - `css/`: Stylesheets (`reset.css`, `common.css`, `index.css`, `about.css`, `contact.css`, `cart.css`, `login.css`, `signup.css`, `signuplog.css`, `product-details.css`, `erro.css`).
  - `img/`, `icon/`, `product-img/`: Images and icons used across the site.
  - `favicon/`: Browser icons and manifest.

## Run Locally

- Quick start: open `index.html` directly in your browser.
- Recommended: use a static server (e.g., VS Code Live Server) for consistent relative paths.

## Deployment

- Deploy on static hosting providers such as GitHub Pages, Netlify, Vercel, or Firebase Hosting.
- Upload the entire project folder; the entry file is `index.html`.

## Content Notes

- Some “View All” links or actions (e.g., update cart button, apply coupon) currently point to `html/error.html` to simulate navigation flows.
- Product data is static demo content; real cart, checkout, and search are not implemented yet.

## Team

- Nguyen Ngoc Hien — 2400008831
- Dang Thanh Tuan — 2400000749

## Roadmap

- Implement functional search and product filters.
- Build real cart, ordering, and checkout (REST API or GraphQL).
- Admin features (create/update/delete products) with database integration.
- Improve responsiveness, image performance, lazy loading, and SEO.
- Enhance accessibility (ARIA, contrast, keyboard navigation).

## Contributing

- Open issues describing proposals/bugs.
- Create pull requests with detailed change descriptions.

## License

- This project is for educational purposes and front-end UI showcasing.
