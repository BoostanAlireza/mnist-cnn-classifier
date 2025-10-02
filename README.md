# MNIST Digit Classification with CNN

A Convolutional Neural Network implementation for classifying handwritten digits from the MNIST dataset. Achieves 99%+ accuracy with proper data preprocessing, smart training strategies, and comprehensive evaluation.

## 🚀 Quick Start

1. **Install dependencies**:
   ```bash
   pip install tensorflow numpy matplotlib
   ```

2. **Run the notebook**:
   - Open `mnistcnn.ipynb` in Jupyter
   - Execute all cells (Cell → Run All)

## 🏗️ Model Architecture

```
Input (28×28×1) → Conv2D(32) → MaxPool → Conv2D(64) → MaxPool → Flatten → Dense(128) → Dropout → Dense(64) → Dropout → Dense(10) → Softmax
```

**Key Features:**
- 2 convolutional blocks with ReLU activation
- Max pooling for dimension reduction
- Dense layers with 50% dropout for regularization
- Early stopping and model checkpointing

## 📊 Results

- **Test Accuracy**: ~99%+
- **Data Split**: 50k train / 10k validation / 10k test

## 🔧 What's Included

- **Data Preprocessing**: Normalization, reshaping, one-hot encoding
- **Smart Training**: Early stopping prevents overfitting
- **Evaluation**: Test accuracy, sample predictions, confidence scores
- **Visualization**: Training history plots with overfitting detection
- **Educational**: Well-commented code explaining each step


## 🛠️ Customization

- Modify architecture (add layers, change filters)
- Adjust training parameters (batch size, epochs)
- Add data augmentation
- Experiment with different optimizers
