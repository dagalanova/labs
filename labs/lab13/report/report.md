---
## Front matter
title: "ЛАБОРАТОРНАЯ РАБОТА №2"
subtitle: "работа с GitHub"
author: "Галанова Дарья Александровна НПМбд-01-21"

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

–Изучить идеологию и применение средств контроля версий
–Освоить умения по работе с git

# Задание

1. Установка GitHub
2. Работа с ним 

# Выполнение лабораторной работы

Описываются проведённые действия, в качестве иллюстрации даётся ссылка на иллюстрацию (рис. [-@fig:001])
1)Создайте учётную запись наhttps://github.com.
![GITHUB](image/01.png){ #fig:001 width=70% }
2) Базовая настройка git и создание ключей ssh, pgp.
![КОНСОЛЬ1](image/02.png){ #fig:002 width=70% }
3) Создание репозитория курса на основе шаблона
![КОНСОЛЬ 2](image/03.png){ #fig:003 width=70% }
4) Настройка каталога курса
![КОНСОЛЬ 3](image/04.png){ #fig:004 width=70% }
# Выводы

в ходе выполнения данной лабораторной работы я изучил идеологию и применение
средств контроля версий, а также освоил умения по работе с git.
# Список литературы{.unnumbered}

::: {#refs}
:::
