---
## Front matter
lang: ru-RU
title: Лабораторная работа №3
author: |
	Волчок Кристина Александровна
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation
	
date: NEC--2022, 26 April

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---


 
## Цель работы 

- Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.



## Базовые сведения о Markdown

 - Создание заголовков
 - Шрифт
 - Блоки цитирования 
 - Вложение одного списка в другой
 - Загрузка фотографий
 - Команды, используемые для ввода кода

## Обработка файлов в формате Markdown

 - Для обработки файлов в формате Markdown будем использовать Pandoc
https://pandoc.org/. Конкретно, нам понадобится программа pandoc ,
pandoc-citeproc https://github.com/jgm/pandoc/releases, pandoc-crossref
https://github.com/lierdakil/pandoc-crossref/releases.
 - Преобразовываем файл readme.md с помощью команды pandoc в pdf и docx.




## Загрузка наших файлов на GitHub
 - Осуществляется с помощью команд:
 - git add .
 - git commit -am '  '
 - git push

