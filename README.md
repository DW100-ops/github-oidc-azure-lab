GitHub Actions Azure OIDC Lab
This repository demonstrates GitHub Actions authentication to Microsoft Azure using OpenID Connect (OIDC) without using an Azure Client Secret.

Lab Objectives
Configure GitHub Actions OIDC authentication
Configure Microsoft Entra ID Federated Credentials
Authenticate GitHub Actions to Azure
Create an Azure Resource Group
Azure Resources
Application Registration:

github-oidc-lab-app
Repository
github-oidc-azure-lab
OIDC Flow
GitHub Actions → OIDC Token → Microsoft Entra ID → Azure Access Token → Azure Resource Group

Security Benefits
No Azure Client Secret
Short-lived access tokens
Reduced credential management
Improved security posture
