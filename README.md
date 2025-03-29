# Maize-Leaf-Disease-Detection
1. Introduction
The project classifies maize leaf diseases using deep learning models.

Models used: DenseNet201, EfficientNet, InceptionNet, MobileNet, and XceptionNet.

 2. Tools & Dataset
Libraries: cv2, numpy, matplotlib, tensorflow.keras, seaborn.

Dataset:

Split into training, validation, and test sets.

Images resized to 
224
×
224
224×224.

Batch size: 32.

Augmentation: Rotation, shift, shear, zoom, and flip.

 3. Model Architecture
DenseNet201: Densely connected layers, high accuracy.

EfficientNet: Balanced accuracy and efficiency.

InceptionNet: Parallel convolution filters.

MobileNet: Lightweight model for efficiency.

XceptionNet: Depthwise separable convolutions, improved accuracy.

 4. Training & Evaluation
Loss Function: Categorical cross-entropy.

Optimizer: Adam.

Metrics: Accuracy, precision, recall, F1-score.

Callbacks:

Early stopping: Prevents overfitting.

Learning rate reduction: Lowers learning rate when improvement stalls.

 5. Results
Accuracy and loss curves plotted.

Model performance compared using metrics.

Best-performing model identified based on accuracy and efficiency.
