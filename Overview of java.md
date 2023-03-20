# A overview of java
## Short example
类似于对象将状态存储在字段中的方式，方法通常将其临时状态储存在局部变量中。没有特殊的关键字将变量指定为局部变量，完全取决于变量被声明的位置，也就是一个方法的
大括号之内。局部变量只对声明他们的方法可见，这个类的其他部分无法访问局部变量。  
```
  class Example {
  public static void main(String args[]) {
    int num; // this declares a variable called num

    num = 100; // this assigns num the value 100

    System.out.println("This is num: " + num);

    num = num * 2;

    System.out.print("The value of num * 2 is ");
    System.out.println(num);
  }
}

```
