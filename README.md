# Clinico Backend

A Node.js/Express backend for doctor appointment booking platform with OTP verification.

## Features

- OTP-Based Secure Login via Nodemailer
- MongoDB Integration
- JWT Authentication
- Appointment Booking APIs

## Tech Stack

- Node.js, Express.js
- MongoDB (Mongoose)
- JWT, Bcryptjs
- Nodemailer (OTP)

## Setup

```bash
npm install
```

Create `.env` file:
```
PORT=5000
MONGO_URI=your_mongodb_uri
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password
```

```bash
npm start
```

## API Endpoints

- `POST /api/send-otp` - Send OTP for login verification