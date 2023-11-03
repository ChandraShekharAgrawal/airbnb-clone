# Airbnb Clone Web App

This project is an Airbnb clone web application built with Next.js, Tailwind CSS, MongoDB, Prisma, and NextAuth. Currently, it is in developmet phase, so things might not work as intended.

## Overview

The application is a simplified version of Airbnb, allowing users to view and book available properties for rent. It supports user authentication, property listings, and booking functionalities.

## Tech Stack

- **Next.js**: A React framework for building server-rendered applications.
- **Tailwind CSS**: A utility-first CSS framework for quickly building custom designs.
- **MongoDB**: A NoSQL database for storing property and user data.
- **Prisma**: A modern database toolkit used for database access, migrations, and data modeling.
- **NextAuth**: An authentication library for Next.js applications, providing easy-to-use authentication features.

## Features

- **User Authentication**: Secure authentication powered by NextAuth for user sign-up, login, and sessions.
- **Property Listings**: Display available properties, their details, and booking information.
- **Booking System**: Allow users to book a property based on availability.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ChandraShekharAgrawal/airbnb-clone.git
   ```
2. Install Dependencies:
   ```bash
    cd airbnb-clone
    npm install
   ```
3. Set up environment variables:

   - Create a .env file based on the .env.example template and add necessary credentials for MongoDB, NextAuth, and other configurations.

4. Run the development server:
   ```bash
   npm run dev
   ```

## Uses

- Access the application by navigating to http://localhost:3000 in your browser.
- Explore the property listings, sign up, log in, and test the booking system.

## License

This project is licensed under the MIT License.
