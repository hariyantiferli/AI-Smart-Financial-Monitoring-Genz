# AI-Smart-Financial-Monitoring-Genz
## Overview

AI pipeline untuk menganalisis struk belanja dan menghasilkan insight keuangan.

## Technologies

* YOLOv8 (Receipt Detection)
* EasyOCR (Text Extraction)
* Gemini API (Financial Insight Generation)

## Dataset

* Training: 375 images
* Validation: 20 images
* Testing: 14 images
* Total: 409 images

## Workflow

Receipt Image → YOLOv8 Detection → EasyOCR → Gemini API → Spending Insight

## Repository Contents

* Training Notebook
* YOLO Model
* Sample Results
  
## Model Information

- YOLOv8 digunakan untuk mendeteksi area struk.
- EasyOCR digunakan untuk mengekstraksi teks dari struk.
- Gemini API digunakan untuk menghasilkan insight pengeluaran dan rekomendasi keuangan.
