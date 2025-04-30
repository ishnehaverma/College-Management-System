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
student- 'ishneha'
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

![WhatsApp Image 2025-04-30 at 23 25 09_6dbb9b4b](https://github.com/user-attachments/assets/daa1ee5a-fe54-4c4b-a0f1-e8527fd7cabb)


