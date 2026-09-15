---
title: Home
type: landing

sections:

  # ============================================================
  # HERO
  # ============================================================

  - block: hero
    content:
      title: "Koshy Mammoottill Mathew"
      text: "Data Science & Artificial Intelligence"
      primary_action:
        text: "Download CV"
        url: "/uploads/resume.pdf"
        icon: document-arrow-down
      secondary_action:
        text: "Explore My Work"
        url: "#projects"
        icon: arrow-down
      media:
        src: "avatar.jpg"
        alt: "Koshy Mammoottill Mathew"
    design:
      columns: "2"
      background:
        gradient:
          start: primary-100
          end: secondary-100
          direction: "135"
      spacing:
        padding: ["6rem", "0", "6rem", "0"]

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
        ### Big Mart Sales Prediction

        A machine learning project focused on predicting retail sales using data preprocessing, feature engineering, regression, and model evaluation.

        ---

        ### Student Grade Prediction using ANN

        An Artificial Neural Network project exploring student performance prediction using supervised learning techniques.

        ---

        ### MRI Scan Prediction

        A deep learning and computer vision project exploring image-based prediction using Convolutional Neural Networks.

        ---

        ### CNN Image Classification

        Computer vision projects involving image classification, including Cats vs Dogs and Face Mask Detection.

        ---

        ### NLP & Chatbot Projects

        Machine learning and NLP projects involving text classification, TF-IDF, semantic similarity, customer-support datasets, and conversational AI.

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
