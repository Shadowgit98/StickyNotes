Sticky Note Web App Overview: This is a simple, yet powerful sticky note web application that allows users to create, edit, and manage notes efficiently. The application is connected to a backend powered by Appwrite, which handles the data storage, authentication, and real-time features.

Features Create Notes: Add new sticky notes with ease. Edit Notes: Modify existing notes. Delete Notes: Remove notes that are no longer needed. Change Colors: Choose your favourite colors. Real-Time Updates: See updates in real-time across all connected devices. Authentication: Secure login and registration powered by Appwrite. Installation Clone the Repository

bash Copy code :
- git clone https://github.com/Shadowgit98/StickyNotes.git
- cd sticky-note-app
- Install Dependencies

Features
- Drag and Drop notes anywhere on screen
- Save note data, position and color in database
- Change note color at anytime
- Autogrow note size as data is input
- Autosave notes as you add data.

bash

npm install Set Up Appwrite and configure its URI from .env.sample to .env

Ensure you have an Appwrite instance running. Configure your Appwrite project and update the .env file with your Appwrite credentials. Run the Application

bash

npm start Technologies Used Frontend: HTML, CSS, JavaScript, React JS with vite Backend: Appwrite Other Tools: npm, Webpack, etc. Contributing Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

License This project is licensed under the MIT License
