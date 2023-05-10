# MatrixTricks
Matrix Printing and Randomization
This Java code consists of three methods that can be used to print a matrix and generate a randomized matrix with given dimensions and value range.

printMatrix(int[][] mat)
This method takes in a 2D integer array as its input and prints the array to the console in matrix form, with each element separated by a space. The method iterates through each row of the matrix, and for each row, it iterates through each column and prints out the corresponding element.

randomMatrix(int rows, int colm, int a, int b)
This method takes in four parameters: the number of rows, the number of columns, and the minimum and maximum values for the range of values in the randomized matrix. The method creates a new 2D integer array with the specified dimensions and fills it with randomly generated integer values between a and b, inclusive. The method then returns the generated matrix.

main(String[] args)
This method is the entry point of the program. It prompts the user to enter the number of rows and columns for the matrix and the range of values for the randomized matrix. It then calls the randomMatrix method to generate a new matrix with the given dimensions and range of values, and passes this matrix to the printMatrix method to print it out to the console.

Usage
To use this code, simply compile and run the Java file. The program will prompt the user to enter the desired number of rows and columns for the matrix, as well as the range of values for the randomized matrix. Once these values are entered, the program will generate a new matrix and print it out to the console.
