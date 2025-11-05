##  Explainable Deepfake Detection and Real Image Reconstruction using Vision Transformers


###  Overview

Developed an **explainable deep learning pipeline** for detecting and reconstructing **deepfake satellite imagery** using **Vision Transformers (ViT)**, **Autoencoders**, and **Stable Diffusion Img2Img** refinement. The project integrates **explainable AI (XAI)** principles to provide transparent model interpretations while ensuring high classification accuracy and image restoration quality.

---

###  Key Contributions

* Designed an **end-to-end detection and reconstruction system** for AI-generated satellite imagery.
* Implemented a full pipeline covering **dataset preprocessing, model training, validation, and interpretability** using **PyTorch**.
* Trained a **ViT-Small** model on the **DM-AER-DeepFake-V1 dataset**, achieving reliable **real vs. fake** classification.
* Integrated **Autoencoder-based cleanup** and **Stable Diffusion’s Img2Img pipeline** for realistic reconstruction of fake images.
* Applied **Grad-CAM** and attention visualization techniques to explain ViT decision-making and enhance interpretability.
* Evaluated reconstruction quality using **PSNR (Peak Signal-to-Noise Ratio)** and **SSIM (Structural Similarity Index Measure)** metrics.
* Utilized frameworks including **PyTorch**, **timm**, **OpenCV**, and **scikit-image** for training, visualization, and evaluation.
* Advanced the field of **satellite image forensics** by developing a transparent and interpretable model to counter AI-driven misinformation.

---

###  Tech Stack

* **Languages & Frameworks:** Python, PyTorch, timm
* **Libraries:** OpenCV, scikit-image, matplotlib, NumPy
* **Models Used:** Vision Transformer (ViT-Small), Autoencoder, Stable Diffusion Img2Img
* **Concepts:** Explainable AI (XAI), Grad-CAM, PSNR, SSIM

---

### Results

* Achieved high detection accuracy on the DM-AER-DeepFake-V1 dataset.
* Generated interpretable **attention heatmaps** for decision transparency.
* Improved image quality and realism through reconstruction and guided diffusion refinement.



