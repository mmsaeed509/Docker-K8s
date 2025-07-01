# 12 - Kubernetes in Action: Diving into the Core Concepts

**Section Explanation:**
This section gives you hands-on experience with Kubernetes, teaching you how to create, manage, and update resources like pods, deployments, and services. You'll practice both imperative and declarative approaches to managing real workloads.

---

## Section Overview
This module takes you from theory to practice, teaching you how to create, manage, and configure Kubernetes resources. You'll learn both imperative and declarative approaches, understand resource management, and gain practical experience with core Kubernetes concepts.

---

## Topics Covered

### Setup and Prerequisites
- **Module Introduction**
  - Hands-on learning approach
  - Setup requirements
  - Learning objectives
- **Kubernetes does NOT manage your Infrastructure**
  - Infrastructure requirements
  - What you need to set up
  - Platform considerations
- **Kubernetes Required Setup & Installation Steps**
  - kubectl installation
  - Minikube setup
  - Local development environment

### Platform-Specific Setup
- **macOS Setup**
  - kubectl installation on macOS
  - Minikube configuration
  - Development environment setup
- **Windows Setup**
  - kubectl installation on Windows
  - Minikube setup for Windows
  - WSL2 considerations

### Core Kubernetes Concepts
- **Understanding Kubernetes Objects (Resources)**
  - Resource types and categories
  - Object specifications
  - Resource relationships
- **The Deployment Object (Resource)**
  - Deployment concepts
  - Pod management
  - Replica sets
- **The Service Object (Resource)**
  - Service types and purposes
  - Load balancing
  - Service discovery

### Hands-On Practice
- **A First Deployment - Using the Imperative Approach**
  - kubectl commands
  - Creating resources imperatively
  - Basic deployment operations
- **kubectl Behind The Scenes**
  - How kubectl works
  - API communication
  - Resource creation process

### Service Management
- **Exposing a Deployment with a Service**
  - Service creation
  - Port mapping
  - Access patterns
- **Restarting Containers**
  - Container lifecycle management
  - Restart strategies
  - Health monitoring

### Scaling and Updates
- **Scaling in Action**
  - Horizontal pod scaling
  - Resource management
  - Performance considerations
- **Updating Deployments**
  - Rolling updates
  - Update strategies
  - Version management
- **Deployment Rollbacks & History**
  - Rollback procedures
  - History management
  - Recovery strategies

### Advanced Configuration
- **The Imperative vs The Declarative Approach**
  - Command-line vs YAML
  - When to use each approach
  - Best practices
- **Creating a Deployment Configuration File (Declarative Approach)**
  - YAML syntax
  - Resource specifications
  - Configuration management
- **Adding Pod and Container Specs**
  - Container configuration
  - Resource limits
  - Environment variables

### Resource Management
- **Working with Labels & Selectors**
  - Labeling strategy
  - Selector patterns
  - Resource organization
- **Creating a Service Declaratively**
  - Service YAML configuration
  - Service types
  - Network policies
- **Updating & Deleting Resources**
  - Resource lifecycle management
  - Update procedures
  - Cleanup strategies

### Advanced Topics
- **Multiple vs Single Config Files**
  - File organization
  - Multi-file deployments
  - Configuration management
- **More on Labels & Selectors**
  - Advanced labeling
  - Complex selectors
  - Resource filtering
- **Liveness Probes**
  - Health checking
  - Probe configuration
  - Failure handling
- **A Closer Look at the Configuration Options**
  - Advanced configuration
  - Optimization techniques
  - Best practices

---

## Resources

### Video Lectures & Subtitles (`.srt`)
- `188 Module Introduction_en.srt`
- `189 Kubernetes does NOT manage your Infrastructure_en.srt`
- `190 Kubernetes Required Setup & Installation Steps_en.srt`
- `191 macOS Setup_en.srt`
- `192 Windows Setup_en.srt`
- `193 Understanding Kubernetes Objects (Resources)_en.srt`
- `194 The Deployment Object (Resource)_en.srt`
- `195 A First Deployment - Using the Imperative Approach_en.srt`
- `196 kubectl Behind The Scenes_en.srt`
- `197 The Service Object (Resource)_en.srt`
- `198 Exposing a Deployment with a Service_en.srt`
- `199 Restarting Containers_en.srt`
- `200 Scaling in Action_en.srt`
- `201 Updating Deployments_en.srt`
- `202 Deployment Rollbacks & History_en.srt`
- `203 The Imperative vs The Declarative Approach_en.srt`
- `204 Creating a Deployment Configuration File (Declarative Approach)_en.srt`
- `205 Adding Pod and Container Specs_en.srt`
- `206 Working with Labels & Selectors_en.srt`
- `207 Creating a Service Declaratively_en.srt`
- `208 Updating & Deleting Resources_en.srt`
- `209 Multiple vs Single Config Files_en.srt`
- `210 More on Labels & Selectors_en.srt`
- `211 Liveness Probes_en.srt`
- `212 A Closer Look at the Configuration Options_en.srt`
- `213 Summary_en.srt`

### Reference Materials (`.pdf`)
- `214 slides-kubernetes-action.pdf`: Comprehensive slides covering all concepts

### HTML Resources
- `214 Module Resources.html`: Overview of all module resources

### External Links (`.url`)
- `190 kubectl-Setup-Instructions-All-OS-.url`: kubectl setup guide
- `190 Minikube-Setup-Instructions-All-OS-.url`: Minikube setup guide
- `191 kubectl-Setup-macOS-.url`: macOS kubectl setup
- `191 Minikube-Setup.url`: macOS Minikube setup
- `192 kubectl-Setup-Windows-.url`: Windows kubectl setup
- `192 Minikube-Setup.url`: Windows Minikube setup

### Progressive Code Projects
Each zip file represents a step in the learning process:
- `195 kub-action-01-starting-setup.zip`: Initial Kubernetes setup
- `204 kub-action-02-declarative-approach-basics.zip`: Basic declarative approach
- `209 kub-action-03-merging-config-files.zip`: Multi-file configuration
- `210 kub-action-04-more-on-labels-and-selectors.zip`: Advanced labeling
- `212 kub-action-05-finished.zip`: Complete Kubernetes application

---

## Core Kubernetes Resources

### Pods
```yaml
apiVersion: v1
kind: Pod
metadata:
  name: my-pod
spec:
  containers:
  - name: my-container
    image: nginx:latest
```

### Deployments
```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: my-deployment
spec:
  replicas: 3
  selector:
    matchLabels:
      app: my-app
  template:
    metadata:
      labels:
        app: my-app
    spec:
      containers:
      - name: my-container
        image: nginx:latest
```

### Services
```yaml
apiVersion: v1
kind: Service
metadata:
  name: my-service
spec:
  selector:
    app: my-app
  ports:
  - port: 80
    targetPort: 80
  type: ClusterIP
```

---

## Learning Path

### Phase 1: Environment Setup
1. Install kubectl and Minikube
2. Set up local development environment
3. Verify installation and connectivity

### Phase 2: Basic Operations
1. Learn imperative commands
2. Create basic resources
3. Understand resource relationships

### Phase 3: Declarative Approach
1. Work with YAML configurations
2. Create complex resource definitions
3. Manage resource lifecycle

### Phase 4: Advanced Concepts
1. Implement health checks
2. Configure advanced features
3. Apply best practices

---

## Key Learning Outcomes
By the end of this section, you will be able to:
- Set up a local Kubernetes development environment
- Create and manage pods, deployments, and services
- Use both imperative and declarative approaches
- Configure resource specifications and limits
- Implement health checks and monitoring
- Apply labels and selectors effectively
- Manage resource updates and rollbacks

---

## How to Use These Resources
- **Follow the setup instructions** for your platform
- **Work through the progressive projects** to build experience
- **Practice with both imperative and declarative approaches**
- **Use the slides** for visual reinforcement
- **Reference the external links** for platform-specific guides

---

> **Pro Tip:** Practice creating resources using both imperative commands and declarative YAML files to understand the differences and when to use each approach. 