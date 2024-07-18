---
layout: default
---


# Abstract

<div style="display: flex; justify-content: center; align-items: center; height: 500px;">
  <img src="pic/paper/figure1.png" alt="111" style="width: 200%; max-width: 500px; height: auto;"/>
</div>

  Infrastructure sensors installed at elevated positions offer a broader perception range and encounter fewer occlusions. Integrating both infrastructure and ego-vehicle data through V2X communication, known as vehicle-infrastructure cooperation, has shown considerable advantages in enhancing perception capabilities and addressing corner cases encountered in single-vehicle autonomous driving.
However, cooperative perception still faces numerous challenges, including limited communication bandwidth and practical communication interruptions.
In this paper, we propose CTCE, a novel framework for cooperative 3D object detection. This framework transmits queries with temporal contexts enhancement, effectively balancing transmission efficiency and performance to accommodate real-world communication conditions.
Additionally, we propose a temporal-guided fusion module to further improve performance. The roadside temporal enhancement and vehicle-side spatial-temporal fusion together constitute a multi-level temporal contexts integration mechanism, fully leveraging temporal information to enhance performance.
Furthermore, a motion-aware reconstruction module is introduced to recover lost roadside queries due to communication interruptions.
Experimental results on V2X-Seq and V2X-Sim datasets demonstrate that CTCE outperforms the baseline QUEST, achieving improvements of $3.8\%$ and $1.3\%$ in mAP, respectively. Experiments under communication interruption conditions validate CTCE's robustness to communication interruptions.

# Method

  ![img](pic/paper/figure2.png)

<!--
# 3. Experiments

## 1) Experiments details

<div style="display: flex; justify-content: center; align-items: center; height: 500px;">
  <img src="pic/paper/5.png" alt="555" style="width: 200%; max-width: 500px; height: auto;"/>
</div>


## 2) Baseline Compare

<div style="display: flex; flex-direction: row; justify-content: center;">
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px; height: 400px;">
    <img src="pic/baseline/cv.gif" alt="1" style="width: 350px; height: auto;"/>
    <figcaption>Physical-based</figcaption>
  </figure>
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px; height: 400px;">
    <img src="pic/baseline/grip.gif" alt="2" style="width: 350px; height: auto;"/>
    <figcaption>GRIP++</figcaption>
  </figure>
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px; height: 400px;">
    <img src="pic/baseline/walenet.gif" alt="3" style="width: 350px; height: auto;"/>
    <figcaption>WaleNet</figcaption>
  </figure>
</div>

<div style="display: flex; flex-direction: row; justify-content: center;">
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px; height: 400px;">
    <img src="pic/baseline/t.gif" alt="1" style="width: 350px; height: auto;"/>
    <figcaption>Trajectron++</figcaption>
  </figure>
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px; height: 400px;">
    <img src="pic/baseline/tp.gif" alt="2" style="width: 350px; height: auto;"/>
    <figcaption>POP</figcaption>
  </figure>
</div>




## 2) Planning performance

### a) Non-reactive

<div style="display: flex; flex-direction: row; justify-content: center;">
  <figure style="display: flex; flex-direction: column; align-items: center; margin: 0 20px 20px 0; height: 400px;">
    <img src="pic/case/bgr.gif" alt="1" style="width: auto; max-width: 100%; height: auto; margin-bottom: 10px;"/>
    <figcaption></figcaption>
  </figure>
  <figure style="display: flex; flex-direction: column; align-items: center; margin: 0 20px 20px 0; height: 400px;">
    <img src="pic/case/d.gif" alt="2" style="width: auto; max-width: 100%; height: auto; margin-bottom: 10px;"/>
    <figcaption></figcaption>
  </figure>
  <figure style="display: flex; flex-direction: column; align-items: center; margin: 0 0 20px 0; height: 400px;">
    <img src="pic/case/sind.gif" alt="3" style="width: auto; max-width: 100%; height: auto; margin-bottom: 10px;"/>
    <figcaption></figcaption>
  </figure>
</div>

<div style="display: flex; flex-direction: row; justify-content: center;">
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px; height: 400px;">
    <img src="pic/case/usa.gif" alt="1" style="width: 350px; height: auto;"/>
    <figcaption></figcaption>
  </figure>
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px; height: 400px;">
    <img src="pic/case/zam-t.gif" alt="2" style="width: 350px; height: auto;"/>
    <figcaption></figcaption>
  </figure>
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px; height: 400px;">
    <img src="pic/case/zam-zip.gif" alt="3" style="width: 350px; height: auto;"/>
    <figcaption></figcaption>
  </figure>
</div>


### b) Reactive

<div style="display: flex; flex-direction: row; justify-content: center;">
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px;">
    <img src="pic/case/usa-int.gif" alt="1" style="width: 350px; height: auto;"/>
    <figcaption></figcaption>
  </figure>
</div>


-->
