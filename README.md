# terrain-visibility
This repository contains an unofficial implementation of a paper titled "A faster algorithm to compute the visibility map of a 1.5D terrain" by Maarten L ̈offler et al.

## Overview

This code implements a solution to the 1.5D terrain visibility problem, which is, given an x-monotonic polygonial line in $R^2$ with n vertices and $m <= n$ viewpoints, find the visible parts of the terrain. The algorithm time complexity is $O(n + m log m)$ which is an improvement compared to previous work. You can find more information about the algorithm in the paper: [https://www.semanticscholar.org/paper/A-Faster-Algorithm-to-Compute-the-Visibility-Map-of-L%C3%B6ffler-Saumell/1405e04a59a1186b11ec897e92737ff42e8b8bbf](link).

A Colab notebook is provided to run this unofficial implementation. Note that the "right-visibility" can be implemented similarly to the "left-visibility".

## Example

Here is a terrain example with the provided visibility maps:


![image](https://github.com/user-attachments/assets/66061402-febb-46b7-94f1-e5d64c06f2fd)

Note that the red dots are the viewpoints. Here is the calculated visibility map:


![image](https://github.com/user-attachments/assets/c8fe42fe-b142-401e-94fc-fa9215dedfda)

## Citation

```
@inproceedings{loffler2014faster,
  title={A faster algorithm to compute the visibility map of a 1.5 D terrain},
  author={L{\"o}ffler, Maarten and Saumell, Maria and Silveira, Rodrigo Ignacio},
  booktitle={Abstracts 30th European Workshop on Computational Geometry},
  pages={1--4},
  year={2014}
}
```
