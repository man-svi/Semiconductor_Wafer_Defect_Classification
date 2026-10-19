# Semiconductor_Wafer_Defect_Classification
A CNN-based machine learning project for classifying semiconductor wafer defects.
# Semiconductor Wafer Defect Classification Using CNN

## Project Overview
This project uses Machine Learning and a Convolutional Neural Network (CNN) to classify semiconductor wafer maps into four defect categories. It demonstrates the application of image classification in semiconductor manufacturing and VLSI.

## Dataset
The project uses the WM-811K Wafer Map Dataset. A sample of 2,000 wafer maps is selected from four defect categories:
- Center
- Edge-Loc
- Edge-Ring
- Scratch

Dataset source: https://www.kaggle.com/datasets/qingyi/wm811k-wafer-map

The dataset is not included in this repository because of its large size.

## Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- TensorFlow and Keras
- Matplotlib
- Scikit-learn

## Methodology
1. Load and inspect the dataset.
2. Clean the defect labels.
3. Select four defect categories.
4. Resize wafer maps to 32 × 32 pixels.
5. Normalize the images.
6. Split the data into training and testing sets.
7. Train a CNN model.
8. Evaluate the model using accuracy and classification metrics.

## CNN Architecture
- Input: 32 × 32 × 1
- Convolutional layers: 16 and 32 filters
- Max-pooling layers
- Flatten layer
- Dense layer: 64 neurons
- Dropout: 30%
- Output: 4 classes using softmax

## Results
- Sample size: 2,000 wafer maps
- Training samples: 1,600
- Testing samples: 400
- Test accuracy: 78%

Performance may vary depending on data sampling and model settings.

## Limitations
- Only four defect categories are used.
- The experiment uses a small sample of the original dataset.
- Further testing is required before any real-world industrial use.

## Future Improvements
- Include more defect categories.
- Improve the model through hyperparameter tuning.
- Compare CNN with traditional machine learning methods.
- Develop an interface for predicting wafer defects.

## How to Run
1. Open the notebook in Google Colab.
2. Obtain the WM-811K dataset from the source above.
3. Upload the dataset to Google Drive.
4. Update the dataset file path if needed.
5. Run the notebook cells in order.

## Author
Student Machine Learning Mini-Project
