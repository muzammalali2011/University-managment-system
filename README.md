# University-managment-system
A comprehensive university management system built with PHP, MySQL, HTML, CSS, and JavaScript that handles student enrollments, course management, grading, and user administration.
**Features**
User Roles
Admin: Full system control
Professor: Manage courses and grades
Student: View courses and grades

**Core Modules**
Student enrollment system
Course management
Grade tracking and calculation
Department administration
User authentication

**Technology Stack**
Backend
PHP 7.4+
MySQL 8.0
PDO for database access

Frontend
HTML5
CSS3 (with responsive design)
JavaScript (vanilla)

**Development Tools**
XAMPP/WAMP for local development
VS Code
Git/GitHub

**Installation**
Prerequisites
Web server (Apache/Nginx)
PHP 7.4+
MySQL 8.0+
Composer (for optional dependencies)


Usage
Access the system at http://localhost/university-management-system

Login with default credentials:

Admin: admin/admin123

Professor: prof1/prof123

Student: student1/student123

**Project Structure**
university-management-system/
├── admin/               # Admin modules
├── includes/            # Core system files
│   ├── auth.php         # Authentication
│   ├── config.php       # Configuration
│   └── functions.php    # Helper functions
├── public/              # Public assets
│   ├── css/
│   ├── js/
│   └── images/
├── students/            # Student portal
├── db/                  # Database files
│   ├── schema.sql       # Database schema
│   └── sample-data.sql  # Sample data
├── .gitignore
├── LICENSE
└── README.md

**Contributing**
Fork the project
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request



