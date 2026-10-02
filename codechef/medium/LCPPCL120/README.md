# LCPPCL120

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Printing numbers 10 - 24

Listen

### Task

Write a program to print numbers from $10$ to $24$ in the increments of $2$ on separate lines using a for loop.

 **Output:** 

```
10
12
14
16
18
20
22
24

```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-02T09:32:49.504Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    for(int i = 10; i <= 24; i = i + 2)
    {
        cout << i << endl;
    }
}
```

---

[View on CodeChef](https://www.codechef.com/problems/LCPPCL120)