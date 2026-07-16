# Chest-X-Ray-AI-Detection

This project, a ResNet-18 multi-classification model built with PyTorch, aims to assist in the automated screening of chest X-rays to detect multiple diseases (COVID-19, Pneumonia, or Tuberculosis) to improve the speed and accuracy of diagnosis.

# First Full Test: Adam Optimizer, Batch of 32, 10 Epochs
<img width="630" height="432" alt="image" src="https://github.com/user-attachments/assets/0e095be8-e2f5-4a10-8a75-c6b820e0c976" />
<img width="425" height="179" alt="image" src="https://github.com/user-attachments/assets/2ffbfc01-464e-4188-9e7c-a92d9f628e9d" />
Notes
- Performance: High Overall Precision
- Error: Some Confusion between Normal and Pneumonia
- Future Considerations
    - May consider implementing weighted random sampling, which ensures a proportional number of each category in sample batches during training, to address potential class imbalance issues in the sample in the future
    - May consider implementing a way for the model to save the best-performing parameters (based on validation loss) and return to them when training
