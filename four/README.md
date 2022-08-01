## Задача 8: Напишите программу, которая на вход принимает число (N), а на выходе показывает все чётные числа от 1 до N.

+ 5 -> 2, 4
+ 8 -> 2, 4, 6, 8

___

``` C
int number = 5;

int count = 1;

while(count < number+1) {
    if (count%2 == 0)
    {
    Console.Write(count + ", ");
    count++ ;
    }
    else 
    {  
    count++ ;
    }
}


Console.WriteLine("");
number = 8;

count = 1;

while(count < number+1) {
    if (count%2 == 0)
    {
    Console.Write(count + ", ");
    count++ ;
    }
    else 
    {  
    count++ ;
    }
}
Console.WriteLine("");
```