---
## Front matter
lang: ru-RU
title: ОС
author: Лефтеров Игорь НПИ-01-21
institute: Москва,РУДН, 2022
date: Москва, 28 апреля 2022г

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# Отчет по лабораторной работе №3 Лефтеров Игорь

# Цель работы

Изучить идеологию и применение средств контроля версий. Освоить умения по работе с git.


# Задание

-Сделайте отчет по предыдущей лабораторной работе в формате MD.
-В качестве отчета предоставить отчеты в 3 форматах: pdf, docx и md.


# Выполнение лабораторной работы

Создаем учетную запись на github.com.

![Учетная запись](image/1.png){ #fig:001 width=70% }

## Настройка

Настраиваем систему контроля версий git. Синхранизируем учётную запись github с компьютером:
git config --global user.name"Имя Фамилия"
git config --global user.email"work@mail"
После этого создаём новый ключ на github (команда ssh-keygen -C"lefterov33 <lefterov_33@mail>") и привязываем его к компьютеру через консоль.
Базовая настройка git
![Зададим имя и почту](image/2.png){ #fig:002 width=70% }

## Настройка git

Настроим utf-8 в выводе сообщений git, настройка верификации и подписание коммитов, зададим имя начальной ветки(будем называть ее master), параметр auticrlf,  параметр safecrlf.
![Настройка](image/3.png){ #fig:003 width=70% }

## Создание ключа shh

Создание ключа shh.
![Ключ shh](image/4.png){ #fig:004 width=70% }

## Добавление ключа на гит

Добавление ключа на git.
![Добавление ключа shh](image/5.png){ #fig:005 width=70% }

## Создание ключа пгп

Создание ключа pgp.
![Ключ pgp](image/6.png){ #fig:006 width=70% }

## Добавление ключа пгп

Добавление ключа gpg.
![Добавление ключа pgp](image/7.png){ #fig:007 width=70% }

## Настройка

Настройка автоматических подписей коммитов git.
![Настройка коммитов](image/8.png){ #fig:008 width=70% }

## Настройка

Настройка авторизации gh(gh auth login).
![Настройка gh](image/9.png){ #fig:009 width=70% }

## Удаление

Удаление лишнего файла.
![Удаление файла package.json](image/10.png){ #fig:010 width=70% }

## Настройка

Настрйока каталога курса(git push).
![Настройка каталога](image/11.png){ #fig:011 width=70% }

# Выводы

В ходе выполнения данной лабораторной работы были приобретены практические навыки git на виртуальную машину, а также настройка дополнительный для работы сервисов.


## {.standout}

Wer's nicht glaubt, bezahlt einen Taler
