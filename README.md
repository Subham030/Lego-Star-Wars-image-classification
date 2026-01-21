# Lego-Star-Wars-image-classification

### Model Configuration & Hyperparameters
1. Loss Function : Sparse Categorical Cross Entropy
2. Optimozer: Adam (Learning rate: 0.001)
3. Metrics: Accuracy
4. Callbacks: Early Stopping
   -Monitor: val_loss
   -Patience: 5

## Comparison between a custom-built Convolutional Neural Network (CNN) against a Transfer Learning approach using VGG16.

#### Custom CNN Results:
- **Accuracy:** 70%
- **Loss:** 0.5221
- **Observation:** While the model learned basic patterns, it reached a performance plateau quickly.
<img width="574" height="235" alt="Screenshot 2026-01-21 131530" src="https://github.com/user-attachments/assets/23e469b3-be8e-4d25-9b7d-69f0fe5dc2e8" />

#### VGG16 Transfer Learning Results:
- **Accuracy:** 90%
- **Loss:** 0.3656
- **Observation:** By leveraging pre-trained weights from ImageNet, the model achieved a 20% boost in accuracy. It demonstrated superior generalization on the Star Wars Lego test set.
