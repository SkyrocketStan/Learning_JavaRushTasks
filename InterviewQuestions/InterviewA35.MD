## 35. Какие ограничения есть у локальных классов?

Локальный класс наделён особенностями внутренних классов, но имеет отличительные черты, а именно:

1. Локальный класс имеет доступ только к финальным полям и аргументам обрамляющего метода, а также ко всем 
полям обрамляющего класса, в том числе приватным и статическим;
2. Локальный класс виден и может создаваться только в блоке, в котором описан;
3. У локального класса не ставится модификатор доступа;
4. Локальный класс не может иметь статических полей, методов, классов (за исключением финальных);
5. Локальный класс, объявленный в статическом блоке может обращаться только к статическим полям 
внешнего класса.