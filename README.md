
# **GenieAI 🧞‍♂️ – Your AI-Powered Chat Assistant**  

### **Overview**  
GenieAI is an interactive AI chatbot built using **React (frontend) and Node.js (backend)** that allows users to ask any question and receive intelligent responses. Powered by **OpenAI's API**, GenieAI can generate answers, summaries, and insights in real-time.

---

## 🚀 **Features**  
✅ AI-powered chatbot using OpenAI's GPT models  
✅ Clean and responsive UI built with **React & Tailwind CSS**  
✅ Secure backend integration with **Node.js & Express.js**  
✅ Supports **GPT-3.5 & GPT-4** models  
✅ Option to **clear** conversation history  
✅ Lightweight, fast, and easy to use  

---

## 🛠️ **Tech Stack**  

### **Frontend:**  
- React (Vite) ⚛️  
- Tailwind CSS 🎨  
- Fetch API for HTTP requests  

### **Backend:**  
- Node.js & Express.js 🌐  
- OpenAI API 🤖  
- CORS & dotenv for security  

---

## 📂 **Project Structure**  

```
GenieAI/
│── frontend/          # React frontend (Vite)
│   ├── src/
│   │   ├── components/  # UI components
│   │   ├── App.jsx      # Main React component
│   │   ├── main.jsx     # Entry point
│   │   ├── index.css    # Styling (Tailwind)
│   │   ├── vite.config.js # Vite configuration
│   ├── package.json     # Frontend dependencies
│   ├── .env             # Environment variables
│   ├── README.md        # Documentation
│
│── backend/           # Node.js backend
│   ├── server.mjs      # Express server
│   ├── .env            
│   ├── package.json    # Backend dependencies
│
│── public/            # Static assets
│── .gitignore         # Git ignore file
│── README.md          # Documentation
```

---
## 🎯 **How It Works**  

1️⃣ The user enters a question in the input field.  
2️⃣ The React frontend sends the query to the backend (`http://localhost:5001/api/chat`).  
3️⃣ The Node.js backend forwards the request to OpenAI’s API.  
4️⃣ OpenAI processes the request and returns a response.  
5️⃣ The response is displayed in the GenieAI chat interface.  

---


### **Deploying to Production**  
- **Frontend Deployment:** Deploy the frontend using **Vercel** or **Netlify**.  
- **Backend Deployment:** Deploy the backend on **Render, Railway, or Vercel**.  

---

## 🔥 **Future Improvements**  
✅ Save chat history using a database (MongoDB, Firebase)  
✅ Voice-to-text AI assistant integration 🎙️  
✅ User authentication (Login & Signup) 🔐  
✅ Multi-language support 🌍  

---

## 🎉 **Contributing**  
Want to improve GenieAI? Feel free to fork the repo and submit a pull request! 🚀  

---

### 🔗 **Connect with Me **  
👨‍💻 GitHub: https://github.com/JeevanKatiyar  
💬 LinkedIn: https://www.linkedin.com/in/jeevan-kumar-katiyar-a40382239/ 
📧 Email: Jeevankatiyar02@gmail.com

---
