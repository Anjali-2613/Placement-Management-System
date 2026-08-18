# Placement Management System 🚀 (Work In Progress)

Welcome to the **Placement Management System**! This is a Salesforce-based application designed to streamline, automate, and manage the campus placement process efficiently. 

This repository contains the metadata, custom apps, objects, and screen flows for the system.

## 📌 Project Overview
The goal of this project is to simplify the placement drive lifecycle, allowing administrators and placement officers to track student registrations, company job openings, and interview rounds within Salesforce.

## ✨ Key Features (Current & Upcoming)
- **Student Registration Flow:** A guided `Student Registration SCN` screen flow deployed on the App Home Page for easy and quick student onboarding.
- **Custom App Layout:** Tailored Salesforce Lightning App interface customized for placement activities.
- **Data Management:** Custom objects and fields to accurately capture student metrics, company details, and placement history.

## 🛠️ Tech Stack & Tools Used
- **Platform:** Salesforce Lightning Experience (Developer Edition / Sandbox)
- **Automation:** Salesforce Flow Builder (Screen Flows)
- **Development Tooling:** Visual Studio Code (VS Code) & Salesforce CLI (SFDX)
- **Version Control:** Git & GitHub

## 🚀 How to Deploy this Metadata
If you want to pull or deploy this metadata into your own Salesforce Org, follow these steps:

1. Clone this repository to your local machine:
   ```bash
   git clone <YOUR_GITHUB_REPO_URL>
   ```
2. Open the folder in VS Code.
3. Authorize your Salesforce Org:
   ```bash
   sf org authorize web -a pms-dev
   ```
4. Deploy the source metadata to the org:
   ```bash
   sf project deploy start
   ```

---
*Note: This project is currently under active development.*
