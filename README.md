<h1>Материалы по курсу "Практикум по программированию на языке Python"</h1>

Курс преподаётся студентам третьего года обучения кафедры ИАД факультета ФУПМ МФТИ (ГУ).

__Автор:__ Мурат Апишев ([facebook](https://www.facebook.com/great.mel), [machinelearning.ru](http://www.machinelearning.ru/wiki/index.php?title=Участник:Mapishev))

__Правила курса__:

- Курс проводится в формате "лекции + практические задания"
- Зачёт по курсу выставляется по результатам выполнения заданий
- Для доступа к зачёту необходимо выполнить __все__ практические задания и получить за них в сумме __не менее 35 баллов__. Форма самого зачёта будет определена в дальнейшем, для гарантированного получения зачёта автоматом нужно набрать в сумме __не менее 45 баллов__.

<h4>Результаты выполнения практических заданий:</h4>

- [Задание 1](https://docs.google.com/spreadsheets/d/1xnf1n7dusbb_k_USNXhCHTvQxmhcNIgyX6LaluCg2ek/edit?usp=sharing)

<h2>Занятие 1: Введение в язык программирования Python</h2>

<h4>Содержание:</h4>

- мотивация изучения языка
- язык Python, история, особенности, сравнение с другими языками
- основной дистрибутив, редакторы
- запуск скриптов
- введение в язык, базовый синтаксис
- оператор вывода, ввод с клавиатуры
- понятия объекта, переменной и типа
- операторы присваивания
- встроенные неизменяемые типы данных: числа, строки, кортежи
- встроенные изменяемые типы данных: списки, словари, множества
- работа с файлами, файловый менеджер контекста
- условный оператор, тернарный условный оператор
- операторы циклов while и for, операторы break, continue, else, pass
- именование переменных
- импорт модулей
- функции exec и eval

<h4>Ссылки на лекцию:</h4>

- [PDF](https://github.com/MelLain/mipt-python/blob/master/lectures/pdf/mel-lain-mipt-python-intro.pdf)
- [Jupyter Notebook](https://github.com/MelLain/mipt-python/blob/master/lectures/src/mel-lain-mipt-python-intro.ipynb)

<h2>Занятие 2: Модель памяти, операции над встроенными типами данных</h2>

<h4>Содержание:</h4>

- стадии жизни объекта
- сборщик мусора, циклические и слабые ссылки, гарантии
- изменяемые и неизменяемые объекты, ссылки на них
- поверхностное и глубокое копирование
- идентификатор объекта, операторы равенства и идентичности
- атрибуты объекта, функция dir
- числовые типы данных
- побитовые операции
- операции над множествами
- продвинутое индексирование
- форматирование строк
- регулярные выражения, модули re и regex
- подробнее о файлах, модуль os.path

<h4>Ссылки на лекцию:</h4>

- [PDF](https://github.com/MelLain/mipt-python/blob/master/lectures/pdf/mel-lain-mipt-python-types.pdf)
- [Jupyter Notebook](https://github.com/MelLain/mipt-python/blob/master/lectures/src/mel-lain-mipt-python-types.ipynb)

<h2>Занятие 3: Пользовательские и встроенные функции, итераторы и генераторы</h2>

<h4>Содержание: </h4>

- функции range, zip, enumerate
- базовый синтаксис функций, возвращаемое значение, рекурсия
- передача аргументов в функцию
- области видимости переменных, глобальные переменные, правило LEGB
- ключевые слова global и nonlocal
- функции-замыкания
- анонимные функции
- функции map, filter, sorted, functools.reduce
- итерирование, функции iter и next
- генераторные функции, оператор yield
- модуль itertools

<h4>Ссылки на лекцию:</h4>

- [PDF](https://github.com/MelLain/mipt-python/blob/master/lectures/pdf/mel-lain-mipt-python-functions.pdf)
- [Jupyter Notebook](https://github.com/MelLain/mipt-python/blob/master/lectures/src/mel-lain-mipt-python-functions.ipynb)

<h4>Ссылка на первое практическое задание:</h4>

- [Jupyter Notebook](https://github.com/MelLain/mipt-python/blob/master/tasks/mel-lain-mipt-python-task-intro.ipynb)

<h2>Занятие 4: Основы ООП, особенности ООП в Python</h2>

<h4>Содержание: </h4>

- парадигма объектно-ориентированного программирования
- понятия класса, объекта класса
- понятия интерфейса и абстрактного класса
- особенности реализации принципов ООП в Python
- методы \_\_init\_\_ и \_\_new\_\_, параметр self
- методы и атрибуты, функции для работы с атрибутами
- магические методы классов, их перегрузка, менеджеры контекста
- наследование
- перегрузка методов
- полиморфизм, duck typing
- сохранение объектов классов, модуль pickle
- исключения, обработка исключений

<h4>Ссылки на лекцию:</h4>

- [PDF](https://github.com/MelLain/mipt-python/blob/master/lectures/pdf/mel-lain-mipt-python-classes.pdf)
- [Jupyter Notebook](https://github.com/MelLain/mipt-python/blob/master/lectures/src/mel-lain-mipt-python-classes.ipynb)

<h2>Занятие 5: Продвинутое использование ООП, проектирование кода</h2>

<h4>Содержание: </h4>

- проектирование кода
- виды отношений между классами
- принципы SOLID
- пример применения принципов для улучшения кода
- множественное наследование, порядок распознавания методов
- вызов родительских методов, функция super
- статические методы классов
- понятие шаблона проектирования
- шаблон singleton
- шаблон mixin
- шаблоны фасад, адаптер, DAO
- понятие фабрики, шаблон простая фабрика
- шаблоны фабричный метод и абстрактная фабрика
- шаблон декоратор
- декораторы функций и классов в Python
- метаклассы в Python

<h4>Ссылки на лекцию:</h4>

- [PDF](https://github.com/MelLain/mipt-python/blob/master/lectures/pdf/mel-lain-mipt-python-design.pdf)
- [Jupyter Notebook](https://github.com/MelLain/mipt-python/blob/master/lectures/src/mel-lain-mipt-python-design.ipynb)

<h4>Ссылка на второе практическое задание:</h4>

- [Jupyter Notebook](https://github.com/MelLain/mipt-python/blob/master/tasks/mel-lain-mipt-python-task-oop.ipynb)

<h2>Занятие 6: Представление, обработка, анализ и визуализация данных</h2>

<h4>Содержание: </h4>

- представление плотных матриц в Python, базовые операции
- библиотека numpy, описание
- методы создания массива numpy.ndarray
- классы ndarray и matrix
- изменение размерности массивов
- индексирование массовов
- арфметические операции над массивами, broadcasting
- матричные операции над массивами, сравнение с наивной реализацией
- агрегирующие функции
- конкатенация массивов
- примеры дополнительных полезные функции numpy
- примеры постановок и решений задач на векторные и матричные операции
- DataFrame в библиотеке pandas
- доступ к элементам, индесирование
- pandas.DataSeries, операции над столбцами, выборка по условию
- создание и редактирование DataFrame, итерирование, конкатенация
- примеры полезных атрибутов и функций DataFrame
- базовая визуализация на основе DataFrame
- библиотека Matplotlib
- простейшие графики в matplotlib, форматирование
- диаграммы scatter для отображения двумерной выборки

<h4>Ссылки на лекцию:</h4>

- [PDF](https://github.com/MelLain/mipt-python/blob/master/lectures/pdf/mel-lain-mipt-python-data.pdf)
- [Jupyter Notebook](https://github.com/MelLain/mipt-python/blob/master/lectures/src/mel-lain-mipt-python-data.ipynb)

<h2>Занятие 7: ToDo</h2>
