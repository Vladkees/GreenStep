# 🌱 GreenStep — Ecological Mobile App

GreenStep is a cross-platform ecological app designed to help users track their eco-friendly actions, earn an EcoScore, join challenges, and contribute to a greener planet.

---

## ✅ Functional Requirements

### 👤 User (Eco Citizen)
- Register via email or social login (Google, Apple)
- Secure login/logout
- Track eco-actions (recycling, biking, etc.)
- Earn/view **EcoScore**
- Join local events & eco-challenges
- View leaderboard rankings
- View/edit eco-profile and activity stats
- Connect with friends
- Upload documents/photos of actions
- Receive personalized eco tips
- Manage app settings

### 🛠️ Administrator
- Admin dashboard login
- Manage eco-challenges and actions
- Moderate uploads and events
- Publish tips and global announcements
- Set EcoScore calculation rules
- View usage and community engagement
- Approve user-submitted events
- Targeted notifications
- Export user/activity data

### ⚙️ System
- Real-time EcoScore calculation
- Location/time tracking of actions
- Send reminders for goals/challenges
- Securely store user history
- Prevent fraudulent entries
- Sync data across devices
- Support multilingual content
- Daily backups
- GDPR-compliant

---

## 📊 Non-Functional Requirements

### 🚀 Performance
- ≥ 5,000 concurrent users
- 95% of API calls < 300ms
- Home dashboard loads < 2s
- Real-time score updates < 1s

### 🛡️ Security
- HTTPS + OAuth 2.0 + JWT
- Encrypted user data and docs
- 2FA for admin panel
- GDPR & COPPA compliance

### 📈 Scalability
- Support 100k+ users
- Regional scaling (events, feeds)
- Modular services for future features

### 👁️‍🗨️ Usability
- Cross-platform (iOS & Android)
- WCAG 2.1 AA compliance
- Multilingual (English, Ukrainian)
- 3-tap action logging UX

### 📉 Analytics & Reporting
- Admin dashboard with KPIs
- Leaderboard and impact stats
- Export to PDF/CSV
- All changes timestamped

---

## 🧱 System Architecture

### 🔧 Main Components

| Component               | Description                                |
|-------------------------|--------------------------------------------|
| Mobile App (Flutter)    | User interface and offline support         |
| API Gateway             | Auth, routing, rate-limiting               |
| User Service            | Profiles, scores, settings                 |
| EcoAction Service       | Track & verify eco-friendly actions        |
| Challenge/Event Service | Manage community activities & rankings     |
| Notification Service    | Push/email alerts                          |
| Analytics Service       | Generate usage and impact reports          |
| Storage Service         | Manage uploads (photos, docs)              |
| Admin Panel (Vue/React) | Admin UI for moderation and insights       |
| Database (PostgreSQL)   | Store persistent data                      |
| Kafka/RabbitMQ          | Event-driven communication                 |

---

## 🧰 Tech Stack

| Layer          | Tools / Frameworks                |
|----------------|----------------------------------|
| Frontend       | Flutter                          |
| Backend        | Node.js / Python Flask           |
| API Gateway    | NGINX / Express Gateway          |
| Database       | PostgreSQL                       |
| Authentication | Auth0 / Firebase Auth            |
| Messaging      | Kafka / RabbitMQ                 |
| Storage        | AWS S3 / Firebase Storage        |
| Monitoring     | Prometheus + Grafana             |
| Notifications  | Firebase Cloud Messaging (FCM)   |
| CI/CD          | GitHub Actions / GitLab CI       |
| Deployment     | Docker + Kubernetes / GCP        |

---
