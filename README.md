#Circular Convolution Program in C

#OUTPUT OF PROGRAM :


Enter the length of the first matrix : 3

Enter the elements of the first matrix : 12
10
20


Enter the length of the Second matrix : 5

Enter the elements of the first matrix : 10
5
8
7
6

 First matrix before padding:
[ 12    10      20      ]

 Second matrix before padding:
[ 10    5       8       7       6       ]

 Both the Matrix After padding :
        1st Matrix       2nd Matrix
             12              10
             10              5
             20              8
             0               7
             0               6

 ******* Final Matrix *****
        10      6       7       8       5
        5       10      6       7       8
        8       5       10      6       7
        7       8       5       10      6
        6       7       8       5       10

 ******* Circular Convulated Matrix *****

[ 320   280     346     264     302     ]
