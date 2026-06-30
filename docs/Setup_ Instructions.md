# Pre-requisite Setup

**Install Docker Desktop**
Docker Desktop is a free application that lets you run Docker containers on your computer.
Visit the official Docker Desktop download page: https://www.docker.com/products/docker-desktop/
Download OS specific Version, Install and restart to see docker instance running.
Use command prompt to ensure docker isntallation is successful - "docker --version"

**langflow on docker**
With Docker running, use this single command to download and start Langflow:
"docker run -it -p 7860:7860 langflowai/langflow:latest"
Once Completed,Open your web browser and go to:
http://localhost:7860

# Steps to get started on Langflow.
Start Creating workflows on langflow local instance.
User a Chat Input and connect it to an Agent.
Within each agent Connect to the Open AI using a valid API Key and select preferred LLM models.
Provide agent instructions in System prompts.
