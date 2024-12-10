Wisdom Square - MERN Stack Web Application
Project Overview
Wisdom Square is a web application similar to Reddit that allows users to post questions, provide answers, vote on posts, and earn reputation points. It is built using the MERN stack (MongoDB, Express.js, React.js, Node.js) and aims to facilitate collaborative learning for educational institutions.

Features
User Registration and Login
Question Posting and Answering
Voting System for Questions, Answers, and Comments
Reputation Points System
User Profiles and Leaderboard
Report Generation and Activity Tracking
Technologies Used
Front-end: React.js, HTML, CSS
Back-end: Node.js, Express.js
Database: MongoDB
Authentication: JWT (JSON Web Token)
Hosting: Front-end (Netlify), Back-end (Heroku)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/wisdom-square.git
Navigate to the project directory:

bash
Copy code
cd wisdom-square
Install dependencies for both client and server:

bash
Copy code
cd client
npm install
cd ../server
npm install
Start the development server:

bash
Copy code
cd server
npm run dev
Usage
Visit http://localhost:3000/ to access the application.
Register or log in to your account.
Post questions, answer questions, and vote on posts.
View reputation points and track your progress on the leaderboard.
Project Structure
bash
Copy code
wisdom-square/
├── client/         # Frontend (React)
├── server/         # Backend (Node.js, Express)
├── config/         # Configuration files
├── models/         # Mongoose models
├── routes/         # API routes
├── controllers/    # Route controllers
└── README.md       # Project documentation
Contributing
Fork the repository.

Create a new branch:

bash
Copy code
git checkout -b feature/your-feature-name
Commit your changes:

bash
Copy code
git commit -m 'Add new feature'
Push the branch:

bash
Copy code
git push origin feature/your-feature-name
Open a pull request.

License
This project is licensed under the MIT License.
