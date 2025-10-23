# FIT5230
"FIT5230 Milestone 3 Project: OSCP - An ultra-fast, 4.46ms adversarial purification defense system
 OSCP: One-Step Control Purification - Ultra-Fast Adversarial Defense
 
FIT5230 Milestone 3 Final Project - Light Team [Poker King]

This repository contains the final code, presentation materials, and documentation for the One-Step Control Purification (OSCP) system, an adversarial defense mechanism designed to break the long-standing speed bottleneck in diffusion-based defenses.

Team Members: Lu Rongqing, Yuan Cong

 Core Project Achievements

Our OSCP system achieves an industry-leading balance between speed and robustness, making real-time adversarial defense feasible.

Metric

Traditional Baseline ($\approx 500\text{ms}$)

OSCP Optimized Final Result

Improvement

Purification Speed (Single Step)

$\approx 500\text{ms}$

4.46 milliseconds

$\mathbf{100\times}$ Faster

Robustness (against PIAA)

$37.5\%$

$46.9\%$

$\mathbf{+25\%}$ Relative Gain

Key Innovations:

U-Net Capacity Enhancement ($\mathbf{hidden\_dim=128}$): Increased model size to effectively neutralize complex, evasive PIAA noise.

Adaptive Noise Control ($\mathbf{1.3\times}$): Empirically optimized signal amplification for potent single-step purification.

🎥 Demonstration & Submission Files

1. 10-Minute Video Demonstration

The video showcases the project goals, technical innovations, and live code execution of the $\mathbf{4.46\text{ms}}$ timing module and the $\mathbf{46.9\%}$ defense rate against PIAA.

Video Link: [INSERT VIDEO LINK HERE]

2. Core Code (Colab Notebook)

The runnable Jupyter Notebook containing the final optimized OSCP model, attack scripts, and evaluation modules.

Final Colab Notebook Link (Recommended Run Environment): [INSERT COLAB LINK HERE]

3. Presentation Slides

The full presentation used in the M3 video and live demo.

Presentation File: [/presentation/OSCP_ One-Step Real-Time Defense.pptx](./presentation/OSCP_ One-Step Real-Time Defense.pptx)

💻 Getting Started (Local Setup)

Prerequisites

Python 3.8+

PyTorch (CUDA enabled)

Required libraries (see the import section of the Jupyter notebook)

Running the Code

Clone the repository:

git clone [YOUR REPO URL]
cd [YOUR REPO NAME]


Install dependencies:
(Add your specific installation steps, e.g., pip install torch torchvision...)

pip install -r requirements.txt # (if you create this file)


Run the Notebook:
Open the oscp_baseline.ipynb file inside the /notebooks directory and run all cells sequentially to reproduce the results. We recommend using the Colab link above for the fastest reproduction.

🧑‍💻 Team Contribution

Lu Rongqing: Core architecture setup, U-Net capacity optimization ($\mathbf{hidden\_dim=128}$), presentation structure, and final analysis.

Yuan Cong: Adaptive noise control ($\mathbf{1.3\times}$) implementation, PIAA attack script development, code evaluation, and documentation.

🙏 License

This project is licensed under the MIT License.
