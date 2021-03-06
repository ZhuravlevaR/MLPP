﻿# MLPP
 
Межлабораторная программа по биохимическим исследованиям. Является элементом комплексной сервисно-методической поддержки клиентов АО «Вектор-Бест», направленной на повышение степени лояльности клиентов к компании, удовлетворенности от работы с нашей биохимической продукцией, в конечном счете – на увеличение объема продаж. Цель: повышение качества результатов и их сопоставимости в лабораториях, использующих наборы реагентов для биохимического анализа «Вектор-Бест».

1ая форма (Вывод_статистики_в_таблицу.ipynb) с 2017 года – подробный отчёт с результатами конкретной лаборатории в традиционной табличной форме.

С числом лабораторий, выполнивших данное исследование, целевыми значениями для разных групп сравнения. Под группами сравнения подразумеваются либо результаты всех участников, независимо от прибора, либо результаты, полученные с использованием конкретных приборов. Также удалось выделить группы участников, работающих на приборах А15, А25, Miura, Sapphire, BA-400.

Для каждой группы посчитаны среднеквадратическое отклонение. Показано смещение относительно целевого значения в % и смещение в виде индекса среднеквадратического отклонения (SDI), отражающего положение результата по отношению к остальным результатам в группе сравнения.

SDI не вычислялся, если в группе сравнения было менее 10 результатов. Допустимые значения SDI лежат в пределах от -2,0 до 2,0.

В качестве допустимого смещения приведены фиксированные нормы точности для каждого аналита.

2ая форма отчёта (Регрессия_анализ_динамики.ipynb) была добавлена во 2ом цикле 2018 года – менее детализированная, но более показательная. Представлена динамика индекса среднеквадратического отклонения результатов одной конкретной лаборатории за время участия в программе, начиная с 2017 года.

Третий вариант отчёта (Z_стастистика.ipynb) отражает распределение лабораторий по среднему значению индекса SDI (как среднее для всех показателей) и положение лабораторий относительно остальных.
