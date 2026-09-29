# Key system

A lightweight, web-based authentication and key generation system built with HTML, CSS, and JavaScript.

## Features
- **Admin Panel (`admin.html`):** Generate unique system keys stored in `localStorage`.
- **Key Verification (`key.html`):** Validate access keys and update session states.
- **Protected Dashboard (`dashboard.html`):** Protected content area with automatic redirection if not authenticated via valid session.

## Tech Stack
- HTML5
- CSS3
- JavaScript (LocalStorage & SessionStorage)

## How to Test
1. Open `admin.html` to generate a new key.
2. Copy the generated key.
3. Open `key.html`, paste the key, and click Login.
4. You will be redirected to the protected `dashboard.html`.
