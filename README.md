# bash-matrices
various matrix manipulations in a bash script
Run this as a bash script in the same directory with one or more text files containing a matrix.

The script can print out the dimensions of a matrix by typing "matrix dims filename" where filename is the name of a file containing
a matrix of tab delimited numbers.

The script can transpose an M x N matrix into an N x M matrix by reflecting along the matrix's main diagonal leaving the values along 
the main diagonal unchanged. To invoke this type "matrix transpose filename" where filename is the name of a file containing
a matrix of tab delimited numbers.

The script can display a row vector mean of the input matrix where each element in the row represents the mean value of the correspsonding
column from the input matrix. To invoke this type "matrix mean filename" where filename is the name of a file containing
a matrix of tab delimited numbers.

The script can add two matrices together pair-wise by taking two M x N matrices and adding their elements together such that the
the resulting M x N matrix has elements where the row and column position is the sum of the elements in that position in the two 
summand matrices. Returns an error if the summand matrices are of different dimensions. To invoke this type "matrix add file1 file2" 
where file1 and file2 are the names of files containing a matrix of tab delimited numbers.

The script can multiply an M x N matrix with an N x P matrix to produce an M x P matrix. If dimensions are incorrect it returns an
error. To invoke this type "matrix multiply file1 file2" where file1 and file2 are the names of files containing a matrix of tab delimited 
numbers.
