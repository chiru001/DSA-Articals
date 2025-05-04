---
title: "DSA-Introduction: Part 5"
datePublished: Sun May 04 2025 12:18:52 GMT+0000 (Coordinated Universal Time)
cuid: cma9mbtsz000308ld0zenbqix
slug: dsa-introduction-part-5
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/BfrQnKBulYQ/upload/3dc036762f0842fe7dd76f4082593aac.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1746361120930/74513870-2ef7-488a-9b36-f915d2d9d2c6.jpeg
tags: chai, chaiaurcode, chaicode, chaicohort, chai-code, chaiaurcpp

---

Let’s start with an example of constant time complexity

**C++ Code Example: Constant Time**

```cpp
#include <iostream>
using namespace std;

int main() {
    int x, y, z;         // Step 1: Variable declaration
    z = x + y;           // Step 2: Addition operation
    cout << z << endl;   // Step 3: Output the result
    return 0;            // Step 4: Exit the program
}
```

---

### **Assumption:**

> Let’s assume each operation takes **1 second**.

| Line of Code | Description | Time Taken |
| --- | --- | --- |
| `int x, y, z;` | Declaring 3 variables | 3 sec |
| `z = x + y;` | Adding `x` and `y`, storing in `z` | 2 sec |
| `cout << z;` | Printing result | 1 sec |
| `return 0;` | Exiting program | 1 sec |
| **Total** |  | **7 sec** |

---

### **Why is this Constant Time (O(1))?**

* This program always takes the **same number of steps**, no matter what values `x` and `y` are.
    
* Whether `x = 1` or `x = 1000000`, the number of operations doesn't change.
    

So its **time complexity is constant**:

> **O(1), Ω(1), Θ(1)**

---

### For Beginners:

Think of it like this:

If you go to a vending machine and press a button, it **always gives you the item in 1 step**, no matter how big or small the snack is.

That’s **constant time** — always the same effort.

## Constant Time Example 2

## **C++ Code**

```cpp
int main()
{
    int a, b, c, d, e, f;        // Variable declarations
    a = b + c + d;               // 2 additions + 1 assignment
    f = 2 * a - c * d;           // 2 multiplications + 1 subtraction + 1 assignment
    cout << a << b << c;        // Printing 3 variables
    return 0;                    // Exit
}
```

---

### **Updated Time Complexity Table**

| Line of Code | Explanation | Time Taken |
| --- | --- | --- |
| `int a, b, c, d, e, f;` | Declare 6 variables | 6 sec |
| `a = b + c + d;` | 2 additions + 1 assignment | 3 sec |
| `f = 2 * a - c * d;` | 2 multiplications + 1 subtraction + 1 assignment | 4 sec |
| `cout << a << b << c;` | Print 3 variables | 3 sec |
| `return 0;` | Exit the program | 1 sec |
| **Total Time** |  | **17 sec** |

---

### **Time Complexity**

* Regardless of how large the variables are, the number of operations stays the same.
    
* So this program still has:  
    **O(1)** – Constant Time  
    **Ω(1)** – Best Case  
    **Θ(1)** – Average Case
    

---

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1746360962179/fd674faf-1461-46fb-b46d-6f4ba88f29a4.png align="center")

**Missed the earlier parts?**  
Make sure to check out the previous posts in this series for a complete understanding of time complexity and algorithm analysis:

* 🔗 [**DSA Introduction – Part 1**](https://hashnode.com/post/cma9jk346000109js0hjs1asn)
    
* 🔗 [**DSA Introduction – Part 2**](https://hashnode.com/post/cma9julja000s08l79cy8cp0i)
    
* [🔗 **DSA Introduction – Part 3**](https://hashnode.com/post/cma9koi9f000109lefmpb3mbg)
    
* [🔗 **DSA Introduction – Part 4**](https://hashnode.com/post/cma9llwhm000908i90axfe77y)
    
* [🔗 **DSA Introduction – Part 5**](https://hashnode.com/post/cma9mbtsz000308ld0zenbqix)
    
* [🔗 **DSA Introduction – Part 6**](https://hashnode.com/post/cma9o234e000g09l5fmd45z7i)