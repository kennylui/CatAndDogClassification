# CatAndDogClassification
This is a deep learning project using CNN Keras for classifying images of Cats and Dogs.

Dataset
https://www.kaggle.com/competitions/dogs-vs-cats/data
-----
Unzip the dataset file and upload "data" folder to current directory.

Data directory: ./data/

Result
-----
Original
-----
![original-1](https://user-images.githubusercontent.com/35885529/166156331-34eb0ab6-3c57-49b6-8a19-26d07436b0e8.PNG)

Dropout = 0.2
-----
![dropout0 2-1](https://user-images.githubusercontent.com/35885529/166156343-8e5b95ed-3d3c-4b2e-98dd-e7d9eb326b3f.PNG)

Dropuout = 0.5
-----
![dropout0 5-1](https://user-images.githubusercontent.com/35885529/166156306-7f38dc8f-2bd8-4aeb-b9c2-6c90d2dda782.PNG)

Conclusion
-----
Training Accuracy > 0.9

Validation Accuracy > 0.75

Training Loss < 0.21

Validation Accuracy < 0.6 (Unstable)

Added dropout property improved result in validation accuracy and validation loss.

Through testing, dropout = 0.5 is best in this model.

Validation accuracy increases as training increases throughout training.

Validation loss decreases as training loss decreases through training.
