# Basic CI Pipeline with GitHub Actions

This repository contains a simple **Continuous Integration (CI) pipeline** built with **GitHub Actions**.  
It was created for learning purposes and to demonstrate a basic pipeline configuration.

## 🚀 Pipeline Overview
The workflow file is located at:  
`.github/workflows/ci.yml`

### Steps included:
- ✅ **Checkout Code** → Get the source code from GitHub  
- ⚙️ **Setup Node.js** → Configure Node.js (version 18)  
- 📦 **Install Dependencies** → Run `npm install`  
- 🧪 **Run Tests** → Run `npm test`  
- 📤 **Simulate Deploy** → Simulate a successful deploy to staging  
- ❌ **Simulate Deploy Failure** → Simulate a failed deploy (pipeline stops here)  

## 🛠️ How it works
- The workflow runs automatically on:
  - Every push to the `main` branch  
  - Every pull request targeting the `main` branch  

## 📊 Example
Check the **Actions** tab in this repository to see the pipeline executions and results.

## 📌 Notes
- This project is for **educational purposes** only.  
- No real deployment is performed — deploy steps are only simulations. 
