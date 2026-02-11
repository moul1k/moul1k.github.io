---
layout: default
---

<style>
body {
  line-height: 1.45;
}

.wrapper {
  max-width: 760px;
}

h1 {
  margin-top: 8px;
  margin-bottom: 4px;
}

h2 {
  margin-top: 22px;
  margin-bottom: 6px;
}

p {
  margin: 6px 0;
}

.section-divider {
  margin: 22px 0;
  border-top: 1px solid #e6e6e6;
}

.top-links {
  margin-top: 6px;
  margin-bottom: 12px;
}

.top-links a {
  margin-right: 14px;
  font-weight: 500;
  color: #1f4fd8;
  text-decoration: none;
  transition: color 0.2s ease;
}

.top-links a:hover {
  text-decoration: underline;
  color: #163bb5;
}

.button-link {
  display: inline-block;
  padding: 3px 9px;
  margin-right: 6px;
  margin-top: 6px;
  font-size: 13px;
  border: 1px solid #1f4fd8;
  border-radius: 4px;
  color: #1f4fd8;
  text-decoration: none;
  transition: all 0.2s ease;
}

.button-link:hover {
  background-color: #1f4fd8;
  color: white;
}
</style>


<p align="center">
<img src="profile.jpeg" width="115" style="border-radius:50%;">
</p>

<h1 align="center">Moulik Kumar</h1>

I’m a graduate student in **Data Science at the University of Colorado Boulder**, originally from **Pune, India**. Before moving into data science, I studied **Physics at IIT Kharagpur**, where I became interested in how mathematical structure and computational systems intersect.

I’m drawn to analytically grounded yet operationally complex problems - building models that clarify structure rather than merely optimize metrics.

---

## Current Work & Interests

I’m currently working under **[Professor Maria Antoniak](https://maria-antoniak.github.io/)** on annotating and identifying literary clichés in model-generated prose, studying how large language models internalize and reproduce literary conventions.

My broader interests include NLP, computer vision, scientific and physics-informed ML, quantitative data analysis, and quantum information theory.

---

## Work Experience

**PubMatic - CTO Team Intern (Machine Learning)**  

At PubMatic, I worked on multimodal machine learning systems for political video advertisement analysis during the 2024 U.S. election cycle. The system integrated visual embeddings from video frames, OCR-extracted textual signals, and audio-derived features into unified classification pipelines. I helped design model architectures combining CNN-based encoders with transformer-style representations and structured advertiser metadata. The deployment pipeline processed large-scale campaign datasets using optimized Python and SQL workflows for near real-time inference. Performance was evaluated using precision-recall metrics under class imbalance constraints, achieving high precision in candidate identification tasks. I also contributed to entity resolution systems using fuzzy matching and named entity recognition models with near-production precision levels.

**IISER Bhopal - Summer Research Intern (NLP)**  

At IISER, I developed subgenre classification models using hybrid neural and linguistic feature approaches on the Brown corpus. The system combined BiLSTMs with attention mechanisms, TF-IDF features, and structured syntactic indicators. Careful preprocessing ensured clean train-test splits and minimized leakage across categories. Multiple architectures were evaluated under cross-validation to stabilize macro-F1 performance. The final model balanced interpretability with competitive classification accuracy across subgenres.

---

## Selected Projects

**Machine Learning – Driven Discovery of Stable Heusler Alloys**

This project focused on predicting thermodynamic stability in Heusler compounds using supervised and generative machine learning models. I implemented XGBoost classifiers achieving high test accuracy and CGCNN graph neural networks with strong R² performance for formation energy prediction. To explore compositional search, I trained conditional WGAN-GP models to generate candidate stable alloys. The workflow integrated materials database preprocessing, compositional feature engineering, and graph-based structural representations.

<a href="#" class="button-link">Paper</a>
<a href="#" class="button-link">Code</a>

**Building Resilience through ESG: Evaluating Indian PSUs**

This project examined how ESG indicators correlate with financial resilience using panel econometrics and machine learning. I implemented fixed-effects regression models, GMM estimators, and simulated stress-testing scenarios across multi-year PSU financial datasets. Feature normalization and structured panel construction were central to the modeling process. Results identified statistically significant governance-related indicators associated with resilience under adverse conditions.

<a href="#" class="button-link">Paper</a>
<a href="#" class="button-link">Code</a>

**Statistical NLP Analysis of Literary Style**

This analysis compared stylistic distributions between Project Gutenberg texts and Reddit WritingPrompts data. I applied lexical richness metrics, readability indices, hypothesis testing, and bootstrap resampling to quantify stylistic divergence. Rather than treating style as classification, the focus was on measuring distributional shifts across lexical and structural dimensions.

<a href="#" class="button-link">Paper</a>
<a href="#" class="button-link">Code</a>

**Learning to Control Active Matter**

This project applied TD Actor-Critic reinforcement learning to stochastic particle simulations inspired by Vicsek-style collective motion models. The environment modeled alignment dynamics under noise, and policies were evaluated using order parameters and convergence metrics. The integration of numerical simulation and policy-gradient optimization enabled controllable emergent behavior.

<a href="#" class="button-link">Paper</a>
<a href="#" class="button-link">Code</a>

**Quantum Prisoner’s Dilemma Simulation**

Using IBM Qiskit, I implemented parameterized quantum strategies encoded as unitary transformations on entangled qubit states. Payoff matrices were computed across varying entanglement strengths to observe equilibrium shifts. The simulations demonstrated convergence toward cooperative equilibria under maximal entanglement.

<a href="#" class="button-link">Paper</a>
<a href="#" class="button-link">Code</a>

**Diffusion-Limited Aggregation (Fractal Simulation)**

This simulation modeled stochastic random-walk particle attachment to generate fractal growth structures. Fractal dimensions were estimated using box-counting methods to validate scaling behavior. The results aligned with theoretical DLA properties observed in statistical physics literature.

<a href="#" class="button-link">Paper</a>
<a href="#" class="button-link">Code</a>

---

## Publications

**Multi-Modal Machine Learning for Political Video Advertisement Analysis**  
<a href="https://www.ijcaonline.org/archives/volume186/number46/multi-modal-machine-learning-for-political-video-advertisement-analysis-integrating-audio-textual-and-visual-features/" class="button-link" target="_blank">View</a>

**Building Resilience through ESG: Evaluating Indian PSUs**  
<a href="https://drive.google.com/file/d/1GPjbZ0KNkRzsak2oeGqKfjWsh2IO8HDt/view?usp=sharing" class="button-link" target="_blank">View</a>
