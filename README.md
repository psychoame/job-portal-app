# 🚀 GETJOBS.COM - Job Portal Application

A modern job portal application built with JSP and HTML/CSS/JavaScript.

## 🌟 Features

- **Modern UI/UX**: Beautiful, responsive design
- **Job Categories**: Browse jobs by industry
- **User Authentication**: Separate login for applicants and employers
- **Job Posting**: Employers can post job openings
- **Job Search**: Applicants can search and apply for jobs
- **Interview Scheduling**: Built-in interview management system

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: JSP (Java Server Pages)
- **Database**: MySQL
- **Server**: Apache Tomcat

## 🚀 Quick Start

### Option 1: GitHub Pages (Demo Version)
1. Fork this repository
2. Go to Settings > Pages
3. Select source as "Deploy from a branch"
4. Choose main branch
5. Your site will be live at: `https://yourusername.github.io/repository-name`

### Option 2: Local Development
1. Install Java JDK 8+
2. Install Apache Tomcat 9+
3. Set up MySQL database
4. Deploy to Tomcat server

## 📁 Project Structure

```
├── index.html              # Main homepage (GitHub Pages compatible)
├── src/main/webapp/        # JSP application files
│   ├── home1.jsp          # Original homepage
│   ├── login_a.jsp        # Applicant login
│   ├── login_e.jsp        # Employer login
│   ├── app_home.jsp       # Applicant dashboard
│   ├── emp_home.jsp       # Employer dashboard
│   ├── 1.jsp             # Registration page
│   └── WEB-INF/
│       └── web.xml        # Web configuration
├── pom.xml                # Maven configuration
└── README.md              # This file
```

## 🎯 Demo Features

- **Interactive UI**: Hover effects and animations
- **Responsive Design**: Works on all devices
- **Category Browsing**: Click job categories to see details
- **Login Simulation**: Demo login functionality

## 🔧 Database Setup

Create these tables in MySQL:

```sql
-- Applicants table
CREATE TABLE applicant (
    first_name VARCHAR(50),
    last_name VARCHAR(50),
    gender VARCHAR(10),
    username VARCHAR(50) PRIMARY KEY,
    password VARCHAR(50),
    email VARCHAR(100)
);

-- Employers table
CREATE TABLE employer (
    emp_name VARCHAR(50) PRIMARY KEY,
    password VARCHAR(50),
    web_address VARCHAR(100)
);

-- Jobs table
CREATE TABLE job (
    company VARCHAR(50),
    web_address VARCHAR(100),
    vacancies VARCHAR(10),
    salary VARCHAR(20),
    job_desc VARCHAR(50),
    location VARCHAR(50),
    sel_post VARCHAR(50),
    interview_date VARCHAR(20),
    interview_time VARCHAR(20),
    interview_place VARCHAR(100)
);

-- Interviews table
CREATE TABLE interview (
    can_uname VARCHAR(50),
    com_name VARCHAR(50),
    interview_date VARCHAR(20),
    interview_time VARCHAR(20),
    interview_place VARCHAR(100)
);
```

## 🌐 Live Demo

Visit the live demo: [Your GitHub Pages URL]

## 📱 Screenshots

- Modern homepage with job categories
- Responsive design for mobile devices
- Interactive login buttons
- Professional job portal interface

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

Created with ❤️ for job seekers and employers worldwide.

---

**GETJOBS.COM** - Connecting talent with opportunity! 🎯 