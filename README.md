#### Task
<p>Given an integer, n, perform the following conditional actions:
<ul>
  <li>If n is odd, print Weird
  <li>If n is even and in the inclusive range of 2 to 5, print Not Weird
  <li>If n is even and in the inclusive range of 6 to 20, print Weird
  <li>If n is even and greater than 20, print Not Weird
    
#### Input Format
<p>A single line containing a positive integer, n.
  
#### Constraints
<li>1<=n<=100
  
#### Output Format
<p>Print Weird if the number is weird. Otherwise, print Not Weird.
  
#### Sample Input 0
  `3 `
#### Sample Output 0
  `Weird`
#### Explanation 0
  n = 3 <br>
  n is odd and odd numbers are weird, so print Weird.
#### Sample Input 1
  `24 `
#### Sample Output 1
  `Not Weird`
#### Explanation 1
  n = 24<br>
  n > 20 and n is even, so it is not weird.

-------------------------------------------------
  # Solution
-------------------------------------------------
  
#!/bin/python3<br><br>
import math<br>
import os<br>
import random<br>
import re<br>
import sys<br><br>
if __name__ == '__main__':<br>
  n = int(input().strip())
  
``` 
if n%2 != 0:
      print("Weird")
    else :
      if(n>=2 and n<=5):
          print("Not Weird")
      elif(n>=6 and n<=20):
          print("Weird")
      elif(n>20):
          print("Not Weird")
```

