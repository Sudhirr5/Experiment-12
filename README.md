# Experiment-12 : Pytest – Python program for Addition
### Name : SUDHIR KUMAR. R
### Reg No. : 212223230221

## Aim:
To write a Python program using **Pytest** for testing the addition of two numbers.

## Algorithm:
1. Start the program.
2. Define a function `add(a, b)` inside **EX12.py** that returns the sum of two numbers.
3. Create a separate test file **TEST\_EX12.py**.
4. Import the `add` function from **EX12.py** into the test file.
5. Write test cases using `assert` statements to check correctness.
6. Run the test using: (-s for stdout to get to display the print statements)

   ```bash
   ppytest -s TEST_EX12.py
   ```
7. If all tests pass, the program is correct.

## Program:

**EX12.py**
```python
def add(a, b):
    return a + b
```

**TEST\_EX12.py**
```python
from EX12 import add

def test_addition():
    
    print()
    
    print("add(2, 3) =", add(2, 3))      
    assert add(2, 3) == 5

    print("add(-1, 1) =", add(-1, 1))     
    assert add(-1, 1) == 0

    print("add(0, 0) =", add(0, 0))     
    assert add(0, 0) == 0

    print("add(10, -5) =", add(10, -5))   
    assert add(10, -5) == 5

```

### Output:

<img width="1073" height="297" alt="image" src="https://github.com/user-attachments/assets/ddafe054-0503-4dab-b13d-8a3507bd06f5" />

### Result:
Thus, the **Pytest program for Addition (EX12 & TEST\_EX12)** was successfully written, executed, and tested. ✅
