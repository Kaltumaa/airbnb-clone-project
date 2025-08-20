# 🏡 Airbnb Clone Project

This repository is for **Pro-Dev Backend** and **Pro-Dev Frontend** courses.  
It demonstrates both backend and frontend aspects of building an Airbnb Clone application.  

---

## 🌍 Project Overview
The goal is to create a full-stack accommodation booking system inspired by Airbnb.  
It allows users to browse listings, view details, book properties, and make payments.  

### Goals
- Build a scalable backend with APIs, databases, and security.  
- Design a responsive frontend with consistent UI/UX.  
- Practice real-world collaboration with defined roles.  
- Implement DevOps practices with CI/CD pipelines.  

---

# ⚙️ Pro-Dev Backend

## 👥 Team Roles
- **Backend Developer**: Implement APIs, business logic, and database connections.  
- **Database Administrator (DBA)**: Design schema, optimize queries, ensure data security.  
- **DevOps Engineer**: Manage deployments, Docker, CI/CD pipelines, monitoring.  
- **QA Engineer**: Write and run test cases, track bugs, validate functionality.  
- **Project Manager**: Coordinate tasks, timelines, communication.  
- **UI/UX Designer**: Provide wireframes and ensure backend supports UI needs.  
- **Business Analyst**: Gather requirements and align features with goals.  

---

## ⚙️ Technology Stack
- **Backend Framework**: Django + Django REST Framework (DRF)  
- **Database**: PostgreSQL  
- **API**: REST + GraphQL support  
- **Caching**: Redis  
- **Task Queue**: Celery  
- **Containerization**: Docker + Docker Compose  
- **CI/CD**: GitHub Actions + Deployment Pipeline  
- **Monitoring**: Prometheus + Grafana  

---

## 🗄️ Database Design
- **Users** (Profile, Authentication, Roles)  
- **Properties** (Owner, Location, Pricing, Amenities)  
- **Bookings** (Check-in/out dates, Guests, Linked to Users & Properties)  
- **Payments** (Booking reference, Status, Transaction ID)  
- **Reviews** (User feedback linked to Property & User)  

---

## 🛠️ Feature Breakdown
- **User Management** (Sign-up, Login, JWT auth, Profiles)  
- **Property Management** (CRUD, images, amenities, search)  
- **Booking Management** (Check availability, create/cancel booking, notifications)  
- **Payments** (Integration with Stripe/Flutterwave, refunds, confirmations)  
- **Reviews** (User can leave reviews with rating + text)  
- **Data Optimization** (Caching, indexes, async tasks)  

---

## 🔐 API Security
- Authentication with JWT  
- Authorization with roles (admin, host, guest)  
- Rate limiting with DRF throttling  
- Input validation + sanitization  
- Encrypted payments and secure API calls  

---

## 🔄 CI/CD Pipeline
- **CI**: Linting, unit tests, coverage reports via GitHub Actions  
- **CD**: Build Docker image → Push to registry → Deploy to staging/production  
- **Monitoring**: Logging (ELK stack), alerts with Grafana dashboards  

---

# 🎨 Pro-Dev Frontend

## 🎯 UI/UX Design Planning

### Design Goals
- Create intuitive booking flow  
- Maintain visual consistency  
- Ensure mobile responsiveness  

### Key Features
- Property search + filtering  
- Detailed property view  
- Checkout & payment  

### Primary Pages
| Page | Description |
|------|-------------|
| **Property Listing View** | Grid of properties with filters |
| **Listing Detailed View** | Full details, images, booking form |
| **Simple Checkout View** | Streamlined payment + confirmation |

---

## ✨ Importance of User-Friendly Design
A well-designed booking system reduces friction, increases conversion, and improves customer satisfaction.  

---

## 🎨 Figma Design Specifications

**Color Styles**  
- Primary: `#FF5A5F`  
- Secondary: `#008489`  
- Background: `#FFFFFF`  
- Text: `#222222`  
- Secondary Text: `#717171`  

**Typography**  
- Primary Font: Circular, Medium (500), 16px  
- Headings: Circular, Bold (700), 24–32px  
- Secondary Text: Circular, Book (400), 14px  

**Why this matters**  
Identifying design properties ensures the mockup translates into a consistent, professional UI.  

---

## 📋 Project Roles and Responsibilities
| Role | Responsibilities |
|------|------------------|
| Project Manager | Oversees timeline, coordinates team |
| Frontend Developers | Build UI components, ensure responsiveness |
| Backend Developers | Build APIs, manage DB, implement logic |
| Designers | Create mockups, ensure UX consistency |
| QA/Testers | Write test cases, perform tests, report bugs |
| DevOps Engineers | Deployment, CI/CD, server infrastructure |
| Product Owner | Define requirements, prioritize features |
| Scrum Master | Facilitate agile, remove blockers |

---

## 🧩 UI Component Patterns
Planned reusable components include:  

- **Navbar**: Logo, search bar, user nav, responsive menu  
- **Property Card**: Image, details (price, location, rating), favorite button  
- **Footer**: Site links, company info, social media, copyright  

Each component is designed for **reusability** and **consistency** across the app.  

---

# ✅ Conclusion
This repository covers **both Pro-Dev Backend and Pro-Dev Frontend requirements**,  
providing a full-stack perspective on building an Airbnb-style booking application.  
