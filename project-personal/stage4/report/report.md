---
## Front matter
title: "Отчёт по выполнению индивидуального проекта.4 этап"
subtitle: "Дисциплина: Операционные системы"
author: "Волчок Кристина Александровна"

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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Научиться добавлять к сайту ссылки на научные и библиометрические ресурсы.

# Выполнение лабораторной работы

В папке admin вижу наличие 2 файлов, один из которых- текстовый
документ _index.md. Поработаем с ним.(рис. [-@fig:001])

![Наша папка](image/1.1.jpg){ #fig:001 width=70% }


Вносим изменения в наш файл, все поля заполняем по форме. Которая представлена в комментариях.(рис. [-@fig:002])

![Наша папка](image/0.jpg){ #fig:002 width=70% }

Открываю терминал, с помощью команды ~/bin/hugo server проверяю исправность работы сервера и не допустила ли я ошибок. Вызываю ~/bin/hugo (рис. [-@fig:003])


![~/bin/hugo ](image/1.2.jpg){ #fig:003 width=70% }


Перехожу по ссылке, сгенерированной с помощью команды ~/bin/hugo server,
здесь с нашим сайтом будут происходить все первоначальные изменения (после
каждого вызова команды ~/bin/hugo server). Посмотрим, что изменилось (рис. [-@fig:004])


![Появились иконки с соцсетями](image/1.jpg){ #fig:004 width=70% }

В терминале с помощью команды hugo создаю новый текстовый документ
post5.md в папке post(рис. [-@fig:005])

![Создание текстового документа](image/2.jpg){ #fig:005 width=70% }


Открываю файл и вношу изменения(рис. [-@fig:006])


![Изменения](image/4.jpg){ #fig:006 width=70% }

Помещаю документ и картинку к нему в отдельную папку post5, переименовываю текстовый документ в index.md, а картинку в featured.jpg 

Открываю терминал, с помощью команды ~/bin/hugo server проверяю исправность работы сервера и не допустила ли я ошибок. Вызываю ~/bin/hugo.(рис. [-@fig:007])

![~/bin/hugo server](image/1.2.jpg){ #fig:007 width=70% }

 Перехожу по ссылке, сгенерированной с помощью команды ~/bin/hugo server, здесь с нашим сайтом будут происходить все первоначальные изменения (после каждого
вызова команды ~/bin/hugo server). 

В терминале с помощью команды hugo создаю новый текстовый документ
post6.md в папке post(рис. [-@fig:008])

![Создание текстового докумета](image/5.jpg){ #fig:008 width=70% }


Открываю файл и вношу изменения (рис. [-@fig:009])


![Изменения в текстовом файле](image/7.jpg){ #fig:009 width=70% }


Помещаю документ и картинку к нему в отдельную папку post6, переименовываю текстовый документ в index.md, а картинку в featured.jpg(рис. [-@fig:010])

![Наша папка](image/6.jpg){ #fig:010 width=70% }


Открываю терминал, с помощью команды ~/bin/hugo server проверяю исправность работы сервера и не допустила ли я ошибок. Вызываю ~/bin/hugo. Перехожу
по ссылке, сгенерированной с помощью команды ~/bin/hugo server, здесь с нашим сайтом будут происходить все первоначальные изменения (после каждого
вызова команды ~/bin/hugo server). Посмотрим, что изменилось(рис. [-@fig:011])


![Наш сайт и посты, которые мы написали](image/8.jpg){ #fig:011 width=70% }








# Выводы

В ходе выполнения данного  этапа индивидуального проекта  я научилась добавлять к сайту
ссылки на научные и библиометрические ресурсы, написала пост о прошедшей
неделе и пост на заданную тему



::: {#refs}
:::
