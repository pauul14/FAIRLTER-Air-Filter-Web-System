FAIRLTER — Air Filter Web System

Academic Group Project | Web Development | CCC 151

FAIRLTER is a web-based interface developed as part of an academic group project during our sophomore year in the BS Computer Applications program at Mindanao State University–Iligan Institute of Technology (MSU-IIT).

The project explores an air-filtration concept aimed at addressing air pollution through environmental monitoring and an interactive management interface.

Project Overview

The FAIRLTER web application provides a frontend for viewing and managing air-filtration units, represented as bins within the system.

The interface combines environmental monitoring concepts with web development technologies, providing users with tools to explore individual units, inspect sensor information, and interact with monitoring features.



Features

The repository contains code for the following features:

Interactive User Interface: Web-based layout with navigation, responsive styling, and interactive elements.

Bin Management: Interface for viewing, searching, adding, deleting, and recovering registered units.

Sensor Information: Displays sensor readings and air-quality status indicators.

Data Visualization: Chart.js integration for displaying sensor-reading history.

Location Mapping: Leaflet integration for displaying unit locations using demonstration coordinates.

Detailed Information Panels: Modal interfaces for viewing and managing individual units.

Contact Form: User interface for submitting inquiries.

These describe features represented in the source code and do not constitute independent validation of a deployed system.

Technologies Used

| Category | Technologies |
| --- | --- |
| Frontend | HTML5, CSS3, JavaScript |
| Backend | PHP |
| Database | MySQL |
| Data Visualization | Chart.js |
| Mapping | Leaflet |
| Development | Web Development, Responsive UI Design |

I participated as a frontend developer in this collaborative academic project.

My work focused on the frontend development of the web application as part of the development team.

This project provided practical experience in web interface development, working with frontend technologies, and collaborating with other developers on a shared system.

Repository Structure

```text
FAIRLTER-Air-Filter-Web-System/
├── login.html        # Main web interface
├── style.css         # Frontend styling
├── script.js         # Client-side application logic
├── index.php         # PHP API endpoints
├── db_connect.php    # Database connection
├── failter.png       # Project branding
├── prototype.png     # Concept prototype image
├── homepage.mp4      # Homepage media
└── README.md         # Project documentation
```

Running the Project

The repository preserves the academic project's source files but is not currently documented as a fully deployable application.

The PHP backend uses a MySQL database named fairlter_db. The original database schema is not included in this repository.

The frontend currently references api/index.php, while the supplied PHP endpoint is located at the repository root. This path must be reconciled for API requests to function.

A local PHP/MySQL environment, the appropriate database structure, and development configuration are required before the complete system can be tested.

The included map coordinates are demonstration data. The repository does not independently establish that the application is connected to live physical air-quality sensors.

FAIRLTER was developed collaboratively as an academic group project.

My contribution was in frontend development. Other parts of the application were developed as part of the group's collective work.
