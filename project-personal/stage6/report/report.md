---
## Front matter
title: "ИНДИВДУАЛЬНЫЙ ПРОЕКТ "
subtitle: "///"
author: "Галанова Дарья "

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
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

делать всё правильно 

# Задание

Добавить к сайту ссылки на научные и библиометрические ресурсы.


# Выполнение ИП
1) Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте:(рис. [-@fig:001])

![Название рисунка](image/1.png){ #fig:001 width=70% }


2) Сделать пост по прошедшей неделе.(рис. [-@fig:001])

![Название рисунка](image/2.png){ #fig:002 width=70% }

3) Добавить пост на тему по выбору: Оформление отчёта.Создание презентаций.Работа с библиографией. Я выбрала создание презентации и вот что получилось (рис. [-@fig:001])

![Название рисунка](image/3.png){ #fig:003 width=70% }

# Выводы

я всё сделала. получилось круто 

# Список литературы{.unnumbered}

::: {#refs}
:::
