# Marine Debris Detection System

海洋垃圾智慧辨識系統

A computer vision project that detects common marine debris using YOLOv11.

This project covers the complete workflow of an object detection system, including dataset preparation, annotation, data augmentation, model training, API development, Docker containerization, and cloud deployment.

---

## Project Overview | 專案概述

本專案旨在建立一套海洋垃圾物件辨識系統（Marine Debris Detection System），利用 YOLOv11 模型辨識常見海洋垃圾，並完整實作從資料集建置到模型部署的流程。

專案內容涵蓋：

- 資料收集（Dataset Collection）
- 資料標註（Annotation）
- 資料增強（Data Augmentation）
- YOLOv11 模型訓練（Model Training）
- 模型評估（Model Evaluation）
- FastAPI 開發（API Development）
- Docker 容器化（Containerization）
- 雲端部署（Cloud Deployment）

This project focuses on building an end-to-end computer vision pipeline for marine debris detection using YOLOv11.

The project includes:

- Dataset Collection
- Annotation
- Data Augmentation
- Model Training
- Model Evaluation
- FastAPI Development
- Docker Containerization
- Cloud Deployment

---

## Target Classes | 目標辨識類別

Current planned classes:

- Plastic Bottle
- Can
- Plastic (Bag)
- unknow (Fishing Net...)
- Foam

（Classes may be adjusted after dataset inspection.）
（實際類別將依資料集分析結果進行調整。）

---

## Project Status | 專案進度

- [x] Project Planning
- [x] Git & GitHub Setup
- [x] Python Virtual Environment Setup
- [ ] Dataset Audit
- [ ] Annotation
- [ ] Data Augmentation
- [ ] YOLOv11 Training
- [ ] Model Evaluation
- [ ] FastAPI Development
- [ ] Docker Containerization
- [ ] Cloud Deployment