# Hospital Management System (HMS)

A web-based Hospital Management System designed to streamline healthcare operations, manage patient records, coordinate doctor appointments, and handle administrative workflows efficiently.

---

## 🚀 Features

### 👤 Admin Portal
* **Dashboard Management:** Overlook global statistics of the hospital system.
* **Doctor Management:** Add, remove, and manage medical staff profiles and specializations.
* **Patient & Appointment Records:** Track full user registrations and historical medical appointments.

### 🩺 Doctor Portal
* **Appointment Tracking:** View upcoming or scheduled patient visits.
* **Prescription Management:** Digitally prescribe medication and log treatment notes directly to patient charts.
* **Patient Search:** Search and reference registered clinic patient histories.

### 👥 Patient Portal
* **Appointment Booking:** Schedule visits with available doctors based on specialized departments.
* **Billing and Invoice View:** Access billing records, statements, and payment status histories.
* **Profile Management:** Update personal credentials and account settings securely.

---

## 📂 Repository Structure

The project separates frontend styling, assets, and backend PHP logical modules cleanly:

```text
├── css/                     # Custom supplemental styles
├── fonts/                   # Asset iconography and web fonts
├── images/                  # Graphical elements and user profile placeholders
├── js/                      # JavaScript logic for form validation and UX interactions
│
├── admin-panel.php          # Main control dashboard for system administrators
├── admin-panel1.php         # Secondary administration layout view
├── doctor-panel.php         # Entry workspace for medical staff 
├── doctor_login.php         # Authentication gateway for doctors
├── index.php                # Public landing page and primary login hub
├── index_admin.php          # Dedicated secure administrator login screen
│
├── addnew.php               # Interface to register new staff or entities
├── appsearch.php            # Query system for scheduling details
├── billing.php / billout.php# Ledger management and invoice generators
├── contact.php              # Public customer support and inquiry form
├── prescribe.php            # Core portal for writing patient prescriptions
├── reports.php              # Document generator for hospital metrics
│
├── store.sql                # Complete database schema structure and relational tables
├── composer.json            # PHP package dependencies configuration
└── htaccess                 # Apache server routing security configuration
