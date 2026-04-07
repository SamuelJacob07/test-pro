Act as a senior DevOps engineer and mentor.

Help me build a complete end-to-end CI/CD DevOps project using:

- AWS EC2 (Ubuntu, free-tier)
- Jenkins (Declarative Pipeline)
- Docker
- Docker Hub
- Kubernetes (Minikube)
- Prometheus & Grafana (lightweight)

Requirements:

1. Application:
   - Create a simple Python Flask app
   - Include: app.py and requirements.txt

2. Containerization:
   - Provide a Dockerfile to build the app image

3. Source Control:
   - Push code to a public GitHub repository

4. Jenkins CI/CD:
   - Install and configure Jenkins on EC2
   - Create a declarative pipeline that:
     - Clones GitHub repo
     - Builds Docker image
     - Pushes image to Docker Hub
     - Deploys to Kubernetes using kubectl

5. Kubernetes (Minikube):
   - Setup Minikube on EC2
   - Provide deployment.yaml and service.yaml
   - Expose application using NodePort or port-forward

6. Continuous Deployment:
   - On code change → rebuild and redeploy
   - Handle Docker image caching issue (use rollout restart or best practice)

7. Monitoring:
   - Install Prometheus and Grafana using Helm
   - Keep setup lightweight for low-memory EC2
   - Show how to access Grafana dashboard

8. Deliverables:
   - All configuration files (Dockerfile, Jenkinsfile, YAMLs)
   - Step-by-step Linux commands
   - Folder structure
   - Where to replace usernames (Docker Hub, GitHub)

9. Troubleshooting:
   - Common issues and fixes:
     - Image not updating
     - Jenkins permission issues
     - Minikube resource errors

10. Output Format:
   - Clear step-by-step guide
   - Commands + configs + brief explanations
   - Beginner-friendly but production-oriented

Constraints:
- Use minimal resources (free-tier EC2)
- Prefer simple, reliable setup
- Use best practices where possible

Goal:
I should be able to follow your steps and successfully build, deploy, and monitor the application using a full CI/CD pipeline.
