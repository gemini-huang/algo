
# 操作链表
1. 单链表反转
1. 链表中环的检测
1. 两个有序的链表合并
1. 删除链表倒数第 n 个结点
1. 求链表的中间结点

## 回文字判断
> 什么是回文字符串
如：abba, 从前读到尾和从尾读取前都是一样的.
abcba, aviva 都是回文字

提供三种解题思路:
1. 第一种是借用一个栈, 将一半的数据存入栈中, 后半部分与出栈的元素比较.
2. 第二种二个指针向中间逼近
3. 第三种也是使用二个指针,先从中间开始向左右扩散