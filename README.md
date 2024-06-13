# User Registration and Login System

## Overview

This project provides a simple user registration and login system using HTML, CSS, JavaScript, and Bootstrap. User data is stored in the browser's localStorage. The system includes three main pages: registration, login, and profile.

## Table of Contents

- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
  - [Registration Page](#registration-page)
  - [Login Page](#login-page)
  - [Profile Page](#profile-page)
- [Functions](#functions)
- [Styles](#styles)
- [License](#license)

## Project Structure

The project contains the following files:

- `index.html`: Registration page
- `login.html`: Login page
- `profile.html`: Profile page
- `styles.css`: Custom CSS for styling

## Installation

1. Clone the repository or download the project files.
2. Ensure you have an internet connection to access Bootstrap and jQuery from the CDN.
3. Open `index.html`, `login.html`, or `profile.html` in your browser to use the system.

## Usage

### Registration Page

- **Path:** `index.html`
- **Description:** Allows users to register by entering their name, email, and password.
- **Functionality:**
  - Checks for duplicate email entries.
  - Stores user information in localStorage.

### Login Page

- **Path:** `login.html`
- **Description:** Allows users to log in by entering their email and password.
- **Functionality:**
  - Verifies user credentials.
  - Redirects to the profile page upon successful login.
  - Displays an error message on login failure.

### Profile Page

- **Path:** `profile.html`
- **Description:** Displays the logged-in user's name and email.
- **Functionality:**
  - Retrieves user information from localStorage.
  - Allows the user to log out.

## Functions

### Registration Page (index.html)

- **saveData()**
  - Collects name, email, and password from input fields.
  - Checks for duplicate email entries.
  - Stores user data in localStorage.
  - Alerts the user if the email is already registered.

### Login Page (login.html)

- **saveData()**
  - Collects email and password from input fields.
  - Verifies user credentials against stored data.
  - Alerts the user of login success or failure.
  - Stores current user data in localStorage.
  - Redirects to the profile page on successful login.

### Profile Page (profile.html)

- **logOut()**
  - Clears user data from localStorage.
  - Redirects to the login page.

## Styles

Custom CSS is included in the `styles.css` file to style the container and card elements. Bootstrap is used for additional styling.

```css
.container {
    width: 100%;
    height: 100vh;
    background-color: purple;
}

.container .card {
    width: 50%;
    height: 50rem;
    background-color: white;
    padding: 20px;
    margin: auto;
    margin-top: 50px;
}

.login {
    padding: 10px;
}
```

## License

This project is open-source and available for any use. Modify and distribute as needed.

---

Enjoy using the User Registration and Login System! If you encounter any issues or have any suggestions, feel free to contribute or contact the project maintainer.
