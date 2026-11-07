GitHub Actions Azure OIDC Lab
This repository demonstrates GitHub Actions authentication to Microsoft Azure using OpenID Connect (OIDC) without storing an Azure Client Secret.

Objectives
Authenticate GitHub Actions to Azure using OIDC
Use Microsoft Entra ID Federated Credentials
Eliminate Azure Client Secrets
Create and verify an Azure Resource Group
Azure Resources
Application Registration:

github-oidc-lab-app
Repository:

github-oidc-azure-lab
Workflow
The workflow:

Checks out the repository
Authenticates to Azure using OIDC
Verifies Azure authentication
Creates a Resource Group
Verifies the Resource Group
Security Benefits
OIDC provides:

No stored Azure Client Secret
Short-lived Azure access tokens
Improved credential security
Reduced secret management
Author
Created as part of a DevOps GitHub Actions OIDC lab.
