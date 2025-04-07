📇 Comic-Themed Contact App
A fun, comic-styled Contact Management App that allows users to search, add, and update contacts with ease. Built using React for the frontend and Firebase for the backend.

✨ Features
🔍 Search contacts by name or email

➕ Add new contacts using a form modal

✏ Update existing contact details

☁ Firebase integration for real-time database operations

🎨 Comic-style UI for a playful user experience

🛠 Tech Stack
Frontend: React, Tailwind CSS (with Comic-theme styling)

Backend: Firebase (Realtime Database)

State Management: useState, useEffect

Form Handling: Formik + Yup with Modals

Notifications: React Toastify (comic styling enabled — improvements ongoing)

🚀 Getting Started
1. Clone the Repo
bash
Copy
Edit
git clone https://github.com/Akshatsingh1103/contact-app.git
cd contact-app
2. Install Dependencies
bash
Copy
Edit
npm install
3. Add Firebase Config
Create a .env file in the root directory and add your Firebase credentials:

env
Copy
Edit
REACT_APP_API_KEY=your_api_key
REACT_APP_AUTH_DOMAIN=your_project_id.firebaseapp.com
REACT_APP_DATABASE_URL=your_database_url
REACT_APP_PROJECT_ID=your_project_id
REACT_APP_STORAGE_BUCKET=your_project_id.appspot.com
REACT_APP_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_APP_ID=your_app_id
4. Start the App
bash
Copy
Edit
npm run dev
⚠ Known Issues
Toast notifications appear but don’t auto-close sometimes. Investigating potential style override issues or improper ToastContainer configs.

📷 Screenshots
(Optional section — Add screenshots of your app here using ![desc](path) syntax if needed)

📬 Contact
Feel free to contribute, raise issues, or get in touch via GitHub
