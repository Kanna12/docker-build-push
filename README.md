## Docker Build and Push at Pod Level
This solution allows DevOps teams to build and push Docker images directly at the pod level in Kubernetes. Once the job is completed, the pod can be safely deleted, ensuring a clean and efficient workflow for image creation and deployment.

Features:
Build Docker Images: Easily build Docker images within a Kubernetes pod.

Push to Docker Repositories: Push images to your specified Docker registry (e.g., ECR).

Auto Cleanup: The pod is deleted automatically after the job completes, ensuring no leftover resources.

Ideal for automating the CI/CD pipeline and handling Docker image builds directly from Kubernetes environments.
