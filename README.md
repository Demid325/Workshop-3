# Анализ данных в разработке игр [in GameDev]
Отчет по лабораторной работе #3 выполнил(а):
- Белоусов Демид Алексеевич
- НМТ231702

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | # | 20 |
| Задание 3 | # | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Цель работы
Разработать оптимальный баланс нанесения урона оружием для игры Save RTF 

## Задание 1
### Расширьте варианты доступного оружия в игре. Используйте шаблон таблицы для визуализации оружия игры Save RTF.
Для настройки оружия проанализируем таблицу "Damage". Из данных видно, что средний урон пулемёта крайне низок.
Предлагаются следующие изминения: 
  Пулемёт:
  Увеличить урон до 2 единиц за выстрел;
  Повысить скорострельность до 7.
  Пистолет: 
  Характеристики сбалансированы удачно — изменений не требуется.
  Винтовка: 
  Уменьшить шанс попадания на дистанции 8–10.
  Дробовик: 
  Повысить шанс попадания на ближней дистанции.
  Снайперская:
  Снизить шанс попадания при дальности 7.

Также для расширения вариантов стоит проанализировать таблицу "Средний урон". Можно заметить, что отсутствует оружие, эффективная дистанция которого находилась бы в диапазоне 5–6 единиц.
Таким оружием могла бы стать полуавтоматическая винтовка или же DMR. Её скорострельность должна быть выше, чем у снайперской например 2, но при этом урон — ниже, около 5  единиц за выстрел.

Подробнее изминения баланса приведены в таблице
[Workshop3.xlsx](https://github.com/user-attachments/files/19494549/Workshop3.xlsx)

## Задание 2
-
## Задание 3
-
## Выводы
В ходе работы мы изучили процесс создания баланса в играх и провели балансеровки оружия для игры Save RTF.

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
