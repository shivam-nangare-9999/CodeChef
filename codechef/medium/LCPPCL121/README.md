# LCPPCL121

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Factorial of any number

Listen

Write a program that does the following

- Declare an integer variable num and initialise it to a user defined input
- Output to the console the factorial of num Remember to use loops for this problem Factorial of a number n is the product of all the numbers from 1 to n Factorial of a number(n) = n  *(n-1)* ... 2 * 1
### Sample 1:
Input
Output

```
6
```

```
The factorial of the given number is: 720

```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-02T09:36:09.081Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main()
{
    int num;
    cin >> num;

    int factorial = 1;

    for(int i = 1; i <= num; i++)
    {
        factorial = factorial * i;
    }

    cout << "The factorial of the given number is: " << factorial;

    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPCL121)