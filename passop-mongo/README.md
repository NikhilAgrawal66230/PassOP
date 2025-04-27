# PassOP – Password Manager

PassOP is a secure and user-friendly password manager built with React (Vite), Node.js/Express, and MongoDB. It allows users to safely store, manage, and retrieve passwords with modern UI features and robust backend security.

## Features

- Secure storage and management of passwords
- Add, edit, and delete password entries
- Password masking and visibility toggle
- Copy-to-clipboard functionality
- Responsive design with Tailwind CSS
- Real-time notifications with React Toastify
- RESTful API backend with MongoDB for persistent storage

## Tech Stack

- **Frontend:** React (Vite), Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

## Getting Started

### Prerequisites

- Node.js and npm
- MongoDB

### Setup & Running the Project

1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   cd passop-mongo
   ```

2. **Install frontend dependencies:**
   ```sh
   npm install
   ```

3. **Install backend dependencies:**
   ```sh
   cd backend
   npm install
   ```

4. **Configure environment variables:**
   - In `backend/.env`, set your MongoDB URI and database name:
     ```
     MONGO_URI=mongodb://localhost:27017
     DB_NAME=passop
     ```

5. **Start the backend server:**
   ```sh
   npm start
   ```

6. **Start the frontend development server (in a new terminal):**
   ```sh
   cd ..
   npm run dev
   ```

7. **Access the application:**
   - Open your browser and go to `http://localhost:5173` (or the port shown in your terminal).


