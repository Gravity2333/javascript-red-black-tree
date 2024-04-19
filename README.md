# js-red-black-tree
一个Javascript实现的红黑树
使用方式：
npm install js-red-black-tree

```javascript
import RBTree from "js-red-black-tree";

const rbTree = new RBTree()
rbTree.insert(6);
rbTree.insert(2);
rbTree.insert(15);
rbTree.insert(10);
rbTree.insert(18);
rbTree.insert(12);
rbTree.search(6);
rbTree.inOrderTraversal();
console.log(rbTree.min(), rbTree.max());
```