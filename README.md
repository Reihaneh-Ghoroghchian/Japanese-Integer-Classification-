# Japanese-Integer-Classification-
A deep learning project for classifying handwritten Japanese digits using CNNs in PyTorch Lightning. Models were trained on a grayscale MNIST-style dataset and tracked using Comet.ml.

📦 Project Highlights
Models: ResNet18, ResNet50, DenseNet121 (with LeNet-5, AlexNet, VGG-16 for comparison)

Dataset: Grayscale digit images (Train.pkl, Train_labels.csv, Test.pkl)

Augmentation: Affine transforms, contrast adjustment, normalization

Metrics: Achieved up to 99.7% validation accuracy and 90.1% on Kaggle

Tools: PyTorch, PyTorch Lightning, Comet.ml, Matplotlib, MONAI, Pandas

🧠 Training & Evaluation
Custom PyTorch datasets and loaders with advanced preprocessing

Trained with AdamW/RMSprop optimizers and LR tuning

Comet.ml used for tracking metrics, hyperparameters, and logs

Final models saved as .pt; predictions exported to .csv

