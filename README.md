# Fitness-Training-Center-Management-System
BRD (Business Requirement Document) --> Use Case SRS (System Requirement Specification) --> Activity Diagrams (Drawio) --> Class Diagram (Drawio) --> Collaboration Diagrams (Drawio) --> Sequence Diagrams (Drawio) --> State Diagrams --> Wireframe (Figma)

---

## Overview

The **Fitness Training Center Management System** is a comprehensive, end‑to‑end solution designed to automate and optimize every aspect of a modern fitness facility. By unifying **Administrators**, **Coaches**, and **Members** on a single platform, the system:

- Eliminates manual paperwork and data entry  
- Streamlines scheduling, billing, and reporting  
- Delivers AI‑driven personalization for workouts and nutrition  

---

## Key Features

**1. Member Management**  
- Registration, profile maintenance, and subscription handling  
- Session booking, waitlist management, attendance tracking  
- Progress monitoring with AI‑personalized workout and nutrition plans  

**2. Coach Management**  
- Work schedule creation and adjustment  
- Performance tracking, time logs, and leave records  
- Certification and specialization management  

**3. Session & Subscription Management**  
- Booking, modification, and cancellation of training sessions  
- Automated waitlist processing and notifications  
- Support for online payments (credit card, e‑wallet) and cash transactions  

**4. Administrator Dashboard**  
- Financial reporting with integration to accounting systems (QuickBooks, Xero)  
- HR integration (BambooHR, Workday) for coach data management  
- Facility scheduling, resource allocation, and expense tracking  

**5. AI‑Powered Recommendations**  
- Automatic generation and iterative updates of workout and nutrition programs  
- Adaptive insights based on member progress and coach feedback  

**6. Notification System**  
- Scheduled reminders for sessions, renewals, and system updates  
- Multi‑channel delivery via in‑app alerts, email, and SMS  

---

## Technology Stack

| Layer           | Technology                        |
| --------------- | --------------------------------- |
| **Frontend**    | React (Web), Flutter (Mobile)     |
| **Backend**     | Laravel                           |
| **Database**    | MySQL                             |
| **Cloud Infra** | AWS / Azure / Google Cloud        |
| **APIs**        | RESTful services                  |
| **Integrations**| Stripe (payments), Firebase (push), Twilio (SMS) |

---

## Repository Structure

```plaintext
├── documents/                         # Project Documentation
│   ├── BRD.pdf                        # Business Requirement Document
│   ├── SRS.pdf                        # System Requirement Specification
│   ├── Use_Case_Diagrams/            # Use Case Diagrams (Draw.io)
│   ├── Activity_Diagrams/            # Activity Diagrams (Draw.io)
│   ├── Class_Diagram/                # Class Diagram (Draw.io)
│   ├── Sequence_Diagrams/           # Sequence Diagrams (Draw.io)
│   ├── Collaboration_Diagrams/      # Collaboration Diagrams (Draw.io)
│   └── State_Diagrams/              # State Diagrams (Draw.io)
│
└── wireframes/                       # UI Wireframes
    ├── Admin.png
    ├── Client.png
    ├── Scheduling Manager.png
    ├── Financial Manager.png
    └── Coach.png
```
---

## Documentation Highlights

> **BRD & SRS**  
> Full descriptions of functional and non‑functional requirements, tailored for stakeholders and developers.

> **Use Cases**  
> Fifteen detailed scenarios covering registration, scheduling, payments, AI updates, notifications, and more.

> **UML Diagrams**  
> Complete set: Activity, Class, Sequence, Collaboration, and State diagrams demonstrate clear system architecture.

> **Wireframes**  
> High‑fidelity mockups for Administrator and Member interfaces, illustrating user flows and interactions.

---

## Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/LanAnh55/Fitness-Training-Center-Management-System.git
   cd Fitness-Training-Center-Management-System
2. **Review documentation**

- Open files in /documents for BRD, SRS, and UML diagrams.

- View /wireframes for interface designs.

**Explore the design**

- Examine use case flows and UML diagrams to understand system behavior.

- Inspect wireframes for UI/UX patterns and layout decisions.


**Prototype Figma**: [View on Figma](https://www.figma.com/design/v7T251U75h34V1wyyRKqo2/Fitness-Training-Center-Management-System?node-id=1-5938&t=r2g2iiATro74HJvH-1)

---

**Version:** 1.1.0

**Contact:** Nguyễn Thị Lan Anh ([lananh2004@gmail.com](lananh2004@gmail.com))
