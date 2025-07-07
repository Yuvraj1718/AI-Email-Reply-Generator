# AI Email Reply Generator

A full-stack application that generates professional email replies using Google’s Gemini API, based on user input and selected tone.

## 🔧 Technologies Used
- **Backend:** Spring Boot, WebClient, Jackson
- **Frontend:** React.js, Material UI, Axios
- **Extension:** Chrome Extension (Manifest V3)
- **AI Integration:** Gemini API

## ✨ Features
- Generate AI-based replies from email content with selectable tone (e.g., professional, casual)
- Spring Boot REST API for processing requests and parsing Gemini responses
- React frontend for input form, tone selection, and displaying results
- Chrome Extension injects "AI Reply" button directly into Gmail’s compose box

## 🚀 Getting Started

### Backend (Spring Boot)
1. Navigate to `/email-writer-sb`
2. Configure `application.properties` with Gemini API key and URL
3. Run the Spring Boot application

### Frontend (React)
1. Navigate to `/email-writer-react`
2. Install dependencies: `npm install`
3. Start the dev server: `npm run dev`

### Chrome Extension
1. Navigate to `/email-writer-ext`
2. Open Chrome > Extensions > Enable Developer Mode
3. Load unpacked extension from this folder
4. Use in Gmail to generate replies directly in the compose window
