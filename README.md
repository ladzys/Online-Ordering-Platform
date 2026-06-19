# 🐑 Hougang Mutton Stall Ordering Platform

A full-stack e-commerce and order management platform designed for traditional wet market business, starting with a family-owned mutton stall located at **105 Hougang Avenue 1, #01-30, Singapore**.

This project aims to modernize the ordering experience for customers by providing a convenient digital platform for placing pickup and delivery orders, while also streamlining inventory, order management, and customer engagement for stall operators.

Beyond solving a real business problem, this project serves as a personal software engineering portfolio project focused on learning modern web development, cloud architecture, database design, cybersecurity principles, DevOps practices, and scalable application development.

---

## 📌 Project Overview

Traditional wet market businesses often rely on walk-in customers, phone calls, and manual order-taking processes. While effective, these methods can create challenges such as long waiting times, order miscommunication, and limited scalability.

The Hougang Mutton Stall Ordering Platform seeks to bridge the gap between traditional market operations and modern digital solutions by providing an accessible online ordering system for customers while offering business owners powerful tools to manage daily operations.

This project is being developed as both:

- A practical solution for a real family-owned business.
- A portfolio project to strengthen my technical skills in software development, system design, cloud technologies, and cybersecurity.

---

## 🎯 Project Objectives

### Business Objectives

- Enable customers to place orders online.
- Reduce customer waiting time at the stall.
- Improve order accuracy through digital workflows.
- Support pickup and delivery services.
- Improve operational efficiency for stall staff.
- Create a foundation for future business growth.

### Personal Learning Objectives

- Build a production-ready full-stack application.
- Learn modern web development frameworks.
- Gain experience with relational databases.
- Implement secure authentication and authorization.
- Practice DevOps and containerization workflows.
- Apply cybersecurity best practices in application development.
- Develop experience working on a real-world software project from concept to deployment.

---

## 👥 Target Users

### Customers

Customers can:

- Create an account
- Browse available products
- Place pickup orders
- Schedule deliveries
- Track order status
- Save favourite products
- View order history

### Stall Operators

Staff and business owners can:

- Manage products
- Monitor inventory
- Process customer orders
- Update order statuses
- Manage deliveries
- View sales reports and analytics

---

## 🚀 Core Features

### Customer Features

#### Authentication & User Management

- User registration
- Secure login/logout
- Password reset functionality
- Email verification
- Role-based access control
- Session management

#### Product Catalogue

- Browse products
- Product search
- Product filtering
- Product availability indicators
- Product images and descriptions

#### Shopping Cart

- Add products to cart
- Update quantities
- Remove items
- Save cart between sessions

#### Order Management

- Pickup orders
- Delivery orders
- Scheduled collection times
- Order tracking
- Order history
- Reorder functionality

#### Custom Meat Preparation

- Bone-in / Boneless selection
- Fat preference options
- Custom cut sizes
- Special preparation instructions

#### Customer Profiles

- Saved addresses
- Contact details
- Order history
- Favourite products

---

### Admin Features

#### Order Dashboard

- View all incoming orders
- Update order status
- Manage delivery schedules
- Print order summaries

#### Product Management

- Add products
- Edit products
- Remove products
- Manage pricing

#### Inventory Management

- Update stock levels
- Monitor product availability
- Low stock notifications

#### Customer Management

- View customer information
- Track purchase history
- Manage loyalty programs

#### Analytics & Reporting

- Daily sales reports
- Weekly sales reports
- Monthly sales reports
- Product performance tracking
- Customer analytics

---

## 🔮 Planned Future Enhancements

### Loyalty Program

- Points-based rewards system
- Membership tiers
- Referral rewards

### Mobile Application

- Android application
- iOS application
- Push notifications

### AI-Powered Recommendations

- Recipe suggestions
- Portion recommendations
- Product recommendations

### Subscription Services

- Weekly recurring orders
- Monthly recurring deliveries
- Automated billing

### Multi-Language Support

- English
- Malay
- Tamil
- Chinese

---

## 🏗️ System Architecture

```text
Client (Web Browser / Mobile App)

          │

          ▼

      Next.js Frontend

          │

          ▼

        API Layer

          │

          ▼

       Supabase

 ├── Authentication
 ├── PostgreSQL Database
 ├── Storage
 └── Realtime Services

          │

          ▼

     Admin Dashboard
```

---

## 🛠️ Technology Stack

### Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS
- shadcn/ui

### Backend

- Next.js API Routes
- Supabase

### Database

- PostgreSQL

### ORM

- Prisma ORM

### Authentication

- Supabase Authentication

### Hosting

- Vercel

### DevOps

- Docker
- GitHub Actions (Planned)

### Version Control

- Git
- GitHub

---

## 🗄️ Database Design

### Core Tables

```text
users
products
categories
orders
order_items
addresses
payments
inventory
reviews
```

### Entity Relationships

```text
User
 ├── Orders
 ├── Addresses
 └── Reviews

Order
 ├── Order Items
 └── Payment

Product
 ├── Inventory
 └── Reviews
```

---

## 📂 Project Structure

```text
hougang-mutton-stall/

├── src/
│   ├── app/
│   ├── components/
│   ├── services/
│   ├── hooks/
│   ├── lib/
│   ├── types/
│   └── middleware/
│
├── prisma/
│
├── public/
│
├── docker/
│
├── docs/
│
├── tests/
│
└── README.md
```

---

## 📋 Development Roadmap

### Phase 1 – MVP

- [ ] Project setup
- [ ] Database design
- [ ] User authentication
- [ ] Product catalogue
- [ ] Shopping cart
- [ ] Pickup ordering
- [ ] Admin order management

### Phase 2 – Business Operations

- [ ] Delivery management
- [ ] Inventory tracking
- [ ] Customer profiles
- [ ] Notifications

### Phase 3 – Growth Features

- [ ] Loyalty rewards
- [ ] Analytics dashboard
- [ ] Subscription services
- [ ] Mobile application

### Phase 4 – Advanced Features

- [ ] AI recommendations
- [ ] Route optimisation
- [ ] Demand forecasting
- [ ] Business intelligence reporting

---

## 🔐 Security Considerations

As an aspiring Cybersecurity Analyst, security is an important focus area of this project.

Planned security measures include:

- Secure authentication practices
- Password hashing
- Input validation and sanitisation
- Protection against SQL Injection
- Protection against Cross-Site Scripting (XSS)
- Protection against Cross-Site Request Forgery (CSRF)
- Secure session management
- Role-based access control
- Audit logging
- HTTPS enforcement
- Secure API design

---

## 📚 Learning Outcomes

This project is intended to provide practical experience in:

- Full-Stack Development
- System Design
- Database Modelling
- Cloud Computing
- DevOps Practices
- Secure Software Development
- Authentication & Authorisation
- API Development
- Application Deployment
- Cybersecurity Principles

---

## 🏪 About the Business

This platform is inspired by a family-owned mutton stall located at:

**105 Hougang Avenue 1**  
**#01-30**  
**Singapore**

The goal is to bring modern digital capabilities to a traditional business while maintaining the personalised customer experience that local market vendors are known for.

---

## 👨‍💻 Author

### Mohamed Haneefa Jiyavudeen

Aspiring Cybersecurity Analyst | Technology Enthusiast | Lifelong Learner

This project represents my commitment to continuous learning through real-world application development. By building a platform for my family business, I aim to strengthen my skills in software engineering, cloud technologies, secure development practices, and cybersecurity while creating meaningful value for a real business.

---

## 📄 License

This project is currently developed for educational, portfolio, and family business purposes.

All rights reserved unless otherwise specified.
