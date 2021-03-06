# Plant Pathology

## Problem Statement
Misdiagnosis of the many diseases impacting agricultural crops can lead to misuse of chemicals leading to the emergence of resistant pathogen strains, increased input costs, and more outbreaks with significant economic loss and environmental impacts. Current disease diagnosis based on human scouting is time-consuming and expensive, and although computer-vision based models have the promise to increase efficiency, the great variance in symptoms due to age of infected tissues, genetic variations, and light conditions within trees decreases the accuracy of detection.

## Objectives
Objectives of ‘Plant Pathology Challenge’ are to train a model using images of training dataset to 1) Accurately classify a given image from testing dataset into different diseased category or a healthy leaf; 2) Accurately distinguish between many diseases, sometimes more than one on a single leaf; 3) Deal with rare classes and novel symptoms; 4) Address depth perception—angle, light, shade, physiological age of the leaf; and 5) Incorporate expert knowledge in identification, annotation, quantification, and guiding computer vision to search for relevant features during learning.

## Dataset

---
## Architecture
EfficientNetB7
<p align = center>
<img src = "efficient_net.png">
</p>

## Hyper parameters
- learning_rate = 0.00009
- epochs = 50
- batch_size = 64
- training_unit = tpu(kaggle provides 8 tpu-V3 to train)
- optimizer = adam
- loss = categorical_cross_entropy

## Results
- Accuracy = 0.93152