---
layout: default
---


<div style="display: flex; justify-content: center; align-items: center; height: 500px;">
  <img src="pic/paper/1.png" alt="111" style="width: 200%; max-width: 500px; height: auto;"/>
</div>


# 1. Abstract

  Autonomous driving is developing rapidly and has become a hot topic in both industry and research. The planning system plays a crucial role in meeting the requirements of autonomous driving, such as safety and effectiveness. However, current planning system designs may not effectively serve planning tasks. A typical modular planning system offers high interpretability and flexibility. However, it may cause task-agnostic problems between the upstream predictor and the downstream planner. End-to-end driving systems have a natural advantage in achieving system-wide integration, but their poor interpretability poses safety risks. To leverage the strengths and mitigate the weaknesses of existing systems, a task-unified planning framework is proposed, aiming to inspire the current prediction-planning paradigm. In this architecture, driving tasks are first modeled. Then, the predictor and planner are jointly designed and optimized based on the driving tasks. Finally, during the actual planning process, the upstream and downstream components remain relatively independent to allow flexible adjustments. The core of this architecture is a planning-oriented predictor named POP, which fully retains the advantages of modular systems by designing the predictor to optimize driving requirements. Comprehensive experiments demonstrate its effectiveness. Compared with typical modular systems, POP can reduce collision scenarios by nearly 50%, ensuring system safety without compromising driving efficiency or comfort, significantly enhancing overall planning performance.

# 2. Method

  ![img](pic/paper/2.png)

# 3. Experiments

## 1) Experiments details

<div style="display: flex; justify-content: center; align-items: center; height: 500px;">
  <img src="pic/paper/5.png" alt="555" style="width: 200%; max-width: 500px; height: auto;"/>
</div>


## 2) Baseline Compare

<div style="display: flex; flex-direction: row; justify-content: center;">
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px;">
    <img src="pic/baseline/cv.gif" alt="1" style="width: 250px; height: auto;"/>
    <figcaption>Physical-based</figcaption>
  </figure>
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px;">
    <img src="pic/baseline/grip.gif" alt="2" style="width: 250px; height: auto;"/>
    <figcaption>GRIP++</figcaption>
  </figure>
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px;">
    <img src="pic/baseline/walenet.gif" alt="3" style="width: 250px; height: auto;"/>
    <figcaption>WaleNet</figcaption>
  </figure>
</div>

<div style="display: flex; flex-direction: row; justify-content: center;">
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px;">
    <img src="pic/baseline/t.gif" alt="1" style="width: 250px; height: auto;"/>
    <figcaption>Trajectron++</figcaption>
  </figure>
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px;">
    <img src="pic/baseline/grip.gif" alt="2" style="width: 250px; height: auto;"/>
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
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px;">
    <img src="pic/case/usa.gif" alt="1" style="width: 350px; height: auto;"/>
    <figcaption></figcaption>
  </figure>
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px;">
    <img src="pic/case/zam-t.gif" alt="2" style="width: 350px; height: auto;"/>
    <figcaption></figcaption>
  </figure>
  <figure style="display: flex; flex-direction: column; align-items: center; margin-bottom: 20px;">
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



###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |


