# 7. В чем отличие final, finally, finalize?

> final - Ключевое слово, модификатор доступа. 

Означает что изменения ссылки на объект невозможны.

Класс не может быть наследован. Переменная будет ссылаться только на одну ячейку памяти и не 
будет изменена. Но значение в этой ячейке поменять можно.

[Почитать на джавараше](https://javarush.ru/groups/posts/591-vot-tak-final)


> finally - ключевое слово, использующееся в конструкции try-catch-finally 

Включает в себя код, который должен выполниться в любом случае: возникло исключение или нет. 
Обычно в finally закрываются ресурсы. 
Начиная с Java 7 вместо finally можно использовать try-with-resourses.
 
> finalize - Метод вызываемый сборщиком мусора перед уничтожением объекта.
> Используется для освобождения ресурсов.
