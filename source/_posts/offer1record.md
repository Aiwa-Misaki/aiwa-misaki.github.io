---
title: 剑指 Offer（原版） 记录
date: 2023-05-05 00:29:37
tags: 学习
---

16/05/2023 更新：正在回顾，思考新解法。
<!-- more -->



### 03. 数组中重复的数字

- [x] (https://leetcode.cn/problems/shu-zu-zhong-zhong-fu-de-shu-zi-lcof/?favorite=xb9nqhhg)

```c++
// 这题可以用map或者set（或者数组）
// std::unordered_xxx<> 底层是 hash table 实现的，不能用于 string 等不可散列化的类型
// 另外还有种方法是 swap
```

### 04. 二维数组中的查找 ###

- [x] (https://leetcode.cn/problems/er-wei-shu-zu-zhong-de-cha-zhao-lcof/?favorite=xb9nqhhg)

```c++
// 我的解法：left right top bottom 逐个缩小范围
// 更好的解法：缩小范围时只记住一个顶点就行
```

### 05. 替换空格 ###

- [x] (https://leetcode.cn/problems/ti-huan-kong-ge-lcof/?favorite=xb9nqhhg)

```c++
// 原地修改字符串
// 先开空间，从后往前修改
```

### 06. 从尾到头打印链表 ###

- [x] (https://leetcode.cn/problems/cong-wei-dao-tou-da-yin-lian-biao-lcof/?favorite=xb9nqhhg)

```c++
// 用递归，不需要倒转链表
```

### 07. 重建二叉树 ###

- [x] (https://leetcode.cn/problems/zhong-jian-er-cha-shu-lcof/?favorite=xb9nqhhg)

```c++
// 递归，实现不熟练
```

### 09. 用两个栈实现队列 ###

- [x] (https://leetcode.cn/problems/yong-liang-ge-zhan-shi-xian-dui-lie-lcof/?favorite=xb9nqhhg)

```c++
// easy
```

### 10- I. 斐波那契数列 ###

- [x] (https://leetcode.cn/problems/fei-bo-na-qi-shu-lie-lcof/?favorite=xb9nqhhg)

```c++
// 加法取余问题
```

### 10- II. 青蛙跳台阶问题 ###

- [x] (https://leetcode.cn/problems/qing-wa-tiao-tai-jie-wen-ti-lcof/?favorite=xb9nqhhg)

```c++
// 简单dp
```

### 11. 旋转数组的最小数字 ###

- [x] (https://leetcode.cn/problems/xuan-zhuan-shu-zu-de-zui-xiao-shu-zi-lcof/?favorite=xb9nqhhg)

```c++
// 二分
```

### 12. 矩阵中的路径 ###

- [x] (https://leetcode.cn/problems/ju-zhen-zhong-de-lu-jing-lcof/?favorite=xb9nqhhg)

```c++
// dfs
```

### 13. 机器人的运动范围 ###

- [x] (https://leetcode.cn/problems/ji-qi-ren-de-yun-dong-fan-wei-lcof/?favorite=xb9nqhhg)

```c++
// 简单遍历
```

### 14- I. 剪绳子 ###

- [x] (https://leetcode.cn/problems/jian-sheng-zi-lcof/?favorite=xb9nqhhg)

```c++
// easy dp
// 但是可以优化
```

### 14- II. 剪绳子 II ###

- [ ] (https://leetcode.cn/problems/jian-sheng-zi-ii-lcof/?favorite=xb9nqhhg)

```c++

```

### 15. 二进制中1的个数 ###

- [x] (https://leetcode.cn/problems/er-jin-zhi-zhong-1de-ge-shu-lcof/?favorite=xb9nqhhg)

```c++
// 位运算
```

### 16. 数值的整数次方 ###

- [x] (https://leetcode.cn/problems/shu-zhi-de-zheng-shu-ci-fang-lcof/?favorite=xb9nqhhg)

```c++
// 快速幂
```

### 17. 打印从1到最大的n位数 ###

- [x] (https://leetcode.cn/problems/da-yin-cong-1dao-zui-da-de-nwei-shu-lcof/?favorite=xb9nqhhg)

```c++

```

### 18. 删除链表的节点 ###

- [x] (https://leetcode.cn/problems/shan-chu-lian-biao-de-jie-dian-lcof/?favorite=xb9nqhhg)

```c++
// 快慢指针
```

### 19. 正则表达式匹配 ###

- [x] (https://leetcode.cn/problems/zheng-ze-biao-da-shi-pi-pei-lcof/?favorite=xb9nqhhg)

```c++
// dp 注意初始值
```

### 20. 表示数值的字符串 ###

- [x] (https://leetcode.cn/problems/biao-shi-shu-zhi-de-zi-fu-chuan-lcof/?favorite=xb9nqhhg)

```c++
// 状态机
```

### 21. 调整数组顺序使奇数位于偶数前面 ###

- [x] (https://leetcode.cn/problems/diao-zheng-shu-zu-shun-xu-shi-qi-shu-wei-yu-ou-shu-qian-mian-lcof/?favorite=xb9nqhhg)

```c++
// 快排
```

### 22. 链表中倒数第k个节点 ###

- [x] (https://leetcode.cn/problems/lian-biao-zhong-dao-shu-di-kge-jie-dian-lcof/?favorite=xb9nqhhg)

```c++
// 快慢指针 
```

### 24. 反转链表 ###

- [x] (https://leetcode.cn/problems/fan-zhuan-lian-biao-lcof/?favorite=xb9nqhhg)

```c++

```

### 25. 合并两个排序的链表 ###

- [x] (https://leetcode.cn/problems/he-bing-liang-ge-pai-xu-de-lian-biao-lcof/?favorite=xb9nqhhg)

```c++
// 递归
```

### 26. 树的子结构 ###

- [x] (https://leetcode.cn/problems/shu-de-zi-jie-gou-lcof/?favorite=xb9nqhhg)

```c++
// 递归
```

### 27. 二叉树的镜像 ###

- [x] (https://leetcode.cn/problems/er-cha-shu-de-jing-xiang-lcof/?favorite=xb9nqhhg)

```c++
// 递归
```

### 28. 对称的二叉树 ###

- [x] (https://leetcode.cn/problems/dui-cheng-de-er-cha-shu-lcof/?favorite=xb9nqhhg)

```c++
// 递归
```

### 29. 顺时针打印矩阵 ###

- [x] (https://leetcode.cn/problems/shun-shi-zhen-da-yin-ju-zhen-lcof/?favorite=xb9nqhhg)

```c++

```

### 30. 包含min函数的栈 ###

- [x] (https://leetcode.cn/problems/bao-han-minhan-shu-de-zhan-lcof/?favorite=xb9nqhhg)

```c++

```

### 31. 栈的压入、弹出序列 ###

- [x] (https://leetcode.cn/problems/zhan-de-ya-ru-dan-chu-xu-lie-lcof/?favorite=xb9nqhhg)

```c++

```

### 32 - I. 从上到下打印二叉树 ###

- [x] (https://leetcode.cn/problems/cong-shang-dao-xia-da-yin-er-cha-shu-lcof/?favorite=xb9nqhhg)

```c++

```

### 32 - II. 从上到下打印二叉树 II ###

- [x] (https://leetcode.cn/problems/cong-shang-dao-xia-da-yin-er-cha-shu-ii-lcof/?favorite=xb9nqhhg)

```c++

```

### 32 - III. 从上到下打印二叉树 III ###

- [x] (https://leetcode.cn/problems/cong-shang-dao-xia-da-yin-er-cha-shu-iii-lcof/?favorite=xb9nqhhg)

```c++

```

### 33. 二叉搜索树的后序遍历序列 ###

- [x] (https://leetcode.cn/problems/er-cha-sou-suo-shu-de-hou-xu-bian-li-xu-lie-lcof/?favorite=xb9nqhhg)

```c++

```

### 34. 二叉树中和为某一值的路径 ###

- [x] (https://leetcode.cn/problems/er-cha-shu-zhong-he-wei-mou-yi-zhi-de-lu-jing-lcof/?favorite=xb9nqhhg)

```c++

```

### 35. 复杂链表的复制 ###

- [x] (https://leetcode.cn/problems/fu-za-lian-biao-de-fu-zhi-lcof/?favorite=xb9nqhhg)

```c++

```

### 36. 二叉搜索树与双向链表 ###

- [x] (https://leetcode.cn/problems/er-cha-sou-suo-shu-yu-shuang-xiang-lian-biao-lcof/?favorite=xb9nqhhg)

```c++

```

### 37. 序列化二叉树 ###

- [x] (https://leetcode.cn/problems/xu-lie-hua-er-cha-shu-lcof/?favorite=xb9nqhhg)

```c++

```

### 38. 字符串的排列 ###

- [x] (https://leetcode.cn/problems/zi-fu-chuan-de-pai-lie-lcof/?favorite=xb9nqhhg)

```c++

```

### 39. 数组中出现次数超过一半的数字 ###

- [x] (https://leetcode.cn/problems/shu-zu-zhong-chu-xian-ci-shu-chao-guo-yi-ban-de-shu-zi-lcof/?favorite=xb9nqhhg)

```c++

```

### 40. 最小的k个数 ###

- [x] (https://leetcode.cn/problems/zui-xiao-de-kge-shu-lcof/?favorite=xb9nqhhg)

```c++

```

### 41. 数据流中的中位数 ###

- [x] (https://leetcode.cn/problems/shu-ju-liu-zhong-de-zhong-wei-shu-lcof/?favorite=xb9nqhhg)

```c++
// 两个堆
```

### 42. 连续子数组的最大和 ###

- [x] (https://leetcode.cn/problems/lian-xu-zi-shu-zu-de-zui-da-he-lcof/?favorite=xb9nqhhg)

```c++
// dp
```

### 43. 1～n 整数中 1 出现的次数 ###

- [x] (https://leetcode.cn/problems/1nzheng-shu-zhong-1chu-xian-de-ci-shu-lcof/?favorite=xb9nqhhg)

```c++

```

### 44. 数字序列中某一位的数字 ###

- [x] (https://leetcode.cn/problems/shu-zi-xu-lie-zhong-mou-yi-wei-de-shu-zi-lcof/?favorite=xb9nqhhg)

```c++

```

### 45. 把数组排成最小的数 ###

- [x] (https://leetcode.cn/problems/ba-shu-zu-pai-cheng-zui-xiao-de-shu-lcof/?favorite=xb9nqhhg)

```c++
// 自定义cmp
```

### 46. 把数字翻译成字符串 ###

- [x] (https://leetcode.cn/problems/ba-shu-zi-fan-yi-cheng-zi-fu-chuan-lcof/?favorite=xb9nqhhg)

```c++

```

### 47. 礼物的最大价值 ###

- [x] (https://leetcode.cn/problems/li-wu-de-zui-da-jie-zhi-lcof/?favorite=xb9nqhhg)

```c++

```

### 48. 最长不含重复字符的子字符串 ###

- [x] (https://leetcode.cn/problems/zui-chang-bu-han-zhong-fu-zi-fu-de-zi-zi-fu-chuan-lcof/?favorite=xb9nqhhg)

```c++

```

### 49. 丑数 ###

- [x] (https://leetcode.cn/problems/chou-shu-lcof/?favorite=xb9nqhhg)

```c++

```

### 50. 第一个只出现一次的字符 ###

- [x] (https://leetcode.cn/problems/di-yi-ge-zhi-chu-xian-yi-ci-de-zi-fu-lcof/?favorite=xb9nqhhg)

```c++

```

### 51. 数组中的逆序对 ###

- [x] (https://leetcode.cn/problems/shu-zu-zhong-de-ni-xu-dui-lcof/?favorite=xb9nqhhg)

```c++

```

### 52. 两个链表的第一个公共节点 ###

- [x] (https://leetcode.cn/problems/liang-ge-lian-biao-de-di-yi-ge-gong-gong-jie-dian-lcof/?favorite=xb9nqhhg)

```c++

```

### 53 - I. 在排序数组中查找数字 I ###

- [x] (https://leetcode.cn/problems/zai-pai-xu-shu-zu-zhong-cha-zhao-shu-zi-lcof/?favorite=xb9nqhhg)

```c++

```

### 53 - II. 0～n-1中缺失的数字 ###

- [x] (https://leetcode.cn/problems/que-shi-de-shu-zi-lcof/?favorite=xb9nqhhg)

```c++

```

### 54. 二叉搜索树的第k大节点 ###

- [x] (https://leetcode.cn/problems/er-cha-sou-suo-shu-de-di-kda-jie-dian-lcof/?favorite=xb9nqhhg)

```c++

```

### 55 - I. 二叉树的深度 ###

- [x] (https://leetcode.cn/problems/er-cha-shu-de-shen-du-lcof/?favorite=xb9nqhhg)

```c++

```

### 55 - II. 平衡二叉树 ###

- [x] (https://leetcode.cn/problems/ping-heng-er-cha-shu-lcof/?favorite=xb9nqhhg)

```c++

```

### 56 - I. 数组中数字出现的次数 ###

- [x] (https://leetcode.cn/problems/shu-zu-zhong-shu-zi-chu-xian-de-ci-shu-lcof/?favorite=xb9nqhhg)

```c++

```

### 56 - II. 数组中数字出现的次数 II ###

- [x] (https://leetcode.cn/problems/shu-zu-zhong-shu-zi-chu-xian-de-ci-shu-ii-lcof/?favorite=xb9nqhhg)

```c++

```

### 57. 和为s的两个数字 ###

- [x] (https://leetcode.cn/problems/he-wei-sde-liang-ge-shu-zi-lcof/?favorite=xb9nqhhg)

```c++

```

### 57 - II. 和为s的连续正数序列 ###

- [x] (https://leetcode.cn/problems/he-wei-sde-lian-xu-zheng-shu-xu-lie-lcof/?favorite=xb9nqhhg)

```c++

```

### 58 - I. 翻转单词顺序 ###

- [x] (https://leetcode.cn/problems/fan-zhuan-dan-ci-shun-xu-lcof/?favorite=xb9nqhhg)

```c++

```

### 58 - II. 左旋转字符串 ###

- [x] (https://leetcode.cn/problems/zuo-xuan-zhuan-zi-fu-chuan-lcof/?favorite=xb9nqhhg)

```c++

```

### 59 - I. 滑动窗口的最大值 ###

- [x] (https://leetcode.cn/problems/hua-dong-chuang-kou-de-zui-da-zhi-lcof/?favorite=xb9nqhhg)

```c++

```

### 59 - II. 队列的最大值 ###

- [x] (https://leetcode.cn/problems/dui-lie-de-zui-da-zhi-lcof/?favorite=xb9nqhhg)

```c++

```

### 60. n个骰子的点数 ###

- [x] (https://leetcode.cn/problems/nge-tou-zi-de-dian-shu-lcof/?favorite=xb9nqhhg)

```c++

```

### 61. 扑克牌中的顺子 ###

- [x] (https://leetcode.cn/problems/bu-ke-pai-zhong-de-shun-zi-lcof/?favorite=xb9nqhhg)

```c++

```

### 62. 圆圈中最后剩下的数字 ###

- [x] (https://leetcode.cn/problems/yuan-quan-zhong-zui-hou-sheng-xia-de-shu-zi-lcof/?favorite=xb9nqhhg)

```c++

```

### 63. 股票的最大利润 ###

- [x] (https://leetcode.cn/problems/gu-piao-de-zui-da-li-run-lcof/?favorite=xb9nqhhg)

```c++

```

### 64. 求1+2+…+n ###

- [x] (https://leetcode.cn/problems/qiu-12n-lcof/?favorite=xb9nqhhg)

```c++

```

### 65. 不用加减乘除做加法 ###

- [x] (https://leetcode.cn/problems/bu-yong-jia-jian-cheng-chu-zuo-jia-fa-lcof/?favorite=xb9nqhhg)

```c++
// mark
```

### 66. 构建乘积数组 ###

- [x] (https://leetcode.cn/problems/gou-jian-cheng-ji-shu-zu-lcof/?favorite=xb9nqhhg)

```c++
// dp空间优化
```

### 67. 把字符串转换成整数 ###

- [x] (https://leetcode.cn/problems/ba-zi-fu-chuan-zhuan-huan-cheng-zheng-shu-lcof/?favorite=xb9nqhhg)

```c++
// 状态机，细节处理麻烦
```

### 68 - I. 二叉搜索树的最近公共祖先 ###

- [x] (https://leetcode.cn/problems/er-cha-sou-suo-shu-de-zui-jin-gong-gong-zu-xian-lcof/?favorite=xb9nqhhg)

```c++
// 二叉搜索树的性质/递归
```

### 68 - II. 二叉树的最近公共祖先 ###

- [x] (https://leetcode.cn/problems/er-cha-shu-de-zui-jin-gong-gong-zu-xian-lcof/?favorite=xb9nqhhg)

``` c++

```