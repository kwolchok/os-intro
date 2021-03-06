---
## Front matter
title: "Отчёт по лабораторной работе 9"
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

В ходе лабораторной работы я должна познакомиться с операционной системой Linux.Получить практические навыки работы с редактором emacs


# Задание 

1. Открыть emacs.

2. Создать файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f (C-x C-f).

3. Наберите текст:

1 #!/bin/bash

2 HELL=Hello

3 function hello {

4 LOCAL HELLO=World

5 echo $HELLO

6 }

7 echo $HELLO

8 hello

4. Сохранить файл с помощью комбинации Ctrl-x Ctrl-s (C-x C-s).

5. Проделать с текстом стандартные процедуры редактирования,каждое действие долж-
но осуществляться комбинацией клавиш.

5.1. Вырезать одной командой целую строку (С-k).

5.2. Вставить эту строку в конец файла (C-y).

5.3. Выделить областьтекста (C-space).

5.4. Скопировать область в буфер обмена (M-w).

5.5. Вставить область в конец файла.

5.6. Вновь выделить эту область и на этотраз вырезать её (C-w).

5.7. Отмените последнее действие (C-/).

6. Научитесь использовать команды по перемещению курсора.

6.1. Переместите курсор в начало строки (C-a).

6.2. Переместите курсор в конец строки (C-e).

6.3. Переместите курсор в начало буфера (M-<).

6.4. Переместите курсор в конец буфера (M->).

7. Управление буферами.

7.1. Вывести список активных буферов на экран (C-x C-b)

7.2. Переместитесь во вновь открытое окно (C-x) o со списком открытых буферов
и переключитесь на другой буфер.

7.3. Закройте это окно (C-x 0).

7.4. Теперь вновь переключайтесь между буферами,но уже без вывода их списка на
экран (C-x b).

8. Управление окнами.

8.1. Поделите фрейм на 4 части: разделите фрейм на два окна по вертикали (C-x 3),
а затем каждое из этих окон на две части по горизонтали (C-x 2) 

8.2. В каждом из четырёх созданных окон откройте новый буфер (файл) и введите
несколько строктекста.

9. Режим поиска

9.1. Переключитесьв режим поиска (C-s) и найдите несколько слов,присутствующих
втексте.

9.2. Переключайтесь между результатами поиска,нажимая C-s.

9.3. Выйдите из режима поиска,нажав C-g.

9.4. Перейдите в режим поиска и замены (M-%),введитетекст,который следует найти
и заменить,нажмите Enter ,затем введитетекстдля замены.Послетого как будут
подсвечены результаты поиска,нажмите ! для подтверждения замены.

9.5. Испробуйте другой режим поиска,нажав M-s o.Объясните,чем он отличается от
обычного режима?




# Выполнение лабораторной работы

# Создание нового файла с использованием vi


1.Открыла emacs.(рис. [-@fig:001])

![emacs](image/1.jpg){ #fig:001 width=70% }

2.Создала файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f (C-x C-f).(рис. [-@fig:002])

![файл lab07.sh](image/2.jpg){ #fig:002 width=70% }

3.Набрала текст:(рис. [-@fig:003])

1 #!/bin/bash

2 HELL=Hello

3 function hello {

4 LOCAL HELLO=World

5 echo $HELLO

6 }

7 echo $HELLO

8 hello

![текст](image/6.png){ #fig:003 width=70% }


4. Сохранила файл с помощью комбинации Ctrl-x Ctrl-s (C-x C-s).(рис. [-@fig:004])

5. Проделала с текстом стандартные процедуры редактирования, каждое действие осуществлялось комбинацией клавиш.

5.1. Вырезала одной командой целую строку (С-k).

![Сохранила файл](image/8.png){ #fig:004 width=70% }

5.2. Вставила эту строку в конец файла (C-y).(рис. [-@fig:005])


![Вставила строку](image/10.png){ #fig:005 width=70% }

5.3. Выделила область текста (C-space).(рис. [-@fig:006])

![Область текста](image/11.png){ #fig:006 width=70% }

5.4. Скопировала область в буфер обмена (M-w).(рис. [-@fig:007])

5.5. Вставила область в конец файла.

![Копирование](image/12.png){ #fig:007 width=70% }

5.6. Вновь выделила эту область и на этот раз вырезала её (C-w).(рис. [-@fig:008])

![Вырезание](image/13.png){ #fig:008 width=70% }

5.7. Отменила последнее действие (C-/).(рис. [-@fig:009])

![Отмена последних действий ](image/14.png){ #fig:009 width=70% }

6. Научилась использовать команды по перемещению курсора.

6.1. Переместила курсор в начало строки (C-a).(рис. [-@fig:010])

![Курсор в начале](image/17.png){ #fig:010 width=70% }

6.2. Переместила курсор в конец строки (C-e).(рис. [-@fig:011])

![Курсор в конце](image/15.png){ #fig:011 width=70% }

Переместила курсор в начало буфера (M-<), а также переместила курсор в конец буфера (M->).

7. Управление буферами.

7.1. Вывела список активных буферов на экран (C-x C-b).(рис. [-@fig:012])

![ Список активных буферов](image/19.png){ #fig:012 width=70% }

7.2. Переместились во вновь открытое окно (C-x) со списком открытых буферов и переключились на другой буфер.(рис. [-@fig:013])


![Перемещение](image/19.png){ #fig:013 width=70% }

7.3. Закрыла это окно (C-x 0).(рис. [-@fig:014])

![Закрвла окно](image/20.png){ #fig:014 width=70% }

 Вновь переключилась между буферами, но без вывода их списка на экран (C-x b).

8. Управление окнами.

8.1. Поделила фрейм на 4 части: разделила фрейм на два окна по вертикали

(C-x 3), а затем каждое из этих окон на две части по горизонтали (C-x 2).(рис. [-@fig:015])

![Поделила фрейм на 4 части](image/22.png){ #fig:015 width=70% }


8.2. В каждом из четырёх созданных окон открыла новый буфер (файл) и ввела несколько строк текста.(рис. [-@fig:016])

![ . ](image/24.png){ #fig:016 width=70% }

9. Режим поиска

9.1. Переключилась в режим поиска (C-s) и нашла несколько слов, присутствующих в тексте.(рис. [-@fig:017])

![Переключение в режим поиска](image/25.png){ #fig:017 width=70% }

9.2. Переключалась между результатами поиска, нажимая C-s.(рис. [-@fig:018])

![Переключение между результатами поиска](image/26.png){ #fig:018 width=70% }

9.3. Вышла из режима поиска, нажав C-g.(рис. [-@fig:019])

![Выход из режима поиска](image/27.png){ #fig:019 width=70% }

9.4. Перешла в режим поиска и замены (M-%), ввела текст, который следует найти и заменить, нажала Enter , затем ввела текст для замены. После того как были подсвечены результаты поиска, нажала ! для подтверждения замены.


9.5. Испробовала другой режим поиска, нажав M-s o. Он отличается от обычного режима тем, что при поиске указывает номера строк в которых найдено введённое слово и выделяет их цветом. В обычном режиме выделение цветом появляется, только когда нужно подтвердить замену.(рис. [-@fig:021])

![.](image/28.png){ #fig:021 width=70% }



# Контрольные вопросы
1. Кратко охарактеризуйте редактор emacs.

2. Какие особенности данного редактора могутсделать его сложным для освоения но-
вичком?

3. Своими словами опишите,чтотакое буфер и окно втерминологии emacs’а.

4. Можно ли открыть больше 10 буферов в одном окне?

5. Какие буферы создаются по умолчанию при запуске emacs?

6. Какие клавиши вы нажмёте,чтобы ввести следующую комбинацию C-c | и C-c C-|?

7. Как поделитьтекущее окно на две части?

8. В каком файле хранятся настройки редактора emacs?

9. Какую функцию выполняет клавиша и можно ли её переназначить?

10. Какой редактор вам показался удобнее в работе vi или emacs? Поясните почему.

# Ответы на контрольные вопросы:

1) Emacs − один из наиболее мощных и широко распространённых
редакторов, используемых в мире Unix. По популярности он
соперничает с редактором vi и его клонами. В зависимости от ситуации,
Emacs может быть:
- текстовым редактором;
- программой для чтения почты и новостей Usenet;
- интегрированной средой разработки (IDE);
- операционной системой и т.д.
Всё это разнообразие достигается благодаря архитектуре Emacs,
которая позволяет расширять возможности редактора при помощи
языка Emacs Lisp. На языке C написаны лишь самые базовые и
низкоуровневые части Emacs, включая полнофункциональный 
интерпретатор языка Lisp. Таким образом, Emacs имеет встроенный
язык программирования, который может использоваться для настройки,
расширения и изменения поведения редактора. В действительности,
большая часть того редактора, с которым пользователи Emacs работают
в наши дни, написана на языке Lisp.
2) Основную трудность для новичков при освоении данного редактора
могут составлять большое количество команд, комбинаций клавиш,
которые не получится все запомнить с первого раза и поэтоу придется
часто обращаться к справочным материалам.
3) Буфер – это объект, представляющий собой текст. Если имеется
несколько буферов, то редактировать можно только один. Обычно буфер
считывает данные из файла или записывает в файл данные из буфера.
Окно – это область экрана, отображающая буфер. При запуске редактора
отображается одно окно, но при обращении к некоторым функциям
могут открыться дополнительные окна. Окна Emacs и окна графической
среды X Window – разные вещи. Одно окно X Window может быть
разбито на несколько окон в смысле Emacs, в каждом из которых
отображается отдельный буфер.
4) Да, можно.
5) При запуске Emacs по умолчанию создаются следующие буферы:
- «scratch» (буфер для несохраненного текста)
- «Messages» (журнал ошибок, включающий также информацию,
которая появляется в области EchoArea)
- «GNU Emacs» (справочный буфер о редакторе)
6) C-c | сначала, удерживая «ctrl», нажимаю «c», после – отпускаю обе
клавиши и нажимаю «|»
C-c C-| сначала, удерживая «ctrl», нажимаю «с», после – отпускаю обе
клавиши и, удерживая «ctrl», нажимаю «|»
7) Чтобы поделить окно на две части необходимо воспользоваться
комбинацией «Ctrl-x 3» (по вертикали) или «Ctrl-x 2» (по горизонтали).
8) Настройки Emacs хранятся в файле .emacs.
9) По умолчанию клавиша «←» удаляет символ перед курсором, но в
редакторе её можно переназначить. Для этого необхдимо изменить
конфигурацию файла .emacs.
10) Более удобным я считаю редактор emacs, потому что в нем проще
открывать другие файлы, можно использовать сразу несколько окон, нет
«Командного режима», «Режима ввода», «Режима командной строки»,
которые являются немного непривычными и в какой-то степени
неудобными.

# Вывод

В ходе проделанной лабораторной работы я познакомилась с операционной системой Linux, получила практические навыки работы с редактором Emacs.


