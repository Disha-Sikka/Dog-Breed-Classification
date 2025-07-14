# Dog-Breed-Classification

This project tackles image classification task of identifying dog breeds from images. With 157 unique breeds in the dataset, I trained the model from scratch (no pretrained weights!) to recognize everything from a golden retriever to an affenpinscher.

---

## DataSet

* A training set of dog images
* A validation set for performance tracking
* A test set for generating final predictions

The goal is to build a model that classifies a dog image into one of **157 breeds** as accurately as possible.

---
## Approach

We:

1. **Designed a lightweight CNN** with 4 convolutional blocks + classifier
2. Applied **data augmentation** to improve generalization
3. Used **Adam optimizer** with a **StepLR scheduler**
4. Trained for **25 epochs**, saving logs and checkpoints
5. Logged accuracy and losses for both train and validation sets

---


## 📊 Training Performance

```
Validation Accuracy after 25 epochs: ~3.17%
Training Loss: decreasing gradually from ~4.83 to ~4.17
```

