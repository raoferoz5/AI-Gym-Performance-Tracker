# 🏋️ AI Gym Performance Tracker
**A sophisticated workout analytics platform built with Python, featuring modular AI-ready architecture and data-driven insights.**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Kivy](https://img.shields.io/badge/Kivy-FFFFFF?style=for-the-badge&logo=kivy&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 🌟 Executive Summary
The **AI Gym Performance Tracker** is a professional-grade application designed to bridge the gap between manual workout logging and intelligent performance analytics. Built using **Modular Software Design** principles, it offers a scalable foundation for fitness enthusiasts and developers looking to integrate AI-driven health insights and computer vision form tracking.

---

## 📸 Interface Showcase

| **Main Dashboard** | **Workout Management** |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/02a39729-e55c-448f-bc90-b0a897c6b964" width="400" alt="Dashboard" /> | <img src="https://github.com/user-attachments/assets/b49ccae1-2ac1-4542-9587-02de1a29ccea" width="400" alt="Add Workout" /> |

| **Performance Analytics** |
| :---: |
| <img src="https://github.com/user-attachments/assets/ce60f37c-0ad7-424d-831b-e6237eee84cd" width="820" alt="Home Screen" /> |

---

## 🚀 Core Functionalities
*   **Dynamic Lifecycle Tracking:** Comprehensive CRUD operations for exercises, sets, repetitions, and weight resistance.
*   **Structured Data Persistence:** High-performance local storage utilizing an optimized SQLite relational schema.
*   **Automated Analytics Engine:** Built-in logic to analyze workout volume and progress trends over time.
*   **Professional Reporting:** Automated generation of summary reports for performance review and optimization.
*   **Cross-Platform UI:** Responsive interface developed with the Kivy framework, ready for desktop and mobile deployment.

## 🏗️ Technical Architecture
The repository is designed with high modularity to support enterprise-level scaling and AI integration:

*   **`main.py`**: Application entry point managing state and navigation.
*   **`database.py`**: Data Access Layer (DAL) handling all secure SQL operations.
*   **`ai_engine.py`**: Dedicated module for future Computer Vision (form analysis) integration.
*   **`ml_predictor.py`**: Predictive engine designed to forecast workload capacity and recovery.
*   **`report_generator.py`**: Business logic for transforming raw data into actionable performance summaries.

---

## 🛠️ Installation & Setup
```bash
# Clone the repository
git clone [https://github.com/raoferoz5/AI-Gym-Performance-Tracker.git](https://github.com/raoferoz5/AI-Gym-Performance-Tracker.git)

# Navigate to directory
cd AI-Gym-Performance-Tracker

# Launch application
python main.py
