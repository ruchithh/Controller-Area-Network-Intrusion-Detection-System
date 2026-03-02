# 🚗 CAN-IDS-System

### Controller Area Network Intrusion Detection System

## 📌 Overview

This project implements a **real-time Intrusion Detection System (IDS)** for automotive Controller Area Network (CAN) communication using ESP32.
The system monitors CAN messages and detects malicious or abnormal traffic to improve vehicle network security.

## 🎯 Objectives

* Monitor CAN bus communication
* Detect spoofing and abnormal CAN messages
* Simulate attacker node behavior
* Provide real-time intrusion alerts

## 🏗️ System Architecture

![Architecture](ARCHITECTURE_IMAGE.png)

## ⚙️ Hardware Used

* ESP32 Development Board
* MCP2515 CAN Module
* CAN Transceiver
* Push Button (Attack Simulation)

## 📂 Project Structure

ATTACKER_NODE – Generates malicious CAN frames
BRAKE_ECU – Simulated brake ECU
SPEED_ECU – Speed control ECU
IDS_MONITOR – Intrusion detection logic

## 🚨 Features

* Real-time CAN monitoring
* Attack simulation
* Embedded IDS implementation
* Lightweight automotive cybersecurity model

## ▶️ Demo

See OUTPUT_VIDEO.mp4 for system output demonstration.

## 👨‍💻 Author

Kairamkonda Ruchith

## 🤝 Collaboration

Developed as part of an academic team project.
This repository represents my implementation and maintained version.
