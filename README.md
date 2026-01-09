# 🧠 Custom Vision–Language Model for PCB Quality Inspection

## 📌 Overview
This repository presents the **system design and methodology** for a **custom Vision–Language Model (VLM)** developed for **industrial Printed Circuit Board (PCB) quality inspection**.

The solution is designed with a strong focus on:
- **Offline inference**
- **Low latency (< 2 seconds)**
- **High reliability and hallucination control**

The proposed model architecture is based on **Liquid AI’s Transformer (Liquid Foundation Model)**, selected for its efficiency, controllability, and suitability for safety-critical industrial environments.

---

## 🎯 Problem Statement
Manual PCB inspection is time-consuming, inconsistent, and prone to human error.  
Generic large Vision–Language Models often:
- hallucinate defects,
- fail to provide accurate spatial grounding,
- depend on cloud-based inference.

### Objective
Design a Vision–Language system that:
- analyzes PCB images,
- answers natural language inspection queries,
- outputs **structured results** (defect type, bounding box, confidence),
- runs **offline** with minimal inference latency.

---

## 🧩 Key Features
- Transformer-based **Vision–Language architecture**
- **Offline deployment** capability
- **Bounding box localization** for defect detection
- **Hallucination mitigation** using confidence gating
- **Parameter-efficient fine-tuning** (LoRA / QLoRA)
- Industrial-grade **structured JSON outputs**

---

## 🏗️ Model Architecture

### Selected Model
**Liquid Foundation Model (LFM) – Transformer Architecture**  
Developed by **Liquid AI**

📄 Reference Documentation:  
🔗 https://share.google/wdqQBMwHgrbOrnfNA

### High-Level Architecture Flow
