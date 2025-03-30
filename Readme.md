# Email Writer AI Assistant

## Overview
Email Writer AI Assistant is a web-based application that generates email replies based on the given content and tone. It simplifies the process of drafting professional, casual, or friendly email responses using AI.

## Features
- Accepts email content as input.
- Allows users to select a tone (professional, casual, friendly, etc.).
- Generates AI-powered email replies.
- Provides a simple UI for input and result display.
- Option to copy the generated email to the clipboard.

## Technologies Used
### Frontend
- React.js with Material UI for a responsive UI.

### Backend
- Spring Boot (Java) for API development.
- REST API for handling email content and tone selection.
- AI-based response generation.

## Installation and Usage

### Prerequisites
- Node.js and npm (for frontend)
- Java and Spring Boot (for backend)

### Backend Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/ashutosh4036/email-writer-ai-assistant.git
   cd email-writer-ai-assistant
   ```
2. Navigate to the backend folder and run the Spring Boot application:
   ```sh
   cd backend
   mvn spring-boot:run
   ```
3. The backend should now be running on `http://localhost:8080`.

### Frontend Setup
1. Navigate to the frontend folder:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React development server:
   ```sh
   npm start
   ```
4. Open `http://localhost:3000` in your browser.

## API Endpoints
- `POST /api/email/generate` - Generates an AI-powered email reply based on input content and tone.

## Usage Example
1. Enter an email body into the provided text field.
2. Select a tone from the dropdown.
3. Click "Generate Reply" to get an AI-generated response.
4. Copy the response using the "Copy to Clipboard" button.

## License
This project is licensed under the MIT License.

## Author
Ashutosh Tripathi

