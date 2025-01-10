# Bell Hospital Management System

## Overview
The Bell Hospital Management System is a Java-based application designed to digitize and automate hospital operations. This system replaces the manual record-keeping process by efficiently managing patient, doctor, lab test, and appointment records. Built using object-oriented programming principles, it ensures scalability and ease of use for healthcare institutions.

## Features
- **Patient Management**: Register, update, and search patient records by ID or contact details.
- **Doctor Management**: Register, update, and search doctor records by ID or specialization.
- **Lab Test Records**: Add and search lab test results linked to patient IDs.
- **Appointment Scheduling**: Schedule appointments for patients with doctors and view appointments by date or doctor.
- **File-Based Storage**: Persist all records using a simple file system.

## Technologies
- **Programming Language**: Java
- **IDE**: Eclipse
- **File Storage**: For record persistence
- **Object-Oriented Design**: Implements UML-based architecture

## Limitations
- The application uses file-based storage, which may not scale well for larger datasets.
- User interface is command-line based; no graphical interface is implemented.
- Lab test and appointment records are limited to basic operations.

## Future Enhancements
- Upgrade storage to a relational database system (e.g., MySQL).
- Develop a graphical user interface for better user experience.
- Add reporting features for patient history, doctor workload, and lab test summaries.
