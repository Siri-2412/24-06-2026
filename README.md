# TechPortal Dashboard

A clean and responsive **dashboard-style website** built using **HTML, CSS, and JavaScript**.
This project includes a **top navigation bar**, **sidebar menu**, **main dashboard content**, and **popup login/signup forms**.

---

## Features

* Responsive **navbar** with logo and authentication buttons
* Sidebar with dashboard navigation links
* Hero section with welcome message
* Informational cards for news, events, and features
* Popup **Login** and **Sign Up** forms
* Professional and modern dashboard UI
* Clean layout using **HTML, CSS, and JavaScript**

---

## Project Structure

```bash
TechPortal/
│── index.html
│── style.css
```

---

## Technologies Used

* **HTML5** – page structure
* **CSS3** – styling and layout
* **JavaScript** – popup form functionality

---

## How It Works

### Navbar

The top navigation bar contains:

* Website logo (**TechPortal**)
* **Login** button
* **Sign Up** button

### Sidebar

The sidebar provides quick navigation options such as:

* Dashboard
* Profile
* Projects
* Events
* Settings

### Main Content

The main content section includes:

* A **hero section** with a welcome message
* Dashboard **cards** showing latest updates, events, and features

### Popup Forms

When the user clicks:

* **Login** → Login popup appears
* **Sign Up** → Signup popup appears

Popup visibility is controlled using JavaScript functions:

* `showForm(id)`
* `closeForm(id)`

---

## File Description

### `index.html`

Contains:

* Navbar
* Sidebar
* Main content
* Login popup form
* Signup popup form
* JavaScript for opening and closing forms

### `style.css`

Contains:

* Page layout styling
* Navbar and sidebar design
* Card and hero section styles
* Popup form styles
* Button hover effects
* Professional color theme

---

## JavaScript Functions

### Show Popup Form

```javascript
function showForm(id) {
    document.getElementById(id).style.display = "flex";
}
```

### Close Popup Form

```javascript
function closeForm(id) {
    document.getElementById(id).style.display = "none";
}
```

---

## How to Run the Project

1. Download or copy the project files.
2. Save the files in the same folder:

   * `index.html`
   * `style.css`
3. Open `index.html` in your browser.

---

## Future Improvements

You can improve this project by adding:

* Form validation
* Database connectivity
* User authentication backend
* Responsive mobile sidebar menu
* Dashboard charts and analytics
* Dark mode toggle

---

## Output

This project creates a **professional dashboard interface** with authentication popups and structured navigation.

---

## Author

Developed as a frontend dashboard project using **HTML, CSS, and JavaScript**.
