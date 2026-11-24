# 🧵 Batik Cost Management App

A web application that helps batik producers calculate the true cost of production, from raw materials to waste disposal, and keep track of material stock in one place.

> **Portfolio showcase.** This repository is published to demonstrate my work. It is **not** an open-source project and is not licensed for reuse, redistribution, or contributions.

---

## 📸 VIDEO DEMO
https://youtu.be/to28-FKHrTM

---

## 📖 About the Project

Batik production involves many hidden costs, such as fabric and wax, water and electricity, labor, and waste handling. Without a clear breakdown, it is hard to price products properly or see where money is going.

This app lets users record each cost component for a production run, automatically calculates the total production cost, and presents everything in a clear summary that can be exported as a PDF report. It also includes material stock tracking so producers know what they have on hand.

---

## ✨ Features

### 1. Production Cost Calculation
Input and calculate the cost of batik production across four categories:

| Category | What it covers |
|---|---|
| **Material Cost** | Fabric, dyes, wax, and other raw materials |
| **Energy Cost** | Water and electricity usage |
| **System Cost** | Employee / labor costs |
| **Disposal Cost** | Waste management and disposal |

### 2. Cost Summary & PDF Report
- View a consolidated summary of all cost categories
- Generate and print a production cost report as a **PDF**

### 3. Material Stock Tracking
- Track available material stock
- Keep an overview of what is used and what remains

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Backend** | Laravel (PHP) |
| **Frontend** | React |
| **Database** | MySQL |

---

## 🏗️ Architecture Overview

```
┌──────────────┐      REST API      ┌──────────────┐      ┌──────────┐
│    React     │  ───────────────►  │   Laravel    │ ───► │  MySQL   │
│  (Frontend)  │  ◄───────────────  │  (Backend)   │ ◄─── │    DB    │
└──────────────┘       JSON         └──────────────┘      └──────────┘
                                           │
                                           ▼
                                     PDF Report
```

---

## 🎯 What I Learned / Highlights

- Designing a relational database schema for cost and inventory data
- Building a REST API with Laravel and consuming it from a React frontend
- Implementing cost aggregation and summary logic
- Generating printable PDF reports from application data
- Modeling a real-world small-business problem into a usable product

---


---

## 📄 License & Usage

This project is a **personal portfolio showcase**. All rights reserved. The source code is not be copied, modified, or distributed without permission.

---

## 👤 Role

**Chris** : Full Stack Developer
