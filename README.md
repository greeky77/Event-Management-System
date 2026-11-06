# Gatherly

Gatherly is a responsive event discovery and registration website built with plain HTML, CSS, and JavaScript. Browse a curated calendar, search and filter by category, save favorites, view event details, and register for a spot.

## Features

- Responsive layouts for desktop, tablet, and mobile
- Event cards with photography, dates, venues, category, and price
- Live search, category filters, and sort control
- Event details dialog with client-side form validation
- Registration confirmation and saved ticket list
- Favorites, registrations, and theme preference saved with Local Storage
- Light/dark mode, reduced-motion support, and keyboard shortcuts (`Ctrl/⌘ + K`)
- Newsletter signup interaction

## Run locally

No build step or dependencies are required. Open `index.html` in a browser, or serve the folder with any static server, for example:

```sh
npx serve .
```

## Deploy

This is a static site and can be deployed directly from the repository with GitHub Pages, Netlify, or Vercel. The entry point is `index.html`.

## Data and customization

Edit the `events` array in `app.js` to add events or update event details. Registrations and favorites are stored in the visitor's browser using Local Storage; this demo does not send data to a server. Event photos are served by Unsplash and fonts by Google Fonts.

## Version control / submission

Initialize a Git repository, commit the project, push it to GitHub, and deploy the repository on GitHub Pages, Netlify, or Vercel. Add the repository and deployment URLs here when available.
