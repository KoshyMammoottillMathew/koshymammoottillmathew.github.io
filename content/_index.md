---
title: Home
type: landing

sections:

  # ============================================================
  # HERO
  # ============================================================

  - block: resume-biography-3
    content:
      username: admin
      button:
        text: "Download CV"
        url: "/uploads/resume.pdf"
    design:
      background:
        gradient:
          start: primary-100
          end: secondary-100
          direction: "135"

  # ============================================================
  # INTRODUCTION
  # ============================================================

  - block: markdown
    id: introduction
    content:
      title: "Data. Intelligence. Impact."
      text: |
        I am an aspiring **Data Science and AI professional** focused on building practical solutions using **machine learning, artificial intelligence, data analytics, and predictive modeling**.

        My multidisciplinary background combines **Data Science & Artificial Intelligence, Human Resource Management, Clinical Psychology, and English Literature**.

        I am particularly interested in applying technology to real-world problems while bringing a human-centered perspective to data and AI.

    design:
      columns: "1"


  # ============================================================
  # AREAS OF FOCUS
  # ============================================================

  - block: features
    id: expertise
    content:
      title: "Areas of Focus"
      text: "Technologies and domains I am developing through continuous learning and hands-on projects."

      items:

        - name: "Machine Learning"
          description: "Predictive modeling, classification, regression, feature engineering, and model evaluation."
          icon: chart-bar

        - name: "Artificial Intelligence"
          description: "Neural networks, deep learning, computer vision, and practical AI applications."
          icon: cpu-chip

        - name: "Natural Language Processing"
          description: "Text classification, TF-IDF, semantic similarity, chatbots, and conversational AI."
          icon: chat-bubble-left-right

        - name: "Data Analytics"
          description: "Data preprocessing, exploratory analysis, visualization, and data-driven decision making."
          icon: presentation-chart-line


  # ============================================================
  # PROJECTS
  # ============================================================

  - block: markdown
    id: projects
    content:
      title: "Featured Projects"
      text: |
        ### SignBridge AI — ASL Fingerspelling-to-Text Recognition

        An end-to-end deep learning accessibility project that recognizes continuous **American Sign Language (ASL) fingerspelling** from video and converts it into text.

        The system uses **MediaPipe Hand Landmarker** to extract 21 three-dimensional hand landmarks (63 features per frame), followed by a **Temporal Conv1D + Bidirectional GRU + CTC** architecture for sequence recognition without frame-level character alignment.

        **Key results:** 16.32% best validation CER · 15.96% later cached FSBoard test-split CER · 2.34M-parameter TensorFlow/Keras model.

        The project also includes **SignBridge Live**, an interactive Gradio webcam prototype for near-real-time fingerspelling recognition.

        **Technologies:** Python · TensorFlow/Keras · MediaPipe · OpenCV · NumPy · Pandas · Gradio

        **[View SignBridge AI on GitHub](https://github.com/KoshyMammoottillMathew/SignBridgeAI)**

    design:
      columns: "1"


  # ============================================================
  # RESEARCH & PROJECT REPORT
  # ============================================================

  - block: markdown
    id: research
    content:
      title: "Research & Project Report"
      text: |
        ### SignBridge AI: Real-Time ASL Fingerspelling-to-Text Recognition Using Deep Learning

        **Academic Project Report · 2026**

        Comprehensive project documentation covering **FSBoard video preprocessing, MediaPipe hand-landmark extraction, Temporal Conv1D + Bidirectional GRU + CTC sequence modelling, model training, Character Error Rate (CER) evaluation, diagnostic testing, and the SignBridge Live interactive prototype**.

        The documented system achieved a **best validation CER of 16.32%** and a **later cached FSBoard test-split CER of 15.96%**.

        **[View Project Report](https://github.com/KoshyMammoottillMathew/SignBridgeAI/blob/main/docs/SignBridge_AI_Project_Report.pdf)** · **[View GitHub Repository](https://github.com/KoshyMammoottillMathew/SignBridgeAI)**

    design:
      columns: "1"


  # ============================================================
  # EXPERIENCE
  # ============================================================

  - block: markdown
    id: career
    content:
      title: "Professional Experience"
      text: |
        ### Trust Operations Content Reviewer — Amazon

        **July 2022 – March 2025**

        Worked in Amazon Ads Trust Operations, reviewing and moderating content while maintaining quality, accuracy, and process compliance.

        Contributed to process improvement initiatives involving workflow optimization, batch assignment, time tracking, mentoring, and cross-training.

        Received multiple recognition awards for contributions and performance.

    design:
      columns: "1"


  # ============================================================
  # EDUCATION
  # ============================================================

  - block: markdown
    id: education
    content:
      title: "Education"
      text: |
        **Certificate in Data Science & Artificial Intelligence**  
        KELTRON

        **Master of Business Administration — Human Resource Management**  
        Indira Gandhi National Open University (IGNOU)

        **Master of Arts — Clinical Psychology**  
        Indira Gandhi National Open University (IGNOU)

        **Bachelor of Arts — English Literature**  
        Indira Gandhi National Open University (IGNOU)

    design:
      columns: "1"


  # ============================================================
  # CONTACT
  # ============================================================

  - block: cta-card
    id: contact
    content:
      title: "Let's Connect"
      text: "Interested in Data Science, Artificial Intelligence, Machine Learning, analytics, or potential opportunities?"
      button:
        text: "Get In Touch"
        url: "mailto:koshymammoottillmathew@gmail.com"

    design:
      background:
        gradient:
          start: primary-500
          end: secondary-600
          direction: "135"
        text_color_light: true
---
