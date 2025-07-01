# 02 - Docker Images & Containers: The Core Building Blocks

**Section Explanation:**
This section dives into the two most fundamental concepts in Docker: images and containers. You'll learn what they are, how they work together, and how to build, run, and manage your own containers and images for real applications.

This section covers the fundamental concepts of Docker: **Images** and **Containers**. These are the two core building blocks that form the foundation of Docker technology. You'll learn how they work together, how to create and manage them, and how to build your own custom images.

---

## Section Overview
This module dives deep into the essential concepts of Docker. You'll understand what images and containers are, how they relate to each other, and how to work with both pre-built and custom images. The section includes hands-on practice with NodeJS and Python applications, covering everything from basic usage to advanced management techniques.

---

## Topics Covered

### Core Concepts
- **Images & Containers: What and Why**
  - Understanding the relationship between images and containers
  - How images serve as templates for containers
- **Image Layers & Read-Only Nature**
  - How Docker images are structured in layers
  - Why images are read-only and how this affects containers

### Working with Images
- **Using External (Pre-Built) Images**
  - Running containers from existing images
  - Understanding image repositories
- **Building Custom Images with Dockerfiles**
  - Creating your own Dockerfile
  - Understanding Dockerfile instructions
- **Image Management**
  - Inspecting images behind the scenes
  - Naming and tagging images
  - Deleting images

### Working with Containers
- **Container Lifecycle Management**
  - Creating and running containers
  - Stopping and restarting containers
  - Understanding attached vs detached containers
- **Interactive Mode & Container Access**
  - Entering running containers
  - Attaching to already-running containers
- **File Operations**
  - Copying files into and from containers
- **Automatic Cleanup**
  - Removing stopped containers automatically

### Sharing & Distribution
- **Image Sharing Overview**
- **Pushing Images to DockerHub**
- **Pulling & Using Shared Images**

---

## Resources

### Video Lectures & Subtitles (`.srt`)
- `018 Module Introduction_en.srt`
- `019 Images & Containers What and Why_en.srt`
- `020 Using & Running External (Pre-Built) Images_en.srt`
- `021 Our Goal A NodeJS App_en.srt`
- `022 Building our own Image with a Dockerfile_en.srt`
- `023 Running a Container based on our own Image_en.srt`
- `025 Images are Read-Only!_en.srt`
- `026 Understanding Image Layers_en.srt`
- `027 A First Summary_en.srt`
- `029 Managing Images & Containers_en.srt`
- `030 Stopping & Restarting Containers_en.srt`
- `031 Understanding Attached & Detached Containers_en.srt`
- `033 Entering Interactive Mode_en.srt`
- `034 Deleting Images & Containers_en.srt`
- `035 Removing Stopped Containers Automatically_en.srt`
- `036 A Look Behind the Scenes Inspecting Images_en.srt`
- `037 Copying Files Into & From A Container_en.srt`
- `038 Naming & Tagging Containers and Images_en.srt`
- `039 Sharing Images - Overview_en.srt`
- `040 Pushing Images to DockerHub_en.srt`
- `041 Pulling & Using Shared Images_en.srt`
- `043 Module Summary_en.srt`

### Reference Materials (`.pdf`)
- `044 Cheat-Sheet-Images-Containers.pdf`: Quick reference guide for images and containers
- `044 slides-images-containers.pdf`: Presentation slides covering all concepts

### HTML Resources
- `024 EXPOSE & A Little Utility Functionality.html`: Additional information about EXPOSE directive
- `028 Images & Containers.html`: Comprehensive reference for images and containers
- `032 Attaching to an already-running Container.html`: Guide for container attachment
- `042 Managing Images & Containers.html`: Detailed management guide
- `044 Module Resources.html`: Overview of all module resources

### Code Projects
- `021 nodejs-app-starting-setup.zip`: Starting code for NodeJS application
- `023 nodejs-app-first-dockerfile.zip`: NodeJS app with initial Dockerfile
- `026 nodejs-app-finished.zip`: Complete NodeJS application
- `033 python-app-starting-setup.zip`: Starting code for Python application
- `044 python-app-finished.zip`: Complete Python application

---

## Hands-On Projects

### NodeJS Application
- **Starting Setup**: Basic NodeJS app structure
- **First Dockerfile**: Initial containerization attempt
- **Finished Version**: Complete, working containerized application

### Python Application
- **Starting Setup**: Basic Python app structure
- **Finished Version**: Complete, working containerized application

---

## Key Learning Outcomes
By the end of this section, you will be able to:
- Understand the relationship between Docker images and containers
- Build custom Docker images using Dockerfiles
- Run and manage containers effectively
- Share and distribute your images
- Work with both pre-built and custom images
- Handle container lifecycle management
- Use interactive mode and file operations with containers

---

## How to Use These Resources
- **Start with the Module Introduction** to understand the section's goals
- **Follow the video lectures** in order for a structured learning path
- **Use the cheat sheet** as a quick reference during practice
- **Work through the code projects** to apply your knowledge
- **Review the slides** for a visual summary of concepts
- **Reference the HTML guides** for additional details and best practices

---

> **Pro Tip:** Practice building and running containers with both the NodeJS and Python applications to reinforce your understanding of the concepts. 