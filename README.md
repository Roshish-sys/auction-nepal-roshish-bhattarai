🏠 Real Estate Live Auction System

A secure, real-time digital property auction platform with KYC verification, eSewa/Khalti deposits, Socket.IO live bidding, and LLaMA 3 chatbot.

📌 Overview

The Real Estate Live Auction System is a MERN-stack based web application that enables users to participate in secure, transparent, real-time property auctions.
The system uses:

Automatic KYC verification

Secure payment deposit & refund via eSewa/Khalti

Live real-time bidding using Socket.IO

AI Chatbot using LLaMA 3 for user support

Admin monitoring dashboard with suspicious activity detection

This project aims to modernize traditional property auctions by ensuring fairness, trust, and smooth user experience.

🚀 Features
👤 User Features

KYC verification (citizenship upload + OTP)

Secure deposit upload (QR-based payment screenshot)

Join live auction rooms

Real-time bidding (instant updates, no refresh needed)

Personalized dashboard

Receive auto refunds if user doesn’t win

AI chatbot for support (LLaMA 3)

🛠 Admin Features

Verify KYC and deposit submissions

Manage properties and auction listings

Live monitoring of bidding activity

Suspicious activity detection (rapid bids, duplicate logins, etc.)

Approve winners and trigger refunds

Real-time logs & auction analytics

🧰 Tech Stack
Frontend:

React.js

TailwindCSS

Socket.IO Client

Axios

Backend:

Node.js

Express.js

Socket.IO Server

JWT Authentication

Multer (file uploads)

Database:

MongoDB (Atlas or Local)

AI Integration:

LLaMA 3 API

Payment Integration:

eSewa API (Verification)

Khalti API (Verification)

📂 Project Structure
/client
   ├── src
   ├── components
   ├── pages
   ├── services
   └── utils

/server
   ├── controllers
   ├── routes
   ├── models
   ├── middleware
   ├── socket
   └── config

/database
   └── schema files