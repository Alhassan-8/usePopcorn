# 🍿 usePopcorn

A modern, responsive React application for movie enthusiasts to search, discover, and manage their movie watchlists with an intuitive rating system.

> **📚 Learning Project**: This application was built as part of Jonas Schmedtmann's ["The Ultimate React Course 2024"](https://www.udemy.com/course/the-ultimate-react-course/) on Udemy. It demonstrates modern React concepts including custom hooks, state management, API integration, and component composition.

![React](https://img.shields.io/badge/React-19.1.0-blue?logo=react)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?logo=javascript)
![CSS3](https://img.shields.io/badge/CSS3-Modern-blue?logo=css3)
![License](https://img.shields.io/badge/License-MIT-green)

## 📚 Learning Objectives

This project was developed as part of **Jonas Schmedtmann's "The Ultimate React Course 2024"** and demonstrates mastery of:

### React Fundamentals
- ⚛️ **Component Composition**: Building reusable, composable components
- 🎣 **Hooks Mastery**: Using useState, useEffect, useRef with best practices
- 🔄 **State Management**: Managing complex state across multiple components
- 🎯 **Event Handling**: Keyboard events, click handlers, and form interactions

### Advanced React Patterns
- 🛠️ **Custom Hooks**: Creating reusable logic with `useMovies`, `useLocalStorageState`, `useKey`
- 📡 **API Integration**: Fetching data from external APIs with proper error handling
- 💾 **Data Persistence**: Using localStorage for client-side data storage
- 🔍 **Search Implementation**: Real-time search with debouncing and request cancellation

### Performance & Best Practices
- ⚡ **Performance Optimization**: Preventing unnecessary re-renders
- 🧹 **Cleanup Functions**: Proper cleanup of side effects and event listeners
- 🎨 **Modern CSS**: CSS custom properties, responsive design, and dark theming
- 📝 **Code Organization**: Clean component architecture and separation of concerns

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

> **Note**: This is a learning project from Jonas Schmedtmann's React course. Feel free to clone and experiment!

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Basic understanding of React concepts

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

## 🤝 Contributing & Learning

This is a learning project, but contributions and improvements are welcome! If you're also taking the course or learning React:

### For Course Students
- Share your own implementations and variations
- Suggest improvements or additional features
- Help other students understand concepts

### For Contributors
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### 💡 Ideas for Extension
- Add movie recommendations
- Implement user authentication
- Add social features (sharing watchlists)
- Connect to additional movie APIs
- Add movie trailers integration

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [OMDB API](http://www.omdbapi.com/) for movie data
- [Create React App](https://create-react-app.dev/) for the initial setup
- React team for the amazing framework

---

**🎯 Built for Learning | Part of Jonas Schmedtmann's React Course**

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
