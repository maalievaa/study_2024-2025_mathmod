---
## Front matter
title: "Лабораторная работа №1"
subtitle: "Настройка рабочего пространства"
author: "Алиева Милена Арифовна"

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

Настроить рабочее пространство для дальнейшей работы

# Задание

1. Настроить github
2. Настроить markdown

# Выполнение лабораторной работы

1.  Создадим новый каталог для данного курса, перейдём в него (рис. [-@fig:001]).

![Создание каталога](image/1.jpg){#fig:001 width=70%}

2. Создадим репозиторий на основе предложенного шаблона, назовём его study_2024-2025_mathmod (рис. [-@fig:002]).

![Создание репозитория](image/2.jpg){#fig:002 width=70%}

3. Клонируем репозиторий в наш каталог (рис. [-@fig:003]).

![Клонирование репозитория](image/3.jpg){#fig:003 width=70%}

4. Чтобы создать нужную структуру курса, создадим необходимые каталоги  (рис. [-@fig:004]).

![Выбираем нужный курс, создаём структуру](image/4.jpg){#fig:004 width=70%}

5. Отправим файлы на сервер (рис. [-@fig:005]).

![Отправка файлов на сервер](image/5.jpg){#fig:005 width=70%}

6. Проверим, что всё выгрузилось корректно и github готов к работе (рис. [-@fig:006]).

![Проверка корректности выполнения](image/6.jpg){#fig:006 width=70%}

# Выводы

В процессе выполнения данной лабораторной работы я настроила github для дальнейшей работы на курсе

