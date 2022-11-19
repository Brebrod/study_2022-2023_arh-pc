---
## Front matter
title: "Отчёт по лабораторной работе №6"
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

Целью моей работы является приобретение практических навыков работы в Midnight Commander. Освоение инструкций языка ассемблера mov и int.

# Выполнение лабораторной работы

![Запуск Midnight Commander](/home/nypopov/Изображения/Снимок экрана от 2022-11-19 21-57-45.png){ #fig:001 width=100% }

![Создание каталога](/home/nypopov/Изображения/Снимок экрана от 2022-11-19 22-00-44.png){ #fig:002 width=100% }

![Создание файла](/home/nypopov/Изображения/Снимок экрана от 2022-11-19 22-01-19.png){ #fig:003 width=100% }

![Ввод текста программы](/home/nypopov/Изображения/Снимок экрана от 2022-11-19 22-04-00.png){ #fig:004 width=100% }

![Проверка содержимого файла](/home/nypopov/Изображения/Снимок экрана от 2022-11-19 22-04-50.png){ #fig:005 width=100% }

![Трансляция, компоновка и запуск](/home/nypopov/Изображения/Снимок экрана от 2022-11-19 22-10-18.png){ #fig:006 width=100% }

![Загрузка файла](/home/nypopov/Изображения/Снимок экрана от 2022-11-19 22-12-12.png){ #fig:007 width=100% }

![Копирование файла](/home/nypopov/Изображения/Снимок экрана от 2022-11-19 22-17-21.png){ #fig:008 width=100% }

![Проверка работы программы с использованием файла in_out.asm](/home/nypopov/Изображения/Снимок экрана от 2022-11-19 22-24-59.png){ #fig:009 width=100% }

![Замена подпрограммы sprintLF на sprint](/home/nypopov/Изображения/Снимок экрана от 2022-11-19 22-26-04.png){ #fig:010 width=100% }

![Проверка работы программы с заменой](/home/nypopov/Изображения/Снимок экрана от 2022-11-19 22-27-19.png){ #fig:011 width=100% }

![Результат изменения первой программы](/home/nypopov/Изображения/Снимок экрана от 2022-11-19 22-45-59.png){ #fig:012 width=100% }

![Результат изменения второй программы](/home/nypopov/Изображения/Снимок экрана от 2022-11-19 22-52-25.png){ #fig:013 width=100% }



# Выводы

Мною была приобретены практические навыки работы в Midnight Commander и освоены инструкции языка ассемблера mov и int.


