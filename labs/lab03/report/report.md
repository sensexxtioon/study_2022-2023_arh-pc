---
## Front matter
title: "Лаболаторная работа №3"
subtitle: "Архитектура вычислительных систем"
author: "Федоров Андрей Андреевич"

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

Целью работы является освоение процедуры оформления отчетов с помощью
легковесного языка разметки Markdown


# Задание

1. В соответствующем каталоге сделайте отчёт по лабораторной работе No 3
в формате Markdown. В качестве отчёта необходимо предоставить отчёты
в 3 форматах: pdf, docx и md.ig:001 width=90% }
2. Загрузите файлы на github.


# Выполнение лабораторной работы
1. Я открыл терминал

2. Я открыл терминал и перешёл в каталог курса сформированный при выполнении лаборатор-
ной работы No3 как на рисунке и обновил локальный репозиторий, скачав изменения из удаленного репозитория с помощью команды git pull [-@fig:001]

![терминал](image/1.png){ #fig:001 width=90% }

3. Я Перешёл в каталог с шаблоном отчета по лабораторной работе No 3 [-@fig:002]

![терминал](image/2.png){ #fig:002 width=90% }

4. Я провёл компиляцию шаблона с использованием Makefile. Для этого ввёл команду make [-@fig:003]

![терминал](image/3.png){ #fig:003 width=90% }

5. Я Удалил полученный файлы с использованием Makefile. Для этого ввел команду make clean (но она у меня не сработала по каким-то причинам)

6. Я открыл фаил report.md с помощью getdit [-@fig:004]

![терминал](image/4.png){ #fig:004 width=90% }

7. Я заполнил и скомпилировал отчёт с использованием Makefile

8. Я загрузил файлы на гитхаб


# Выводы
Я освоил процедуры оформления отчетов с помощью легковесного языка разметки Markdown

# Список литературы{.unnumbered}

::: {#refs}
:::
