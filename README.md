# Merchant-Configurable Payment Gateway System

This project demonstrates a **merchant-configurable online payment system** built using **React** for the frontend and **Node.js (Express)** for the backend.
It showcases how a web application can securely initiate payments, manage merchant configurations, and integrate with a third-party payment gateway.

The project is designed to help understand **end-to-end payment flow**, backend API design, and frontend–backend interaction in a real-world payment scenario.

---

## Tech Stack

### Frontend

* React
* JavaScript
* Vite
* Axios

### Backend

* Node.js
* Express.js
* Razorpay SDK
* dotenv

---

## Key Features

* Merchant-side configurable payment setup
* Secure payment order creation on backend
* Razorpay checkout integration
* Frontend–backend communication using REST APIs
* Environment-based configuration for sensitive keys

---

## Prerequisites

Make sure you have the following installed:

* Node.js ([https://nodejs.org/](https://nodejs.org/))
* npm / pnpm / yarn
* A Razorpay account for API keys

---

## Project Setup

### 1. Clone the repository

```bash
git clone https://github.com/luvkushsaini/Merchant-Configurable-Payment-Gateway-System.git
```

### 2. Navigate to the project directory

```bash
cd Merchant-Configurable-Payment-Gateway-System
```

---

## Backend Setup

```bash
cd server
pnpm install   # or npm install / yarn install
```

### Environment Configuration

Create a `.env` file in the `server` directory using the provided sample:

```env
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret
```

### Start Backend Server

```bash
pnpm start
```

Backend runs on:

```
http://localhost:5000
```

---

## Frontend Setup

```bash
cd client
pnpm install   # or npm install / yarn install
pnpm start
```

Frontend runs on:

```
http://localhost:5173
```

---

## How It Works

1. User enters payment details on the frontend
2. Frontend requests backend to create a payment order
3. Backend securely creates a Razorpay order
4. Razorpay checkout opens on the frontend
5. Payment is processed and verified
6. Success or failure response is handled in the UI

---

## Usage

* Enter a payment amount
* Click **Pay Now**
* Complete payment using Razorpay test credentials
* View payment confirmation on success

---

## Learning Outcomes

* Understanding real-world payment flows
* Secure handling of API keys using environment variables
* Designing backend APIs for payments
* Integrating third-party SDKs
* Coordinating frontend and backend services

