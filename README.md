# 🎭 AI Digital Human Generator

<div align="center">

![AI Digital Human Generator](https://img.shields.io/badge/AI-Digital_Human_Generator-6C63FF?style=for-the-badge&logo=ai&logoColor=white)

**Create Photorealistic Digital Humans with AI-Powered Speech, Emotions & Gestures**

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.104.0-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![Gemini AI](https://img.shields.io/badge/Gemini_AI-Google-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

</div>

---

## 📌 Table of Contents
- [🌟 Project Overview](#-project-overview)
- [✨ Key Features](#-key-features)
- [🏗️ Tech Stack](#-tech-stack)
- [📁 Project Structure](#-project-structure)
- [🚀 Getting Started](#-getting-started)
- [⚙️ Installation Guide](#-installation-guide)
- [🎯 Use Cases](#-use-cases)
- [🤝 Contributing](#-contributing)
- [📞 Support](#-support)
- [📜 License](#-license)

---

## 🌟 Project Overview

**AI Digital Human Generator** is an innovative web application that leverages cutting-edge artificial intelligence to create photorealistic digital humans with synchronized speech, facial expressions, gestures, and emotions. Powered by **Google's Gemini API** and optimized for **CPU-only environments**, this tool democratizes digital human creation for everyone.

### 🎯 Vision
To democratize AI-powered digital human creation by providing an accessible, intuitive platform that combines multiple AI technologies to generate lifelike virtual beings for various applications.

---

## ✨ Key Features

### 🎨 Human Generation
- **Photorealistic Avatars**: Create high-quality digital humans
- **Customizable Features**: Adjust age, gender, ethnicity, and style
- **Multiple Styles**: Realistic, Anime, Cartoon, and more
- **Instant Preview**: See changes in real-time

### 🗣️ Voice Synthesis
- **Text-to-Speech**: Convert text to natural-sounding speech
- **Multiple Languages**: Support for 50+ languages
- **Voice Customization**: Adjust pitch, speed, and accent
- **Lip Sync**: Automatic lip movement synchronization

### 😊 Facial Expressions
- **Emotion Library**: 8 basic emotions + custom expressions
- **Real-time Animation**: Smooth transitions between expressions
- **Intensity Control**: Adjust expression strength
- **Automatic Emotion Detection**: AI-powered emotion recognition

### 🤝 Gesture Animation
- **Natural Movements**: Realistic hand and body gestures
- **Speech Synchronization**: Gestures sync with speech
- **Custom Gestures**: Create and save custom gesture sequences
- **Animation Presets**: Ready-to-use gesture libraries

### 💾 Export & Share
- **Multiple Formats**: Save as images, videos, GIFs
- **High Resolution**: Export in 4K quality
- **Social Media Ready**: Optimized for various platforms
- **Share URL**: Generate shareable links

---

## 🏗️ Tech Stack

### Frontend
| Technology | Version | Purpose |
|------------|---------|---------|
| React | 18.2.0 | UI Framework |
| Vite | 4.5.0 | Build Tool |
| Three.js | 0.158.0 | 3D Rendering |
| Material-UI | 5.14.19 | UI Components |
| Axios | 1.6.2 | HTTP Client |
| Socket.io | 4.5.4 | WebSocket |
| React Router | 6.20.0 | Navigation |
| Framer Motion | 10.16.4 | Animations |

### Backend
| Technology | Version | Purpose |
|------------|---------|---------|
| FastAPI | 0.104.1 | Web Framework |
| Python | 3.9+ | Language |
| SQLAlchemy | 2.0.23 | ORM |
| PyTorch | 2.1.0 | ML Framework (CPU) |
| Transformers | 4.35.0 | NLP Models |
| Google Gemini | 0.3.0 | AI Integration |
| WebSockets | 11.0 | Real-time Communication |
| JWT | 3.3.0 | Authentication |

### Database
| Technology | Version | Purpose |
|------------|---------|---------|
| SQLite | 3.x | Development Database |
| PostgreSQL | 14+ | Production Database |

---

## 📁 Project Structure



---

## 🚀 Getting Started

### 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Python** 3.9 or higher
- **Node.js** 16.0 or higher
- **npm** 8.0 or higher
- **Git** (for cloning)
- **Gemini API Key** (free from Google AI Studio)

### 🔑 Get Gemini API Key

1. Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Sign in with your Google account
3. Click on "Create API Key"
4. Copy your API key
5. Save it securely

---

## ⚙️ Installation Guide

### Step 1: Clone the Repository

```bash
git clone https://github.com/vishakha2121/AI-Digital-Human-Generator.git
cd AI-Digital-Human-Generator


# Navigate to backend
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Create .env file
cp .env.example .env
# Edit .env and add your GEMINI_API_KEY

# Initialize database
python scripts/init_db.py

# Start backend server
uvicorn app.main:app --reload --host 0.0.0.0 --port 8000


# In a new terminal, navigate to frontend
cd frontend

# Install dependencies
npm install

# Create .env file
cp .env.example .env

# Start development server
npm run dev