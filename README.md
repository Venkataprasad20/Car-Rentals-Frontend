🚗 Car Rentals – MERN Stack Application

A complete Car Rental Management System built with the MERN Stack (MongoDB, Express.js, React.js, Node.js) that enables customers to browse, book, and manage car rentals while providing administrators powerful tools to manage cars, users, and bookings.

This project demonstrates full-stack development skills, REST API design, database schema modeling, authentication/authorization, file uploads, and responsive UI development.

📌 Features
User Features

🔍 Search & Browse Cars – Filter by price, model, and availability.
📅 Car Booking – Choose pick-up & drop-off dates and confirm instantly.
📜 View Booking History – Track all past and current bookings.
👤 Secure Authentication – Register, log in, and manage personal details.

Admin Features

🚗 Car Management – Add, edit, or remove cars with details and images.
📦 Booking Management – Approve or reject bookings.
👥 User Management – Monitor and manage customer accounts.

🛠️ Tech Stack & Tools

Frontend
   .React.js – Component-based UI development.
   .Vite – Lightning-fast build tool for React.
   .Tailwind CSS – Utility-first CSS framework for responsive design.
   .React Router DOM – Client-side routing and protected routes.
   .Axios – API communication with backend.
   .React Hooks – State and side-effect management (useState, useEffect, useContext).

Backend
   .Node.js – JavaScript runtime for backend services.
   .Express.js – REST API development and routing.

MongoDB & Mongoose – NoSQL database and schema modeling.

Multer – File upload handling for car images and user profile pictures.

Bcrypt.js – Password hashing for secure storage.

JSON Web Token (JWT) – Authentication and authorization.

CORS – Cross-origin request handling.

Dotenv – Environment variable management.

Other Tools & Platforms

Postman – API testing and debugging.

Git & GitHub – Version control and project hosting.

Vercel – Frontend deployment.

Render – Backend deployment.

📂 Project Structure
Car-Rentals-Frontend/
│── src/
│   ├── components/       # Reusable UI components
│   ├── pages/            # Page-level components
│   ├── layouts/          # Layout wrappers (Auth, Dashboard)
│   ├── utils/            # API configs, helper functions
│   ├── App.jsx
│   └── main.jsx
│── public/
│── package.json

Car-Rentals-Backend/
│── controllers/          # Request handling logic
│── models/               # Mongoose schemas
│── routes/               # API routes
│── middlewares/          # Auth middleware, file uploads
│── uploads/              # Uploaded car images
│── server.js
│── package.json

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/yourusername/Car-Rentals.git

2️⃣ Backend Setup
cd Car-Rentals-Backend
npm install


Create .env in the backend root:

PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret


Run backend:

npm run dev

3️⃣ Frontend Setup
cd Car-Rentals-Frontend
npm install


Create .env in the frontend root:

VITE_API_BASE_URL=http://localhost:5000/api


Run frontend:

npm run dev

📸 Screenshots
Home Page	Car Details	Booking Page

	
	
🚀 Deployment

Frontend: [Live Demo Link]

Backend API: [API Endpoint Link]
