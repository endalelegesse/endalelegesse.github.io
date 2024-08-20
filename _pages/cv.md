---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Information and Communication Engineering, South China University of Technology, 2028 (expected)
* M.Eng. in Information and Communication Engineering, Beijing Jiaotong University, 2024
* B.Eng. in Communication Engineering, GitHub Beijing Jiaotong University, 2021

Academic Project experience
======
* 2023-2024: Deep Learning based Prediction Model Design for Predicting Rain Fade Signal Attenuation for Microwave and mmWave Bands Master Thesis Disertation 
  * Beijing Jiaotong University
  * Duties includes: 
     - Study existing rain attenuation prediction models(including ITU-R models, Global Crane Model and other research works)
     - Data Collection from the target geographical location(Addis Ababa, Ethiopia), Data includes Rain Rate and Microwave/mmWave link profile data 
     - Design deep learning prediction model(LSTM) which uses rain rate and microwave/mmWave link profile data as input and predict the attenuation that will be caused on the target communication link. 
     - Preprocess and analyse the collected data based on the design requirments 
     - Train and simulate the design using the preprocessed data 
     - Summarize the Conclusion and write dissertation
    * Participated in the 4th International Conference on Machine Learning and Intelligent Systems Engineering (MLISE), Zhuhai, China and my work has been accepted for publication in this confference. 
        - 4th International Conference on Machine Learning and Intelligent Systems Engineering (MLISE), Zhuhai, China
        - Article Title: Rain Attenuation Prediction Modeling for Microwave and Millimeter Wave Band Using LSTM
  * Supervisor:  <a href="https://faculty.bjtu.edu.cn/eie/8077.html">Prof. Xiong Lei</a>

* 2022-2023: Study of Characteristics Analysis and Modeling of Train-to-Train Wireless Channel in Station Scenario, group work under  <a href="https://faculty.bjtu.edu.cn/eie/8077.html">Prof. Xiong Lei</a> at The State Key Laboratory of Advanced Rail Autonomous Operation, Beijing Jiaotong University, Beijing 100044, China
  * Beijing Jiaotong University
  * Duties included:
      1. **Literature Review:**
       - Review existing research on Train-to-Train (T2T) wireless communication channels.
       - Investigate previous studies on ray tracing (RT) techniques in wireless communications, particularly for high-speed rail scenarios.
      2. **Selection of Frequency Band:**
       - Choose the 2.1 GHz frequency band for analysis, considering its relevance for T2T communication.
      3. **Ray Tracing (RT) Simulation Setup:**
       - Develop or use existing RT tools to simulate the wireless channel characteristics.
       - Set up the simulation environment, including models of high-speed trains and surrounding environments.
      4. **Parameter Identification:**
       - Identify key channel characteristics to analyze: path loss, multipath clustering, delay spread, Rice factor, angular spread, and channel non-stationarity.
      5. **Simulation Execution:**
       - Run simulations to model the T2T wireless channel under different environmental conditions.
       - Analyze how changes in the environment impact channel characteristics.
      6. **Data Collection and Analysis:**
       - Collect data from the simulations, focusing on path loss, multipath clustering, and other identified parameters.
       - Use statistical methods to analyze the distribution of path loss, delay spread, Rice factor, and angular spread.
      7. **Non-Stationarity Analysis:**
       - Introduce and calculate the time correlation coefficient (TPCC) of the power delay profile (PDP) to assess channel non-stationarity.
       - Determine the quasi-stationarity distance based on TPCC analysis.
      8. **Model Validation:**
       - Compare the simulation results with existing measured data to validate the accuracy of the RT model.
       - Quantify the consistency between the simulation results and real-world measurements.
      9. **Channel Model Development:**
       - Develop a channel model for the station scenario based on the simulation results.
       - Summarize the channel model parameters, such as path loss factors, shadow fading distribution, and multipath clustering characteristics.
      10. **Scenario-Specific Analysis:**
       - Study the impact of different distances between trains on channel characteristics.
       - Analyze how the proximity of trains affects channel correlation, multipath components (MPCs), and overall channel behavior.
      11. **Performance Evaluation:**
       - Evaluate the communication system performance in high-speed rail scenarios.
       - Determine the required frequency of channel estimation to maintain reliable communication.
      12. **Discussion of Results:**
       - Discuss the implications of the findings on T2T communication system design.
       - Highlight the need to consider rapid channel changes and estimation frequency in system design.

  * Supervisor:  <a href="https://faculty.bjtu.edu.cn/eie/8077.html">Prof. Xiong Lei</a>

Skills
======
<ul>{% for post in site.softwareskills reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  
Service and leadership
======

