---
layout: note
title: "Sum Of Even Numbers After Queries"
feature-image: /assets/images/author-image.png
permalink: /:year/:month/:day/:title
tags:
---

[Leetcode Link](https://leetcode.com/problems/sum-of-even-numbers-after-queries/).

This problem at first glance seems to be a simple simulation problem. That is, the technical difficulty involves programming a not-too-clever bruteforce algorithm that just solves the problem. Yes, this is true but this solution will hit TLE for large inputs.

This kind of solution, with python, is as shown below:
```python
class Solution:
    def sumEvenAfterQueries(self, nums: List[int], queries: List[List[int]]) -> List[int]:
        
        output = []
        sz_queries = len(queries)
        
        for j in range(sz_queries):
            nums[queries[j][1]] += queries[j][0]
            
            even_sum = 0
            for n in nums:
                if n%2 == 0:
                    even_sum += n
        
            output.append(even_sum)
        
        return output
```
This works but a more performant has to be cleverly designed. I think due to the repeated sums of even numbers, a "dynamic solution" might be possible?

---

[Tutorial Link from _Coding Decoded_](https://www.youtube.com/watch?v=2bjRM_6hDsI).
