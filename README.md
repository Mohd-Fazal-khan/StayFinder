# StayFinder - Property Rental Platform

A full-stack web application for booking and managing rental properties, built with React, Node.js, and MongoDB.

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

