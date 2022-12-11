Мінімальна площа опор
====

### **Опис**

Цей параметр визначає мінімально допустимий розмір опор. Якщо частина опори має меншу площу, ніж значення цього параметра на певному шарі, вона залишається.

![No filtering on area (minimum area is 0)](../images/minimum_support_area_0.png)
![Small pieces of support are left out](../images/minimum_support_area_10.png)

Тонкі опори схильні до перекидання. Вони також, як правило, підтримують невеликі елементи, які, ймовірно, добре друкуватимуться без підтримки. Якщо опора перекинеться, на деталі залишиться багато плям. Тому, можливо, краще залишити ці тонкі опори. Цей параметр дає змогу відфільтрувати опори за площею поперечного перерізу опори.

### **Вплив**

Збільшення площі зменшить кількість надрукованої підтримки, дещо скоротивши час і використання матеріалів. Що ще важливіше, це підвищує надійність друку, оскільки зменшується ймовірність перекидання опорних колон. Однак це також усуне підтримку дрібних елементів у вашій моделі, тому якість друку виступів може погіршитися для цих частин.

Для деяких форм це може мати неприємний побічний ефект у вигляді видалення верхньої частини опори, якщо верхня частина опускається нижче порогової області, а нижня – ні. Це може залишити деякі частини без підтримок там де ви зазвичай їх очікуєте.

![The tip of the arc is not supported because the area on those layers is too small](../images/minimum_support_area_problem.png)