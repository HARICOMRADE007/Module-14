# Exp.No:14d 
## Deque - DELETION

---

### AIM  
To write a Python program to delete elements at FRONT END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Create an empty deque.  
3. Define how many elements to input (e.g., 3 inputs as in the example).  
4. Loop through the range of input size:  
   - Read an integer from the user.  
   - Append the integer to the deque.  
5. Remove the front element of the deque using `popleft()`.  
6. Print the final deque after deletion.  

---

### PROGRAM  

```
#Reg.No: 212222060074
#Name: Hariharan K
#Add Your Code Here
import collections
a=int(input())
b=int(input())
c=int(input())
de=collections.deque([a,b,c])
de.popleft()
print("The deque after deleting is :")
print(de)
```

### OUTPUT
<img width="1184" height="328" alt="image" src="https://github.com/user-attachments/assets/d7a92d88-ce4b-4337-9194-a089e1befb7f" />


### RESULT
Therefore, the output is the example to write a Python program to delete elements at FRONT END of deque using a collection built-in function.
