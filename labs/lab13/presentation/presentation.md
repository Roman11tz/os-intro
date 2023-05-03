---
## Front matter
lang: ru-RU
title: Лабораторная работа №13
subtitle: Кавказова Диана Алексеевна
author:
author:
  - Кавказова Д.А.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 3 мая 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

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

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Кваказова Диана Алексеевна
  * НБИбд-01-22
  * Российский университет дружбы народов
  
:::
::::::::::::::



## Актуальность

- Для учащихся в сфере IT необходимо уметь работать с файлами через терминал на основе Linux.

## Объект и предмет исследования

- Основы интерфейса взаимодействия
пользователя с системой Unix на уровне командной строки
- Операционные системы

## Цели и задачи

- Изучить материал по созданию лабораторной
- Выполнить необходимые действия поэтапно


## шаг 1

В домашнем каталоге создаём подкаталог ~/work/os/lab_prog. Создаём в нём файлы: calculate.h, calculate.c, main.c.

![рисунок](image/1.png){#fig:001 width=95%}

## шаг 2

При необходимости исправьте синтаксические ошибки. Создаём Makefile.


![рисунок](image/2.png){#fig:002 width=95%}

## шаг 3

С помощью gdb выполняем отладку программы calcul (перед использованием gdb
исправьте Makefile):
– Запускаем отладчик GDB, загрузив в него программу для отладки.


![рисунок](image/3.png){#fig:003 width=95%}

## шаг 4
С помощью утилиты splint попробуум проанализировать коды файлов calculate.c
и main.c

![рисунок](image/4.png){#fig:004 width=95%}



## Вывод

Познакомились с операционной системой Linux. Получили практические навыки рабо-
ты с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

:::

