# Amitflix

A Netflix-style movie browsing web app that uses **TMDB** and **OMDb** to help you discover trending titles, search movies/TV shows, and view rich title details.

## Features
- Browse trending/popular titles (TMDB)
- Search movies & TV shows
- Detailed title view (poster, overview/plot, ratings, release info, etc.)
- Responsive UI (mobile + desktop)

## APIs Used
- **TMDB (The Movie Database)** — trending/popular lists, discovery, posters, metadata
- **OMDb (Open Movie Database)** — extra metadata (IMDb data, additional ratings, plot, etc.)

## Tech Stack
- Frontend: React
- API calls: Fetch/Axios
- Styling: CSS / Tailwind / Bootstrap

## Getting Started

### 1) Clone the repository
```bash
git clone https://github.com/localhostamit/Amitflix.git
cd Amitflix
```

### 2) Install dependencies
```bash
npm install
```

### 3) Configure environment variables
Create a `.env` file in the project root.

#### If you're using **Vite**
```env
VITE_TMDB_API_KEY=your_tmdb_api_key
VITE_OMDB_API_KEY=your_omdb_api_key
```

#### If you're using **Create React App (CRA)**
```env
REACT_APP_TMDB_API_KEY=your_tmdb_api_key
REACT_APP_OMDB_API_KEY=your_omdb_api_key
```

Notes:
- Do **not** commit `.env` files.
- You can get keys from TMDB and OMDb official sites.

### 4) Run locally

#### Vite
```bash
npm run dev
```
Open: `http://localhost:5173`

#### CRA
```bash
npm start
```
Open: `http://localhost:3000`

## Build for Production
```bash
npm run build
```

## Deployment
You can deploy on Vercel / Netlify / Render / GitHub Pages (depending on your setup).

## Roadmap / Ideas
- Watchlist / Favorites
- Trailer playback (YouTube)
- Filters (genre, year, language)
- Pagination + infinite scroll
- User auth + profiles
- Dark mode

## Contributing
1. Fork the repo
2. Create a branch: `git checkout -b feature/my-feature`
3. Commit changes
4. Push and open a PR

## License
 MIT

## Author
**Amit**  
GitHub: https://github.com/localhostamit
