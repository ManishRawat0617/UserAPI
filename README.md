# REST API Authentication and Authorization

This project demonstrates a simple implementation of authentication and authorization using **Node.js**, **NeDB** (a lightweight embedded database), 
**JSON Web Tokens (JWT)**, **Two-Factor Authentication (2FA)** with TOTP, and **Bcrypt** for password hashing.

## Features:
- **User Registration**: Users can register by providing a name, email, and password.
- **User Login**: Users can log in with their credentials to receive an access token and refresh token.
- **2FA Support**: Supports Two-Factor Authentication (2FA) using TOTP via the Google Authenticator app.
- **Token Refresh**: Allows users to refresh their access tokens using a valid refresh token.
- **Role-Based Authorization**: Endpoints for different user roles such as "admin" and "moderator."
- **Token Revocation**: Users can log out, invalidating their access and refresh tokens.

## Prerequisites:
- **Node.js**: Make sure you have Node.js installed on your system.
- **NPM**: The Node package manager is required to install the dependencies.
- **NeDB**: Used as an embedded database for storing users, tokens, etc.


