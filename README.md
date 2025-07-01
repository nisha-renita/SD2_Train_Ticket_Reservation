# Train Ticket Reservation System

This is a web-based Train Ticket Reservation System. It lets users search for trains, check seat availability, view train details, and book tickets online. Admin users can manage train data and see booking details.

## Features

- User Registration and Login
- Search Trains between stations
- Check Train Schedule and Timings
- View Seat Availability
- Book Train Tickets
- View Booking History
- Admin Panel for managing trains
- Secure Login and Password Changes
- Payment Gateway Simulation

## Technologies Used

- Frontend: HTML, CSS, Bootstrap
- Backend: Java (J2EE), Servlets, JDBC
- Database: Oracle SQL
- Build Tool: Maven
- Server: Apache Tomcat

## How The Code Works

### User Side Flow

1. **Register / Login**  
   - Users create an account or log in with email and password.
   
2. **Search Trains**  
   - Users enter “from” and “to” stations to see available trains, fares, and seat info.
   
3. **View Details**  
   - Users can check train timings, fare, and available seats.
   
4. **Book Tickets**  
   - Users choose a train, enter seat count, and proceed to payment.
   
5. **Payment and Confirmation**  
   - On successful booking, ticket details are saved in the database.

6. **View Profile and Booking History**  
   - Users can update profile info and see their past bookings.

---

### Admin Side Flow

1. **Admin Login**  
   - Admin logs in with secure credentials.
   
2. **Manage Trains**  
   - Admin can add, update, or remove trains in the system.
   
3. **View Trains & Bookings**  
   - Admin can view all trains and booking histories.

---

## How To Run The Project

> **Note:** This project uses Oracle Database. Make sure Oracle SQL and Tomcat are installed.

### Database Setup

1. Open Oracle SQL Developer.
2. Run SQL scripts in `/sql` folder (or follow instructions in README) to create tables:
    - ADMIN
    - CUSTOMER
    - TRAIN
    - HISTORY
3. Insert initial data for demo users and trains.

### Running In Eclipse

1. Open Eclipse EE (Enterprise Edition).
2. Import the project:
   - File → Import → Git → Projects From Git → Clone URI
   - Paste your GitHub repository URL.
3. Right-click the project → Run As → Maven Build → enter:
    ```
    clean install
    ```
4. Set up Tomcat Server (v8.0 or above) in Eclipse.
5. Right-click project → Run As → Run On Server.
6. Visit the app:
    ```
    http://localhost:8083/trainbook/
    ```

---

## Demo Credentials

- **Admin**
  - Username: admin@demo.com
  - Password: admin

- **User**
  - Username: shashi@demo.com
  - Password: shashi

---




