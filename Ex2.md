# Ex.No:2  
# Ex.Name: Function Overloading – Sum of Two and Three Integers  

## Date:  

## Aim:  
To write a C++ program that overloads a function to perform:  
- Sum of two integers  
- Sum of three integers  

## Algorithm:  
1. Start the program.  
2. Create a class `Sum` that contains overloaded functions:  
   - `int add(int a, int b)` to return sum of two integers.  
   - `int add(int a, int b, int c)` to return sum of three integers.  
3. In the `main()` function:  
   - Read integers from the user.  
   - Call the overloaded functions accordingly.  
   - Display results.  
4. Stop the program.  

## Program:
```cpp
#include <iostream>
using namespace std;

class Sum {
public:
    int add(int a, int b) {
        return a + b;
    }
    int add(int a, int b, int c) {
        return a + b + c;
    }
};

int main() {
    int a, b, c;
    cin >> a >> b >> c;

    Sum s;
    cout << "Sum of two Numbers=" << s.add(a, b) << endl;
    cout << "Sum of three Numbers=" << s.add(a, b, c) << endl;

    return 0;
}
```

## Output:
```
Input:
10 20 30

Output:
Sum of two Numbers=30
Sum of three Numbers=60
```
## Result:
<img width="868" height="508" alt="image" src="https://github.com/user-attachments/assets/d360a256-1f28-4838-8d75-48465d40abdc" />

