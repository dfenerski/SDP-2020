# Вектори и Дървета

## Task 0.1

Като използвате данните от nums.txt, извлечете числата от файла и ги запишете във вектор. След което премахнете числата от вектора във интервала [a, b], където а и b се въвеждат от потребителя. Сортирайте вектора в намаляващ ред, използвайки функцията от STL sort(). Запишете крайния резултат в файл.


## Task 0.2

Реализирайте кореново дърво, което съдържа като елементи символни низове (string), с произволен брой деца. Запазете указателите към децата във вектор. Като използвате данните от hierarchy.txt създайте дърво, което съответства на йерархията описана в текстовия файл. На всеки ред от файла е описано как се стига от корена на дървото до съответния низ (вижте примера как е форматиран реда). Ако някоя  от връзките от низа липсва в дървото добавете я. В противен случай ако съществува продължавате по нея. Да се изпише на екрана дървото като за всяко ниво n се слагат по 3(n-1) празни разстояния, така че да се получи йерахично изписване на екрана.
```
Вход:

Josh Adams->Mery Gosebery->Tomas Smith 
Josh Adams->Mery Goseberry->John Doe
Reichel Lore->Doroty Null
Reichel Lore->Rupert Smith
Josh Adams->Mery Gosebery->Tomas Smith->Ken Follet

Изход:
  Josh Adams
     Mery Gosebery
     Tomas Smith
         Ken Follet
Reichel Lore
   Doroty Null
   Rupert Smith
```

## Task 1

Имате файл students.txt където са записани данни за студенти от ФМИ. На всеки ред от файла са записани данните на един студент в следния формат <трите имена на студента>, <курс>, <среден успех>. Създайте подходяща структура за записите, прочетете ги  от файла и ги вкарайте в вектор. Премахнете всеки студент, чиито среден успех е по-малък от 3.00. Сортирайте в нарастващ вид обектите във вектора, използвайки sort(), първо по курс и после по среден успех. Запишете обектите във файл в същия формат.

## Task 2

В следващата задача нека дърветата, за които говорим да са обикновени, т.е. да имат не фиксиран брой деца и да не са сортирани по някакъв начин.

* Напишете функция, която по подадено дърво (корена на дървото), да връща дължината на дървото.
* Напишете функция, която по подадено дърво (корена на дървото), да връща броя елементи на дървото.
* Напишете функция, която по подадено дърво (корена на дървото), да трие самото дърво.
* Напишете функция, която по подадено дърво (корена на дървото) и цяло число, да проверява дали числото принадлежи на дървото и да връща указател към него. В противен случай да връща nullptr.