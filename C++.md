### C++

1. 基类指针指向派生类  基类有虚函数 派生类重写 就指向派生类 ，不是虚函数 指向基类
2. 类指针指向空 可以安全调用不涉及成员变量的函数
3. 生成可执行文件顺序  预处理->编译->汇编->链接
4. 接受一个参数的构造函数允许赋值语句隐式调用初始化，explicit构造函数只能显式调用
5. 基类中说明了虚函数后，派生类中将其对应的函数可不必说明为虚函数
6. 默认构造函数分为三类 普通构造函数 无形参， 拷贝构造函数 左值引用& ，默认移动构造函数 右值引用&&
7. 运算符重载是多态的一种表现
7. malloc new 得到的存储区属于内存中的堆
7. 子类是指新类是继承父类，子类型必须是子类继承了父类的所有可继承特性，也即公有继承，才能说是子类型，否则就只是单纯的子类
7. 构造函数里初始化列表初始化顺序由成员变量的声明顺序决定
7. lambda 泛型 参数类型声明为auto           auto fun = [](auto a,auto b){return a+b;};
7. 只能通过new来创建 将析构函数设为私有
7. printf 从右往左编译
7. 构造函数不能声明为虚函数，析构函数可以
7. https://zhuanlan.zhihu.com/p/431714886
7. const class object 常对象 只能调用类的 const 成员
7. volatile 防止编译器优化  多线程应用中被几个任务共享的变量等等
7. volatile 的意思是让编译器每次操作该变量时一定要从内存中真正取出，而不是使用已经存在寄存器中的值
7. 若析构函数不为虚，则指向派生类对象的基类指针在delete时无法释放派生类对象，造成内存泄漏
7. 不能声明为虚函数的有:普通函数(非成员函数)、静态成员函数、内联成员函数、构造函数、友元函数
7. static 修饰的变量在类外初始化，static修饰的变量不能再构造函数里初始化，const修饰的在参数列表初始化
