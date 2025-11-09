# Pokédex App

A modern Pokédex web app built using **Next.js**, **React**, **Material UI**, and **PokeAPI**. This app allows users to browse Pokémon by type, view detailed information, and explore evolution chains.

## Live Demo

[Deployment Link](https://pokemon-reyid.netlify.app)

---

## Setup Instructions

1. **Clone the repository:**

```bash
git clone hhttps://github.com/wawanneutron/pokemon-pokede-catalog.git
cd pokemon-pokede-catalog
```

2. **Install dependencies:**

```bash
npm install
# or
yarn install
```

3. **Run development server:**

```bash
npm run dev
# or
yarn dev
```

4. Open `http://localhost:3000` in your browser.

---

## Features Implemented

- Welcome modal shown on first visit using `sessionStorage`
- Browse Pokémon list with pagination and filters by type
- View Pokémon evolution chains with navigation to each
- Fetch Pokémon details with pagination
- Type-based accent background and colors
- Responsive UI with Material UI components
- Reusable pagination hook and modular hooks for fetching data
- Dynamic routing with query params (e.g., `/pokemon/type?name=fire`)
- SEO optimization with meta tags
- Compare Pokémon feature to view multiple Pokémon side by side

---

## Technical Decisions

- **Next.js App Router** was chosen for flexible routing and server/client components.
- **React Query** (`@tanstack/react-query`) was used for data fetching, caching, and background updates.
- **Material UI (MUI)** provided a clean and customizable UI component system.
- **PokeAPI** serves as the data source for all Pokémon-related info.
- **Session Storage** is used for temporary state persistence (e.g., welcome modal).
- **Pagination logic** was encapsulated into a custom `usePagination` hook for reuse.

---

## Contact

- Email: hellowawansetiawan@gmail.com

- WhatsApp: +62 877-3269-7337

- LinkedIn: [linkedin.com/in/wawan setiawan](https://www.linkedin.com/in/wawan-setiawan-84934a206/)
