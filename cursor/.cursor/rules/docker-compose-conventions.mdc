---
name: "docker-compose-conventions"
description: "Best practices for defining Docker Compose services for clarity, persistence, and reliability"
globs: ["**/docker-compose*.yml", "**/docker-compose*.yaml", "**/compose*.yml", "**/compose*.yaml"]
---

# Docker Compose Conventions

## Service Definition
- **Names:** Use descriptive, lowercase service names with hyphens
- **Images:** Specify exact image versions for reproducibility
- **Ports:** Map only necessary ports and use host:container format

## Persistence
- **Volumes:** Use named volumes for persistent data
- **Bind Mounts:** Use bind mounts sparingly and only for development
- **Data:** Ensure critical data is stored in persistent volumes

## Networking
- **Networks:** Use custom networks for service isolation
- **DNS:** Leverage Docker's built-in DNS for service discovery
- **Security:** Restrict network access to minimum required

## Reliability
- **Restart Policies:** Set appropriate restart policies for production services
- **Health Checks:** Include health checks for critical services
- **Dependencies:** Use depends_on for service startup order
