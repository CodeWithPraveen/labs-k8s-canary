# Repository for the Kubernetes + Canary deployment lab

## Implement the Canary Deployment Strategy for a Weather App

## Overview
In this lab, you will create a canary deployment of the BrezyWeather API app in Kubernetes. This containerized app provides APIs to work with weather forecast details of a city. The main deployment will contain the app's initial version, while the patch version will contain the enhanced version that supports additional API endpoints. You'll create a Kubernetes deployment manifest for the main application version, followed by a Kubernetes service for the application, which you'll test to ensure it works correctly. Next, you'll deploy the patch version as part of the canary deployment strategy. Finally, you'll verify the canary deployment by checking the traffic redirections to both deployments.

## Learning Objectives
- Implement a canary deployment strategy in a Kubernetes cluster. 
- Creating Kubernetes deployment and service manifests.
- Safely deploy an update to a production app, minimizing service disruptions.
- Testing traffic redirections of deployed versions in the Kubernetes cluster.

## What will you learn?
- Canary deployment strategy
- Implementing canary deployments.
- Kubernetes deployment and service management.

## Prerequisites
- Basic understanding of Canary deployment strategy. 
- Basic understanding of Kubernetes concepts and terminology.
- Familiarity with Docker containerization technology.

## Hands-on Lab URL
https://www.udemy.com/labs/3476/overview
