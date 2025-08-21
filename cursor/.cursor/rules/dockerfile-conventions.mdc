---
name: "dockerfile-conventions"
description: "Best practices for writing secure, efficient, and maintainable Dockerfiles"
globs: ["**/Dockerfile*", "**/*.dockerfile"]
---

# Dockerfile Conventions

## Security
- **Base Images:** Use official, minimal base images from trusted sources
- **User:** Run containers as non-root user when possible
- **Secrets:** Never hardcode secrets or sensitive information in Dockerfiles

## Efficiency
- **Layers:** Minimize the number of layers by combining RUN commands
- **Cache:** Order instructions to maximize Docker layer caching
- **Size:** Use multi-stage builds to reduce final image size

## Maintainability
- **Labels:** Add appropriate labels for metadata
- **Documentation:** Include clear comments for complex operations
- **Versioning:** Pin specific versions of packages and base images

## Best Practices
- **COPY vs ADD:** Prefer COPY over ADD unless you need ADD's special features
- **Working Directory:** Set WORKDIR before copying files
- **Health Checks:** Include HEALTHCHECK instructions when appropriate
