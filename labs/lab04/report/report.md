---
## Front matter
title: "Отчет по лабораторной работе №3"
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

Целью работы является изучение идеологии и применение средств контроля версий, а также приобретение практических навыков по работе с системой git.

# Описание результатов выполнения задания:

## Настройка github

(рис. [-@fig:001])

![Создаем учетную запись на github для выполнения дальнейшей работы](image/1.png){ #fig:001 width=70% }

## Базовая настройка github

(рис. [-@fig:002])

![ Открыв терминал, вводим следующие команды, указав имя и email владельца репозитория](image/2.png){ #fig:002 width=70% }

(рис. [-@fig:003])

![ Настроим utf-8 в выводе сообщений git](image/3.png){ #fig:003 width=70% }

(рис. [-@fig:004])

![ Задаем имя начальной ветки (будем называть ее master), также определяем параметры autocrlf и safecrlf](image/4.png){ #fig:004 width=70% }

## Создание SSH ключа

(рис. [-@fig:005])

![ Для последующей идентификации пользователя на сервере репозиториев сгенерируем пару ключей (приватный и открытый)](image/5.png){ #fig:005 width=70% }

(рис. [-@fig:006])

![ Скопировав из локальной консоли ключ в буфер обмена, вставляем в необходимое поле на github](image/6.png){ #fig:006 width=70% }

(рис. [-@fig:007])

![   Созданный ключ](image/7.png){ #fig:007 width=70% }

## Сознание рабочего пространства и репозитория курса на основе шаблона

(рис. [-@fig:008])

![   создаем каталог для предмета «Архитектура компьютера» в терминале](image/8.png){ #fig:008 width=70% }

(рис. [-@fig:009])

![   скопированный ключ вставляем в необходимое поле на github](image/9.png){ #fig:009 width=70% }

## Создание репозитория курса на основе шаблона

(рис. [-@fig:010])

![   клонируем созданный репозиторий ](image/10.png){ #fig:010 width=70% }

## Настройка каталога курса

(рис. [-@fig:011])

![   переходим в каталог курса ](image/11.png){ #fig:011 width=70% }

(рис. [-@fig:012])

![   удаляем лишние файлы ](image/12.png){ #fig:012 width=70% }

(рис. [-@fig:013])

![    создаем  необходимые каталоги ](image/13.png){ #fig:013 width=70% }

(рис. [-@fig:014])

![   отправляем файлы на сервер ](image/14.png){ #fig:014 width=70% }

(рис. [-@fig:015])

![   Проверяем правильность создания иерархии рабочего пространства в локальном репозитории и на странице github.](image/15.png){ #fig:015 width=70% }

# Задания для самостоятельной работы

(рис. [-@fig:016])

![   Перейдя по нужному пути до папки report, загружаем туда первую и вторую лабораторную работу ](image/16.png){ #fig:016 width=70% }


# Вывод

Идеология средств контроля версий изучена, приобретены практические навыки по работе с системой git, цель работы достигнута

Ссылка на мой github: https://github.com/yilancova/study_2022-2023_arh-pc/tree/master/labs
