В проекте № 3 выполнить следующее:

1. Создать контейнер, содержащий объекты пользовательского типа. Тип контейнера map. Отсортировать его по убыванию элементов. Если алгоритмы не поддерживают заданный тип контейнера, написать свой алгоритм. Просмотреть контейнер. (Дополнительно: использовать 3 разных алгоритма сортировки из STL)

2. Используя подходящий алгоритм, найти в контейнере элемент, удовлетворяющий заданному условию. Использовать поиск с конца. (Дополнительно: используйте алгоритмы lower_bound и upper_bound)

3. Переместить элементы, удовлетворяющие заданному условию в другой (предварительно пустой) контейнер set (при перемещении элементов ассоциативного контейнера в не ассоциативный перемещаются только данные, ключи не перемещаются и наоборот, при перемещении элементов не ассоциативного контейнера в ассоциативный должен быть сформирован ключ). Просмотреть второй контейнер с конца через итераторы.

4. Отсортировать первый и второй контейнеры по возрастанию элементов. Просмотреть их. Найти k-тую порядковую статистику.

5. Получить третий контейнер путем слияния первых двух. Просмотреть третий контейнер.

6. Подсчитать, сколько элементов, удовлетворяющих заданному условию, содержит третий контейнер. Определить, есть ли в третьем контейнере элемент, удовлетворяющий заданному условию. (Дополнительно: используйте лямбды; используйте на контейнерах различные алгоритмы для работы с множествами(не менее двух))

7. Продемонстрировать работу со std::string — использовать не менее 3 разных конструкторов, а также конструктор копирования, перемещения. Использовать не менее трех специализированных методов, которые есть у string(вроде substr, split)/

8. Работа с функциональными объектами. Написать свой функтор, который принимает стандартный (из STL) функциональный объект. Применить внутри функтора библиотечный функциональный объект. Написать второй функциональный объект с отличным от первого кол-вом параметров. Использовать как минимум 2 различных биндера для их связки. Продемонстрировать их использование.
