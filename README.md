# Age and Gender Detection using Computer Vision
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

![Age and Gender Detection](images/demo.png)

This project demonstrates an age and gender detection system using computer vision techniques. The goal of this project is to accurately predict the age and gender of individuals from images or video streams. The system utilizes pre-trained deep learning models to perform these predictions and offers a simple and intuitive interface for users to interact with.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Results](#results)
- [Contributions](#contributions)
- [License](#license)

## Introduction

Age and gender detection is a significant application of computer vision that has various practical applications, ranging from targeted marketing to security systems. This project aims to showcase the capabilities of deep learning models in accurately estimating the age and gender of individuals based on their facial features.

The project employs a convolutional neural network (CNN) architecture that has been pre-trained on a large dataset of faces to learn relevant features for age and gender estimation. The trained model can then be used to predict the age and gender of new faces.

## Installation

1. Clone this repository to your local machine using:
   ```
   git clone https://github.com/yourusername/age-gender-detection.git
   ```

2. Navigate to the project directory:
   ```
   cd age-gender-detection
   ```

3. Install the required dependencies using:
   ```
   pip install -r requirements.txt
   ```

4. Download the pre-trained model weights from [here](link_to_model_weights) and place them in the `models` directory.

## Usage

1. Place the images you want to analyze in the `input_images` directory.

2. Run the age and gender detection script:
   ```
   python detect.py
   ```

3. The script will process the images, perform age and gender predictions, and save the annotated images in the `output_images` directory.

## Models

The project employs a pre-trained deep learning model for age and gender detection. The specific architecture used is a modified version of the ResNet-50 model, fine-tuned on a dataset of facial images.

The model's architecture and weights are saved in the `models` directory. You can find more details about the model architecture in the `model_architecture.ipynb` notebook.

## Results

The accuracy of the age and gender predictions may vary depending on the quality of input images and the diversity of the dataset used for training. In general, the model provides reasonable estimations and is suitable for various applications.

Sample results can be found in the `output_images` directory.

## Contributions

Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this README file to match your project structure, details, and preferences. Make sure to include relevant information about how to use the project, the underlying models, and any acknowledgments for external resources used.
https://user-images.githubusercontent.com/78723011/194758842-b96f93a7-c38a-411a-888f-83e00fd5b54e.mp4
