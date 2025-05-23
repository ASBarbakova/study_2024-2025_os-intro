---
## Front matter
title: "Индивидуальный проект"
subtitle: "3 этап"
author: "Барбакова Алиса Саяновна"

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

Добавить к сайту достижения

# Задание
1. Список достижений.
   - Добавить информацию о навыках (Skills).  
   - Добавить информацию об опыте (Experience).  
   - Добавить информацию о достижениях (Accomplishments).  
2. Сделать пост по прошедшей неделе.  
3. Добавить пост на тему по выбору:
   - Легковесные языки разметки.  
   - Языки разметки. LaTeX.  
   - Язык разметки Markdown.  

# Выполнение индивидуального проекта

Захожу в терминал, ввожу команду ~/bin/blog server. У меня открывается localhost, на котором я могу смотреть мои изменения с сайтом. В папке открываю файл md, ввожу туда информацию о моих навыках и хобби (рис. [-@fig:001]).

![Skills](image/1.png){#fig:001 width=70%}

Там же редактирую информацио об опыте (рис. [-@fig:002]).

![Experience](image/2.png){#fig:002 width=70%}

И добавляю информацию о достижениях (рис. [-@fig:003]).

![Accomplishments](image/3.png){#fig:003 width=70%}

Захожу в другой каталог, создаю новую папку для поста по прошедшей неделе. Пишу пост (рис. [-@fig:004]).

![Пост по прошедшей неделе](image/4.png){#fig:004 width=70%}

Там же создаю другую папку, пишу пост по выбранной теме - "Язык разметки Markdown." (рис. [-@fig:005]).

![Язык разметки Markdown](image/5.png){#fig:005 width=70%} 

# Выводы

Достижения к сайту были добавлены.

# Список литературы{.unnumbered}

1. Кулябов Д. С. Введерние в операционную систему UNIX - Лекция.
2. Таненбаум Э., Бос Х. Современные операционные системы. - 4-е изд. -СПб. : Питер, 2015. - 1120 с.
