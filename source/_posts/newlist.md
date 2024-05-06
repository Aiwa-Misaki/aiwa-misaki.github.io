---
title: 剑指 Offer（专项突击版） 记录
date: 2023-03-18 23:56:29
tags: 学习
---
19/03/2023 更新：119 题都写完了，接下来简单复盘+补充其他解法和思路
<!-- more -->

- [x] ### 001. 整数除法 ###
  
  [https://leetcode.cn/tag/hash-table](https://leetcode.cn/problems/xoh6Oh/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  位运算·数学·
   ```c++ 
   // 重点处理溢出
   ```
- [x] ### 002. 二进制加法 ### 
  [https://leetcode.cn/tag/math](https://leetcode.cn/problems/JFETK5/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  位运算·数学·字符串·模拟·
  
   ```c++ 
   // 逆序运算
   auto ite = a.rbegin();
   while ( ite < a.rend());
  
   ```
- [x] ### 003. 前 n 个数字二进制中 1 的个数 ### 
  [https://leetcode.cn/tag/simulation](https://leetcode.cn/problems/w3tCBm/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  位运算·动态规划·
   ```c++ 
   // 移位运算
  
   ```
- [x] ### 004. 只出现一次的数字 ### 
  [https://leetcode.cn/tag/dynamic-programming](https://leetcode.cn/problems/WGki4K/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  位运算·数组·
   ```c++ 
   // 利用位运算
   ```
- [x] ### 005. 单词长度的最大乘积 ### 
  [https://leetcode.cn/tag/array](https://leetcode.cn/problems/aseY1I/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  位运算·数组·字符串·
   ```c++ 
   // 位运算掩码
   // 使用 int 表示
   mask |= 1<<(word[j]-'a');
   ```
- [x] ### 006. 排序数组中两个数字之和 ### 
  [https://leetcode.cn/tag/string](https://leetcode.cn/problems/kLl5u1/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·双指针·二分查找·
   ```c++ 
   // 双指针剪枝
   ```
- [x] ### 007. 数组中和为 0 的三个数 ### 
  [https://leetcode.cn/tag/binary-search](https://leetcode.cn/problems/1fGaJU/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·双指针·排序·
   ```c++ 
   // 三元组如何不重复
   (a){
     (b c){
       // 双指针
     }
   }
   // 每一重循环内，相邻两个遍历的元素不同
   ```
- [x] ### 008. 和大于等于 target 的最短子数组 ### 
  [https://leetcode.cn/tag/sorting](https://leetcode.cn/problems/2VG8Kg/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·二分查找·前缀和·滑动窗口·
   ```c++ 
   // 数组全是正整数
   // 1) 前缀和 + set::lower_bound() 即二分查找
   // 2) 滑动窗口
   ```
- [x] ### 009. 乘积小于 K 的子数组 ###
  [https://leetcode.cn/tag/sliding-window](https://leetcode.cn/problems/ZVAVXX/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·滑动窗口·
   ```c++ 
   // 数组全是正整数
   //   	
   ```
- [x] ### 010. 和为 k 的子数组 ### 
  [https://leetcode.cn/tag/sliding-window](https://leetcode.cn/problems/QTMn0o/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·哈希表·前缀和·
	 ```c++ 
	 
   ```
- [x] ### 011. 0 和 1 个数相同的子数组 ### 
  [https://leetcode.cn/tag/prefix-sum](https://leetcode.cn/problems/A1NYOS/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·哈希表·前缀和·
	 ```c++ 
	 
   ```
- [x] ### 012. 左右两边子数组的和相等 ### 
  [https://leetcode.cn/tag/prefix-sum](https://leetcode.cn/problems/tvdfij/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·前缀和·
	 ```c++ 
	 
   ```
- [x] ### 013. 二维子矩阵的和 ### 
  [https://leetcode.cn/tag/prefix-sum](https://leetcode.cn/problems/O4NDxx/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  设计·数组·矩阵·前缀和·
	 ```c++ 
	 
   ```
- [x] ### 014. 字符串中的变位词 ### 
  [https://leetcode.cn/tag/prefix-sum](https://leetcode.cn/problems/MPnaiL/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  哈希表·双指针·字符串·滑动窗口·
	 ```c++ 
	 
   ```
- [x] ### 015. 字符串中的所有变位词 ### 
  [https://leetcode.cn/tag/sliding-window](https://leetcode.cn/problems/VabMRr/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  哈希表·字符串·滑动窗口·
	 ```c++ 
	 
   ```
- [x] ### 016. 不含重复字符的最长子字符串 ### 
  [https://leetcode.cn/tag/sliding-window](https://leetcode.cn/problems/wtcaE1/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  哈希表·字符串·滑动窗口·
	 ```c++ 
	 
   ```
- [x] ### 017. 含有所有字符的最短字符串 ### 
  [https://leetcode.cn/tag/sliding-window](https://leetcode.cn/problems/M1oyTv/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  哈希表·字符串·滑动窗口·
	 ```c++ 
	 
   ```
- [x] ### 018. 有效的回文 ### 
  [https://leetcode.cn/tag/sliding-window](https://leetcode.cn/problems/XltzEq/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  双指针·字符串·
	 ```c++ 
	 
   ```
- [x] ### 019. 最多删除一个字符得到回文 ### 
  [https://leetcode.cn/tag/string](https://leetcode.cn/problems/RQku0D/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  贪心·双指针·字符串·
	 ```c++ 
	 
   ```
- [x] ### 020. 回文子字符串的个数 ### 
  [https://leetcode.cn/tag/string](https://leetcode.cn/problems/a7VOhD/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  字符串·动态规划·
	 ```c++ 
	 
   ```
- [x] ### 021. 删除链表的倒数第 n 个结点 ### 
  [https://leetcode.cn/tag/dynamic-programming](https://leetcode.cn/problems/SLwz0R/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  链表·双指针·
	 ```c++ 
	 
   ```
- [x] ### 022. 链表中环的入口节点 ### 
  [https://leetcode.cn/tag/two-pointers](https://leetcode.cn/problems/c32eOV/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  哈希表·链表·双指针·
	 ```c++ 
	 
   ```
- [x] ### 023. 两个链表的第一个重合节点 ### 
  [https://leetcode.cn/tag/two-pointers](https://leetcode.cn/problems/3u1WK4/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  哈希表·链表·双指针·
	 ```c++ 
	 
   ```
- [x] ### 024. 反转链表 ### 
  [https://leetcode.cn/tag/two-pointers](https://leetcode.cn/problems/UHnkqh/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  递归·链表·
	 ```c++ 
	 
   ```
- [x] ### 025. 链表中的两数相加 ### 
  [https://leetcode.cn/tag/linked-list](https://leetcode.cn/problems/lMSNwu/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  栈·链表·数学·
	 ```c++ 
	 
   ```
- [x] ### 026. 重排链表 ### 
  [https://leetcode.cn/tag/math](https://leetcode.cn/problems/LGjMqU/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  栈·递归·链表·双指针·
	 ```c++ 
	 
   ```
- [x] ### 027. 回文链表 ### 
  [https://leetcode.cn/tag/two-pointers](https://leetcode.cn/problems/aMhZSa/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  栈·递归·链表·双指针·
	 ```c++ 
	 
   ```
- [x] ### 028. 展平多级双向链表 ### 
  [https://leetcode.cn/tag/two-pointers](https://leetcode.cn/problems/Qv1Da2/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  深度优先搜索·链表·双向链表·
	 ```c++ 
	 
   ```
- [x] ### 029. 排序的循环链表 ### 
  [https://leetcode.cn/tag/doubly-linked-list](https://leetcode.cn/problems/4ueAj6/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  链表·
  
   ```c++ 
   // 如何简化问题？
   ```
- [x] ### 030. 插入、删除和随机访问都是 O(1) 的容器 ###
  [https://leetcode.cn/tag/linked-list](https://leetcode.cn/problems/FortPu/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  设计·数组·哈希表·数学·随机化·
   ```c++ 
   int randomIndex = rand()%nums.size();
   ```
- [x] ### 031. 最近最少使用缓存 ###
  
  [https://leetcode.cn/tag/randomized](https://leetcode.cn/problems/OrIXps/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  设计·哈希表·链表·双向链表·
  
   ```c++ 
   list<pair<int, int>> ll;
   map<int, pair<int, int> *> dict;
   
   
   class LRUCache {
       list<pair<int, int>> l;
       unordered_map<int, decltype(l.begin())> m;
       int capacity;
   public:
       LRUCache(int capacity) {
           this->capacity = capacity;
       }
   
       int get(int key) {
           auto ite = m.find(key);
           if (ite == m.end()) return -1;
           int val = ite->second->second;
           l.erase(ite->second);
           l.emplace_back(key, val);
           m[key] = --l.end();
           return val;
       }
   
       void put(int key, int value) {
           if (m.find(key) != m.end()) {
               l.erase(m.find(key)->second);
           }
           l.emplace_back(key, value);
           m[key] = --l.end();
           if (m.size() > capacity) {
               auto top = l.begin();
               m.erase(top->first);
               l.pop_front();
           }
       }
   };
   
  
   ```
- [x] ### 032. 有效的变位词 ###
  [https://leetcode.cn/tag/doubly-linked-list](https://leetcode.cn/problems/dKk3P7/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  哈希表·字符串·排序·
   ```c++ 
   1) 排序比较
   2) 哈希表统计
   ```
- [x] ### 033. 变位词组 ### 
  [https://leetcode.cn/tag/sorting](https://leetcode.cn/problems/sfvd7V/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·哈希表·字符串·排序·
	 ```c++ 
	 
   ```
- [x] ### 034. 外星语言是否排序 ### 
  [https://leetcode.cn/tag/sorting](https://leetcode.cn/problems/lwyVBB/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·哈希表·字符串·
	 ```c++ 
	 
   ```
- [x] ### 035. 最小时间差 ### 
  [https://leetcode.cn/tag/string](https://leetcode.cn/problems/569nqc/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·数学·字符串·排序·
	 ```c++ 
	 
   ```
- [x] ### 036. 后缀表达式 ### 
  [https://leetcode.cn/tag/sorting](https://leetcode.cn/problems/8Zf90G/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  栈·数组·数学·
	 ```c++ 
	 
   ```
- [x] ### 037. 小行星碰撞 ### 
  [https://leetcode.cn/tag/math](https://leetcode.cn/problems/XagZNi/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  栈·数组·
	 ```c++ 
	 
   ```
- [x] ### 038. 每日温度 ### 
  [https://leetcode.cn/tag/array](https://leetcode.cn/problems/iIQa4I/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  栈·数组·单调栈·
	 ```c++ 
	 // 单调栈模版题
   ```
- [x] ### 039. 直方图最大矩形面积 ### 
  [https://leetcode.cn/tag/monotonic-stack](https://leetcode.cn/problems/0ynMMM/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  栈·数组·单调栈·
   ```c++ 
   // 用单调栈：转化矩形面积算法
   ```
- [x] ### 040. 矩阵中最大的矩形 ### 
  [https://leetcode.cn/tag/monotonic-stack](https://leetcode.cn/problems/PLYXKQ/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  栈·数组·动态规划·矩阵·单调栈·
  
   ```c++ 
   // 分层单调栈
   ```
- [x] ### 041. 滑动窗口的平均值 ### 
  [https://leetcode.cn/tag/monotonic-stack](https://leetcode.cn/problems/qIsx9U/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  设计·队列·数组·数据流·
	 ```c++ 
	 
   ```
- [x] ### 042. 最近请求次数 ### 
  [https://leetcode.cn/tag/data-stream](https://leetcode.cn/problems/H8086Q/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  设计·队列·数据流·
	 ```c++ 
	 
   ```
- [x] ### 043. 往完全二叉树添加节点 ### 
  [https://leetcode.cn/tag/data-stream](https://leetcode.cn/problems/NaqhDT/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  树·广度优先搜索·设计·二叉树·
	 ```c++ 
	 
   ```
- [x] ### 044. 二叉树每层的最大值 ### 
  [https://leetcode.cn/tag/binary-tree](https://leetcode.cn/problems/hPov7L/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  树·深度优先搜索·广度优先搜索·二叉树·
	 ```c++ 
	 
   ```
- [x] ### 045. 二叉树最底层最左边的值 ### 
  [https://leetcode.cn/tag/binary-tree](https://leetcode.cn/problems/LwUNpT/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  树·深度优先搜索·广度优先搜索·二叉树·
	 ```c++ 
	 
   ```
- [x] ### 046. 二叉树的右侧视图 ### 
  [https://leetcode.cn/tag/binary-tree](https://leetcode.cn/problems/WNC0Lk/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  树·深度优先搜索·广度优先搜索·二叉树·
	 ```c++ 
	 
   ```
- [x] ### 047. 二叉树剪枝 ### 
  [https://leetcode.cn/tag/binary-tree](https://leetcode.cn/problems/pOCWxh/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  树·深度优先搜索·二叉树·
	 ```c++ 
	 
   ```
- [x] ### 048. 序列化与反序列化二叉树 ### 
  [https://leetcode.cn/tag/binary-tree](https://leetcode.cn/problems/h54YBf/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  树·深度优先搜索·广度优先搜索·设计·字符串·二叉树·
	 ```c++ 
	 
   ```
- [x] ### 049. 从根节点到叶节点的路径数字之和 ### 
  [https://leetcode.cn/tag/binary-tree](https://leetcode.cn/problems/3Etpl5/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  树·深度优先搜索·二叉树·
	 ```c++ 
	 
   ```
- [x] ### 050. 向下的路径节点之和 ### 
  [https://leetcode.cn/tag/binary-tree](https://leetcode.cn/problems/6eUYwP/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  树·深度优先搜索·二叉树·
   ```c++ 
   // multiset + dfs 
   // 效率较差
  
   ```
- [x] ### 051. 节点之和最大的路径 ### 
  [https://leetcode.cn/tag/binary-tree](https://leetcode.cn/problems/jC7MId/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  树·深度优先搜索·动态规划·二叉树·
   ```c++ 
   // 分解问题
   ```
- [x] ### 052. 展平二叉搜索树 ### 
  [https://leetcode.cn/tag/binary-tree](https://leetcode.cn/problems/NYBBNL/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  栈·树·深度优先搜索·二叉搜索树·二叉树·
	 ```c++ 
	 
   ```
- [x] ### 053. 二叉搜索树中的中序后继 ### 
  [https://leetcode.cn/tag/binary-tree](https://leetcode.cn/problems/P5rCT8/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  树·深度优先搜索·二叉搜索树·二叉树·
	 ```c++ 
	 
   ```
- [x] ### 054. 所有大于等于节点的值之和 ### 
  [https://leetcode.cn/tag/binary-tree](https://leetcode.cn/problems/w6cpku/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  树·深度优先搜索·二叉搜索树·二叉树·
	 ```c++ 
	 
   ```
- [x] ### 055. 二叉搜索树迭代器 ### 
  [https://leetcode.cn/tag/binary-tree](https://leetcode.cn/problems/kTOapQ/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  栈·树·设计·二叉搜索树·二叉树·迭代器·
	 ```c++ 
	 
   ```
- [x] ### 056. 二叉搜索树中两个节点之和 ### 
  [https://leetcode.cn/tag/iterator](https://leetcode.cn/problems/opLdQZ/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  树·深度优先搜索·广度优先搜索·二叉搜索树·哈希表·双指针·二叉树·
	 ```c++ 
	 
   ```
- [x] ### 057. 值和下标之差都在给定的范围内 ### 
  [https://leetcode.cn/tag/binary-tree](https://leetcode.cn/problems/7WqeDu/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·桶排序·有序集合·排序·滑动窗口·
   ```c++ 
   // multiset 和 priority_queue 的区别
   // multiset 由 BST 实现，建立的复杂度为 O(N logN)
   // priority_queue 由 heap 实现，建立复杂度为 O(N)
   // multiset 全部有序，pq 只能进行取堆顶的访问
   
   // multiset 的最小最大值
   multiset<int> m;
   *m.begin(); // minimum
   *m.rbegin(); // maximum
   
   // 如何判断是否有 [x-t,x+t] 之间的数字？
   ```
- [x] ### 058. 日程表 ### 
  [https://leetcode.cn/tag/sliding-window](https://leetcode.cn/problems/fi9suh/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  设计·线段树·二分查找·有序集合·
	
	 ```c++ 
   auto cmp = [&](){}
   set<int, decltype(cmp)> c(cmp);
   // use stl to perform bin search
   c.upper_bound()
   ```
- [x] ### 059. 数据流的第 K 大数值 ### 
  [https://leetcode.cn/tag/ordered-set](https://leetcode.cn/problems/jBjn9C/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  树·设计·二叉搜索树·二叉树·数据流·堆（优先队列）·
   ```c++ 
   // priority_queue
   ```
- [x] ### 060. 出现频率最高的 k 个数字 ### 
  [https://leetcode.cn/tag/heap-priority-queue](https://leetcode.cn/problems/g5c51o/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·哈希表·分治·桶排序·计数·快速选择·排序·堆（优先队列）·
  
   ```c++ 
   // 1) 先遍历一遍，然后用size=k的pq
   
   // 2) 边遍历边维护size=k的pq
   // 用 pq + map + set(记录哪些元素已经在pq里)
   // 这个方法不行，因为pq没法动态更新
  
   ```
- [x] ### 061. 和最小的 k 个数对 ### 
  [https://leetcode.cn/tag/heap-priority-queue](https://leetcode.cn/problems/qn8gGX/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·堆（优先队列）·
  ```c++
  // priority_queue 的 constructor
  std::priority_queue<pair<int,int>, vector<pair<int,int>>, (type of cmp)>(cmp func)
  // greater = min-heap
  // less = max-heap
  ```
   ```c++ 
   // 复杂小顶堆的实现
   // 自定义 greater
   priority_queue<pair<int,int>, vector<pair<int,int>>, decltype(cmp)> pq(cmp);
   ```
- [x] ### 062. 实现前缀树 ### 
  [https://leetcode.cn/tag/heap-priority-queue](https://leetcode.cn/problems/QC3q1f/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  设计·字典树·哈希表·字符串·
	 ```c++ 
	 
   ```
- [x] ### 063. 替换单词 ### 
  [https://leetcode.cn/tag/string](https://leetcode.cn/problems/UhWRSj/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  字典树·数组·哈希表·字符串·
   ```c++ 
   // split 字符串
   #include <string>
   #include <vector>
   #include <sstream>
   
   std::stringstream test("this_is_a_test_string");
   std::string segment;
   std::vector<std::string> seglist;
   
   while(std::getline(test, segment, '_')){
     seglist.push_back(segment);
   }
   
   //Member access within misaligned address with linked-list
   for(int i=0;i<26;i++){
   	dict[i] = nullptr;
   }
   ```
- [x] ### 064. 神奇的字典 ### 
  [https://leetcode.cn/tag/string](https://leetcode.cn/problems/US1pGT/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  设计·字典树·哈希表·字符串·
   ```c++ 
   // 前缀树，带有标记的dfs
  
   ```
- [x] ### 065. 最短的单词编码 ### 
  [https://leetcode.cn/tag/string](https://leetcode.cn/problems/iSwD2y/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  字典树·数组·哈希表·字符串·
   ```c++ 
   // 字典树
   // 清理标记位
   ```
- [x] ### 066. 单词之和 ###
  [https://leetcode.cn/tag/string](https://leetcode.cn/problems/z1R5dt/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  设计·字典树·哈希表·字符串·
   ```c++ 
   
   ```
- [x] ### 067. 最大的异或 ### 
  [https://leetcode.cn/tag/string](https://leetcode.cn/problems/ms70jA/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  位运算·字典树·数组·哈希表·
   ```c++ 
   // 转二进制字符串
   std::string s = std::bitset<64>( 12345 ).to_string();
   // 二进制字符串转数值
   bitset<64> bs(res);
   long val = bs.to_ulong;
   ```
- [x] ### 068. 查找插入位置 ### 
  [https://leetcode.cn/tag/hash-table](https://leetcode.cn/problems/N6YdxV/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·二分查找·
   ```c++ 
   // 练习二分查找如何不死循环不重不漏
   while(begin<end){
               int mid = (begin+end)/2;
               if(nums[mid] == target){
                   return mid;
               }else if(nums[mid]>target){
                   end = mid - 1;
               }else{
                   begin = mid + 1;
               }
           }
   ```
- [x] ### 069. 山峰数组的顶部 ### 
  [https://leetcode.cn/tag/binary-search](https://leetcode.cn/problems/B1IidL/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·二分查找·
   ```c++ 
   
   ```
- [x] ### 070. 排序数组中只出现一次的数字 ### 
  [https://leetcode.cn/tag/binary-search](https://leetcode.cn/problems/skFtm2/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·二分查找·
   ```c++ 
   
   ```
- [x] ### 071. 按权重生成随机数 ### 
  [https://leetcode.cn/tag/binary-search](https://leetcode.cn/problems/cuyjEf/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·数学·二分查找·前缀和·随机化·
   ```c++ 
   // 数轴 + 二分查找
   
   #include <random>
   std::random_device rd;     // Only used once to initialise (seed) engine
   std::mt19937 rng(rd());    // Random-number engine used (Mersenne-Twister in this case)
   std::uniform_int_distribution<int> uni(min,max); // Guaranteed unbiased
   auto random_integer = uni(rng);
   ```
- [x] ### 072. 求平方根 ### 
  [https://leetcode.cn/tag/randomized](https://leetcode.cn/problems/jJ0w9p/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数学·二分查找·
   ```c++ 
   while (begin<end-1){
     
   }
   // 最后需要判断 end 是否符合
   ```
- [x] ### 073. 狒狒吃香蕉 ### 
  [https://leetcode.cn/tag/binary-search](https://leetcode.cn/problems/nZZqjQ/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·二分查找·
   ```c++ 
   // 最大值
   std::max_element(vec.begin(),vec.end());
   ```
- [x] ### 074. 合并区间 ### 
  [https://leetcode.cn/tag/binary-search](https://leetcode.cn/problems/SsGoHC/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·排序·
   ```c++ 
   // 排序后用 priority_queue
   
   // 时间复杂度不佳
   ```
- [x] ### 075. 数组相对排序 ### 
  [https://leetcode.cn/tag/sorting](https://leetcode.cn/problems/0H97ZC/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·哈希表·计数排序·排序·
   ```c++ 
   // 注意，heap不是全排序的，set才是
   ```
- [x] ### 076. 数组中的第 k 大的数字 ### 
  [https://leetcode.cn/tag/sorting](https://leetcode.cn/problems/xx4gT2/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·分治·快速选择·排序·堆（优先队列）·
   ```c++ 
   // 快速排序
   int l = left;
   int r = right;
   while (l < r) {
   		while (nums[l] <= pivot && l < r) l++;
   		while (nums[r] >= pivot && l < r) r--;
   		swap(nums[l], nums[r]);
   }
   swap(nums[right], nums[r]);
   ```
- [x] ### 077. 链表排序 ### 
  [https://leetcode.cn/tag/heap-priority-queue](https://leetcode.cn/problems/7WHec2/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  链表·双指针·分治·排序·归并排序·
   ```c++ 
   Node* sort(){
     l = sort(left);
     r = sort(right);
     return merge(l, r);
   }
   ```
- [x] ### 078. 合并排序链表 ###
  
  [https://leetcode.cn/tag/merge-sort](https://leetcode.cn/problems/vvXgSW/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  链表·分治·堆（优先队列）·归并排序·
  
   ```c++ 
   // 
  
   ```
- [x] ### 079. 所有子集 ### 
  [https://leetcode.cn/tag/merge-sort](https://leetcode.cn/problems/TVdhkn/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  位运算·数组·回溯·
   ```c++ 
       void traverse(int cur_pos, vector<int> &nums, vector<int> &cur){
           if(cur_pos==nums.size()){
               vec.emplace_back(cur);
               return;
           }
           cur.emplace_back(nums[cur_pos]);
           traverse(cur_pos+1, nums, cur);
           cur.pop_back();
   
           traverse(cur_pos+1, nums, cur);
   
       }
   ```
- [x] ### 080. 含有 k 个元素的组合 ### 
  [https://leetcode.cn/tag/backtracking](https://leetcode.cn/problems/uUsW3B/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·回溯·
	 ```c++ 
	 
   ```
- [x] ### 081. 允许重复选择元素的组合 ### 
  [https://leetcode.cn/tag/backtracking](https://leetcode.cn/problems/Ygoe9J/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·回溯·
	 ```c++ 
	 
   ```
- [x] ### 082. 含有重复元素集合的组合 ###
  [https://leetcode.cn/tag/backtracking](https://leetcode.cn/problems/4sjJUc/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·回溯·
   ```c++ 
   // 如何在回溯时去重
   // bfs时，同一层不遍历重复的
   ```
- [x] ### 083. 没有重复元素集合的全排列 ###
  [https://leetcode.cn/tag/backtracking](https://leetcode.cn/problems/VvJkup/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·回溯·
   ```c++ 
   // dfs
   ```
- [x] ### 084. 含有重复元素集合的全排列 ### 
  [https://leetcode.cn/tag/backtracking](https://leetcode.cn/problems/7p8L0Z/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·回溯·
   ```c++ 
   // multimap 只能同时删除所有相同的元素
   ```
- [x] ### 085. 生成匹配的括号 ### 
  [https://leetcode.cn/tag/backtracking](https://leetcode.cn/problems/IDBivT/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  字符串·动态规划·回溯·
	 ```c++ 
	 
   ```
- [x] ### 086. 分割回文子字符串 ### 
  [https://leetcode.cn/tag/backtracking](https://leetcode.cn/problems/M99OJA/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  深度优先搜索·广度优先搜索·图·哈希表·
   ```c++ 
   // dp+记忆化搜索
   ```
- [x] ### 087. 复原 IP ### 
  [https://leetcode.cn/tag/hash-table](https://leetcode.cn/problems/0on3uN/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  字符串·回溯·
   ```c++ 
   
   ```
- [x] ### 088. 爬楼梯的最少成本 ### 
  [https://leetcode.cn/tag/backtracking](https://leetcode.cn/problems/GzCJIP/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·动态规划·
	 ```c++ 
	 
   ```
- [x] ### 089. 房屋偷盗 ###
  
  [https://leetcode.cn/tag/dynamic-programming](https://leetcode.cn/problems/Gu0c2T/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·动态规划·
   ```c++ 
   
   ```
- [x] ### 090. 环形房屋偷盗 ### 
  [https://leetcode.cn/tag/dynamic-programming](https://leetcode.cn/problems/PzWKhm/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·动态规划·
   ```c++ 
   // 两轮 dp，实质上也是dp
   ```
- [x] ### 091. 粉刷房子 ### 
  [https://leetcode.cn/tag/dynamic-programming](https://leetcode.cn/problems/JEj789/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·动态规划·
	 ```c++ 
	 
   ```
- [x] ### 092. 翻转字符 ### 
  [https://leetcode.cn/tag/dynamic-programming](https://leetcode.cn/problems/cyJERH/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  字符串·动态规划·
   ```c++ 
   // 注意多状态转移，如何设置dp的意义？
   ```
- [x] ### 093. 最长斐波那契数列 ### 
  [https://leetcode.cn/tag/dynamic-programming](https://leetcode.cn/problems/Q91FMA/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·哈希表·动态规划·
	 ```c++ 
	 // 二维dp
   ```
- [x] ### 094. 最少回文分割 ### 
  [https://leetcode.cn/tag/dynamic-programming](https://leetcode.cn/problems/omKAoA/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  字符串·动态规划·
	 ```c++ 
	 // 注意如何设置dp子问题
   ```
- [x] ### 095. 最长公共子序列 ### 
  [https://leetcode.cn/tag/dynamic-programming](https://leetcode.cn/problems/qJnOS7/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  字符串·动态规划·
   ```c++ 
   // TODO：压缩成一维dp
   ```
- [x] ### 096. 字符串交织 ### 
  [https://leetcode.cn/tag/dynamic-programming](https://leetcode.cn/problems/IY6buf/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  字符串·动态规划·
   ```c++ 
   // dp, 思考一下怎么设置子问题
   ```
- [x] ### 097. 子序列的数目 ### 
  [https://leetcode.cn/tag/dynamic-programming](https://leetcode.cn/problems/21dk04/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  字符串·动态规划·
   ```c++ 
   // 注意初始化
   ```
- [x] ### 098. 路径的数目 ### 
  [https://leetcode.cn/tag/dynamic-programming](https://leetcode.cn/problems/2AoeFn/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数学·动态规划·组合数学·
	 ```c++ 
	 // 2路转移
   ```
- [x] ### 099. 最小路径之和 ### 
  [https://leetcode.cn/tag/combinatorics](https://leetcode.cn/problems/0i0mDW/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·动态规划·矩阵·
	 ```c++ 
	 // 2路转移
   ```
- [x] ### 100. 三角形中最小路径之和 ### 
  [https://leetcode.cn/tag/matrix](https://leetcode.cn/problems/IlPe0q/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·动态规划·
	 ```c++ 
	 
   ```
- [x] ### 101. 分割等和子集 ###
  [https://leetcode.cn/tag/dynamic-programming](https://leetcode.cn/problems/NUPfPr/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数学·字符串·模拟·
   ```c++ 
   // 背包问题，注意 dp[i][j]表示什么
   ```
- [x] ### 102. 加减的目标值 ### 
  [https://leetcode.cn/tag/simulation](https://leetcode.cn/problems/YaVDxD/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·动态规划·回溯·
	 ```c++ 
	 
   ```
- [x] ### 103. 最少的硬币数目 ### 
  [https://leetcode.cn/tag/backtracking](https://leetcode.cn/problems/gaM7Ch/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  广度优先搜索·数组·动态规划·
   ```c++ 
   // 三重循环 dp
   ```
- [x] ### 104. 排列的数目 ### 
  [https://leetcode.cn/tag/dynamic-programming](https://leetcode.cn/problems/D0F0SV/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  数组·动态规划·
   ```c++ 
   // TODO：降维优化
   ```
- [x] ### 105. 岛屿的最大面积 ### 
  [https://leetcode.cn/tag/dynamic-programming](https://leetcode.cn/problems/ZL6zAn/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  深度优先搜索·广度优先搜索·并查集·数组·矩阵·
	 ```c++ 
	 
   ```
- [x] ### 106. 二分图 ### 
  [https://leetcode.cn/tag/matrix](https://leetcode.cn/problems/vEAB3K/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  深度优先搜索·广度优先搜索·并查集·图·
   ```c++ 
   // 需要考虑每一个联通分量
   // dfs染色
   ```
- [x] ### 107. 矩阵中的距离 ### 
  [https://leetcode.cn/tag/graph](https://leetcode.cn/problems/2bCMpM/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  广度优先搜索·数组·动态规划·矩阵·
   ```c++ 
   // 队列 bfs
   // 图搜索需要记录visited
   ```
- [x] ### 108. 单词演变 ### 
  [https://leetcode.cn/tag/matrix](https://leetcode.cn/problems/om3reC/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  广度优先搜索·哈希表·字符串·
   ```c++ 
   
   ```
- [x] ### 109. 开密码锁 ### 
  [https://leetcode.cn/tag/string](https://leetcode.cn/problems/zlDJc7/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  广度优先搜索·数组·哈希表·字符串·
   ```c++ 
   // 字符串操作复杂度太高，转换为int
   // 注意进位退位等问题
   ```
- [x] ### 110. 所有路径 ###
  [https://leetcode.cn/tag/string](https://leetcode.cn/problems/bP4bmD/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  深度优先搜索·广度优先搜索·图·回溯·
   ```c++ 
   // dfs 有向无环图
   // 不需要 visited？
   
   // dfs 用 stack 来记录路径
   ```
- [x] ### 111. 计算除法 ### 
  [https://leetcode.cn/tag/backtracking](https://leetcode.cn/problems/vlzXQL/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  深度优先搜索·广度优先搜索·并查集·图·数组·最短路·
   ```c++ 
   // make_pair
   vec.emplace_back(make_pair(v1,v2));
   
   // 注意图遍历的 visited 记录
   
   // 可以用 Floyd 算法优化
   ```
- [x] ### 112. 最长递增路径 ### 
  [https://leetcode.cn/tag/shortest-path](https://leetcode.cn/problems/fpTFWP/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  深度优先搜索·广度优先搜索·图·拓扑排序·记忆化搜索·数组·动态规划·矩阵·
   ```c++ 
   // no official way of computing hash on pair
   unordered_set<pair<int,int>>s; // error
   set<pair<int,int>> s; // √
   
   // 记忆化 dfs 复杂度高
   
   // todo：动态规划方法
   ```
- [x] ### 113. 课程顺序 ### 
  [https://leetcode.cn/tag/matrix](https://leetcode.cn/problems/QA2IGt/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  深度优先搜索·广度优先搜索·图·拓扑排序·
   ```c++ 
   // unordered_multimap
       auto range = map.equal_range(1);
       for (auto it = range.first; it != range.second; ++it) {
           std::cout << it->first << ' ' << it->second << '\n';
       }
   
   // 这题我写的bfs拓扑排序
   ```
- [x] ### 114. 外星文字典 ###
  
  [https://leetcode.cn/tag/topological-sort](https://leetcode.cn/problems/Jf1JuT/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
	深度优先搜索·广度优先搜索·图·拓扑排序·数组·字符串·
	 ```c++ 
   // 这题我写的dfs拓扑排序
   ```
- [x] ### 115. 重建序列 ### 
  [https://leetcode.cn/tag/string](https://leetcode.cn/problems/ur2n8P/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  图·拓扑排序·数组·
   ```c++ 
   // 拓扑排序然后对比
   
   // 邻接矩阵：vector<vector<int>>
   
   // 序列 [1,2,3] 只需要考虑 1<2, 2<3，为什么？因为偏序关系
   ```
- [x] ### 116. 省份数量 ### 
  [https://leetcode.cn/tag/array](https://leetcode.cn/problems/bLyHh0/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  深度优先搜索·广度优先搜索·并查集·图·
   ```c++ 
   // 并查集，可以优化
   void Union(vector<int> &par, int x, int y);
   void Find(vector<int> &par, int x);
   ```
- [x] ### 117. 相似的字符串 ###
  [https://leetcode.cn/tag/graph](https://leetcode.cn/problems/H6lPxb/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  深度优先搜索·广度优先搜索·并查集·数组·字符串·
   ```c++ 
   // 并查集
   // TODO：路经压缩
   ```
- [x] ### 118. 多余的边 ###
  [https://leetcode.cn/tag/string](https://leetcode.cn/problems/7LpjUW/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
  深度优先搜索·广度优先搜索·并查集·图·
   ```c++ 
   
   ```
- [x] ### 119. 最长连续序列 ###
	
	[https://leetcode.cn/tag/graph](https://leetcode.cn/problems/WhsWhI/?envType=study-plan&id=lcof-ii&plan=lcof&plan_progress=bxz2fei)
	并查集·数组·哈希表·
	
	 ```c++ 
	 // nlogn: sort+dp
	 
	 // n: unordered_map
   ```