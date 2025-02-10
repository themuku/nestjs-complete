# NestJS & Prisma Projects (100% Free Tools)  

---

## Mini-Projects  

### 1. Task Manager API  
**Objective**: Learn REST API basics with validation.  
**Features**:  
- CRUD operations for tasks.  
- Validation for task fields (title, description).  
- Error handling.  
**Tech Stack**:  
- NestJS, `class-validator`, in-memory array.  

---

### 2. Auth Service  
**Objective**: Implement JWT-based authentication.  
**Features**:  
- User registration/login.  
- Protected routes using guards.  
- Basic error handling.  
**Tech Stack**:  
- NestJS, JWT, in-memory array.  

---

### 3. Blog with Prisma  
**Objective**: Master Prisma with PostgreSQL.  
**Features**:  
- Create posts with titles/content.  
- User-post relationships (1:Many).  
- Filter posts by author/date.  
**Tech Stack**:  
- NestJS, Prisma, PostgreSQL.  

---

### 4. Product Catalog (MongoDB)  
**Objective**: Explore NoSQL with MongoDB.  
**Features**:  
- Product CRUD operations.  
- Category management.  
- Filter products by price/category.  
**Tech Stack**:  
- NestJS, Mongoose, MongoDB Atlas (free tier).  

---

### 5. CMS with RBAC  
**Objective**: Secure content management.  
**Features**:  
- Admin/Editor/Viewer roles.  
- Markdown content editing.  
- Audit logs for changes.  
**Tech Stack**:  
- NestJS, Prisma, Passport.js, PostgreSQL.  

---

### 6. GraphQL API  
**Objective**: Build a GraphQL server.  
**Features**:  
- Fetch posts with queries.  
- Create/update posts with mutations.  
- Error handling for GraphQL resolvers.  
**Tech Stack**:  
- NestJS, Apollo Server, Prisma.  

---

## Production Projects  

### 1. E-Commerce Platform  
**Objective**: Build a scalable e-commerce backend.  
**Features**:  
- User auth (JWT + Google OAuth2).  
- Product catalog with search/filters.  
- Shopping cart and mock payments.  
- Admin dashboard for order management.  
**Tech Stack**:  
- NestJS, Prisma (PostgreSQL), Redis.  
**Deployment**: Docker + Render (free tier).  

---

### 2. Learning Management System (LMS)  
**Objective**: Create a course management system.  
**Features**:  
- Course creation (text/PDFs).  
- Student progress tracking.  
- Role-based access (Admin/Instructor/Student).  
- Discussion forums (WebSockets).  
**Tech Stack**:  
- NestJS, Prisma (MongoDB Atlas), WebSockets.  
**Deployment**: Docker + Railway (free tier).  

---

### 3. Content Management System (CMS)  
**Objective**: Manage content with RBAC and media.  
**Features**:  
- Multi-role access (Admin/Editor).  
- Markdown content editing.  
- Media storage with MinIO (self-hosted S3).  
- SEO-friendly URLs.  
**Tech Stack**:  
- NestJS, Prisma (PostgreSQL), MinIO.  
**Deployment**: Docker + Railway.  

---

### 4. Social Media API  
**Objective**: Build a real-time social platform.  
**Features**:  
- User profiles, posts, comments, likes.  
- Follow/unfollow system.  
- Real-time notifications (WebSockets).  
**Tech Stack**:  
- NestJS, Prisma (PostgreSQL), Redis, WebSockets.  
**Deployment**: Docker + Render (free tier).  

---

## Deployment Projects  

### 1. Dockerize All Applications  
**Steps**:  
- Create `Dockerfile` for each project.  
- Use multi-stage builds for optimization.  
- Define services in `docker-compose.yml`.  

### 2. Deploy to Free-Tier Platforms  
**Options**:  
- **Render**: For PostgreSQL-based apps.  
- **Railway**: For MongoDB/PostgreSQL.  
- **MinIO**: Self-hosted storage for media.  

---

## Tools & Technologies  
- **Backend**: NestJS, Prisma.  
- **Databases**: PostgreSQL, MongoDB Atlas (free tier).  
- **Auth**: Google OAuth2, JWT.  
- **Deployment**: Docker, Render, Railway.  