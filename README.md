# StayFinder - Property Rental Platform
A full-stack web application for booking and managing rental properties, built with React, Node.js, and MongoDB.

<img width="1920" height="929" alt="Screenshot (137)" src="https://github.com/user-attachments/assets/0204f06e-0b9b-4d3f-aef2-f29c29fb2722" />
<img width="1920" height="909" alt="Screenshot (138)" src="https://github.com/user-attachments/assets/268e8469-d41f-4a4e-917a-403165b26eae" />
<img width="1920" height="821" alt="Screenshot (139)" src="https://github.com/user-attachments/assets/ec3b6ea8-ff9c-49f8-b68f-94ebb1a96550" />
<img width="1900" height="697" alt="Screenshot (140)" src="https://github.com/user-attachments/assets/2adb799e-4e4c-4748-861d-4c9e99034efa" />
<img width="1920" height="855" alt="Screenshot (141)" src="https://github.com/user-attachments/assets/40d940f7-1adc-426a-99c5-299efe09c649" />
<img width="1903" height="884" alt="Screenshot (142)" src="https://github.com/user-attachments/assets/7a568c17-6e83-4d42-8fb4-aff5c755c2ec" />




## Features

- 🏠 Property Listings: Browse, search and filter available properties
- 📅 Booking System: Book properties with date range selection 
- 💳 Payment Integration: Secure payments via Stripe
- 👤 User Authentication: Register and login for guests/hosts
- 🔍 Property Search: Filter by location, dates, and guest count
- 📍 Location Mapping: Interactive maps showing property locations
- 📱 Responsive Design: Mobile-friendly interface

## Tech Stack

### Frontend
- React with Vite
- React Router for navigation
- TailwindCSS for styling
- Axios for API requests
- React Leaflet for maps
- Stripe for payments
- Date-fns for date handling

### Backend
- Node.js & Express
- MongoDB & Mongoose
- JWT for authentication
- Cloudinary for image storage
- Stripe API integration
- CORS enabled

## Getting Started

### Prerequisites
- Node.js
- MongoDB Atlas account
- Cloudinary account
- Stripe account

### Installation

1. Clone the repository
```bash
git clone https://github.com/Mohd-Fazal-khan/StayFinder

1) Backend
cd backend
npm install

Crete .env file and add
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
STRIPE_SECRET_KEY=your_stripe_secret_key


2) Frontend
cd frontend
npm install

Crete .env file and add
VITE_API_URL=http://localhost:5000
```
### Run your Project
1) Frontend
   
   npm run dev
3) Backend
   
   npm run dev
   
### Live Url
``` https://front-sage-six.vercel.app/ ```



