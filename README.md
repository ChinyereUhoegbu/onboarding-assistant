This project was created for my MIT programme (University of Lagos - MIT 811)
# IT Onboarding Assistant

A role-based onboarding assistant for IT Staff, Managers, and Administrators, designed to standardize and streamline the onboarding of new hires across the EMEA region.  

🔗 **Live Demo (GitHub Pages):** (https://chinyereuhoegbu.github.io/onboarding-assistant/)

## 📌 Problem Statement
This project has been initiated to streamline and standardize the IT onboarding process for new agents in the EMEA region.  

Currently, onboarding new hires involves multiple **manual steps** such as account creation, license assignment, and system verification. These steps vary depending on the user’s license type (F1, F3, or E3), but there is no centralized guide or tool to ensure consistency across IT and helpdesk teams.  

As a result, the onboarding process is prone to **inefficiencies, delays, and errors**, which negatively impact IT operations and the new hire experience.  

## ❌ Current Problems Faced
- Lack of standardized workflows for IT onboarding across different license types.  
- Manual and inconsistent task tracking → missed or duplicated steps.  
- No centralized knowledge base guiding IT staff on the correct onboarding sequence.  
- Difficulty in tracking progress for a batch of new hires.  
- Increased risk of delays in system readiness for agents on **Day 1**.  

## ✅ What the Application Does
- Provides a centralized **Onboarding Assistant** tool for IT teams.  
- Displays **onboarding workflows tailored to each license type (F1, F3, E3)**.  
- Allows IT staff to generate **task checklists** for individual hires or batches.  
- Enables **progress tracking** through tick-off checklists.  
- Includes a **reset function** for new onboarding cycles.  
- Is lightweight, accessible, and hosted using **cost-free or low-cost technology** (GitHub Pages).  

## 🧪 Proof of Concept
This application currently serves as a **proof of concept** for an IT Onboarding Assistant.  

It demonstrates how IT Staff, Managers, and Administrators can interact with standardized onboarding workflows in a lightweight, browser-based solution.  

The PoC validates the following:
- Role-based views and permissions (Staff, Manager, Administrator).  
- Workflow definition, publishing, and usage.  
- Checklist tracking with progress states (completed, pending, ignored).  
- Basic audit logging for accountability.  

## ➡️ Future iterations could expand this into a production-grade solution with:  
- Secure authentication (Azure AD, OAuth).  
- Persistent backend database (instead of localStorage).  
- Integration with ticketing systems (e.g., ServiceNow, Odoo, Jira).  
- CI/CD pipelines for automated deployment.  

## 🎯 Objectives
- Standardize the IT onboarding process across the EMEA region.  
- Reduce errors and delays by providing guided, license-type-specific flows.  
- Improve efficiency for IT and helpdesk teams with simpler task management.  
- Enhance visibility and accountability in the onboarding process.  
- Deliver a practical, easy-to-use tool (“Onboarding Assistant”) as both a **guide and tracker**.  

## 📈 Expected Improvements
When these objectives are achieved, the project will:  
- Increase accuracy and consistency in new hire onboarding.  
- Improve readiness of new agents on **Day 1**.  
- Reduce dependency on manual tracking or memory.  
- Support scalability as the workforce grows.  
- Contribute to a better **employee experience** through timely provisioning of accounts and tools.  

## 🚀 Features
### IT Staff
- Create and track onboarding checklists.  
- Complete or ignore tasks, and save/load progress.  
### IT Manager
- Define, edit, and publish workflows for F1, F3, and E3 licenses.  
- View all checklists created by staff.  
- Track metrics (e.g., total checklists, completed tasks).  
### Administrator
- Manage users (create, delete, assign roles).  
- Oversee system configuration.  
- View detailed audit logs of all onboarding activities.  

## ⚙️ How to Use
1. Clone the repo
2. Open index.html in your browser.
3. Log in with one of the sample accounts:
Staff: staff / staff123
Manager: manager / manager123
Admin: admin / admin123

4. Start exploring role-based features.
