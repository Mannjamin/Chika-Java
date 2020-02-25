# Chika-Java
A basic Java executable for demonstrating the Chika Formula for checking if an Integer is a multiple of seven.

## The Chika Formula
1.  Take the last digit of any whole number.
2.  Multiply it by 5.
3.  Add this to the remaining part of the number, you will get a new number.
4.  If this new number is divisible by 7, then the original number is divisible by 7.

## How it works
1.  Open any preferred console in the directory containing the jar file.
2.  Write into the console `java -jar chika.jar [INSERT INTEGER]`
>  We assume anyone using this Jar file will already have Java installed on their system.

>  Futhermore, we assume anyone using Windows 10, has added Java to PATH for command prompt / powershell / bash

## Example
```
java -jar chika.jar 2996

Input: 2996
299 + 6 x 5 = 329
32 + 9 x 5 = 77
7 + 7 x 5 = 42
4 + 2 x 5 = 14
1 + 4 x 5 = 21
2 + 1 x 5 = 7
Input is a multiple of 7!
```

## Reference:
[Nigerian Kid, Chika, Propounds New Maths Formula, Recognised By UK School](https://allafrica.com/stories/201911130037.html "Nigerian Kid, Chika, Propounds New Maths Formula, Recognised By UK School")
