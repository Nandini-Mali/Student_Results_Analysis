🎓 ResultSync – Student Results Analysis

ResultSync is a web-based student result management system designed to simplify academic result management and provide separate dashboards for students and faculty.

✨ Features

- 👨‍🏫 Faculty Dashboard – Faculty-side interface for managing student results.
- 🎓 Student Dashboard – Students can access their academic information and results.
- 🔐 Login System – Dedicated login interface.
- 🗄️ Database Integration – Stores and manages data using MySQL.
- 📄 File Processing – Includes support for PDF and Excel file processing.

🛠️ Tech Stack

Frontend: React.js, Vite, Tailwind CSS
Backend: Java, Spring Boot, Spring Data JPA
Database: MySQL
Tools & Libraries: Maven, Apache PDFBox, Apache POI

🚀 Getting Started

Prerequisites

- Node.js and npm
- Java 17+
- MySQL
- Maven (or the included Maven Wrapper)

1. Clone the Repository

git clone https://github.com/Nandini-Mali/Student_Results_Analysis.git
cd Student_Results_Analysis

2. Run the Frontend

cd resultsync/Frontend
npm install
npm run dev

3. Run the Backend

Open another terminal:

cd resultsync/Backend/resultsync-backend

Configure your MySQL database connection in the Spring Boot application settings, then run:

./mvnw spring-boot:run

On Windows, use "mvnw.cmd spring-boot:run".

🎯 Objective

To provide a centralized platform for managing student results and making academic information more accessible to students and faculty.

👩‍💻 Author

Nandini Mali

---

⭐ If you find this project useful, consider giving the repository a star!
