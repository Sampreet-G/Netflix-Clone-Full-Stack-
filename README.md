# Netflix Clone React App by Sampreet Ghosh

A full-featured Netflix clone built with React, Firebase, and Vite. This project replicates core Netflix functionalities including user authentication, movie browsing, and trailer playback with a sleek, modern UI.

## Features

- **User Authentication:** Sign up, login, and logout using Firebase Authentication.
- **Movie Browsing:** Fetches movies dynamically from The Movie Database (TMDb) API.
- **Video Player:** Play movie trailers with a custom video player component.
- **Responsive Design:** Mobile-friendly and adaptive layouts.
- **Fast Build:** Powered by Vite for fast development and optimized build.
- **Modern UI:** Clean and intuitive user interface styled with CSS.

## Technologies Used

- React (with hooks and context)
- Vite (build tool)
- Firebase (authentication and Firestore)
- TMDb API for movies and videos
- React Router for navigation
- React Toastify for notifications
- Custom CSS for styling

## Installation & Setup

1. **Clone the repository:**
git clone <repository-url>
cd netflix-clone-react


2. **Install dependencies:**
npm install


3. **Firebase Setup:**
- Create a Firebase project.
- Enable Email/Password Authentication.
- Add your Firebase config in `firebase.js`.

4. **Get TMDb API Key:**
- Sign up at [TMDb](https://www.themoviedb.org/) and get an API key.
- The key is used in API fetch headers (already included, but get your own for production).

5. **Start the development server:**
npm run dev


6. Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

## Project Structure

- `/src/components` - Reusable UI components (Navbar, TitleCards, Player, etc.)
- `/src/pages` - Main pages (Home, Login, Player)
- `/src/assets` - Images, icons, and cards data
- `/src/firebase.js` - Firebase initialization and auth functions
- `/src/App.jsx` - Root app component with routing
- `/vite.config.js` - Vite config file for React integration

## Usage

- Create an account or log in with email and password.
- Browse movies on the homepage.
- Click a movie to watch its trailer in the player page.
- Use navigation for seamless transitions.

## Known Issues & Improvements

- API key is publicly exposed in source — consider server-side proxy for production.
- Add pagination or infinite scroll for larger movie lists.
- Enhance error handling and loading states.
- Implement user profiles and favorites list.

## License

This project is for educational and demonstration purposes only.

---

Feel free to fork, customize, and improve this Netflix clone React app!

