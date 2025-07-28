# 🧠 Dense-PMSFNet

## PMDFNet: Pyramidal Multi-scale Dense Fusion Network for Retinal Vessel and FAZ Segmentation

---

### 📌 Overview

**Dense-PMSFNet** implements **PMDFNet**, a deep learning architecture for automatic segmentation of retinal blood vessels and the **Foveal Avascular Zone (FAZ)** from **Optical Coherence Tomography Angiography (OCTA)** images.

It combines multi-scale pyramidal feature extraction, dense connections, and attention-based decoding mechanisms to produce high-precision segmentation results—critical for early diagnosis of **Diabetic Retinopathy**, **macular ischemia**, and other retinal vascular disorders.

---

### 🎯 Objective

To design a pixel-wise segmentation network that:
- Utilizes densely connected encoders,
- Fuses multi-scale contextual features,
- Enhances decoding with attention mechanisms,
- Achieves high accuracy on OCTA datasets.

---

### 📊 Key Features

- 🔗 **Dense Encoder**: Leverages **DenseNet-121** for rich feature reuse and gradient flow.
- 🔺 **Pyramidal Multi-Scale Fusion Module (MSPFM)**: Captures both **local and global** spatial features for improved segmentation context.
- 🧠 **Attention-based Deep Decoder**: Refines output by fusing important spatial-channel information.
- 📈 **Superior Metrics**: Achieves **high Dice and IoU** scores on the **OCTA-500** dataset.

---

### 📚 Motivation

- Retinal vessels are the only deep microvessels in the human body that can be observed **non-invasively**.
- Pathological changes (diameter, color, curvature) indicate diseases like **diabetic retinopathy**, **hypertension**, and **atherosclerosis**.
- Manual annotation of retinal vessels is **time-consuming** and prone to **human error**.
- Fundus images present challenges like **low contrast**, **uneven illumination**, and **noise**.
- Hence, an **automated segmentation model** like PMDFNet helps ophthalmologists in **early disease detection**.

---

### 🔍 Clinical Relevance

> *"Ophthalmologists can detect early microvascular changes from fundus images; however, manual processes are prone to oversight, especially with fine-diameter vessels. Dense-PMSFNet automates this, providing consistent and accurate support for medical professionals."*

---

### 🧪 Dataset

- **OCTA-500** Dataset: A publicly available, annotated OCTA image dataset used for evaluating vessel and FAZ segmentation performance.

---

### 🧠 Model Architecture

1. **Encoder**:
   - Based on **DenseNet-121**
   - Promotes feature reuse and mitigates vanishing gradients

2. **MSPFM** (Multi-Scale Pyramidal Fusion Module):
   - Aggregates multi-resolution features
   - Balances fine and coarse information

3. **Decoder with Attention**:
   - Improves spatial awareness in the segmentation output
   - Merges multi-level features for precise boundary delineation

---

### 💬 Related Research Insights

- **AI in Retinal Imaging**:
  > A study using AI on OCTA B-scans showed that tomographic and vascular features significantly differ between diabetic and healthy eyes. The AI model achieved an **AUC of 0.91**, indicating its potential in **early detection** of diabetic changes.

- **Dehazing in Medical Imaging**:
  > Low visibility in hazy conditions degrades imaging quality. The **URNet** model (UNet + ResNet blocks + dilated convolution) was proposed to enhance such images, ensuring more robust feature extraction in medical and real-world scenarios.

---

### 🤝 Contributing

If you'd like to contribute:
1. Fork the repo
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

---

### 📜 Citations

If you use this work, please cite:

```bibtex
@article{yourcitation2025,
  title={PMDFNet: Pyramidal Multi-scale Dense Fusion Network for Retinal Vessel and FAZ Segmentation},
  author={Author1, Author2, Contributor},
  journal={Medical Image Analysis},
  year={2025},
  publisher={Elsevier}
}
