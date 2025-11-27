# React Practice Form Validation

A small React + TypeScript project that fetches user data from the public JSONPlaceholder API, provides a search form to filter users by name, and offers navigation to individual user detail pages.

## Features
- Fetches user records from `https://jsonplaceholder.typicode.com/users` using Axios on initial load. 
- Search form filters the list of users by name without additional API calls.
- Clickable user cards navigate to a dedicated detail page via React Router.
- Detail view shows contact, company, and address information with a back button to return to the list.
- Styled with Tailwind CSS 4 for a simple, responsive layout.

## Project Structure
- `src/Pages/HomePage.tsx` – Loads users, manages search form state, and renders the filtered list.
- `src/Components/UserList.tsx` – Displays user cards linking to detail routes.
- `src/Components/SearchList.tsx` – Search form component for filtering users.
- `src/Components/UserDetail.tsx` – Fetches and renders details for a selected user.
- `src/App.tsx` – Defines application routes.

## Getting Started
### Prerequisites
- Node.js and npm installed.

### Installation
```bash
npm install
```

### Running the app
```bash
npm run dev
```
Then open the printed local URL (default `http://localhost:5173`) in your browser.

### Build for production
```bash
npm run build
```

## Deployment
The project is configured for GitHub Pages using `npm run deploy`, which builds the site and publishes the `dist` folder to the `gh-pages` branch. The `homepage` field in `package.json` is set for the GitHub Pages path.

## Tech Stack
- React 19 with TypeScript
- Vite for bundling and development server
- React Router 7
- Axios for HTTP requests
- Tailwind CSS 4 for styling
