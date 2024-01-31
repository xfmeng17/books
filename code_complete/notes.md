# CodeComplete2 读书笔记

## 摘抄

1. 准确使用对账词(7.3 Good Routine Names)

 - add/remove
 - begin/end    
 - create/destory
 - first/last
 - get/put
 - get/set
 - increment/decrement
 - insert/delete
 - locl/unlock
 - min/max
 - next/previous
 - old/new
 - open/close
 - show/hide
 - source/target
 - start/stop
 - up/down

2. 变量初始化原则(10.3 Guidelines for Initializing Variables)

 - Principle of Proximity 把相关的操作放在一起
 - Named Constant 具名常量，在程序运行期间其值不能改变的标识符，通常变量名使用大写

3. 混合耦合(10.8 Using Each Variable for Exactly One Purpose)

 - hybrid coupling 混合耦合，一个变量两种用户，比如 uint32_t page_count = -1 时意味着错误


