# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 212222040095

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
```
1.do..While:
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")
    
    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        
        while True:
            print(start, end=' ')
            if start < end:
                start += 1
            else:
                break
    else:
        print("Please enter valid positive numbers.")

display()
```
2.while..do:
```
start = input("Enter a positive value for START: ")
end = input("Enter a positive value for END: ")

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)
    
    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")
```
3.switch:
```
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }
    
    n = input('Enter a value for N: ')
    
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()
```
4.if..else:
```
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    
    try:
        a = int(a)
        b = int(b)
        
        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    
    except ValueError:
        print("Enter a valid number.")
        
compare()
```
5.for:
```
def iterate():
    string = input("Enter a string: ")
    for i in string:
        print(ord(i), end=" ")

iterate()
```
### Output:
![1](https://github.com/user-attachments/assets/6c8d2485-2c87-4df4-ae51-57986a7a98c7)
![2](https://github.com/user-attachments/assets/47f82d26-4123-490b-bb9a-8328a81707bd)
![3](https://github.com/user-attachments/assets/8298f40b-a848-4057-b073-b07cab799363)
![4](https://github.com/user-attachments/assets/8f37ceb7-e677-4a07-820d-5d30eb1dc3be)
![5](https://github.com/user-attachments/assets/5d563411-24ad-4154-8efc-f0bc0752cbc0)

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


