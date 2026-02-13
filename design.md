JanSetu AI – System Design Document

1. Introduction

JanSetu AI is an AI-powered full-stack web and mobile application designed to act as a digital helpdesk for government services. The platform enables citizens to report public issues, access welfare schemes, and receive AI-based assistance in local languages.

2. System Architecture
High-Level Architecture
Client (Web/App)
        ↓
API Gateway (Backend)
        ↓
AI Engine
        ↓
Database
        ↓
Authority Dashboard

Architecture Type:

REST-based Microservice Architecture

Cloud-native deployment

3. Technology Stack
Frontend:

React.js (Web)

Flutter (Mobile)

Tailwind CSS / Material UI

Backend:

Node.js

Express.js

AI & NLP:

Python

Transformers / NLP Models

Multilingual Translation Model

Database:

MongoDB (NoSQL)

Hosting:

AWS / Azure / GCP

Authentication:

OTP-based login

JWT Tokens

4. System Modules
4.1 User Module

Aadhaar/Mobile Login

Language Selection

Complaint Submission

Scheme Search

4.2 Complaint Management Module

Complaint categorization

Image upload

Geo-tagging

Status tracking

4.3 AI Engine Module

Complaint classification (NLP)

Department mapping

Complaint format generation

Language translation

4.4 Authority Module

Dashboard access

Complaint filtering

Status update

Analytics

5. Database Design
Collections:
Users

user_id

name

mobile

aadhaar_hash

preferred_language

Complaints

complaint_id

user_id

category

description

image_url

geo_location

assigned_department

status

timestamp

Schemes

scheme_id

name

eligibility

documents_required

application_process

6. AI Workflow

User submits complaint

Text sent to NLP model

Model detects category

Maps to appropriate department

Complaint formatted professionally

Backend forwards to authority

7. Security Design

Aadhaar stored in hashed format

OTP verification system

Role-based access control

Encrypted API communication (HTTPS)

Secure cloud storage

8. Scalability Strategy

Cloud-based deployment

Load balancer support

Horizontal scaling

Microservice architecture

Containerization using Docker

9. Data Flow Diagram (Conceptual)
User → Frontend → Backend → AI Engine → Database → Authority Dashboard

10. Future Enhancements

Voice-based complaint system

SMS integration for rural users

Predictive issue detection

Heatmap analytics

Integration with official government portals

11. Conclusion

JanSetu AI aims to bridge the gap between citizens and government authorities by leveraging AI, multilingual support, and automation to ensure transparent and efficient grievance redressal.
