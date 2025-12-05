# LunaLearn — AI-Powered Study Companion 🌙
LunaLearn is an AI-driven study companion that helps decrease the barriers to learning through guided study sessions, smart explanations, summaries, and auto-generated flashcards. Built with React, TypeScript, Spring Boot, and PostgreSQL, it provides a calm, supportive workspace to help learners understand deeply and study more effectively.

# Table of Contents
- [Overview](#overview)
- [MVP Scope](#mvp-scope)
- [Future Enhancements](#future-enhancements)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)

# Overview
The goal of LunaLearn is to blend thoughtful, simple UX with AI-powered learning tools to make studying less overwhelming and more effective. Users can:

- Run **guided study sessions** with a Notion-style notes editor  
- Request **clear concept explanations**  
- Generate **summaries, quizzes, and flashcards**  
- Get support through **Stuck Mode** when overwhelmed  
- Build a personalized history of learning sessions

# MVP Scope
The MVP focuses on delivering a functional, end-to-end study experience with the essential tools needed for meaningful learning.

### **Main Dashboard**
- Welcome message/onboarding  
- “Resume Last Session” banner  
- Quick actions:
  - Start Study Session  
  - Explain Something  
  - Review Flashcards  
  - Enter Stuck Mode  
- Recent activity list

### **Study Session Workspace**
- Topic + goal display  
- Notion-style notes editor  
- Auto-save  
- AI tools:
  - Explain selected text  
  - Summarize notes  
  - Quiz me  
  - Generate flashcards  
- Reflection modal on session end

### **Explain Mode**
- Paste text to receive structured explanations  
- Follow-up actions:
  - Simplify  
  - Add examples  
  - Convert to flashcards  
  - Insert into session notes
 
### **Flashcards**
- Create sets manually or through AI  
- Review cards (flip, mark known/unknown)  
- Manage sets

### **Stuck Mode**
- User describes what they're struggling with  
- AI provides emotional support + micro-steps  
- Option to start a new study session from the response

### **Backend Functionality**
- CRUD for sessions, notes, flashcards  
- AI service integration  
- Minimal authentication or single-user mode for MVP  
- REST API with endpoints for core features

### **Deployment Setup**
- Frontend deployable
- Backend deployable
- Cloud-hosted PostgreSQL  
- Environment variables for configuration

# Future Enhancements
These features fall outside the scope of the MVP and will be added iteratively.

### **User Accounts & Authentication**
- Secure login/register  
- OAuth support (Google, GitHub)  
- Multi-user syncing  

### **Advanced Editor Features**
- PDF upload + AI explanation  
- Richer text formatting  
- Highlighting & tagging  
- Multiple notes per session  

### **Enhanced Learning Tools**
- AI-generated study plans  
- Mastery tracking  
- Spaced repetition system (SRS) for flashcards  
- Daily review workflow  

### **Improved Stuck Mode**
- Mood tracking  
- Gentle reminders  
- Adaptive tone  
- Resilience strategies  

### **Collaboration**
- Share sessions or flashcards  
- Peer/mentor mode

# Tech Stack
### **Frontend:**  
- React  
- TypeScript  
- React Router  
- CSS Modules / Styled Components  

### **Backend:**  
- Java 17+  
- Spring Boot  
- Spring Data JPA  
- OpenAI API  

### **Database:**  
- PostgreSQL  

### **Tooling:**  
- Docker  
- Maven/Gradle  

# Getting Started
Setup instructions will be added once scaffolding is complete.
