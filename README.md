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
RUN FUNCTIONALITY OF THIS CODE-
=== Hospital Simple Menu ===
1  - Add patient
2  - Delete patient
3  - List patients
4  - Add doctor
5  - List doctors
6  - Enqueue appointment request
7  - Show request queue
8  - Process next request (schedule)
9  - Undo last scheduled appointment
10 - Show scheduled appointments
0  - Exit
Choose an option: 1
Enter patient name: Alice
Added patient 1 : Alice

Choose an option: 4
Enter doctor name: Dr. Smith
Added doctor 1 : Dr. Smith

Choose an option: 6
Enter patient id: 1
Enter doctor id: 1
Enter date/time (string): Monday 10AM
Enqueued request #1  patient 1 -> doctor 1  at Monday 10AM

Choose an option: 8
Scheduled appointment s1: patient Alice (p1) -> doctor Dr. Smith (d1) at Monday 10AM (from req #1)

Choose an option: 10
Scheduled appointments:
  s1: Alice (p1) -> Dr. Smith (d1) at Monday 10AM [active]

