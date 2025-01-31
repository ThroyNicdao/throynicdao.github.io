---
layout: project
type: project
image: img/array02b.gif
title: "OffsetArray"
date: 2022
published: True
labels:
  - Java
  - ICS
  - Project

summary: "This Java class, OffsetArrayList<E>, is a custom implementation of an ArrayList with an additional offset feature. It functions similarly to a standard ArrayList, but elements are accessed with an adjustable offset, shifting the valid index range. This means that valid indices start at offset rather than 0."
---

<img class="img-fluid" src="../img/OffsetArray.png">

The `OffsetArrayList` class is a custom implementation of an `ArrayList` with an adjustable **offset**, meaning valid indices start at a specified number rather than `0`. It allows adding, removing, and modifying elements while automatically resizing the internal array when needed. The class also includes methods for shifting elements when inserting or deleting items, ensuring the list remains properly structured. It throws exceptions for invalid operations, such as accessing out-of-bounds indices. Additionally, a built-in `unitTest()` function verifies its correctness, and the `main()` method demonstrates its functionality by adding, removing, and printing elements.
 

