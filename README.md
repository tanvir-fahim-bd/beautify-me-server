# Beautify Me – Beauty Service Booking Platform

**Beautify Me** is an online beauty service booking platform that allows customers to explore available services, schedule appointments, make payments, and share reviews based on their experiences.

The platform provides a convenient booking experience with date and time-slot selection, personalized user dashboards, and an administrative dashboard for managing users, services, and platform activities.

## 🌐 Live Project

- **Live Website:** https://beautify-me-e67e5.web.app/
- **Client Repository:** https://github.com/TanvirFahimBD/beautify-me-client

---

## 📸 Project Screenshots

<!-- Add actual project screenshots to the screenshots directory -->

| Home Page | Services |
|:---:|:---:|
| ![Home Page](./screenshots/home.png) | ![Services](./screenshots/services.png) |

| User Dashboard | Admin Dashboard |
|:---:|:---:|
| ![User Dashboard](./screenshots/user-dashboard.png) | ![Admin Dashboard](./screenshots/admin-dashboard.png) |

---

## ✨ Key Features

### 👤 User Features
- User registration and login.
- Authentication required before booking services.
- Browse available beauty services.
- Book services by selecting a specific date and available time slot.
- View and update personal profile information.
- Access a personalized user dashboard.
- Make booking payments through the dashboard.
- Review previously received services.
- View booking and service history.

### 🛡️ Admin Features
- Access a dedicated admin dashboard.
- View and manage user accounts.
- Delete existing user accounts.
- Assign administrator roles to other users.
- Create and publish new beauty services.
- Delete existing services.
- Manage platform services and user access.

### 🔒 Additional Features
- Firebase Authentication.
- Protected routes for authenticated users.
- Role-based dashboard access.
- Date-based appointment scheduling.
- Time-slot-based booking management.
- Custom 404 page for unknown routes.

---

## 🛠️ Technologies Used

### Frontend
- **React.js** – Building reusable UI components and interactive user interfaces.
- **React Router** – Managing client-side routing and navigation.
- **Firebase Authentication** – Handling user authentication and account management.

### Backend
- **Node.js** – Providing the server-side JavaScript runtime.
- **Express.js** – Developing REST APIs and handling backend requests.
- **MongoDB** – Storing and managing application data.

### Deployment & Hosting
- **Firebase Hosting** – Hosting the frontend application.
- **Railway** – Used as a deployment platform during development (verify its exact role in the final deployment).

---

## 📦 Dependencies

### Frontend Dependencies

Main expected dependencies based on the project architecture:

- react
- react-dom
- react-router-dom
- firebase

### Backend Dependencies

Main expected dependencies:

- express
- mongodb
- cors
- dotenv

> **Note:** Verify the exact dependencies and versions from the frontend and backend `package.json` files before publishing.

---

## ⚙️ Run Locally

Follow these steps to run the project on your local machine.

### Prerequisites

Make sure you have installed:

- Node.js (LTS recommended)
- npm
- Git
- MongoDB account or local MongoDB server
- Firebase project with Authentication configured

### 1. Clone the Frontend Repository

```bash
git clone https://github.com/TanvirFahimBD/beautify-me-client.git

cd beautify-me-client
```

### 2. Install Frontend Dependencies

```bash
npm install
```

### 3. Configure Frontend Environment Variables

Create a `.env` file in the frontend root directory.

```env
# Backend API
REACT_APP_API_URL=http://localhost:5000

# Firebase Configuration
REACT_APP_apiKey=your_firebase_api_key
REACT_APP_authDomain=your_firebase_auth_domain
REACT_APP_projectId=your_firebase_project_id
REACT_APP_storageBucket=your_firebase_storage_bucket
REACT_APP_messagingSenderId=your_firebase_sender_id
REACT_APP_appId=your_firebase_app_id
```

> Adjust environment variable names according to the actual frontend configuration. For Vite projects, use the `VITE_` prefix instead of `REACT_APP_`.

### 4. Clone and Configure the Backend

Clone the backend repository into a separate directory.

```bash
git clone YOUR_SERVER_REPOSITORY_URL

cd YOUR_SERVER_DIRECTORY
```

Install dependencies:

```bash
npm install
```

Create a `.env` file in the backend root directory.

```env
PORT=5000
DB_USER=your_mongodb_username
DB_PASS=your_mongodb_password
```

Add any other environment variables required by the backend implementation, including payment gateway credentials if applicable.

### 5. Start the Backend Server

```bash
npm start
```

If your backend supports a development script:

```bash
npm run dev
```

Backend API:

```text
http://localhost:5000
```

### 6. Start the Frontend Application

For Create React App:

```bash
npm start
```

For Vite:

```bash
npm run dev
```

The frontend should now be accessible through your local development server.

---

## 🧠 Technology Choices & Why I Used Them

| Technology | Purpose |
|---|---|
| React.js | Building reusable and interactive UI components |
| React Router | Managing application navigation and protected routes |
| Firebase Authentication | Providing user registration and login |
| Node.js | Running server-side JavaScript |
| Express.js | Developing REST APIs and backend services |
| MongoDB | Managing users, services, bookings, and reviews |
| Firebase Hosting | Deploying and hosting the frontend |
| Railway | Backend deployment during development (verify) |

---

## 🚧 Challenges Faced During Development

Some important engineering challenges addressed while developing the platform:

- **Authentication & Authorization:** Implementing authentication and restricting booking functionality to logged-in users.
- **Appointment Scheduling:** Managing date-specific bookings and time-slot selection.
- **Booking Management:** Handling booking information and maintaining service history.
- **Payment Integration:** Connecting the booking workflow with payment functionality.
- **Role-Based Access Control:** Separating user and administrator permissions and dashboard functionality.
- **User Management:** Implementing administrative operations such as deleting accounts and assigning admin roles.
- **Service Management:** Building CRUD functionality for beauty services.
- **Frontend & Backend Integration:** Connecting React components with Express APIs and managing asynchronous data communication.

---

## 💡 Problems Solved

- Simplified the process of discovering and booking beauty services online.
- Eliminated the need for manual appointment scheduling.
- Provided date and time-slot-based appointment booking.
- Centralized customer booking and service history.
- Enabled customers to make payments through their dashboard.
- Introduced a review system for collecting customer feedback.
- Provided administrators with centralized user and service management.
- Established separate user and admin dashboards.

---

## 🔮 Future Improvements

- Real-time appointment availability.
- Booking cancellation and rescheduling.
- Automated booking confirmation and email notifications.
- Advanced service filtering and searching.
- Admin analytics and revenue reporting.
- Improved appointment management.
- Additional security and performance optimizations.

---

## 👨‍💻 Developer

**Tanvir Hossain Fahim**  
Software Engineer | Full-Stack Developer

- **Portfolio:** https://tanvir-fahim-bd.netlify.app/
- **GitHub:** https://github.com/TanvirFahimBD
- **LinkedIn:** https://www.linkedin.com/in/tanvir-fahim/

---

⭐ If you find this project interesting, consider giving it a star!

**Built with ❤️ to make beauty service booking easier and more convenient.**
