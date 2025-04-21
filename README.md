# Ibni Sina Healthcare Information System

**Ibni Sina** is a full-stack healthcare management system that includes both a Django-based web application and a Python-based console interface. The system supports efficient management of patient and doctor records, appointments, and prescriptions with secure login and role-based access.

## Overview

The system was developed to assist Ibni Sina Healthcare Centre with digitalizing patient and doctor workflows. It offers two interfaces:

1. **Web Application (Django Framework)** – Designed with HTML/CSS templates and MySQL as the backend
2. **Console Application (Pure Python)** – Allows direct interaction with the database via command-line menus

## Features

### Common Features (Web + Console)
- User authentication for doctors and patients
- Appointment management (add, update, delete, view)
- Viewing patient and doctor records
- Prescription history lookup
- Role-based access control

### Web Application (Django)
- Admin panel for record management
- Views, Models, Forms, and Templates architecture
- Authentication via Django's built-in auth system
- Separate dashboards for doctors and patients
- Tested with 25 scenarios – 84% pass rate
- GitHub link: [Database-Design-and-development](https://github.com/Talal-Abuabdu/Database-Design-and-development)

### Console Application (Python)
- Command-line menu for appointments, patient/doctor lookup, and prescriptions
- Uses `mysql.connector` for database interaction
- Standalone script with login validation

## System Architecture

- **Backend**: MySQL 8.0.32
- **Web Backend**: Django Framework (Python 3.11.2)
- **Frontend**: HTML, CSS, Django Crispy Forms
- **Console App**: `DatabaseApplication.py` (uses direct SQL queries)
- **ORM**: Django's Object Relational Mapper
- **ER Diagram**: Included (see `ER diagram.mwb`)

## Known Issues

- Some UI design elements need enhancement (web app)
- Console login logic requires improvement (incorrect query format)
- No HTTPS applied on the web deployment yet
- No prescription data added to the database in the current version

## Future Enhancements

- Secure HTTPS deployment for user trust
- Improve UI/UX design (color, alignment, feedback)
- Add user-specific filtering (e.g., only view personal appointments)
- Enable prescription history functionality for patients
- Improve console login validation using correct SQL syntax
- Implement sign-out and account management features

## Development Methodology

- Agile development lifecycle with feedback loops
- Trello used for task management
- Version control via Git and GitHub
- Testing included both manual and automated methods
- Feedback from mentors and peers shaped iterative improvements

## Security & Access Control

- Role-based authentication (doctor/patient)
- Password validation and encryption via Django
- Console password check to be refined
- GDPR and privacy principles partially applied
- Plan to implement HTTPS and stronger user-level access restrictions

## Author

Talal AbuAbdo  
GitHub: [Talal-Abuabdu](https://github.com/Talal-Abuabdu)

## License

This project was developed for academic purposes under Unit 4 – Database Design and Development coursework. No commercial license is applied.
