# 🎬 Movie Database

A React-based movie search application that allows users to search for movies and view detailed information using the OMDb API.

![React](https://img.shields.io/badge/React-19.2.3-61DAFB?logo=react)
![Axios](https://img.shields.io/badge/Axios-1.13.2-5A29E4)

## ✨ Features

- **Movie Search** - Search for any movie by title
- **Real-time Results** - Instant display of search results with movie posters
- **Movie Details Popup** - View detailed information including:
  - Title and release year
  - IMDb rating
  - Plot summary
  - Movie poster

## 🛠️ Tech Stack

- **React.js** - Frontend framework
- **Axios** - HTTP client for API requests
- **OMDb API** - Movie database API
- **CSS** - Styling

## 📦 Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/movie-database.git
   ```

2. Navigate to the project directory
   ```bash
   cd movie-database
   ```

3. Install dependencies
   ```bash
   npm install
   ```

4. Start the development server
   ```bash
   npm start
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## 🚀 Usage

1. Type a movie name in the search box
2. Press **Enter** to search
3. Click on any movie card to view more details
4. Click **Close** to dismiss the popup

## 📁 Project Structure

```
src/
├── components/
│   ├── Search.js      # Search input component
│   ├── Results.js     # Results container component
│   ├── Result.js      # Individual movie card component
│   └── Popup.js       # Movie details popup component
├── App.js             # Main application component
├── index.js           # Entry point
└── index.css          # Styles
```

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
