# question-2
wap to implements the fifo page replacement algorithm.first generate a random page reference string where page numbers range from
0 to 9.apply the random page reference string to each algorithm and record the number of page faults incurred by each algorithm.
implement the replacement algorithm so that the number of page frames can vary from 1 to 7.assume that demand paging is used


=>page replacement needs to have its code and data reside in memory before it is executed.but sometimes the memory size cannot fit all the code and data of running programs.the solution is to slice both memory and programs into equal-sized pages

FIFO=> the newly brought in page will replace the oldest page resident in memory.the idea is that the earliest page brought in will
be the first one replaced.

