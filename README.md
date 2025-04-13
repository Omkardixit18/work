Grocery App – Omkar
A modern grocery store web application built with Next.js 13, Firebase Authentication, and Tailwind CSS. This project includes features such as user login, registration, password reset, and an auto-scrolling product showcase.

🌟 Features
🔐 User Authentication (Login, Register, Forgot Password)

🖼️ Auto-scrolling image slider for product showcase

🎨 Responsive UI with Tailwind CSS

⚙️ Firebase integration for authentication and backend services

🚀 Built with Next.js App Router (app/ directory)

🚀 Getting Started
Prerequisites
Node.js (v16 or higher)

npm or yarn

Firebase project setup

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Omkardixit18/work.git
cd work
Install dependencies:

bash
Copy
Edit
npm install
# or
yarn install
Configure Firebase:

Create a Firebase.js file in the root directory.

Initialize Firebase with your project's configuration:

javascript
Copy
Edit
// Firebase.js
import { initializeApp } from 'firebase/app';
import { getAuth } from 'firebase/auth';

const firebaseConfig = {
  apiKey: 'YOUR_API_KEY',
  authDomain: 'YOUR_AUTH_DOMAIN',
  projectId: 'YOUR_PROJECT_ID',
  storageBucket: 'YOUR_STORAGE_BUCKET',
  messagingSenderId: 'YOUR_MESSAGING_SENDER_ID',
  appId: 'YOUR_APP_ID',
};

const app = initializeApp(firebaseConfig);
export const auth = getAuth(app);
Run the development server:

bash
Copy
Edit
npm run dev
# or
yarn dev
Open http://localhost:3000 to view the application in your browser.

🗂️ Project Structure
pgsql
Copy
Edit
work/
├── app/
│   ├── login/
│   │   └── page.js
│   ├── register/
│   │   └── page.js
│   ├── forgot-password/
│   │   └── page.js
│   ├── dashboard/
│   │   └── page.js
│   └── components/
│       └── Slider.js
├── public/
├── styles/
│   └── globals.css
├── Firebase.js
├── package.json
└── README.md
🔧 Available Scripts
npm run dev – Start the development server

npm run build – Build the application for production

npm run start – Start the production server

📸 Screenshots
Include screenshots of your application here to showcase the UI and features.

🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

📄 License
This project is licensed under the MIT License.
