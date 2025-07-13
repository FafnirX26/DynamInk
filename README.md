# DynamInc

> **DynamInc reads you while you read** - our AI instantly adapts text complexity, highlights what matters, and personalizes every paragraph based on your unique reading patterns. Reading reimagined.

## ✨ Features

- **🧠 Adaptive Text Intelligence**: Content automatically adjusts based on your reading speed and attention patterns
- **📊 Real-time Analytics**: Track WPM, dwell time, and content preferences across different text types
- **🎯 Smart Highlighting**: AI identifies and emphasizes plot-critical sentences and key information
- **📚 Personalized Experience**: Custom reading baselines and content adaptation per user
- **🔄 Dynamic Content Modes**: Switch between full text, condensed, summary, and auto-adaptive views
- **📈 Reading Statistics**: Comprehensive insights into your reading habits and preferences

## 🚀 Quick Start

### Prerequisites
- Python 3.9+
- Node.js 16+
- npm or yarn

### Backend Setup
```bash
cd backend
python -m venv bookplusai
source bookplusai/bin/activate  # On Windows: bookplusai\Scripts\activate
pip install -r requirements.txt
python -m uvicorn main:app --reload --port 8000
```

### Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

Visit `http://localhost:5173` to start reading!

## 🏗️ Architecture

- **Frontend**: React + TypeScript + Vite
- **Backend**: FastAPI + Python
- **Analytics**: Real-time reading behavior tracking
- **AI Content Analysis**: Text classification and adaptive rendering

## 📖 How It Works

1. **Reading Speed Calibration**: Take a quick reading test to establish your baseline
2. **Smart Content Loading**: Text loads progressively with basic content first, enhanced features follow
3. **Behavior Analysis**: Intersection Observer API tracks reading patterns in real-time
4. **Adaptive Rendering**: Content automatically adjusts based on your attention and speed
5. **Progress Tracking**: Reading history persists across sessions

## 🎯 Content Adaptation

- **Dialogue**: Enhanced when you read carefully, minimized when skimmed
- **Descriptions**: Expanded for slow readers, condensed for speed readers  
- **Action Sequences**: Emphasized for engagement-focused reading
- **Plot-Critical**: Always highlighted regardless of reading speed

## 📊 Analytics Dashboard

View detailed statistics including:
- Reading speed patterns by content type
- Attention levels and preferences
- Session analytics and progress tracking
- Personalized reading insights

## 🔧 Development

```bash
# Run backend
cd backend && python -m uvicorn main:app --reload --port 8000

# Run frontend  
cd frontend && npm run dev

# Both servers running:
# Backend: http://localhost:8000
# Frontend: http://localhost:5173
```

## 📄 License

MIT License - see LICENSE file for details

---

*Transform your reading experience with AI-powered adaptive text that learns from you.*