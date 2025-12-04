# 🚖 Ride Sharing System  
*A Shell-Script Based Smart Ride-Sharing Platform using Dijkstra’s Algorithm*

<p align="center">
  <img src="https://img.shields.io/badge/Language-Bash-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Algorithm-Dijkstra's-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/OS-Linux%20(Ubuntu)-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Storage-Text%20Files-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/Course-Operating%20System%20Lab-red?style=for-the-badge">
</p>

---

## 📘 Overview

This project presents a **Ride Sharing System** implemented using **Bash Shell Scripting**, integrating **Dijkstra’s Algorithm** for optimal route planning.  
The system includes user & rider management, ride request handling, shortest-path calculation, and real-time matching.

It demonstrates strong fundamentals in:

- Linux Shell Scripting  
- Algorithm design  
- Data management  
- System automation  
- Menu-driven CLI applications  

---

## 📑 Table of Contents

- [Features](#-features)
- [System Architecture](#-system-architecture)
- [Tools & Technologies](#-tools--technologies)
- [Project Structure](#-project-structure)
- [Installation & Setup](#-installation--setup)
- [How It Works](#-how-it-works)
- [Algorithms](#-algorithms)
- [Screenshots](#-screenshots)
- [Performance Evaluation](#-performance-evaluation)
- [Limitations](#-limitations)
- [Future Enhancements](#-future-enhancements)
- [Project Report](#-project-report)
- [Authors](#-authors)

---

## Features

### Admin Panel
- Create / delete user accounts  
- Create / delete rider accounts  
- Add / delete locations  
- View all users, riders & locations  
- View complete ride history  

### User Panel
- View profile  
- Check ride history  
- Search for a ride  
- Automatic fare calculation  
- Cancel ride  

### Rider Panel
- View pending ride requests  
- Accept ride requests  
- Job assignment + ride update  

### Core System Features
- **Dijkstra’s Algorithm** for shortest distance  
- File-based database  
- Timestamp-based unique IDs  
- Real-time ride matching  

---

## System Architecture

```
User / Rider / Admin
        │
        ▼
Shell Script Menu
        │
        ├── User Module
        ├── Rider Module
        └── Admin Module
        │
        ▼
Text Files (Database)
admin.txt, userinformation.txt, riderinformation.txt,
location.txt, riderequest.txt, ridinginformation.txt
        │
        ▼
Dijkstra’s Algorithm
```

---

## 🛠️ Tools & Technologies

| Area | Technology |
|------|------------|
| Language | Bash (Shell Scripting) |
| Algorithm | Dijkstra’s Algorithm |
| Platform | Ubuntu / Linux |
| Storage | Text Files |
| Commands | grep, awk, sed, loops, functions |
| IDE | VS Code / Terminal |

---

## 📁 Project Structure

```
RideSharingSystem/
├─ ride.sh
├─ admin.txt
├─ userinformation.txt
├─ riderinformation.txt
├─ riderequest.txt
├─ ridinginformation.txt
├─ location.txt
└─ README.md
```

---

## Installation & Setup

### Requirements
- Linux OS (Ubuntu preferred)
- Bash shell
- Terminal / VS Code

### Run the Program

```bash
chmod +x ride.sh
./ride.sh
```

---

## How It Works

### User Workflow
1. Login / Create account  
2. Request ride  
3. System calculates shortest route  
4. Fare is automatically generated  
5. Rider accepts  
6. Ride completes & stored  

### Admin Workflow
- Manage all accounts, locations, and ride history  

### Rider Workflow
- Accept or reject ride requests  

---

## 🔢 Algorithms

### **Dijkstra’s Algorithm**
Used to compute the shortest path based on stored locations.

### 🔑 Unique ID Generation
```bash
id=$(date +%s)
```

### 🔒 Authentication
Matches data from:
- admin.txt  
- userinformation.txt  
- riderinformation.txt  

---

## Screenshots

> *Only the most important screenshots are included for clarity.*

### 🖥️ Main Menu  

![Main Menu](https://drive.google.com/uc?export=view&id=1bs-LDjLNsgJ3vgpRDSnWcGclWTkMtjGr)

---

### 🔐 Admin Login  
![Admin Login](https://drive.google.com/uc?export=view&id=10jdv2bSWHilcRjv7Kwh0fAjkIQ6YsmAv)

---

### 👤 Create User Account  
![Create User Account](https://drive.google.com/uc?export=view&id=1dkzwulZiaoxDFgEj571EHwJslPZm7OcQ)

---

### 🔍 Search Ride (Dijkstra + Fare)  
![Search Ride](https://drive.google.com/uc?export=view&id=1hiPrtkyuR4hc5LyJlCYGVp9xaCfIg1Y-)

---

### 🚴 Rider Accept Ride  
![Rider Accept Ride](https://drive.google.com/uc?export=view&id=1S-iTqBq3ZU2h--C4BlafBy3NLunIN_Dq)


---

## 📊 Performance Evaluation

- ✔ Fast execution time  
- ✔ Accurate distance & fare calculation  
- ✔ Clean and simple user workflow  
- ✔ Effective file-based data handling  

---

## ⚠️ Limitations

- Text files are not scalable  
- No real-time GPS tracking  
- No GUI (text-based only)  
- Passwords not encrypted  
- Concurrency issues possible  

---

## 🌟 Future Enhancements

- Move to SQL/NoSQL storage  
- Add graphical interface (JavaFX / Web App)  
- Real-time tracking  
- Smart dynamic pricing  
- OTP-based authentication  
- Mobile App version  

---

## 📄 Project Report

For full system explanation including **algorithms, evaluation, screenshots & details**, check the complete project report:

📥 **Project Report (PDF):**  
[Download Project Report (PDF)](https://drive.google.com/file/d/1CdSkJBRGYedwmjKJV-Pa-zh9TEq-sRAJ/view?usp=drive_link)


---

## 👨‍💻 Authors

- **Md. Zehadul Islam**  
- **Abir Al Anan** 



