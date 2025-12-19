
# AyurVardan

AyurVardan is a comprehensive healthcare application designed to connect patients with Ayurvedic doctors, providing a seamless and holistic approach to wellness. The platform offers distinct, feature-rich interfaces for both patients and doctors, facilitating personalized consultations, diet planning, and health monitoring.

## Features

### For Patients

- **User Authentication:** Secure sign-up and login functionality.
- **Personalized Dashboard:** A comprehensive overview of upcoming appointments, health metrics, and personalized recommendations.
- **Ayurvedic Profile:** An integrated questionnaire to determine the user's Prakriti and Vikriti, offering deeper insights into their mind-body constitution.
- **Health Tracking:** Sync with Google Health to monitor live vitals, track menstrual cycles, and calculate BMI.
- **Consultations:**
  - Find doctors (both online and nearby).
  - Book and manage appointments.
  - Engage in real-time chat with doctors.
  - Initiate video and audio calls.
- **Diet Planning:** Receive and view personalized diet plans from doctors.
- **Yoga Asanas:** Access a library of yoga asanas tailored to the user's Ayurvedic profile.
- **E-commerce:** Browse and purchase Ayurvedic products from the integrated shop.
- **Community Hub:** Engage with other users, share experiences, and learn from the community.
- **AI Chatbot:** Get instant answers to general Ayurvedic questions from an AI-powered assistant.

### For Doctors

- **Secure Login:** A separate login portal for doctors.
- **Patient Management:**
  - View a list of all assigned patients.
  - Access detailed patient dashboards with health records and history.
- **Chat & Consultation:**
  - Chat directly with patients.
  - Initiate video and audio calls.
- **Diet Plan Generation:**
  - Create and send customized diet plans.
  - Leverage an AI-powered recipe generator to create meals based on the patient's diet.
- **Recipe Library:** View and manage AI-generated recipes.

## Tech Stack

- **Frontend:** React, TypeScript, Vite
- **UI:** Recharts for charts
- **AI:** Google Generative AI (Gemini)

## Run Locally

**Prerequisites:** Node.js

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   ```
2. **Navigate to the project directory:**
   ```bash
   cd ayur-vardan
   ```
3. **Install dependencies:**
   ```bash
   npm install
   ```
4. **Set up environment variables:**
   - Create a `.env.local` file in the root of the project.
   - Add your Gemini API key to the file:
     ```
     GEMINI_API_KEY=your_api_key
     ```
5. **Run the app:**
   ```bash
   npm run dev
   ```

## Project Structure

```
ayur-vardan/
├── components/      # Reusable UI components
├── data/            # Mock data for the application
├── views/           # Main views for different parts of the app (Doctor, Patient, etc.)
├── App.tsx          # Main application component
├── index.tsx        # Entry point of the application
├── types.ts         # TypeScript type definitions
├── package.json     # Project dependencies and scripts
└── vite.config.ts   # Vite configuration
```
