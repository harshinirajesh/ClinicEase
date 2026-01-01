```markdown
# ClinicEase – Full Stack Doctor Appointment Booking System

ClinicEase is a comprehensive healthcare management application built using the **MERN Stack (MongoDB, Express, React, Node.js)**. It provides a seamless platform for patients to book appointments with doctors across various specialties, along with dedicated dashboards for **Doctors** and **Administrators**.

---

## Features

### Patient Side
- **User Authentication**: Secure signup and login using JWT.
- **Doctor Browsing**: Filter doctors by specialty (General Physician, Gynecologist, Dermatologist, etc.).
- **Appointment Booking**: View available time slots and book appointments.
- **Online Payments**: Secure payment integration using Razorpay.
- **Profile Management**: Update personal details and upload profile images via Cloudinary.

### Doctor Panel
- **Dashboard**: View total earnings, appointment count, and recent bookings.
- **Appointment Management**: Mark appointments as completed or cancel them.
- **Availability Toggle**: Control visibility and availability for patients.

### Admin Panel
- **Doctor Management**: Add new doctors, update profiles, and manage credentials.
- **Global Overview**: View and manage all appointments across the platform.

---

## Tech Stack

- **Frontend**: React.js, Tailwind CSS, Vite  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB Atlas  
- **Cloud Storage**: Cloudinary  
- **Payment Gateway**: Razorpay  
- **Authentication**: JSON Web Tokens (JWT), Bcrypt.js  

---

## Project Structure

```

├── admin/          # React Vite project for Admin & Doctor Panel
├── backend/        # Node.js API with Express & MongoDB
├── frontend/       # React Vite project for Patient Interface

````

---

## Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/prescripto.git
cd prescripto
````

### 2. Configure Environment Variables

Create a `.env` file inside the `backend` folder:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
ADMIN_EMAIL=admin_email
ADMIN_PASSWORD=admin_password
```

### 3. Install Dependencies

```bash
# Backend
cd backend
npm install

# Frontend (Patient)
cd ../frontend
npm install

# Admin & Doctor Panel
cd ../admin
npm install
```

### 4. Run the Application

Open three separate terminals:

```bash
# Terminal 1: Backend Server
cd backend
npm run server

# Terminal 2: Patient Frontend
cd frontend
npm run dev

# Terminal 3: Admin / Doctor Panel
cd admin
npm run dev
```

---

## Screenshots

<img width="1668" height="857" src="https://github.com/user-attachments/assets/f81da862-7e25-4f3d-b576-c4f860246269" />
<img width="1570" height="868" src="https://github.com/user-attachments/assets/73ddaa1c-f8ab-4525-aeb6-6dd8e2fd1a55" />
<img width="1601" height="811" src="https://github.com/user-attachments/assets/08805074-7ce8-4122-88b0-e979fbf8bf6f" />
<img width="1600" height="829" src="https://github.com/user-attachments/assets/a5d07186-08a1-49f8-a6f1-4cad619fc2fa" />
<img width="1882" height="804" src="https://github.com/user-attachments/assets/35092323-eb6f-49e6-995e-6a10789bc159" />
<img width="1858" height="774" src="https://github.com/user-attachments/assets/c1ee8161-0ac2-4f96-a1e3-7bc47984230d" />

---

## Contributing

Contributions are welcome. Feel free to fork the repository, create a new branch, and submit a pull request.

```
```
come! Feel free to open a Pull Request or report an Issue.
