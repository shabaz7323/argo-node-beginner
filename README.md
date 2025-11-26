
# Beginner Argo CD Project – Node.js App

## Steps
1. Build & push Docker image:
   docker build -t your-dockerhub-username/argo-node-app:latest .
   docker push your-dockerhub-username/argo-node-app:latest

2. Update image name in k8s/deployment.yaml

3. Push repo to GitHub

4. Install Argo CD and apply:
   kubectl apply -f argo-application.yaml

5. Open Argo CD UI and sync the app.
