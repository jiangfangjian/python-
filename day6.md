#### 一、对于不变对象来说，调用对象自身的任意方法，也不会改变该对象自身的内容。相反，这些方法会创建新的对象并返回，这样，就保证了不可变对象本身永远是不可变的
- a = 'abc'
- a.replace('a', 'A')
- 'Abc'
- a
- 'abc'
#### 二、参数
- 1.位置参数：如power(x, n),按照位置依次赋值给参数x,n
- 2.默认参数：如power(x, n=2),n为默认参数
- 3.可变参数：如cal(*num),允许传入0个或者任意个参数，并且在函数调用时自动组成一个tuple
- 4.关键字参数:如person(name, age, **kw),允许你传入0个或任意个含参数名的参数，这些关键字参数在函数内部自动组装为一个dict
- 5.命名关键字参数:如person(name, age, *, city, job)或者person(name, age, *args, city, job)，命名关键字参数必须传入参数名，这和位置参数不同。如果没有传入参数名，调用将报错
