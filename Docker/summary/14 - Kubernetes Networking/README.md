# 14 - Kubernetes Networking

**Section Explanation:**
This section covers how networking works in Kubernetes, including pod-to-pod communication, services, DNS, and multi-service architectures. You'll learn how to connect applications and expose them both inside and outside the cluster.

This section covers **Kubernetes networking** concepts, including pod communication, services, and multi-container applications. You'll learn how containers communicate within and across pods in a Kubernetes cluster.

---

## Section Overview
This module explores Kubernetes networking patterns, from basic pod communication to complex multi-service architectures. You'll learn about services, DNS resolution, and how to build interconnected applications in Kubernetes.

---

## Topics Covered

### Introduction to Kubernetes Networking
- **Module Introduction**: Networking concepts and goals
- **Starting Project & Our Goal**: Multi-service application setup

### Basic Networking Concepts
- **Creating a First Deployment**: Basic pod deployment
- **Another Look at Services**: Service types and configuration
- **Multiple Containers in One Pod**: Pod-internal communication

### Advanced Networking
- **Pod-to-Pod Communication**: IP addresses and environment variables
- **Using DNS for Pod-to-Pod Communication**: Automatic domain resolution
- **Challenge Solution**: Practical networking exercises

### Frontend Integration
- **Adding a Containerized Frontend**: Frontend application deployment
- **Using a Reverse Proxy**: Load balancing and routing

---

## Resources

### Video Lectures (`.srt`)
- `233 Module Introduction_en.srt`
- `234 Starting Project & Our Goal_en.srt`
- `235 Creating a First Deployment_en.srt`
- `236 Another Look at Services_en.srt`
- `237 Multiple Containers in One Pod_en.srt`
- `238 Pod-internal Communication_en.srt`
- `239 Creating Multiple Deployments_en.srt`
- `240 Pod-to-Pod Communication with IP Addresses & Environment Variables_en.srt`
- `241 Using DNS for Pod-to-Pod Communication_en.srt`
- `242 Which Approach Is Best And a Challenge!_en.srt`
- `244 Challenge Solution_en.srt`
- `245 Adding a Containerized Frontend_en.srt`
- `246 Deploying the Frontend with Kubernetes_en.srt`
- `247 Using a Reverse Proxy for the Frontend_en.srt`
- `248 Module Summary_en.srt`

### Reference Materials
- `249 slides-kubernetes-network.pdf`: Networking concepts slides

### Code Projects
- `234 kub-network-01-starting-setup.zip`: Initial setup
- `236 kub-network-02-dummy-user-service.zip`: Basic service
- `238 kub-network-03-pod-internal.zip`: Pod communication
- `241 kub-network-04-automatic-domain-names.zip`: DNS resolution
- `244 kub-network-05-all-services-connected.zip`: Connected services
- `245 kub-network-06-added-frontend.zip`: Frontend integration
- `247 kub-network-07-finished.zip`: Complete networking solution

### External Resources
- `244 CORS-Tutorial.url`: CORS configuration guide

---

## Key Learning Outcomes
- Understand Kubernetes networking fundamentals
- Configure services for pod communication
- Implement DNS-based service discovery
- Build multi-service applications
- Handle frontend-backend communication

---

> **Pro Tip:** Practice with the progressive projects to understand how different networking patterns work in real applications. 