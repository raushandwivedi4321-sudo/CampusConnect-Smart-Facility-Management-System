# 🎓 Smart Campus - Facility Hub

Smart Campus Facility Hub is a lightweight, responsive single-page web application (SPA) designed to streamline the reservation and management of campus facilities such as computer labs, libraries, seminar halls, and auditoriums. It features role-based access for both students and administrators.

---

## ✨ Features

### 👨‍🎓 Student Portal
- **User Authentication:** Sign up for an account using a name, email, UID, and password, or log in with existing credentials.
- **Facility Exploration:** View available campus facilities along with descriptions and icons.
- **Facility Reservation:** Select a facility, choose an available date/time slot, and provide a booking purpose.
- **Conflict Prevention:** Prevents users from requesting already approved time slots.
- **Booking Status Tracker:** Monitor the status of booking requests (`Pending`, `Approved`, `Rejected`).
- **Personal Profile:** View user details and account role.

### 🔑 Admin Portal
- **Dedicated Admin Login:** Secure access for administrators.
- **Centralized Management:** View all facility booking requests submitted across the campus.
- **Approval Workflow:** Approve or reject booking requests with single-click actions.
- **Conflict Enforcement:** Prevents approving overlapping reservations for the same facility and time slot.
- **Dashboard Overview:** Monitor key statistics, including total facilities, total active bookings, and pending requests.

---

## 🛠️ Tech Stack

- **HTML5:** Semantic markup structure.
- **CSS3:** Custom styling with flexbox, grid, and CSS media queries for full responsiveness across mobile and desktop.
- **JavaScript (ES6):** Client-side interactivity, dynamic page routing, form handling, and state management.
- **Storage:**
  - `localStorage` for persistent user registrations and booking records.
  - `sessionStorage` for active session management.

---

## 🚀 Getting Started

### Prerequisites
No external dependencies, web servers, or package managers (like Node.js or npm) are required. All you need is a modern web browser (Chrome, Firefox, Edge, Safari, etc.).

### Installation & Execution
1. Clone or download the repository to your local machine.
2. Save the code file as `index.html`.
3. Double-click or open `index.html` in your web browser.

---

## 🔑 Default Credentials

### Administrator Account
- **Email:** `admin@12345.com`
- **Password:** `Admin12345`

### Student Account
- Click on the **Sign Up** link on the login page to create a new student account, or use any newly registered student credentials.

---

## 📂 Project Structure

```text
├── index.html        # Single-file application (HTML, CSS styles, and JS logic)
└── README.md         # Project documentation
```

---

## 📖 How to Use

1. **Sign Up / Log In:** Choose between the **Student** or **Admin** tab.
2. **Dashboard:** Browse available facilities and view key stats.
3. **Book a Facility:**
   - Click **Book Now** on any facility card.
   - Pick a date, choose a time slot, state the purpose, and submit.
4. **Track Requests:** Go to **My Bookings** (Student) to view approval status.
5. **Manage Requests:** Log in as an Admin and navigate to **Manage Bookings** to approve or reject requests.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).