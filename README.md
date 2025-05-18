# Quri
**Quri** is a full-stack AI-powered voice interface designed for effortless consumption of newsletters. It lets users **listen, take notes, search the web, and interact—all through voice commands**, without touching their screens.

Voice-based AI interface for consuming newsletters hands-free. Aggregated repo linking Quri's iOS frontend, email processing backend, and real-time voice agent.



This repository aggregates the core components of Quri, spanning frontend and backend services.
---

## 🎥 Demo

> ▶️ [Watch the Quri Demo Video](https://youtu.be/VoiCGiHXJsw)  
Shows real-time voice interaction with newsletters, note-taking, and app navigation.

---

## 🔗 Project Structure

| Module | Description |
|--------|-------------|
| [Frontend – Swift iOS App](https://github.com/Vikhyat05/QuriIOS-Frontend) | iOS app built with Swift and SwiftUI, enabling voice-based navigation and interaction |
| [Backend – Email Processing Service](https://github.com/Vikhyat05/QuriEmailProcessing-Backend) | FastAPI service that parses emails, extracts newsletters, and prepares content for AI interaction |
| [Backend – Real-Time Voice Agent](https://github.com/Vikhyat05/QuriEmailProcessing-Backend) | Handles LLM integration, WebSocket-based communication, and real-time voice response using TTS/STT pipelines | AI Memory Managment 

---


## 🚀 Technologies Used

- **Frontend**: SwiftUI (iOS), Core Data for local persistence and Keychain for secure storage
- **Backend**: FastAPI (Python), WebSockets (websockets library), WebRTC
- **Database**: Supabase (PostgreSQL)
- **Authentication**: Google OAuth; Supabase
- **Custom Audio Pipeline**: AVFoundation and AVAudioEngine with custom WebSocket channels for live audio input/output, with dynamic STT and TTS integration
- **AI/ML**: Hume TTS, OpenAI GPT models (text generation, transcription)
- **Integrations**: Gmail API and BeautifulSoup for inbox access , email actions and email content parsing

