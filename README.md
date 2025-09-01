# Super-Resolution-of-Pixelated-Images-with-SRGAN-and-EDSR
# 🖼️ Image Super-Resolution (EDSR + SRGAN)

A deep learning project that applies **super-resolution** techniques to enhance pixelated images.  
It combines **EDSR (Enhanced Deep Super-Resolution Network)** and **SRGAN (Super-Resolution GAN)** to achieve both **distortion-minimized** and **photo-realistic** high-resolution outputs.  

---

## 🚀 Features

### 🔬 EDSR (Enhanced Deep Super-Resolution)
- High PSNR/SSIM scores for distortion minimization  
- Residual learning with deep convolutional blocks  
- Produces sharp and detailed high-resolution reconstructions  

### 🎨 SRGAN (Super-Resolution GAN)
- Uses GAN-based generator and discriminator  
- Optimized for perceptual realism  
- Generates natural textures and photo-like details  

### 📊 Comparative Analysis
- **EDSR** → Quantitative improvement (PSNR, SSIM)  
- **SRGAN** → Qualitative improvement (visual realism)  

---

## 🛠️ Technologies Used
- Python 3.8+  
- TensorFlow / Keras  
- NumPy, OpenCV  
- Matplotlib, scikit-image  

---

## 📂 Project Structure
├── data/ # Dataset (DIV2K HR images)
├── models/
│ ├── edsr_model.py # EDSR definition
│ ├── srgan_generator.py # SRGAN generator
│ ├── srgan_discriminator.py # SRGAN discriminator
├── train/
│ ├── train_edsr.py # EDSR training script
│ ├── train_srgan.py # SRGAN training script
├── results/ # Sample outputs (LR → EDSR → SRGAN → HR)
└── README.md


---

## 📊 Dataset
We use the **DIV2K dataset** for training and evaluation.  


Observation:

EDSR excels in distortion reduction (higher PSNR/SSIM).

SRGAN generates perceptually realistic, visually pleasing images.

📈 Evaluation

EDSR → Best for tasks requiring accurate detail reconstruction.

SRGAN → Best for human-perceived visual quality.

📚 References

EDSR: Enhanced Deep Residual Networks (CVPR 2017)

SRGAN: Photo-Realistic Super-Resolution GAN (CVPR 2017)

DIV2K Dataset

✨ Author

Developed by Srikar Reddy
