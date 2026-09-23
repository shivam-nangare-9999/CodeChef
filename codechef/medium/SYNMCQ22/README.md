# SYNMCQ22

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Multiple Choice Question

What will be the output of this code, if the a = 5 and b = 9 based on user input?

```
#include <bits/stdc++.h>
using namespace std;

int main() 
{
    int a, b;
    cin >> a >> b;
    cout << a << b << a + b;
    
    return 0;
}

```

## Solution

**Language:** C++  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-23T15:56:58.964Z  

```cpp
#include <iostream>
using namespace std;

int main() {

  int a, b;
  int sum;
  int diff;
  cin >> a;
  cin >> b;
  sum = a + b;
  diff = a - b;
  cout << "Sum is: " << sum << endl;     //dont forget to print diff on a separate line
  cout << "Difference is: "<< diff;

  
}

```

---

[View on CodeChef](https://www.codechef.com/problems/SYNMCQ22)