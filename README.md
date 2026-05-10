# Restaurant POS & Automation System

A comprehensive digital ordering and receipt management solution built using the **Microsoft Power Platform**. This project streamlines the restaurant workflow from the initial customer order to automated email receipt delivery.

## 🚀 Project Overview
The **Om Zizo POS System** replaces manual ordering with a sleek, low-code interface. It handles complex pricing (half vs. full portions), calculates totals automatically, and triggers a backend workflow to process the data and notify management/customers via email.

## 🛠️ Tech Stack
* **Power Apps (Canvas App):** User interface and front-end logic.
* **Power Automate:** Backend orchestration and data processing.
* **SharePoint:** Data storage for menu items and order history.
* **Office 365 Outlook:** Automated email dispatching.

---

## 📱 Application Modules

### 1. Welcome & Branding
The landing page establishes the brand identity with a clean layout and a call-to-action to start the ordering process.

<img width="1191" height="677" alt="111" src="https://github.com/user-attachments/assets/5e664f3a-4ee9-4ad0-b536-02a5bfdcf6f9" />


### 2. Digital Menu & Order Entry
An interactive ordering board where users can:
* Select from a variety of items (Foul, Eggs, Cheese with Tomato, etc.).
* Choose portion sizes (Half/Full) with dynamic pricing.
* See the live total update as items are added.

<img width="1190" height="671" alt="222" src="https://github.com/user-attachments/assets/c7ff14ef-1a32-4fa2-80c6-1168a07374ab" />


### 3. Automated Receipt Generation
Once the order is confirmed, the system generates a professional digital invoice. This screen displays:
* Itemized breakdown of the order.
* Quantity and portion specifics.
* Final total calculation.
* Current timestamp and "Thank You" messaging.

<img width="467" height="668" alt="333" src="https://github.com/user-attachments/assets/3cc5dfd4-43ea-487e-b18b-6dd0fc610c93" />

### 4. Backend Workflow (Power Automate)
The app is integrated with a multi-step flow that automates the paperwork:
1.  **Trigger:** Receives data directly from the Power App.
2.  **Retrieval:** Fetches detailed item information from SharePoint.
3.  **Formatting:** Converts order data into a clean HTML table.
4.  **Notification:** Sends a structured email receipt via Outlook.

<img width="798" height="661" alt="444" src="https://github.com/user-attachments/assets/e376b065-ffe3-4c38-b2e3-16d017f1ac70" />


---

## 🔧 Key Features
* **Dynamic UI:** Built with localized Arabic support for seamless user experience.
* **Validation Logic:** Prevents errors in portion selection and quantity.
* **End-to-End Automation:** No manual entry is required after the order is submitted.
* **Scalable Architecture:** Easily expandable to include more menu items or different branches.

---

## 📖 How to Use
1.  Clone this repository.
2.  Import the **Power App** package into your environment.
3.  Connect the **SharePoint** lists used for data storage.
4.  Ensure the **Power Automate** flow is turned on and the connections are authenticated.
