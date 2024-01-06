# Image-Encryption-AES

Securely encrypt and decrypt images using the Advanced Encryption Standard (AES) algorithm. This project is designed for client-side image encryption and decryption, and it provides a server-side API for handling image storage and retrieval.

## Software Requirements

### Client-side (Sender and Receiver):
- **Operating System:** Windows, macOS, or Linux.
- **Web Browser:** Latest versions of popular browsers like Chrome, Firefox, Safari, or Edge.

### Server-side (Backend and Cloud Storage):
- **Operating System:** Linux distribution (Ubuntu, CentOS, etc.) or another suitable server OS.
- **Node.js:** Install the latest LTS (Long Term Support) version of Node.js for running the backend.
- **npm or Yarn:** Choose one of these package managers to install backend dependencies.
- **Express.js:** Web framework for building the backend API.
- **Crypto Libraries:** Libraries for implementing AES encryption and decryption.
- **Firebase Admin SDK:** Required if you are integrating with Firebase Cloud Storage. Set up a Firebase account and configure Firebase Admin SDK for your project.

### Cloud Storage:
- **Firebase Account:** To set up Firebase Cloud Storage and integrate it with your project.

### Usage:
- Sign in to your web application with valid credentials.
- Upload an image for encryption.
- Choose the encryption method (AES).
- Click "Encrypt" to secure your image.
- You can then decrypt and view the original image.
