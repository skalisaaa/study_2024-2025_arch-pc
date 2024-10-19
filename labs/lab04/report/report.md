---
## Front matter
title: "Отчёт по лабораторной работе №4"
subtitle: "Создание и процесс обработки программ на языке ассемблера NASM"
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

Освоить процедуры компиляции и сборки программ, познакомиться с языком ассемблера NASM.


# Задание

Написать 2 программы: "Hello world"; "Имя Фамилия"


# Выполнение лабораторной работы

Создаем каталог для работы с программами на языке ассемблера NASM, переходим в него и создаем текстовый файл:

![Последовательно выполняем программы, проверяем наличие файла и открываем его](image/1.png){#fig:fig1 width=70%}


После того, как открыли файл, вводим в него текст как в примере:

![Внимательно переписываем текст в файл](image/sn1.png){#fig:fig2 width=70%}


Вводим команду для превращения текста в объектный код:

![Проверяем, чтобы объектный файл был создан](image/2.png){#fig:fig3 width=70%}


Вводим команду, которая компилирует исходный файл hello.asm в obj.o:

![Проверяем наличие файлов](image/3.png){#fig:fig4 width=70%}


Передаем объектный файл на обработку компоновщику:

![С помощью команды ls проверяем, чтобы исполняемый файл hello был создан](image/4.png){#fig:fig5 width=70%}


Выполняем следующую команду:

![Проверяем наличие исполняемого файла](image/5.png){#fig:fig6 width=70%}


Запускаем на выполнение созданный исполняемый файл:

![Вводим команду ./hello](image/6.png){#fig:fig7 width=70%}


# Выполнение самостоятельной работы

В нужном каталоге создаем копию файла hello.asm с именем lab4.asm:

![Создаем и запускаем файл](image/7.png){#fig:fig8 width=70%}


Открытый файл редактиурем в соответствии с заданием:

![Вписываем имя и фамилию](image/sn2.png){#fig:fig9 width=70%}


Вводим необходимые команды для превращения текста в объектный код и превращения файла в объектный файл; выполняем компоновку объектного файла и запускаем получившийся исполняемый файл:

![Последовательно выполняем команды](image/8.png){#fig:fig10 width=70%}

![Вводим команды](image/9.png){#fig:fig11 width=70%}


С помощью команды ./hello запускаем на выполнение исполняемый файл:

![Загружаем в удалённый репозиторий](image/10.png){#fig:fig12 width=70%}


Копируем файлы hello.asm и lab4.asm в необходимый каталог:

![Вводим команды](image/11.png){#fig:fig13 width=70%}


Загружаем файлы на Github:

![Загружаем файлы в репозиторий](image/12.png){#fig:fig14 width=70%}


# Выводы

После выполнения данной самостоятельной работы я познакомилась с языком ассемблера NASM и научилась создавать работающие программы.
