# Online Learning Platform - Hasbar Institute

## Video URL
[Watch Demo Video](https://youtu.be/1OpuyltGOZA?si=6SilQZSUYG-1MK5q)

## Project Overview

The **Hasbar Institute Online Learning Platform** is a web application designed to offer a dynamic and engaging learning experience for students interested in various domains such as Software Engineering, Data Science, Digital Marketing, UI/UX, and Product Management. This platform facilitates user authentication, course selection, and provides an interactive dashboard for a personalized learning journey.

## Project Structure

### 1. `app.py`

The `app.py` file serves as the main entry point for the Flask application. It includes route definitions for the index, signup, login, dashboard, and logout pages. The routes handle user authentication, database interactions, and rendering of HTML templates.

### 2. `templates` folder

The `templates` folder contains HTML files for different pages of the application, including `index.html`, `signup.html`, `login.html`, `dashboard.html`, and others. These files define the structure and content of each page, with placeholders for dynamic data.

### 3. `static` folder

The `static` folder includes static assets such as CSS files (`style.css`) and JavaScript files (`app.js`). The CSS file defines the styling of the web pages, while the JavaScript file includes client-side scripting for enhanced interactivity.

### 4. `database.db`

The `database.db` file is an SQLite database that stores user information. The `users` table within the database holds details such as user ID, name, username, hashed password, and selected course.

## Design Choices

1. **User Authentication:** Passwords are securely hashed using the `generate_password_hash` function from the Werkzeug library. This ensures the security of user credentials.

2. **Styling with Tailwind CSS:** The application uses Tailwind CSS for styling, following a utility-first approach. Tailwind provides a clean and modern design, and its utility classes allow for rapid styling without compromising flexibility.

3. **Responsive Design:** The application's layout and styling are designed to be responsive, ensuring a seamless user experience across various devices.

4. **Dynamic Dashboard:** The dashboard dynamically displays information based on the user's selected course, providing a personalized learning experience.

## Getting Started

To run the project locally, follow the instructions in the `README.md` file. Make sure to set up a virtual environment, install dependencies, and start the Flask application.

## Contributing

Contributions to the project are welcome! If you'd like to contribute, follow the outlined steps in the `README.md` file, create a new branch for your feature, and submit a pull request.

Enjoy your learning journey at Hasbar Institute!