layout: archive
title: ""
permalink: /researches/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Main Projects
======
* <p style="text-align: justify;">
  Indirect monitoring data-driven remaining useful life prediction for blast furnace cooling systems (Principal Investigator, Funded by National Natural Science Foundation of China)
  </p>
* <p style="text-align: justify;">
  Multi-modal data-driven remaining useful life prediction for blast furnace hearths (Principal Investigator, Funded by Shandong Provincial Natural Science Foundation)
  </p>
* <p style="text-align: justify;">
  Non-stationary degradation modeling based remaining useful life prediction and maintenance for blast furnace walls (Principal Investigator, Funded by Qingdao Post-doctoral Applied Research Project)
  </p>
* <p style="text-align: justify;">
  Running status monitoring and test verification for traction drive systems of high-speed train (Participant, Funded by National Natural Science Foundation of China)
  </p>
* <p style="text-align: justify;">
  Sensor fault diagnosis and application verification for a class of nonlinear systems under strong disturbance (Participant, Funded by National Natural Science Foundation of China)
  </p>
* <p style="text-align: justify;">
  Big data-driven fault detection: improved PCA and PLS methods (Participant, Funded by National Natural Science Foundation of China)
  </p>
* <p style="text-align: justify;">
  Intelligent prediction and self-healing control for abnormal working conditions of large generator sets (Participant, Funded by National Natural Science Foundation of China)
  </p>

Research Areas
======
* <p style="text-align: justify;">
  <strong>Deep learning based remaining useful life prediction:</strong> A novel two-stage LSTM-TDNN-based RUL predictor is proposed for complicated industrial equipment. A set of nonlinear HI functions are constructed to guide LSTM model building. Compared with the traditional feature fusion-based HI construction methods, the proposed approach considers various degradation rates and can be applied to a variety of working conditions. A series of LSTMs are used to build the mapping relations from individual time-series feature sets to the HIs, aligning time scales of data and solving the problem of unequal length sequences to some extent. By introducing the TDNN stage, the historical information of HI in a finite time window is fused to achieve further refinement of prediction.
  </p>

<p align="center">
<img src="https://raw.githubusercontent.com/crazy0066/Xiaopeng.Xi/refs/heads/master/images/fig1.png" alt="fig1" width="400" style="height:auto;">
<img src="https://raw.githubusercontent.com/crazy0066/Xiaopeng.Xi/refs/heads/master/images/fig2.png" alt="fig2" width="500" style="height:auto;">
</p>
<p align="center">Architecture of the RUL predictor (left). Comparison of RUL prediction results (right).</p>

* <p style="text-align: justify;">
  <strong>Non-Markovian stochastic degradation process modeling and prognostics:</strong> Some practical systems such as blast furnaces and turbofan engines have degradation processes with memory effects. The term of memory effects implies that the future states of the
degradation processes depend on both the current state and the past states because of the interaction with environments. However, most works generally used a memoryless Markovian process to model the degradation processes. To characterize the memory effects in practical systems, we develop a new type of degradation model, in which the diffusion is represented as a fractional Brownian motion (FBM). FBM is actually a special non-Markovian process with long-term dependencies. Based on the monitored data, a Monte Carlo method is used to predict the RUL.
  </p>

<p align="center">
<img src="https://raw.githubusercontent.com/crazy0066/Xiaopeng.Xi/refs/heads/master/images/fig5.png" alt="fig5" width="440" style="height:auto;">
<img src="https://raw.githubusercontent.com/crazy0066/Xiaopeng.Xi/refs/heads/master/images/fig6.png" alt="fig6" width="440" style="height:auto;">
</p>
<p align="center">Temperature degradation path of a blast furnace (left). RUL prediction results with C-MAPSS data (right).</p>

* <p style="text-align: justify;">
  <strong>Model and data dual-driven fault diagnosis:</strong> A novel model and data dual-driven fault diagnosis approach is proposed for satellite ACSs. Firstly, an Hi/H∞ optimization-based fault detection filter is considered as a residual generator, which is designed to be robust against disturbance and sensitive to a fault. Then, the occurrence of a fault can be detected based on the residual evaluation. Eventually, a random forest (RF) algorithm is developed to achieve fault isolation with system input–output and residual signals.
  </p>

<p align="center">
<img src="https://raw.githubusercontent.com/crazy0066/Xiaopeng.Xi/refs/heads/master/images/fig3.png" alt="fig3" width="520" style="height:auto;">
<img src="https://raw.githubusercontent.com/crazy0066/Xiaopeng.Xi/refs/heads/master/images/fig4.png" alt="fig4" width="390" style="height:auto;">
</p>
<p align="center">Flowchart of model and data dual-driven method (left). Fault detection results of triple faults (right).</p>


Applications
======
* <p style="text-align: justify;">
  <strong>Health status assessment for traction drive systems of high-speed train:</strong> High-speed trains are regarded as important transportation with high demands of safe operation. The traction drive systems of high-speed train mainly consist of traction transformer, traction converter, traction motor, gearbox, and wheel set. Subjected to the multi-physical field coupling effect and the multiple working conditions, it is very challenging to dynamically assess the health status of the critical components of traction drive systems. The major mission is to capture the degradation behavior of each component and estimate the health indicator of the system via deep learning methods.
  </p>

<p align="center">
<img src="https://raw.githubusercontent.com/crazy0066/Xiaopeng.Xi/refs/heads/master/images/fig7.png" alt="fig7" width="900" style="height:auto;">
</p>
<p align="center">Examples of IGBT failure and traction motor fault.</p>

* <p style="text-align: justify;">
  <strong>Remaining useful life prediction of blast furnace walls:</strong> A.
  </p>


* <p style="text-align: justify;">
  <strong>Fault classification of satellite attitude control systems:</strong> A.
  </p>

  
