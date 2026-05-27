# Joshua Laubach

**AV Simulation & ML Evaluation Engineer** · San Francisco, CA
Reinforcement learning, causal inference, and ODD-based evaluation for autonomous systems.

---

## Projects

### [DriveNet — End-to-End AV Simulation & ODD Evaluation](https://github.com/joshlaubach/drivenet-carla-av)
CARLA 0.9.16 · PPO · Behavior Cloning · Causal Inference

End-to-end AV pipeline spanning expert data collection through RL fine-tuning and causal fix validation.

- Collected **~97K expert frames** across **324 ODD condition combinations** (rain, night, fog, traffic density)
- Full pipeline: behavior cloning → PPO fine-tuning with custom reward shaping + road-rule monitor
- Applied **propensity score matching** to isolate per-condition impact on policy safety metrics
- Three sensor suites (RGB cam, multi-cam, LiDAR BEV) with 39-test CI benchmark suite

---

### [AI Robustness Evaluation — nuScenes Perception](https://github.com/joshlaubach/nuscenes-stability)
Faster R-CNN · PyTorch · COCO mAP · Calibration Analysis

- Fine-tuned Faster R-CNN ResNet-50 FPN on nuScenes CAM_FRONT with full reproducibility controls
- Surfaced **14.9pp precision drop at night** (F1: 0.554 day → 0.482 night) driven by false positive inflation
- Evaluated across day/night, traffic density, and geographic conditions at 9 score thresholds

---

### [AI Math Tutoring Platform](https://github.com/joshlaubach/math-problem-generator) *(in progress)*
Python · FastAPI · React/TypeScript · LLM APIs · SymPy

- LLM-driven hint generation with **SymPy-verified solution validation** — hints are mathematically correct, not just plausible
- Adaptive difficulty engine adjusts problem generation based on per-student KPI tracking
- Built on FastAPI + React/TypeScript; working toward a fully autonomous AI math tutor

---

## Skills

| Domain | Tools |
|--------|-------|
| **RL & ML** | PPO, DQN, Policy Gradient, CNNs, Behavior Cloning, LSTM/GRU, Causal Inference |
| **Simulation** | CARLA 0.9.16, Reward Shaping, ODD Coverage Design, Scenario Authoring |
| **Evaluation** | ODD Analysis, Adversarial Edge-Case Testing, Distribution Shift, Threshold Optimization |
| **Frameworks** | PyTorch, TensorFlow, Scikit-learn, XGBoost |
| **Languages** | Python, SQL, C++ (basic) |

---

## Education

- **M.S. Data Science & Artificial Intelligence** — Boston University
- **Postgrad Certificate, AI & ML** — California Institute of Technology
- **B.A. Applied Mathematics & Statistics** — UC Berkeley

---

[linkedin.com/in/josh-laubach](https://linkedin.com/in/josh-laubach) · [josh.laubach1@gmail.com](mailto:josh.laubach1@gmail.com)
