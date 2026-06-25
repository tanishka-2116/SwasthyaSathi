# Frontend

This folder contains the frontend development of SwasthyaSathi.

Technology Stack:
- HTML5
- CSS3
- JavaScript
- Chart.js
- Glassmorphism UI Design

Responsibilities:
- User Interface Design
- Client-side Logic
- Interactive Health Dashboard
- Chart Visualizations
- Form Validation
- API Integration

File Structure:
frontend/
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
└── README.md

Pages Included:
- Home
- About Us
- Profile
- Health Check
- Wellness Score
- Assessment History
- Health Graph

Features:
- Glassmorphism UI Design
- Light & Dark Mode
- Responsive Layout
- Interactive Charts (Chart.js)
- Form Validation
- API Integration
- PDF Report Generation
- OCR Lab Report Upload

API Integration:
- User Login/Register → api.php?action=save-user
- Save Assessment → api.php?action=save-assessment
- Get History → api.php?action=get-assessments
- Delete Assessment → api.php?action=delete-assessment
- Calculate Risk → api.php?action=calculate-risk

Setup Instructions:
1. Place files in web server root
2. Ensure backend (api.php) is configured
3. Open index.html in browser
4. Frontend connects to backend API automatically

Dependencies:
- Chart.js (CDN)
- Google Fonts (Inter)
- PHPMailer (backend)

Browser Support:
- Chrome, Firefox, Edge, Safari (latest versions)

---

SwasthyaSathi — Preventive Healthcare Platform
