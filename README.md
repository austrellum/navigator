# Навигатор бордосферы

> **⚠️ Активная разработка!** Структура и содержимое проекта могут быть значительно изменены без дополнительных уведомлений

«Навигатор» — это независимый каталог русскоязычных борд, доступный в нескольких форматах:

**[Веб-страница](https://austrellum.github.io/navigator)** · **[Markdown](./index.md)** · [Простой текст](./index.txt) · [HTML](./index.html) · [JSON](./index.json) ([API endpoint](https://austrellum.github.io/navigator/index.json))

## Зачем нужен еще один каталог?

Существующие решения имеют ряд взаимосвязанных недостатков, таких как:

  - **Технологическое устаревание** — например, у [overchan.ru](http://overchan.ru/), где до сих пор используются фреймы и верстка не адаптирована под мобильные устройства
  - **Громоздкость списков** — обычно проявляется у википодобных каталогов, например у [Неолурка](https://neolurk.org/wiki/%D0%A1%D0%BF%D0%B8%D1%81%D0%BE%D0%BA_%D1%80%D1%83%D1%81%D1%81%D0%BA%D0%BE%D1%8F%D0%B7%D1%8B%D1%87%D0%BD%D1%8B%D1%85_%D0%B8%D0%BC%D0%B8%D0%B4%D0%B6%D0%B1%D0%BE%D1%80%D0%B4). Такими каталогами не всегда удобно пользоваться, они занимают несколько десятков экранов своими безразмерными таблицам и содержат много лишней информации
  - **Предвзятость суждений** — каталоги содержат обширные описания борд, основанные на взаимных претензиях, разногласиях, местечковых форсах и т.п.
  - **Чрезмерный охват** — каталоги пытаются охватить борды всех времен, народов и языков вместе с их разделами и движками в придачу. Особенно это видно, например, у [imageboards.json](https://github.com/ccd0/imageboards.json)
  - **Неактуальность информации** — сведения в каталоге отстают на несколько лет или даже больше, значительная часть борд в таком каталоге уже давно закрылась
  - **Закрытость формата** — сам каталог тяжело поддерживать (в частности — обновлять) и, при необходимости, переносить (например, на новый движок)

«Навигатор» создан с учетом этих проблем:

  - Вместо сложных движков и БД используются обычные файлы в простых, проверенных временем форматах
  - Вместо излишне широкого фронта работ обозначена относительно небольшая прослойка сайтов и требований к ним
  - Вместо одного формата предоставляется сразу несколько вариантов просмотра и использования данных

Все это позволяет легко хранить, обновлять и распространять каталог «Навигатора». В случае *непредвиденных ситуаций* любой желающий сможет легко продолжить дело, оформив свой форк, или скопировав содержимое каталога любым удобным способом.

## Какие ссылки попадают в «Навигатор»?

Ссылка попадает в каталог, если она ведет на существующую борду, где есть общение на русском языке — полностью, или в некоторой степени. При этом допустимо расположение борды как в [клирнете](https://en.wikipedia.org/wiki/Clearnet_(networking)), так и в [скрытносетях](https://en.wikipedia.org/wiki/Deep_web); борда может считаться заблокированной владельцем или третьими лицами.

В каталог также попадают борды-анклавы и русскоязычные разделы международных борд.

### Категории

Для дополнительного упорядочивания борды распределяются по трем *категориям*:

  - **Общее** — хорошие борды для любых тем
  - **Тематика** — хорошие борды, полностью или частично посвященные определенной теме, вопросу, фандому и т.п.
  - **Мусор** — низкокачественные борды, обладающие *характерными признаками*, включая:
    - Намеренное копирование атрибутов другого, более успешного проекта (обычно уже закрытого) — использование идентичного движка, схожих названий, доменов и т.п; настойчивые попытки паразитировать на таких атрибутах
    - Явное наличие персонализированных *бложеков*, *чятеков*; аватаркофагов, неймфагов и подобных персоналий
    - Заброшенность, отсутствие признаков активности, запустение, нестабильная работа сайта, нерабочие критически важные элементы (например, постинг)
    - Наличие явно бессмысленного или вредящего контента: щитпостинг, шизофорсы, гуро, спам, вайп и т.п.

## Источники

### Русскоязычные

  - [Овернульч (0chan.one)](https://0chan.one/)
  - [Отечественные имиджборды (wiki.1chan.ca)](https://wiki.1chan.ca/%D0%9E%D1%82%D0%B5%D1%87%D0%B5%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D1%8B%D0%B5_%D0%B8%D0%BC%D0%B8%D0%B4%D0%B6%D0%B1%D0%BE%D1%80%D0%B4%D1%8B)
  - [Список русскоязычных имиджборд (neolurk.org)](https://neolurk.org/wiki/%D0%A1%D0%BF%D0%B8%D1%81%D0%BE%D0%BA_%D1%80%D1%83%D1%81%D1%81%D0%BA%D0%BE%D1%8F%D0%B7%D1%8B%D1%87%D0%BD%D1%8B%D1%85_%D0%B8%D0%BC%D0%B8%D0%B4%D0%B6%D0%B1%D0%BE%D1%80%D0%B4)
  - [Список имиджбордов (dollchan.net/chanlist)](https://dollchan.net/chanlist/) — 2022-10-06
  - [Русский Overchan (overchan.ru)](http://overchan.ru/) — ~2020

### Международные

  - [github.com/ccd0/imageboards.json](https://github.com/ccd0/imageboards.json) — 2022-04-13
  - [gitgud.io/iblist/imageboards.json](https://gitgud.io/iblist/imageboards.json) — 2022-01-01
  - [gitgud.io/iblist/textboards.json](https://gitgud.io/iblist/textboards.json) — 2022-01-01

## См. также

  - [CHANGELOG](./CHANGELOG.md)
  - [LICENSE](./LICENSE)
