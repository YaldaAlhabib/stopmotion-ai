Stop-Motion Style Transfer — Thesis

This repository contains the code, experiments, and results for my bachelor’s thesis “AI-driven Frame Generation for Stop Motion Effects in Video Games”.
The goal of the project is to explore how deep learning models (CycleGAN and Pix2Pix) can be used to transform conventional animations into a stop-motion style. 
This research is novel and can open the door for more focus in this realm of art, and tech.


📂 Repository structure
thesis-stopmotion-ai/
├── index.ipynb         # Homepage for the website
├── _quarto.yml         # Quarto config for GitHub Pages
├── notebooks/          # All training/testing notebooks
│   ├── CycleGAN.ipynb
│   ├── pix2pix.ipynb
│   ├── M1_training_testing_cycleGAN.ipynb
│   ├── M2_training_testing_pix2pix.ipynb
│   ├── M3_training_testing_pix2pix.ipynb
│   ├── M4_training_testing_pix2pix.ipynb
│   ├── Results.ipynb
│   ├── video_creation.ipynb
│   └── Gradio_Setup.ipynb
├── images/             # Figures and cover image
└── README.md           # This file

🚀 How to run locally

Clone the repo:

git clone https://github.com/YaldaAlhabib/thesis-stopmotion-ai.git
cd thesis-stopmotion-ai


Install dependencies (Python 3.11+ recommended):

pip install -r requirements.txt


or if you use Conda:

conda env create -f environment.yml
conda activate thesis-env


Launch Jupyter:

jupyter lab

📊 Key notebooks

Results.ipynb → Final experiments and evaluation

M1…M4 notebooks → Training/testing different Pix2Pix and CycleGAN models

video_creation.ipynb → Frame conversion into stop-motion-styled video

Gradio_Setup.ipynb → Simple interactive demo



🙋 Acknowledgements

Based on architectures from CycleGAN and Pix2Pix

Supervised by [Your Professor’s Name].

Built with PyTorch, Quarto, and Jupyter.
