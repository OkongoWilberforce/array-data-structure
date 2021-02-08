# array-data-structure
array as a type of data stucture
#array is  data objects which can store data in more than two dimensions
#An array is a data structure that can hold multi-dimensional data
#For example, in square matrices can contain two rows and two columns and dimension can take five.
# array() function will create an array which takes a vector, which is the numbers and dimension('dim') in the argument.

#creating vectors

vector1 =  c (5, 10, 15,20)
vector2 =  c (25, 30, 35, 40, 45, 50,55,60)

#creating array

a = array (c (vector1, vector2),dim =c(4,4,3))

print(a)
