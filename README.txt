# 🔍 Image Sharpening using Knowledge Distillation

This project enhances blurred or low-resolution images using a lightweight CNN trained via knowledge distillation. A high-capacity teacher model transfers knowledge to a compact student model, enabling real-time performance with SSIM ~0.91 and PSNR ~28 dB.

## 🚀 Features
- Super-resolution student CNN
- Real-time enhancement (30+ FPS)
- Lightweight for deployment
- Evaluation: SSIM & PSNR

## 📦 Files
- `intel(1).ipynb`: Training & inference notebook
- `student_x4_balanced_50ep.pt`: Trained model weights

## 🧪 Dataset
Used downsampled DF2K (DIV2K + Flickr2K) with bicubic blur simulation.

## 💻 Run in Colab
You can test the notebook directly in [Google Colab](https://colab.research.google.com/drive/1dO3P1nCTdzcoktB9jgREt_-ic1GNbqVt#scrollTo=yKAUMCXu1c1z).

## ⚙️ Requirements
See `requirements.txt`.
