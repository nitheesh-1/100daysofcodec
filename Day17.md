##JugsMugsPugs LITE
Write a program that receives a number on the input.
  - If the number is a multiple of 3, it prints "Jugs". 
  - If the number is a multiple of 5, it prints "Mugs".
  - If the number is a multiple of 7, it prints "Pugs".

  - If the number is a multiple of both 3 and 5, it prints "JugsMugs".
  - If the number is a multiple of both 3 and 7, it prints "JugsPugs".
  - If the number is a multiple of both 5 and 7, it prints "MugsPugs".
  - If the number is a multiple of both 3, 5 and 7, it prints "JugsMugsPugs".
Otherwise, it prints the number.

LITE REQUIREMENT:
Limit your code to use only if statements and not to exceed 4 of them. 
You are a real winner if you can achieve it using not more than 3 if statements.

GO FOR IT! 

-----
While you are it, try and see if you can use only one print statement. 


```
INPUT 
15

OUTPUT
JugsMugs

INPUT 
21

OUTPUT
JugsPugs
INPUT 
105

OUTPUT 
JugsMugsPugs
```

num = int(input())
ans = ""
if num % 3 == 0:
  ans+="Jugs"
if num % 5 == 0:
  ans+="Mugs"
if num % 7 == 0:
  ans+="Pugs"
print(ans or num)
