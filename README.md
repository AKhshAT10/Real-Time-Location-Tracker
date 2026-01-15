# 🌍 Real-Time Location Tracker

A real-time location tracking web application built using **Node.js**, **Express.js**, **Socket.IO**, and **Leaflet.js**.  
The application tracks live user locations and displays them dynamically on an interactive map.

live : https://locationtracker-g4ra.onrender.com

---

## Features

- Real-time location tracking
- Interactive map using Leaflet.js
- Live updates via Socket.IO (WebSockets)
- Supports multiple connected users
- Low-latency location broadcasting

---

## Tech Stack

- **Backend:** Node.js, Express.js  
- **Real-Time Communication:** Socket.IO  
- **Frontend Map:** Leaflet.js  
- **Template Engine:** EJS  
- **Development Tool:** Nodemon  

---

## Project Structure

```text
Real-Time-Location-Tracker/
│
├── public/
│   ├── css/
│   │   └── styles.css
│   │
│   └── js/
│       └── script.js
│
├── views/
│   └── index.ejs
│
├── app.js
├── package.json
├── README.md
└── .gitignore
