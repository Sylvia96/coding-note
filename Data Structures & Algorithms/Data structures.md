# Data structures

[Data Structures & Algorithms #1 - What Are Data Structures?](https://www.youtube.com/watch?v=bum_19loj9A)

[300分钟实现数据结构与算法全掌握](https://www.bilibili.com/video/BV1DT4y1G7ha?from=search&seid=1258024095126319528)

![Alt Text](https://github.com/Sylvia96/coding-notes/blob/master/Data%20Structures%20&%20Algorithms/%E6%88%AA%E5%B1%8F2020-06-02%E4%B8%8A%E5%8D%881.28.47.png?raw=true)

## Common data structures
* **Array & String（数组与字符串）**

*Convert a string to an array, and operate on **each character** in the string*

**Pros:**

*simple*

*O(1): Query by index*

**Cons:**

*continuous space*

*O(n): (Query if a[n] exists -> traverse the whole array) / (Add/delete a[n])*

*Example: 字符串t是否为s的字母异位词 ——— 假设字符串只包含小写字母 —> 两个长度为26的字符数组统计每个字符串中小写字符出现的次数/一个长度为26的字符数组，出现在s中的字符+1，出现在t中的字符-1，判断最后是否为0*

* **Linked list（链表）**

*单链表、双链表*

**Pros：**

*避免数组的一大缺陷，即分类数组时需开辟一段连续的内存空间（灵活分配内存空间）*

*O(1): Add/delete*

**Cons：**

*O(n): Query 不能通过下标进行快速查询（想好自己是否需要频繁的查询和遍历），每次都要从链表的头开始一个一个读取*

>数据元素个数不确定且经常需要进行添加和删除 -> 链表合适

>数据元素大小确定，删除插入操作并不多 -> 数组合适

- [x] skills: fast/slow pointers (prev, curr, next); false linked list head; draw it!

* **Stack（栈）** hard

*LIFO*

*Basic idea: realized by a single linked list; care only about the last operation; O(1): find the last one of the last operation when you finished the last operation*

* **Queue（队列）**

*FIFO*

*commonly used in 广度优先搜索*

* **Deque（双端队列）**

*use a double linked list; 队列头尾两端能在O(1)时间内进行数据的查看、添加和删除*

*commonly used in 实现一个长度动态变化的窗口或连续区间*

* **Tree（树）** the most important

*Intuitive structure*

*Recursive algorithm(递归算法)*

*面试常考：普通二叉树、平衡二叉树、完全二叉树、二叉搜索树(important)、四叉树、多叉树*

*Traversal: preorder (root-left-right): 树里搜索或创建一颗新树; inorder (left-root-right): 二叉搜索树; postorder (left-right-root)*

## Advanced data structures

* **Priority Oueue(优先队列)**
* **Graph(图)**
* **Trie(前缀树)**
* **Segment Tree(线段树)**
* **Fenwick Tree / Binary Indexed Tree(树状数组)**
