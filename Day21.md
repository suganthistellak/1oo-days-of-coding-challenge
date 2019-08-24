## Read two inputs. 
The first input is a digit. 
The second input is a number. 

Is the digit present in the number? If yes, return True.
If no, return False.

```

Example 
INPUT
1
100
OUTPUT
True

INPUT
4
234
OUTPUT
True

INPUT
1
2000
OUTPUT
False

```

digit_c = input()
number_s = input() 

digit_c is the character equivalent of a digit  
number_s is the string equivalent of a number 


#print("METHOD 1 output")
for digit in number_s: 
  if digit == digit_c:
    print(True)
    break
else:
  print(False)
#print("METHOD 2 output")
if digit_c in number_s: 
  print(True)
else:
  print(False )
#print("METHOD 3 output")
print(digit_c in number_s) 






