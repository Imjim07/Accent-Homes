# Accent Homes

A full-stack luxury short-let apartment booking platform built 
for a real estate client based in Asaba, Nigeria.

## Live Site
[accenthomes.pages.dev](https://accenthomes.pages.dev)

## Tech Stack
- Frontend: HTML5, CSS3, Vanilla JavaScript
- Backend/Database: Firebase Firestore
- Authentication: Firebase Auth (admin role-based access)
- Media: Cloudinary (upload, optimisation, transformation)
- Payments: Paystack (live integration)
- Deployment: Cloudflare Pages

## Features
- Public property listing and browsing
- Live booking flow with Paystack payment integration
- Full CRUD admin portal for managing properties and bookings
- Role-based access control (admin vs guest)
- Cloudinary media management with image optimisation
- Mobile-responsive design

## Project Structure
/
├── public/          # Frontend pages
├── admin/           # Admin portal
├── js/              # Firebase, Paystack, UI logic
├── css/             # Stylesheets
└── .env.example     # Environment variable template

## Environment Variables
FIREBASE_API_KEY=
FIREBASE_PROJECT_ID=
CLOUDINARY_CLOUD_NAME=
PAYSTACK_PUBLIC_KEY=
