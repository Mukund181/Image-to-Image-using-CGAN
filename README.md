# 🎨 Pix2Pix Image-to-Image Translation using PyTorch

This project demonstrates a simplified implementation of **Pix2Pix**, a Conditional GAN (cGAN) used for **paired image-to-image translation** tasks, such as converting sketches to realistic images.

---

## 📌 Overview

Given a **paired image** (e.g., a sketch on the left and a photo on the right), the model learns to generate the photo from the sketch using a generator–discriminator setup.

- Generator: A simplified U-Net model
- Discriminator: A basic PatchGAN-style classifier
- Training input: Paired images (left = input, right = target)

---

## 🧠 How It Works

1. Load a single paired image (`city.jpg`) where:
   - Left half is the **input**
   - Right half is the **target**
2. Preprocess and split the image
3. Run through the generator to produce an output
4. Visualize **input**, **generated output**, and **ground truth target**

---
