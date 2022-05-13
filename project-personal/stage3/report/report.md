---
## Front matter
title: "иНДИВИДУАЛЬНЫЙ ПРОЕКТ №3"
subtitle: "Добавить к сайту достижения."
author: "ГАЛАНОВА ДАРЬЯ АЛЕКСАНДРОВНА "

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


# Задание


1)писок достижений.
Добавить информацию о навыках (Skills).
Добавить информацию об опыте (Experience).
Добавить информацию о достижениях (Accomplishments).

2)Сделать пост по прошедшей неделе.

3)Добавить пост на тему по выбору:
Легковесные языки разметки.
Языки разметки. LaTeX.
Язык разметки Markdown.



# Выполнение 

## Список достежений 

1) Добавить информацию о навыках (Skills).  (рис. [-@fig:001])

![Skills](image/1.png){ #fig:001 width=70% }

2) Добавить информацию об опыте (Experience). (рис. [-@fig:002])

![Experience](image/2.png){ #fig:002 width=70% }

3) Добавить информацию о достижениях (Accomplishments).(рис. [-@fig:003])

![Experience](image/3.png){ #fig:003 width=70% }

## Сделать пост по прошедшей неделе.
 я сделаю его оригинально и смешно (рис. [-@fig:004])

![2post](image/4.png){ #fig:004 width=70% }

##Добавить пост на тему по выбору:

Язык разметки Markdown. (рис. [-@fig:005])

![Skills](image/5.png){ #fig:005 width=70% }


# Выводы

всё можно посмотреть у меня на сайте и сделать выводы по нему 

# Список литературы{.unnumbered}

::: {#refs}
:::
