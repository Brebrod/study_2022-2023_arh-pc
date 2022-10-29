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

Целью моей работы является изучение идеологии и
применения средств контроля версий. Приобретение практических навыков по
работе с системой git.

# Задание

Настроить git. Создать рабочее пространство и репозиторий на основе шаблона. Настроить каталог курса.

# Выполнение лабораторной работы

![Предварительная конфигурация git](/home/nypopov/Изображения/Снимок экрана от 2022-10-15 10-00-51.png){ #fig:001 width=100% }

![Создание SSH ключа](/home/nypopov/Изображения/Снимок экрана от 2022-10-15 10-06-39.png){ #fig:002 width=100% }

![Загрузка SSH ключа](/home/nypopov/Изображения/Снимок экрана от 2022-10-15 10-10-23.png){ #fig:003 width=100% }

![Создание рабочего пространства и репозитория курса](/home/nypopov/Изображения/Снимок экрана от 2022-10-15 10-20-33.png){ #fig:004 width=100% }

![Настройка каталога курса](/home/nypopov/Изображения/Снимок экрана от 2022-10-15 10-24-08.png){ #fig:005 width=100% }

![Настройка каталога курса](/home/nypopov/Изображения/Снимок экрана от 2022-10-15 10-32-23.png){ #fig:006 width=100% }

![Проверка правильности иерархии рабочего пространства](/home/nypopov/Изображения/Снимок экрана от 2022-10-15 10-34-37.png){ #fig:007 width=100% }

![Проверка правильности иерархии репозитория](/home/nypopov/Изображения/Снимок экрана от 2022-10-15 10-36-04.png){ #fig:008 width=100% }



![Создание отчёта в соответствующем каталоге](/home/nypopov/Изображения/Снимок экрана от 2022-10-15 11-17-55.png){ #fig:009 width=100% }

![Перемещение отчётов предыдущих работ](/home/nypopov/Изображения/Снимок экрана от 2022-10-15 11-37-24.png){ #fig:010 width=100% }

![Загрузка файлов на github](/home/nypopov/Изображения/Снимок экрана от 2022-10-15 11-50-06.png){ #fig:011 width=100% }



# Выводы

Мною были изучены идеология и применение средств контроля
версий. Приобретены практических навыки по работе с системой git.


