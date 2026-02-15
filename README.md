# JanSetu AI – Smart Public Issue Reporting & Assistance Platform

 JanSetu AI is an AI-powered digital platform that enables citizens to report public infrastructure issues, access government services, and receive guided assistance — all in one place.

---

## Problem Statement

Citizens often face difficulty in:
- Reporting civic issues (roads, sanitation, water, etc.)
- Identifying the correct government authority
- Accessing government schemes and services
- Communicating effectively in local languages

This leads to unresolved issues, lack of awareness, and inefficient governance.

---

## Solution

JanSetu AI acts as a **digital helpdesk for public services** by combining:

-  Issue reporting with AI assistance
-  AI-powered complaint classification & guidance
-  Location-based authority routing
-  Multilingual support
-  Real-time status tracking
-  Government scheme discovery

---

##  Features

###  User Authentication
- Google OAuth login
- Secure and simple onboarding

###  Issue Reporting
- Upload description + images
- Auto-classification using AI
- Suggests proper reporting method

###  AI Assistant
- Guides users on how to report issues
- Provides info on schemes like:
  - MNREGA
  - Ayushman Bharat
  - Education programs

###  Smart Routing
- Detects user location
- Routes complaint to relevant authority

###  Notification System
- Sends alerts to authority (dummy for prototype)
- Tracks complaint status

###  Multilingual Support
- Supports regional languages for accessibility

---

##  Tech Stack

### Frontend
- React / Next.js
- Tailwind CSS

### Backend
- Node.js / Express.js
- REST API architecture

### Database
- MongoDB (Atlas)

### AI Integration
- Amazon Nova / OpenAI API
- NLP-based classification & chatbot

### Authentication
- Google OAuth (Firebase/Auth0)

### Cloud & Deployment
- AWS (EC2 / S3 / Lambda)
- Firebase (optional)

---

##  System Architecture
User (Web/App)
↓
Frontend (React / Next.js)
↓
Backend API (Node.js)
↓
AI Engine (Nova / OpenAI)
↓
Database (MongoDB)
↓
Notification Service (SMS / Email / Dummy API)

---

##  How It Works

1. User logs in via Google
2. Reports an issue with description/image
3. AI classifies the issue and suggests action
4. System identifies authority based on location
5. Complaint is logged and notification is sent
6. User tracks progress via dashboard

---

##  Use Cases

- Reporting road damage or construction delays
- Accessing healthcare schemes
- Finding employment programs
- Educational assistance
- Public grievance redressal

---

##  Future Enhancements

- Real government API integration
- Automated authority escalation
- Voice-based reporting
- Real-time tracking with maps
- Integration with smart city platforms

---

##  Hackathon Value

- Solves real-world civic problems
- Scalable for Smart Cities
- AI-driven governance support
- Inclusive and accessible design

---

##  Team

- Devashya Kothari (Team Leader)
- Arnav Aghniotri
- Mayank Vishvas
- Lakshya Panwar

---

##  Note

This is a prototype developed for the **Amazon Nova National Hackathon**.  
Actual government integration is simulated.

