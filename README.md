Organ Donation System

A digital platform to bridge the gap between organ donors, recipients, and hospitals. This system aims to streamline the organ donation process, reduce waiting time, and save lives by efficiently managing donor registrations, recipient requests, and organ matching.

Features

- User Registration & Authentication – Separate portals for donors, recipients, and hospital administrators.
- Donor Management – Register as a donor, update health records, and manage consent.
- Recipient Management – Add recipients to the waiting list, specify required organ type, and track status.
- Organ Matching Algorithm – Match donors with recipients based on blood type, tissue compatibility, urgency, and location.
- Request & Allocation Logs – Transparent tracking of organ allocation with timestamps.
- Admin Dashboard – Monitor system activity, approve/deny requests, and generate reports.
- Notifications – Email/SMS alerts for successful matches and transplant coordination.

Tech Stack

Backend: Java (Spring Boot)
Frontend: React.js / HTML, CSS, JavaScript
Database: PostgreSQL / MySQL
Authentication: JWT / Spring Security
Hosting: AWS / Heroku / DigitalOcean


User Roles

1. Donor – Register, update medical info, view donation history.
2. Recipient – Register, request organs, check match status.
3. Hospital Admin – Verify donors, allocate organs, manage transplant records.
4. System Admin – Oversee platform, manage users, generate analytics.

Installation & Setup

Prerequisites
- Java 17 or higher
- Maven
- Node.js & npm
- PostgreSQL / MySQL
- Git


API Endpoints (Sample)

| Method | Endpoint                  | Description               |
|--------|---------------------------|---------------------------|
| POST   | /api/auth/register        | User registration         |
| POST   | /api/auth/login           | User login                |
| GET    | /api/donors               | List all donors           |
| POST   | /api/recipients/request   | Add recipient request     |
| GET    | /api/match/organ/{type}   | Find organ matches        |
| PUT    | /api/admin/approve/{id}   | Approve donation request  |


Contributing

Contributions are welcome! Please follow these steps:
1. Fork the project.
2. Create your feature branch (git checkout -b feature/amazing-feature).
3. Commit your changes (git commit -m 'Add some amazing feature').
4. Push to the branch (git push origin feature/amazing-feature).
5. Open a Pull Request.

Contact

Project Maintainer: Kartik Yadav Gurve - gurvekartik6@gmail.com
Project Link: https://github.com/gurvekartik6/Organ_Donation_Management_System.git

Disclaimer

This system is for educational/demonstration purposes only. Real-world organ donation must follow legal and medical regulations of the respective country/state.
