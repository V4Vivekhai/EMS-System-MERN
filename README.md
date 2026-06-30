Employee Management System (EMS) — MERN Stack

A full stack Employee Management System built with MongoDB, Express, React, and Node.js. This project covers everything you'd expect from a real-world HR tool — attendance tracking, leave management, payslips, and role-based access for Admins and Employees.

I built this as a complete, end-to-end full stack project, the kind of thing that works great as a portfolio piece or a final year college project. It's not just a CRUD app — it tries to mirror how an actual company's internal EMS tool would be structured and used.

🔗 Live Demo: coming soon
📂 Repo: EMS-System-MERN


✨ Features


Role-based authentication — separate Admin and Employee portals, each with their own dashboard and permissions
Employee Management — add, update, and manage employee records and departments
Attendance Management — track daily attendance for the whole team
Leave Management — employees can apply for leave, admins can approve/reject
Payslip Generation — generate and manage employee payslips
Secure Login System — JWT-based authentication with protected routes
Clean, responsive UI — built with React, designed to feel like a real internal tool rather than a generic admin panel



🛠️ Tech Stack

Frontend: React (Vite), Tailwind CSS
Backend: Node.js, Express.js
Database: MongoDB (Mongoose)
Auth: JWT-based authentication
Other: REST API architecture, role-based middleware




🚀 Getting Started

Prerequisites


Node.js (v18 or above recommended)
MongoDB (local or Atlas)
npm or yarn


1. Clone the repository

bashgit clone https://github.com/V4Vivekhai/EMS-System-MERN.git
cd EMS-System-MERN

2. Setup the Backend

cd backend
npm install

Create a .env file in the backend folder:

envPORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key

Run the backend:

npm run dev

3. Setup the Frontend

cd frontend
npm install
npm run dev

The app should now be running on http://localhost:5173 (frontend) and http://localhost:5000 (backend API).


📁 Project Structure

EMS-System-MERN/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   └── App.jsx
└── README.md


🗺️ Roadmap


 Email notifications for leave approval/rejection
 Payroll automation with scheduled jobs
 Analytics dashboard for admins
 Dark mode



🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the issues page if you'd like to contribute.


👤 Author

Vivek Khurana
Final Year CSE Student | MERN Stack Developer

If you found this project useful, consider giving it a ⭐ on GitHub — it helps a lot!


📄 License

This project is open source and available under the MIT License.
