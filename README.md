# 🧠 NeuroNews — AI-Enhanced News Platform

NeuroNews is a full-stack, AI-powered news platform built as my Semester 6 BSc Computer Science project.  

The goal was to create a smarter way to discover, track, and engage with news using modern backend architecture and AI-driven features.

This project was designed and developed independently, covering everything from backend APIs and authentication to real-time systems and AI model integration.

⚠️ **Note:** The source code for this project is private. This repository is intended to document the design, features, and technical learnings.

---

## 🎯 Project Objectives

- Build a scalable MERN-based news platform with secure authentication  
- Design robust REST APIs and real-time communication  
- Integrate AI models for intelligent content processing  
- Gain end-to-end full-stack development experience  

---

## 🚀 Key Features

### 🔐 Secure Authentication

- OTP-based user registration and login  
- Email verification using Nodemailer  
- JWT-based authentication for login and all client requests  

---

### 🏠 Intelligent News Dashboard

- Homepage displaying top headlines  
- Category-based filtering (Science, Sports, Technology, etc.)  
- Data aggregated from multiple third-party News APIs  

---

### 🔍 Smart Search & News Reminders

- Search news using natural language prompts  

**Example:**  
“Tell me if there’s news about Tata stock”

- Users receive email notifications when relevant news appears later  
- Dedicated reminders section to view and manage saved alerts  

---

### 📬 Reminder Management

- View all saved reminders  
- Delete reminders directly from the dashboard  
- Structured storage for fast access  

---

### 🌐 Chrome Extension + Real-Time System

When a user opens a news article on the original publisher’s website:

- A custom Chrome extension activates  
- Establishes a WebSocket connection with the backend  
- Backend uses web scraping to fetch related YouTube videos in real time  
- Enhances user engagement without leaving the news context  

---

### 🤖 AI-Powered News Categorization

- Many news APIs lack proper category tagging  
- Implemented Facebook BART model via Flask (Python) to classify news articles based on content  
- Enabled accurate categorization across all sources  

---

### 🧠 Keyword Extraction & Optimized Storage

- Extracted relevant keywords from articles  
- Stored news in MongoDB, organized by:
  - Date  
  - Category  
  - Keywords  
- Designed for fast querying and scalability  

---

## 🛠️ Tech Stack

**Frontend**
- React.js  

**Backend**
- Node.js  
- Express.js  
- MongoDB  

**AI & Data Processing**
- Flask (Python)  
- Facebook BART Model  

**Real-Time & Automation**
- WebSockets  
- Puppeteer (Web Scraping)  

**Other Tools**
- Nodemailer  
- JWT Authentication  
- Chrome Extension  

---

### 3 Third-Party News APIs Used

- News.org  
- NewsAPI  
- GNews API  

---

## 🧩 System Architecture (High-Level)

- MERN stack for core application  
- Flask Server for AI-based categorization  
- WebSockets for real-time browser–backend communication  
- MongoDB for structured, efficient data storage  

---

## 📸 Project Screenshots

### Homepage

<img width="1218" height="605" alt="Screenshot 2025-06-04 023321" src="https://github.com/user-attachments/assets/97dc79e1-b7f4-4a62-b248-42ff2fae01fc" />

---

### Cetegories Menu

<img width="1198" height="583" alt="Screenshot 2025-06-04 023405" src="https://github.com/user-attachments/assets/5c0292f8-bb1b-475b-8baa-f19ccf78b53a" />

---

### Specific Category Page (Science)

<img width="1336" height="657" alt="Screenshot 2025-06-04 023443" src="https://github.com/user-attachments/assets/c6fdb57b-fb30-43fd-9ae6-6f9a0e09548b" />

---

### Chrome extension in action

<img width="1052" height="581" alt="Screenshot 2025-06-04 023541" src="https://github.com/user-attachments/assets/21f7f1c1-1853-4ff2-a71e-cd49460de50b" />

---

## 📚 Key Learnings

- Backend architecture and REST API design  
- Secure authentication and authorization  
- Real-time communication using WebSockets  
- Integrating AI models into full-stack applications  
- Designing systems for scalability and maintainability  
- Working independently on a production-like project  
