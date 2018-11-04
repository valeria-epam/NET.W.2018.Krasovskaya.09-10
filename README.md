1. Для объектов класса Book (ISBN, автор, название, издательство, год издания,
количество страниц, цена) (домашнее задание 8-ого дня)
реализовать возможность строкового представления различного вида.
Например, для объекта со значениями ISBN = 978-0-7356-6745-7, AuthorName
= Jeffrey Richter, Title = CLR via C#, Publisher = Microsoft Press, Year = 2012,
NumberOPpages = 826, Price = 59.99$, могут быть следующие варианты:
- Jeffrey Richter, CLR via C#
- Jeffrey Richter, CLR via C#, &quot;Microsoft Press&quot;, 2012
- ISBN 13: 978-0-7356-6745-7, Jeffrey Richter, CLR via C#, &quot;Microsoft Press&quot;,
2012, P. 826.
- Jeffrey Richter, CLR via C#, &quot;Microsoft Press&quot;, 2012
- ISBN 13: 978-0-7356-6745-7, Jeffrey Richter, CLR via C#, &quot;Microsoft Press&quot;,
2012, P. 826., 59.99$.
и т.д.

 См. [задание дня 8](https://github.com/valeria-epam/NET.W.2018.Krasovskaya.08/blob/master/BookListStorage/Book.cs)

2. Не изменяя класс Book, добавить для объектов данного класса дополнительную
возможность форматирования, изначально не предусмотренную классом.

 См. [задание дня 8](https://github.com/valeria-epam/NET.W.2018.Krasovskaya.08/blob/master/BookExtension/BookFormatExtension.cs)

3. Для реализованных в пп. 1, 2 функциональностей разработать модульные тесты.

См. [для п.1](https://github.com/valeria-epam/NET.W.2018.Krasovskaya.08/blob/master/Book.Tests/BookTest.cs)

См. [для п.2](https://github.com/valeria-epam/NET.W.2018.Krasovskaya.08/blob/master/BookExtension.Tests/BookFormatExtensionTests.cs)

4. Выполнить рефакторинг класса (с целью сокращения повторного кода) в алгоритмах
Евклида (для рефакторинга использовать делегаты, рефакторинг возможен только в
случае, когда все метод находятся в одном классе!). Интерфейс класса измениться не
должен.

См. [задание дня 3](https://github.com/valeria-epam/NET.W.2018.Krasovskaya.03/blob/master/FindGCD/GCD.cs)

5. В класс с алгоритмом сортировки не прямоугольной матрицы, принимающим как
компаратор интерфейс IComparer&lt;int[]&gt; добавить метод, принимающий как параметр
делегат-компаратор, инкапсулирующий логику сравнения строк матрицы.
Протестировать работу разработанного метода на примере сортировки матрицы,
используя прежние критерии сравнения. Класс реализовать двумя способами,
«замкнув» в первом варианте реализацию метода сортировки с делегатом на метод с
интерфейсом, во втором – наоборот.

См. [задание дня 5](https://github.com/valeria-epam/NET.W.2018.Krasovskaya.05/tree/master/BubbleSort)
