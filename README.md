# Netflix Clone

A responsive Netflix clone built with React and Vite.  
Features user authentication (Firebase), movie browsing, and a modern UI inspired by Netflix.

## Features

- User authentication (Sign Up, Sign In, Sign Out) using Firebase
- Browse movies, TV shows, and popular content
- Responsive navbar with scroll effect
- Profile dropdown and notifications
- Toast notifications for feedback
- Modern Netflix-like design

## Tech Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Firebase Authentication & Firestore](https://firebase.google.com/)
- [React Router](https://reactrouter.com/)
- [React Toastify](https://fkhadra.github.io/react-toastify/)
- CSS

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/netflixclone.git
   cd netflixclone
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up Firebase:**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Authentication (Email/Password)
   - Replace the config in `src/firebase.js` with your Firebase credentials

4. **Run the app:**
   ```bash
   npm run dev
   ```

5. **Open in browser:**
   - Visit [http://localhost:5173](http://localhost:5173)

## Folder Structure

```
src/
  assets/         # Images and icons
  components/     # Reusable UI components (Navbar, etc.)
  pages/          # Main pages (Home, Login, Player)
  firebase.js     # Firebase configuration and auth functions
  App.jsx         # Main app component
```

## Credits

- UI inspired by [Netflix](https://www.netflix.com/)
- Built by [Your Name]

## License

This project is for educational purposes only.
