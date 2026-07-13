---
layout: archive
permalink: /projects/
title: "Projects"
author_profile: true
---

{% include base_path %}

<link rel="stylesheet" href="{{ base_path }}/assets/css/modern-style.css">

<div class="modern-page" markdown="0">

<section>
<h2><span class="section-icon">🚀</span> Featured Projects</h2>

<div class="projects-grid">

  <!-- Blood Glucose -->
  <div class="project-card">
    <div class="project-img" style="background: linear-gradient(135deg, #e74c3c, #c0392b);">
      <i class="fas fa-heartbeat"></i>
    </div>
    <div class="project-body">
      <div class="project-name">Microwave Non-Invasive Blood Glucose Monitoring System</div>
      <div class="project-desc">
        Designed a microwave detection circuit based on ESP32 MCU with an active Fano-resonance microwave sensor. Developed an Android app with BLE connectivity and SQLite storage. Applied cubic polynomial fitting and adaptive DBSCAN clustering for glucose prediction (RMSE ~1.0 mmol/L) with anomaly detection F1 >95%.
      </div>
      <div class="project-tech-stack">
        <span class="project-tech-tag">ESP32</span>
        <span class="project-tech-tag">Android (Java)</span>
        <span class="project-tech-tag">BLE</span>
        <span class="project-tech-tag">DBSCAN</span>
        <span class="project-tech-tag">Microwave Sensing</span>
        <span class="project-tech-tag">SQLite</span>
        <span class="project-tech-tag">Android Studio</span>
      </div>
      <div class="project-links">
        <a href="https://github.com/ChirsDickman" target="_blank" class="project-link github"><i class="fab fa-github"></i> GitHub</a>
      </div>
    </div>
  </div>

  <!-- Deep-MGIAS -->
  <div class="project-card">
    <div class="project-img" style="background: linear-gradient(135deg, #2980b9, #6dd5fa);">
      <i class="fas fa-eye"></i>
    </div>
    <div class="project-body">
      <div class="project-name">Deep-MGIAS: Meibomian Gland Image Analysis System</div>
      <div class="project-desc">
        Multi-stage deep learning pipeline for eyelid and meibomian gland segmentation using U-Net variants (nnU-Net, U-Net++, Attention U-Net, ResUNet), achieving peak IoU of 0.9022. Random Forest classifier for gland atrophy prediction. PyQt-based clinical GUI with real-time visualization.
      </div>
      <div class="project-tech-stack">
        <span class="project-tech-tag">PyTorch</span>
        <span class="project-tech-tag">U-Net</span>
        <span class="project-tech-tag">nnU-Net</span>
        <span class="project-tech-tag">Attention U-Net</span>
        <span class="project-tech-tag">ResUNet</span>
        <span class="project-tech-tag">Random Forest</span>
        <span class="project-tech-tag">PyQt</span>
        <span class="project-tech-tag">Medical Imaging</span>
      </div>
      <div class="project-links">
        <a href="https://github.com/ChirsDickman" target="_blank" class="project-link github"><i class="fab fa-github"></i> GitHub</a>
        <span class="project-link demo" style="cursor:default;opacity:0.7;"><i class="fas fa-file-alt"></i> 2026SR0233395</span>
      </div>
    </div>
  </div>

  <!-- IoT Incubator -->
  <div class="project-card">
    <div class="project-img" style="background: linear-gradient(135deg, #27ae60, #2ecc71);">
      <i class="fas fa-thermometer-half"></i>
    </div>
    <div class="project-body">
      <div class="project-name">IoT-Based Thermostatic Biological Incubator</div>
      <div class="project-desc">
        STM32-based thermostatic incubator with PID temperature control (±0.5°C). Designed schematics and PCB in Altium Designer. NBIoT connectivity via TCP. Android app with MQTT for real-time remote monitoring and configuration.
      </div>
      <div class="project-tech-stack">
        <span class="project-tech-tag">STM32</span>
        <span class="project-tech-tag">C (Keil)</span>
        <span class="project-tech-tag">PID Control</span>
        <span class="project-tech-tag">Altium Designer</span>
        <span class="project-tech-tag">MQTT</span>
        <span class="project-tech-tag">NBIoT</span>
        <span class="project-tech-tag">Android</span>
        <span class="project-tech-tag">PCB Design</span>
      </div>
      <div class="project-links">
        <a href="https://github.com/ChirsDickman" target="_blank" class="project-link github"><i class="fab fa-github"></i> GitHub</a>
      </div>
    </div>
  </div>

  <!-- ChatBot -->
  <div class="project-card">
    <div class="project-img" style="background: linear-gradient(135deg, #8e44ad, #c39bd3);">
      <i class="fas fa-comments"></i>
    </div>
    <div class="project-body">
      <div class="project-name">ChatBot Intelligent Conversational Mini-Program</div>
      <div class="project-desc">
        Intelligent conversational mini-program with natural language understanding capabilities. Registered software copyright with the National Copyright Administration of China.
      </div>
      <div class="project-tech-stack">
        <span class="project-tech-tag">NLP</span>
        <span class="project-tech-tag">Mini-Program</span>
        <span class="project-tech-tag">ChatBot</span>
        <span class="project-tech-tag">WeChat</span>
      </div>
      <div class="project-links">
        <span class="project-link demo" style="cursor:default;opacity:0.7;"><i class="fas fa-file-alt"></i> 2023SR1295184</span>
      </div>
    </div>
  </div>

</div>
</section>

</div>
