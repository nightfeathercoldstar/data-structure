#### 查找二叉树：
定义：
- 每个结点都有一个值key
- 对于每一个结点：
	- 左子树所有结点的值都要小于该结点的值
	- 右子树所有检点的值都要大于该节点的值

特点：
- 快速查找：查找、删除、插入的平均时间复杂度为O(logn)
- 有序性：中序遍历BST可以得到一个有序的节点值序列



样例：
```markdown
        5
       / \
      3   7
     / \   \
    2   4   8
```


#### 判定树：
（可以体现决策性）
```markdown
          是否有工作
         /          \
       是            否
      /               \
    信用良好        信用差
    /      \          |
   是       否       拒绝
  /          \
 通过        拒绝
```
