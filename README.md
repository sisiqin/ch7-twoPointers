# ch7-twoPointers

#### two pointers有同向双指针和相向双指针

#### 对于求 2 个变量如何组合的问题（比如3sum） 可以循环其中一个变量，然后研究另外一个变量如何变化
## 基本功

- 同向：window sum 

- 相向： quick select --- 载体： Kth Smallest Numbers in Unsorted Array

## 经典题

- 2/3/4 sum

- 2/3/4 sum closest

- 2/3/4 sum with duplication

- two sum data struture design -- 只能用hash map

- Triangle Count

- 2 sum less/greater than a target -- return count numbers/ pairs 

- Partition Array ： by a target / by odd even / by positive negative ... 分成两份/分成三份

-  Sort Colors -- color的个数是固定的/是input，是两道完全不同的题

     - 如果是固定的，那么统计一下不同颜色出现的个数，重新构造一个array，return出去就好了。这是o(n)的，跟排序没有关系
  
     - 如果颜色个数是input，那么需要排序，用**彩虹排序**



