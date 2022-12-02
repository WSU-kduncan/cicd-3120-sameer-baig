# Project Overview

- Project Overview: Using containers to run a website with the required dependencies like apache2
- Part 4 - Diagramming goes here

# Run Project Locally

- Downloaded Docker from desktop
- Dockerfile includes off of what image to build off of, what things to isntall and update, and copy from whatever host directory to a container directory
- docker build -t project:latest -t project:0.1 .
	- docker run --name website -it -p 8080:80 project 
- localhost:80

# DockerHub

- 
- How to authenticate with DockerHub via CLI using Dockerhub credentials
  - Credentials: Authentication tokens
- 

# GitHub Actions

- Configuring GitHub Secrets
  - What secrets were set based on what info
- Behavior of GitHub workflow
  - Jobs done when triggered by a certain event. 
  - 

# Deployment

- Description of container restart script
- Setting up a webhook on the server
  - How you created you own listener
  - How you installed the [webhook on GitHub](https://github.com/adnanh/webhook)
  - How to keep the webhook running if the instance is on
- Description of Webhook task definition file
- Steps to set up a notifier in GitHub or DockerHub
