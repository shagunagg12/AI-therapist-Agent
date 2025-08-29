# Aura 3.0 - Your AI Therapist Companion

Aura is a full-stack AI therapist and mental wellness companion designed to provide a safe and supportive space for users. This application features an interactive and calming user interface, mood tracking, engaging mini-games, and an intelligent chat feature powered by Google Gemini.

### ✨ Features

* **Calm & Soothing UI**: Aesthetically pleasing design with both light and dark modes to create a relaxing user experience.
* **Interactive Landing Page**: An engaging hero section with an emotion slider that dynamically changes the background theme.
* **User Authentication**: Secure sign-up, login, and logout functionality using JSON Web Tokens (JWT) and bcrypt for password hashing.
* **Personalized Dashboard**: A central hub for users to track their mood, view past entries, and access wellness activities.
* **Engaging Mini-Games**:
    * **Breathing Patterns**: Guided breathing exercises to help users relax.
    * **Zen Garden**: An interactive space for mindfulness and calm.
* **AI-Powered Chat**: A fully functional chat interface to converse with an AI therapist powered by Google Gemini, complete with typing indicators and message history.
* **Full-Stack Architecture**: Built with a modern tech stack:
    * **Frontend**: Next.js
    * **Backend**: Node.js with Express.js
    * **Database**: MongoDB Atlas
* **API Documentation & Testing**: Backend endpoints tested and documented using Echo API.
* **Cloud Deployment**: Seamless deployment with the backend on Render and the frontend on Vercel.

### 🛠️ Tech Stack

* **Frontend**: Next.js, React
* **Backend**: Node.js, Express.js
* **Database**: MongoDB, Mongoose
* **AI Integration**: Google Gemini
* **Authentication**: JWT, bcrypt.js
* **Deployment**: Vercel (Frontend), Render (Backend)
* **Background Tasks**: Ingest

### 🚀 Getting Started

**(You can add instructions here on how to clone and run the project locally)**

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/aura-3.0.git](https://github.com/your-username/aura-3.0.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd aura-3.0
    ```
3.  **Install dependencies (for both frontend and backend):**
    ```bash
    # In the root directory
    npm install

    # Or navigate to each folder (frontend/backend) and run npm install
    ```
4.  **Set up environment variables:**
    Create a `.env` file in the backend directory and add the necessary variables (e.g., MongoDB URI, JWT secret).
5.  **Run the development servers:**
    ```bash
    # Run the backend server
    npm run start:backend

    # Run the frontend server
    npm run dev:frontend
    ```

### 🤝 Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please feel free to open an issue or submit a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

### 📄 License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.
