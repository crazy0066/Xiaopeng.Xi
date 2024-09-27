---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Main Projects
======
* Indirect monitoring data-driven remaining useful life prediction for blast furnace cooling systems (Principal Investigator, Funded by National Natural Science Foundation of China)
* Multi-modal data-driven remaining useful life prediction for blast furnace hearths (Principal Investigator, Funded by Shandong Provincial Natural Science Foundation)
* Non-stationary degradation modeling based remaining useful life prediction and maintenance for blast furnace walls (Principal Investigator, Funded by Qingdao Post-doctoral Applied Research Project)
* Running status monitoring and test verification for traction drive systems of high-speed train (Participant, Funded by National Natural Science Foundation of China)
* Sensor fault diagnosis and application verification for a class of nonlinear systems under strong disturbance (Participant, Funded by National Natural Science Foundation of China)
* Big data-driven fault detection: improved PCA and PLS methods (Participant, Funded by National Natural Science Foundation of China)
* Intelligent prediction and self-healing control for abnormal working conditions of large generator sets (Participant, Funded by National Natural Science Foundation of China)

Research Areas
======
* <strong>Deep learning based remaining useful life prediction:</strong> A novel two-stage LSTM-TDNN-based RUL predictor is proposed for complicated industrial equipment. A set of nonlinear HI functions are constructed to guide LSTM model building. Compared with the traditional feature fusion-based HI construction methods, the proposed approach considers various degradation rates and can be applied to a variety of working conditions. A series of LSTMs are used to build the mapping relations from individual time-series feature sets to the HIs, aligning time scales of data and solving the problem of unequal length sequences to some extent. By introducing the TDNN stage, the historical information of HI in a finite time window is fused to achieve further refinement of prediction.

<p align="center">
<img src="https://raw.githubusercontent.com/crazy0066/Xiaopeng.Xi/refs/heads/master/images/fig1.png" alt="Architecture of the proposed LSTM-TDNN-based RUL predictor" width="400" style="height:auto;">
<img src="https://raw.githubusercontent.com/crazy0066/Xiaopeng.Xi/refs/heads/master/images/fig2.png" alt="Comparison of RUL prediction results between one-stage and two-stage approaches" width="500" style="height:auto;">
</p>
<p align="center">Architecture of the RUL predictor (left). Comparison of RUL prediction results (right).</p>

* <strong>Non-Markovian stochastic degradation process modeling and prognostics:</strong> 

<p align="center">
<img src="https://raw.githubusercontent.com/crazy0066/Xiaopeng.Xi/refs/heads/master/images/fig5.png" alt="fig5" width="400" style="height:auto;">
<img src="https://raw.githubusercontent.com/crazy0066/Xiaopeng.Xi/refs/heads/master/images/fig6.png" alt="fig6" width="500" style="height:auto;">
</p>
<p align="center">Temperature degradation path of a blast furnace (left). RUL prediction results with C-MAPSS data (right).</p>

* <strong>Model and data dual-driven fault diagnosis:</strong> A novel model and data dual-driven fault diagnosis approach is proposed for satellite ACSs. Firstly, an Hi/H∞ optimization-based fault detection filter is considered as a residual generator, which is designed to be robust against disturbance and sensitive to a fault. Then, the occurrence of a fault can be detected based on the residual evaluation. Eventually, a random forest (RF) algorithm is developed to
achieve fault isolation with system input–output and residual signals.

<p align="center">
<img src="https://raw.githubusercontent.com/crazy0066/Xiaopeng.Xi/refs/heads/master/images/fig3.png" alt="fig3" width="520" style="height:auto;">
<img src="https://raw.githubusercontent.com/crazy0066/Xiaopeng.Xi/refs/heads/master/images/fig4.png" alt="fig4" width="390" style="height:auto;">
</p>
<p align="center">Flowchart of model and data dual-driven method (left). Fault detection results of triple faults (right).</p>

