### Бързи клавиши във Visual Studio

За ваше удобство има **бързи клавиши във Visual Studio**, за които ще обясним по-късно в настоящата глава, но засега ни интересуват 2 конкретни комбинации. Едната комбинация е за форматиране на **кода в целия документ**, а другата комбинация - за форматиране на **част от кода**. Ако искаме да форматираме **целия код**, то трябва да натиснем [**CTRL + K + D**]. В случай, че искаме да форматираме само **част от кода**, то ние трябва да **маркираме с мишката частта**, която искаме да форматираме, и да натиснем [**CTRL + K + F**].

Нека използваме **грешния пример** от преди малко:

```csharp
for(int i=0;i<5;i++){
Console.WriteLine(i);
}
```
Ако натиснем [**CTRL + K + D**], което е нашата комбинация за форматиране на **целия документ**, ще получим код, форматиран според **общоприетите конвенции за C#**, който ще изглежда по следния начин:

```csharp
for (int i = 0; i < 5; i++)
{
    Console.WriteLine(i);
}
```
Тази комбинация може да ни помогне, ако попаднем на лошо форматиран код.