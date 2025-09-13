# AI driven Stop-Motion Style Transfer
This repository contains the code, experiments, and results for my bachelor’s thesis **“AI-driven Frame Generation for Stop Motion Effects in Video Games”**. The project explores how deep learning models (CycleGAN and Pix2Pix) can be used to transform conventional animations into a stop-motion style.

🌐 This research is novel and can open the door for more focus in this realm of art, and tech.


## 📂 Repository structure
```
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
```

## 🚀 How to run locally
1. Clone the repo:
   ```bash
   git clone https://github.com/YaldaAlhabibstopmotion-ai.git
   cd stopmotion-ai
   ```
2. Install dependencies (Python 3.11+ recommended):
   ```bash
   pip install -r requirements.txt
   ```
   or with Conda:
   ```bash
   conda env create -f environment.yml
   conda activate thesis-env
   ```
3. Launch Jupyter:
   ```bash
   jupyter lab
   ```

## 📊 Key notebooks
- **Results.ipynb** → Final experiments and evaluation  
- **M1…M4 notebooks** → Training/testing different Pix2Pix and CycleGAN models  
- **video_creation.ipynb** → Frame conversion into stop-motion-styled video  
- **Gradio_Setup.ipynb** → Simple interactive demo  



## 🙏 Acknowledgements
- Based on architectures from [CycleGAN and Pix2Pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) by Jun-Yan Zhu et al.  
- Supervised by *Prof. Milena Lazarova*.  
- Built with PyTorch, Quarto, and Jupyter.


