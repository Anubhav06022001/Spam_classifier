---

# **SMS Spam Classifier**

This project is a machine learning application that classifies SMS messages as either spam or not spam. It provides an interactive web-based interface for users to input a message and check its classification. The app is deployed on Render for easy access.

## **Table of Contents**
- [Features](#features)
- [Setup Instructions](#setup-instructions)
  - [1. Setting Up the Virtual Environment](#1-setting-up-the-virtual-environment)
  - [2. Installing Requirements](#2-installing-requirements)
  - [3. Running the Application](#3-running-the-application)
- [Deployment](#deployment)
- [Live Demo](#live-demo)
- [Screenshots](#screenshots)
- 
---

## **Features**
- Classifies SMS messages as spam or not spam using machine learning.
- User-friendly web interface built with Flask.
- Deployed on Render for easy accessibility.

---

## **Setup Instructions**

### **1. Setting Up the Virtual Environment**
1. Open your terminal or command prompt.
2. Create a virtual environment with Python 3.9:
   ```bash
   conda create -p venv python=3.9 -y
   ```
3. Activate the virtual environment:
   ```bash
   conda activate venv/
   ```

### **2. Installing Requirements**
1. Ensure you’re in the project directory.
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### **3. Running the Application**
1. If using Jupyter Notebook:
   - Install Jupyter Notebook and the IPython kernel:
     ```bash
     pip install ipykernel
     pip install jupyter notebook
     ```
   - Launch the notebook:
     ```bash
     jupyter notebook
     ```
2. Run the application directly:
   ```bash
   python app.py
   ```

---

## **Deployment**

The application is deployed on [Render](https://render.com). Follow these steps to deploy it yourself:
1. Visit [Render's Dashboard](https://dashboard.render.com/web).
2. Click **New** and select **Web Services**.
3. Choose **Build and Deploy from a Git Repository** and click **Next**.
4. Configure the deployment settings:
   - Specify the branch and build command.
5. Trigger a manual deployment with the **Deploy Latest Commit** option.
6. Wait 2-3 minutes for the deployment to complete.

---

## **Live Demo**

Access the deployed application at:  
[**Spam Classifier on Render**](https://spam-classifier-ls1r.onrender.com)

---

## **Screenshots**

**Application Output**  
![Application output]("C:\Users\anubh\OneDrive\Pictures\Screenshots\Screenshot 2025-01-19 202623.png")

---
