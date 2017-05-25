# Math-Operators
There are five total math operators in C# and they are +, -, *, /, and %.
The adding operator is simple, for example:
int x = 46 + 7;
Console.WriteLine(x);
//outputs 53
The subtracting operator is also simple, for example:
int x = 6 - 4;
Console.WriteLine(x);
//outputs 2
The multiplication operator is straight forward as well, for example:
int x = 4 * 4;
Console.WriteLine(x);
//outputs 16
The division operator is a little more tricky. It has to be a whole number/integer, so if you divide 16/6 the output would be 2. You disregard the remainder, for example:
int x = 10 / 3;
Console.WriteLine(x);
//outputs 3
The modulus operator is also a little tricky. It now takes the remainder of division and disregards the whole number/integer. So if you divide 16/6 the output would be 4, which is the remainder. For example:
int x = 25 % 3;
Console.WriteLine(x);
//outputs 1
You can also combine operators into one equation (order does matter), for example:
int x = 5 - 6 + 4;
Console.WriteLine(x);
//outputs 3
int x = 6 * 7 + 3;
Console.WriteLine(x);
//outputs 46
There are also increments and decrements in C#, for example:
x++;   //same as x = x + 1
x--;   //same as x = x - 1;
You can also simplify adding and subtracting operators, for example:
int x = 23;
x += 3;   //outputs 23 + 3 = 26
x -= 3;   //outputs 23 - 3 = 20
