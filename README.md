# 🚀 Smart Email Assistant

## ✨ Overview
The **Smart Email Assistant** is an AI-powered tool designed to generate intelligent email replies with ease. Built using **Spring Boot**, **Spring AI**, and **React**, it features a **Chrome Extension** that integrates seamlessly into Gmail, allowing users to craft responses effortlessly.

## 🌟 Features
- 🤖 **AI-Powered Email Generation**: Generates context-aware email responses based on user input.
- 📩 **Gmail Integration**: Works within Gmail via a Chrome extension for a smooth experience.
- 🎭 **Customizable Tone**: Choose from different tones (e.g., professional, casual, friendly) to match your communication style.
- 🛠 **REST API with Spring Boot**: Backend built using Spring Boot and integrated with Gemini API.
- 🖥 **User-Friendly UI**: Frontend developed using React with a sleek and intuitive interface.

## 🛠 Tech Stack
- **Backend**: Spring Boot, Spring AI, Gemini API
- **Frontend**: React, Material UI
- **Browser Extension**: Chrome Extension
- **Database**: PostgreSQL (Optional, if needed for future features)

## 🚀 Installation & Setup
### 📌 Backend (Spring Boot)
1. Clone the repository:
   git clone https://github.com/yourusername/smart-email-assistant.git
   cd smart-email-assistant/backend

2. Add your **OpenAI API key** in `application.properties`:
   openai.api.key=your_secret_key_here

3. Build and run the application:
   mvn clean install
   mvn spring-boot:run


### 📌 Frontend (React)
1. Navigate to the frontend directory:
   cd ../frontend
 
2. Install dependencies:
   npm install

3. Start the React development server:
   npm start


### 📌 Chrome Extension
1. Navigate to the `chrome-extension` folder inside the project.
2. Load the extension in Chrome:
   - Open `chrome://extensions/` in your browser.
   - Enable "Developer mode" (top-right corner).
   - Click "Load unpacked" and select the `chrome-extension` folder.

## 🎯 Usage
1. Enter the email content in the provided text box.
2. Choose the desired tone for the response.
3. Click "Generate Reply" to get an AI-generated response.
4. Copy the generated reply and use it in your email.
5. If using the Chrome extension, click the "Generate Reply" button directly within Gmail.

## 🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request. 

## 📜 License
This project is licensed under the **MIT License**.

## 📬 Contact
For any queries or suggestions, feel free to reach out via [your email/contact info].
