# Object Detection

## Project Overview
This project involves implementing classifiers and object detection algorithms with a focus on practical applications using the MNIST dataset for handwritten digit classification and YOLOv5 for object detection in custom images.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Project Components](#project-components)
  - [MNIST Classification](#mnist-classification)
  - [YOLO Object Detection](#yolo-object-detection)
- [Installation](#installation)
- [Usage](#usage)

## Technologies Used
- **Python**: Main programming language.
- **NumPy**: For handling large, multi-dimensional arrays and matrices.
- **OpenCV**: Used for image processing operations.
- **Scikit-learn**: For implementing machine learning algorithms.
- **YOLOv5**: Utilized for state-of-the-art object detection.
- **Jupyter Notebook**: For interactive code execution and presentation.

## Project Components

### MNIST Classification
This component involves using Support Vector Machines (SVM) and Random Forest classifiers to identify handwritten digits from the MNIST dataset. The tasks include:
- Data preparation and visualization.
- Training linear and non-linear SVMs.
- Optimizing and evaluating Random Forest classifiers.
- Analyzing classifier performance through accuracy metrics and confusion matrices.

### YOLO Object Detection
Implementation of YOLOv5 for detecting objects in a custom image of a Montreal street scene. Key tasks include:
- Acquiring and preparing images.
- Applying pre-trained YOLOv5 models to detect objects.
- Custom function implementation for drawing bounding boxes and labels.
- Performance analysis based on different detection thresholds.

## Installation
To set up your environment to run these notebooks, install the required libraries using:
```bash
pip install numpy opencv-python scikit-learn torch torchvision notebook
```

## Usage
To run the notebooks in this repository, follow these steps:

Ensure you have Python and Jupyter Notebook installed on your system. If not, you can install them using Anaconda, which simplifies the management of packages and notebooks.

1. Clone the repository to your local machine:
```bash
git clone https://github.com/yourusername/your-repository-name.git
```

2. Navigate to the cloned directory:
```bash
cd your-repository-name
```

3. Install required Python packages:
```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:
```bash
jupyter notebook
```

Open the .ipynb files within the Jupyter Notebook interface in your browser to view and run the individual cells.








