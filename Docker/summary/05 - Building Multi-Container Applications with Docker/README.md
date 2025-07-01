# 05 - Building Multi-Container Applications with Docker

**Section Explanation:**
This section guides you through building applications that use multiple containers, such as a database, backend, and frontend. You'll learn how to connect these services, manage their data, and create robust, scalable Dockerized solutions.

This section focuses on building **real-world multi-container applications** using Docker. You'll learn how to containerize complex applications with multiple services, implement proper networking, data persistence, and development workflows.

---

## Section Overview
This module takes you through building a complete multi-container application with MongoDB, Node.js backend, and React frontend. You'll learn how to containerize each service, set up networking between containers, implement data persistence, and create efficient development workflows with live code updates.

---

## Topics Covered

### Application Architecture
- **Our Target App & Setup**
  - Understanding the application structure
  - MongoDB database service
  - Node.js backend API
  - React frontend SPA
  - Service communication requirements

### Containerizing Individual Services
- **Dockerizing the MongoDB Service**
  - Setting up MongoDB container
  - Configuration and initialization
  - Data persistence considerations
- **Dockerizing the Node App**
  - Containerizing the backend API
  - Environment configuration
  - Dependencies and build process
- **Moving the React SPA into a Container**
  - Frontend containerization
  - Build process optimization
  - Static file serving

### Multi-Container Integration
- **Adding Docker Networks**
  - Setting up inter-container communication
  - Network configuration for services
  - Efficient cross-container communication
- **Adding Data Persistence**
  - MongoDB volume configuration
  - Data persistence across container restarts
  - Backup and recovery considerations

### Development Workflows
- **Volumes, Bind Mounts & Polishing**
  - Development vs production configurations
  - Code sharing and live updates
  - Optimizing development experience
- **Live Source Code Updates**
  - React container with bind mounts
  - Hot reloading and development efficiency
  - Real-time code changes

### Troubleshooting & Best Practices
- **Fixing MongoDB Authentication Errors**
  - Common authentication issues
  - Security best practices
  - Configuration troubleshooting

---

## Resources

### Video Lectures & Subtitles (`.srt`)
- `084 Module Introduction_en.srt`
- `085 Our Target App & Setup_en.srt`
- `086 Dockerizing the MongoDB Service_en.srt`
- `087 Dockerizing the Node App_en.srt`
- `088 Moving the React SPA into a Container_en.srt`
- `089 Adding Docker Networks for Efficient Cross-Container Communication_en.srt`
- `091 Adding Data Persistence to MongoDB with Volumes_en.srt`
- `092 Volumes, Bind Mounts & Polishing for the NodeJS Container_en.srt`
- `093 Live Source Code Updates for the React Container (with Bind Mounts)_en.srt`
- `094 Module Summary_en.srt`

### Reference Materials (`.pdf`)
- `095 slides-multi-container.pdf`: Presentation slides covering multi-container concepts
- `093 windows-wsl2-file-events.pdf`: Windows WSL2 file event considerations

### HTML Resources
- `090 Fixing MongoDB Authentication Errors (relevant for next lecture).html`: Troubleshooting guide
- `095 Module Resources.html`: Overview of all module resources

### Code Projects
- `085 multi-01-starting-setup.zip`: Initial multi-container application setup
- `095 multi-02-finished.zip`: Complete multi-container application

---

## Application Architecture

### Services Overview
- **MongoDB**: Database service with data persistence
- **Node.js Backend**: REST API service
- **React Frontend**: Single Page Application

### Communication Flow
- Frontend ↔ Backend API
- Backend API ↔ MongoDB
- All services connected via Docker networks

---

## Learning Path

### Phase 1: Understanding the Application
1. Analyze the target application structure
2. Understand service dependencies
3. Plan containerization strategy

### Phase 2: Individual Service Containerization
1. Containerize MongoDB service
2. Containerize Node.js backend
3. Containerize React frontend

### Phase 3: Multi-Container Integration
1. Set up Docker networks
2. Configure inter-service communication
3. Implement data persistence

### Phase 4: Development Optimization
1. Configure development workflows
2. Implement live code updates
3. Optimize development experience

---

## Key Learning Outcomes
By the end of this section, you will be able to:
- Design and implement multi-container applications
- Containerize different types of services (database, backend, frontend)
- Set up efficient inter-container communication
- Implement data persistence in multi-container environments
- Create development workflows with live code updates
- Troubleshoot common multi-container issues
- Apply best practices for containerized applications

---

## How to Use These Resources
- **Start with the application overview** to understand the target architecture
- **Follow the containerization process** for each service
- **Work with the complete application** to see all concepts in action
- **Use the slides** for visual reinforcement of concepts
- **Reference the troubleshooting guide** for common issues

---

> **Pro Tip:** Practice building the multi-container application step by step to understand how different services work together in a containerized environment. 