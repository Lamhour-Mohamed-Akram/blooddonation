# 🩸 Blood Donation Management System

A full-stack web application for blood donation management built with Java EE, Servlets, JSP and MySQL.

## 📋 Description

This project was developed during a 4-month internship at Ben M'sik Faculty of Sciences, Casablanca. It provides a complete blood donation management system for:

- **Donors** - Register, manage donations, track history
- **Beneficiaries** - Request blood donations
- **Experts** - Manage and validate requests
- **Administrators** - System management and user accounts

## 🛠️ Tech Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Apache Tomcat](https://img.shields.io/badge/Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

## 📁 Project Structure

```
├── src/                    # Java source files (Servlets, Models, DAO)
├── WebContent/             # JSP pages and web resources
├── build/                  # Compiled classes
├── appblooddonation.sql    # Database schema
├── Rapport_Final.docx      # Final project report
└── Blood Donation Final.pptx # Presentation
```

## 🚀 Getting Started

1. Import project into Eclipse (Java EE)
2. Set up MySQL database:
```bash
mysql -u root -p < appblooddonation.sql
```
3. Configure database connection in your DAO classes
4. Deploy to Apache Tomcat 8+
5. Access at `http://localhost:8080/blooddonation`

## 🔗 Related Project

Frontend design: [blood-donation](https://github.com/Lamhour-Mohamed-Akram/blood-donation) (HTML/CSS/Bootstrap)

## 📊 Features

- User authentication & authorization
- Blood type compatibility matching
- Donation request management
- Email notifications
- Admin dashboard

## 👤 Author

**Mohamed-Akram Lamhour**
- GitHub: [@Lamhour-Mohamed-Akram](https://github.com/Lamhour-Mohamed-Akram)
- LinkedIn: [ak2lamhour](https://linkedin.com/in/ak2lamhour)
