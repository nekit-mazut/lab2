# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #2 выполнил(а):
- Дюпин Никита Александрович
- РИ-220936
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Научиться записывать на питоне механику / логику изменения игровой переменной. Передавать результаты в гугл таблицу и использовать эти данные в юнити.

## Задание 1
### Выбрать переменную в игре, описать её и построить схему экономической модели.
Ход работы:
Мной была выбрана Doom 64.
Это игра в жанре шутера от первого лица(fps), в качестве главного героя выступает безымянный космический десантник, который был отправлен на очередную миссию на спутники Марса. На каждом из уровней главный герой должен уничтожать орды разнообразных демонов, используя различные виды оружия.

![cb53ef5c5b4c6691a878382e592e629b1585171657](https://github.com/nekit-mazut/lab2/assets/145917921/8844ea8b-7a10-4b98-af94-7d65635fa6fd)

Я буду описывать роль здоровья в данной игре.
Суть здоровья проста, я бы описал эту переменную как некий счётчик допустимых ошибкок игрока, чем больше у тебя здоровья тем больше атак от демонов ты можешь выдержать.
Здоровье теряется от попавших по персонажу атак врагов и восполняется от подобранных игроком объектов разбросанных по карте по типу зелий со здоровьем и сфер душ.
Переменная варьируется от 0 до 200 здоровья, где при 0 здоровья игрок погибает, при этом в начале уровня у игрока всегда не менее 100 здоровья.

![image](https://github.com/nekit-mazut/lab2/assets/145917921/7349c82a-fc77-4e9e-a094-98df7edfeb50)





## Задание 2
Реализация передачи данных через Python в гугл таблицу

Берутся случайные значения здоровья и передаются в таблицу
![image](https://github.com/nekit-mazut/lab2/assets/145917921/c0f68e8c-6f77-4011-b101-492e5a535e4b)

Диаграмма описывающая изменения здоровья.
![image](https://github.com/nekit-mazut/lab2/assets/145917921/2acad6be-554d-4aa0-a658-06b37e838d15)


## Задание 3
Проект Unity, описывающий динамику изменения здоровья посредством звука.



https://github.com/nekit-mazut/lab2/assets/145917921/2bef6837-ed3a-490c-8c2f-3e7c3b07729f






## Выводы

Благодаря данной работе, я научился передавать данные из Python в гугл таблицы, и реализовывать эти данные в Unity. # github съел изображения, переделано.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
