---
# Front matter
title: "Отчет по индвидуальному проекту, этап 3"
author: "Хамбалеев Булат Галимович"


# Generic otions
lang: ru-RU
toc-title: "Содержание"


# Pdf output format
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
### Fonts
mainfont: Ubuntu
romanfont: Ubuntu
sansfont: Ubuntu
monofont: Ubuntu
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
## Misc options
indent: true
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Добавить к сайту свои достижения.

# Задание

Данный этап индвидуального проекта подразумевает добавление некоторой информации о своих достижениях, а также некоторые посты.


# Выполнение работы

1. Добавим информацию о навыках.(рис 1)


![рис.1. Навыки.](images/1.jpg){ #fig:001 width=90% }


2. Добавим информацию об опыте. (рис.2)


![рис.2. Опыт.](images/2.jpg){ #fig:002 width=90% }


3. Добавим информацию о достижениях.(рис 3)


![рис.3. Достижения.](images/3.jpg){ #fig:003 width=90% }


4. Сделаем пост по прошедшей неделе. (рис. 4)


![рис.4. Пост по неделе.](images/4.jpg){ #fig:004 width=90% }


5. Сделаем пост на тему "Язык разметки markdown". (рис. 5)


![рис.5. Mardown.](images/5.jpg){ #fig:005 width=90% }


# Библиография

1. ТУИС РУДН

2. https://ru.wikipedia.org/wiki/Markdown

# Выводы

Во время выполнения лабораторной работы я разместил на сайте информацию о достижениях и несколько постов.