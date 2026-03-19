# 📦 SnapTest - Modern Web Application
[![Deploy Web App and Trigger Tests](https://github.com/amogh4432/SnapTest/actions/workflows/deploy_and_test.yml/badge.svg)](https://github.com/amogh4432/SnapTest/actions)

A lightweight, responsive web application built for high-performance user interactions. This repository serves as the "System Under Test" (SUT) for the SnapTest Automation suite.

## 🚀 Live Demo
**View the App here:** [https://amogh4432.github.io/SnapTest/](https://amogh4432.github.io/SnapTest/)

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **CI/CD:** GitHub Actions
* **Hosting:** GitHub Pages

## 🔄 Integrated CI/CD Flow
This repository is integrated with a **Cross-Repository Dispatch** system. 
1. Every `push` to `main` triggers an automatic deployment to GitHub Pages.
2. Once the deployment is live, this repo "pings" the **SnapTest_Automation** repository to start a full regression suite.

## 📁 Project Structure
- `/src`: Contains the application source code.
- `.github/workflows`: Contains the deployment and trigger logic.
