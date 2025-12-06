---
marp: true
title: Product Documentation
author: Technical Writer
theme: gaia
paginate: true
---

<style>
/* ====== CUSTOM THEME ADDITIONS ====== */
section {
  font-family: "Segoe UI", sans-serif;
}
h1 {
  color: #006699;
}
table {
  font-size: 0.8em;
}
/* Footer styling for page numbers */
footer {
  font-size: 0.6em;
  color: #555;
}
</style>

# Product Documentation using Marp

**Prepared by:**  
24f2008092@ds.study.iitm.ac.in

<footer>Slide 1</footer>

---

# Objective

- Maintainable documentation in version control  
- Convertible to HTML / PDF / PPTX  
- Uses Marp Markdown  

<footer>Slide 2</footer>

---

<!-- _background: url('https://upload.wikimedia.org/wikipedia/commons/thumb/2/20/Computer_network.svg/512px-Computer_network.svg.png') -->
<!-- _backgroundSize: cover -->

# System Architecture

This slide has a **full background image**.

<footer>Slide 3</footer>

---

# Algorithm Performance

We describe time complexity using mathematical notation.

### Time Complexity:

$$
T(n) = O(n \log n)
$$

### Space Complexity:
$$
S(n) = O(n)
$$

<footer>Slide 4</footer>

---

# Custom Styling via Directives

<!-- _color: #006699 -->
<!-- _fontSize: 26px -->
<!-- _backgroundColor: #E8F6FF -->

This slide uses custom color, font size, and background.

- Bullets
- More bullets
- Even more bullets

<footer>Slide 5</footer>

---

# Code Example

```python
def merge_sort(A):
    if len(A) <= 1:
        return A
    mid = len(A) // 2
    left = merge_sort(A[:mid])
    right = merge_sort(A[mid:])
    return merge(left, right)
