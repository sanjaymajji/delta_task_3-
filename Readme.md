

<h1>Quiz Blitz</h1>

A feature-rich Quiz application built using the **MERN stack**, offering a user-friendly interface and robust security mechanisms. The app enables users to create, share, and play quizzes, making it an engaging platform for learning and fun.

---

## **Features**
- **User Profiles**: Create and manage personalized profiles.
- **Create Quizzes**: Users can design and share custom quizzes.
- **Play Quizzes**: Access and participate in quizzes created by others.
- **Secure Authentication**: 
  - **JWT Tokens**: Ensure secure logins and token-based authentication.
  - **Cookies**: Manage user sessions effectively.
- **Database**: User and quiz data is securely stored in **MongoDB**.

---

## **Technologies Used**

### **Frontend**
- **React.js**: Provides an intuitive and dynamic user interface.
  
### **Backend**
- **Node.js**: Manages server-side logic and API endpoints.
- **Express.js**: Handles routing and middleware efficiently.

### **Database**
- **MongoDB**: A NoSQL database for secure and scalable data storage.

### **Authentication**
- **JWT**: Ensures token-based secure login functionality.
- **Cookies**: Manage sessions for a seamless user experience.

---

## **Installation and Setup**

### Prerequisites
- **Node.js** installed ([Download Node.js](https://nodejs.org/)).
- **MongoDB** installed locally or use a cloud instance ([MongoDB Atlas](https://www.mongodb.com/cloud/atlas)).

### Steps
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd quiz-app
   ```
2. Install dependencies:
   ```bash
   # For backend
   cd backend
   npm install

   # For frontend
   cd ../frontend
   npm install
   ```
3. Configure Environment Variables:
   - Create a `.env` file in the `backend` directory and add:
     ```env
     MONGO_URI=<your_mongo_db_connection_string>
     JWT_SECRET=<your_jwt_secret>
     PORT=5000
     ```
4. Run the Application:
   - Start the backend server:
     ```bash
     cd backend
     npm start
     ```
   - Start the frontend:
     ```bash
     cd ../frontend
     npm start
     ```
5. Access the app at `http://localhost:3000`.

---

## **Project Architecture**
- **Frontend**: Handles the UI and communicates with backend APIs.
- **Backend**: Provides RESTful API endpoints for authentication, quiz creation, and user management.
- **Database**: Stores user profiles, quizzes, and results in a structured and secure format.

---

## **Key Highlights**
- **Responsive Design**: Optimized for devices of all sizes.
- **Secure Authentication**: Combines JWT and cookies for a robust session management system.
- **Scalability**: MongoDB ensures the app can handle a growing number of users and quizzes.

---

## **Future Enhancements**
- Add leaderboards to track top-performing users.
- Implement real-time quiz play with WebSocket or Socket.IO.
- Provide detailed quiz analytics and user progress tracking.
- Enable social media integration for easy sharing of quizzes.

---

