# 2. Зачем нужны методы equals & hashCode?

> .equals()
 
Сравнивает два объекта на предмет их равнозначности. 
По умолчанию сравнивает хешкоды. 
Метод переопределяется и в нем можно сравнивать, например, значения всех полей объекта.


> .hashCode() 

Возвращает хэшкод объекта. 

Так же может переопределяться.
Например, можно сделать так, что два объекта с абсолютно одинаковыми значениями полей
будут возвращать одинаковый хеш.

Некоторые методы проверяют хешкод перед тем, как сделать проверку на .equals 
чтобы не тратить на него время если этот код одинаков.  
 