# Разметка видеоконтента
![](https://img.shields.io/badge/Made_by-НКЭиВТ-blue) ![](https://img.shields.io/badge/Python-3.12.X-yellow)  ![](https://img.shields.io/badge/torch-2.4.1-green) ![](https://img.shields.io/badge/OpenCV-4.10.0-darkblue)
## Содержание
  - [О нас:](#о-нас)
    - [Состав команды:](#состав-команды)
  - [Описание проекта:](#описание-проекта)
  - [Руководство пользователя:](#руководство-пользователя)

## О нас:

Мы команда из колледжа [НКЭиВТ](http://www.nke.ru/), представляем этот проект следующим составом:

#### Состав команды:

- Христофорова Алёна - Тимлид и разработчик
- Довгаль Александр - Разработчик
- Котлубовский Антон - Разработчик
- Попенко Захар - Разработчик
- Латыпов Руслан - Разработчик

## Описание проекта:

Проект был написан, используя torch 2.4.1, OpenCV 4.9.0, Python 3.12.X для Всероссийского хакатона Цифрового прорыва кейса «Разметка видеоконтента»

В release находятся исходники сайта, в vseros_bot.zip исходники тг-бота 

В YOLO.ipynb детекция, в Hacks_AI_2.ipynb транскрибация, в GraphCommit.ipynb анализ звукового ряда

Демо проекта: https://coldboy.ru/nkeivt_hackaton/

Демо тг-бота: https://t.me/vseros_tg_bot

## Руководство пользователя:

Наше решение представляет собой веб-сервис. 
На веб-сервисе есть четыре кнопки: выберите файл (аудио/видео) и функционал:
- Transcribe & Analyze Sentiment (транскрибация и анализ тональности): система отделяет видеоряд от звука, переводит звук в текст и анализирует тональность, а также модерирует по Base/Black.
- Analyze Audio (анализ аудио): система отделяет видеоряд от звука, анализирует аудио (выявляет тональность, изменение интонации и потенциальные моменты для модерации/промо)
- Detect Objects (обнаружение объектов): система выделяет объекты, символы и сцены и классифицирует их (находит категорию, к которой относится объект/символ/сцена)
