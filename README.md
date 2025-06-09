## Nub Healthcare System
<br>
# Overview
The Nub Healthcare System is a console-based application written in C, developed entirely by me to manage healthcare operations for a hospital or clinic. It provides a user-friendly system to handle patient records, employee details, appointment scheduling, pharmacy inventory, pathology tests, blood bank operations, and emergency contact information. The system supports multiple user roles (Admin, Doctor, Nurse, Pharmacist, Pathologist) with specific functionalities to streamline healthcare tasks.
<br>
# Features
Patient Management: Add, view, search, and remove patient records with details like name, ID, medical history, and vitals.
Employee Management: Manage employee records, including doctors and nurses, with options to add, view, search, and remove.
Appointment Scheduling: Schedule, view, search, and cancel appointments, with checks for available time slots and alternative suggestions.
Clinical Management: Record patient vitals (BMI, blood pressure), issue prescriptions, and view medical history.
Pharmacy Management: Manage medicine inventory, search medicines, and generate bills for medications.
Pathology Management: Add, search, and bill pathology tests.
Blood Bank: Handle blood donations, requests, and searches by blood group.
Emergency Contacts: Display emergency contact numbers for hospitals, ambulances, blood banks, and police services.
Data Persistence: Save and load data to/from files (patients, employees, appointments, medicines, tests, donations) for persistent storage.
<br>
# Prerequisites
C Compiler: A C compiler like GCC is required to compile and run the program.
Operating System: Compatible with Windows, Linux, or macOS with standard C libraries.
Disk Space: Minimal space for data files (patients.dat, employees.dat, appointments.dat, medicines.dat, tests.dat, donations.dat).
<br>
# Usage
Start the Program: Run the executable to access the login menu. Choose a role (Doctor, Nurse, Pharmacist, Pathologist, or Admin).
Role-Based Functionalities:
Admin: Access all modules (Patient, Employee, Appointment, Clinical, Pharmacy, Pathology, Blood Bank, Emergency Contacts).
Doctor: Manage patients, clinical records, pathology tests, blood bank, and view emergency contacts.
Nurse: Handle patients, appointments, clinical records, pathology, blood bank, and emergency contacts.
Pharmacist: Manage medicines, view inventory, search medicines, bill medications, and view emergency contacts.
Pathologist: Add/search tests, handle test billing, and view emergency contacts.
<br>
# Navigation:
Use the menu-driven interface by entering numbers to select options.
Follow prompts to input data (e.g., patient details, appointment times, medicine names).
Data is saved automatically to files when exiting.
<br>
# Example Tasks:
Add a patient: Go to "Patient Management" → "Add Patient" and enter details.
Book an appointment: Select "Appointment" → "Add Appointment," choose a patient, doctor, and time slot.
Record vitals: Choose "Clinical Management" → "Vitals" to input weight, height, and blood pressure.
Bill medicines: Navigate to "Pharmacy" → "Billing" and enter medicine names and quantities.
<br>
# File Structure
main.c: The complete source code, written by me, containing all application logic.
Data Files (created during runtime):
patients.dat: Stores patient records.
employees.dat: Stores employee records.
appointments.dat: Stores appointment details.
medicines.dat: Stores medicine inventory.
tests.dat: Stores pathology test details.
donations.dat: Stores blood donation records.
<br>
# Limitations
Console-based interface without a graphical user interface (GUI).
Fixed limits: 100 patients, 100 appointments, 100 medicines, 30 employees, and 100 tests.
No password-based authentication for user roles.
Basic input validation; users must provide data in the correct format.
