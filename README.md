# Stafflytics AI | Business Intelligence Suite

Stafflytics AI is a professional-grade, AI-powered business intelligence system built for real-time staff monitoring and workforce analytics. It leverages computer vision and machine learning to provide live staff tracking, automated attendance, security monitoring, and actionable labor analytics — adaptable to restaurants, retail stores, offices, warehouses, and any business running on live camera feeds.

> 🔒 **This is a showcase repository.** Stafflytics AI's source code is kept private. This README documents the system's architecture, features, and tech stack. A full walkthrough/demo video is below, with further details available on request.

## 🎥 Demo

https://github.com/user-attachments/assets/0bb3425f-c55c-4938-8154-3b8c2b7f201c

*A walkthrough of live staff tracking, automated attendance, and the reporting dashboard in action.*

## ✨ Key Features
- **Intelligence Monitor**: Real-time video stream with AI-driven bounding boxes and activity labeling.
- **Vision Engine**: Powered by YOLOv8-Pose for movement analysis and `face_recognition` for automated staff/visitor identification.
- **Automated Attendance**: Seamless clock-in/out based on visual presence, with anti-fake protection and late arrival tracking.
- **Peak Traffic Planner**: A high-intensity event planner to help manage busy periods and staffing needs around peak hours or events.
- **Exact Efficiency Metrics**: Measures staff performance based on authorized zone presence, movement intensity, and customer/visitor proximity.
- **Security Alerts**: Instant notifications via email for unauthorized entry into restricted zones (e.g., stockrooms, server rooms, offices).
- **Salary Administration**: Automated tracking of work hours, efficiency scores, and monthly payroll calculation.
- **Executive Reporting**: Generates professional Daily/Weekly BI reports in PDF and Excel formats.

## 🛠️ Technology Stack
- **Backend**: Python (Flask)
- **AI/ML**: OpenCV, Ultralytics YOLOv8, Dlib (Face Recognition)
- **Database**: SQLite3 with WAL mode for concurrent access
- **Frontend**: Vanilla HTML5, CSS3 (Modern UI), JavaScript (Async/Fetch)
- **Communication**: SMTP (Email)

## 🔒 Security & Privacy
Stafflytics AI is designed with a **local-first** approach. All video processing and biometric matching happen on local hardware — no video data is sent to the cloud, ensuring maximum privacy for staff and visitors.

## 👤 Author

**[Minhaj Asghar](https://minhajasghar.vercel.app)**
GitHub: https://github.com/minhajasghar

---
*Built for real-time, privacy-first workforce intelligence — across any business running on live camera feeds.*
