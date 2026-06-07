# CPU Scheduler AI Simulator

An interactive full-stack web application designed to visualize and analyze CPU Scheduling Algorithms through animated simulations, real-time analytics, and AI-powered recommendations.

---

## 📌 Project Overview

The **CPU Scheduler AI Simulator** is an educational and diagnostic platform that bridges core Operating System concepts with modern web technologies. The simulator provides real-time animated visualization of how various CPU scheduling algorithms process workloads and optimize execution performance.

The platform helps students, educators, and developers understand scheduling behaviors through interactive simulations, industrial use-case presets, and performance comparisons.

---

# 🛠️ Tech Stack & System Architecture

## Frontend

* HTML5
* CSS3
* Vanilla JavaScript (ES6+)
* Glassmorphism UI Design
* Responsive Grid Layout
* CSS Flexbox Animations

## Backend & Database

* Supabase (PostgreSQL)
* Authentication & Session Management
* Row-Level Security (RLS)

## Data Visualization

* Chart.js
* Dynamic Gantt Charts
* Real-Time Performance Graphs

---

# ✨ Core Features

## 🔹 Dynamic Process Queue Management

Users can:

* Add or remove processes dynamically
* Customize Process IDs
* Modify:

  * Arrival Time
  * Burst Time
  * Priority Values

---

## 🔹 Multi-Algorithm Simulation Engine

The simulator supports:

### ✅ FCFS (First Come First Served)

Non-preemptive scheduling based on arrival order.

### ✅ SJF (Shortest Job First)

Schedules shortest burst tasks first.

### ✅ Priority Scheduling

Executes tasks according to assigned priorities.

### ✅ Round Robin

Preemptive scheduling using configurable Time Quantum.

---

## 🔹 Industrial Scenario Presets

### 🏦 Banking Operations (Round Robin)

Simulates transaction handling and report generation.

### 🏥 Hospital Emergency (Priority)

Models emergency-based scheduling and triage systems.

### 📟 Embedded Systems (SJF)

Represents sensor polling and short-cycle execution environments.

---

## 🔹 Live Visualization & Analytics

After simulation execution, the system displays:

* Animated Gantt Charts
* Comparative Bar Graphs
* Average Waiting Time Metrics
* Algorithm Efficiency Comparison

---

## 🔹 Smart AI Recommendation Engine

The built-in diagnostic engine:

* Recommends optimal scheduling algorithms
* Detects bottlenecks and convoy effects
* Provides workload optimization suggestions
* Evaluates latency and execution efficiency

---

## 🔹 Cloud-Based Simulation History

Authenticated users can:

* Store simulation logs in Supabase
* Access timestamped execution history
* Review previous scheduling runs

---

# 📈 Performance Metrics

The simulator calculates Average Waiting Time using:

WT = TAT - BT

Where Turnaround Time is:

TAT = Finish\ Time - Arrival\ Time

Average Waiting Time:

Avg\ WT = \frac{\sum_{i=1}^{n} WT_i}{n}

---

# 👥 Team & Credits

## 🚀 Development Group

**Logical Forge**

## 👨‍💻 Core Team

* Sachin Porwal
* Shreya Rai
* Sandhya Pal
* Viraj Bakshi

---

# 🌐 Deployment & Repository

## Live Deployment

Hosted using **Vercel**

## GitHub Repository

Source code available on GitHub.

---

# 🎯 Key Highlights

* Full-stack educational simulator
* Real-time scheduling visualization
* AI-powered optimization recommendations
* Responsive modern UI
* Cloud-backed telemetry history
* Industrial simulation presets
* Interactive analytics dashboard

---

# 📚 Educational Objective

This project was developed to simplify complex Operating System scheduling concepts through practical visualization and interactive experimentation, helping learners understand real-world CPU scheduling behaviors efficiently.
