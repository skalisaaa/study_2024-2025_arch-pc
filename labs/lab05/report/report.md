---
## Front matter
title: "Отчёт по лабораторной работе №5"
subtitle: "Основы работы с Midnight Commander"
author: "Скобеева Алиса Алексеевна"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Освоить инструкции языка ассемблера mov. Приобрести знания использования Midnight Commander. 

# Выполнение лабораторной работы

Открываем Midnight Commander:

![Вводим команду mc](image/1.png){#fig:fig1 width=70%}

Переходим в каталог, созданный при выполнении 4 лабораторной работы:

![Переходим в каталог](image/2.png){#fig:fig2 width=70%}

Создаем каталог lab05:

![Используем функциональную клавишу F7](image/3.png){#fig:fig3 width=70%}

Создаем файл lab5-1.asm с помощью команды touch и открываем его: 

![Заполняем файл по листингу](image/4.png){#fig:fig4 width=70%}

Транслируем текст программы и запускаем исполняемый файл:

![Проверяем, как работает данная программа](image/5.png){#fig:fig5 width=70%}

Скачиваем файл со страницы курса и перемещаем его в нужный каталог:

![Проверяем наличие файла](image/6.png){#fig:fig6 width=70%}

Создаем копию файла lab5-1.asm:

![Создаем копию файла клавишей F6](image/7.png){#fig:fig7 width=70%}

Проверяем созданный файл:

![Проверяем скопированный файл](image/8.png){#fig:fig8 width=70%}

Открываем созданный файл и заполняем его по листингу:

![Открываем и заполняем файл](image/9.png){#fig:fig9 width=70%}

Транслируем и запускаем новый файл:

![Смотрим, как сработала программа](image/10.png){#fig:fig10 width=70%}

Снова открываем файл для редактирования и меняем sprintLF на sprint: 

![Редактируем файл](image/11.png){#fig:fig11 width=70%}

Транслируем и запускаем файл:

![Смотрим, как сработала программа и сравниваем ее с прошлой](image/12.png){#fig:fig12 width=70%}

Таким образом, можем сделать вывод, что команда sprint выводит текст в той же строке, а sprintLF переносит текст на новую строку.


# Выполнение самостоятельной работы

Создаем копию файла lab5-1:

![Создание копии файла](image/13.png){#fig:fig13 width=70%}

Редактируем файл так, чтобы введенный текст с клавиатуры выводился в консоль:

![Редактируем файл](image/14.png){#fig:fig14 width=70%}

Транслируем файл и запускаем программу:

![Проверяем правильность написания программы](image/15.png){#fig:fig15 width=70%}

Создаем копию файла lab5-2, открываем его и редактируем так, чтобы введенный текст с клавиатуры выводился в консоль:

![Редактируем файл](image/16.png){#fig:fig16 width=70%}

Транслируем файл и запускаем программу:

![Проверяем правильность написания программы](image/17.png){#fig:fig17 width=70%}


# Выводы

Я приобрела навыки работы с Midnight Commander и освоила инструкцию mov.
