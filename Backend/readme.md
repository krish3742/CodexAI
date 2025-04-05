# CodexAI Backend

This is the backend service for the **CodexAI** application. It is built with **Node.js**, **Express.js**, and integrates with the **Google Gemini API** to provide intelligent code suggestions, explanations, and more.

---

## Features

- **AI-Powered Endpoints**: Interacts with OpenAI's API for code generation, explanation, and refactoring.
- **Secure API Integration**: Uses environment variables to securely manage API keys.
- **Error Handling**: Comprehensive and consistent API error responses.
- **CORS Support**: Configured to allow secure communication with the frontend.

---

## Tech Stack

- **Backend**: Node.js, Express.js
- **AI Integration**: Google Gemini API
- **Environment Management**: dotenv
- **Middleware**: CORS, Express JSON

---

## Installation

1. **Install dependencies:**

   ```bash
   npm install
   ```

2. **Configure environment variables:**

   Create a `.env` file in the `backend/` directory and add the following:

   ```env
    GOOGLE_GEMINI_KEY=Your_Key
    CORS_ORIGIN_URL=Frontend_URL
   ```

3. **Start the server:**

   ```bash
   npm start
   ```

---

## API Endpoints

- **POST** `/ai/get-review` - Returns an AI-generated explanation for the provided code snippet.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
