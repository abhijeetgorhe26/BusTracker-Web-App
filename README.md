# 🚌 BusTracker Web Application

**Radhika Project** – A freelance project developed for a client to simplify and modernize bus tracking. The application provides real-time tracking, role-based dashboards, ETA alerts, and route management through a web-based interface.

## 🔍 Overview

This system supports three user roles:
- **Student**: View live bus location, ETA, select stops, get notifications.
- **Parent**: Get alerts when the bus arrives or departs, view child’s travel log.
- **Admin/Driver**: Share GPS location, update bus details, manage routes.

## 🧰 Tech Stack

- **Frontend**: HTML, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **APIs**: Google Maps API (for live tracking)
- **Hosting**: GitHub Pages (Frontend)

## ✨ Features

### Student Panel
- Live bus location view
- ETA to bus stop
- Stop selection
- Notification preferences
- View route & schedule
- Login/Signup

### Parent Panel
- Child’s assigned bus info
- Bus arrival/reach notifications
- Boarding and drop history
- Login access

### Admin/Driver Panel
- Update bus location (GPS)
- Add/update bus info
- Send delay/alert messages
- Edit or manage routes
- Assign buses to users

### Public Pages
- About the system
- Contact info (with feedback & FAQ)
- Chatbox for quick support
- Responsive design

## 📄 Pages

- `/` Home (welcome page with login links)
- `/login` Login for all roles
- `/dashboard` Role-specific dashboards
- `/track` Live map with real-time bus tracking
- `/about` & `/contact` Static info pages

## 🚀 Getting Started

Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/bustracker.git
cd bustracker
npm install
