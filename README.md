# Handwritten-Digit-Classification-using-SVM

# Data-set
[MNIST database (Modified National Institute of Standards and Technology database)](https://www.kaggle.com/oddrationale/mnist-in-csv/home)

# Abstract
Handwritten digits classification means recognizing the digits from a series of handwritten
digits from sources like papers, photos, emails, and receipts using artificial intelligence.
This problem is well-researched and has various applications, especially in the banks, for
recognizing digits on cheques, traffic monitoring for identifying the number on the plates
of vehicles, and data entry from the handwritten forms.
Handwritten digit recognition is a standard paradigm in the field of pattern recognition where handwritten digits, a multi class classification problem is to classify among ten classes, i.e., 0-10. The project proposes
to use a support vector machine (SVM) model to classify the recognized digits.

# Accuracy on Train.csv
## Linear Kernel
Accuracy : 92.058%
## Non-Linear Kernel : poly 
Accuracy : 95.091%
## Non-Linear Kernel : rbf
Accuracy : 96.225%


# Accuracy on Test.csv
We use rbf kernel on the Test Sample of 10,000 images. 
Accuracy : 96%

## Predicted Outputs on Test Data
![Handwritten Digit Image and Corresponding Output](https://github.com/visheshkl/Handwritten-Digit-Classification-using-SVM/blob/main/output.png)
