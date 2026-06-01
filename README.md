# Machine-Learning-Assignment
Machine Learning - CNN Performance Evaluation System
CNN Performance Evaluation System
Overview
This project investigates how the depth of a Convolutional Neural Network (CNN) affects image classification performance.
Three CNN architectures of increasing depth were designed, trained, and evaluated on the CIFAR-10 dataset:
•	Shallow CNN
•	Medium CNN
•	Deep CNN
The project compares these architectures using training accuracy, training loss, test accuracy, and confusion matrix analysis to determine whether deeper networks improve classification performance and generalization.
________________________________________
Why This Project Is Useful
Choosing the right CNN architecture is an important challenge in deep learning.
This project demonstrates:
•	How CNN depth influences feature learning
•	The difference between training performance and generalization
•	Why higher training accuracy does not always result in better test performance
•	How confusion matrices can be used to analyse classification behaviour
The project can serve as a learning resource for students studying machine learning, deep learning, and computer vision.
________________________________________
Dataset
The project uses the CIFAR-10 dataset.
Dataset Characteristics
•	60,000 colour images
•	10 image classes
•	32 × 32 image resolution
•	50,000 training images
•	10,000 testing images
Classes:
•	Airplane
•	Automobile
•	Bird
•	Cat
•	Deer
•	Dog
•	Frog
•	Horse
•	Ship
•	Truck
________________________________________
Project Results
Test Accuracy Comparison
Model	Test Accuracy (%)
Shallow CNN	72.67
Medium CNN	75.14
Deep CNN	77.57
Key Findings
•	Medium CNN achieved the highest training accuracy (96.49%)
•	Deep CNN achieved the highest test accuracy (77.57%)
•	Deeper architectures improved generalization performance
•	Dropout regularization helped reduce overfitting
•	Higher training accuracy did not necessarily lead to better real-world performance
________________________________________
Getting Started

Clone the Repository
git clone https://github.com/janibshradha24/Machine-Learning-Assignment.git 
cd Machine-Learning-Assignment

Install Dependencies
pip install -r requirements.txt

Run the Notebook
jupyter notebook CNN_Performance_Evaluation.ipynb

Run all cells to reproduce:
•	Model training
•	Training accuracy plots
•	Training loss plots
•	Test accuracy evaluation
•	Confusion matrix analysis
________________________________________
Repository Structure
Machine-Learning-Assignment/ │ ├── README.md ├── LICENSE ├── requirements.txt ├── CNN_Performance_Evaluation.ipynb ├── CNN_Performance_Presentation.pptx ├── Transcript.pdf ├── training_accuracy.png ├── training_loss.png ├── test_accuracy.png └── confusion_matrix.png
________________________________________
Technologies Used
•	Python
•	PyTorch
•	NumPy
•	Pandas
•	Matplotlib
•	Seaborn
•	Scikit-learn
________________________________________
Getting Help
If you have questions about the project or encounter any issues:
•	Review the notebook documentation
•	Consult the PyTorch documentation
•	Open an issue in this GitHub repository
________________________________________
Author
Shradha Janib
University of Hertfordshire
Machine Learning Tutorial Project
________________________________________
Contributing
This repository was created for educational purposes. Suggestions and improvements are welcome through GitHub issues or pull requests.
________________________________________
References
LeCun, Y. et al. (1998). Gradient-Based Learning Applied to Document Recognition.
Krizhevsky, A. et al. (2012). ImageNet Classification with Deep Convolutional Neural Networks.
CIFAR-10 Dataset: https://www.cs.toronto.edu/~kriz/cifar.html
PyTorch Documentation: https://pytorch.org/docs/stable/
________________________________________
License
This project is licensed under the MIT License.
