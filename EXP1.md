# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 19/03/25                                                                         
### REGISTER NUMBER : 212222040047

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

### Do While:
```
def display():
    start=input("Enter a positive value for START: ")
    end=input("Enter a positive value for END: ")
    if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=' ')
            if start<end:
                start+=1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()
```
### While Do:
```
start=input("Enter a positive value for START: ")
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
    start=int(start)
    end=int(end)
    while start<end:
        print(start)
        start+=1
else:
    print("Enter a valid positive number.")
```
### Switch:
```
def switch():
    switcher={0:"even",1:"odd"}
    n=input('Enter a value for N: ')
    try:
        n=int(n)
        print(switcher[n%2])
    except ValueError:
        print("Enter a valid number.")
switch()
```
### If Else:
```
def compare():
    a=input("Enter a value for A: ")
    b=input("Enter a value for B: ")
    try:
        a=int(a)
        b=int(b)
        if a>b:
            print("A is greater than")
        elif a<b:
            print("B is greater than")
        else:
            print("A is equal to B")
    except ValueError:
        print("Enter a valid number.")

compare()
```
### For:
```
def iterate():
    string=input("Enter a string: ") 
    for i in string:
        print(ord(i),end=" ")
iterate() 
```

### Output:

### Do While:
![stl- EX 1 a](https://github.com/user-attachments/assets/bc97b244-f0f2-4192-81fd-d556c4671b9b)

### While Do:
![stl- EX 1 b](https://github.com/user-attachments/assets/a67d28b2-b9c5-4b8e-97bc-d6c616946b1b)

### Switch:
![stl- EX 1 c](https://github.com/user-attachments/assets/95404188-3a25-4b78-8f46-f08f1a21511b)

### If Else:
![stl- EX 1 d](https://github.com/user-attachments/assets/0341749a-e602-4bb2-a63a-5844e863c52b)

### For:
![stl- EX 1 e](https://github.com/user-attachments/assets/90fd592c-1163-48f3-9dbf-1c3b076e1520)





### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


