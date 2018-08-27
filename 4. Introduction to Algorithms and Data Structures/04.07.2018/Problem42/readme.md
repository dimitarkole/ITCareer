﻿## 4. Уравновесен масив
Да се напише програма, която позволява да се въведе размер на масив и стойностите на неговите елементи и после го подрежда така, че стойностите на елементите да нарастват от началото до средата на масива и след това отново да намаляват от средата до края. Елементите от първата половина на масива не трябва да преминават във втората му половина. Полученият масив трябва да бъде отпечатан.

Вход
- Входните данни трябва да се прочетат от конзолата.
- На първия ред се подава цяло четно число N, съдържащо броят на числата в масива
- На втория ред се подават N цели числа, отделени едно от друго с интервал. Това са стойностите на елементите в масива.
- Входните данни винаги ще са валидни и в описания формат. Не е необходимо да бъдат изрично проверявани.

Изход
- Изходните данни ("уравновесеният" масив) трябва да бъдат отпечатани на конзолата.

| Вход                | Изход               |
| ------------------- | ------------------- |
| 10                  | 2 3 4 6 8 9 7 4 2 1 |
| 4 2 6 3 8 1 7 4 2 9 |	                    |

## 5. Сортиране по произволна колона
Напишете програма, която сортира таблица от числови стойности по произволна колона.

Вход
- Входните данни трябва да се прочетат от конзолата.
- На първия ще ви бъдат подадени три цели числа R, C и S, разделени с интервал. R e броят на редовете в таблицата, C - броят на колоните, a S - номерът на колоната, по която трябва да бъде сортиран масива. 
- На следващите R реда ще са числата от всеки от редовете в таблицата, C на брой, разделени с интервали.
- Входните данни винаги ще са валидни и в описания формат. 

Изход
- Изходните данни трябва да бъдат отпечатани на конзолата.
- На R реда трябва да бъдат изведени числата от таблицата, сортирани по указаната колона.		 

Подсказки
- Ще се наложи да ползвате двумерен масив или масив от масиви.
- Тествайте задачата с различно големи масиви и различни алгоритми за сортиране. 
- Обърнете внимание дали при стабилни и нестабилни алгоритми се получава еднакъв резултат.
- Коментирайте в клас има ли начин за минимизиране на размяната на редовете при сортирането. 

| Вход    | Изход   |
| ------- | ------- |
| 3 4 1   | 1 2 3 4 |
| 1 2 3 4 | 2 3 1 2 |
| 3 1 2 4 | 3 1 2 4 |
| 2 3 1 2 |         |
| ------- | ------- |
| 4 2 2   | 3 1     |
| 1 2     | 1 2     |
| 3 1     | 2 3     |
| 2 3     | 4 4     |
| 4 4     |         |