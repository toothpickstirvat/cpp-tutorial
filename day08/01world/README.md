# 非虚的世界

* 对象的自洽性
    * 对同样的函数调用，每个对象都会做出恰当的响应
* 通过指向子类对象的基类指针调用函数
    * 只能调用基类的成员函数，虽然指针指向子类对象
    * 一旦调用子类所特有的成员函数，将引发编译错误
* 通过指向基类对象的子类指针调用函数
    * 可以调用子类的成员函数，尽管指针指向基类对象
    * 直接或间接地访问子类的成员变量，后果不可预知
* 名字隐藏
    * 子类成员函数隐藏基类的同名成员函数















