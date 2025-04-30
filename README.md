# College-Management-System
A college management system built using Django framework. It is designed for interactions between students and teachers. Features include attendance, marks and time table.

# Installation
Python and Django need to be installed

- pip install django

# Usage
Go to the College-ERP folder and run

- python manage.py runserver

Then go to the browser and enter the url http://127.0.0.1:8000/

# Login
The login page is common for students and teachers.

The username is their name and password for everyone is 'project123'.

Example usernames:
student- 'sarthak'
teacher- 'trisila'

You can access the django admin page at http://127.0.0.1:8000/admin and login with username 'admin' and the above password.

Also a new admin user can be created using

- python manage.py createsuperuser

# Users

New udents and teachers can be added through the admin page. A new user needs to be created for each.

The admin page is used to modify all tables such as Students, Teachers, Departments, Courses, Classes etc.
st

For more details regarding the system and features please refer the reports included.

# Update (25/04/2025)

Added method to reset attendance time range in Django Admin page.

![WhatsApp Image 2025-04-30 at 19 14 40_d717277d](https://github.com/user-attachments/assets/252135b2-03ac-4380-9c3c-eeb891acbd9e)

This is present in Django Admin -> Attendance (http://127.0.0.1:8000/admin/info/attendanceclass/).
Start Date: Start Date of Attendance period
End Date: End Date of Attendance period

This will delete all present attendance data and create new attendance objects for the given time range.

# Screenshots
**Teacher Page**

![WhatsApp Image 2025-04-30 at 23 21 53_535c393f](https://github.com/user-attachments/assets/12d84f03-456f-4794-a730-b812fdf66e77)

![WhatsApp Image 2025-04-30 at 23 35 58_305bf0c1](https://github.com/user-attachments/assets/1a105c35-1c3d-4064-9729-3e9f45da8949)

![WhatsApp Image 2025-04-30 at 23 31 57_593e78df](https://github.com/user-attachments/assets/0ab98ffc-6801-4b8b-9096-d632a09f631a)

![WhatsApp Image 2025-04-30 at 23 32 38_a8766410](https://github.com/user-attachments/assets/86a83afa-0cde-492e-a06a-da07bf577f54)

![WhatsApp Image 2025-04-30 at 23 45 15_2cbbffea](https://github.com/user-attachments/assets/f882a7c6-9882-458e-903b-7a966efea319)

![WhatsApp Image 2025-04-30 at 23 32 58_9531a4d9](https://github.com/user-attachments/assets/45885ef4-a33e-4107-a370-411fd0672cad)

![WhatsApp Image 2025-04-30 at 23 33 15_9a7a6ac7](https://github.com/user-attachments/assets/3c148336-dd74-4451-bea9-0fd8b7481a7f)

**Admin Page**

![WhatsApp Image 2025-04-30 at 23 40 10_e6cb878d](https://github.com/user-attachments/assets/d81ff8ec-491e-4ad6-8db2-6dd33d8c0477)

![WhatsApp Image 2025-04-30 at 23 40 23_c4449c40](https://github.com/user-attachments/assets/c2e1d11b-f6be-40ab-9535-3e226d2a8ce9)

![WhatsApp Image 2025-04-30 at 23 40 37_9a8ac74e](https://github.com/user-attachments/assets/94166d8c-b307-4b27-b696-04e2a44900b1)


