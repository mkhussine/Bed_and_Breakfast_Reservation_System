## Bed & Breakfast Reservation System.

This is a full-featured web application for managing reservations at a small bed and breakfast. Built in Go, the system allows guests to view available rooms, check availability, and make bookings. It also provides a secure administrative backend for the property owner to manage reservations and receive notifications.

---

## Project Overview

The application simulates a bed and breakfast with two rentable rooms. Users can:

* Visit the website and browse room details
* Search for room availability between specific dates
* Book available rooms
* Receive confirmation notifications

The property owner can:

* Log in securely to a backend system
* View upcoming and past reservations on a calendar
* Edit or cancel bookings
* Receive notifications about new reservations

---

## Key Features

### For Guests

* View room information and property details
* Search availability by date range
* Book one or more nights
* Receive confirmation by email or SMS

### For Property Owner

* Secure login system
* Admin dashboard for managing bookings
* Calendar view of all reservations
* Ability to modify or cancel reservations
* Notifications for new bookings

---

### **Tech Stack**

* **Language:** JavaScript (Node.js)
* **Web Framework:** Express.js
* **Templating:** HTML + EJS (or Pug/Handlebars – choose based on your preference)
* **Database:** PostgreSQL
* **Authentication:** Custom login with session handling (using `express-session` and `bcrypt` or similar)
* **Notifications:** Email (using `nodemailer`)


