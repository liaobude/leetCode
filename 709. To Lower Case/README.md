## 思路

题目：[转换成小写字母](https://leetcode-cn.com/problems/to-lower-case)

`A-Z` 的 **ASCII** 码 为 **65-90**

`a-z` 的 **ASCII** 码为**97-122**

差值为 `97-65 = 32`

只需要在循环中判断该字符串的值是否在 **65-90** 之间

若在则加上 **32** 即可