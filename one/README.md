## Задача 2: Напишите программу, которая на вход принимает два числа и выдаёт, какое число большее, а какое меньшее.

+ a = 5; b = 7 -> max = 7
+ a = 2 b = 10 -> max = 10
+ a = -9 b = -3 -> max = -3

___

``` C
int a = 5;
int b = 7;

if (a > b) 
{
    Console.WriteLine("max = " + a);
}
else
{
    Console.WriteLine("max = " + b);
}

a = 2;
b = 10;

if (a > b) 
{
    Console.WriteLine("max = " + a);
}
else
{
    Console.WriteLine("max = " + b);
}

a = -9;
b = -3;

if (a > b) 
{
    Console.WriteLine("max = " + a);
}
else
{
    Console.WriteLine("max = " + b);
}
```