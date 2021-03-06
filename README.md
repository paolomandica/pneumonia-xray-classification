# Chest X-Ray Images Classification (Pneumonia)

In this project I trained a CNN for the classication of Chest X-Ray Images of healty/pneumonia cases, choosing the best one between 3 different approaches:
- a **custom** (deep) **CNN**;
- a **shallow CNN** (SCNNB);
- a **pre-trained ResNet50**.

I then chose the best model based on various metrics, optimal for medical analysis, and I **interpreted** the results using gradients-based techniques by using the *tf-explain* library.

Use [this link](https://nbviewer.jupyter.org/github/paolomandica/pneumonia-xray-classification/blob/main/main.ipynb) if you have problems visualizing the notebook.

## Dataset
The dataset used for the project is taken from the [Chest X-Ray Image (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) kaggle competition.

It consists of **5863 X-Ray images** (JPEG format) and 2 categories (**Pneumonia/Normal**), divided into:
- **train**: 1341 Normal, 3875 Pneumonia
- **test**: 234 Normal, 390 Pneumonia

## Files
- **main.ipynb**: notebook containing all the code for the completion of the project.
