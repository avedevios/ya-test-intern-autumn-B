# B. Путешествие контейнера

- Ограничение времени	2 секунды
- Ограничение памяти	256Mb
- Ввод	стандартный ввод или input.txt
- Вывод	стандартный вывод или output.txt

Компания SeaTrail занимается грузоперевозкой. Для большей сохранности перевозимых вещей каждый товар упаковывается в индивидуальный контейнер. Для удобства транспортировки и загрузки он имеет кубическую форму.

Компания выпускает новый индивидуальный контейнер класса B. Для этого она заказала справочник грузов и их габаритов, в котором данные приведены списком в формате «название_груза; ширина; высота; длина».

По стандартам компании, контейнер класса B должен подходить минимум для половины товаров. Так как место в грузовике ограничено, компания хочет минимизировать занимаемый одним контейнером объем, чтобы иметь возможность перевозить больше товаров. Вычислите минимальную длину ребра контейнера, который будет удовлетворять стандартам компании.
## Формат ввода

В первой строке содержится 
n
1
≤
n
≤
1
0
5
 - количество товаров в каталоге. В следующих 
n
строках содержится строка 
n
a
m
e
 - название груза (строка до 20 символов латинского алфавита) и три числа 
w
h
l
 - ширина, высота и длина соответственно 
1
≤
w
,
h
,
l
≤
1
0
9
## Формат вывода

В единственной строке выведите минимальную длину ребра контейнера, удовлетворяющего условию задачи.
### Пример

**Ввод**

3

bed 150 50 230

tv 20 20 30

PC 10 40 30

**Вывод**

40
