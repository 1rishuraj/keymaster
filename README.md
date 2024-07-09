# KeyMaster 🗝

**KeyMaster** is a secure password manager built with the MERN stack, featuring a React frontend and an Express.js backend, with MongoDB handling CRUD operations. The application allows the user to save, update, and delete passwords, ensuring secure storage and easy access.

![keymaster](https://github.com/1rishuraj/keymaster/assets/49861230/12b63942-0135-4c7f-9b93-5c568e69db7c)


## Features

- **Password Management**: Save, edit, and delete your passwords with ease.
- **Copy to Clipboard**: Quickly copy your saved passwords with a single click.
- **Secure Viewing**: Toggle between visible and hidden password states.
- **Responsive Design**: Mobile-friendly and intuitive user interface.
- **Password Suggestion AI-Bot**: Get new password suggestions via an AI-integrated chatbot.
- **Persistent Storage**: Passwords are stored in MongoDB, ensuring data persists across sessions.
- **Deployed on Vercel**: The application is hosted online.

## Important Note

This project is designed for personal use and all passwords are stored in a single MongoDB database. This means that the application is intended for use by a single user, whose database credentials are provided.

### Deploy Your Own Instance

To use KeyMaster for your own purposes, you can deploy the codebase and provide your own MongoDB database URL as an environment variable. 

## Usage

- **Save Password**: Enter the website URL, username, and password, then click the "Save" button.
- **Copy Password**: Click the copy icon next to a saved password to copy it to your clipboard.
- **Edit Password**: Click the edit icon next to a saved password to update it.
- **Delete Password**: Click the delete icon next to a saved password to remove it from the database.
- **Show/Hide Password**: Click the eye icon to toggle password visibility.
- **AI Chatbot**: Click the chatbot popup to ask for password suggestions.

## Code Overview

### Frontend

The frontend is built using React with functional components and hooks for state management.

- **Navbar Component**: Provides a navigation bar with a logo and a GitHub link.
- **Manager Component**: Handles form input, password visibility toggling, and CRUD operations.
- **Footer Component**: Displays the footer with a logo and creator's name.
- **Toastify**: Provides toast notifications for user actions.
- **UUID**: Generates unique IDs for each saved password.
- **HTML Component**: Embeds the AI chatbot to serve password suggestion requests.


### Backend

The backend is powered by Express.js, handling API requests and interacting with MongoDB.

- **Get Passwords**: Fetches all saved passwords from the database.
- **Save/Update Password**: Adds a new password to the database or edit the existing ones. 
- **Delete Password**: Removes a password from the database by ID.

## Demo

Check out the demo [here](https://drive.google.com/file/d/1MbY5o0BKQtFw-fDGvPvuZKlO0NiexT3j/view).

## Contributing

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature/your-feature-name
    ```
3. Commit your changes:
    ```sh
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature/your-feature-name
    ```
5. Open a pull request.

## Acknowledgments

- **React Toastify** for notifications
- **UUID** for unique ID generation
- **Lordicon** for beautiful icons
- **Vercel** for hosting

---

Made with 💖 by Rishu Raj (https://github.com/1rishuraj)
