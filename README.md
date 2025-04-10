# HABITUAL – Gamified Habit Tracker

This is a simple gamified habit tracker web app built using Java (Spring Boot), Gradle, and OAuth2 login with Google. The goal is to allow users to track habits across devices securely using OAuth login.

## Features

- Sign in with Google (OAuth2)
- Backend powered by Spring Boot
- Local database using H2
- .env support for managing credentials

## Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/PROGFINAL.git
   cd PROGFINAL
   ```
2. Create a .env file in the root:
   ```.env
   GOOGLE_CLIENT_ID=your-client-id
   GOOGLE_CLIENT_SECRET=your-client-secret
   ```
3. Run the app:
   ```bash
   ./gradlew :backend:bootRun
   ```

## Folder Structure
```githubexpressionlanguage
   PROGFINAL/
   ├── backend/        # Spring Boot backend
   ├── frontend/       # Frontend (React or HTML)
   ├── .env            # Your environment variables
   └── README.md       # This file
```

## To-Do
- Add frontend logic and UI 
- Persist habits and user data 
- Deploy to the cloud
