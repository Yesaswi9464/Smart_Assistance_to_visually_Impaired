# Safe Steps – Assistive Navigation System

Safe Steps is a web-based assistive technology designed to help visually impaired users navigate their surroundings safely.  
The application uses **AI vision, voice commands, OCR, and navigation tools** to provide real-time assistance.

---

## Features

### 1. Live Object Detection
Uses **TensorFlow.js COCO-SSD** to detect objects through the device camera and highlight them in real time.

- Real-time camera feed
- Object detection boxes
- Voice description of detected objects

### 2. Navigation Aid
Allows users to navigate safely using **voice or text input**.

- Voice destination input
- Opens Google Maps walking navigation
- Uses GPS location

### 3. Document Reader
Reads printed text using **OCR (Optical Character Recognition)**.

- Upload an image
- Extract text using Tesseract.js
- Text-to-speech output

### 4. AI Assistant
A simple assistant that allows users to ask questions by typing or speaking.

### 5. Voice Control
Users can control the application using voice commands.

Example commands:
- "Live detection"
- "Navigation"
- "Reader"
- "Assistant"

### 6. SOS Emergency Button
A floating SOS button that sends an emergency message through WhatsApp.

---

## Technologies Used

- HTML5
- CSS3
- JavaScript
- TensorFlow.js
- COCO-SSD Model
- Tesseract.js (OCR)
- Web Speech API
- Web Camera API
- Geolocation API

---

## Project Structure
