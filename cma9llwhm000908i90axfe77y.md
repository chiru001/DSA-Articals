---
title: "DSA-Introduction: Part 4"
datePublished: Sun May 04 2025 11:58:42 GMT+0000 (Coordinated Universal Time)
cuid: cma9llwhm000908i90axfe77y
slug: dsa-introduction-part-4
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/ZS67i1HLllo/upload/a89954a20a1fb4a6a392fb67a68279a7.jpeg
tags: chaiaurcode, chaicode, chaicohort, chaiaurcpp

---

# Understanding Constant Time Complexity – O(1)

When you're learning Data Structures and Algorithms (DSA), one of the first concepts you'll hear about is **time complexity** — a way to describe how fast or slow a program runs depending on the size of the input.

Let’s start with the **simplest and fastest** one:

---

## What is Constant Time Complexity?

**Constant Time Complexity**, written as **O(1)**, means:

> No matter how big the input is, the operation takes the **same amount of time** to execute.

It doesn’t care if you’re working with 1 item or 1 million items it always takes just one step.

---

## Think of It Like This:

Imagine you have a **locker with 1,000 drawers**, and each drawer is labeled with a number from 1 to 1,000.

If someone asks you, “Give me the item in drawer 700,” and you go **straight to drawer 700** and pull it out. You did it in **one move**.

That’s **constant time** — no searching, no looping. Just direct access.

---

## Simple Code Example in Python

```python
def get_first_element(arr):
    return arr[0]

numbers = [10, 20, 30, 40, 50]
print(get_first_element(numbers))
```

**Missed the earlier parts?**  
Make sure to check out the previous posts in this series for a complete understanding of time complexity and algorithm analysis:

* 🔗 [**DSA Introduction – Part 1**](https://hashnode.com/post/cma9jk346000109js0hjs1asn)
    
* 🔗 [**DSA Introduction – Part 2**](https://hashnode.com/post/cma9julja000s08l79cy8cp0i)
    
* [🔗 **DSA Introduction – Part 3**](https://hashnode.com/post/cma9koi9f000109lefmpb3mbg)
    
* [🔗 **DSA Introduction – Part 4**](https://hashnode.com/post/cma9llwhm000908i90axfe77y)
    
* [🔗 **DSA Introduction – Part 5**](https://hashnode.com/post/cma9mbtsz000308ld0zenbqix)
    
* [🔗 **DSA Introduction – Part 6**](https://hashnode.com/post/cma9o234e000g09l5fmd45z7i)