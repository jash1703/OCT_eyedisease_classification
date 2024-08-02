# OCT Eye Disease Classification

This project focuses on classifying eye diseases using Optical Coherence Tomography (OCT) images by leveraging different deep learning models. The models evaluated include VGG16, MobileNetV2, and InceptionV3.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Models Used](#models-used)
- [Results](#results)

## Project Overview

The OCT Eye Disease Classification project is designed to classify various eye diseases using Optical Coherence Tomography (OCT) images. By employing deep learning techniques and evaluating different convolutional neural network (CNN) architectures, this project aims to identify the most effective model for accurate disease classification. The project includes fine-tuning and comparing several pre-trained models to achieve optimal performance.

## Dataset

The dataset comprises OCT images categorized into distinct classes, each representing a specific eye disease. The dataset includes diverse images to cover various disease types and severity levels. The training set boasts 5,000 images per class, allowing to deep-dive into the intricacies of each condition. To refine and tune the models, a validation set of 1,000 images per class stands ready.

- CNV (Choroidal Neovascularization): An eye condition where abnormal blood vessels grow underneath the retina. These vessels can leak blood and fluid, leading to a bulge or bump in the macula.

- DME (Diabetic Macular Edema): A consequence of diabetes, this condition is characterized by fluid accumulation in the macula due to leaking blood vessels. Without treatment, DME can lead to blindness.

- Drusen: Tiny yellow or white deposits under the retina. They're common as we age, but a large number in one place or their rapid increase can indicate a problem, such as age-related macular degeneration (AMD).
- we have the eyes that are untouched by these conditions, categorized under 'Normal'.

![Screenshot 2024-08-03 031453](https://github.com/user-attachments/assets/a913c2b1-000e-4813-a892-0a07b9b95591)

## Models Used

The following deep learning models were used:

- **VGG16**: Known for its simplicity and depth, it provides a good baseline for image classification tasks.
- **MobileNetV2**: Optimized for mobile and embedded vision applications, this model is lighter and faster.
- **InceptionV3**: A more complex model that includes factorized convolutions, leading to better performance on large-scale datasets.


## Results

Based on the models tested:

- The **VGG16** model provided the best performance without significant overfitting, making it the most suitable model for this classification task.

