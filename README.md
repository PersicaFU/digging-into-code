# digging-into-code
## 做题要求
+ 时间复杂度
  + O(1) 没有循环等复杂结构
  + O(n) for循环里面的代码会执行n遍,正比
  + O(log(N)) 设循环x次后 刚好跳出loop，（算出log2^n 次以后）
  + O(nlogN) O(log(N))循环n次
  + O(m*n) O(n) 嵌套循环O(m)
+ 空间复杂度
  + O(1) 如果算法执行所需要的临时空间不随着某个变量n的大小而变化 e.g. i=1
  + O(n) 数组占n（若有循环，但没有再分配新的空间，则不变） e.g. int[] m = new int[n]
## Array
