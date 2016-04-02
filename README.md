#Circular Convolution Program in C

#OUTPUT OF PROGRAM :


Enter the length of the first matrix : 3
.tab{padding-left: 5px}
Enter the elements of the first matrix : 12<br>
10<br>
20<br>
<br>
<br>
Enter the length of the Second matrix : 5<br>
<br>
Enter the elements of the first matrix : 10<br>
5<br>
8<br>
7<br>
6<br>

 First matrix before padding:<br>
[ 12    10      20      ]<br>
<br>
 Second matrix before padding:<br>
[ 10    5       8       7       6       ]<br>
<br>
 Both the Matrix After padding :<br>
        1st Matrix  : [12, 10, 20, 0, 0]<br>
        2nd Matrix  : [10, 5, 8, 7, 6] <br>
    
 ******* Final Matrix *****<br>
      |  10       6        7        8        5    |<br>
      |  5        10       6        7        8    |<br>
      |  8        5        10       6        7    |<br>
      |  7        8        5        10       6    |<br>
      |  6        7        8        5        10   |<br>
<br>
 ******* Circular Convulated Matrix *****<br><br>
[ 320   280     346     264     302     ]<br>
