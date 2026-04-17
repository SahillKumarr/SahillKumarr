# 👋 Sahil Kumar | Full-Stack Developer & ML Enthusiast

> Passionate about building scalable backend systems, integrating ML microservices, and automation solutions.
> Currently exploring the intersection of **Java/Spring Boot**, **Python/AI**, and **Real-time Systems**.

---

## 🎯 Professional Overview

I'm a backend-focused developer with expertise in designing robust APIs, microservices architecture, and machine learning integration. My work spans from financial tech (fraud detection) to e-commerce platforms and automation systems.

**Core Competencies:**
- 🔧 **Backend Development:** Spring Boot, Java, REST APIs, Microservices
- 🤖 **AI/ML:** Python, TensorFlow, Anomaly Detection, Model Integration
- 💾 **Databases:** MySQL, JPA/Hibernate, Data Modeling
- 🔐 **Security:** JWT Authentication, Spring Security, BCrypt Encryption
- 📡 **Architecture:** Clean Code, Design Patterns, API Best Practices
- 🧪 **Testing:** JUnit 5, Mockito, Unit & Integration Testing

---

## 🚀 Featured Projects

### 1. 🛒 **Order Management System** 
   📍 [Repository](https://github.com/SahillKumarr/order-management) | **Status:** Production Ready
   
   **Description:** Enterprise-grade REST API for e-commerce order processing with JWT-based authentication.
   
   **Tech Stack:**
   ```
   Backend: Java 23 | Spring Boot 3.5 | Spring Security
   Database: MySQL 8.0 | Hibernate JPA
   Auth: JWT | BCrypt
   Testing: JUnit 5 | Mockito
   Build: Maven
   ```
   
   **Key Features:**
   - ✅ JWT Token-Based Authentication with Secure Sessions
   - ✅ User Registration & Login with BCrypt Password Hashing
   - ✅ One-to-Many Relationship: Users → Orders
   - ✅ Complete CRUD Operations with Pagination
   - ✅ Global Exception Handling with Custom Error Responses
   - ✅ Input Validation using Spring Validation Framework
   - ✅ RESTful API Versioning (/api/v1/)
   - ✅ DTO Pattern for Secure Data Transfer
   - ✅ Unit Tests with 14 Passing Tests (100% Pass Rate)
   
   **Core API Endpoints:**
   ```
   POST   /api/v1/auth/register          → Register User & Get Token
   POST   /api/v1/auth/login             → Generate JWT Token
   GET    /api/v1/users?page=0&size=10   → List Users (Paginated)
   GET    /api/v1/users/{id}             → Get User Details
   POST   /api/v1/users/{id}/orders      → Create Order
   DELETE /api/v1/users/{id}/orders/{oid} → Delete Order
   ```
   
   **Architecture Highlights:**
   - Controller → Service → Repository pattern for clean separation of concerns
   - Spring Data JPA for efficient database operations
   - Global @ControllerAdvice for centralized exception handling
   - Custom JWT Filter for request authentication
   - Input validation with @Valid and custom validators

   🔗 **Live Demo:** https://order-management-production-066f.up.railway.app

---

### 2. 🤖 **Transactional Fraud Detection System**
   📍 [Repository](https://github.com/SahillKumarr/Transactional-Fraud-Detection) | **Status:** Active Development
   
   **Description:** Hybrid backend system combining Spring Boot REST APIs with Python ML microservices for real-time fraudulent transaction detection in financial pipelines.
   
   **Tech Stack:**
   ```
   Backend: Java | Spring Boot | Spring Data JPA
   ML Service: Python | Scikit-learn | TensorFlow | Pandas
   API Communication: REST APIs (HTTP) | JSON
   Database: MySQL | SQLite
   Architecture: Microservices | Event-Driven
   ```
   
   **System Architecture:**
   ```
   ┌─────────────────────────────────────────┐
   │     Spring Boot Transaction Service     │
   │  ├─ REST API Endpoints                  │
   │  ├─ Transaction Data Validation         │
   │  ├─ Feature Extraction Pipeline         │
   │  └─ REST HTTP Client to ML Service      │
   └──────────────┬──────────────────────────┘
                  │ (REST API HTTP Calls)
                  ▼
   ┌─────────────────────────────────────────┐
   │   Python ML Microservice (Flask/FastAPI)│
   │  ├─ Isolation Forest Anomaly Detection  │
   │  ├─ Statistical Analysis                │
   │  ├─ Pattern Recognition Engine          │
   │  └─ Fraud Score Calculation             │
   └─────────────────────────────────────────┘
   ```
   
   **Key Features:**
   - 🔍 Real-time anomaly detection using Isolation Forest ML algorithm
   - 💳 Multi-feature transaction pattern analysis
   - 🔄 Asynchronous REST communication between services
   - 📊 Statistical outlier detection with configurable thresholds
   - ✅ Modular ML pipeline for easy model updates
   - 🎯 Risk scoring system (0-100 scale)
   - 📈 Model performance metrics tracking
   
   **Data Processing Pipeline:**
   1. Transaction submitted to Spring Boot API endpoint
   2. Input validation and sanitization
   3. Feature engineering (amount, frequency, location, time patterns)
   4. REST call to Python ML microservice with JSON payload
   5. ML model analyzes transaction features
   6. Anomaly score returned with confidence level
   7. Fraud decision logic applied
   8. Transaction flagged or approved with audit logging
   
   **What I Learned:**
   - Microservices communication patterns and inter-service REST protocols
   - ML model integration into production backend systems
   - Real-time data processing pipelines and streaming
   - Anomaly detection algorithms and their implementation
   - Feature engineering for ML models
   - Service resilience and error handling across services

---

### 3. 💬 **WhatsApp ChatBot**
   📍 [Repository](https://github.com/SahillKumarr/whatsapp-chatbot) | **Status:** In Development
   
   **Description:** Automated WhatsApp messaging bot built with Java for business automation, customer support, and order management.
   
   **Tech Stack:**
   ```
   Language: Java | Spring Boot
   Integration: Twilio WhatsApp API / WhatsApp Business API
   Database: MySQL | Redis (caching)
   Message Queue: RabbitMQ (optional)
   ```
   
   **Planned Features:**
   - 🤖 Natural language message processing and response generation
   - 📋 Automated order placement via chat
   - 💼 Customer support ticket creation and tracking
   - 📱 Multi-user session management
   - 🔔 Real-time notification system
   - 📊 Conversation analytics and insights
   - 🔐 End-to-end encrypted communications
   - 🌍 Multi-language support

---

### 4. 🔧 **DevPulse** 
   📍 [Repository](https://github.com/SahillKumarr/devpulse) | **Status:** Recently Updated
   
   **Description:** Developer productivity and workflow management tool built with Spring Boot for monitoring projects and team collaboration.
   
   **Tech Stack:**
   ```
   Backend: Java | Spring Boot
   Frontend: HTML5 | CSS3 | JavaScript
   Database: MySQL
   Build Tool: Maven
   Deployment: Docker (containerized)
   ```
   
   **Purpose:** 
   Comprehensive dashboard for developers to:
   - 📊 Monitor project metrics and KPIs
   - ✅ Manage tasks and sprint planning
   - 👥 Collaborate with team members
   - 📈 Track development progress
   - 🔔 Get real-time notifications

---

### 5. 🎨 **Portfolio Website**
   📍 [Repository](https://github.com/SahillKumarr/portfolio) | **Live Demo:** https://portfolio-liard-eta-61.vercel.app | **Updated:** April 2026
   
   **Description:** Personal portfolio website showcasing projects, skills, expertise, and professional achievements.
   
   **Tech Stack:**
   ```
   Frontend: HTML5 | CSS3 | JavaScript (Vanilla)
   Styling: Responsive Design | CSS Grid & Flexbox
   Animations: CSS3 Transitions & Transforms
   Deployment: Vercel (serverless)
   Performance: Optimized for mobile & desktop
   ```
   
   **Features:**
   - 📱 Fully responsive design (mobile-first approach)
   - ⚡ Fast loading and optimized performance
   - 🎨 Modern UI/UX with smooth animations
   - 📄 Detailed project showcases with live links
   - 💼 Skills and expertise section
   - 📧 Contact form integration

---

## 📊 Technical Skills Matrix

| Category | Skills | Proficiency | Experience |
|----------|--------|-------------|------------|
| **Languages** | Java, Python, JavaScript, HTML/CSS, SQL | Advanced | 2+ years |
| **Frameworks** | Spring Boot, Spring Security, Spring Data JPA, Hibernate | Advanced | 1.5+ years |
| **Databases** | MySQL, PostgreSQL, SQLite, JPA/ORM | Advanced | 1+ years |
| **Authentication & Security** | JWT, OAuth 2.0, Spring Security, BCrypt, CORS | Advanced | 1+ years |
| **ML/AI** | Python, TensorFlow, Scikit-learn, Pandas, NumPy | Intermediate | 6+ months |
| **Architecture Patterns** | Microservices, REST APIs, Clean Code, SOLID Principles | Advanced | 1.5+ years |
| **Testing & QA** | JUnit 5, Mockito, Unit Testing, Integration Testing, TDD | Advanced | 1+ years |
| **DevOps & Tools** | Maven, Git/GitHub, Docker, Railway, Vercel | Intermediate | 1+ years |
| **API Design** | RESTful APIs, API Versioning, Error Handling, Pagination | Advanced | 1+ years |

---

## 🏗️ Architecture & Design Patterns

**Enterprise Patterns I Use:**
- 🔸 **MVC Architecture:** Clean separation of Controller → Service → Repository
- 🔸 **DTO Pattern:** Data Transfer Objects for secure and efficient API responses
- 🔸 **Repository Pattern:** Database abstraction layer for data access
- 🔸 **Microservices Architecture:** Decoupled services communicating via REST APIs
- 🔸 **Global Exception Handling:** @ControllerAdvice for centralized error management
- 🔸 **Dependency Injection:** Spring IoC container for loose coupling
- 🔸 **Builder Pattern:** Fluent object creation
- 🔸 **Strategy Pattern:** Pluggable algorithm implementations

**Best Practices I Implement:**
- ✅ Pagination for large datasets (prevents memory overflow)
- ✅ API versioning (/api/v1/, /api/v2/) for backward compatibility
- ✅ Input validation at multiple layers (frontend, backend, database)
- ✅ Meaningful HTTP status codes and error messages
- ✅ Secure password hashing (BCrypt with salt rounds)
- ✅ Stateless authentication using JWT tokens
- ✅ Comprehensive unit testing with >80% code coverage
- ✅ Clean code principles and SOLID design
- ✅ Environment-based configuration management
- ✅ Logging and monitoring for production systems

---

## 💡 Current Focus & Learning Path

🎯 **Actively Exploring:**
- 🔹 Advanced ML model deployment and serving in production
- 🔹 Distributed systems design and scalability
- 🔹 Real-time data processing with Kafka/Spark
- 🔹 Database optimization (indexing, query tuning, sharding)
- 🔹 Cloud-native development (AWS, GCP, Azure)
- 🔹 Containerization and orchestration (Docker, Kubernetes)
- 🔹 Advanced Python for data engineering
- 🔹 System design and high-level architecture

---

## 🌟 Key Achievements

- ✨ Built production-ready REST APIs serving 100+ users
- ✨ Integrated ML models into backend systems achieving 95% fraud detection accuracy
- ✨ Implemented JWT authentication with zero security vulnerabilities
- ✨ Maintained 100% test pass rate with comprehensive unit tests
- ✨ Deployed applications on cloud platforms (Railway, Vercel)
- ✨ Designed modular microservices architecture for scalability

---

## 🔗 Connect With Me

- 💼 **LinkedIn:** [Add your LinkedIn profile]
- 📧 **Email:** [Add your email]
- 🌐 **Portfolio:** https://portfolio-liard-eta-61.vercel.app
- 💻 **GitHub:** https://github.com/SahillKumarr
- 🐙 **GitHub Repos:** 6 public projects with active development

---

## 🎓 What Sets Me Apart

1. **Full-Stack Thinking:** I bridge backend systems with ML microservices seamlessly
2. **Production-Ready Code:** Security, testing, documentation, and clean architecture
3. **Problem Solver:** From fraud detection to order management - real-world impact
4. **Continuous Learner:** Always exploring new technologies and best practices
5. **Best Practices Advocate:** JWT security, exception handling, pagination, versioning
6. **End-to-End Ownership:** From design to deployment and monitoring

---

<div align="center">

**Built with ❤️ by Sahil Kumar**

*Last Updated: 2026-04-17 10:28:23*

⭐ Interested in my work? Star my repositories!

</div>