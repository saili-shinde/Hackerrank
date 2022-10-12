# Hackerrank solutions
## Python code solution
### Say "Hello, World!" With Python
Here is a sample line of code that can be executed in Python:
```
print("Hello, World!")
```
You can just as easily store a string as a variable and then print it to stdout:
```
my_string = "Hello, World!"
print(my_string)
```
The above code will print Hello, World! on your screen. Try it yourself in the editor below!

**Input Format**

You do not need to read any input in this challenge.

**Output Format**

Print Hello, World! to stdout.

**Sample Output 0**
```
Hello, World!
```
***code***
```
print("Hello, World!")



```

### Python If-Else
**Task**
Given an integer,`n`,perform the following conditional actions:

If`n`is odd, print Weird
If`n`is even and in the inclusive range of  to`2`,`5` print Not Weird
If`n`is even and in the inclusive range of  to`6`,`20`print Weird
If`n`is even and greater than`20`, print Not Weird

**Input Format**

A single line containing a positive integer,`n`.

**Constraints**

`1<=n<=100`

**Output Format**

Print Weird if the number is weird. Otherwise, print Not Weird.

**Sample Input 0**
```
3
```
**Sample Output 0**
```
Weird
```
**Explanation 0**

`n=3`
 `n`is odd and odd numbers are weird, so print Weird.
**Sample Input 1**
```
24
```
**Sample Output 1**
```
Not Weird
```
**Explanation 1**

`n=24`

`n>20`and`n` is even, so it is not weird.

***code***
```
import math
import os
import random
import re
import sys



if __name__ == '__main__':
    n = int(raw_input().strip())
if n%2!=0:
    print('Weird')
elif n%2==0 and 2<=n<=5:
    print('Not Weird')
elif n%2==0 and 6<=n<=20:
    print('Weird')
elif n%2==0 and n>20:
    print('Not Weird')



```
