# Observation of various CNN architectures in object classification

[Dataset](https://www.kaggle.com/datasets/ash2703/handsignimages)

This research compares the performance of various Convolutional Neural Network (CNN) architectures in object classification tasks. The three main architectures analyzed are VGG16, ResNet50, and MobileNet. Each architecture is evaluated using classification report, confusion matrix, and metrics such as accuracy, precision, recall, and F1-score.

## Result

1. VGG16
Architecture: Consists of 16 training layers with a 3x3 kernel.
Pros: Effective for image recognition.
Disadvantages: Requires large computing power.
Results:
Accuracy: 59%
Macro average F1-score: 0.56
Problems: Classes like H and I have very low recall (14% and 11%).
Confusion Matrix: Many mispredictions in dominant classes, such as class E.
2. ResNet50
Architecture: Consists of 50 layers with residual blocks to overcome vanishing gradient problem.
Pros: Efficient and capable of learning complex features.
Disadvantages: Performance is affected by data bias.
Results:
Accuracy: 17%
Macro average F1-score: 0.12
Problems: Some classes like A, B, E, and H have an F1-score of 0.00.
Confusion Matrix: Prediction errors are dominant in classes G and F.
3. MobileNet
Architecture: Designed for devices with limited resources, such as mobile phones.
Pros: Lightweight and efficient with high performance.

## Conclusion
1. MobileNet performs best with high efficiency and near-perfect accuracy.
2. VGG16 performs reasonably well but is constrained by large computational power.
3. ResNet50 showed the lowest performance, possibly due to data bias or class distribution imbalance.

This research provides an important overview of the advantages and disadvantages of various CNN architectures in object classification tasks, especially in the context of datasets with uneven class distribution.
