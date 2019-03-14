# datasciencePython
from sklearn import datasets
from sklearn import svm
import matplotlib.pyplot as plt
# load all data into digits
digits = datasets.load_digits()

# print loaded data
print(digits.data())

# print the last value
print(digits.target)

# print the images code
print(digits.images[0])

# print fifth letter of string i.e 4th position
fifth_letter = "MONTY"[4]
print fifth_letter
