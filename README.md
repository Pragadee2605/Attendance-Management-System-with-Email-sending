**Attendance Management System**

**Overview**

The Attendance Management System is a web-based application built using Flask and Chart.js. It allows users to track student attendance and visualize data using bar and pie charts.

**Features**

Upload attendance data via an Excel sheet

Process and store attendance records

Display attendance percentage for each student

Visualize attendance statistics with bar and pie charts

Highlight students who fall below the attendance threshold

**Technologies Used**

Python (Flask framework)

HTML, CSS, JavaScript

Chart.js for data visualization

Pandas for data processing

Jinja2 for template rendering



**Usage**

Run the Flask application:

python app.py

Open a web browser and go to http://127.0.0.1:5000/.

Upload an Excel sheet containing attendance data.

View the processed data and attendance charts.


Fix: Generate an App Password for Gmail SMTP
Follow these steps to generate an App Password for your Flask email sender:

1️⃣ Go to Google App Passwords
👉 https://myaccount.google.com/apppasswords

2️⃣ Sign in to your Google Account (if prompted).

3️⃣ Under "Select app", choose Mail.

4️⃣ Under "Select device", choose Other (Custom name) and type something like "Flask Email".

5️⃣ Click "Generate", and Google will give you a 16-character password (e.g., abcd efgh ijkl mnop).

6️⃣ Use this App Password instead of your regular Gmail password in your Python SMTP code



paste the generated app password in the SENDER_PASSWORD = "   abcd efgh ijkl mnop   "

and use the mail is at SENDER_EMAIL = "       " and important the email you use should be enabled 2-factor authentication


