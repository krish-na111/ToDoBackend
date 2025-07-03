# MERN To-do-App
A full-stack ToDo application with user authentication, task management, and filtering options.
```md
#backend
This is the backend server for the MERN ToDo application. It handles user authentication and task management.

## Project Description
The backend handles:
- Secure user authentication using JWT and bcrypt
- Task creation, retrieval, update, and deletion
- Filtering tasks by `status` (Pending/Completed) and `priority` (Low/Medium/High)
- Ensures data access control by associating tasks with the authenticated user

---
## Technologies Used

- Node.js
- Express.js
- MongoDB (via Mongoose)
- JWT (JSON Web Token)
- bcrypt.js (for password hashing)
- CORS

---

## Setup instructions
### 1.clone the repository
```bash
git clone https://github.com/yourusername/todoapp-backend.git
cd todoapp-backend
### 2. Install dependencies
npm install
### 3. configure environment variables
PORT=8080
MONGOURL=mongodb_connection_uri
### 4. Run the server
node index.js



