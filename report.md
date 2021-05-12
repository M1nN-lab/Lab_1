---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе 1"
subtitle: "дисциплина: Математическое моделирование"
author: "Пейтель Андрей Андреевич, НПИбд-02-18"

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

# Выполнение лабораторной работы

1. Установил имя и электронную почту. Настроил параметры установки окончаний строк. 
Установил отображение unicode. (см. рис. -@fig:001)

![Подготовка к работе с git](image/1.png){ #fig:001 width=70% }

2. Создал git репозиторий  (см. рис. -@fig:002)

![Создание репозитория ](image/2.png){ #fig:002 width=70% }

3.  Проверка состояние репозитория. (см. рис. -@fig:003)

![Проверка](image/3.png){ #fig:003 width=70% }

4.  Добавьте стандартные теги страницы (см. рис. -@fig:004)

![Логи](image/4.png){ #fig:004 width=70% }

5. Просмотрел логи (см. рис. -@fig:008)

![Логи](image/8.png){ #fig:008 width=70% }

6. Изменил hello.html (см. рис. -@fig:0014)

![Изменил файл](image/14.png){ #fig:0014 width=70% }

7. Добавил каталог .git (см. рис. -@fig:0026)

![Каталог .git](image/26.png){ #fig:0026 width=70% }

8. Изменил основную страницу { #fig:0022 width=70% }

![Изменил основую страницу](image/22.png){ #fig:0022 width=70% }

9. Создал клон репозитория hello { #fig:0044 width=70% }

![Создал клон](image/44.png){ #fig:0044 width=70% }

10. Научился извлекать изменения из общего репозитория { #fig:0046 width=70% }

![Извлечения общих изменений](image/46.png){ #fig:0046 width=70% }


# Выводы

Начал знакомство с GitHub и GitBash, начал изучение языка Markdown.
