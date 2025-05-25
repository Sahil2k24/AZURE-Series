# ☁️ Azure Learning Journey – Week 12 🚀

**Topic:** *Azure IAM & Managed Identities 🔑*

This week’s focus was on strengthening **cloud security** with Azure's Identity and Access Management (IAM) capabilities and understanding how **Managed Identities** simplify secure access across Azure services.

---

## 📌 Key Concepts Covered

### 🔐 Azure Identity and Access Management (IAM)

Azure IAM allows you to manage **who has access to what** in your cloud environment.

* Uses **Role-Based Access Control (RBAC)** to assign permissions based on roles (e.g., Reader, Contributor, Owner).
* Grants **fine-grained access** to Azure resources and enhances overall security posture.

### 🌐 Microsoft Entra ID (formerly Azure AD)

* Centralized identity platform for managing users, groups, and devices.
* Supports **Single Sign-On (SSO)** and **multi-factor authentication (MFA)**.
* Critical for user authentication and identity federation in enterprise environments.

---

## 🔄 Service Principals vs. Managed Identities

| Feature              | Service Principal                 | Managed Identity                      |
| -------------------- | --------------------------------- | ------------------------------------- |
| Use Case             | Authenticate non-human apps       | Authenticate within Azure environment |
| Secret/Password Mgmt | Requires manual secret management | No secret handling—managed by Azure   |
| Scope                | Works inside & outside Azure      | Works only within Azure               |
| Security             | Potential risk if secrets leaked  | More secure—no credentials exposed    |

---

## 🧪 Hands-On Demo

✅ **Objective:** Access Azure Blob Storage securely from a Virtual Machine
✅ **Approach:**

1. Enabled a **System-Assigned Managed Identity** on the VM
2. Granted RBAC role (e.g., `Storage Blob Data Contributor`) on the storage account
3. Used Azure CLI on VM to retrieve and interact with Blob Storage securely—**no secrets involved!**

---

## 🔐 Why Use Managed Identities?

* Eliminates hardcoded credentials in code
* Reduces risk of leaked secrets
* Seamless integration with services like Azure Functions, VMs, Logic Apps, and AKS

---

## 💬 Let’s Talk

How are you managing authentication in your Azure or multi-cloud environments?
Have you implemented **Managed Identities** yet? Share your experience below! 👇

---

## 🔗 Stay Connected

🔗 [LinkedIn – Sahil Patil](https://www.linkedin.com/in/sahil-cloudgeek/)
🐙 [GitHub – Sahil2k24](https://github.com/Sahil2k24)

---

> **“Secure access starts with smart identity design—IAM and Managed Identities make that effortless.”** 🔐🚀

---
