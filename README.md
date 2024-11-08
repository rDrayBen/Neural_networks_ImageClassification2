# Neural_networks_ImageClassification2

In this project, I tried to apply different solutions to the image classification problem with Caltech101 dataset. There were used:
1. Plain CNN model implemented from scratch(didn't perform well, which caused overfitting)
2. Pretrained ResNet model with frozen parameters(did a better job and got 80% accuracy on val data)
3. Finally, pretrained fine-tunned ResNet model, which achieved 95% accuracy results.

Besides implementing training and validation processes, I performed some evaluation checks, using several popular metrics like classification report, ROC-AUC etc.
