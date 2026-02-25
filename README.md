# Pharmacy Management System (PMS)

A Java-based desktop application built to simulate the operations of a real-world pharmacy. Developed as a team project at the **University of Arizona** following a defined System ConOps and Requirements specification, using **Agile Scrum** across the full Software Development Lifecycle (SDLC).

---

## 📋 Overview

The PMS is designed to streamline and automate core pharmacy operations including prescription processing, inventory management, patient records, billing, and reporting. The system enforces role-based access control, ensuring that only authorized personnel can perform sensitive actions.

---

## ✨ Features

- **Role-Based Access Control** — Supports four user roles: Pharmacy Manager, Pharmacist, Pharmacy Technician, and Cashier, each with distinct permissions
- **Prescription Management** — Enter, validate, fill, and track prescriptions with full activity logging
- **Inventory Control** — Real-time stock monitoring with low-stock and expiration alerts
- **Patient Management** — Create and manage patient profiles including medication history and insurance info
- **Billing & Sales** — Process prescription and non-prescription purchases with receipt generation and multiple payment methods
- **Reporting & Analytics** — Generate financial summaries, inventory reports, compliance reports, and prescription refill reports
- **Notification System** — Alerts for low stock, expiring medications, and prescription pickup

---

## 🛠️ Tech Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Swing](https://img.shields.io/badge/Java_Swing-GUI-007396?style=for-the-badge&logo=java&logoColor=white)

- **Language:** Java
- **UI Framework:** Java Swing
- **Architecture:** Client-server, MVC pattern
- **Development:** IntelliJ IDEA, VS Code, Git

---

## 📁 Project Structure

```
Pharmacy Management System/
├── Data/               # Data models (Drug, Patient, Prescription, User)
├── PharmacyReports/    # Report generation logic
├── UI/                 # All Swing UI screens and panels
└── Utils/              # Shared UI builder utilities
```

---

## 🖥️ Key Screens

- `LoginUI` — Secure login with lockout after 5 failed attempts
- `DashboardUI` — Central navigation hub for all user roles
- `PrescriptionEntryUI` — Enter and validate new prescriptions
- `InventorySearchUI` — Search and manage drug inventory
- `PatientEntryUI` / `PatientSearchUI` — Manage patient records
- `NotificationUI` — View system alerts and notifications
- Multiple report screens for financial, inventory, and compliance data

---

## 👥 Team

Developed by a team of 4 Software Engineering students at the University of Arizona as part of the SDLC coursework (Fall 2024).

---

## 📄 License

This project was developed for academic purposes at the University of Arizona. All rights reserved.
