# Video Analysis Project – YOLO + ReID + CLIP Classification

## 📘 Overview
This project demonstrates a complete pipeline for:
1. **Tracking people** in videos using **YOLOv12 + BoT-SORT**  
2. **Extracting facial embeddings** with **InsightFace** for ReID (re-identification)  
3. **Performing clustering (DBSCAN)** to link appearances of the same person  
4. **Analyzing video segments** using **CLIP embeddings** to detect normal vs. criminal events  
5. Optionally, querying videos through **VLM (Vision-Language Models) APIs**

---

## ⚙️ Installation and Usage
1. **Clone or download** this repository.  
2. **Upload all files to Google Colab** — exactly as they appear here in the repository.  
3. **Run all notebook cells in order.**  
   - The code automatically installs all required dependencies.  
   - No manual setup is needed.  

---

## 📁 Files Overview
- `x.json` – contains ReID results structured by:
