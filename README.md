# Robust Trajectory Planning for Autonomous Driving: A Factor Graph Approach Considering
Perception and Control Uncertainties

This project builds upon and extends the GPIR (Generalized Planning as Inference) framework.
<br>
(Original repository: [jchengai/gpir](https://github.com/jchengai/gpir))

---

## 🎥 Demonstration

### Video Demonstrations

<p align="center">
  <strong>Combined Demonstration (democom.mp4)</strong>
  <br>
  <video src="democom.mp4" width="800" style="border-radius: 10px; box-shadow: 0px 4px 10px rgba(0,0,0,0.1);" controls>
  </video>
  <br>
  <em>Figure 1: Comprehensive demonstration showing trajectory planning performance in complex dynamic scenarios.</em>
</p>

<p align="center">
  <strong>Obstacle Avoidance Demonstration (demoobs.mp4)</strong>
  <br>
  <video src="demoobs.mp4" width="800" style="border-radius: 10px; box-shadow: 0px 4px 10px rgba(0,0,0,0.1);" controls>
  </video>
  <br>
  <em>Figure 2: Detailed demonstration of obstacle avoidance behavior with uncertainty factor integration.</em>
</p>

### GIF Demonstration

<p align="center">
  <img src="show.gif" alt="Planning Demonstration with Uncertainty Factors" width="800" style="border-radius: 10px; box-shadow: 0px 4px 10px rgba(0,0,0,0.1);">
  <br>
  <em>Figure 3: Animated GIF demonstration of superior performance in complex dynamic scenarios (lane changes and obstacle avoidance) after integrating uncertainty factors.</em>
</p>

---

## 💡 Research Motivation

Our work stems from the future outlook discussed in the original GPIR paper:

> “A major limitation of this work is the failure to adequately model uncertainty (e.g., prediction uncertainty)... The framework of treating planning as probabilistic reasoning holds great potential for systematically handling uncertainty.”

To address the original framework's shortcomings in uncertainty modeling, we further explore the potential of “planning as probabilistic reasoning” to achieve systematic uncertainty handling.

## ✨ Core Contributions

We introduce two key uncertainty factors into the probabilistic inference framework to enhance system robustness:

* 👁️ Perceptual Uncertainty Factor
* ⚙️ Control Uncertainty Factor

## 📈 Experimental Results

By integrating these factors, our approach demonstrates superior performance over the original GPIR baseline in complex dynamic scenarios such as lane changes and obstacle avoidance.

The generated vehicle trajectories exhibit:
* Significantly smoother motion
* Markedly enhanced ride comfort
* Overall planning performance with greater robustness

## 🔓 Code Availability

> Note: The source code will be released in this repository upon formal acceptance of the corresponding paper. Stay tuned!
