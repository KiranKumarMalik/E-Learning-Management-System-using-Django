# e-Learning Management System

A learning management and online assessment system for academic education.

## Features

- Admin adds courses, teachers, and students and assigns them courses.
- The teacher creates course content, announcements, assignments, quizzes, takes attendance, etc. A teacher can see the details and analysis of the assessments.
- Students can enroll in the courses using the access key, see the course content of the enrolled courses, participate in assessments and see their results in detail.
- Discussion section for both teacher and student.

## Relational Schema

![schema](https://user-images.githubusercontent.com/87283264/187967219-55bea00e-3151-488a-a4be-d2a95b9d8a5c.png)

## Tech Stack

1. Django 4.0.4
2. Bootstrap 5.0.2
3. jQuery 3.6.0
4. Chart.js v3.9.1
5. Animate.css 4.1.1

## Admin UI
Here you have to create/Add Department, Course, Faculty, Student

![Admin UI](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/432a48963d7121f42ebafaae53c9f4fc2690ea4e/ss/Screenshot%202025-04-14%20203715.png)

## Faculty UI
Faculty Login
username: Faculty id
Password
![login (65)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/4b595aabc3e14875fc9521c993a77df0f89fe5c4/ss/Screenshot%202025-04-14%20205123.png)

Dashboard
![Screenshot (63)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/4b595aabc3e14875fc9521c993a77df0f89fe5c4/ss/Screenshot%202025-04-14%20194037.png)

Python Course
![Screenshot (70)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/4b595aabc3e14875fc9521c993a77df0f89fe5c4/ss/Screenshot%202025-04-14%20194758.png)

Post Announcement
![Screenshot (71)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/33135561cd6a7d976094a8d57d13a828dc5056cf/ss/Screenshot%202025-04-14%20194940.png)
![Screenshot](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/4b595aabc3e14875fc9521c993a77df0f89fe5c4/ss/Screenshot%202025-04-14%20195007.png)

Edit Announcement
![Screenshot (72)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/4b595aabc3e14875fc9521c993a77df0f89fe5c4/ss/Screenshot%202025-04-14%20195222.png)
![Screenshot (72)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/4b595aabc3e14875fc9521c993a77df0f89fe5c4/ss/Screenshot%202025-04-14%20195242.png)

Add Assignment
![Screenshot (67)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/4b595aabc3e14875fc9521c993a77df0f89fe5c4/ss/Screenshot%202025-04-14%20200132.png)
![Screenshot (68)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/4b595aabc3e14875fc9521c993a77df0f89fe5c4/ss/Screenshot%202025-04-14%20200207.png)

Add Course Materials
![Screenshot (69)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/4b595aabc3e14875fc9521c993a77df0f89fe5c4/ss/Screenshot%202025-04-14%20200524.png)
![Screenshot (69)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/758a1af860973d866df4167c9a767f476c678251/ss/Screenshot%202025-04-14%20200558.png)

Create Discussion
![Screenshot (69)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/758a1af860973d866df4167c9a767f476c678251/ss/Screenshot%202025-04-14%20200829.png)
![Screenshot (69)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/758a1af860973d866df4167c9a767f476c678251/ss/Screenshot%202025-04-14%20200858.png)
![Screenshot (69)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/758a1af860973d866df4167c9a767f476c678251/ss/Screenshot%202025-04-14%20200922.png)

Take Attendance
![Screenshot (69)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/758a1af860973d866df4167c9a767f476c678251/ss/Screenshot%202025-04-14%20200946.png)
![Screenshot (69)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/758a1af860973d866df4167c9a767f476c678251/ss/Screenshot%202025-04-14%20201109.png)

Add Quizzes
![Screenshot (69)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/758a1af860973d866df4167c9a767f476c678251/ss/Screenshot%202025-04-14%20201247.png)
![Screenshot (69)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/758a1af860973d866df4167c9a767f476c678251/ss/Screenshot%202025-04-14%20201259.png)
![Screenshot (69)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/758a1af860973d866df4167c9a767f476c678251/ss/Screenshot%202025-04-14%20201614.png)
![Screenshot (69)](https://github.com/KiranKumarMalik/E-Learning-Management-System-using-Django/blob/758a1af860973d866df4167c9a767f476c678251/ss/Screenshot%202025-04-14%20201259.png)


## Run Locally

1. Clone the project

```bash
git clone https://github.com/nz-m/eLMS-SWE.git
```

2. Go to the project directory

```bash
cd eLMS-SWE
```

3. Create a virtual environment and activate it (Windows)

```bash
python -m venv env
```

```bash
env\Scripts\activate
```

4. Install dependencies

```bash
pip install -r requirements.txt
```

> **Note:** If you're using newer versions of python(3.10+), you may need to add the `--use-deprecated=legacy-resolver` option when installing dependencies with `pip` to avoid errors :

```bash
pip install -r requirements.txt --use-deprecated=legacy-resolver
```

5. Make migrations and migrate

```bash
python manage.py makemigrations
```

```bash
python manage.py migrate
```

6. Create admin/superuser

```bash
python manage.py createsuperuser
```

7. Finally run the project

```bash
python manage.py runserver
```

Now the project should be running on http://127.0.0.1:8000/

Login as admin and add some courses, teacher and students.

Demo : https://youtu.be/NyL2ajUNxYk

## License

[The MIT License (MIT)](https://github.com/nz-m/eLMS-SWE/blob/main/LICENCE)
