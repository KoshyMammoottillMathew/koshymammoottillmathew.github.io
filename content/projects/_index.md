---
title: 'Research & Project Report'
date: 2026-09-21
type: landing

design:
  spacing: '5rem'

sections:
  - block: markdown
    content:
      title: "Research & Project Report"
      text: |
        ## SignBridge AI — ASL Fingerspelling-to-Text Recognition Using Deep Learning

        **Academic Deep Learning & Accessibility Project · 2026**

        SignBridge AI is an end-to-end deep learning system for recognizing continuous **American Sign Language (ASL) fingerspelling** from video and converting it into text.

        The system uses **MediaPipe Hand Landmarker** to extract 21 three-dimensional hand landmarks, producing **63 features per frame**. These temporal landmark sequences are processed using a **Temporal Conv1D CNN** for local motion patterns and **Bidirectional GRU** layers for longer sequence context. **Connectionist Temporal Classification (CTC)** enables sequence recognition without requiring frame-level character alignment.

        ### Key Results

        - **Best validation CER:** 16.32%
        - **Later cached FSBoard test-split CER:** 15.96%
        - **Model parameters:** 2,340,410
        - **Input representation:** 21 hand landmarks × (x, y, z) = 63 features per frame
        - **Architecture:** Temporal Conv1D + Bidirectional GRU + CTC

        ### SignBridge Live

        The project includes **SignBridge Live**, an interactive Gradio webcam prototype demonstrating near-real-time ASL fingerspelling recognition.

        ### Technologies

        **Python · TensorFlow/Keras · MediaPipe · OpenCV · NumPy · Pandas · Gradio · Google Colab**

        ### Project Resources

        **[View SignBridge AI on GitHub](https://github.com/KoshyMammoottillMathew/SignBridgeAI)**

        **[View Complete Project Report](https://github.com/KoshyMammoottillMathew/SignBridgeAI/blob/main/docs/SignBridge_AI_Project_Report.pdf)**

        > **Scope:** SignBridge AI recognizes ASL fingerspelling. It is not a complete ASL language-translation system.

    design:
      columns: "1"
---
