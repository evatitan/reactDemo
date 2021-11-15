# reactDemo

## 一、TodoList 案例相关知识点
1. 拆分组件、实现静态组件，注意：className、style的写法。
2. 动态初始化列表，如何确定将数据放在哪个组件的state中？
  - 某个组件使用：放在其自身state中
  - 某些组件使用：放在其共同的父组件state中（官方称此操作为：状态提升）
3. 关于父子之间通信
  - 【父组件】给【子组件】传递数据：通过 props 传递
  - 【子组件】给【父组件】传递数据：通过 props 传递，要求父提前给子传递一个函数
4. 注意 defaultChecked 和 cheecked 的区别， 类似的还有： defaultValue 和 Value
5. 状态在哪里，操作状态的方法就在哪里。