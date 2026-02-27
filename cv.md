# **РЕЗЮМЕ**

### _Содержание_

- [_Контактная информация_](https://htmlacademy.ru)

- [_О себе_](https://htmlacademy.ru)

- [_Навыки_](https://htmlacademy.ru)

- [_Инструменты разработки_](https://htmlacademy.ru)

- [_Пример кода_](https://htmlacademy.ru)

![Я](ya.jpg)
![ещея](yyyy.jpg)
![тожея](my_photo.jpg)

# **Листратенко Анастасия Сергеевна**

## 1. Контактная информация:

- Номер телефона: +375255037408

- Email: nlisenko117@gmail.com

- Telegram: Anastasia Listratenko

## 2. О себе:

> Моя главная цель — профессиональное развитие в сфере современных технологий и медиа. Я ставлю в приоритет качество выполняемой работы, дисциплину и постоянное расширение кругозора.

## 3. Навыки:

- Языки программирования: C# (базовые знания: ООП, классы, методы), HTML5 (разметка структуры страниц).

- Инструменты разработки: Visual Studio / VS Code

- Дополнительно: Опыт работы в команде и создание контента в рамках BRU-MEDIA (Фотографии, видео, монтаж).

## 4. Опыт работ:

![Награждение](my_photo_moscow.jpg)

Награждение в Москве на конкурсе Образование послезавтра в 2024 году

## 5. Пример кода:

```
using System;

class Program
{
    static void Main()
    {
        int[] nums = { 5, 2, 8, 1, 9 };

        for (int i = 0; i &lt; nums.Length - 1; i++)
        {
            for (int j = 0; j &lt; nums.Length - i - 1; j++)
            {
                if (nums[j] > nums[j + 1])
                {
                    int temp = nums[j];
                    nums[j] = nums[j + 1];
                    nums[j + 1] = temp;
                }
            }
        }

        Console.WriteLine("Отсортированный массив:");
        foreach (int n in nums) Console.Write(n + " ");
    }
}
```
