# EX.No:6(D) Python OOP: Operator Overloading (Less Than `<`)

## AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.



## ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.



## Program
![image](https://github.com/user-attachments/assets/a03bddcf-26cd-4487-b68c-aaf5c5c66f39)

## Output
![image](https://github.com/user-attachments/assets/a5edef74-74d0-4fed-a2a0-c59995451eaf)

## Result
Thus, the program has been successfully executed.
