# usePopcorn - Movie Search & Rating App

A modern, responsive React application for searching and rating movies. Built with React hooks, custom components, and a beautiful user interface.

## 🎬 Features

- **Movie Search**: Search through a curated collection of popular films
- **Movie Details**: View detailed information about each movie including plot, cast, and ratings
- **Star Rating System**: Rate movies on a 10-star scale
- **Watchlist Management**: Add movies to your watched list and track your ratings
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Local Storage**: Your watchlist and ratings are saved locally in your browser

## 🚀 Live Demo

Visit the live application: [https://kukushkindmi1riy.github.io/useFilms/](https://kukushkindmi1riy.github.io/useFilms/)

## 📱 Screenshots

- **Desktop View**: Two-column layout with search results and movie details
- **Mobile View**: Single-column responsive design optimized for touch
- **Tablet View**: Adaptive layout that works on all screen sizes

## 🛠 Technical Details

### Mock Data Implementation

Due to CORS (Cross-Origin Resource Sharing) restrictions when deploying to GitHub Pages, the application currently uses **mock data** instead of the OMDB API. This ensures the app works perfectly in production without any external API dependencies.

#### Available Movies

The app includes a curated selection of 10 popular films:

1. **Inception** (2010) - 8.8/10
2. **The Matrix** (1999) - 8.7/10
3. **Parasite** (2019) - 8.6/10
4. **The Dark Knight** (2008) - 9.0/10
5. **The Shawshank Redemption** (1994) - 9.3/10
6. **Pulp Fiction** (1994) - 8.9/10
7. **The Godfather** (1972) - 9.2/10
8. **Fight Club** (1999) - 8.8/10
9. **Forrest Gump** (1994) - 8.8/10
10. **Se7en** (1995) - 8.6/10

#### Search Functionality

You can search by:
- **Movie title** (e.g., "inception", "matrix", "dark")
- **Year** (e.g., "1994", "2010")
- **Partial matches** are supported

### Technologies Used

- **React 18** with functional components and hooks
- **Custom Hooks**: `useMovies`, `useLocalStorageState`, `useKey`
- **CSS3** with custom properties and responsive design
- **GitHub Pages** for deployment
- **Local Storage** for data persistence

### Key Components

- `App.js` - Main application component
- `StarRating.js` - Reusable star rating component
- `useMovies.js` - Custom hook for movie data management
- `useLocalStorageState.js` - Custom hook for localStorage
- `useKey.js` - Custom hook for keyboard event handling

## 🎯 How to Use

1. **Search Movies**: Type in the search bar (minimum 3 characters)
2. **View Details**: Click on any movie to see detailed information
3. **Rate Movies**: Use the star rating system to rate movies
4. **Add to Watchlist**: Click "Add to list" to save movies you've watched
5. **View Statistics**: See your average ratings and watchlist summary

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/KukushkinDmi1riy/useFilms.git
cd useFilms
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Building for Production

```bash
npm run build
```

### Deployment

The app is automatically deployed to GitHub Pages using the `gh-pages` package:

```bash
npm run deploy
```

## 🔧 Future Improvements

- [ ] Integrate with real OMDB API (when CORS issues are resolved)
- [ ] Add movie trailers and additional media
- [ ] Implement user accounts and cloud storage
- [ ] Add movie recommendations
- [ ] Include more detailed movie information
- [ ] Add sorting and filtering options

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Contact

- GitHub: [@KukushkinDmi1riy](https://github.com/KukushkinDmi1riy)
- Project Link: [https://github.com/KukushkinDmi1riy/useFilms](https://github.com/KukushkinDmi1riy/useFilms)

---

**Note**: This application uses mock data for demonstration purposes. In a production environment, you would typically integrate with a real movie database API like OMDB, TMDb, or similar services.
