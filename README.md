<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/dfafd81c-e052-41de-8f1f-e87e67661c4f" /># Node.js Authentication System

This project contains a complete authentication system using Node.js, Express, and MongoDB. It includes features like sign up, sign in, sign out, password reset, and social authentication (Google). The project is structured to be scalable with separate components for models, controllers, and routes.

## Live Site
[Click here](https://nodejs-authentication-system-l2pu.onrender.com/user/signin) to visit the live site.

## Features Implemented
- **Sign-up with Email**: Create an account using your email and password.
- **Sign-in**: Log into your account securely.
- **Sign Out**: Log out of your session.
- **Reset Password**: You can reset your passwords after signing in.
- **Encrypted Passwords**: Passwords are securely stored using encryption.
- **Google Login/Signup**: Sign in or sign up using your Google account.
- **Forgot Password**: Reset your password via email.
- **Password Strength Validation**: Notifications are displayed for unmatching passwords during sign up and incorrect passwords during sign in.
- **reCAPTCHA Integration**: Protects against bot traffic on sign up and login pages.

## Environment Variables

Before running the application locally, ensure you have set up the following environment variables in a .env file located at the root of your project:

1. **PORT**: Specifies the port number the application listens on.
2. **DB_URL**: MongoDB database connection URL.
3. **CLIENT_ID**: Google OAuth client ID.
4. **CLIENT_SECRET**: Google OAuth client secret (sign in with Google).
5. **EMAIL**: Email address for sending emails.
6. **PASSWORD**: App-specific password or regular password for the Gmail account.
7. **RECAPTCHA_SECRET_KEY**: Google reCAPTCHA secret key.
8. **CLIENT_URL**: URL to redirect after signing in with Google, e.g., "http://localhost:3000/auth/login/success".

Ensure that you have the appropriate values for each variable before running the application.

Example `.env` file:

```plaintext
PORT=3000
DB_URL=mongodb://localhost:27017/authdatabase
CLIENT_ID=your_client_id
CLIENT_SECRET=your_client_secret
EMAIL=your_email@gmail.com
PASSWORD=your_gmail_password
RECAPTCHA_SECRET_KEY=your_recaptcha_secret_key
CLIENT_URL=http://localhost:3000/auth/login/success
```

## Folder
  ```csharp
node-authentication/
├── config/                  # Configuration files
│   └── mongodb.js           # MongoDB configuration
│
├── controllers/             # Controller logic
├── models/                  # Database models
├── routes/                  # Route definitions
├── views/                   # EJS views
├── app.js                   # Express application setup
│
├── public/                  # Static assets
│
├── package.json             # NPM package configuration
├── README.md                # Project README file
├── .gitignore               # Git ignore configuration
└── .env                     # Environment variables file

```

## Installation and Setup

Follow these steps to run the project locally:


1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/nodejs-authentication-system.git
  
2. Navigate into the project directory:
   ```bash
   cd node-authentication-system
    ```
3. Install dependencies:
   ```bash
   npm install

4. Start the server:
   ```bash
   npm start
5. Open your web browser and visit http://localhost:3000 to access the application.

## Dependencies required

- Express.js
- MongoDB
- Passport.js
- bcrypt
- express-session
- express-ejs-layouts
- dotenv
- nodemailer

## Credits

This project was created by [Ravikant Singh](https://github.com/ravikantsingh12). Contributions via issues or pull requests are welcome!

## Follow me on

- [LinkedIn](https://www.linkedin.com/in/ravikant-singh-327a98241)

## TEST FUCNTION
### register in website
<img width="1917" height="1075" alt="image" src="https://github.com/user-attachments/assets/4f4ec168-d189-4d45-b790-60db93446eff" />

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/d1092282-c4e0-4bb8-833b-68c8b9fb1066" />

### After register, information of user store in mongodb

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/598282f9-0f34-4684-a08b-f227a88d9793" />

### Sign in with user account

<img width="1843" height="1035" alt="image" src="https://github.com/user-attachments/assets/7ad94a86-db03-4c1b-b9e8-efc2b6dd97e0" />

### Complete Sign in

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/63dcbdd9-d47a-4b64-951a-d79e74040d78" />

### Forgot password

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/65f61a70-f0bb-45ea-b568-d0643108129a" />

### New password is sent by email which set up

### Complete sign in with new password

### Sign in with google account

### Choose account google

### Complete sign in

### Change password

<img width="1911" height="1065" alt="image" src="https://github.com/user-attachments/assets/37acb7c8-456b-4d5b-a67c-6de320f5e7d3" />

<img width="1918" height="1068" alt="image" src="https://github.com/user-attachments/assets/c27807a7-941c-426d-a7e8-c36e4d00df6c" />

### Print alert password changed successfully

<img width="1905" height="1064" alt="image" src="https://github.com/user-attachments/assets/6cfa8255-a107-4a59-b6fb-38c31a42e869" />

### Complete sign in

<img width="1893" height="1050" alt="image" src="https://github.com/user-attachments/assets/09b689e8-323e-4f3d-9e3c-35aa682e1d9f" />

