---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "дисциплина: Архитектура компьютера"
author: "Студент: Попов Н.Ю.
Группа: НММбд-03-22"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: false # List of figures
lot: false # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью моей работы является освоение процедуры оформления отчётов с помощью легковесного языка разметки Markdown.

# Задание

Заполнить и скомпилировать отчёт с использованием Makefile. Загрузить файлы на Github.

# Выполнение лабораторной работы

![Предварительная установка и проверка ПО](/home/nypopov/Изображения/Снимок экрана от 2022-10-29 13-40-47.png){ #fig:001 width=100% }

![Обновление локального репозитория](/home/nypopov/Изображения/Снимок экрана от 2022-10-29 13-28-53.png){ #fig:002 width=100% }

![Компиляция шаблона](/home/nypopov/Изображения/Снимок экрана от 2022-10-29 13-42-11.png){ #fig:003 width=100% }

![Проверка полученных файлов и их удаление](/home/nypopov/Изображения/Снимок экрана от 2022-10-29 13-46-42.png){ #fig:004 width=100% }

![Открытие файла отчёта с помощью gedit и его редактирование](/home/nypopov/Изображения/Снимок экрана от 2022-10-29 14-08-46.png){ #fig:005 width=100% }

Компиляция отчёта и загрузка на Github


# Выводы

Мною была освоена процедура оформления отчётов с помощью легковесного языка разметки Markdown.


