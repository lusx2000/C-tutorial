```c
switch

编程实现简单的计算器功能，要求用户按如下格式从键盘输入算式：
操作数1  运算符op  操作数2
计算并输出表达式的值，其中算术运算符包括：加（+）、减（-）、乘（*）、除（/）、^(次幂）。
要求使其能进行浮点数的算术运算，同时允许使用字符*、x与X作为乘号，并且允许输入的算术表达式中的操作数和运算符之间可以加入任意多个空格符。 
**输入格式要求："%f %c%f" 提示信息："Please enter the expression:\n"
**输出格式要求："%f + %f = %f \n" "%f - %f = %f \n" "%f * %f = %f \n" "%f / %f = %f \n" "Division by zero!\n"  "%f ^ %f = %f \n" "Invalid operator! \n"
程序运行示例1如下：
Please enter the expression: 2.0 + 4.0
2.000000 + 4.000000 = 6.000000
程序运行示例2如下：
Please enter the expression: 2.0 - 4.0
2.000000 - 4.000000 = -2.000000
程序运行示例3如下：
Please enter the expression: 2.0 * 4.0
2.000000 * 4.000000 = 8.000000
程序运行示例4如下：
Please enter the expression: 2.0 x 4.0
2.000000 * 4.000000 = 8.000000
程序运行示例5如下：
Please enter the expression: 2.0 X 4.0
2.000000 * 4.000000 = 8.000000
程序运行示例6如下：
Please enter the expression: 2.0 / 4.0
2.000000 / 4.000000 = 0.5000000
程序运行示例7如下：
Please enter the expression: 2.0 / 0
Division by zero! 
程序运行示例8如下：
Please enter the expression:2.0 ^5.0
2.000000 ^ 5.000000 = 32.000000 
程序运行示例9如下：
Please enter the expression: 2.0 \ 4.0
Invalid operator!
```

```c
用do while语句编程，输入一组整型数据，然后显示每次将输入数据进行累加运算后的结果。当输入0时，停止输入数据，结束程序的运行。
**输入格式要求："%d" 提示信息："Input num:"
**输出格式要求："sum = %d\n"
程序运行示例如下：
Input num:1
sum = 1
Input num:2
sum = 3
Input num:3
sum = 6
Input num:4
sum = 10
Input num:0
sum = 10
```

```c
从键盘任意输入a，b，c的值，编程计算并输出一元二次方程ax2+bx+c=0的根。根据一元二次方程的求根公式，令
p=−b2a,q=∣∣b2−4ac∣∣√2a
当b2−4ac=0时，输出两个相等的实根x1=x2=p；当b2−4ac>0时，输出两个不相等的实根：x1=p+q，x2=p−q；当b2−4ac<0时，输出一对共轭复根：x1=p+qi，x2=p−qi。当a=0时，输出"It is not a quadratic equation!\n"。

**输入格式要求："%f,%f,%f" 提示信息："Please enter the coefficients a,b,c:"
**输出格式要求：
相等实根: "x1 = x2 = %.2f\n"
不相等的实根: "x1 = %.2f, x2 = %.2f\n"
一对共轭复根: "x1 = %.2f+%.2fi, x2 = %.2f-%.2fi\n"

程序运行示例如下：
Please enter a,b,c: 0,10,2
It is not a quadratic equation!

```

```c
从键盘输入n，然后计算并输出1～n之间的所有数的阶乘值。
**输入格式要求："%d" 提示信息："Please enter n:"
**输出格式要求："%d! = %ld\n"
程序运行示例如下：
Please enter n:10
1! = 1
2! = 2
3! = 6
4! = 24
5! = 120
6! = 720
7! = 5040
8! = 40320
9! = 362880
10! = 3628800
```

```c
下面程序用于计算两个正整数的最小公倍数。 (改错)
#include <stdio.h>
 
int MinCommonMultiple(int a, int b)
 
main()
{
    int a, b, x;
 
    printf("Input a,b:");
    scanf("%d,%d",&a,&b);    
 
    x = MinCommonMultiple(int a,int b);
    printf("MinCommonMultiple = %d\n", x);
}
 
int MinCommonMultiple(int a, int b);   
{
    int i;
 
    for (i=1; i<b; i++)
    {
        if ((i*a) % b = 0)       
            return i*a;
    }
return 0;   
}
```

```c
编程将字符串s倒序输出，要求利用函数递归实现。
**输入格式要求："%s" 提示信息："input your string:\n"
**输出格式要求："%c"
程序运行的输入输出样例：
屏幕先输出提示信息：
input your string:
然后用户键盘输入：
abcdefg   
最后屏幕输出：
gfedcba
```

