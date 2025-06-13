# Interview-Screener

An AI-powered interview screening platform that leverages computer vision, natural language processing, and large language models to automate and enhance the interview process.

## 🚀 Technologies

### Frontend
- React.js
- Modern UI/UX design

### Backend
- Python with FastAPI
- RESTful API architecture

### Database
- MongoDB Atlas / Firebase

### AI/ML Components
- Computer Vision: OpenCV, MediaPipe
- Natural Language Processing: spaCy, Transformers (HuggingFace)
- Machine Learning: Scikit-learn
- LLM Integration: OpenAI/Gemini APIs

### Development Tools
- Version Control: GitHub
- IDE: VSCode with CoPilot or Cursor
- Design: Figma
- Authentication: Firebase Auth / OAuth
- Deployment: Vercel/Render

## 🛠️ Setup Instructions

### Prerequisites
- Python 3.x
- Node.js and npm
- Git

### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/ACM-Codify/Interview-Screener.git
   cd Interview-Screener
   ```

2. Create and activate a virtual environment:
   ```bash
   # For Linux/Mac
   python3 -m venv interview_project
   source interview_project/bin/activate

   # For Windows
   python3 -m venv interview_project
   interview_project\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Start the backend server:
   ```bash
   uvicorn backend.main:app --reload
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

## 🤝 Contributing

1. Create a new branch with your name:
   ```bash
   git checkout -b your-name
   ```

2. Make your changes and commit them:
   ```bash
   git add .
   git commit -m "Description of your changes"
   ```

3. Push your changes to your branch:
   ```bash
   git push origin your-name
   ```

4. Create a Pull Request (PR) to the main branch

## 📝 Project Structure
```
Interview-Screener/
├── backend/
│   ├── main.py
│   └── requirements.txt
├── frontend/
│   ├── src/
│   └── package.json
└── README.md
```

## 🔑 Environment Variables
Create a `.env` file in the root directory with the following variables:
```
OPENAI_API_KEY=your_api_key
GEMINI_API_KEY=your_api_key
MONGODB_URI=your_mongodb_uri
```