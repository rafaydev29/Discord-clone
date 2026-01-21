# Discord Clone

A web-based chat application built with PHP and MySQL that mimics the core functionality and user interface of Discord.

## Features

- **User Authentication**: Secure login and registration system.
- **Messaging**: Send and receive messages with other users.
- **Friend System**: Send friend requests, accept/reject requests, and manage your friends list.
- **User Profiles**: Customize your profile with an avatar image and "About Me" status.
- **Blocking**: Ability to block users to prevent interactions.
- **Responsive UI**: A dark-themed interface designed to look like Discord, optimized for both desktop and mobile.

## Technologies Used

- **Frontend**: HTML5, CSS3 (Custom Discord-like theme), JavaScript
- **Backend**: PHP
- **Database**: MySQL (MariaDB)
- **Server**: Apache (via XAMPP)

## Installation & Setup

1. **Prerequisites**:
   - Install [XAMPP](https://www.apachefriends.org/index.html) or any local server environment that supports PHP and MySQL.

2. **Clone the Repository**:
   - Download or clone this project into your `htdocs` folder (e.g., `C:\xampp\htdocs\discord`).

3. **Database Setup**:
   - Open **phpMyAdmin** (usually `http://localhost/phpmyadmin`).
   - Create a new database named `discord_clone`.
   - Import the `discord_clone.sql` file located in the root directory of this project.

4. **Run the Application**:
   - Open your web browser and navigate to `http://localhost/discord`.

## Database Schema

The project relies on the following database structure:
- **`users`**: Stores username, email, password, profile image, and about status.
- **`messages`**: Stores chat history between users.
- **`friends`**: Tracks established friendships.
- **`friend_requests`**: Manages pending, accepted, or rejected friend requests.
- **`blocks`**: Handles user blocking logic.

## License

This project is for educational purposes.
