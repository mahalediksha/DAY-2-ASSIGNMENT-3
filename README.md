# DAY-2-ASSIGNMENT-3

Code to check whether a string is pangram

import string 
def pangram(str): 
 alphabets="abcdefghijklmnopqrstuvwxyz"
for char in alphabets:           
  if char not in str.lower():
   return False
return True
string = 'abc def ghi jkl mno pqr stu vwx yz'
if(pangram(string)==True):    
   print("The string is pangram") 
else: 
   print("The string is not pangram")

OUTPUT:
The string is pangram
