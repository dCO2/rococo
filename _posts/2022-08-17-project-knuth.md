---
layout: project
title: "Project Knuth: Learning Algorithm Design [#coding]"
feature-image: /assets/images/author-image.png
permalink: /:year/:month/:day/:title
tags: 
---

`project begin date: Jan 04, 2022`  
`project end date: Indefinite`  
`completion rate: 50%`  
`success rate: 40%`  
`remarks: difficult; work in progress`

<details>
  <summary><h2>> List of Content</h2></summary>
  <ol>
    <li><a href="">Intro</a></li>
      <ul style="margin-top:0; margin-bottom:0;">
        <li></li>
      </ul>
    <li><a href="">Philosophying</a></li>
  </ol>
</details>

![](/assets/images/three-wise-men.jpg)
_Three Wise Men_ by Jimoh Buraimoh, 1991

- Why learn Algorithm design?
- Write down your thought process when thinking about a solution for problems.
  - Leetcode 985, [Sum Of Even Numbers After Queries](/2022/09/21/sum-of-even-number-after-queries).
- See [Using Anki to think about algorithm design problems]().
  - [are you not cramming code?]()---Oh no, actually not.
- Algorithms that easily become a part of you (because they are simple? or their problem statement is straightforward? or the solution is memorable?)
  - Linked List: "_Design an algorithm that, given a pointer to the head of a linked list, returns a pointer to the element at the middle of the list_", [Leetcode Link](https://leetcode.com/problems/middle-of-the-linked-list/)
  - Bit-shifting, Adhoc: "_Design an algorithm that, given a non-empty array of integers where every integer appears twice except for one integer, returns the value of that one integer_", [Leetcode Link](https://leetcode.com/problems/single-number/)
  - Breadth-first search
  - Depth-first search
- Restate problem statement for algorithms in your own words (i.e., compress them)
  - For example, despite the long plot for the problem in [Leetcode 198 - House Robber](https://leetcode.com/problems/house-robber/), the task is basically to _design an algorithm that makes a selection of numbers in an array such that the sum of the selected numbers is maximum but adjacent numbers cannot be selected_.
  - A compressed statement then is; _select maximum sum of non-adjacent numbers from given array_.
- It is also important to understand that algorithms designed with the technical interview process in mind are not in their final form. They could be modified into shorter and easier-to-think-about code by employing the programming language's standard library. Employing this standard algorithms library is a skill.
  - For example... "_Design an algorithm that, given the head of an unsorted linked list of integers, returns the head to the linked list sorted using insertion sort_"
  - To solve this, if the input is not a linked list but an array, one could go on and implement the insertion sort procedure. But it is usually better to employ standard lbrary algorithm. The algorithm below is an implementation of the insertion sort procedure on an array, making use of the `std::rotate`, `std::upper_bound`, and `std::next` algorithms in c++.  
  ```c++
  for(auto i = start; i != end; i++){
    std::rotate(std::upper_bound(start, i, *i), i, std::next(i));
  }
  ```
- ...
