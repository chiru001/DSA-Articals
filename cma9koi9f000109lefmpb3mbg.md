---
title: "DSA-Introduction: Part 3"
seoTitle: "Understanding Time Complexity: Linear, Quadratic & Cubic"
seoDescription: "earn how different types of time complexity O(n), O(n²), and O(n³) affect your program's performance. Simple examples, real-life analogies, and graphs make"
datePublished: Sun May 04 2025 11:32:44 GMT+0000 (Coordinated Universal Time)
cuid: cma9koi9f000109lefmpb3mbg
slug: dsa-introduction-part-3
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/ieic5Tq8YMk/upload/1f615888ce74a76d2ec0bbaa118bfd17.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1746358085371/42b58b41-9cb8-4e1c-b02e-7271b581e1fb.jpeg
tags: chaiaurcode, chaicode, chaiaurcpp, chaiaurdsa

---

## From Linear to Quadratic Time Complexity

#### Quadratic Equation Example:

Let’s take this equation:

> **f(n) = 2n² + 3n - 5**

Now plug in a large value, like **n = 3000**:

> **f(3000) = 2(3000)² + 3(3000) - 5**  
> **f(3000) = 18,000,000 + 9000 - 5 = 18,008,995**

As you can see, the **2n²** part gives us **18 million**, while the **3n** and **\-5** are tiny in comparison.

---

### What Does This Mean?

In quadratic equations, as `n` grows larger, the **n² term dominates** the growth. So we **focus on n²** and ignore the rest when analyzing time complexity.

> So, **f(n) = 2n² + 3n - 5** simplifies to **O(n²)**

---

### Real-Life Example (Quadratic):

Imagine you’re planning seating for a party.  
You want to pair every guest with every other guest for a handshake.

* If you have 10 guests, the number of handshakes is close to **n²**.
    
* If you double the guests to 20, the number of handshakes doesn’t just double it **quadruples**!
    

This is what **quadratic growth** feels like it increases rapidly with `n`.

---

### Now Let’s Look at a **Cubic Equation**

> **f(n) = an³ + bn² + cn + d**

Example:

> **f(n) = 2n³ + 5n² + 4n + 10**

---

### What’s the Most Dominant Term?

You're right if you said:

> **n³ is the most dominant** term when `n` is large.

So we ignore the smaller parts and focus only on the term with the **highest power**.

> So, **f(n) ≈ O(n³)**

---

### Real-Life Example (Cubic):

Imagine you have a 3D box made of cubes.  
If each side is `n` cubes long, then the total number of small cubes inside is **n × n × n = n³**.

* If `n = 10` → you have 1,000 cubes
    
* If `n = 100` → you have 1,000,000 cubes!
    

The growth explodes — that’s cubic complexity.

---

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1746358850432/c2d82db1-968e-44d6-9837-518b3de67c7d.png align="center")

**Missed the earlier parts?**  
Make sure to check out the previous posts in this series for a complete understanding of time complexity and algorithm analysis:

* 🔗 [**DSA Introduction – Part 1**](https://hashnode.com/post/cma9jk346000109js0hjs1asn)
    
* 🔗 [**DSA Introduction – Part 2**](https://hashnode.com/post/cma9julja000s08l79cy8cp0i)