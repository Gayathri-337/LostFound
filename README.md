🐾 CampusTrack | Smart Campus Recovery System
CampusTrack is a sophisticated full-stack management system engineered to streamline the recovery of misplaced assets within a university environment. By utilizing intelligent matching and a dual-portal interface, it connects students who have lost items with those who have found them.

🚀 Key Features
🎓 Student Portal
Item Reporting: Quickly list found items with categories and campus zones.

Search & Claim: Search a real-time database of found items and submit ownership claims.

Live Messaging: Securely chat with founders to arrange item returns.

Personalized Dashboard: Dynamic greetings and status tracking for active claims.

🛡️ Admin Control Center
System Analytics: Visualized data trends using Chart.js, showing weekly activity and recovery rates.

Claim Management: Approve or reject ownership claims based on provided evidence.

Inventory Control: Full CRUD operations to manage the campus-wide lost and found database.

🛠️ Technical Stack
Frontend: HTML5, CSS3 (Glassmorphism UI),JavaScript (ES6+), Chart.js.

Backend: Java 17, Spring Boot 3, Spring Security (BCrypt Password Hashing).

Database: MySQL (Persistent storage for users, items, and claims).

Communication: RESTful API architecture with JSON data exchange.

📂 Project Structure
Plaintext

src/main/java/com/campus/connect/
├── config/        # Security and CORS configurations
├── controller/    # REST API Endpoints (Auth, Items, Admin)
├── dto/           # Data Transfer Objects for Analytics and Login
├── model/         # JPA Entities (User, Item, Claim)
├── repository/    # JPA Repositories for MySQL interaction
└── service/       # Business logic and password encryption
⚙️ Setup Instructions
1. Database Configuration
Create a MySQL database named campustrack_db.

Update src/main/resources/application.properties with your MySQL credentials:

Properties

spring.datasource.url=jdbc:mysql://localhost:3306/campustrack_db
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD
2. Running the Application
Clone the repository: git clone https://github.com/yourusername/campustrack.git

Open the project in IntelliJ IDEA or Eclipse.

Run the CampusTrackApplication.java file.

Access the landing page at http://localhost:8080/login.html.



© 2026 CampusTrack | Empowering Campus Connections ✅
