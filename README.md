# Hospital-Patient-Appointment-System
This is a minimal hospital appointment management system written in C language, showcasing the use of core data structures such as linked lists, binary search trees (BST), circular queues, arrays, and stacks.  The project simulates a simple hospital system where patients, doctors, and appointments are managed through a text-based menu.


Features

Patients (Linked List)

Add new patients (auto-increment ID).

Delete existing patients.

List all patients.

Doctors (Binary Search Tree)

Add new doctors (auto-increment ID).

List doctors in sorted order by ID.

Appointment Requests (Circular Queue)

Store appointment requests (patient → doctor with date/time).

View all pending requests.

Scheduling (Array of Appointments)

Process appointment requests into confirmed schedules.

Each schedule stores patient name, doctor name, and time.

Supports undo functionality using a stack.

Undo (Stack)

Rollback the most recent scheduled appointment.

Interactive Menu

Add/Delete patients

Add/List doctors

Enqueue appointment requests

Process requests → schedule

Undo last schedule

View scheduled appointments

Data Structures Used

Linked List → Patient management

Binary Search Tree (BST) → Doctor management

Circular Queue → Appointment requests

Array → Confirmed schedules

Stack → Undo last scheduled appointment

Example Flow

Add patients and doctors.

Enqueue appointment requests (patient → doctor, time).

Process requests into confirmed schedules.

Undo the last schedule if needed.

Display all current appointments.
