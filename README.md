# hello-idp

This is a **test Flask application** used to validate the **Internal Developer Platform (IDP)** workflow.  
It demonstrates the **end-to-end GitOps deployment**, including:

- Building a Docker image with GitHub Actions
- Pushing the image to **Artifact Registry**
- Updating the GitOps repository
- Automatic deployment to GKE via ArgoCD

---

## ⚙️ Purpose

This simple test application was used to verify that the IDP workflow is functioning correctly.  
When running, it can be accessed via HTTP and returns: **"Hello from Internal Developer Platform"**.  
It is not intended for production use and is currently inactive to minimize cloud costs.

---

## 📖 Documentation

Full platform workflow and details are documented in the main README of [internal-dev-platform](https://github.com/smithddevon/internal-dev-platform)