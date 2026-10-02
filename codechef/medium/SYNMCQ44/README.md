# SYNMCQ44

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Multiple Choice Question

How many times will "C++" be printed by this code?

```
#include <iostream>
using namespace std;

int main() {

  for (int i = 0 ; i <= 5 ; i = i + 2) {
    cout << "C++"<< endl;
  }
  
}

```

## Solution

**Language:** C++  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-02T09:38:39.626Z  

```cpp
#include <bits/stdc++.h>
using namespace std;

int main()
{
    int n;
    cin >> n;

    int arr[n];

    // Taking array input
    for(int i = 0; i < n; i++)
    {
        cin >> arr[i];
    }

    // Printing array in reverse
    for(int i = n - 1; i >= 0; i--)
    {
        cout << arr[i] << " ";
    }

    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/SYNMCQ44)