"""
This function takes in a matrix with a vector, and for each element in one row multiplies by each number in the vector and then adds them together. This is repeated for every row in the matrix. Function returns a new vector. 
"""
def matVec(matrix, vector):
  new_x = []
  for i in range(len(matrix)):
    product = 0
    for j in range(len(vector)):
      total += matrix[i][j] * vector[j]
     new_x.append(product)
  return new_x
  
  testmatrix01 = [[1,2,3], [3,4,5], [5,6,7]]
  testvector01 = [1,2,3]
      
  
