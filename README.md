# 📘 Student Records API

A RESTful API for managing student records using Node.js, Express, and PostgreSQL.
This project demonstrates full-stack development skills including CRUD operations, authentication, and data validation.

## 🚀 Features

• Create, Read, Update, and Delete (CRUD) student records

• Authentication & authorization (JWT-based)

• PostgreSQL database integration with Sequelize ORM

• Error handling & input validation

• RESTful API design with modular structure

## 🛠 Tech Stack

• Backend: Node.js, Express

• Database: PostgreSQL, Sequelize

• Authentication: JWT

• Tools: Git, Postman, Docker (optional)

## 📂 Project Structure
```
student-records-api/
│── src/
│   ├── routes/        # API routes
│   ├── controllers/   # Request handling logic
│   ├── models/        # Sequelize models
│   ├── middleware/    # Auth & error handling
│   └── config/        # Database & environment setup
│── .gitignore
│── package.json
│── README.md
```

---

## ⚙️ Installation
```bash
# Clone the repository
git clone https://github.com/your-username/student-records-api.git

# Navigate to project folder
cd student-records-api

# Install dependencies
npm install
```
## 🔑 Environment Setup

Create a .env file in the root directory:
```
PORT=5000
DB_HOST=localhost
DB_USER=postgres
DB_PASSWORD=yourpassword
DB_NAME=student_db
DB_PORT=5432
JWT_SECRET=your_jwt_secret
```
## ▶️ Running the Project
```
# Start development server
npm run dev

# Run in production
npm start
```
The API will be available at:
👉 http://localhost:5000/api/students

## 📌 API Endpoints

| Method | Endpoint           | Description              |
|--------|--------------------|--------------------------|
| GET    | /api/students      | Get all students         |
| GET    | /api/students/:id  | Get a single student     |
| POST   | /api/students      | Create a new student     |
| PUT    | /api/students/:id  | Update an existing student |
| DELETE | /api/students/:id  | Delete a student         |
## 🧪 Testing
```
# Run all tests
npm test
```
## 📊 Tech Stack
• Backend: Node.js, Express

• Database: PostgreSQL + Sequelize ORM

• Auth: JWT + Middleware

• Testing: Jest / Supertest

• Version Control: Git + GitHub


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

##👤 Author

Tien Le
📧 Email: [tienlext2001@gmail.com]
💻 GitHub: github.com/tle2209
