Project Title: A Study on Dog Breed Classification: Transfer Learning vs. CNN
Description
This project explores the effectiveness of transfer learning compared to a conventional Convolutional Neural Network (CNN) in classifying dog breeds. Utilizing the Stanford Dogs dataset, the study compares the performance of a model created from scratch against a transfer learning model using MobileNetV2.

Key Features
Transfer Learning Model: Employs MobileNetV2, pre-trained on ImageNet.
Custom CNN Model: A CNN developed from scratch specifically for dog breed classification.
Data Augmentation: Techniques to enhance model robustness including rotating, flipping, and zooming.
Performance Metrics: Accuracy, precision, recall, and F1 score are used to measure model performance.
Dataset
Stanford Dogs Dataset: Consists of approximately 20,000 images spread across numerous dog breeds. Available for download here.
Technologies Used
TensorFlow
Keras
Python
Installation
Clone this repository:

bash
Copy code
git clone https://github.com/your-username/your-repository.git
Install required packages:

Copy code
pip install -r requirements.txt
Usage
Run the main script to train the models:

Copy code
python train_models.py
Results
The transfer learning model outperformed the CNN built from scratch in terms of accuracy and computational efficiency. The detailed performance comparison is documented in the project report.

Contributing
Contributions, issues, and feature requests are welcome. Feel free to check issues page if you want to contribute.

License
Distributed under the MIT License. See LICENSE for more information.

Authors
Tharun Reddy Pyayala
Pavan Kumar Kalisetty
Mythresh Neerugattu
Acknowledgements
Professor Khalid Kattan for guidance and project oversight.
References and resources utilized are listed in the detailed project documentation.
