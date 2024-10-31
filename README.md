# Using Deep Learning (CNN, ANN) for Flexural Rigidity Prediction in 3D printed Structures 
<p align="center">
  <img src="https://github.com/user-attachments/assets/03c70c79-6f06-4a76-96f9-e06d5dad3d86" width="40%" />
  <img src="https://github.com/user-attachments/assets/50ad45fe-8ee4-49d4-b0e0-c04d5ea2cd5a" width="42%" />
  <img src="https://github.com/user-attachments/assets/d5998544-a1a4-4399-9284-11778c3100b7" width="80%" />
</p>

 
**Neural network models for predicting flexural rigidity of metal 3D printed porous gyroid beams using cross-sectional layer images. Multiple architectures including ANNs and CNNs with/without PCA dimensionality reduction were developed and compared.**

## Key Features
- ├── data/
    - │   ├── images.zip/      # Layer image data
  - │   └── test_data.csv/   # Bending test results
- ├── models/          # Model implementations
  - │   ├── ANN_PCA.ipynb
  - │   ├── ANN_single_image.ipynb
  - │   ├── CNN.ipynb
  - │   └── Model.ipynb
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
