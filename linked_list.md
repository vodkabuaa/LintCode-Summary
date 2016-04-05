1.Convert Sorted List to Balanced BST

思路：这里面可以通过求整体长度，以及长度位置与节点的关系，通过divide and conquer的方式来完成求解。

注意：helper函数中记得要传入指针引用，否则传入的仍然是之前的head位置。


2.Copy List with Random Pointer

利用hashtable。 遍历两遍，第一遍记录每个节点的正常指针，并将节点本身存储到hashtable中。第二遍遍历更改节点中随机指针指向的位置

3.Linked List Cycle

跑到相遇位置，第一次停止。然后慢指针从开头再跑一次

http://javabypatel.blogspot.in/2015/12/detect-loop-in-linked-list.html
