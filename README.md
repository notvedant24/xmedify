# MEDIFY - Medical Center Slot Booking Platform

MEDIFY is a web application designed for booking appointment slots at medical centers. Built with modern web technologies, it provides a user-friendly interface for patients to book appointments and for medical centers to manage their schedules efficiently.

## Table of Contents📚

- [Introduction](#introduction)
- [Features](#features)
- [Screenshot](#screenshot)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction🚀

MEDIFY is a comprehensive platform designed to streamline the process of booking and managing medical appointments. Patients can easily find available slots, book appointments, and receive reminders. Medical centers can manage their schedules, view appointments, and update availability.

## Features🛠️

- User-friendly interface for booking medical appointments
- Real-time availability of appointment slots
- User authentication and profile management
- Admin panel for medical centers to manage appointments
- Email and SMS reminders for appointments
- Responsive design for optimal viewing on various devices

## Screenshot📷

![MEDIFY](https://github.com/BoddepallyVenkatesh06/MEDIFY-Medical-Center-Slot-Booking-Platform/blob/main/Screenshot_Medify.png)

## Getting Started🎯

### Prerequisites📋

Before you begin, ensure you have the following installed on your system:
- Node.js
- npm (Node Package Manager)
- Render (for backend database)

### Installation⚙️

1. Clone the repository:

```bash
git clone https://github.com/notvedant24/xmedify
cd medify-slot-booking
```

2. Install frontend dependencies:

```bash
cd client
npm install
```

3. Install backend dependencies:

```bash
cd ../server
npm install
```

4. Set up environment variables:

Create a `.env` file in the `server` directory and add the following environment variables:

```
render.com
```


### Usage📈

To start the development servers:

1. Start the backend server:

```bash
cd server
npm start
```

2. Start the frontend development server:

```bash
cd ../client
npm start
```

The application will be running in development mode at `http://localhost:3000`.

To build the application for production:

1. Build the frontend:

```bash
cd client
npm run build
```

2. Serve the built frontend with the backend server.

## Contributing❤️

Contributions are welcome! If you'd like to contribute to MEDIFY, please follow these steps:

1. Fork the project.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.
