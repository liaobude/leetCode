## 解题思路

题目：[只出现一次的数字](https://leetcode-cn.com/problems/single-number)

这是一道非常有意思的题目

因为在这道题的解法中使用到了 「`异或`」

所以要解这道题首先循环数组 `nums`

其次在循环中依次异或当前值 `v`

最后获得的数就为缺少值

eg：nums = [4, 1, 2, 1, 2]

循环结束后 res = 4 ^ 1 ^ 2 ^ 1 ^ 2 = (1 ^ 1) ^ (2 ^ 2) ^ 4 = 0 ^ 0 ^ 4 =4

最终结果的时间复杂度为 `n` ，且没有使用额外空间



## 异或

0异或任何值都等于自己

任何数与自己异或都等于0

eg：a ^ b ^ a = (a ^ a) ^ b = 0 ^ b = 0