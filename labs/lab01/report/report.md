---
## Front matter
title: "Отчёт по лабораторной работе №1


Информационная безопасность"
subtitle: "Настройка рабочего пространства и конфигурация операционной системы на виртуальную машину."
author: "Самсонова Мария Ильинична, 


НФИбд-02-21, 1032216526"

babel-lang: russian 
babel-otherlangs: english 
mainfont: Arial 
monofont: Courier New 
fontsize: 12pt

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

Настроить рабочее пространство для лабораторных работ, приобрести практические навыки установки операционной системы на виртуальную машину и настройки минимально необходимых для дальнейшей работы сервисов.

# Теоретическое введение

**Oracle VM VirtualBox** — это мощная и бесплатная виртуализационная платформа, разработанная корпорацией Oracle, которая позволяет пользователям создавать и управлять виртуальными машинами на своих компьютерах. [1]

# Выполнение лабораторной работы

## Установка и конфигурация операционной системы на виртуальную машину

### Virtual Box

![(рис. 1. Имя и путь  ОС)](image/1.png){ #fig:002 width=70% height=70% }

![(рис. 2. Размер пямяти и число процессоров)](image/2.png){ #fig:003 width=70% height=70% }

![(рис. 3. Виртуальный жесткий диск)](image/3.png){ #fig:004 width=70% height=70% }

![(рис. 4. Итог настроек)](image/4.png){ #fig:005 width=70% height=70% }

![(рис. 5. Носители)](image/5.png){ #fig:006 width=70% height=70% }

![(рис. 5. Запуск)](image/6.png){ #fig:006 width=70% height=70% }

![(рис. 7. Стартовое меню установки)](image/7.png){ #fig:007 width=70% height=70% }

![(рис. 8. Root password)](image/8.png){ #fig:008 width=70% height=70% }

![(рис. 9. Create User)](image/9.png){ #fig:009 width=70% height=70% }

![(рис. 10. Ethernet)](image/10.png){ #fig:010 width=70% height=70% }

![(рис. 11. Keyboard)](image/11.png){ #fig:011 width=70% height=70% }

![(рис. 12. Установки системы)](image/12.png){ #fig:012 width=70% height=70% }

### Переход в ОС Linux

![(рис. 13. успешное создание пользователя)](image/18.png){ #fig:013 width=70% height=70% }

![(рис. 14. Вхождение в систему)](image/19.png){ #fig:014 width=70% height=70% }

### Домашнее задание

![(рис. 15. dmesg)](image/13.png){ #fig:015 width=70% height=70% }

![(рис. 16. dmesg | less)](image/14.png){ #fig:016 width=70% height=70% }

![(рис. 17. Объем доступной оперативной памяти, версия ядра линукс, частота процессора, модель процессора, тип файловой системы корневого раздела )](image/15.png){ #fig:017 width=70% height=70% }

![(рис. 18. Последовательность монтирования файловых систем)](image/16.png){ #fig:018 width=70% height=70% }


# Вывод

Были настроено рабочее пространство для лабораторных работ, приобретены практические навыки
установки операционной системы на виртуальную машину и настройки минимально необходимых для дальнейшей работы сервисов.

# Список литературы. Библиография

[1] Документация по Virtual Box: https://www.virtualbox.org/wiki/Documentation
