# 404errors - Accessible Locations Map
## Overview
This project is a web application that helps users find and rate accessible locations for people with disabilities. The interactive map displays various locations such as hospitals, parks, shopping centers, and other establishments with accessibility features.

## Features
* Interactive Map: Visual representation of accessible locations with filtering options
* User Authentication: Secure login and registration system
* Accessibility Filtering: Filter locations by various accessibility features:
1. Ramps
2. Accessible toilets
3. Wide entrances
4. Features for blind people
5. Free movement inside buildings
* Location Categories: Filter by location types like hospitals, parks, museums, etc.
* Location Details: View detailed information about each location
* User Feedback System: Users can leave ratings and reviews for locations
* Accessibility Features Rating: Users with disabilities can update accessibility information
# Tech Stack

### Backend: Nest (Typescript)
* Database: Postgres
* ORM: TypeORM
* Architecture: Layer architecture + modular
* Authorization: JWT
* File uploading: Firebase storage (Firebase SDK)
* Email: SendGrid service
* Db management: TypeOrm migrations and seeders

### Frontend: React with React Router
* State Management: React Context API
* Styling: Emotion (CSS-in-JS)
* Maps: Mapbox GL JS
* Form Handling: Formik with Yup validation
* UI Components: Custom components with tooltips

## User Flow

* Registration/Login: Users can create accounts with email verification
* Map Exploration: Browse accessible locations on the map
* Filtering: Apply filters to find specific location types or accessibility features
* Location Details: View details, accessibility features, and user reviews
* Feedback: Leave ratings and reviews for locations (one per user per location)
* Editing: Users with disabilities can update accessibility information

## Accessibility Focus

* Tooltips for all interactive elements
* Clear visual indicators for interactive components
* Support for users with various disabilities
* Option for users to upload disability documents to verify their status
* Features to help all users find accessible locations
