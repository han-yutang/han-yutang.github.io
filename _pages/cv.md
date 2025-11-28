---
layout: archive
permalink: /
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

🎓 Education
=====
- **M.Sc(Eng) in Electrical and Electronic Engineering**, <a href="https://www.hku.hk/" target="_blank" style="color: inherit; text-decoration: underline;">The University of Hong Kong</a> <span style="float: right;">2024.09 – 2026.06</span>  
  - GPA: 3.58  
  - Main Courses: IP Networks, Computer Vision, Biomedical Signals & Systems, High-Performance Computer Architecture, Pattern Recognition, Advanced DSP, Human-Computer Interaction, etc.  

- **B.Eng in Electronic Information Engineering**, <a href="https://www.shu.edu.cn/" target="_blank" style="color: inherit; text-decoration: underline;">Shanghai University</a> <span style="float: right;">2020.09 – 2024.06</span>  
  - GPA: 3.55 / 4.0, Average: 88.03 / 100, Rank: top 20%  
  - Main Courses: Digital Signal Processing, Digital Image Processing, Computer Networks, RF Circuit Design, Information Theory & Coding, Data Structure, etc.  

---

🏆 Academic Achievements                                                
=====                             
* 1st Class Scholarship, Shanghai University (2023)
* "Self-Strengthening" Scholarship, Shanghai University (2023)
* 2nd Class Scholarship, Shanghai University (2022)
* "ChatBot Intelligent Chat Application V1.0", Software Copyright Registration No.: 2023SR1295184
* "Deep-MGIAS: Deep Learning-Based Meibomian Gland Image Analysis System V1.0", Software Copyright Registration: Pending

---

💡 Skills
=====
* **Language**:
  * Chinese proficiency: Mandarin & Shanghainese (Native), Cantonese (Beginner🙂)
  * English proficiency: **IELTS 7.0 with 7.5 in writing**, CET-6, CET-4
* **Programming Language**: Python, C/C++, MATLAB/Simulink, Java & SQL, HTML/CSS/JavaScript
* **Software Tools**: TensorFlow, PyTorch, Embedded Systems Development, Android Development, Multisim Circuit Simulation
* **Certifications**: National Computer Rank Examination Level 4 (Network Engineer); Information Security Professional Certificate Level 1 (NISP-1); Shanghai Higher Education IT Proficiency Exam Level 2 (C Programming); Alipay Junior Web Front-End Developer Certification

---

💼 Internship
=====
- **Algorithm Strategic intern @ Bosch (China) Investment Ltd.** <span style="float: right;">2025.09 – Now</span> 
  - Participated in the algorithm development of an embedded AI-based indirect tire pressure monitoring system for commercial vehicles, leveraging existing vehicle sensors to implement a hybrid mathematical-AI algorithm on low-cost embedded ECUs for real-time and accurate tire pressure monitoring.
  - Addressed harsh commercial vehicle operating conditions and sensor limitations by applying multiple advanced denoising techniques, removing over 90% of environmental noise and abnormal signals, and extracting more than 10 relevant features.
  - Built and trained deep neural network models in TensorFlow to deeply fuse multi-scale features from various sensors, significantly improving tire pressure estimation stability and robustness.
  - Reconstructed and generated embedded code using MATLAB/Simulink based on validated models, providing technical support for subsequent vehicle-level deployment and real-time operation.
  - Utilized Git for version control and team collaboration, establishing a complete algorithm development–deployment–testing workflow, ensuring traceability and iterative improvement of model versions.

- **AI Engineer intern @ Tab Next Limited, Hong Kong** <span style="float: right;">2025.06 – 2025.08</span>
  - Assisted in developing an an intelligent customer service system based on the WhatsApp Business API, leveraging the Qwen 3.0 large language model to create an end-to-end automated workflow for medical imaging appointment booking, enabling real-time request processing and automated scheduling.
  - Designed prompt engineering and context management mechanisms for Cantonese and Traditional Chinese scenarios, ensuring user requests were accurately routed to the corresponding processing modules, achieving ~95% intent recognition accuracy and ~90% task completion rate in multi-turn conversations.
  - Conducted black-box testing and defect tracking for dialogue flow and intent recognition modules, simulating end-user appointment interactions, validating system responses, and using SQL commands in MySQL to clean specific test session records, ensuring data isolation and reproducibility in the test environment.
  - Used Docker to containerize the development environment, enabling rapid independent deployment and debugging of system components, improving team development efficiency.

- **Electrical intern @ Shanghai Telecommunication Engineering Co., Ltd.** <span style="float: right;">2023.06 – 2023.07</span>
  - Participated in the precise mapping of the weak power facilities of Yangpu District Urban Operation and Management Center. Handled and verified complex low-voltage construction drawings using AutoCAD, ensuring accuracy of the diagrams.
  - Participated in an intelligent security monitoring project, applying YOLOv5 + DeepSORT to perform crowd density analysis in key areas and generate real-time alerts for abnormal behavior.
 
- **Part-time TA @ Shanghai Hou Zai Education Consulting Co., Ltd.** <span style="float: right;">2022.01 – 2023.12</span>
  - Provided weekend tutoring for high school mathematics, helping students understand and master key concepts to improve academic performance.

---

🔬 Research Experience
=====
* **Microwave Non-Invasive Blood Glucose Monitoring System Based on Fano Resonance and BLE** <span style="float: right;">2023.12 – 2024.06</span>  
  - **Hardware**: Designed a microwave detection circuit based on ESP32 MCU, integrating a voltage-controlled oscillator and detector to generate/receive microwave signals, combined with an active Fano-resonance microwave sensor for highly sensitive glucose measurements.
  - **Software**: Developed a mobile Android app in Android Studio for UI, parameter configuration, and data visualization; implemented a local SQLite database and used Bluetooth Low Energy (BLE) for device connection and real-time data transmission. 
  - **Algorithm**: Quantified the relationship between S-parameters and glucose concentration, using cubic polynomial fitting for glucose prediction (RMSE ~1.0 mmol/L). Applied adaptive DBSCAN clustering to identify and remove outliers, effectively handling device drift, user errors, and environmental noise; achieved anomaly detection F1 score >95%.

* **Deep-MGIAS: Deep Learning-Based Meibomian Gland Image Analysis System** <span style="float: right;">2025.03 – 2025.08</span>  
  - **Preprocessing**: Combined Gaussian denoising and Laplacian sharpening with adaptive alpha blending to enhance gland contrast and boundary clarity
  - **Multi-Stage Segmentation**: Developed a two-stage segmentation pipeline for eyelids and glands, leveraging a suite of U-Net variants (nnU-Net, U-Net++, Attention U-Net, ResUNet), achieving a peak IoU of 0.9022 on the test dataset.
  - **Feature Engineering & Classification**: Extracted comprehensive morphological and texture features from segmented glands and employed a Random Forest classifier to accurately predict gland atrophy levels with strong interpretability.
  - **GUI**: Built a PyQt-based user interface enabling seamless image import/export, real-time segmentation visualization, and automated Meiboscore assessment, streamlining clinical workflow and usability. 

* **IoT-Based Thermostatic Biological Incubator** <span style="float: right;">2023.03 – 2023.06</span>  
  - **Hardware**: Developed an IoT-based thermostatic biological incubator using STM32 as the core controller, designed schematics and PCB layout using Altium Designer, and performed chip soldering.  
  - **Firmware**: Implemented temperature acquisition, setting, display, and PID control algorithms in C using Keil, achieving ±0.5°C precision; established data communication with the server via NBIoT using TCP.  
  - **Software**: Developed an Android app using MQTT for sub-second, low-latency remote data transfer; visualized real-time temperature and supported remote configuration of target temperatures, enabling unattended incubator operation. 

---

🌍 Extra-Curricular Activities
=====
* <a href="https://skliotsc.um.edu.mo/um-organises-3rd-skl-iotsc-summer-camp-for-outstanding-university-students/" target="_blank" style="color: inherit; text-decoration: underline;">**Summer Camp @ SKL-IOTSC, University of Macau**</a> <span style="float: right;">2025.07</span>  
  - Selected to participate in the 3rd SKL-IOTSC Summer Camp hosted by the State Key Laboratory of Internet of Things for Smart City.
  - Participated in academic lectures across five major IoT research domains—Intelligent Sensing & Network Communication, Urban Big Data, Smart Energy, Intelligent Transportation, and Urban Safety . 

* <a href="https://mp.weixin.qq.com/s/U0oRLA9g9eZ7A9FKwxSL6g" target="_blank" style="color: inherit; text-decoration: underline;">**Summer Camp @ Function Hub, HKUST (Guangzhou)**</a> <span style="float: right;">2025.06</span>  
  - Selected to participate in the Summer Camp organized by the Function Hub at the Hong Kong University of Science and Technology (Guangzhou).
  - Engaged with research thrusts in advanced materials, microelectronics, sustainable energy and environment, and explored cross-disciplinary innovation in smart city technologies.  

* **Summer Program @ Institute of Electronic Design Automation, Peking University** <span style="float: right;">2024.07</span>  
  - Attended 2024 IC Summer School on Advanced Technology.  
  - Gained hands-on training in sparse computing, hardware-software co-design, and timing optimization.  

