---
title: "DSA-Introduction: Part 2"
datePublished: Sun May 04 2025 11:09:29 GMT+0000 (Coordinated Universal Time)
cuid: cma9julja000s08l79cy8cp0i
slug: dsa-introduction-part-2
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/BQLw0OrA6F4/upload/247126d39d43bf55bfb909f805ff45f3.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1746356961169/0bef300c-2a2c-40c6-a76d-e08c528613cc.jpeg
tags: chaiaurcode, chaicode

---

### Understanding Linear Equations in Time Complexity

Let’s start with a simple **linear equation**:

> **f(n) = an + b**  
> Example: **f(n) = 3n + 5**

Now, let’s see what happens when we plug in small values of `n`:

* If **n = 1**:  
    **f(1) = 3(1) + 5 = 8**
    
* If **n = 2**:  
    **f(2) = 3(2) + 5 = 11**
    

So the difference between `f(1)` and `f(2)` is **3** — not a huge jump.

---

Now let’s try with **larger values of n**:

* **f(100) = 3(100) + 5 = 305**
    
* **f(1000) = 3(1000) + 5 = 3005**
    
* **f(3000) = 3(3000) + 5 = 9005**
    

As you can see, when `n` becomes large, the **+5** becomes almost unnoticeable.

---

### So What Does This Mean?

In time complexity, we focus on how fast things grow.  
When `n` (input size) becomes very large:

> We **ignore constants** like `a` and `b`.

So instead of writing:

> **f(n) = 3n + 5**

We just focus on:

> **f(n) ≈ n** (because 3 and 5 don't make a big difference when `n` is very large)

---

### Real-Life Example:

Imagine I give you **₹3005**, and you’re supposed to return it.  
But you only have **₹3000** right now. I’ll probably say:

> “It’s fine, forget the ₹5 — just give me ₹3000.”

That ₹5 becomes **insignificant** when compared to a big amount like ₹3000.

---

### In Summary:

* For small inputs, constants matter.
    
* But when input size is large, we ignore constants in time complexity.
    
* So, **f(n) = 3n + 5** simplifies to **O(n)** in Big-O notation.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1746358943491/d8c198e6-3303-4ebe-8d2a-7afa24ee4093.png align="center")

**Missed the earlier parts?**  
Make sure to check out the previous posts in this series for a complete understanding of time complexity and algorithm analysis:

* 🔗 [**DSA Introduction – Part 1**](https://hashnode.com/post/cma9jk346000109js0hjs1asn)
    
* 🔗 [**DSA Introduction – Part 2**](https://hashnode.com/post/cma9julja000s08l79cy8cp0i)
    
* [🔗 **DSA Introduction – Part 3**](https://hashnode.com/post/cma9koi9f000109lefmpb3mbg)
    
* [🔗 **DSA Introduction – Part 4**](https://hashnode.com/post/cma9llwhm000908i90axfe77y)
    
* [🔗 **DSA Introduction – Part 5**](https://hashnode.com/post/cma9mbtsz000308ld0zenbqix)
    
* [🔗 **DSA Introduction – Part 6**](https://hashnode.com/post/cma9o234e000g09l5fmd45z7i)