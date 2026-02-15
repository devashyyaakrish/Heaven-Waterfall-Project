# JanSetu AI – System Design

## Problem

Citizens face difficulty in reporting public issues due to:
- Lack of awareness about where to complain
- Complex and slow government processes
- No centralized platform
- Language barriers

---

## Solution

JanSetu AI is an AI-powered public service helpdesk that:
- Enables easy complaint submission
- Automatically classifies issues using AI
- Assigns relevant government departments
- Provides scheme information and guidance
- Supports multilingual interaction

---

## System Architecture

User (Web App)
   ↓
React Frontend
   ↓
Firebase Authentication (Google Login)
   ↓
Node.js Backend (API Layer)
   ↓
AI Processing Layer (LLM API)
   ↓
MongoDB Database
   ↓
Authority Dashboard + Notification System

---

## Tech Stack

**Frontend:** React + Tailwind CSS  
**Backend:** Node.js + Express  
**Database:** MongoDB Atlas  
**Authentication:** Firebase Google Auth  
**AI:** LLM API (Nova-compatible / OpenAI)  
**Notifications:** Email API  
**Deployment:** Vercel + Render  

---

## AI Integration

AI is used to:
- Classify complaints (Road, Water, Electricity, etc.)
- Assign departments (PWD, Water Board, etc.)
- Detect priority (High / Medium / Low)
- Generate structured complaint text

Note: Architecture is compatible with Amazon Nova models via Bedrock.

---

## Workflow

1. User logs in via Google
2. User submits complaint
3. AI processes and classifies complaint
4. Department is assigned
5. Complaint stored in database
6. Notification sent (simulated)
7. Authority updates status

---

## Key Modules

- User Authentication
- Complaint Management
- AI Processing Engine
- Authority Dashboard
- Scheme Information Module

---

## Scalability

- Cloud-based deployment
- Modular API design
- AI abstraction layer (model-agnostic)
- Scalable database (MongoDB Atlas)
- Future AWS Bedrock integration

---

## Security

- OAuth-based authentication
- Token verification
- Secure API handling
- Environment variable protection

---

## Prototype Scope

- AI classification via API / lightweight model
- Authority notification simulated
- Government integration conceptual

---

## Future Scope

- Voice-based complaint system
- Full multilingual AI support
- Real government API integration
- Predictive analytics & heatmaps

---

## Conclusion

JanSetu AI simplifies citizen-government interaction using AI and cloud technologies, making grievance redressal faster, accessible, and scalable.
