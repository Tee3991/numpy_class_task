# numpy_class_task
##Create a 5 x 5 ndarray X with consecutive integers from 1 to 25 (inclusive).
#Afterwards use Boolean indexing to pick out only the odd numbers in the array and assign the result to Y

import numpy as np


x=np.arange(1,26).reshape(5,5)

Y= print(x[x%2 !=0])

