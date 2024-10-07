## Примери

**1.** Какво ще отпечата на екрана следният код?

```c++
#include <iostream>
int main()
{
    std::cout << (((false || ((!false && true) || 0)) && false) && 1);
}
```

**2.** Какво ще отпечата на екрана следният код?
```c++
#include <iostream>

int main()
{
    int first = 7;
    int second = 2;

    std::cout << 2 * first / (second * (25 / 10)) << std::endl;
    std::cout << 2 * first / (second * 2.5) << std::endl;
}

```

**3.** Какво ще отпечата на екрана следният код?

```c++
#include <iostream>
int main()
{
    double a = 5.02;
    double b = 4.99;
    int c = a + b;
    std::cout << c;
}
```

**4.** Какво ще се случи след компилиране на следния код?
```c++
#include <iostream>
int main()
{
    int num = 5;
    std::cout << ((num == 5) && (num >= 3) || (num / !num)) << std::endl;
}
```

## Задачи

**1.** Въвежда се цяло число. Отпечатайте 1, ако числото е четно и 0, ако е нечетно.

**Пример** 

Вход: 
```c++
198 
```
Изход:
```c++
1
```

**2.** От конзолата се прочитат две цели числа и се отпечатва частното и остатъка им.

**Пример** 

Вход: 
```c++
37
9
```
Изход:
```c++
4
1
```

**3.** Напишете програма, която обръща подадени градуси от Целзий (C) във Фаренхайт (F)! Формулата за това е: F = (9 / 5) * C + 32.

Вход: 
```c++
17
```
Изход:
```c++
62.6
```

**4.** Да се прочетат от конзолата 2 реални числа - дължина и широчина на правоъгълник. Да се изведе периметърът и лицето.

Вход: 
```c++
13
4.5
```
Изход:
```c++
35
58.5
```

**5.** Да се напише програма, която чете от конзолата цяло число - брой секунди, и изчислява колко дни, часове, минути и секунди са.


Вход: 
```c++
481 444
```
Изход:

```c++
5 days, 13 hours, 44 minutes and 4 seconds
```

**6.** Въвежа се цяло число. Да се отпечата без последната цифра.

Вход: 
```c++
6421
```
Изход:

```c++
642
```

**7.** Въвежа се цяло число. Да се отпечата 1, ако числото е валидна оценка от училище  - [2,6], a 0 - ако не е валидна.

Вход: 
```c++
5
```
Изход:

```c++
1
```

**8.** Дадени са ви 4 на брой цели числа - a, b, c, d. Да се изведе дали интервалите [a, b] и [c, d] се пресичат.

Вход: 
```c++
4 9
8 23
```
Изход:

```c++
1
```

**9.** Потребителя въвежда число n. Да се изведе сумата на числата от 1 до n

Вход: 
```c++
17
```
Изход:

```c++
153
```

**10.** Да се напише програма, която приема 4 цели числа и отпечатва 1, ако числата образуват геометрична прогресия в реда, в който са въведени, a 0 - ако съответно не образуват.

Вход: 
```c++
3 9 27 81
```
Изход:

```c++
1
```

**11.** Да се напише програма, която чете от конзолата 2 реални числа и разменя стойностите им без допълнителна промелнива.

**12.** Да се напише програма, която чете от конзолата 2 числа и извежда по-голямото от тях.

Вход: 
```c++
3.14
2.71
```
Изход:

```c++
3.14
```

**13.** Напишете програма, която приема цяло число и отпечатва числото, ако е двуцифрено, или последната му цифра, ако не е.

Вход:
```c++
19
```
Изход:
```c++
19
```
Вход:
```c++
1985
```
Изход:
```c++
5
```

**14.** От конзолата се въвеждат 5 цели числа. Да се изведе сумата на нечетните числа.

Вход:
```c++
4 9 19 6 5
```
Изход:
```c++
33
```

**15.** От конзолата се четат 3 реални числа. Да се изведе дали могат да бъдат страни на триъгълник.

Вход:
```c++
20 21 29 //pythagorean triplet
```
Изход:
```c++
1
```



## Бонус задачи

**\*** Потребителят въвежда число n. Да се изведе сборът на числата, които се делят на 3 и са по-малки или равни на n.

Вход:
```c++
15
```
Изход:
```c++
45
```

**\*\*** Въвежда се трицифрено цяло число n. Да се отпечата числото наобратно, събрано с единица.

Вход:
```c++
735
```
Изход:
```c++
538
```

**\*\*\*** Напишете програма, която приема цяло положително число и:

* Ако то е едноциферно - да се изпечатa.
* Ако то е двуцифрено - да се изпечатa последната му цифра събрана с 1.
* Във всеки друг случай - да се изпечатa цялото без последната цифра.

**Пример 1:**

Вход:
```c++
1234
```

Изход:
```c++
123
```

**Пример 2:**

Вход:
```c++
18
```

Изход:
```c++
9
```

**Пример 3:**

Вход:
```c++
6
```

Изход:
```c++
6
```