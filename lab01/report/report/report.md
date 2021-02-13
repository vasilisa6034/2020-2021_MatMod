---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе 1"
subtitle: "дисциплина: Математическое моделирование"
author: "Василиса Михайловна Крючкова, НПИбд-02-18"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Начать знакомство с GitHub и GitBash, начать изучение языка Markdown.

# Задание

- Подготовиться к работе с git
- Создать репозиторий и файл
- Подгрузить этот файл в git
- Настроить SSH ключ


# Выполнение лабораторной работы

1. Установила имя и электронную почту. Настроила параметры установки окончаний строк. 
Установила отображение unicode. (см. рис. -@fig:001)

![Подготовка к работе с git](image/1.png){ #fig:001 width=70% }

2. Создала git репозиторий и файл README.md в своем рабочем каталоге. (см. рис. -@fig:002)

![Создание репозитория и файла](image/2.png){ #fig:002 width=70% }

3. Добавила в файл запись "# Математическое моделирование". (см. рис. -@fig:003)

![Запись в файл](image/3.png){ #fig:003 width=70% }

4. Добавила файл в репозиторий и сделала коммит. (см. рис. -@fig:004)

![Добавление файла в репозиторий, коммит](image/4.png){ #fig:004 width=70% }

5. Подгрузила свой репозиторий на git. (см. рис. -@fig:005)

![Пуш на git](image/5.png){ #fig:005 width=70% }

6. Создала на компьютере SSH ключ и добавила его на git. (см. рис. -@fig:006)

![Создание SSH ключа](image/6.png){ #fig:006 width=70% }

7. Подключилась по SSH ключу. (см. рис. -@fig:007)

![Подключение по SSH ключу](image/7.png){ #fig:007 width=70% }

# Выводы

Начала знакомство с GitHub и GitBash, начала изучение языка Markdown.
