# 🧑‍💻 Code Reviewer

Code Reviewer is a full-stack **AI-powered code review tool** built with React (frontend) and Node.js + Express (backend).  
It uses **Google Gemini API** to analyze source code and provide smart feedback, suggestions, and improvements.

---

## 📌 Features
- ✅ Paste or upload your code and get instant AI-powered reviews  
- ✅ Supports multiple programming languages  
- ✅ Highlights best practices, errors, and optimizations  
- ✅ Clean and responsive frontend built with React + Prism.js (syntax highlighting)  
- ✅ Backend powered by Express, integrated with Google Generative AI  
- ✅ Secure API key handling with `.env`  

---

## 🛠️ Tech Stack
**Frontend**
- React 19
- React DOM
- Vite
- PrismJS + React Simple Code Editor (code editor + syntax highlighting)
- React Markdown + Rehype Highlight (render reviews nicely)
- Axios (API requests)

**Backend**
- Node.js + Express
- Google Generative AI (`@google/generative-ai`)
- CORS
- dotenv

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/Code-reviewer.git
cd Code-reviewer
```

### 2️⃣ Setup Backend
```bash
cd backend
npm install
```

### Create a .env file inside backend/:
```bash
PORT=5000
GEMINI_API_KEY=your_google_gemini_api_key_here
```

### Start the backend:
```bash
node server.js
```


### 3️⃣ Setup Frontend
```bash
cd ../frontend
npm install
npm run dev
```

## Frontend will run at:
```bash
👉 http://localhost:5173 (default Vite)
```

## Backend runs at:
```bash
👉 http://localhost:5000
```

### Conclusion🤖
```bash
## 🛠️ Tech Stack
- **Frontend:** React, Vite, Axios, React Markdown, PrismJS, React Simple Code Editor
- **Backend:** Node.js, Express, Google Generative AI
- **Styling/Formatting:** PrismJS, rehype-highlight

## 📌 Usage
1. Start **backend** first (`node server.js`) → runs on `http://localhost:5000`
2. Then run **frontend** (`npm run dev`) → runs on `http://localhost:5173`
3. Paste your code in the editor, and the AI will generate a review with suggestions.

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

## 📜 License
This project is licensed under the MIT License.
```



