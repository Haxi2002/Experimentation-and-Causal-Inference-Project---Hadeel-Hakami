# Experimentation-and-Causal-Inference-Project---Hadeel-Hakami

Injaz Smart Reminder: Causal Inference & A/B Testing Lab
An advanced end-to-end data science and experimental design repository implementing Causal Inference, A/B Testing, Variance Reduction (CUPED), and Sequential Testing (Mixture SPRT) workflows on educational platform user data to evaluate the impact of the "Smart Reminder" feature.

🚀 Project Overview
The interactive notebook and Python pipeline is structured into three core analytical sections alongside an advanced diagnostic interlude:

Part 1 — Causal Inference Rehearsal:

Constructs potential outcomes (
Y 
0
​
 ,Y 
1
​
 
) with heterogeneous treatment effects via a logistic baseline.

Evaluates Self-Selection Bias against the true Oracle ATE.

Implements Randomization and verifies covariate balance using Standardized Mean Differences (
SMD
).

Applies Fisher's Randomization Test and Neyman Design-Based Standard Errors.

Part 2 — Randomized Experiment:

Calculates statistical power, minimum detectable effect (
MDE
), and sample size requirements.

Performs A/A testing quality checks and detects Sample Ratio Mismatches (
SRM
) via Chi-square tests.

Analyzes the primary Overall Evaluation Criterion (
OEC
) lift and confidence intervals.

Deploys CUPED (Controlled-experiment Using Pre-Experiment Data) to reduce variance on support call guardrails.

Contrasts naive daily peeking false-positive inflation against the robust Always-Valid Mixture SPRT.

Interlude — Advanced Diagnostic Checks:

Conducts multi-covariate balance verification across demographic and behavioral features.

Computes Family-Wise Error Rates (FWER) and applies Bonferroni Corrections.

Performs subgroup heterogeneity analysis across digital literacy terciles and geographic regions.

Part 3 — Automated Decision Memo:

Executes automated decision rules checking practical significance (
≥2 pp
 lift), statistical significance (
p<0.05
), and guardrail safety to output definitive launch directives (SHIP NATIONALLY, HOLD AND EXTEND, or DO NOT SHIP).

🛠️ Tech Stack & Dependencies
Python 3.x

Pandas & NumPy: Data manipulation, numerical operations, and stochastic simulations.

Matplotlib & SciPy: Statistical modeling, hypothesis testing, and publication-ready data visualization.

⚙️ Quick Start
Install the required dependencies:

Bash
pip install numpy pandas matplotlib scipy
Run the script or Jupyter notebook directly. The script automatically pulls the underlying user dataset from the source, executes the simulation loops, generates diagnostic plots, and prints the automated decision memo.
