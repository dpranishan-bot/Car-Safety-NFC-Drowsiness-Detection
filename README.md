# 🚗 Tech Spartans – Smart Car Safety System

## 👥 Team
**Team Name:** Tech Spartans  
**Team Size:** 4 Members

## 📌 Project Overview

Tech Spartans presents an integrated Smart Car Safety System designed to improve driver authentication, vehicle access security, emergency operation, and driver safety.

The system combines two major safety modules:

1. 🔐 NFC-Based Driver Verification & Vehicle Access
2. 😴 Driver Drowsiness Detection Using Smart Glasses

---

## 🔐 Module 1 – NFC Driver Verification

The NFC-based system verifies the driver's identity before granting vehicle access.

### Workflow

NFC Tag → User Data → NFC Tap → Website → Document Verification → Age Verification → Access Decision → Engine Access

The user's demo identity information is stored on an NFC tag using a smartphone.

The prototype website receives the NFC data and performs simulated verification of:

- Aadhaar
- Driving Licence
- PAN
- Date of Birth / Age Eligibility

### Successful Verification

If all required information is verified and the driver is 18 years or above:

**ENGINE ACCESS: GRANTED**  
**ENGINE STATUS: STARTED**

### Failed Verification

If the driver is underage or required verification information is unavailable/invalid:

**ENGINE ACCESS: DENIED**  
**ENGINE START: NOT SUCCESSFUL**

> For demonstration purposes, only fictional/sample identity data is used.

---

## 🚨 Emergency Mode

The system also includes a separate Emergency Mode.

Before activation, the user is shown the applicable Terms & Conditions and must provide consent.

After consent, fingerprint authentication is performed.

### Workflow

Emergency Mode → Terms & Conditions → User Consent → Fingerprint Authentication → Emergency Mode Activated

The prototype can display relevant insurance/legal disclaimers for unauthorised or underage driving. Actual insurance coverage depends on the applicable policy and law.

---

## 😴 Module 2 – Driver Drowsiness Detection

The second module focuses on preventing accidents caused by driver fatigue or sleepiness.

Smart glasses are equipped with an eye-blink sensor that continuously monitors the driver's eye activity.

### Normal Condition

**EYE ACTIVITY: NORMAL**  
**DRIVER STATUS: ALERT**

### Drowsiness Condition

If the driver's eyes remain closed for an abnormal duration:

**DROWSINESS DETECTED**  
**DRIVER ALERT REQUIRED**  
**ALARM ACTIVATED**

An alarm alerts the driver and helps bring their attention back to the road.

---

## 🛠️ Technologies

- NFC
- Arduino / Embedded Systems
- Eye-Blink Sensor
- Fingerprint Sensor
- Smartphone
- Web Interface
- IoT / Smart Vehicle Safety Concepts
- Sensor-Based Driver Monitoring

---

## 🎯 Objectives

- Prevent unauthorised vehicle access
- Verify driver eligibility before vehicle access
- Provide an emergency authentication mechanism
- Detect driver drowsiness
- Alert the driver before a potential accident
- Demonstrate an affordable smart-vehicle safety prototype

---

## 🔄 Complete System

NFC Driver Verification
        ↓
Identity Verification
        ↓
Age Verification
        ↓
Access Decision
        ↓
Engine Access

AND

Smart Glasses
        ↓
Eye-Blink Monitoring
        ↓
Drowsiness Detection
        ↓
Alarm
        ↓
Driver Alert

---

## 👨‍💻 Team

### Team Spartans

A 4-member team developing innovative technology solutions for safer and smarter transportation.

**Team Members:**
1. Member 1
2. Member 2
3. Member 3
4. Member 4

---

## 🏆 Hackathon Project

Developed as a prototype for a college hackathon with the goal of combining **driver authentication, vehicle security and driver safety** into one integrated system.
