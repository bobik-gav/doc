Основы Питон
===============
Коментарии в Питон
"""""""""""""""""""
Комментарии в Python
.. image:: http://mowshon.ru/page/kommentarii-v-python

Как говорил один умный программист "Код должен быть написан так, чтобы он сам был документацией к себе". Слова правильные, но истолковать их правильно не все сумеют. Читать мысли других программистов и гадать, что он там имел в веду нам не очень нравится. Чтобы избавить читателей Вашего кода от мук, мы научимся правильно составлять комментарии к своему коду на Python.

В Python все комментарии начинаются с символа # и все они они являются однострочными. В качестве многострочного комментария мы будем пользоваться строками документирования т.е. мы разместим код в утроенных кавычках.

Ниже я приведу несколько примеров комментариев на Python.
# Обычный текст комментария


my_var = 'Hi, Mowshon!' # Описываем переменную
# your_var = 'read' - в данном случае код не выполняется т.к. символ # в начале строки
# Обычный текст комментария
my_var = 'Hi, Mowshon!' # Описываем переменную
# your_var = 'read' - в данном случае код не выполняется т.к. символ # в начале строки
Теперь попробуем написать псевдо-многострочный комментарий
""""


1. 1. Я тоже комментарии
расположенный на
несколько строк
""""
Почему же выше мы его назвали "строки документирования" ?
- Дело в том, что обычно такой подход применяется для комментирования функции, модулей, классов изнутри.

# -*- coding: utf-8 -*-
def my_function(number):
    """
    Переменная number дожно содержать целое число
    """
    return number
Теперь чтобы получить содержание комментария внутри функции достаточно выполнить
print(my_function.__doc__)
В Python вопрос о комментариях пожалуй самый простой, двигаемся далее к чему-то более сложному. Задавайте вопросы в комментариях - с радостью объясню непонятные моменты.
Еще записи по теме
Открываю раздел о Python
