<h1>组合模式</h1>

组合模式也叫做合成模式，有时也叫做部分与整体模式，主要是用来描述部分与整体的关系。

例如 将对象组合成树形结构以表示 "部分-整体"的层次结构，使得用户对单个对象和组合对象的使用具有一致性

<li>角色</li>
1。component抽象构件角色：定义参加组合对象的共有方法和属性，可以定义一些默认的行为或属性
2。Leaf叶子节点：叶子对象，其下再也没有其他的分支，也就是遍历的最小单位
3。composite树支构件：树枝对象，作用是组合树枝节点和叶子节点形成一个树形结构


透明组合模式 和 安全组合模式的区别在于component角色的访问权限，树枝上的功能是否暴露出来，注意树叶节点的兼容
安全模式则是树枝节点的特定功能不外露。
