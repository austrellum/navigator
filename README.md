# Навигатор бордосферы

> **⚠️ Активная разработка!** Структура и содержимое проекта могут быть значительно изменены без дополнительных уведомлений

> 🗳️ Редакция «Навигатора» проводит опрос о состоянии и развитии бордосферы — ты можешь **[принять участие!](https://tally.so/r/3jPop4)**

«Навигатор бордосферы» — это независимый каталог русскоязычных борд, доступный в нескольких форматах.

**[Веб-страница](https://austrellum.github.io/navigator)** · **[Markdown](./index.md)** · [Полный список](#доступные-форматы)

## Содержание

  - [О «Навигаторе»](#о-навигаторе)
    - [Зачем еще один каталог](#зачем-еще-один-каталог)
    - [Как добавить новую ссылку](#как-добавить-новую-ссылку)
    - [Какие ссылки попадают в каталог](#какие-ссылки-попадают-в-каталог)
    - [Почему только русскоязычные](#почему-только-русскоязычные)
    - [Как часто выходят новые редакции](#как-часто-выходят-новые-редакции)
    - [Использование материалов «Навигатора»](#использование-материалов-навигатора)
  - [Условные обозначения](#условные-обозначения)
    - [Разделы](#разделы)
    - [Теги](#теги)
  - [Доступные форматы](#доступные-форматы)
    - [ccd0/imageboards.json](#ccd0imageboardsjson)
  - [Источники](#источники)
    - [Русскоязычные](#русскоязычные)
    - [Международные](#международные)
  - [Обратная связь](#обратная-связь)
  - [Отказ от ответственности](#отказ-от-ответственности)
  - [См. также](#см-также)

## О «Навигаторе»

### Зачем еще один каталог

Существующие решения имеют ряд взаимосвязанных недостатков, включая:

  - **Технологическое устаревание** — например, у [overchan.ru](http://overchan.ru/), где до сих пор используются фреймы, и верстка не адаптирована под мобильные устройства
  - **Громоздкость списков** — обычно у википодобных каталогов, например, у [Неолурка](https://neolurk.org/wiki/%D0%A1%D0%BF%D0%B8%D1%81%D0%BE%D0%BA_%D1%80%D1%83%D1%81%D1%81%D0%BA%D0%BE%D1%8F%D0%B7%D1%8B%D1%87%D0%BD%D1%8B%D1%85_%D0%B8%D0%BC%D0%B8%D0%B4%D0%B6%D0%B1%D0%BE%D1%80%D0%B4), список занимает несколько десятков экранов и содержит много нерелевантной информации
  - **Предвзятость суждений** — обширные описания, основанные на взаимных претензиях, разногласиях, местечковых форсах, мемах и т.п.
  - **Чрезмерный охват** — попытки охватить борды всех времен, народов и языков вместе с их разделами и движками, как, например, в [imageboards.json](https://github.com/ccd0/imageboards.json)
  - **Неактуальность информации** — данные устаревают на несколько лет или больше, значительная часть борд в таких каталогах давно закрылась
  - **Закрытость формата** — каталог тяжело поддерживать (в частности — обновлять) и, при необходимости, переносить (например, на новый движок)

«Навигатор» был создан с учетом этих проблем:

  - Вместо сложных технологий используются обычные файлы простых форматов
  - Вместо широкого фронта работ обозначена небольшая прослойка сайтов и требований к ним
  - Вместо одного формата предоставляется сразу несколько вариантов просмотра и использования данных

Все это позволяет легко хранить, обновлять и распространять каталог «Навигатора». В случае *непредвиденных ситуаций* любой желающий сможет легко продолжить дело, оформив свой форк, или скопировав содержимое каталога любым удобным способом.

### Как добавить новую ссылку

Самостоятельно — пока никак, но можно оставить ссылку через [обратную связь](#обратная-связь), и, если такая ссылка соответствует [критериям](#какие-ссылки-попадают-в-каталог), то она появится в следующей редакции.

### Какие ссылки попадают в каталог

Ссылка попадет в каталог, если она ведет на существующую борду, где есть общение на русском языке — полностью, или частично. В каталог также попадают русскоязычные разделы зарубежных борд и т.п.

### Почему только русскоязычные

К сожалению, при текущих возможностях, собрать все борды со всего интернета будет слишком сложно — список получится очень большим, и, скорее всего, он никогда не будет актуальным.

### Как часто выходят новые редакции

Ориентировочный срок — ежемесячно в первых числах, но это не строгое правило.

В период активной разработки возможны более частые выпуски.

### Использование материалов «Навигатора»

Приветствуется использование и распространение материалов «Навигатора бордосферы»: потенциально это может способствовать развитию как русскоязычной, так и общей, международной бордосферы.

Важно отметить, что приветствуется *ненасильственное распространение*, т.е. распространение в специально предназначенных для этого местах (например, в тредах для пиара) или с явного согласия местной администрации.

## Условные обозначения

### Разделы

Каталог «Навигатора» делится на разделы, каждый из которых соответствует этапу [жизненного цикла сайта](#cycle).

Сайты внутри разделов отсортированы по дате открытия (от новых — к старым).

  - Если известна только частичная дата открытия (только год, или только год и месяц), то такие сайты располагаются в начале периода, т.е. в начале года или года и месяца соответственно
  - Если дата открытия неизвестна, то такие сайты располагаются в конце соответствующих разделов

### Теги

Для каждого сайта назначается набор тегов, характеризующих сайт.

Теги имеют *иерархическую структуру*, т.е. существуют теги-предки и теги-потомки. В разделах ниже теги-предки обозначены как `#parent-tag`, а теги-потомки — `#parent-tag:child-tag`.

#### #diff

Теги, определяющие разницу в изменениях между различными редакциями каталога.

*Эти теги отображаются только в JSON-версии, в остальных версиях применяется специальное оформление.*

#### #diff:new

Сайт добавлен в текущей редакции.

#### #diff:lower

Сайт отмечен к перемещению в следующей редакции.

В большинстве случаев это означает, что сайт будет перемещен вниз по жизненному циклу — например, от «живых» к «отмирающим».

В отдельных случах подразумевается полное удаление сайта к следующей редакции.

#### #cycle

Теги, определяющие жизненный цикл сайта (от открытого к закрытому).

Если сайт имеет несколько адресов, то используется более «активный» тег. Например, если сайт недоступен доступен по адресу example.org, но доступен по адресу example.i2p, то такой сайт будет помечен как #live.

*Эти теги отображаются только в JSON-версии, в остальных версиях применяется специальное оформление.*

#### #cycle:live

Раздел: «Живые».

Сайт полноценно работает, содержимое сайта поддерживается в актуальном состоянии.

Формально живым считается сайт, пополняющийся новым и осмысленным содержимым раз в месяц или чаще.

#### #cycle:ghost

Раздел: «Отмирающие».

Сайт работает нерегулярно, содержимое обновляется редко, либо не обновляется уже значительное время.

#### #cycle:readonly

Раздел: «Только чтение».

Сайт поддерживает только чтение, добавление нового содержимого невозможно из-за некой технической неисправности.

#### #cycle:stub

Раздел: «Заглушки».

Сайт отображает только главную страницу-заглушку, никакое другое содержимое сайта не доступно.

#### #cycle:dead

Раздел: «Мертвые».

Сайт и его содержимое недоступны ни по одной из ссылок.

#### #net

Теги, определяющие сети, в которых доступен сайт.

*Эти теги отображаются только в JSON-версии.*

#### #net:www

Сайт доступен в клирнете.

См. [Clearnet (Wikipedia)](https://en.wikipedia.org/wiki/Clearnet_(networking))

#### #net:tor

Сайт доступен в сети Tor.

См. [Darknet (Wikipedia)](https://en.wikipedia.org/wiki/Darknet), [Tor (Wikipedia)](https://en.wikipedia.org/wiki/Tor_(network))

#### #net:i2p

Сайт доступен в сети I2P.

См. [Darknet (Wikipedia)](https://en.wikipedia.org/wiki/Darknet), [I2P (Wikipedia)](https://en.wikipedia.org/wiki/I2P)

#### #net:loki

Сайт доступен в сети Lokinet.

См. [Darknet (Wikipedia)](https://en.wikipedia.org/wiki/Darknet)

#### #access

Теги, определяющие виды доступа к сайту.

#### #access:limited

Доступ к сайту значительно ограничен владельцем сайта.

Обычно это означает, что владелец сайта хочет ограничить приток нежелательной аудитории. Типичные примеры таких ограничений:

  - Необходимость регистрации новой учетной записи
  - Система приглашений (инвайты)
  - Специфичная капча (математическая капча, капча с малоизвестными персонажами и т.п.)
  - Блокировка по географической привязке IP-адресов

#### #access:blocked

Доступ к сайту заблокирован третьими лицами.

Подразумевается, что доступ заблокирован для значительного диапазона IP-адресов.

Обычно такие блокировки применяются представителями властей — для ограничения доступа к содержимому, запрещенному местным законодательством.

#### #community

Теги, определяющие принадлежность сайта к широко известным и характерным сообществам.

#### #community:iich

iichan.ru и связанные сайты.

См. [Ычан (Колчевики)](https://wiki.1chan.ca/%D0%AB%D1%87%D0%B0%D0%BD).

#### #community:ex0ch

Пост-0chan.ru и связанные сайты.

См. [Нульчан (Колчевики)](https://wiki.1chan.ca/%D0%9D%D1%83%D0%BB%D1%8C%D1%87%D0%B0%D0%BD).

#### #community:ex1ch

Пост-1chan.ru и связанные сайты.

См. [Одинчан (Колчевики)](https://wiki.1chan.ca/%D0%9E%D0%B4%D0%B8%D0%BD%D1%87%D0%B0%D0%BD).

#### #community:ex2ch

Пост-2ch.ru и связанные сайты.

См. [Двач (Колчевики)](https://wiki.1chan.ca/%D0%94%D0%B2%D0%B0%D1%87).

#### #community:exapach

Пост-apachan.net и связанные сайты.

См. [Апачан (Колчевики)](https://wiki.1chan.ca/%D0%90%D0%BF%D0%B0%D1%87%D0%B0%D0%BD)

#### #community:foreign

Зарубежный сайт с русскоязычным содержимым.

#### #quality

Теги, определяющие качество содержимого сайта.

#### #quality:cheap

Бесплатная или базовая инфраструктура для сайта: хостинг с начальным или демонстрационным тарифом, временный домен третьего уровня и т.п.

#### #quality:clone

Намеренное копирование атрибутов сторонних, никак не связанных проектов: использование идентичного движка, схожих названий, доменов и т.п; явные попытки паразитировать на таких атрибутах.

Формально сайт считается клоном в двух случаях:

  1. Для сайта используется домен, схожий или идентичный домену стороннего проекта
  2. Для сайта одновременно используются движок и визуальное оформление, схожие или идентичные движку и визуальному оформлению стороннего проекта

#### #quality:comfy

Положительный опыт использования (UX/UI). Адаптивный дизайн, правильная цветовая палитра, в целом удобный интерфейс, доступный для большинства популярных платформ.

#### #quality:obscure

Нестандартная концепция использования. Обычно выражается в не-классическом интерфейсе и способах взаимодействия с ним.

#### #quality:fags

Явное присутствие персонифицированных *бложеков*, *чятеков*; аватаркофагов, неймфагов и т.п.

#### #quality:mods

Злоупотребление модераторскими полномочиями.

#### #quality:wild

Явное присутствие бессмысленного или вредящего контента: щитпостинг, шизофорсы, гуро, спам, вайп и т.п.

#### #service

Теги, определяющие сервисы, предоставляемые сайтом.

#### #service:archive

Статичные страницы и другое содержимое, предназначенное только для чтения. Обычно в архив заносятся неактуальные разделы [борд](#serviceboard), реже — сами борды, целиком.

В отличие от [#readonly](#cyclereadonly), содержимое становится архивным намеренно, а не из-за технической неисправности.

#### #service:blog

Персональный или коллективный блог, личная страница.

#### #service:board

Форумоподобная дискуссионная площадка.

Обычно использует специфичный движок с характерным интерфейсом и поддержкой (псевдо-)анонимного использования.

*Этот тег отображается только в JSON-версии, в остальных версиях применяется специальное оформление.*

#### #service:chat

Чат, чатоподобная площадка для общения.

#### #service:gallery

Коллекция тематических изображений.

#### #service:index

Список ссылок, имеющих отношение к бордосфере. Обычно большая часть таких ссылок ведет на [борды](#serviceboard).

#### #service:news

Новости, обзоры и обсуждения последних событий.

#### #service:stream

Интернет-радио, стримы и другое потоковое содержимое.

#### #service:wiki

База знаний, вики-система.

#### #locale

Теги, определяющие набор языков, используемых на сайте.

  - #locale:ar — Арабский язык
  - #locale:de — Немецкий язык
  - #locale:en — Английский язык
  - #locale:eo — Эсперанто
  - #locale:es — Испанский язык
  - #locale:fi — Финский язык
  - #locale:hu — Венгерский язык
  - #locale:id — Индонезийский язык
  - #locale:it — Итальянский язык
  - #locale:ja — Японский язык
  - #locale:ko — Корейский язык
  - #locale:lt — Литовский язык
  - #locale:pl — Польский язык
  - #locale:pt — Португальский язык
  - #locale:ru — Русский язык
  - #locale:tr — Турецкий язык
  - #locale:uk — Украинский язык
  - #locale:zh-hk — Китайский язык (Китайский традиционный)

*Эти теги отображаются только в JSON-версии, в остальных версиях применяется специальное оформление.*

## Доступные форматы

Оригинальный каталог «Навигатора» можно выгрузить в следующих форматах:

  - [JSON](./index.json) · [API endpoint](https://austrellum.github.io/navigator/index.json)
  - [HTML](./index.html) · [Веб-страница](https://austrellum.github.io/navigator)
  - [OPML](./index.opml)
  - [Markdown](./index.md)
  - [Простой текст](./index.txt)

### ccd0/imageboards.json

Схема, представленная в проекте [ccd0/imageboards.json](https://github.com/ccd0/imageboards.json) — это стандарт де-факто в международной бордосфере. Каталог «Навигатора» доступен в двух версиях этой схемы:

  - [Полный список](./index.full.ccd0-compat.json) · [API endpoint](https://austrellum.github.io/navigator/index.full.ccd0-compat.json) — все сайты «Навигатора»
  - [Только подходящие](./index.ccd0-compat.json) · [API endpoint](https://austrellum.github.io/navigator/index.ccd0-compat.json)

Под подходящими понимаются сайты, которые соответствуют критериям оригинального проекта:

> Archives and closed boards that it is no longer possible to post to will not be listed. To avoid disturbing very slow boards, sites will not be listed unless they have at least 12 posts per year.
>
> —
>
> *Архивы и закрытые борды, на которых больше нельзя постить, не будут указываться в списке. Чтобы не беспокоить очень медленные борды, они не будут указаны в списке, если на них будет менее 12 постов за год.* — пер.

Таким образом, подходящими будут считаться сайты, которые одновременно:

  1. Являются сравнительно активными, т.е. имеют тег [#live](#cyclelive), или [#ghost](#cycleghost)
  2. Являются бордами, или определяют себя около-бордами, т.е. имеют тег [#board](#serviceboard), или [#chat](#servicechat)

## Источники

### Русскоязычные

  - [Овернульч (0chan.one)](https://0chan.one/)
  - [Отечественные имиджборды — Колчевики (wiki.1chan.ca)](https://wiki.1chan.ca/%D0%9E%D1%82%D0%B5%D1%87%D0%B5%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D1%8B%D0%B5_%D0%B8%D0%BC%D0%B8%D0%B4%D0%B6%D0%B1%D0%BE%D1%80%D0%B4%D1%8B)
  - [Список русскоязычных имиджборд — Неолурк (neolurk.org)](https://neolurk.org/wiki/%D0%A1%D0%BF%D0%B8%D1%81%D0%BE%D0%BA_%D1%80%D1%83%D1%81%D1%81%D0%BA%D0%BE%D1%8F%D0%B7%D1%8B%D1%87%D0%BD%D1%8B%D1%85_%D0%B8%D0%BC%D0%B8%D0%B4%D0%B6%D0%B1%D0%BE%D1%80%D0%B4)
  - [Русский Overchan (overchan.ru)](http://overchan.ru/)
  - [Список имиджбордов (dollchan.net)](https://dollchan.net/chanlist/) — 2022-10-06

### Международные

  - [chan.city](https://chan.city/)
  - [github.com/ccd0/imageboards.json](https://github.com/ccd0/imageboards.json) — 2022-04-13
  - [gitgud.io/iblist/imageboards.json](https://gitgud.io/iblist/imageboards.json) — 2022-01-01
  - [gitgud.io/iblist/textboards.json](https://gitgud.io/iblist/textboards.json) — 2022-01-01

## Обратная связь

Для быстрой обратной связи в привычном анонимном формате можно использовать [тред на Ноунейм Параше](https://wc.12hp.ch/wc/res/2577.html).

Также принимаются [Issues](https://github.com/austrellum/navigator/issues) в этом репозитории.

## Отказ от ответственности

«Навигатор бордосферы» и лица, отвечающие за составление каталога, не имеют прямого отношения к ссылкам, перечисленным в каталоге — кроме случаев, когда иное явно указано. Посетители могут использовать ссылки каталога, а также содержимое, доступное через эти ссылки, исключительно на свой страх и риск.

—

«Navigator bordosfery» and the entities responsible for its catalog compiling are not directly affiliated with the links listed in the catalog unless otherwise is stated explicitly. One may use the catalog links, as well as the content available through those links, solely at its own risk.

## См. также

  - [CHANGELOG](./CHANGELOG.md)
  - [LICENSE](./LICENSE)
