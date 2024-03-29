# Анализ поведения пользователей мобильного приложения

## Цель исследования

Изучить воронку продаж и поведение пользователей, а также результаты A/A/B-эксперимента относительно изменения шрифтов в приложении.

## Ход исследования

Исследование включает следующие этапы:

1. Обзор, подготовка и проверка данных.
2. Воронка событий: изучение порядка событий и поведения пользователей.
3. Анализ эксперимента: влияет ли на поведение пользователей новый шрифт в приложении.
4. Выводы.

## Используемые библиотеки

Pandas, Datetime, Scipy, Numpy, Math, Matplotlib, Plotly

## Выводы

Воронка событий показала цепочку из 4 последовательных событий и одно отдельное. Больше всего пользователей (почти 40%) отваливается после первого шага. Из тех, кто остался, пятая часть уходит перед оплатой. Полностью все события цепи проходит меньше половины пользователей.

Проведен эксперимент на предмет нового шрифта в приложении. Пользователи были разделены на 3 группы: 2 контрольные со старыми шрифтами и одну экспериментальную — с новыми. По итогам теста можно сделать вывод, что измененный шрифт в приложении никак не влияет на поведение пользователей.
