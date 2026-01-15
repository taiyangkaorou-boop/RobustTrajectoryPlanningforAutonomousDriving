# Robust Trajectory Planning for Autonomous Driving: A Factor Graph Approach Considering
Perception and Control Uncertainties

This project builds upon and extends the GPIR (Generalized Planning as Inference) framework.
<br>
(Original repository: [jchengai/gpir](https://github.com/jchengai/gpir))

---

## 🎥 Demonstration

### Video Demonstrations

#### Combined Demonstration
<p align="center">
  <strong>democom.mp4</strong>
  <br>
  📥 <a href="https://github.com/taiyangkaorou-boop/RobustTrajectoryPlanningforAutonomousDriving/raw/main/democom.mp4" target="_blank">Download democom.mp4 (14MB)</a>
  <br>
  <em>Figure 1: Comprehensive demonstration showing trajectory planning performance in complex dynamic scenarios.</em>
</p>

#### Obstacle Avoidance Demonstration
<p align="center">
  <strong>demoobs.mp4</strong>
  <br>
  📥 <a href="https://github.com/taiyangkaorou-boop/RobustTrajectoryPlanningforAutonomousDriving/raw/main/demoobs.mp4" target="_blank">Download demoobs.mp4 (11MB)</a>
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

> “The main limitation of this work is that the uncertainties are not well modeled (e.g., prediction uncertainty). However, we believe that planning as probabilistic inference is
a promising framework that can systematically deal with uncertainties, and this remains for future work.”

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
