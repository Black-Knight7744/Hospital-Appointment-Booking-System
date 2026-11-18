# 🏥 Hospital Appointment Booking System

A modern, responsive web application built with **React** that allows patients to browse departments, view doctor profiles, and book medical appointments seamlessly, while providing administrators with tools to manage schedules and bookings.

> Built as a capstone project to demonstrate core React concepts including component architecture, hooks, state management, client-side routing, and form validation.

---

## ✨ Features

### Patient Portal
- **Department & Specialist Browsing:** Filter doctors by medical specialty (e.g., Cardiology, Pediatrics, Orthopedics, Dermatology).
- **Real-Time Slot Selection:** Interactive calendar and time-slot picker preventing double bookings.
- **Appointment Management:** View upcoming appointments, reschedule, or cancel bookings directly from the user dashboard.
- **Responsive UI:** Optimized for desktop, tablet, and mobile screens.

### Admin / Clinic Overview
- **Appointment Dashboard:** Track daily, upcoming, and completed patient bookings.
- **Doctor Schedule Control:** Manage doctor availability and consultation hours.

---

## 🛠️ Tech Stack

- **Frontend Framework:** [React](https://react.dev/) (Functional Components & Hooks)
- **Build Tool:** [Vite](https://vitejs.dev/)
- **Routing:** [React Router](https://reactrouter.com/)
- **Styling:** CSS3 / Tailwind CSS *(update to match your styling setup)*
- **Icons:** Lucide React / React Icons
- **State Management:** React Context API / `useState` & `useReducer`

---

## 📂 Project Structure

```text
hospital_appointment_booking_system/
├── public/                  # Static assets
├── src/
│   ├── assets/              # Images, icons, and global styles
│   ├── components/          # Reusable UI components (Navbar, DoctorCard, Modal, etc.)
│   ├── context/             # Global state management (AuthContext, BookingContext)
│   ├── data/                # Mock data / API service configurations
│   ├── hooks/               # Custom React hooks
│   ├── pages/               # Route views (Home, Doctors, BookAppointment, Dashboard)
│   ├── utils/               # Helper functions and date/time formatters
│   ├── App.jsx              # Main application layout and routes
│   └── main.jsx             # Application entry point
├── index.html
├── package.json
└── README.md