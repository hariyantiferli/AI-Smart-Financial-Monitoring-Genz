# AI-Smart-Financial-Monitoring-Genz

## Overview

AI pipeline untuk menganalisis struk belanja dan menghasilkan insight keuangan.

## Technologies

* YOLOv8 (Receipt Detection)
* EasyOCR (Text Extraction)
* Gemini LLM (Financial Insight Generation)

## Dataset

* Training: 375 images
* Validation: 20 images
* Testing: 14 images
* Total: 409 images

## Workflow

Receipt Image → YOLOv8 Detection → EasyOCR → Gemini LLM → Financial Insight

## Repository Contents

* Training Notebook
* YOLO Model
* Sample Results

## Model Information

- YOLOv8 digunakan untuk mendeteksi area struk pada gambar.
- EasyOCR digunakan untuk mengekstraksi teks dari struk yang telah terdeteksi.
- Gemini LLM digunakan untuk menghasilkan insight pengeluaran dan rekomendasi keuangan berdasarkan hasil ekstraksi teks.
