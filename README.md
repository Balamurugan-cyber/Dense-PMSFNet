# Dense-PMSFNet
🧠 PMDFNet: Pyramidal Multi-scale Dense Fusion Network for Retinal Vessel and FAZ Segmentation
🩺 Overview
This repository contains the implementation of PMDFNet, a deep learning architecture designed for the automatic segmentation of retinal blood vessels and the Foveal Avascular Zone (FAZ) from Optical Coherence Tomography Angiography (OCTA) images.

PMDFNet leverages multi-scale pyramidal fusion, dense encoder connections, and attention-based decoding to achieve high-accuracy segmentation results — essential for early diagnosis of Diabetic Retinopathy, macular ischemia, and other vascular-related retinal disorders.

🎯 Project Objective
To develop a deep learning-based solution that performs pixel-wise segmentation of retinal structures in OCTA images using a densely connected, multi-scale, and attention-enhanced network.

📊 Key Features
🔗 Dense Encoder using DenseNet-121 for rich feature reuse

🔺 Pyramidal Multi-Scale Fusion Module (MSPFM) to capture both local and global features

🧠 scSE Attention Blocks to focus on clinically relevant vessel regions

🔄 Deep Decoder with Fusion Layer for accurate reconstruction

✅ High Dice and IoU Scores on OCTA-500 dataset
The retinal vessels in the fundus are the only deeper microvessels in the human body that can be observed non-invasively. Changes in vessel diameter, curvature, and color can indicate clinical pathologies such as hypertension, diabetes, and atherosclerosis (Mookiah et al., 2021). For instance, diabetic retinopathy, a complication of diabetes, can lead to swelling of the blood vessels in the retinal, posing a significant threat to vision (Govindaswamy et al., 2020). Ophthalmologists can detect these changes using fundus images for early diagnosis of related diseases. However, the current manual labeling of retinal vessels is time-consuming and requires extensive expertise, leading to the potential oversight of fine diameter proliferative vessels (Yan, Yang, & Cheng, 2017). Additionally, challenges such as uneven brightness, low contrast, and high noise in fundus images have troubled clinicians. In this context, the development of automated and refined segmentation models is imperative for tackling these challenges effectively (Li et al., 2022a).

Low visibility in hazy weather causes the loss of image details in digital images captured by some imaging devices such as monitors. This paper proposes an end-to-end U-Net based residual network (URNet) to improve the visibility of hazy images. The encoder module of URNet uses hybrid convolution combining standard convolution with dilated convolution to expand the receptive field for extracting image features with more details. The URNet embeds several building blocks of ResNet into the junction between the encoder module and the decoder module. This prevents network performance degradation due to the vanishing gradient. After considering large absolute difference on image saturation and value components between hazy images and haze-free images in the HSV color space, the URNet defines a new loss function to better guide the network training. Experimental results on synthetic hazy images and real hazy images show that the URNet significantly improves the image dehazing effect compared to the state-of-the-art methods. (C) 2020 Elsevier B.V. All rights reserved.
