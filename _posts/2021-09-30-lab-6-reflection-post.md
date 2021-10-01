---
layout: post
title:  "Lab 6 Reflection Post"
date:   2021-09-30 21:20:39 -0500
author: Isaac Khounborine
categories: jekyll update
---

This lab was very interesting. Figuring out how to use the SQL commands to find
the exact data I was looking for was heavily helped by the CodeAcademy tutorial.

![lab6-1.PNG](https://khounborineii.github.io/assets/lab6-1.PNG)

There was actually something extremely frustrating about finding this first
solution. It was my fault alone. I accidentally used `COUNT()` instead of
`SUM()` for counting the `grads.num` so it wasn't adding up the number of
graduates correctly. This would actually be the ONLY hurdle I would encounter.

![lab6-2.PNG](https://khounborineii.github.io/assets/lab6-2.PNG)

As you can see, I barely had to change the first solution to get the second
solution. I simply had to change the `WHERE` to have the correct parameters.

![lab6-3.PNG](https://khounborineii.github.io/assets/lab6-3.PNG)

I had to do the same for this one too. `ORDER BY` had to be added so it was in
the correct order.

![lab6-4.PNG](https://khounborineii.github.io/assets/lab6-4.PNG)

I had to change the table that was joining with `grads` from `colleges` to  `majors`.
Places with `id` had to be replaced with `cip`, and the `ORDER BY` to had to be
adjusted as well.

That one `COUNT()` vs `SUM()` threw me in a loop for a long time, but once I did it
the longest part of this lab was simply doing the tutorial. One suggestion to
the lab would probably include the `headers on` and `mode column` that you
demonstrated in class so we can view the tables normally. 
