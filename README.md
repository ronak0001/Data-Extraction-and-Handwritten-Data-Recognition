# Data-Extraction-and-Handwritten-Data-Recognition

The idea is mainly focused on extraction of textual data from any pdf or image. A separate neural network for handwritten data recognition is created which is trained on open source EMIST dataset. Primary purpose is to get data from filled application forms and to automate whole process of data processing. OpenCV, Tesseract-OCR and CNN are used to carry out the same analogy.

DataExtraction.ipynb code takes image as an input and extracts textual data using Tesseract-OCR. Textual data in given image is detected with the help of OpenCV. In the end, recognized data is printed as the output which can be stored in a dictionary of a text file or any other way.

A neural network is trained on open source databse EMNIST in HandwrittenRecognition.ipynb to recognise handwritten textual data. After traning and validation, we got approx 86% of accuracy on training data and 87.6% of accuracy over validation set.

As a future scope, both the modules can be integrated to create a system which can extracts data from application forms which might be filled by handwritten as well as printed text data. Furthermore, neural network can be trained on local language data to interpret and recognise local language data and convert it to common language which can make communication process easier and robust.
