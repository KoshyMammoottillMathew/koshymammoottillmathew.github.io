---
title: "SignBridge AI"
date: 2026-09-19
summary: "ASL fingerspelling-to-text recognition using MediaPipe, Temporal Conv1D, BiGRU, and CTC."
authors:
  - admin
image:
  filename: featured.png
  focal_point: Center
  preview_only: true
  alt_text: "SignBridge AI hand landmark recognition interface"

tags:
  - SignBridgeAI
  - Artificial Intelligence
  - Deep Learning
  - Computer Vision
  - Accessibility
links:
  - type: code
    url: https://github.com/KoshyMammoottillMathew/SignBridgeAI
  - type: document
    url: https://github.com/KoshyMammoottillMathew/SignBridgeAI/blob/main/docs/SignBridge_AI_Project_Report.pdf
---

## SignBridge AI

**SignBridge AI** is an end-to-end deep learning accessibility project for recognizing continuous **American Sign Language (ASL) fingerspelling** from video and converting it into text.

### How it works

Video is processed with **MediaPipe Hand Landmarker** to extract 21 three-dimensional hand landmarks, producing **63 features per frame**. The temporal sequence is then modeled using **Temporal Conv1D** layers for local motion patterns and **Bidirectional GRU** layers for longer-range context. **Connectionist Temporal Classification (CTC)** enables sequence recognition without frame-level character alignment.

### Key Results

- **Best validation CER:** 16.32%
- **Later cached FSBoard test-split CER:** 15.96%
- **Model parameters:** 2,340,410
- **Input:** 21 hand landmarks × (x, y, z) = 63 features per frame
- **Architecture:** Temporal Conv1D + Bidirectional GRU + CTC

### SignBridge Live

The project includes **SignBridge Live**, an interactive Gradio webcam prototype for near-real-time fingerspelling recognition.

### Technology Stack

**Python · TensorFlow/Keras · MediaPipe · OpenCV · NumPy · Pandas · Gradio · Google Colab**

### Project Resources

[View the SignBridge AI GitHub Repository](https://github.com/KoshyMammoottillMathew/SignBridgeAI)

[Read the Complete Project Report](https://github.com/KoshyMammoottillMathew/SignBridgeAI/blob/main/docs/SignBridge_AI_Project_Report.pdf)

> **Scope:** SignBridge AI recognizes ASL fingerspelling. It is not a complete ASL language-translation system.
