# 📅 Appointment Scheduler (HTML + JavaScript)

This is a client-side appointment scheduler web app that allows users to:

- Schedule appointments with title, date, time, and description  
- View appointments on a calendar interface  
- Get desktop notifications 5 minutes before the appointment  
- Edit or delete scheduled appointments

Everything works in-browser using **HTML**, **CSS**, and **Vanilla JavaScript**. Data is temporarily stored in memory (does not persist on page refresh).

---

## ✨ Features

- 🗓️ Dynamic calendar with month navigation  
- ➕ Appointment form with title, date, time, and description fields  
- 📋 Daily appointment view  
- ✏️ Edit and 🗑️ delete options  
- 🔔 Desktop reminder 5 minutes before appointment (using Notification API)  
- 📌 Highlights today’s date and days with events  

---

## 🛠️ Tech Stack

- **HTML5** – Markup structure  
- **CSS3** – Styling and layout  
- **JavaScript** – Calendar logic, data handling, reminders  

---

## 📂 File Structure

appointment-calendar/
└── index.html # Main file with all HTML, CSS, and JS


---

## 🚀 How to Run

1. **Download or Clone**

```bash
git clone https://github.com/yourusername/appointment-scheduler.git
cd appointment-scheduler

    Open index.html in a browser

Double-click the file or open with VS Code Live Server or any browser.
🔔 Notification Reminder

    Reminder pops up 5 minutes before the appointment.

    Browser will request permission for notifications the first time you use the app.

    Make sure notifications are allowed in your browser settings.

📌 Limitations

    ❌ Data is not saved permanently (no backend or localStorage used)

    🔄 Refreshing the page clears all appointments

    🔐 No user login/authentication

📈 Future Improvements

    💾 Store data using localStorage or a backend database (MySQL + Node.js)

    📱 Make the UI responsive for mobile use

    📧 Email or SMS reminders

    👥 Multi-user login and dashboard

🙋‍♂️ Author

Made by Lovepreet
