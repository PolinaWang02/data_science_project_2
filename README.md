<center> <img src = https://raw.githubusercontent.com/AndreyRysistov/DatasetsForPandas/main/hh%20label.jpg alt="drawing" style="width:400px;">

# Проект по Data Science. Анализ резюме из HeadHunter.

## Оглавление
1. [Описание проекта](#Описание-проекта)
2. [Описание данных](#Описание-данных)
3. [Зависимости](#Зависимости)
4. [Установка проекта](#Установка-проекта)
5. [Использование проекта](#Использование-проекта)
6. [Авторы](#Авторы)

## Описание проекта

Проект представляет собой последовательную работу с сырыми данными. Сперва исследуется структура данных, затем идет преобразование данных, далее исследуем зависимости, и наконец, проводим очистку.

Предобработка данных необходима перед построением модели, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе.

**Данный проект** направлен на демонстрацию процесса предобработки данных на примере базы резюме, выгруженной с сайта поиска вакансий hh.ru.

**О структуре проекта:**
* [graphics](/graphics) - папка с графиками, построенными в ходе анализа данных
* [Project-1.Ноутбук-шаблон.ipynb](./Project-1.Ноутбук-шаблон.ipynb) - jupyter-ноутбук, содержащий основной код проекта, в котором демонстрируются методы и подходы решения задач предобработки данных


## Описание данных
В вашем распоряжении будет база резюме, выгруженная с сайта поиска вакансий hh.ru.

Файл с исходными данными, а также данные с курсами валют, которые нам потребовались в ходе выполнения проекта можно скачать [здесь](https://drive.google.com/drive/folders/1Q8DTHSW-MFhs4Jrxk1NnWlumdfC80ZSR?usp=drive_link).

Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. Но, как вы знаете, прежде чем построить модель, данные необходимо преобразовать, исследовать и очистить. В этом и состоит наша с вами задача!

Исходный датасет представляет собой набор данных, в котором содержатся 12 признаков с информацией о 45 тыс. соискателей. 

## Используемые зависимости
* Python (3.11.5):
    * [numpy (1.25.2)](https://numpy.org)
    * [pandas (2.0.3)](https://pandas.pydata.org)
    * [matplotlib (3.7.3)](https://matplotlib.org)
    * [seaborn (0.12.2)](https://seaborn.pydata.org)

## Установка проекта

```
git clone https://github.com/SkillfactoryDS/DataCleaningProject
```

## Использование

Вся информация о работе представлена в jupyter-ноутбуке Project-1. Ноутбук-шаблон.ipynb.

## Авторы

* Polina Komarova

