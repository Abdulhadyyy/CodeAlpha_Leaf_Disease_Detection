# Leaf Disease Detection using CNN Algorithm

This project demonstrates **image classification** using:
- A **custom Convolutional Neural Network (CNN)** built from scratch.
- **VGG16 Transfer Learning** model fine-tuned on our dataset.

## Dataset
The dataset should be organized into subfolders, where each folder corresponds to a category:
Dataset/
├── Brownspot/
├── Healthy/
├── Leafblast/
└── Leafblight/

Images are automatically resized to **64×64 pixels** during preprocessing.

## Features
- **CNN Model**
- **VGG16 Transfer Learning**
- Data Augmentation with `ImageDataGenerator`
- Visualization of **training accuracy and loss**
- Model persistence (saving and loading)
- Image prediction for unseen samples

## Performance
| Model                  | Training Accuracy |
|------------------------|-------------------|
| Custom CNN             | **92%**           |
| VGG16 (Transfer Learn) | **72%**           |

## Requirements
keras==2.3.1
tensorflow==1.14.0
numpy==1.19.2
matplotlib==3.1.1
pillow==9.5.0

Install dependencies with:
``` bash pip install -r requirements.txt ```

## Usage
1. Clone the repository:
git clone https://github.com/mayuriagashe1111/CodeAlpha_LeafDiseaseDetection.git

2. Place your dataset in the Dataset/ directory.
3. Run the Jupyter Notebook:
jupyter notebook
4. Train the models and test predictions.

## Results
CNN performed better for this dataset due to its smaller size and simplicity.
VGG16 still provides strong generalization, but may need more data to match CNN accuracy.

## Contact
For questions or contributions, feel free to create an issue or pull request.




