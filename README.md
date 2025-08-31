AI Study Buddy 🧠
A simple, serverless web application that answers any question by connecting to Google's Gemini Large Language Model (LLM) via an API. This project demonstrates the full lifecycle of an AI application, from front-end development to deployment and API key management.

➡️ https://dp-93.github.io/AI-Study-Buddy-Chatbot/


🚀 Features
Ask Anything: Users can input any question into a text box.

Real-Time Answers: Receives and displays answers directly from the Gemini LLM.

Clean UI: Simple, responsive interface built with HTML and Tailwind CSS.

Loading & Error States: Provides clear feedback to the user while the model is thinking or if an error occurs.

🛠️ Tech Stack
Front-End: HTML, CSS, JavaScript

Styling: Tailwind CSS

AI Model: Google Gemini API (gemini-2.5-flash-preview-05-20)

Deployment: GitHub Pages

☁️ Deployment & Security
This application is a serverless, front-end-only project, which presents a unique security challenge for API keys.

Hosting: The application is hosted for free using GitHub Pages, serving the static index.html file directly.

API Key Management:

The Google Gemini API key is embedded in the public JavaScript code. GitHub's Secret Scanning automatically detects this and raises a security alert.

To secure the project, the API key in the Google Cloud Console was restricted to prevent misuse, though for this public demo, restrictions were temporarily lifted to ensure functionality.

The security alert on GitHub was acknowledged and closed, accepting the risk for this public-facing portfolio project.

This project was a practical exercise in managing the real-world trade-offs between security and functionality for client-side web applications.
