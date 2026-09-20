# LCPP30

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

Declare a variable  **"temperature"**  and initialize it with a value of 25.5 (in Celsius) and print it in Celsius and Kelvin (add 273 to the temperature in Celsius).

[ **Note:**  Print the output in exactly the same format as given below. There is single space around hyphen(-)]

### Output Format

Celsius - 25.5
Kelvin - 298.5

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-20T05:33:26.011Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
	// your code goes here
     double temprature = 25.5;
     double kelvin = temprature + 273;
     cout<<"Celsius - "<< temprature << endl;
     cout<<"kelvin - "<<temprature + 273<<endl;
}

```

---

[View on CodeChef](https://www.codechef.com/problems/LCPP30)