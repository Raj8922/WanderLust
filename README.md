#Wanderlust is a full-stack travel listing web application where users can explore destinations, create listings, leave reviews, and see locations interactively on a map!

✨ Features
User Authentication (Register / Login / Logout)

Create, Read, Update, Delete Travel Listings

Leave and Delete Reviews (only review author can delete)

Authorization (only listing owner can edit/delete their listing)

Server-side Validation with JOI

Flash Messages for User Feedback (success/error)

Interactive Google Map Integration
➔ Users can view locations on an embedded map.
➔ Auto-detects user location using Geolocation API.
➔ Destination search with geocoding!

Error Handling (404, validation errors, etc.)

Responsive UI using Bootstrap

MongoDB Database for storing users, listings, and reviews

🗺️ Map Integration
Integrated Google Maps to display:

User's current location

Selected travel destination based on user input

Markers for listings and search locations

Uses Google Maps JavaScript API and Geocoding services.

(You must have a valid Google Maps API Key for this to work.)

🛠️ Tech Stack
Frontend: HTML, EJS, Bootstrap 5

Backend: Node.js, Express.js

Database: MongoDB with Mongoose

Authentication: Passport.js (Local Strategy)

Session Management: express-session and connect-flash

Validation: JOI

Map Integration: @react-google-maps/api, Google Maps API

