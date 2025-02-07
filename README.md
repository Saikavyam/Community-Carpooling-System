# 🚗 Community Carpooling

## 📌 Project Overview
Community Carpooling is a web-based platform that allows users to share rides efficiently, reducing traffic congestion and promoting eco-friendly transportation. Users can post rides, book available rides, and leave reviews.

## ✨ Features
- **User Registration & Login**: Secure user authentication.
- **Post a Ride**: Users can offer rides by specifying pickup, drop-off points, and available seats.
- **Book a Ride**: Users can find and book rides based on availability.
- **Ride Details & Booking Management**: View ride details and manage bookings.
- **Review System**: Users can rate and review rides.
- **Dashboard**: Overview of posted and booked rides.

## 🛠️ Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL

## 🚀 Installation Guide
### Prerequisites
- PHP Server (XAMPP, WAMP, or LAMP)
- MySQL Database
- Web Browser

### Steps to Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/Saikavyam/community-carpooling.git
   ```
2. Move the project to your server's root directory (e.g., `htdocs` for XAMPP).
3. Import the database:
   - Open **phpMyAdmin**.
   - Create a new database named `carpooling_db`.
   - Import the SQL file from the `carpooling db` folder.
4. Start Apache and MySQL from your server control panel.
5. Open the browser and navigate to:
   ```
   http://localhost/community-carpooling/index.html
   ```

## 📂 Project Structure
```
📁 Community Carpooling
 ├── 📁 Codes
 │   ├── index.html (Landing Page)
 │   ├── register.html / register.php (User Registration)
 │   ├── book_ride.html / book_ride.php (Ride Booking)
 │   ├── post_ride.html / post_ride.php (Post a Ride)
 │   ├── dashboard.php (User Dashboard)
 │   ├── styles.css (CSS Styles)
 │   ├── validation.js (Form Validation)
 │   ├── carpooling db (Database Files)
 │   ├── review.html / review.php (Ride Reviews)
 ├── 📁 Output (Screenshots / Sample Data)
```

## 🤝 Contribution
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Added new feature"
   ```
4. Push the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a Pull Request.

## 📜 License
This project is licensed under the MIT License.

## 📞 Contact
For any queries, reach out at [your-email@example.com](mailto:8.saikavya12@gmail.com).


