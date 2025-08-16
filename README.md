# 🥈IEEE HSB ComSoc Modifier ML Competition 2025 – Leaf-wise Mulberry Classification


## This project achieved **2nd Place** in the **IEEE HSB ComSoc Modifier Machine Learning Competition 2025**,
### which consisted of three stages:
 1️⃣ **Model Building (via Kaggle)**    2️⃣ **Presentation**     3️⃣ **Live Debugging**.

## Competition Overview
The Kaggle competition Leaf-wise Mulberry Classification focused on identifying the cultivar of mulberry leaves from a dataset of 5,262 annotated images across 10 distinct classes.
The dataset included natural outdoor variations such as lighting, angles, and backgrounds, making it a challenging real-world classification task.

This competition was integrated into the IEEE HSB ComSoc Modifier ML Competition 2025, which consisted of three consecutive stages:

1️⃣ **Model Building – Kaggle Stage**
Participants were tasked with building a high-performance machine learning model using the official Kaggle dataset. The model needed to:

- Handle noise and variability in real-world leaf images
- Accurately classify leaf cultivars
- Generalize well across validation data
  
2️⃣ **Presentation Stage – Technical Briefing**


Qualified teams delivered a detailed technical presentation covering:

- Their modeling pipeline and design choices
- Performance metrics and evaluation strategy
- Model challenges, limitations, and proposed improvements . This was presented to a panel of IEEE and academic judges.

3️⃣ **Debugging Stage – Live Problem Solving**

In the final stage, teams faced real-time debugging and optimization challenges, including:

- Fixing code snippets or broken training scripts
- Diagnosing model issues like overfitting or low generalization
- Applying rapid improvements to augment performance under pressure
This tested the participants' problem-solving speed, ML understanding, and code efficiency.

Together, these stages evaluated not only modeling ability but also technical communication and live debugging under constraints, providing a holistic measure of applied machine learning skill.

## My Approach
- **Model**: Used EfficientNetB3 (transfer learning) with additional custom layers
- **Preprocessing**: Applied resizing, normalization
= **Augmentation**: Heavy use of Albumentations for robustness
- **Training Strategy**: Cosine Annealing + ReduceLROnPlateau for learning rate scheduling
- **Regularization**: Applied dropout and batch normalization
- **Debugging Stage**: Fixed overfitting, tweaked learning rate and augmentations under time pressure
  
## Folder Descriptions
- **data/:** Contains the validation predictions submitted for debugging or evaluation on kaggle.
- **notebooks/:** Includes the complete model development pipeline (EfficientNet, augmentation, training loop, etc.).
- **presentation/:** Final presentation used to explain model architecture, metrics, and strategy.
## Contact
If you have any questions or would like to connect, feel free to reach out:

Nada Mahmoud
**Email:** nadas.mahmoud4661@gmail.com
**LinkedIn:** https://www.linkedin.com/in/nada-mahmoud-n1466
Email: nadas.mahmoud4661@gmail.com
LinkedIn: https://www.linkedin.com/in/nada-mahmoud-n1466
