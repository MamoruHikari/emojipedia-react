## Emojipedia

Access the live app here: **[Emojipedia](https://emojipedia-react-5od4.onrender.com)**

Note: It may take up to **60 seconds to load** as the app is hosted on Render's free tier.

---

### Description

**Emojipedia** is a React-based project developed to practice core React concepts, including component-based architecture and JSX syntax. The app showcases a list of popular emojis with their names and meanings, using a simple, yet effective, dynamic UI.

In this project, I focused on practicing React fundamentals, specifically working with functional components, passing props, and dynamically rendering content by mapping over arrays. It was a great opportunity to organize data in a modular way using external files like `emojipedia.js` to hold and export data. While the app doesn’t yet use state management, it provides a solid foundation for future improvements.

---

### Features

- Displays a list of emojis, their names, and meanings.
- Each emoji is represented with its corresponding image and a brief description of its meaning.
- The app's components are reusable and modular, promoting best practices for scalability in React development.

---

### Technologies Used

- **React.js**: A JavaScript library for building user interfaces.
- **JSX**: Syntax extension for JavaScript used with React.
- **CSS**: For styling and layout.
- **ES6+**: Modern JavaScript syntax and features.

---

### How It Works

- **App Component**: The main container of the app, which fetches and maps the `emojipedia` data to `Card` components.
- **Card Component**: Each card displays an emoji, its name, and meaning in a structured format.
- **emojipedia.js**: A simple JavaScript file containing an array of objects, where each object includes an emoji, its name, and a brief meaning.

---

### Installation

To get started with this project locally, clone the repository and follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/username/emojipedia-react.git
   ```

2. Navigate into the project directory:
   ```bash
   cd emojipedia-react
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open the app in your browser at [http://localhost:5173](http://localhost:5173).
