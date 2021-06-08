# No Output Buffer Sort

No output buffer sort is an optimization of external merge sort for memory-constrained embedded devices. It uses less memory than external merge sort and is significantly faster when the memory is limited. The algorithm was published in the ACM Transactions on Embedded Computing Systems in 2021 ([paper](https://dl.acm.org/doi/10.1145/3446976)). 

No output buffer sort has the following benefits:

1. Reduces the minimum memory usage to 1 KB which is 33% less than external merge sort.
2. No use of dynamic memory (i.e. malloc()). 
3. Easy to use and include in existing projects. 
4. Open source license. Free to use for commerical and open source projects.

## License
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

## Code Files

* no_output_buffer_sort_block_heap.c, no_output_buffer_sort_block_heap.h - implementation of no output buffer sort
* test_no_output_buffer_sort_block_heap.c - test file


#### Ramon Lawrence<br>University of British Columbia Okanagan
