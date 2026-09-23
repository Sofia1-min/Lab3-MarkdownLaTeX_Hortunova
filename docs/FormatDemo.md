# Задание: Комментированная программа на C#

Создайте консольное приложение на C#, которое демонстрирует все форматы Markdown в комментариях к коду

## Требования к программе:

1. Имя файла: FormatDemo.cs

2. Логика:
- Запрашивает у пользователя два числа
- Выполняет их сложение
- Выводит результаты в форматированном виде

## Пример структуры кода с комментариями в стиле Markdown:

```csharp
Console.WriteLine("Введите первое число: ");
double number1 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("Введите второе число: ");
double number2 = Convert.ToDouble(Console.ReadLine());
double sum = number1 + number2;
Console.WriteLine($"**Результаты операций: {sum}**");
```