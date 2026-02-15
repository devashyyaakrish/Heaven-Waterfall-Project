# 📋 JanSetu AI – Requirements

## 1. Overview

JanSetu AI is an AI-powered platform for:
- Reporting public issues
- Accessing government schemes
- Tracking complaint status

---

## 2. Functional Requirements

### Authentication
- User login via Google OAuth
- Secure session management

---

### Complaint Submission
- Submit complaint with:
  - Description
  - Image (optional)
  - Location
- Store complaint data

---

### AI Processing
- Classify complaint category
- Assign relevant department
- Detect priority level
- Generate structured complaint

---

### Complaint Management
- View submitted complaints
- Track complaint status
- Update complaint status (authority)

---

### Authority Dashboard
- View all complaints
- Filter by category
- Update status (Pending, In Progress, Resolved)

---

### Notification System
- Notify authority on complaint submission
- Email-based notification (prototype)

---

### Scheme Information
- Browse government schemes
- View eligibility and application details

---

## 3. Non-Functional Requirements

### Performance
- Response time < 3 seconds
- Fast AI processing

---

### Scalability
- Cloud-based architecture
- Scalable backend and database

---

### Security
- Secure authentication
- Protected APIs
- Encrypted sensitive data

---

### Usability
- Simple UI
- Mobile-friendly design
- Easy complaint submission

---

### Maintainability
- Modular codebase
- Easy feature extension

---

## 4. Constraints

- Aadhaar integration not included
- Government APIs simulated
- SMS replaced with email (prototype)

---

## 5. External Interfaces

- AI API (Nova-compatible / LLM)
- Firebase Authentication
- Email API
- MongoDB Atlas

---

## 6. Assumptions

- Users have internet access
- AI API is available
- Authorities can access dashboard

---

## 7. Future Requirements

- Voice input
- SMS notifications
- Government API integration
- Advanced AI models (Amazon Nova)
