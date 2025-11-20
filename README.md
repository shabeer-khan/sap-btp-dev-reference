# 📚 SAP BTP Application Development Reference Book: From Scratch

This repository contains the source code and comprehensive technical documentation for a "From Scratch" guide to developing applications on the **SAP Business Technology Platform (BTP)**.

The goal of this project is to build applications by **manually creating all required configuration files** (no CLIs or Wizards) to deeply understand the underlying technical architecture of BTP services, including CAP, UI5, XSUAA, and MTA deployment.

## 📖 The Reference Book (Wiki)

The full, detailed documentation, including concepts, step-by-step instructions, and explanations, is hosted on the **GitHub Wiki**. Each chapter builds upon the previous one.

| Chapter | Focus Area | Technical Outcome | Code Directory |
| :--- | :--- | :--- | :--- |
| **🌐 00** | **BTP Fundamentals & Tools** | Defines the BTP platform, architecture, and necessary development environment. | N/A |
| **🖼️ 01** | **Static HTML5 App** | Deploys a simple web page using the BTP HTML5 App Repository. | [`./Chapter-01-Static-HTML5-App`](./Chapter-01-Static-HTML5-App) |
| **🎨 02** | **Introduction to UI5** | Manually sets up a basic SAPUI5 application structure. | [`./Chapter-02-Introduction-to-UI5`](./Chapter-02-Introduction-to-UI5) |
| **🚀 03** | **Fiori Launchpad Integration** | Configures the **Managed Application Router** and integrates the UI5 app into the Fiori Launchpad Service. | [`./Chapter-03-Fiori-Launchpad-Setup`](./Chapter-03-Fiori-Launchpad-Setup) |
| **⚙️ 04** | **Basic CAP Service** | Creates a minimalist **Cloud Application Programming Model (CAP)** service project. | [`./Chapter-04-Basic-CAP-Service`](./Chapter-04-Basic-CAP-Service) |
| **💾 05** | **CAP & Persistence** | Integrates the CAP service with **HANA Cloud** persistence (manual configuration). | [`./Chapter-05-CAP-Persistence`](./Chapter-05-CAP-Persistence) |
| **📦 06** | **CAP Service Deployment** | Manual creation of the **`mta.yaml`** file for complex multi-module deployment. | [`./Chapter-06-CAP-Service-Deployment`](./Chapter-06-CAP-Service-Deployment) |
| **🔗 07** | **Connecting UI to CAP** | Completes the Full-Stack application by connecting the UI5 frontend to the deployed CAP service. | [`./Chapter-07-Full-Stack-Integration`](./Chapter-07-Full-Stack-Integration) |
| **🔒 08** | **Authentication & Auth** | Implementation of **XSUAA** for role-based access control and security. | [`./Chapter-08-Auth-and-Security`](./Chapter-08-Auth-and-Security) |
| **🤝 09** | **SaaS/Extensibility** | Advanced topics like Multi-Tenancy or S/4HANA side-by-side extension. | [`./Chapter-09-Advanced-Topics`](./Chapter-09-Advanced-Topics) |

---

### 💻 Getting Started

To follow along with the code samples:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/sap-btp-dev-reference.git](https://github.com/YourUsername/sap-btp-dev-reference.git)
    ```
2.  **Prerequisites:** Ensure you have access to an **SAP BTP Trial or Enterprise Account** and the **SAP Business Application Studio (BAS)** or a local **VS Code** environment with the necessary tools installed.

### 📝 Contribution / Feedback

This is an ongoing learning project. Feedback, corrections, and suggestions are welcome via GitHub issues or pull requests.

---

### License

This project is licensed under the [MIT License](LICENSE).
