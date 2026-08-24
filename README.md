# 🎭 AI Digital Human Generator

<div align="center">

![AI Digital Human Generator Banner](https://via.placeholder.com/1200x300/6C63FF/FFFFFF?text=AI+Digital+Human+Generator)

**Create Photorealistic Digital Humans with AI-Powered Speech, Emotions & Gestures**

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.104.0-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![Gemini AI](https://img.shields.io/badge/Gemini_AI-Google-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

[![GitHub Stars](https://img.shields.io/github/stars/yourusername/AI-Digital-Human-Generator?style=social)](https://github.com/yourusername/AI-Digital-Human-Generator/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/yourusername/AI-Digital-Human-Generator?style=social)](https://github.com/yourusername/AI-Digital-Human-Generator/network/members)
[![GitHub Issues](https://img.shields.io/github/issues/yourusername/AI-Digital-Human-Generator)](https://github.com/yourusername/AI-Digital-Human-Generator/issues)

</div>

---

## 📌 Table of Contents
- [🌟 Project Overview](#-project-overview)
- [✨ Key Features](#-key-features)
- [🏗️ Architecture](#-architecture)
- [📊 Tech Stack](#-tech-stack)
- [🚀 Getting Started](#-getting-started)
- [⚙️ Installation Guide](#-installation-guide)
- [💻 Usage Guide](#-usage-guide)
- [🎨 Screenshots](#-screenshots)
- [📁 Project Structure](#-project-structure)
- [🧠 AI Models & APIs](#-ai-models--apis)
- [📡 API Documentation](#-api-documentation)
- [🎯 Use Cases](#-use-cases)
- [🛠️ Development Guide](#-development-guide)
- [🧪 Testing](#-testing)
- [🚢 Deployment](#-deployment)
- [🤝 Contributing](#-contributing)
- [📞 Support](#-support)
- [📜 License](#-license)
- [🙏 Acknowledgments](#-acknowledgments)

---

## 🌟 Project Overview

**AI Digital Human Generator** is a revolutionary web application that leverages cutting-edge artificial intelligence to create photorealistic digital humans with synchronized speech, facial expressions, gestures, and emotions. Powered by **Google's Gemini API** and optimized for **CPU-only environments**, this tool democratizes digital human creation for everyone.

### 🎯 Vision
To democratize AI-powered digital human creation by providing an accessible, intuitive platform that combines multiple AI technologies to generate lifelike virtual beings for various applications.

### 🌍 What Makes This Project Special?

- **🤖 CPU-Optimized**: No GPU required - runs efficiently on regular computers
- **🔌 Gemini AI Integration**: Powered by Google's most advanced AI
- **🎨 Complete Solution**: End-to-end pipeline from generation to animation
- **💰 Cost-Effective**: Free tier of Gemini API available
- **🚀 Quick Setup**: Get started in minutes with our streamlined installation

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

### 🔄 Real-time Features
- **Live Preview**: See changes instantly
- **WebSocket Integration**: Real-time updates
- **Responsive UI**: Works on all devices

---

## 🏗️ Architecture

### High-Level Architecture

### System Components

1. **Frontend Layer** (React)
   - UI Components
   - State Management
   - API Integration
   - Real-time Updates

2. **Backend Layer** (FastAPI)
   - RESTful APIs
   - WebSocket Server
   - Business Logic
   - Authentication

3. **AI Layer** (Gemini + ML)
   - Human Generation
   - Voice Synthesis
   - Emotion Detection
   - Animation Processing

4. **Database Layer** (SQLite)
   - User Management
   - Content Storage
   - Session Management

---

## 📊 Tech Stack

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
| Chart.js | 4.4.1 | Analytics Charts |

### Backend
| Technology | Version | Purpose |
|------------|---------|---------|
| FastAPI | 0.104.1 | Web Framework |
| Python | 3.9+ | Language |
| SQLAlchemy | 2.0.23 | ORM |
| Uvicorn | 0.24.0 | ASGI Server |
| PyTorch | 2.1.0 | ML Framework (CPU) |
| Transformers | 4.35.0 | NLP Models |
| Diffusers | 0.24.0 | Image Generation |
| Google Gemini | 0.3.0 | AI Integration |
| WebSockets | 11.0 | Real-time Communication |
| JWT | 3.3.0 | Authentication |
| Passlib | 1.7.4 | Password Hashing |

### Database
| Technology | Version | Purpose |
|------------|---------|---------|
| SQLite | 3.x | Development Database |
| PostgreSQL | 14+ | Production Database |
| SQLAlchemy | 2.0.23 | ORM |

### DevOps
| Technology | Version | Purpose |
|------------|---------|---------|
| Docker | Latest | Containerization |
| Docker Compose | Latest | Multi-container |
| Git | Latest | Version Control |
| GitHub Actions | Latest | CI/CD |

---

## 🚀 Getting Started

### 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Python** 3.9 or higher
- **Node.js** 16.0 or higher
- **npm** 8.0 or higher
- **Git** (for cloning)
- **SQLite** (included with Python)
- **Gemini API Key** (free from Google AI Studio)

### 🔑 Get Gemini API Key

1. Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Sign in with your Google account
3. Click on "Create API Key"
4. Copy your API key
5. Save it securely (will be used in .env file)

---

## ⚙️ Installation Guide

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/AI-Digital-Human-Generator.git
cd AI-Digital-Human-Generator

# Navigate to backend directory
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Create .env file
cp .env.example .env
# Edit .env and add your GEMINI_API_KEY

# Initialize database
python scripts/init_db.py

# Run database migrations
python scripts/run_migrations.py

# Start backend server
uvicorn app.main:app --reload --host 0.0.0.0 --port 8000

# Navigate to frontend directory (in a new terminal)
cd frontend

# Install dependencies
npm install

# Create .env file
cp .env.example .env

# Start development server
npm run dev#   A I - D i g i t a l - H u m a n - G e n e r a t o r  
 