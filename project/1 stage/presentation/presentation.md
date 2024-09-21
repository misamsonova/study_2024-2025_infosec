---
## Front matter
lang: ru-RU
title: "Этап индивидуального проекта №1"
subtitle: "Установка и конфигурация операционной системы на виртуальную машину"
author: " Самсонова М.И. Группа НФИбд-02-21 "


## i18n babel
babel-lang: russian 
babel-otherlangs: english 
mainfont: Arial 
monofont: Courier New 
fontsize: 12pt

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Цель работы

Настроить рабочее пространство для индивидуального проекта, приобрести практические навыки установки операционной системы на виртуальную машину и настройки минимально необходимых для дальнейшей работы сервисов.

# Теоретическое введение

**Oracle VM VirtualBox** — это мощная и бесплатная виртуализационная платформа, разработанная корпорацией Oracle, которая позволяет пользователям создавать и управлять виртуальными машинами на своих компьютерах. [1]

**Kali Linux (ранее известный как BackTrack Linux)** - это дистрибутив Linux на базе Debian с открытым исходным кодом, который позволяет пользователям проводить расширенное тестирование на проникновение и аудит безопасности. Он работает на нескольких платформах и находится в свободном доступе как для профессионалов в области информационной безопасности, так и для любителей.

Этот дистрибутив содержит несколько сотен инструментов, конфигураций и сценариев с отраслевыми модификациями, которые позволяют пользователям сосредоточиться на таких задачах, как компьютерная экспертиза, реверс-инжиниринг и обнаружение уязвимостей, вместо того чтобы заниматься несвязанными действиями.

Этот дистрибутив специально разработан с учетом потребностей опытных тестировщиков на проникновение, поэтому вся документация на этом сайте предполагает предварительное знание операционной системы Linux в целом. [2]

# Установка и конфигурация операционной системы на виртуальную машину

![(рис. 1. Имя и путь  ОС)](image/1.png){ #fig:001 width=70% height=70% }

# Установка и конфигурация операционной системы на виртуальную машину

![(рис. 2. Размер пямяти и число процессоров)](image/2.png){ #fig:002 width=70% height=70% }

# Установка и конфигурация операционной системы на виртуальную машину

![(рис. 3. Виртуальный жесткий диск)](image/3.png){ #fig:0043width=70% height=70% }

# Установка и конфигурация операционной системы на виртуальную машину

![(рис. 4. Итог настроек)](image/4.png){ #fig:004 width=70% height=70% }

# Установка носителя на виртуальную машину

![(рис. 5. Носители)](image/5.png){ #fig:005 width=70% height=70% }

# Запуск и настройки установленной работы

![(рис. 6. Запуск)](image/6.png){ #fig:006 width=70% height=70% }

# Настройки клавиатуры

![(рис. 7. Настройки клавиатуры)](image/7.png){ #fig:007 width=70% height=70% }

# Настройки клавиатуры

![(рис. 8. Настройки клавиатуры)](image/8.png){ #fig:008 width=70% height=70% }

#  Запуск компонентов с установочного носителя

![(рис. 9. Запуск компонентов с установочного носителя)](image/9.png){ #fig:009 width=70% height=70% }

# Настройки сети

![(рис. 10. Настройки сети)](image/10.png){ #fig:010 width=70% height=70% }

# Настройки сети

![(рис. 11. Настройки сети)](image/11.png){ #fig:011 width=70% height=70% }

# Настройка учетной записи пользователя 

![(рис. 12. Настройка учетной записи пользователя и пароля)](image/12.png){ #fig:012 width=70% height=70% }

# Настройка пароля для учетной записи

![(рис. 13. Настройка пароля)](image/13.png){ #fig:013 width=70% height=70% }

# Разметка дисков

![(рис. 14. Разметка дисков)](image/19.png){ #fig:014 width=70% height=70% }

# Установка базовой системы

![(рис. 15. Установка базовой системы)](image/20.png){ #fig:015 width=70% height=70% }

# Завершение установки дистрибутива Kali

![(рис. 16. Завершение установки)](image/22.png){ #fig:016 width=70% height=70% }


# Переход в ОС Linux

![(рис. 17. успешное создание пользователя)](image/24.png){ #fig:017 width=70% height=70% }

# Переход в ОС Linux

![(рис. 18. Вхождение в систему)](image/23.png){ #fig:018 width=70% height=70% }


# Вывод

Были настроено рабочее пространство для индивидуального проекта, приобретены практические навыки установки операционной системы на виртуальную машину и настройки минимально необходимых для дальнейшей работы сервисов.

# Список литературы. Библиография

[1] Документация по Virtual Box: https://www.virtualbox.org/wiki/Documentation

[2] Документация по Kali Linux: https://www.kali.org/docs/