---
## Front matter
title: "Отчёт по 1 этапу индвидуального проекта


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

Настроить рабочее пространство для индивидуального проекта, приобрести практические навыки установки операционной системы на виртуальную машину и настройки минимально необходимых для дальнейшей работы сервисов.

# Теоретическое введение

**Oracle VM VirtualBox** — это мощная и бесплатная виртуализационная платформа, разработанная корпорацией Oracle, которая позволяет пользователям создавать и управлять виртуальными машинами на своих компьютерах. [1]

**Kali Linux (ранее известный как BackTrack Linux)** - это дистрибутив Linux на базе Debian с открытым исходным кодом, который позволяет пользователям проводить расширенное тестирование на проникновение и аудит безопасности. Он работает на нескольких платформах и находится в свободном доступе как для профессионалов в области информационной безопасности, так и для любителей.

Этот дистрибутив содержит несколько сотен инструментов, конфигураций и сценариев с отраслевыми модификациями, которые позволяют пользователям сосредоточиться на таких задачах, как компьютерная экспертиза, реверс-инжиниринг и обнаружение уязвимостей, вместо того чтобы заниматься несвязанными действиями.

Этот дистрибутив специально разработан с учетом потребностей опытных тестировщиков на проникновение, поэтому вся документация на этом сайте предполагает предварительное знание операционной системы Linux в целом. [2]

# Выполнение лабораторной работы

## Установка и конфигурация операционной системы на виртуальную машину

### Virtual Box

![(рис. 1. Имя и путь  ОС)](image/1.png){ #fig:001 width=70% height=70% }

![(рис. 2. Размер пямяти и число процессоров)](image/2.png){ #fig:002 width=70% height=70% }

![(рис. 3. Виртуальный жесткий диск)](image/3.png){ #fig:0043width=70% height=70% }

![(рис. 4. Итог настроек)](image/4.png){ #fig:004 width=70% height=70% }

![(рис. 5. Носители)](image/5.png){ #fig:005 width=70% height=70% }

![(рис. 6. Запуск)](image/6.png){ #fig:006 width=70% height=70% }

![(рис. 7. Настройки клавиатуры)](image/7.png){ #fig:007 width=70% height=70% }

![(рис. 8. Настройки клавиатуры)](image/8.png){ #fig:008 width=70% height=70% }

![(рис. 9. Запуск компонентов с установочного носителя)](image/9.png){ #fig:009 width=70% height=70% }

![(рис. 10. Настройки сети)](image/10.png){ #fig:010 width=70% height=70% }

![(рис. 11. Настройки сети)](image/11.png){ #fig:011 width=70% height=70% }

![(рис. 12. Настройка учетной записи пользователя и пароля)](image/12.png){ #fig:012 width=70% height=70% }

![(рис. 13. Настройка пароля)](image/13.png){ #fig:013 width=70% height=70% }

![(рис. 14. Разметка дисков)](image/19.png){ #fig:014 width=70% height=70% }

![(рис. 15. Установка базовой системы)](image/20.png){ #fig:015 width=70% height=70% }

![(рис. 16. Завершение установки)](image/22.png){ #fig:016 width=70% height=70% }


### Переход в ОС Linux

![(рис. 17. успешное создание пользователя)](image/24.png){ #fig:017 width=70% height=70% }

![(рис. 18. Вхождение в систему)](image/23.png){ #fig:018 width=70% height=70% }


# Вывод

Были настроено рабочее пространство для индивидуального проекта, приобретены практические навыки установки операционной системы на виртуальную машину и настройки минимально необходимых для дальнейшей работы сервисов.

# Список литературы. Библиография

[1] Документация по Virtual Box: https://www.virtualbox.org/wiki/Documentation

[2] Документация по Kali Linux: https://www.kali.org/docs/