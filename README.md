# Inu Segmentation

## Overview
This is the segmentation project using U2-Net. In this project, we will segment the dogs from the images.
### $U^2 Net$
U2-Net is a U-structure architecture deep learning model designed for salient object detection and semantic segmentation. The goal is to distinguish between salient and non-salient regions. Salient Object Detection is a key task in computer vision to accurately detect and segment areas of an image that are visually prominent from a human visual system perspective.
There are comparable architectures with U2-Net, such as UNet, a highly popular model for semantic segmentation, MaskRCNN,  which use a Region Proposal Network to propose object bounding boxes, then classifies the proposed boxes and generates predicted bounding boxes and masks.

## Dataset
We will use the Dog segmentation dataset from kaggle. https://www.kaggle.com/datasets/santhoshkumarv/dog-segmentation-dataset <br>
The dataset is small but the quality is good. The masks are precise.

## Model
Model: U2-Net

## Training Details
Optimizer: Adam <br>
Learning Rate: 0.001 <br>
Batch Size: 6 (Configurable) <br>
Epochs: 400 (Configurable) <br>

## References
U2-Net Repo: https://github.com/xuebinqin/U-2-Net
