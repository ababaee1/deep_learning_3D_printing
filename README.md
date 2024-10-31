# Using Deep Learning (CNN, ANN) for Flexural Rigidity Prediction in 3D printed Structures 

![image](https://github.com/user-attachments/assets/cdeb9a13-36d7-4021-b989-ab923693d96f)

Neural network models for predicting flexural rigidity of metal 3D printed beams using cross-sectional layer images. Multiple architectures including ANNs and CNNs with/without PCA dimensionality reduction were developed and compared.

## Key Features
- ├── data/
    - │   ├── images/      # Layer image data
  - │   └── test_data/   # Bending test results
- ├── models/          # Model implementations
  - │   ├── ANN_PCA.ipynb
  - │   ├── ANN_single_image.ipynb
  - │   ├── CNN.ipynb
  - │   └── Model_new.ipynb
- └── utils/          # Data preprocessing
  - ├── Getting_DataFrame.ipynb
  - └── Image_combine.ipynb
 

## Dependencies

- Python 3.7+
- TensorFlow 2.x 
- scikit-learn
- numpy
- pandas
- matplotlib
