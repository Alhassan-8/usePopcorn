# 🍿 usePopcorn

A modern, responsive React application for movie enthusiasts to search, discover, and manage their movie watchlists with an intuitive rating system.

![React](https://img.shields.io/badge/React-19.1.0-blue?logo=react)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?logo=javascript)
![CSS3](https://img.shields.io/badge/CSS3-Modern-blue?logo=css3)
![License](https://img.shields.io/badge/License-MIT-green)

## ✨ Features

### 🎬 Movie Discovery

- **Real-time Search**: Search through thousands of movies using the OMDB API
- **Instant Results**: Get immediate feedback with loading states and error handling
- **Movie Details**: View comprehensive information including plot, cast, director, and ratings

### ⭐ Rating & Watchlist Management

- **Interactive Star Rating**: Custom-built star rating component with smooth animations
- **Personal Watchlist**: Add movies to your personal watched list with custom ratings
- **Local Storage**: Persistent data storage - your watchlist survives browser sessions
- **Statistics Dashboard**: Track your viewing habits with automatic calculations

### 🎯 User Experience

- **Keyboard Navigation**: Press Enter to focus search, Escape to close details
- **Responsive Design**: Beautiful UI that works on all device sizes
- **Dark Theme**: Modern dark theme with custom CSS variables
- **Smooth Animations**: Polished transitions and hover effects

## 🚀 Quick Start

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/usepopcorn.git
   cd usepopcorn
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🏗️ Project Structure

```
src/
├── App.js                 # Main application component
├── App.css               # Application styles
├── index.css             # Global styles and CSS variables
├── starRating.js         # Reusable star rating component
├── useMovies.js          # Custom hook for movie API calls
├── useLocalStorageState.js # Custom hook for localStorage
├── useKey.js             # Custom hook for keyboard events
└── index.js              # Application entry point
```

## 🔧 Custom Hooks

### `useMovies(query)`

Handles movie searching with automatic debouncing and error management.

**Features:**

- Automatic API calls when query changes
- Loading states
- Error handling
- Request cancellation

### `useLocalStorageState(initialState, key)`

Provides persistent state management using localStorage.

**Features:**

- Automatic synchronization with localStorage
- JSON serialization/deserialization
- Fallback to initial state

### `useKey(key, action)`

Manages keyboard event listeners for enhanced UX.

**Features:**

- Global keyboard shortcuts
- Automatic cleanup
- Customizable key bindings

## 🎨 Component Architecture

### Core Components

- **App**: Main application container with state management
- **NavBar**: Navigation with search and results counter
- **MovieList**: Displays search results with poster previews
- **MovieDetails**: Detailed movie view with rating functionality
- **WatchedSummary**: Statistics dashboard for watched movies

### Reusable Components

- **StarRating**: Configurable star rating with PropTypes validation
- **Box**: Collapsible container with toggle functionality
- **Loader**: Loading state indicator

```

## 🛠️ Available Scripts

| Command         | Description                                       |
| --------------- | ------------------------------------------------- |
| `npm start`     | Start development server at http://localhost:3000 |
| `npm test`      | Run test suite in interactive watch mode          |
| `npm run build` | Create optimized production build                 |
| `npm run eject` | Eject from Create React App (⚠️ irreversible)     |

## 🌟 API Integration

This application uses the [OMDB API](http://www.omdbapi.com/) for movie data:

- Search functionality
- Detailed movie information
- Poster images
- Ratings and metadata

## 🎨 Design System

### Color Palette

- **Primary**: `#6741d9` (Purple)
- **Background**: `#212529` (Dark gray)
- **Text**: `#dee2e6` (Light gray)
- **Accent**: `#fa5252` (Red for delete actions)

### Typography

- **Font Family**: System fonts for optimal performance
- **Font Sizes**: Responsive scale from 1.4rem to 3.2rem
- **Font Weights**: 400, 600, and bold variants

## 🚀 Performance Optimizations

- **Request Cancellation**: Prevents race conditions in API calls
- **Local Storage**: Reduces API calls for user data
- **CSS Variables**: Efficient styling with custom properties
- **Minimal Re-renders**: Optimized state management

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [OMDB API](http://www.omdbapi.com/) for movie data
- [Create React App](https://create-react-app.dev/) for the initial setup
- React team for the amazing framework

---

**Built with ❤️ and React**

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
```
