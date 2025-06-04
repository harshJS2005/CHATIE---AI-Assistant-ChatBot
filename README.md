# 💬 AI Chat Interface (Gemini API-based Chatbot)

This is a simple, responsive web-based chatbot interface that communicates with Google's **Gemini API** (`gemini-2.0-flash`). It supports both text input and image upload (Base64-encoded), allowing rich, AI-powered conversational interactions.

## 🚀 Features

- Clean and modern **chat UI** with a left-right conversation layout
- **AI responses** powered by Google Gemini API
- **Image support**: users can upload images and send them with messages
- Responsive design for mobile and desktop
- Scroll-to-bottom chat auto-navigation
- Loading animation while waiting for AI response

---

## 🧰 Technologies Used

- **HTML5** – Structure of the chat app
- **CSS3** – Styling with media queries and animations
- **JavaScript** – Chat logic, API calls, event handling
- **Google Gemini API** – AI response engine

---

## 📁 Project Structure


---

## 🧠 How It Works

1. **User sends a message** using the text input or image upload.
2. The message is displayed in the chat as a user bubble.
3. A loading message appears from the AI side.
4. A `POST` request is sent to the Gemini API using `fetch`.
5. The AI's response is extracted and displayed in the AI bubble.
6. The chat auto-scrolls to the bottom.

---

## 🔧 Setup Instructions

1. Clone or download this repository.
2. Replace the `API_KEY` in this line in `index.html`:
   ```js
   const Api_Url = "https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=YOUR_API_KEY_HERE"
   
📝 Notes
You must have a valid Gemini API key from Google AI Studio.

The uploaded image is converted to Base64 and sent as inline content.

This version does not support voice or audio inputs.

🧪 Future Improvements

Chat history saving

Markdown rendering

Multi-turn conversations

Error handling UI

Dark/light mode toggle
