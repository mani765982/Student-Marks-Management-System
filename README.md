---

# Student Management System

This is a simple, client-side Student Management System (SMS) built using **HTML**, **Tailwind CSS**, and vanilla **JavaScript**. It allows you to manage student information, including their marks, attendance, and feedback, and visualize their performance through interactive graphs powered by **Chart.js**.

The application runs entirely in your web browser and uses in-memory data storage, meaning all data will be reset when you close or refresh the page.

---

## Features

* **Student Management**: Add, edit, select, and delete student records.
* **Marks Management**: Record and update student marks for various subjects and types (Quiz, Midterm, etc.).
* **Attendance Tracking**: Mark and manage student attendance status (Present, Absent, Late) for different subjects.
* **Feedback System**: Add and view qualitative feedback for students by subject and teacher.
* **Interactive Graphs**:
    * **Performance Trend**: Visualize a student's average scores over time for a selected subject.
    * **Attendance Summary**: See a pie chart breakdown of a student's attendance (Present, Absent, Late).
    * **Marks Distribution**: View a bar chart showing a student's average marks across different subjects.
* **Responsive Design**: Built with Tailwind CSS for a mobile-first and responsive user interface.
* **Dynamic UI**: Utilizes Lucide Icons for a modern and intuitive visual experience.

---

## How to Use

1.  **Save the Code**: Save the entire provided HTML code into a file named `index.html` (or any `.html` extension).
2.  **Open in Browser**: Open the `index.html` file with your web browser (e.g., Chrome, Firefox, Edge).

### Navigation

* The sidebar on the left allows you to switch between different management tabs: **Students**, **Marks**, **Attendance**, **Feedback**, and **Graphs**.

### Managing Students

1.  Go to the **Students** tab.
2.  **Add New Student**: Click "Add New Student" and fill in the details in the modal.
3.  **Select Student**: Click "Select" next to a student's name to manage their marks, attendance, feedback, and view graphs. The header will show which student is currently selected.
4.  **Edit Student**: Click "Edit" to modify a student's name or class.
5.  **Delete Student**: Click "Delete" to remove a student. **Warning**: This will also delete all associated marks, attendance, and feedback data for that student.

### Managing Data for a Selected Student

* Once a student is selected from the **Students** tab, you can navigate to the **Marks**, **Attendance**, or **Feedback** tabs to add, edit, or delete records specific to that student.
* The "Add" buttons in these tabs will become active only after a student is selected.

### Viewing Graphs

1.  Go to the **Graphs** tab.
2.  Ensure a student is selected.
3.  For the **Performance Trend** graph, use the "Select Subject for Performance Trend" dropdown to choose a subject and see how the selected student's average scores change over time.
4.  The **Attendance Summary** and **Average Marks by Subject** graphs will automatically update based on the selected student's data.

---

## Technologies Used

* **HTML5**: Structure of the web page.
* **Tailwind CSS**: Utility-first CSS framework for styling. (CDN)
* **JavaScript**: Core logic for interactivity, data management, and DOM manipulation.
* **Chart.js**: JavaScript library for creating interactive charts. (CDN)
* **Lucide Icons**: Open-source icon library for UI elements. (CDN)
* **Google Fonts (Inter)**: Modern typeface for consistent typography. (CDN)

---

## Local Data Storage

This application uses **in-memory JavaScript arrays and objects** to store all student data, marks, attendance, and feedback. This means:

* **Data is ephemeral**: Any data you enter will be lost when you close the browser tab or refresh the page.
* **No backend needed**: The application runs completely offline in your browser.

For a persistent data solution, you would need to integrate a backend server and a database.

---

## Development & Contribution

Feel free to fork this repository, modify the code, and experiment with new features.

To run and develop locally:

1.  Clone this repository (or copy the HTML content).
2.  Open the `index.html` file in your browser.
3.  Make changes to the HTML/CSS/JS. The browser will reflect changes on refresh.

---

Enjoy managing your student data!

---
