// Напишите программу, которая на вход принимает два числа и выдаёт, какое число большее, а какое меньшее.
//a = 5; b = 7 -> max = 7
//a = 2 b = 10 -> max = 10
//a = -9 b = -3 -> max = -3
Console.WriteLine("Enter the first number");
int one1=Convert.ToInt32(Console.ReadLine());
Console.WriteLine("Enter the second number");
int two2=Convert.ToInt32(Console.ReadLine());
 int index=0;
 if (one1>two2)
 {
    index=one1;
    Console.WriteLine(index);
 }
 else if (one1<two2)
 {
    index=two2;
    Console.WriteLine(index);
 }
 else
 {
    Console.WriteLine("The numbers are equal");
 }
 //Напишите программу, которая принимает на вход три числа и выдаёт максимальное из этих чисел.
//2, 3, 7 -> 7
//44 5 78 -> 78
//22 3 9 -> 22

 Console.WriteLine("Enter The first number");
 int gif1=Convert.ToInt32(Console.ReadLine());

 Console.WriteLine("Enter The second number");
 int gif2=Convert.ToInt32(Console.ReadLine());

 Console.WriteLine("Enter The Third number");
 int gif3=Convert.ToInt32(Console.ReadLine());

 int index=gif1;

 if (gif1>index)
 {
    gif1=index;
 }
 if (gif2>index)
 {
    gif2=index;
 }
 if (gif3>index)
 {
    gif3=index;
 }
 Console.WriteLine(index);

 // Напишите программу, которая на вход принимает число и выдаёт, является ли число чётным (делится ли оно на два без остатка).
//4 -> да
//-3 -> нет
//7 -> нет
Console.WriteLine("Введите число");
int num1=Convert.ToInt32(Console.ReadLine());
int result=num1%2;
if (result==0)
{
    Console.WriteLine("Yes");
}
else 
{
    Console.WriteLine("No");
}

//Напишите программу, которая на вход принимает число (N), а на выходе показывает все чётные числа от 1 до N.
//5 -> 2, 4
//8 -> 2, 4, 6, 8
Console.WriteLine("Введите число");
int rumb=Convert.ToInt32(Console.ReadLine());
int index=2;
if (rumb>1)
{
    while(index<=rumb)
    {
        Console.WriteLine(index);
        index=index+2;
    }
}
