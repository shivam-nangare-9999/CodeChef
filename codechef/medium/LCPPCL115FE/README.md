# LCPPCL115FE

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-02T09:37:05.453Z  

```c_cpp
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

[View on CodeChef](https://www.codechef.com/problems/LCPPCL115FE)