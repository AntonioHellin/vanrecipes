# vanrecipes

A modern vanilla JavaScript recipe discovery and bookmarking application featuring custom recipe creation, serving adjustments, and real-time search.

## Project Overview

`vanrecipes` is built using ES6+ JavaScript following the Model-View-Controller (MVC) architectural pattern, bundled with Parcel. It connects to the Forkify Recipe API to search across thousands of recipes, adjust ingredient quantities dynamically based on guest servings, and store bookmarked recipes in browser local storage.

## Features

- **Recipe Search & Pagination**: Search through over 1,000,000 recipes with paginated results.
- **Dynamic Servings Adjustment**: Automatically recalculates ingredient quantities when increasing or decreasing servings.
- **Recipe Bookmarking**: Persists favorite recipes locally across browser sessions.
- **Custom Recipe Upload**: Form interface allowing users to submit and view their own culinary creations.

## Prerequisites

- [Node.js](https://nodejs.org/) (version 16.x, 18.x, or later)
- [npm](https://www.npmjs.com/) (version 8.x or later)

## Installation/Build

1. Clone the repository and navigate to the project directory:
   ```bash
   git clone https://github.com/AntonioHellin/vanrecipes.git
   cd vanrecipes
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:
   ```bash
   cp .env.example .env
   ```
   Add your Forkify API key to `.env` if uploading custom recipes.

4. Build for production:
   ```bash
   npm run build
   ```

## Usage

Start the local Parcel development server:
```bash
npm start
```
The browser will automatically open at `http://localhost:1234`.

## License

This project is licensed under the ISC License.
