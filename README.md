# 🏥 Ni-Rog Clinic

A comprehensive **Clinic Management System** built to streamline and automate patient registration, appointment booking, and clinic administration for hospitals, clinics, and dispensaries.

---

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [System Modules](#system-modules)
- [System Design](#system-design)
- [Getting Started](#getting-started)
- [Testing](#testing)
- [Limitations](#limitations)
- [Future Enhancements](#future-enhancements)
- [References](#references)
- [Author](#author)

---

## About the Project

Ni-Rog Clinic replaces manual, paper-based record keeping in clinics with a secure, web-based system. It handles patient registration, doctor and staff management, appointment scheduling, and billing — all accessible through role-based logins for **Admin**, **Doctor**, and **Patient** users.

The system assigns a unique ID to every patient, keeps records searchable and centralized, and lets patients book appointments that doctors can approve or deny based on availability.

## Features

- 🔐 Secure login and registration for Admin, Doctors, and Patients
- 🧑‍⚕️ Doctor and staff registration/management by Admin
- 📅 Appointment booking with doctor and time-slot selection
- ✅ Appointment approval/denial workflow for doctors
- 📖 Patient history tracking
- 🧾 Bill history and viewing
- 🖥️ Admin dashboard for managing the clinic end-to-end
- 💻 Responsive, user-friendly interface

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript, Bootstrap |
| Backend | C#, ASP.NET |
| Database | MS SQL Server |
| IDE / Tools | Visual Studio Code, SQL Server Management Studio |

## System Modules

The application is built around three core modules:

1. **Patient Module** — registration, appointment booking, viewing prescriptions/history, bill payment
2. **Admin Module** — manage doctors, staff, and overall clinic operations
3. **Doctor Module** — view/approve appointments, access patient history

## System Design

The project follows a structured design process, including:

- Entity-Relationship (ER) Diagram
- Data Flow Diagrams (DFD) — Level 1 & Level 2 (Sign-up, Appointment, Login)
- Database Design
- Use Case Diagram
- Activity Diagram

*(Diagrams are available in the original project report.)*

Development followed an **Incremental Model**: requirements were defined early, but features were designed, built, tested, and refined in successive increments based on user feedback.

## Getting Started

### Prerequisites

- Visual Studio 2012 or later
- SQL Server 2014 (or later) Management Studio
- Any modern web browser (Chrome, Firefox, Edge)
- Windows 10 or later recommended

### Installation

```bash
# Clone the repository
git clone https://github.com/Shreyjeetsinh/ni-rog-clinic.git

# Open the solution in Visual Studio
cd ni-rog-clinic
```

1. Open the `.sln` file in Visual Studio.
2. Restore/attach the SQL Server database using the provided schema.
3. Update the connection string in `Web.config` to point to your local SQL Server instance.
4. Build and run the project (`F5`) — it will launch in your default browser via IIS Express.

## Testing

The system was tested using unit and system-level test cases, covering:

| Test Case | Actors | Description |
|---|---|---|
| Login | Patient, Doctor, Admin | Validates user credentials and redirects to the correct dashboard |
| Appointment Booking | Patient, Doctor | Patient books a slot; doctor approves/denies the request |
| Add Doctor & Staff | Staff | Admin adds, updates, or removes doctor/staff records |

## Limitations

- Cannot handle high traffic volumes (no API layer yet)
- No automatic database backup
- Payment module not yet implemented

## Future Enhancements

- 💳 Integrated payment gateway (debit/credit card, net banking)
- 💾 Automatic database backup
- 🔑 OTP verification for users
- ⚡ API integration to support higher traffic loads

## References

- [W3Schools](https://www.w3schools.com/)
- [TutorialsPoint](https://www.tutorialspoint.com/index.html)
- [JavaTpoint](https://www.javatpoint.com/)
- [GeeksforGeeks](https://www.geeksforgeeks.org/)
- [Microsoft Learn – ASP.NET](https://learn.microsoft.com/en-us/aspnet/tutorials)
- [Bootstrap](https://www.getbootstrap.com)

## Author

**Shreyjeetsinh Dodiya**

