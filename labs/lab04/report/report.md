---
## Front matter
title: "Отчет по лабораторной работе №6"
subtitle: "Дисциплина: Архитектура компьютера"
author: "Ланцова Яна Игоревна"

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

Целью работы является приобретение практических навыков работы в Midnight Commander. Освоение инструкций языка ассемблера mov и int.

# Описание результатов выполнения задания:

(рис. [-@fig:001])

![  Откроем Midnight Commander](images/1.png){ #fig:001 width=70% }

(рис. [-@fig:002])

![ Окно Midnight Commander](images/2.png){ #fig:002 width=70% }

(рис. [-@fig:003])

![ Перейдем в каталог, созданный при выполнении лабораторной работы №5](images/3.png){ #fig:003 width=70% }

(рис. [-@fig:004])

![ Создаем папку lab06](images/4.png){ #fig:004 width=70% }

(рис. [-@fig:005])

![  Переходим в него](images/5.png){ #fig:005 width=70% }

(рис. [-@fig:006])

![ Создав файл lab6.asm с помощью команды touch, открываем и редактируем его](images/6.png){ #fig:006 width=70% }

(рис. [-@fig:007])

![   Оттранслируем текст программы lab6.asm в объектный файл.Выполним компоновку объектного файла и запустим получившийся исполняемый файл. На запрос вводим ФИО](images/7.png){ #fig:007 width=70% }

(рис. [-@fig:008])

![   Скачав файл  in_out.asm со страницы курса в ТУИС, Скопируем файл in_out.asm в каталог с файлом lab6.asm](images/8.png){ #fig:008 width=70% }

(рис. [-@fig:009])

![   Скопировав файл lab6.asm, называем его копию lab6-2.asm, затем открываем и редактируем его](images/9.png){ #fig:009 width=70% }

(рис. [-@fig:010])

![    Оттранслируем текст программы lab6-2.asm в объектный файл.Выполним компоновку объектного файла и запустим получившийся исполняемый файл. На запрос вводим ФИО](images/10.png){ #fig:010 width=70% }

(рис. [-@fig:011])

![    В файле lab6-2.asm заменим подпрограмму sprintLF на sprint. Создаем исполняемый файл и проверяем его работу. При вводе строки, она не переносится на следующую строку](images/11.png){ #fig:011 width=70% }

# Задания для самостоятельной работы

(рис. [-@fig:012])

![    Скопировав файл lab6.asm, называем его копию lab6-3.asm, затем открываем и редактируем его](images/12.png){ #fig:012 width=70% }

(рис. [-@fig:013])

![    Оттранслируем текст программы lab6-3.asm в объектный файл.Выполним компоновку объектного файла и запустим получившийся исполняемый файл. На запрос вводим ФИО](images/13.png){ #fig:013 width=70% }

(рис. [-@fig:014])

![    Скопировав файл lab6.asm, называем его копию lab6-4.asm, затем открываем и редактируем его](images/14.png){ #fig:014 width=70% }

(рис. [-@fig:012])

![    Оттранслируем текст программы lab6-3.asm в объектный файл.Выполним компоновку объектного файла и запустим получившийся исполняемый файл. На запрос вводим ФИО](images/15.png){ #fig:015 width=70% }


# Вывод

Практические навыки работы в Midnight Commander были получены. Освоение инструкций языка ассемблера mov и int изучено, цель работы достигнута

Ссылка на мой github: https://github.com/yilancova/study_2022-2023_arh-pc/tree/master/labs
