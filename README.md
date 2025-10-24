# Airbnb Clone Project

## Project Overview

The Airbnb Clone Project is a comprehensive full-stack web application that replicates the core functionalities of Airbnb, one of the world's leading online marketplaces for lodging and travel experiences. This project serves as a practical learning experience in building scalable, secure, and feature-rich booking platforms.

Through this project, we aim to create a robust system that allows users to browse properties, make bookings, manage listings, and handle payments, while providing property owners with tools to manage their listings and bookings effectively.

## Project Goals

- **Build a Scalable Backend Architecture**: Develop a robust backend system capable of handling multiple users, listings, bookings, and transactions simultaneously.

- **Implement Secure API Development**: Create RESTful and GraphQL APIs with industry-standard security measures to protect user data and ensure safe transactions.

- **Design Efficient Database Systems**: Structure a relational database that efficiently manages complex relationships between users, properties, bookings, reviews, and payments.

- **Master Modern Development Workflows**: Utilize Git, GitHub, and collaborative development practices to simulate real-world team environments.

- **Integrate CI/CD Pipelines**: Implement automated testing, building, and deployment processes to ensure code quality and streamline the development lifecycle.

- **Apply Best Security Practices**: Incorporate authentication, authorization, data encryption, and other security measures to create a production-ready application.

## Tech Stack
## 💻 Technology Stack

### Frontend
**React**
- **Purpose**: A JavaScript library for building dynamic and interactive user interfaces
- **Why**: Provides component-based architecture for reusable UI elements and efficient rendering with virtual DOM
- **Use Case**: Building the client-side interface for property browsing, booking flows, and user dashboards

**TypeScript**
- **Purpose**: Typed superset of JavaScript that compiles to plain JavaScript
- **Why**: Adds static typing to catch errors early and improve code quality and maintainability
- **Use Case**: Ensuring type safety across the frontend codebase

**Tailwind CSS**
- **Purpose**: Utility-first CSS framework for rapid UI development
- **Why**: Enables fast, responsive design with minimal custom CSS
- **Use Case**: Styling components, creating responsive layouts, and maintaining consistent design

**Next.js** (Optional)
- **Purpose**: React framework for server-side rendering and static site generation
- **Why**: Improves SEO, performance, and provides built-in routing
- **Use Case**: Server-side rendering of property listings for better search engine visibility

### Backend
**Django**
- **Purpose**: High-level Python web framework for rapid development
- **Why**: Follows the "batteries-included" philosophy with built-in features for authentication, ORM, admin panel, and security
- **Use Case**: Building RESTful APIs, handling business logic, user authentication, and managing the application backend

**Django REST Framework (DRF)**
- **Purpose**: Powerful toolkit for building Web APIs in Django
- **Why**: Provides serialization, authentication, viewsets, and browsable API interface
- **Use Case**: Creating RESTful API endpoints for CRUD operations on properties, bookings, and user data

**GraphQL (with Graphene-Django)**
- **Purpose**: Query language for APIs that allows clients to request exactly what they need
- **Why**: Reduces over-fetching and under-fetching of data, provides a single endpoint for all queries
- **Use Case**: Flexible data fetching for complex queries like property searches with multiple filters

**Celery**
- **Purpose**: Distributed task queue for handling asynchronous operations
- **Why**: Offloads time-consuming tasks from the main application thread
- **Use Case**: Sending email notifications, processing payments, generating reports, and scheduled tasks

### Database
**PostgreSQL**
- **Purpose**: Advanced open-source relational database management system
- **Why**: Offers robust ACID compliance, complex queries, JSON support, and excellent performance
- **Use Case**: Storing structured data including users, properties, bookings, reviews, and transactions

**MySQL** (Alternative)
- **Purpose**: Popular open-source relational database
- **Why**: Reliable, well-documented, and widely supported
- **Use Case**: Alternative to PostgreSQL for storing application data

**Redis**
- **Purpose**: In-memory data structure store used as cache and message broker
- **Why**: Extremely fast data access and temporary data storage
- **Use Case**: Caching frequently accessed data (property listings), session management, and Celery message broker

### Authentication & Security
**JWT (JSON Web Tokens)**
- **Purpose**: Compact, URL-safe token format for securely transmitting information
- **Why**: Stateless authentication that scales well for distributed systems
- **Use Case**: User authentication and authorization across API requests

**OAuth 2.0**
- **Purpose**: Industry-standard authorization framework
- **Why**: Allows secure third-party access without sharing passwords
- **Use Case**: Social login with Google, Facebook, and other providers

**Django Security Middleware**
- **Purpose**: Built-in Django security features
- **Why**: Protects against common vulnerabilities (XSS, CSRF, SQL injection, clickjacking)
- **Use Case**: Securing all API endpoints and user data

### Payment Integration
**Stripe API**
- **Purpose**: Payment processing platform
- **Why**: Secure, developer-friendly, and supports multiple payment methods
- **Use Case**: Processing booking payments, handling refunds, and managing payouts to property owners

### File Storage
**AWS S3 (Amazon Simple Storage Service)**
- **Purpose**: Cloud-based object storage service
- **Why**: Scalable, durable, and cost-effective storage for large files
- **Use Case**: Storing property images, user profile photos, and uploaded documents

**Cloudinary** (Alternative)
- **Purpose**: Cloud-based image and video management service
- **Why**: Automatic image optimization and transformation
- **Use Case**: Managing and delivering property images with dynamic resizing

### DevOps & Deployment
**Docker**
- **Purpose**: Platform for developing, shipping, and running applications in containers
- **Why**: Ensures consistency across development, testing, and production environments
- **Use Case**: Containerizing the application and its dependencies for easy deployment

**Docker Compose**
- **Purpose**: Tool for defining and running multi-container Docker applications
- **Why**: Simplifies the orchestration of multiple services (app, database, cache)
- **Use Case**: Local development environment setup

**GitHub Actions**
- **Purpose**: CI/CD platform integrated with GitHub
- **Why**: Automates testing, building, and deployment workflows
- **Use Case**: Running automated tests on every commit, deploying to staging/production

**Nginx**
- **Purpose**: High-performance web server and reverse proxy
- **Why**: Efficiently serves static files and acts as a load balancer
- **Use Case**: Serving frontend assets and proxying requests to the Django backend

**Gunicorn**
- **Purpose**: Python WSGI HTTP server for UNIX
- **Why**: Production-grade server for running Django applications
- **Use Case**: Serving the Django application in production

### Monitoring & Logging
**Sentry**
- **Purpose**: Error tracking and performance monitoring platform
- **Why**: Real-time error reporting and debugging
- **Use Case**: Tracking application errors and performance issues in production

**Prometheus & Grafana** (Optional)
- **Purpose**: Monitoring and alerting toolkit with visualization
- **Why**: Provides metrics collection and beautiful dashboards
- **Use Case**: Monitoring system health, API performance, and database metrics

### Testing
**Pytest**
- **Purpose**: Python testing framework
- **Why**: Simple syntax, powerful features, and extensive plugin ecosystem
- **Use Case**: Writing and running backend unit and integration tests

**Jest**
- **Purpose**: JavaScript testing framework
- **Why**: Fast, feature-rich, and works well with React
- **Use Case**: Testing frontend components and logic

**Selenium** (Optional)
- **Purpose**: Browser automation tool
- **Why**: Enables end-to-end testing in real browsers
- **Use Case**: Automated testing of complete user workflows

### Additional Tools
**Git & GitHub**
- **Purpose**: Version control system and collaboration platform
- **Why**: Track changes, collaborate with team members, and manage code reviews
- **Use Case**: Source code management and team collaboration

**Postman**
- **Purpose**: API development and testing tool
- **Why**: Simplifies API testing and documentation
- **Use Case**: Testing API endpoints during development

**VS Code**
- **Purpose**: Lightweight but powerful source code editor
- **Why**: Extensive extensions, debugging support, and Git integration
- **Use Case**: Primary development environment for coding
## 👥 Team Roles and Responsibilities

### Project Manager (PM)
**Responsibilities:**
- Oversee the entire project lifecycle from planning to deployment
- Coordinate communication between team members and stakeholders
- Manage project timelines, milestones, and deliverables
- Identify and mitigate risks
- Ensure the project stays within scope and budget
- Facilitate daily stand-ups and sprint planning meetings

### Frontend Developers
**Responsibilities:**
- Design and implement the user interface using React, HTML, CSS, and JavaScript
- Ensure responsive design across different devices and browsers
- Integrate frontend with backend APIs
- Optimize application performance and loading times
- Implement user authentication flows and protected routes
- Collaborate with UI/UX designers to translate designs into functional code
- Write and maintain frontend unit and integration tests

### Backend Developers
**Responsibilities:**
- Design and develop server-side logic using Django and Python
- Create and maintain RESTful APIs and GraphQL endpoints
- Implement business logic and data processing algorithms
- Integrate third-party services (payment gateways, email services, cloud storage)
- Optimize server performance and response times
- Write and maintain comprehensive API documentation
- Implement security measures and authentication mechanisms
- Conduct code reviews and ensure coding standards

### Designers (UI/UX)
**Responsibilities:**
- Create wireframes, mockups, and prototypes for the application
- Design intuitive and aesthetically pleasing user interfaces
- Conduct user research and usability testing
- Develop design systems and style guides
- Ensure consistent branding across the platform
- Collaborate with frontend developers to implement designs
- Create responsive designs for mobile and desktop platforms
- Design user flows and interaction patterns

### QA/Testers (Quality Assurance)
**Responsibilities:**
- Develop and execute comprehensive test plans and test cases
- Perform manual and automated testing (unit, integration, end-to-end)
- Identify, document, and track bugs and issues
- Verify bug fixes and perform regression testing
- Test API endpoints for functionality and performance
- Ensure cross-browser and cross-device compatibility
- Conduct security and performance testing
- Collaborate with developers to improve code quality

### DevOps Engineers
**Responsibilities:**
- Set up and maintain CI/CD pipelines using GitHub Actions or similar tools
- Manage containerization with Docker and orchestration with Kubernetes
- Configure and maintain cloud infrastructure (AWS, Azure, or GCP)
- Implement monitoring and logging solutions
- Automate deployment processes
- Ensure system security and perform regular updates
- Manage database backups and disaster recovery procedures
- Optimize infrastructure costs and performance

### Product Owner
**Responsibilities:**
- Define the product vision and roadmap
- Prioritize features and manage the product backlog
- Write and refine user stories with clear acceptance criteria
- Serve as the voice of the customer and stakeholders
- Make decisions on scope and feature trade-offs
- Validate completed features against requirements
- Gather and analyze user feedback for continuous improvement

### Scrum Master
**Responsibilities:**
- Facilitate Scrum ceremonies (daily stand-ups, sprint planning, retrospectives)
- Remove impediments and blockers for the development team
- Coach the team on Agile principles and practices
- Protect the team from external interruptions
- Foster a collaborative and productive team environment
- Track sprint progress and team velocity
- Promote continuous improvement within the team

### Backend
- **Django**: A high-level Python web framework for rapid development and clean, pragmatic design
- **Django REST Framework**: Powerful toolkit for building Web APIs
- **GraphQL**: Query language for APIs providing flexible and efficient data retrieval

### Database
- **MySQL**: Reliable relational database management system for structured data storage
- **PostgreSQL** (Alternative): Advanced open-source relational database

### Authentication & Security
- **JWT (JSON Web Tokens)**: Secure token-based authentication
- **OAuth 2.0**: Industry-standard protocol for authorization
- **Django Security Middleware**: Built-in protection against common vulnerabilities

### DevOps & Deployment
- **Docker**: Containerization platform for consistent development and deployment environments
- **GitHub Actions**: CI/CD automation for testing and deployment
- **Nginx**: High-performance web server and reverse proxy

### Additional Tools
- **Redis**: In-memory data structure store for caching and session management
- **Celery**: Distributed task queue for handling asynchronous operations
- **Stripe API**: Payment processing integration
- **AWS S3**: Cloud storage for images and media files

# AirBnB Clone - Complete Database Design Guide

## 📋 Project Context
**Platform**: Full-stack booking system (like Airbnb)  
**Backend**: Django + PostgreSQL  
**Timeline**: October 13-20, 2025  
**Key Features**: Property listings, bookings, reviews, payments, messaging

---

## STEP 1: ENTITY-RELATIONSHIP (ER) DIAGRAM

### Phase 1A: Entity Identification

Based on your README features, here are the **core entities**:

#### **Primary Entities** (Must Have)
1. ✅ **User** - Guests, hosts, and admins
2. ✅ **Property** - Rental listings
3. ✅ **Booking** - Reservations
4. ✅ **Review** - Property ratings and feedback
5. ✅ **Payment** - Transaction records
6. ✅ **Message** - User-to-user communication

#### **Supporting Entities** (Enhance Functionality)
7. ✅ **PropertyPhoto** - Property images
8. ✅ **Amenity** - Property features (WiFi, pool, etc.)
9. ✅ **Location** - Detailed property addresses
10. ✅ **Notification** - User alerts
11. ✅ **PropertyAvailability** - Calendar dates
12. ✅ **Category** - Property types (apartment, villa, etc.)

---

### Phase 1B: Complete Entity Attributes

#### **1. USER Entity**

```yaml
Entity: User
Purpose: Represents all platform users (guests, hosts, admins)

Attributes:
  Primary Key:
    - user_id: UUID (Primary Key)
  
  Authentication:
    - email: VARCHAR(255), UNIQUE, NOT NULL
    - password_hash: VARCHAR(255), NOT NULL
    - auth_provider: ENUM('local', 'google', 'facebook'), DEFAULT 'local'
    - oauth_id: VARCHAR(255), NULLABLE (for social login)
  
  Personal Information:
    - first_name: VARCHAR(100), NOT NULL
    - last_name: VARCHAR(100), NOT NULL
    - phone_number: VARCHAR(20), NULLABLE
    - date_of_birth: DATE, NULLABLE
    - profile_picture: VARCHAR(500), NULLABLE
    - bio: TEXT, NULLABLE
  
  User Type & Status:
    - role: ENUM('guest', 'host', 'admin'), DEFAULT 'guest'
    - is_host: BOOLEAN, DEFAULT FALSE (for quick queries)
    - is_verified: BOOLEAN, DEFAULT FALSE
    - verification_token: VARCHAR(255), NULLABLE
    - email_verified_at: TIMESTAMP, NULLABLE
  
  Timestamps:
    - created_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP
    - updated_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP ON UPDATE
    - last_login_at: TIMESTAMP, NULLABLE
    - deleted_at: TIMESTAMP, NULLABLE (soft delete)

Indexes:
  - idx_user_email (email)
  - idx_user_role (role)
  - idx_user_oauth (auth_provider, oauth_id)

Constraints:
  - CHECK (email LIKE '%@%')
  - CHECK (role IN ('guest', 'host', 'admin'))
```

---

#### **2. PROPERTY Entity**

```yaml
Entity: Property
Purpose: Represents rental properties listed by hosts

Attributes:
  Primary Key:
    - property_id: UUID (Primary Key)
  
  Ownership:
    - host_id: UUID, FOREIGN KEY → User(user_id), NOT NULL
    - category_id: UUID, FOREIGN KEY → Category(category_id)
  
  Basic Information:
    - title: VARCHAR(200), NOT NULL
    - description: TEXT, NOT NULL
    - slug: VARCHAR(250), UNIQUE (for SEO-friendly URLs)
  
  Property Details:
    - max_guests: INTEGER, NOT NULL, CHECK (max_guests > 0)
    - bedrooms: INTEGER, NOT NULL, CHECK (bedrooms >= 0)
    - beds: INTEGER, NOT NULL, CHECK (beds > 0)
    - bathrooms: DECIMAL(3,1), NOT NULL, CHECK (bathrooms > 0)
  
  Pricing:
    - price_per_night: DECIMAL(10,2), NOT NULL, CHECK (price_per_night > 0)
    - cleaning_fee: DECIMAL(10,2), DEFAULT 0
    - service_fee_percentage: DECIMAL(5,2), DEFAULT 10.00
    - currency: VARCHAR(3), DEFAULT 'USD'
    - weekend_price: DECIMAL(10,2), NULLABLE (optional weekend pricing)
  
  Booking Rules:
    - min_nights: INTEGER, DEFAULT 1
    - max_nights: INTEGER, DEFAULT 365
    - instant_book: BOOLEAN, DEFAULT FALSE
    - cancellation_policy: ENUM('flexible', 'moderate', 'strict', 'super_strict'), DEFAULT 'moderate'
  
  Check-in/out:
    - check_in_time: TIME, DEFAULT '15:00:00'
    - check_out_time: TIME, DEFAULT '11:00:00'
    - self_check_in: BOOLEAN, DEFAULT FALSE
  
  Status & Visibility:
    - status: ENUM('draft', 'active', 'inactive', 'suspended'), DEFAULT 'draft'
    - is_featured: BOOLEAN, DEFAULT FALSE
    - views_count: INTEGER, DEFAULT 0
    - bookings_count: INTEGER, DEFAULT 0
  
  Timestamps:
    - created_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP
    - updated_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP ON UPDATE
    - published_at: TIMESTAMP, NULLABLE
    - deleted_at: TIMESTAMP, NULLABLE (soft delete)

Indexes:
  - idx_property_host (host_id)
  - idx_property_status (status)
  - idx_property_category (category_id)
  - idx_property_price (price_per_night)
  - idx_property_location (for spatial queries)
  - idx_property_slug (slug)

Constraints:
  - CHECK (max_nights >= min_nights)
  - CHECK (status IN ('draft', 'active', 'inactive', 'suspended'))
  - UNIQUE (slug)
```

---

#### **3. CATEGORY Entity**

```yaml
Entity: Category
Purpose: Property types (apartment, villa, cabin, etc.)

Attributes:
  Primary Key:
    - category_id: UUID (Primary Key)
  
  Details:
    - name: VARCHAR(100), UNIQUE, NOT NULL
    - slug: VARCHAR(100), UNIQUE, NOT NULL
    - description: TEXT
    - icon: VARCHAR(100) (icon reference)
    - display_order: INTEGER, DEFAULT 0
  
  Timestamps:
    - created_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP
    - updated_at: TIMESTAMP

Indexes:
  - idx_category_slug (slug)
  - idx_category_order (display_order)
```

---

#### **4. LOCATION Entity**

```yaml
Entity: Location
Purpose: Detailed property addresses with GPS coordinates

Attributes:
  Primary Key:
    - location_id: UUID (Primary Key)
  
  Reference:
    - property_id: UUID, FOREIGN KEY → Property(property_id), UNIQUE, NOT NULL
  
  Address Components:
    - address_line1: VARCHAR(255), NOT NULL
    - address_line2: VARCHAR(255), NULLABLE
    - city: VARCHAR(100), NOT NULL
    - state_province: VARCHAR(100), NOT NULL
    - country: VARCHAR(100), NOT NULL
    - postal_code: VARCHAR(20)
  
  Geographic Coordinates:
    - latitude: DECIMAL(10, 8), NOT NULL
    - longitude: DECIMAL(11, 8), NOT NULL
  
  Additional Info:
    - neighborhood: VARCHAR(100)
    - directions: TEXT (how to reach the property)
  
  Timestamps:
    - created_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP
    - updated_at: TIMESTAMP

Indexes:
  - idx_location_property (property_id) - UNIQUE
  - idx_location_city (city)
  - idx_location_country (country)
  - idx_location_coordinates (latitude, longitude) - SPATIAL INDEX

Constraints:
  - CHECK (latitude BETWEEN -90 AND 90)
  - CHECK (longitude BETWEEN -180 AND 180)
```

---

#### **5. AMENITY Entity**

```yaml
Entity: Amenity
Purpose: Property features and facilities

Attributes:
  Primary Key:
    - amenity_id: UUID (Primary Key)
  
  Details:
    - name: VARCHAR(100), UNIQUE, NOT NULL
    - icon: VARCHAR(100)
    - category: ENUM('basic', 'entertainment', 'facilities', 'safety', 'accessibility')
    - description: TEXT
  
  Timestamps:
    - created_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP

Indexes:
  - idx_amenity_category (category)
```

---

#### **6. PROPERTY_AMENITY (Junction Table)**

```yaml
Entity: PropertyAmenity
Purpose: Many-to-many relationship between Properties and Amenities

Attributes:
  Composite Primary Key:
    - property_id: UUID, FOREIGN KEY → Property(property_id)
    - amenity_id: UUID, FOREIGN KEY → Amenity(amenity_id)
    - PRIMARY KEY (property_id, amenity_id)
  
  Timestamps:
    - created_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP

Indexes:
  - idx_prop_amenity_property (property_id)
  - idx_prop_amenity_amenity (amenity_id)

Constraints:
  - ON DELETE CASCADE for both foreign keys
```

---

#### **7. PROPERTY_PHOTO Entity**

```yaml
Entity: PropertyPhoto
Purpose: Property images and photos

Attributes:
  Primary Key:
    - photo_id: UUID (Primary Key)
  
  Reference:
    - property_id: UUID, FOREIGN KEY → Property(property_id), NOT NULL
  
  Photo Details:
    - url: VARCHAR(500), NOT NULL
    - thumbnail_url: VARCHAR(500)
    - caption: VARCHAR(255)
    - is_cover: BOOLEAN, DEFAULT FALSE
    - display_order: INTEGER, DEFAULT 0
  
  Metadata:
    - file_size: INTEGER (in bytes)
    - width: INTEGER
    - height: INTEGER
  
  Timestamps:
    - uploaded_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP
    - deleted_at: TIMESTAMP, NULLABLE (soft delete)

Indexes:
  - idx_photo_property (property_id)
  - idx_photo_cover (property_id, is_cover)
  - idx_photo_order (property_id, display_order)

Constraints:
  - CHECK (display_order >= 0)
```

---

#### **8. BOOKING Entity**

```yaml
Entity: Booking
Purpose: Property reservations made by guests

Attributes:
  Primary Key:
    - booking_id: UUID (Primary Key)
  
  References:
    - property_id: UUID, FOREIGN KEY → Property(property_id), NOT NULL
    - guest_id: UUID, FOREIGN KEY → User(user_id), NOT NULL
  
  Booking Dates:
    - check_in_date: DATE, NOT NULL
    - check_out_date: DATE, NOT NULL
    - num_nights: INTEGER, GENERATED ALWAYS AS (check_out_date - check_in_date) STORED
  
  Guest Details:
    - num_guests: INTEGER, NOT NULL, CHECK (num_guests > 0)
    - num_adults: INTEGER, DEFAULT 1
    - num_children: INTEGER, DEFAULT 0
    - num_infants: INTEGER, DEFAULT 0
  
  Pricing Breakdown:
    - base_price: DECIMAL(10,2), NOT NULL (price_per_night * num_nights)
    - cleaning_fee: DECIMAL(10,2), DEFAULT 0
    - service_fee: DECIMAL(10,2), NOT NULL
    - tax_amount: DECIMAL(10,2), DEFAULT 0
    - discount_amount: DECIMAL(10,2), DEFAULT 0
    - total_price: DECIMAL(10,2), NOT NULL
    - currency: VARCHAR(3), DEFAULT 'USD'
  
  Status Management:
    - booking_status: ENUM('pending', 'confirmed', 'checked_in', 'checked_out', 'cancelled', 'completed'), DEFAULT 'pending'
    - payment_status: ENUM('pending', 'paid', 'refunded', 'failed'), DEFAULT 'pending'
    - cancellation_reason: TEXT, NULLABLE
    - cancelled_by: UUID, FOREIGN KEY → User(user_id), NULLABLE
  
  Special Requests:
    - special_requests: TEXT
    - arrival_time: TIME
  
  Confirmation:
    - confirmation_code: VARCHAR(20), UNIQUE
  
  Timestamps:
    - created_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP
    - updated_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP ON UPDATE
    - confirmed_at: TIMESTAMP, NULLABLE
    - cancelled_at: TIMESTAMP, NULLABLE
    - completed_at: TIMESTAMP, NULLABLE

Indexes:
  - idx_booking_property (property_id)
  - idx_booking_guest (guest_id)
  - idx_booking_dates (check_in_date, check_out_date)
  - idx_booking_status (booking_status)
  - idx_booking_confirmation (confirmation_code)

Constraints:
  - CHECK (check_out_date > check_in_date)
  - CHECK (num_guests = num_adults + num_children)
  - CHECK (total_price >= 0)
  - UNIQUE (confirmation_code)
```

---

#### **9. PAYMENT Entity**

```yaml
Entity: Payment
Purpose: Financial transaction records

Attributes:
  Primary Key:
    - payment_id: UUID (Primary Key)
  
  References:
    - booking_id: UUID, FOREIGN KEY → Booking(booking_id), NOT NULL
    - payer_id: UUID, FOREIGN KEY → User(user_id), NOT NULL
  
  Payment Details:
    - amount: DECIMAL(10,2), NOT NULL, CHECK (amount > 0)
    - currency: VARCHAR(3), DEFAULT 'USD'
    - payment_method: ENUM('credit_card', 'debit_card', 'paypal', 'stripe', 'bank_transfer')
    - payment_type: ENUM('booking', 'refund', 'payout'), DEFAULT 'booking'
  
  Status:
    - payment_status: ENUM('pending', 'processing', 'completed', 'failed', 'refunded'), DEFAULT 'pending'
    - failure_reason: TEXT, NULLABLE
  
  External References:
    - transaction_id: VARCHAR(255), UNIQUE (Stripe/PayPal ID)
    - receipt_url: VARCHAR(500)
  
  Timestamps:
    - created_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP
    - processed_at: TIMESTAMP, NULLABLE
    - completed_at: TIMESTAMP, NULLABLE
    - refunded_at: TIMESTAMP, NULLABLE

Indexes:
  - idx_payment_booking (booking_id)
  - idx_payment_payer (payer_id)
  - idx_payment_status (payment_status)
  - idx_payment_transaction (transaction_id)

Constraints:
  - CHECK (amount > 0)
  - UNIQUE (transaction_id)
```

---

#### **10. REVIEW Entity**

```yaml
Entity: Review
Purpose: Property ratings and feedback from guests

Attributes:
  Primary Key:
    - review_id: UUID (Primary Key)
  
  References:
    - booking_id: UUID, FOREIGN KEY → Booking(booking_id), UNIQUE, NOT NULL
    - property_id: UUID, FOREIGN KEY → Property(property_id), NOT NULL
    - reviewer_id: UUID, FOREIGN KEY → User(user_id), NOT NULL
    - host_id: UUID, FOREIGN KEY → User(user_id), NOT NULL
  
  Overall Rating:
    - overall_rating: DECIMAL(2,1), NOT NULL, CHECK (overall_rating BETWEEN 1.0 AND 5.0)
  
  Detailed Ratings:
    - cleanliness_rating: INTEGER, CHECK (cleanliness_rating BETWEEN 1 AND 5)
    - accuracy_rating: INTEGER, CHECK (accuracy_rating BETWEEN 1 AND 5)
    - communication_rating: INTEGER, CHECK (communication_rating BETWEEN 1 AND 5)
    - location_rating: INTEGER, CHECK (location_rating BETWEEN 1 AND 5)
    - check_in_rating: INTEGER, CHECK (check_in_rating BETWEEN 1 AND 5)
    - value_rating: INTEGER, CHECK (value_rating BETWEEN 1 AND 5)
  
  Review Content:
    - comment: TEXT, NOT NULL
    - response: TEXT, NULLABLE (host's response)
    - response_at: TIMESTAMP, NULLABLE
  
  Visibility:
    - is_visible: BOOLEAN, DEFAULT TRUE
    - is_flagged: BOOLEAN, DEFAULT FALSE
    - flagged_reason: TEXT, NULLABLE
  
  Timestamps:
    - created_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP
    - updated_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP ON UPDATE

Indexes:
  - idx_review_booking (booking_id) - UNIQUE
  - idx_review_property (property_id)
  - idx_review_reviewer (reviewer_id)
  - idx_review_host (host_id)
  - idx_review_rating (overall_rating)
  - idx_review_visible (is_visible)

Constraints:
  - CHECK (overall_rating BETWEEN 1.0 AND 5.0)
  - UNIQUE (booking_id) - One review per booking
```

---

#### **11. MESSAGE Entity**

```yaml
Entity: Message
Purpose: Communication between users

Attributes:
  Primary Key:
    - message_id: UUID (Primary Key)
  
  Participants:
    - sender_id: UUID, FOREIGN KEY → User(user_id), NOT NULL
    - recipient_id: UUID, FOREIGN KEY → User(user_id), NOT NULL
    - booking_id: UUID, FOREIGN KEY → Booking(booking_id), NULLABLE
  
  Message Content:
    - subject: VARCHAR(255)
    - body: TEXT, NOT NULL
    - attachment_url: VARCHAR(500), NULLABLE
  
  Status:
    - is_read: BOOLEAN, DEFAULT FALSE
    - is_archived: BOOLEAN, DEFAULT FALSE
    - is_deleted_by_sender: BOOLEAN, DEFAULT FALSE
    - is_deleted_by_recipient: BOOLEAN, DEFAULT FALSE
  
  Timestamps:
    - created_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP
    - read_at: TIMESTAMP, NULLABLE

Indexes:
  - idx_message_sender (sender_id)
  - idx_message_recipient (recipient_id)
  - idx_message_booking (booking_id)
  - idx_message_conversation (sender_id, recipient_id, created_at)
  - idx_message_unread (recipient_id, is_read)

Constraints:
  - CHECK (sender_id != recipient_id)
```

---

#### **12. NOTIFICATION Entity**

```yaml
Entity: Notification
Purpose: System notifications to users

Attributes:
  Primary Key:
    - notification_id: UUID (Primary Key)
  
  Reference:
    - user_id: UUID, FOREIGN KEY → User(user_id), NOT NULL
  
  Notification Details:
    - type: ENUM('booking_confirmed', 'booking_cancelled', 'payment_received', 'new_message', 'review_received', 'property_approved')
    - title: VARCHAR(255), NOT NULL
    - message: TEXT, NOT NULL
    - action_url: VARCHAR(500) (link to relevant page)
  
  References (Optional):
    - related_booking_id: UUID, FOREIGN KEY → Booking(booking_id), NULLABLE
    - related_property_id: UUID, FOREIGN KEY → Property(property_id), NULLABLE
    - related_user_id: UUID, FOREIGN KEY → User(user_id), NULLABLE
  
  Status:
    - is_read: BOOLEAN, DEFAULT FALSE
    - is_sent_email: BOOLEAN, DEFAULT FALSE
    - is_sent_sms: BOOLEAN, DEFAULT FALSE
  
  Timestamps:
    - created_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP
    - read_at: TIMESTAMP, NULLABLE

Indexes:
  - idx_notification_user (user_id)
  - idx_notification_unread (user_id, is_read)
  - idx_notification_type (type)
  - idx_notification_created (created_at)
```

---

#### **13. PROPERTY_AVAILABILITY Entity**

```yaml
Entity: PropertyAvailability
Purpose: Property calendar and date-specific pricing

Attributes:
  Primary Key:
    - availability_id: UUID (Primary Key)
  
  Reference:
    - property_id: UUID, FOREIGN KEY → Property(property_id), NOT NULL
  
  Date Information:
    - date: DATE, NOT NULL
    - is_available: BOOLEAN, DEFAULT TRUE
  
  Custom Pricing:
    - price_override: DECIMAL(10,2), NULLABLE (override base price for this date)
    - min_nights_override: INTEGER, NULLABLE
  
  Timestamps:
    - created_at: TIMESTAMP, DEFAULT CURRENT_TIMESTAMP
    - updated_at: TIMESTAMP

Indexes:
  - idx_availability_property_date (property_id, date) - UNIQUE
  - idx_availability_date (date)

Constraints:
  - UNIQUE (property_id, date)
## STEP 2: DATABASE NORMALIZATION

### Current Status Analysis

**Your existing design is already in 3NF! Here's why:**

✅ **1NF (First Normal Form)**
- All attributes are atomic (no multi-valued fields)
- Each column contains values of single type
- No repeating groups

✅ **2NF (Second Normal Form)**
- No partial dependencies
- All non-key attributes fully depend on primary key

✅ **3NF (Third Normal Form)**
- No transitive dependencies
- Separate tables for related entities

### Improvements Made to Original Design

#### **Original Design Issues:**
```
❌ Property.amenities - storing comma-separated values
❌ Property.location - storing full address in one field
❌ Missing property photos management
❌ Missing availability calendar
❌ Missing notification system
❌ Review tied only to property, not booking
```

#### **Normalized Solution:**
```
✅ PropertyAmenity junction table (M:N relationship)
✅ Separate Location table (1:1 with proper indexing)
✅ PropertyPhoto table with ordering
✅ PropertyAvailability for calendar management
✅ Notification table for system alerts
✅ Review linked to booking for verification
```

---

## STEP 3: SQL SCHEMA IMPLEMENTATION

### Complete PostgreSQL Schema

```sql
-- Enable UUID extension
CREATE EXTENSION IF NOT EXISTS "uuid-ossp";

-- =====================================================
-- TABLE 1: USERS
-- =====================================================
CREATE TABLE users (
    user_id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
    email VARCHAR(255) UNIQUE NOT NULL,
    password_hash VARCHAR(255) NOT NULL,
    auth_provider VARCHAR(20) DEFAULT 'local' CHECK (auth_provider IN ('local', 'google', 'facebook')),
    oauth_id VARCHAR(255),
    
    first_name VARCHAR(100) NOT NULL,
    last_name VARCHAR(100) NOT NULL,
    phone_number VARCHAR(20),
    date_of_birth DATE,
    profile_picture VARCHAR(500),
    bio TEXT,
    
    role VARCHAR(20) DEFAULT 'guest' CHECK (role IN ('guest', 'host', 'admin')),
    is_host BOOLEAN DEFAULT FALSE,
    is_verified BOOLEAN DEFAULT FALSE,
    verification_token VARCHAR(255),
    email_verified_at TIMESTAMP,
    
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    last_login_at TIMESTAMP,
    deleted_at TIMESTAMP,
    
    CONSTRAINT check_email_format CHECK (email ~* '^[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Za-z]{2,}$')
);

CREATE INDEX idx_user_email ON users(email);
CREATE INDEX idx_user_role ON users(role);
CREATE INDEX idx_user_oauth ON users(auth_provider, oauth_id);
CREATE INDEX idx_user_deleted ON users(deleted_at) WHERE deleted_at IS NULL;

-- =====================================================
-- TABLE 2: CATEGORIES
-- =====================================================
CREATE TABLE categories (
    category_id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
    name VARCHAR(100) UNIQUE NOT NULL,
    slug VARCHAR(100) UNIQUE NOT NULL,
    description TEXT,
    icon VARCHAR(100),
    display_order INTEGER DEFAULT 0,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

CREATE INDEX idx_category_slug ON categories(slug);
CREATE INDEX idx_category_order ON categories(display_order);

-- =====================================================
-- TABLE 3: PROPERTIES
-- =====================================================
CREATE TABLE properties (
    property_id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
    host_id UUID NOT NULL REFERENCES users(user_id) ON DELETE CASCADE,
    category_id UUID REFERENCES categories(category_id) ON DELETE SET NULL,
    
    title VARCHAR(200) NOT NULL,
    description TEXT NOT NULL,
    slug VARCHAR(250) UNIQUE,
    
    max_guests INTEGER NOT NULL CHECK (max_guests > 0),
    bedrooms INTEGER NOT NULL CHECK (bedrooms >= 0),
    beds INTEGER NOT NULL CHECK (beds > 0),
    bathrooms DECIMAL(3,1) NOT NULL CHECK (bathrooms > 0),
    
    price_per_night DECIMAL(10,2) NOT NULL CHECK (price_per_night > 0),
    cleaning_fee DECIMAL(10,2) DEFAULT 0,
    service_fee_percentage DECIMAL(5,2) DEFAULT 10.00,
    currency VARCHAR(3) DEFAULT 'USD',
    weekend_price DECIMAL(10,2),
    
    min_nights INTEGER DEFAULT 1,
    max_nights INTEGER DEFAULT 365,
    instant_book BOOLEAN DEFAULT FALSE,
    cancellation_policy VARCHAR(20) DEFAULT 'moderate' CHECK (cancellation_policy IN ('flexible', 'moderate', 'strict', 'super_strict')),
    
    check_in_time TIME DEFAULT '15:00:00',
    check_out_time TIME DEFAULT '11:00:00',
    self_check_in BOOLEAN DEFAULT FALSE,
    
    status VARCHAR(20) DEFAULT 'draft' CHECK (status IN ('draft', 'active', 'inactive', 'suspended')),
    is_featured BOOLEAN DEFAULT FALSE,
    views_count INTEGER DEFAULT 0,
    bookings_count INTEGER DEFAULT 0,
    
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    published_at TIMESTAMP,
    deleted_at TIMESTAMP,
    
    CONSTRAINT check_nights CHECK (max_nights >= min_nights)
);

CREATE INDEX idx_property_host ON properties(host_id);
CREATE INDEX idx_property_status ON properties(status);
CREATE INDEX idx_property_category ON properties(category_id);
CREATE INDEX idx_property_price ON properties(price_per_night);
CREATE INDEX idx_property_slug ON properties(slug);
CREATE INDEX idx_property_featured ON properties(is_featured) WHERE is_featured = TRUE;

-- =====================================================
-- TABLE 4: LOCATIONS
-- =====================================================
CREATE TABLE locations (
    location_id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
    property_id UUID UNIQUE NOT NULL REFERENCES properties(property_id) ON DELETE CASCADE,
    
    address_line1 VARCHAR(255) NOT NULL,
    address_line2 VARCHAR(255),
    city VARCHAR(100) NOT NULL,
    state_province VARCHAR(100) NOT NULL,
    country VARCHAR(100) NOT NULL,
    postal_code VARCHAR(20),
    
    latitude DECIMAL(10, 8) NOT NULL,
    longitude DECIMAL(11, 8) NOT NULL,
    
    neighborhood VARCHAR(100),
    directions TEXT,
    
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    
    CONSTRAINT check_latitude CHECK (latitude BETWEEN -90 AND 90),
    CONSTRAINT check_longitude CHECK (longitude BETWEEN -180 AND 180)
);

CREATE INDEX idx_location_property ON locations(property_id);
CREATE INDEX idx_location_city ON locations(city);
CREATE INDEX idx_location_country ON locations(country);
CREATE INDEX idx_location_coords ON locations USING GIST (ll_to_earth(latitude, longitude));

-- =====================================================
-- TABLE 5: AMENITIES
-- =====================================================
CREATE TABLE amenities (
    amenity_id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
    name VARCHAR(100) UNIQUE NOT NULL,
    icon VARCHAR(100),
    category VARCHAR(20) CHECK (category IN ('basic', 'entertainment', 'facilities', 'safety', 'accessibility')),
    description TEXT,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

CREATE INDEX idx_amenity_category ON amenities(category);

-- =====================================================
-- TABLE 6: PROPERTY_AMENITIES (Junction Table)
-- =====================================================
CREATE TABLE property_amenities (
    property_id UUID REFERENCES properties(property_id) ON DELETE CASCADE,
    amenity_id UUID REFERENCES amenities(amenity_id) ON DELETE CASCADE,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    PRIMARY KEY (property_id, amenity_id)
);

CREATE INDEX idx_prop_amenity_property ON property_amenities(property_id);
CREATE INDEX idx_prop_amenity_amenity ON property_amenities(amenity_id);

-- =====================================================
-- TABLE 7: PROPERTY_PHOTOS
-- =====================================================
CREATE TABLE property_photos (
    photo_id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
    property_id UUID NOT NULL REFERENCES properties(property_id) ON DELETE CASCADE,
    
    url VARCHAR(500) NOT NULL,
    thumbnail_url VARCHAR(500),
    caption VARCHAR(255),
    is_cover BOOLEAN DEFAULT FALSE,
    display_order INTEGER DEFAULT 0,
    
    file_size INTEGER,
    width INTEGER,
    height INTEGER,
    
    uploaded_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    delete

### Relationships Summary

- **User → Property**: One-to-Many (A user can own multiple properties)
- **User → Booking**: One-to-Many (A user can make multiple bookings)
- **User → Review**: One-to-Many (A user can write multiple reviews)
- **Property → Booking**: One-to-Many (A property can have multiple bookings)
- **Property → Review**: One-to-Many (A property can have multiple reviews)
- **Booking → Payment**: One-to-One (Each booking has one payment)
- **Booking → Review**: One-to-One (Each booking can have one review)

## ✨ Feature Breakdown

This section provides an overview of the key features of the Airbnb Clone project, detailing how each feature contributes to the overall functionality of the platform.

### 1. User Management
**Description:**  
This feature handles user registration, login, authentication, and profile management for both guests and hosts. Users can create accounts, update their personal information, upload profile pictures, and manage their authentication credentials securely. This is the foundation of the platform, ensuring that each user has a personalized and secure experience while accessing the system.

---

### 2. Property Management
**Description:**  
Property management allows hosts to create, update, and delete property listings on the platform. Hosts can add detailed information such as property descriptions, pricing, location, amenities, photos, and availability calendars. This feature is essential for building the marketplace inventory and providing guests with comprehensive information to make informed booking decisions.

---

### 3. Search and Filtering
**Description:**  
This feature enables guests to search for properties based on various criteria such as location, price range, number of guests, dates, and amenities. Advanced filtering options help users quickly narrow down results to find properties that match their specific needs. A robust search system is critical for user satisfaction and ensures guests can easily discover suitable accommodations.

---

### 4. Booking System
**Description:**  
The booking system allows guests to reserve properties for specific dates, view availability calendars, and receive booking confirmations. It manages the entire booking lifecycle including booking creation, modification, cancellation, and status tracking (pending, confirmed, completed, cancelled). This is the core transactional feature that enables the platform's primary business function of connecting guests with properties.

---

### 5. Payment Integration
**Description:**  
This feature handles secure payment processing for bookings using integrated payment gateways like Stripe or PayPal. It manages payment authorization, capture, refunds, and maintains transaction records for both guests and hosts. Secure and reliable payment processing is crucial for building trust and ensuring smooth financial transactions on the platform.

---

### 6. Review and Rating System
**Description:**  
The review system allows guests to leave ratings and written feedback for properties after their stay, helping future guests make informed decisions. Hosts can also view and respond to reviews, creating transparency and accountability within the platform. This feature builds trust in the community and helps maintain quality standards across all listings.

---

### 7. Notifications System
**Description:**  
This feature sends real-time notifications to users about important events such as booking confirmations, payment receipts, check-in reminders, new messages, and review requests. Notifications can be delivered via email, SMS, or in-app alerts. Keeping users informed enhances engagement and ensures they don't miss critical updates about their bookings or listings.

---

### 8. Admin Dashboard
**Description:**  
The admin dashboard provides platform administrators with tools to monitor and manage the entire system, including user accounts, property listings, bookings, payments, and reported issues. Admins can view analytics, generate reports, handle disputes, and perform moderation tasks. This feature is essential for maintaining platform integrity, resolving issues, and making data-driven decisions.

---

### 9. Messaging System
**Description:**  
A built-in messaging system enables direct communication between guests and hosts to discuss property details, ask questions, or coordinate check-in arrangements. Real-time or asynchronous messaging helps facilitate smooth transactions and builds relationships between users. Clear communication channels reduce misunderstandings and improve the overall user experience.

---

### 10. Photo Management
**Description:**  
This feature allows hosts to upload, organize, and manage multiple high-quality photos for their property listings. Guests can view photo galleries to get a comprehensive visual understanding of the property before booking. High-quality images are crucial for attracting guests and setting accurate expectations about the property.

---

### 11. Availability Calendar
**Description:**  
The availability calendar displays property booking status across dates, allowing hosts to block unavailable dates and guests to see when properties can be booked. It prevents double bookings and provides a visual interface for managing property availability. This feature is fundamental for efficient inventory management and preventing scheduling conflicts.

---

### 12. User Authentication and Authorization
**Description:**  
This security feature manages user access control, ensuring that users can only perform actions they're authorized to do (e.g., hosts can edit their own properties, guests can cancel their own bookings). It implements secure authentication using JWT tokens or session management and enforces role-based permissions throughout the application. Proper authentication and authorization protect user data and maintain platform security.

## API Security

Security is a critical aspect of the Airbnb Clone project. This section outlines the key security measures that will be implemented to protect user data, ensure secure transactions, and maintain the integrity of the platform.

---

### 1. Authentication
**Implementation:**  
User authentication will be implemented using **JSON Web Tokens (JWT)** and **OAuth 2.0** for third-party login providers (Google, Facebook, etc.). When users log in, they receive a signed JWT token that must be included in subsequent API requests to verify their identity.

**Why It's Crucial:**  
Authentication ensures that only registered and verified users can access the platform's features. Without proper authentication, unauthorized users could impersonate others, access private data, make fraudulent bookings, or manipulate property listings. Protecting user accounts is the first line of defense in maintaining platform security and user trust.

---

### 2. Authorization
**Implementation:**  
Role-Based Access Control (RBAC) will be implemented to ensure users can only perform actions they are permitted to do. Authorization middleware will check user roles and permissions before allowing access to specific API endpoints (e.g., only hosts can edit their own properties, only admins can access the admin dashboard).

**Why It's Crucial:**  
Authorization prevents privilege escalation attacks where users might attempt to access resources or perform actions beyond their permissions. For example, without proper authorization, a guest could potentially modify another user's booking, delete property listings they don't own, or access sensitive payment information. This protects both user data and business operations.

---

### 3. Data Encryption
**Implementation:**  
All sensitive data will be encrypted both **in transit** (using HTTPS/TLS) and **at rest** (using database-level encryption). Passwords will be hashed using strong algorithms like **bcrypt** or **Argon2** before storage, and sensitive personal information will be encrypted in the database.

**Why It's Crucial:**  
Data encryption protects user information from being intercepted during transmission or accessed if the database is compromised. Without encryption, sensitive data like passwords, payment details, personal identification, and private messages could be exposed to attackers. This is essential for compliance with data protection regulations (GDPR, CCPA) and maintaining user trust.

---

### 4. Input Validation and Sanitization
**Implementation:**  
All user inputs will be validated on both client-side and server-side to ensure they meet expected formats and constraints. Input sanitization will be applied to prevent injection attacks by removing or escaping potentially harmful characters before processing data.

**Why It's Crucial:**  
Input validation prevents common security vulnerabilities such as SQL injection, Cross-Site Scripting (XSS), and command injection attacks. Attackers often exploit poorly validated inputs to inject malicious code, manipulate database queries, or execute unauthorized commands. Proper validation ensures that only safe, expected data is processed by the application.

---

### 5. Rate Limiting and Throttling
**Implementation:**  
API rate limiting will be implemented to restrict the number of requests a user or IP address can make within a specific time window (e.g., 100 requests per hour). This will be applied to sensitive endpoints like login, registration, and payment processing.

**Why It's Crucial:**  
Rate limiting protects against brute force attacks, credential stuffing, and Denial of Service (DoS) attacks. Without rate limiting, attackers could attempt thousands of login combinations to crack passwords, overwhelm the server with excessive requests causing downtime, or scrape large amounts of data. This measure ensures fair resource usage and maintains service availability for legitimate users.

---

### 6. CORS (Cross-Origin Resource Sharing) Policy
**Implementation:**  
CORS headers will be configured to allow requests only from trusted domains (the frontend application domain). This prevents unauthorized websites from making requests to the API on behalf of users.

**Why It's Crucial:**  
Proper CORS configuration prevents Cross-Site Request Forgery (CSRF) attacks where malicious websites could trick users' browsers into making unwanted requests to the API while they're authenticated. This protects users from having their accounts manipulated or data stolen through third-party sites.

---

### 7. HTTPS/SSL Encryption
**Implementation:**  
All API communications will be encrypted using HTTPS with SSL/TLS certificates. HTTP connections will be automatically redirected to HTTPS to ensure secure data transmission.

**Why It's Crucial:**  
HTTPS encryption prevents man-in-the-middle (MITM) attacks where attackers intercept network traffic to steal sensitive information like login credentials, session tokens, or payment details. This is especially critical for a booking platform where financial transactions occur and personal data is transmitted regularly.

---

### 8. Secure Payment Processing
**Implementation:**  
Payment processing will be handled through trusted third-party providers like **Stripe** or **PayPal**, which are PCI DSS compliant. The application will never store raw credit card numbers; instead, it will use tokenization where payment providers return secure tokens to represent payment methods.

**Why It's Crucial:**  
Secure payment processing is essential for protecting users' financial information and maintaining legal compliance. Payment data breaches can result in severe financial losses for users, legal penalties for the platform, loss of user trust, and damage to the platform's reputation. Using established payment processors reduces liability and ensures industry-standard security practices.

---

### 9. Security Headers
**Implementation:**  
HTTP security headers will be implemented including Content Security Policy (CSP), X-Content-Type-Options, X-Frame-Options, and Strict-Transport-Security. These headers will be configured in the web server (Nginx) and Django middleware.

**Why It's Crucial:**  
Security headers provide an additional layer of defense against common web vulnerabilities like clickjacking, MIME-type sniffing attacks, and XSS attacks. They instruct browsers on how to handle content and enforce security policies, making it harder for attackers to exploit client-side vulnerabilities.

---

### 10. Session Management
**Implementation:**  
Secure session management will be implemented with features like session expiration, secure cookie flags (HttpOnly, Secure, SameSite), and the ability to invalidate sessions on logout or password change. Sessions will be stored securely using Redis or database-backed sessions.

**Why It's Crucial:**  
Proper session management prevents session hijacking, session fixation, and unauthorized access through stolen session tokens. If sessions aren't properly secured, attackers could impersonate legitimate users by stealing their session IDs, gaining access to accounts without knowing passwords.

---

### 11. Database Security
**Implementation:**  
Database security will include using parameterized queries (via Django ORM) to prevent SQL injection, implementing proper database access controls with least privilege principles, regular backups with encryption, and separating database credentials from source code using environment variables.

**Why It's Crucial:**  
The database contains all critical application data including user credentials, personal information, booking details, and payment records. A compromised database could lead to massive data breaches, financial fraud, and complete system compromise. Protecting the database is fundamental to overall application security.

---

### 12. Logging and Monitoring
**Implementation:**  
Comprehensive logging will be implemented to track security events like failed login attempts, authorization failures, unusual activity patterns, and API errors. Logs will be monitored using tools like **Sentry** for error tracking and **Prometheus/Grafana** for performance monitoring.

**Why It's Crucial:**  
Logging and monitoring enable early detection of security incidents, suspicious activities, and potential breaches. Without proper logging, attacks could go unnoticed for extended periods, making it difficult to respond to threats, investigate incidents, or comply with security audit requirements. Real-time monitoring allows for rapid response to security threats.

---

### Security Best Practices Summary

The Airbnb Clone project follows these security principles:

- **Defense in Depth**: Multiple layers of security controls
- **Principle of Least Privilege**: Users and services have minimal necessary permissions
- **Secure by Default**: Security measures are built-in, not added as afterthoughts
- **Regular Security Audits**: Periodic review and testing of security measures
- **Security Updates**: Keeping all dependencies and frameworks up-to-date with security patches
- **User Education**: Providing guidance on creating strong passwords and recognizing phishing attempts

By implementing these comprehensive security measures, the Airbnb Clone platform ensures the protection of user data, secure financial transactions, and maintains the trust and confidence of both guests and hosts.

## 🔄 CI/CD Pipeline

### What is CI/CD?

**Continuous Integration (CI)** and **Continuous Deployment/Delivery (CD)** are modern software development practices that automate the process of integrating code changes, testing, and deploying applications.

- **Continuous Integration (CI)**: Automatically builds and tests code every time a developer commits changes to the repository. This ensures that new code integrates smoothly with the existing codebase and catches bugs early in the development process.

- **Continuous Deployment/Delivery (CD)**: Automatically deploys tested code to staging or production environments. Continuous Delivery means code is always ready to deploy, while Continuous Deployment automatically releases every change that passes tests to production.

---

### Why CI/CD is Important for This Project

CI/CD pipelines are crucial for the Airbnb Clone project for several reasons:

1. **Early Bug Detection**: Automated testing catches errors and bugs immediately after code is committed, reducing the cost and time of fixing issues later in the development cycle.

2. **Faster Development Cycles**: Automation eliminates manual build and deployment processes, allowing the team to release features and fixes more quickly and frequently.

3. **Consistent Quality**: Every code change goes through the same automated testing and validation process, ensuring consistent quality standards across all releases.

4. **Reduced Risk**: Smaller, incremental updates are less risky than large releases. Automated rollback capabilities allow quick recovery if issues arise.

5. **Improved Collaboration**: CI/CD encourages developers to integrate their work frequently, reducing merge conflicts and improving team collaboration.

6. **Reliable Deployments**: Automated deployment processes eliminate human error and ensure that deployments follow the same proven steps every time.

7. **Documentation and Traceability**: CI/CD pipelines create an audit trail of all changes, tests, and deployments, making it easier to track issues and understand the project's history.

---

### CI/CD Pipeline

The following tools will be used to implement the CI/CD pipeline for the Airbnb Clone project:

#### **GitHub Actions**
- **Purpose**: Primary CI/CD platform for automating workflows
- **Usage**: 
  - Run automated tests on every pull request
  - Build and validate code changes
  - Deploy to staging and production environments
  - Run security scans and code quality checks
- **Why**: Seamlessly integrates with GitHub repositories, provides free tier for public repos, and offers extensive marketplace of pre-built actions

#### **Docker**
- **Purpose**: Containerization platform for packaging applications
- **Usage**:
  - Create consistent development, testing, and production environments
  - Package the application with all its dependencies
  - Enable easy deployment across different platforms
  - Facilitate microservices architecture
- **Why**: Ensures "it works on my machine" problems are eliminated and simplifies deployment processes

#### **Docker Compose**
- **Purpose**: Multi-container orchestration tool
- **Usage**:
  - Define and run multi-container applications (backend, database, cache)
  - Manage local development environments
  - Simplify testing of the complete application stack
- **Why**: Makes it easy to spin up the entire application stack with a single command

#### **pytest (Python Testing)**
- **Purpose**: Testing framework for backend code
- **Usage**:
  - Write and run unit tests for Django models and business logic
  - Create integration tests for API endpoints
  - Generate test coverage reports
- **Why**: Provides simple, scalable test solutions with extensive plugin support

#### **Jest (JavaScript Testing)**
- **Purpose**: Testing framework for frontend code
- **Usage**:
  - Test React components and user interactions
  - Run snapshot tests
  - Measure code coverage
- **Why**: Fast, well-documented, and widely adopted in the React ecosystem

#### **ESLint & Prettier**
- **Purpose**: Code linting and formatting tools
- **Usage**:
  - Enforce consistent code style
  - Catch common programming errors
  - Automatically format code
- **Why**: Maintains code quality and readability across the team

#### **SonarQube / CodeClimate** (Optional)
- **Purpose**: Code quality and security analysis
- **Usage**:
  - Detect code smells and technical debt
  - Identify security vulnerabilities
  - Track code quality metrics over time
- **Why**: Provides insights into code maintainability and security issues

#### **Nginx**
- **Purpose**: Web server and reverse proxy
- **Usage**:
  - Serve static files
  - Act as a reverse proxy to the Django application
  - Handle SSL/TLS termination
- **Why**: High-performance, reliable, and widely used in production environments

#### **AWS / DigitalOcean / Heroku**
- **Purpose**: Cloud hosting platforms
- **Usage**:
  - Host the production application
  - Manage databases and storage
  - Scale resources as needed
- **Why**: Provides reliable infrastructure with easy deployment options

---

### CI/CD Pipeline Workflow

Here's how the CI/CD pipeline will work for the Airbnb Clone project:

#### **1. Code Commit**
- Developer pushes code changes to a GitHub branch
- GitHub Actions workflow is automatically triggered

#### **2. Continuous Integration Phase**
- **Build**: Application is built in a Docker container
- **Lint**: Code is checked for style and syntax errors using ESLint/Prettier
- **Test**: Automated tests run (unit tests, integration tests)
- **Security Scan**: Dependencies are checked for known vulnerabilities
- **Code Quality**: Code is analyzed for quality metrics

#### **3. Review and Approval**
- If all checks pass, the pull request is ready for review
- Team members review the code changes
- Once approved, code is merged into the main branch

#### **4. Continuous Deployment Phase**
- **Build Production Image**: Docker image is built for production
- **Push to Registry**: Image is pushed to Docker Hub or container registry
- **Deploy to Staging**: Application is automatically deployed to staging environment
- **Run Smoke Tests**: Basic functionality tests run on staging
- **Deploy to Production**: After manual approval or automatic promotion, application is deployed to production
- **Monitor**: Deployment is monitored for errors and performance issues

#### **5. Rollback (if needed)**
- If issues are detected, the pipeline can automatically rollback to the previous stable version

---

### Benefits Summary

Implementing a robust CI/CD pipeline for the Airbnb Clone project will:

- ✅ Automate repetitive tasks (testing, building, deploying)
- ✅ Reduce human error in the deployment process
- ✅ Enable faster feature delivery and bug fixes
- ✅ Improve code quality through automated checks
- ✅ Provide quick feedback to developers
- ✅ Create a reliable and repeatable deployment process
- ✅ Support scaling and growth of the application
- ✅ Enhance team productivity and collaboration

By leveraging modern CI/CD practices and tools, the development team can focus more on building features and less on manual processes, ultimately delivering a better product faster.

## Key Features

- User registration and authentication
- Property listing creation and management
- Advanced search and filtering capabilities
- Booking system with availability calendar
- Review and rating system
- Payment processing integration
- Real-time notifications
- User profile management
- Admin dashboard for platform management

## Getting Started

Instructions for setting up the development environment will be added as the project progresses.

## Project Timeline

- **Start Date**: October 13, 2025
- **End Date**: October 20, 2025

## Contributing

This project is part of a learning curriculum. Contribution guidelines will be established as the project develops.

## License

This project is created for educational purposes.

---

*This project is part of the ALX Software Engineering curriculum, focusing on backend development, database design, and full-stack application architecture.*