# ACME_CalculateSecurityHash_1_Dispatcher_WorkItemsExtraction

## 📌 Project Overview
This UiPath project is the **Dispatcher** part of the ACME Calculate Client Security Hash automation.  
It extracts **Work Items (WI5)** from the **ACME System 1 portal** and uploads them into an **Orchestrator Queue** for further processing by the Performer bot.

---

## 🛠 Features
- Built on **UiPath REFramework**.
- Logs into the **ACME System 1 web application**.
- Navigates to **Work Items**.
- Filters items of type **WI5 – Calculate Client Security Hash**.
- Extracts details (Client ID, Name, Country).
- Uploads extracted data to an **Orchestrator Queue**.
- Includes retry and exception handling mechanisms.

---

## 📂 Project Structure
- **Main.xaml** → Entry point of the automation.
- **Framework folder** → REFramework components (Init, GetTransactionData, Process, End).
- **Data folder** → Config file (`Config.xlsx`) containing app settings and credentials.
- **Screenshots / Logs** (optional) → Supporting references.

---

## 📋 Requirements
- UiPath Studio **2022.10+** (or higher).
- Access to **ACME System 1** demo website.
- UiPath Orchestrator account (for queues).
- Required packages:
  - UiPath.Excel.Activities
  - UiPath.System.Activities
  - UiPath.UIAutomation.Activities

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/ACME_CalculateSecurityHash_1_Dispatcher_WorkItemsExtraction.git
