# Deepfake Detection — CYB-486/586
University of Michigan | Dr. Kutub | Spring 2026*

Group Members
- Taha Sohail (Group Leader) — tahasoha@umich.edu
- Dak Bredernitz — dakbred@umich.edu
- Crystal Robinson — rrcrbnsn@umich.edu

Project Overview
Deep learning-based visual deepfake detection using EfficientNet-B4 
trained on the FaceForensics++ dataset. We train three separate models 
on different face crop regions (full face, eye, mouth) to identify which 
region contains the strongest manipulation artifacts.

Task Breakdown
- **Taha** — Full face model, dataset setup, final report
- **Dak** — Eye region model, DCT spectral analysis
- **Crystal** — Mouth region model, metadata analysis, evaluation metrics

Tools
- Python / PyTorch
- EfficientNet-B4
- Grad-CAM
- MTCNN (face detection)
- FFmpeg (frame extraction)
- ExifTool (metadata analysis)
- FaceForensics++ dataset

Folder Structure
- /notebooks — Colab notebooks for each model
- /results — Grad-CAM heatmaps and accuracy tables
- /metadata — ExifTool output
