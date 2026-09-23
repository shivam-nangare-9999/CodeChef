# SYNMCQ23

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Multiple Choice Question

What will be the output of this code, if the user enters 5 and 9?

```
#include <bits/stdc++.h>
using namespace std;

int main() {
  int a, b;
  cin >> a >> b; 
  int c = a + 2;
  int d = c + b;
  cout << d;
}

```

## Solution

**Language:** C++  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-23T15:57:38.933Z  

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

[View on CodeChef](https://www.codechef.com/problems/SYNMCQ23)