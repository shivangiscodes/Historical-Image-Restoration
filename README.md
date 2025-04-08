
# Bringing Old Photo Back to Life

This project uses deep learning to restore and enhance old, faded, or damaged photographs. It is based on the paper _"Bringing Old Photos Back to Life"_ and leverages a multi-stage pipeline for image enhancement, face detection, and colorization.

## 🧠 Project Overview

Many old photos suffer from various types of degradation such as blur, noise, scratches, and fading. This project aims to:

- Detect and enhance facial features in old photos.
- Restore clarity and remove degradation.
- Optionally colorize black-and-white photos using AI.

## 📁 Project Structure

- `Bringing_Old_Photo_Back_to_Life.ipynb`: The main notebook that demonstrates the step-by-step restoration pipeline.
- `input/`: Folder where you can place your old photos to be restored.
- `output/`: Folder where the enhanced results are saved.

## 🚀 Features

- **Face Detection & Alignment** using pretrained models.
- **Photo Restoration** using deep learning networks like UNet or DeOldify.
- **Optional Colorization**.
- End-to-end processing pipeline using OpenCV and PyTorch.

## 📦 Requirements

You can install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

Common dependencies include:

- Python 3.7+
- OpenCV
- NumPy
- Torch
- torchvision
- PIL (Pillow)
- imageio
- scikit-image
- facenet-pytorch (optional for better face detection)

## 🧪 How to Use

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Old-Photo-Restoration.git
cd Old-Photo-Restoration
```

2. Place your old images in the `input/` directory.

3. Run the notebook:

```bash
jupyter notebook Bringing_Old_Photo_Back_to_Life.ipynb
```

4. Follow the instructions in the notebook to process and view results.

## 📷 Example

| Original | Restored |
|----------|----------|
| ![](examples/original.jpg) | ![](examples/restored.jpg) |

## 📚 Reference

This implementation is inspired by the paper:

> **Zhang, Ziyu, et al.** “Bringing Old Photos Back to Life.” CVPR 2020.  
> [Paper Link](https://arxiv.org/abs/2004.09484)

GitHub Repo (Official): [https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life](https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life)

## 📝 License

This project is for educational and research purposes only.
