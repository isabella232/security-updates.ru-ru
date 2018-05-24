---
TOCTitle: Настройка технологий сетевой защиты Windows XP SP2 на малом предприятии
Title: Настройка технологий сетевой защиты Windows XP SP2 на малом предприятии
ms:assetid: 'c74175c6-46bd-4fd2-976f-9b89daf37348'
ms:contentKeyID: 20212695
ms:mtpsurl: 'https://technet.microsoft.com/ru-ru/library/Cc875819(v=TechNet.10)'
---

Как настроить технологии сетевой защиты Windows XP SP2 на малом предприятии
===========================================================================

Опубликовано 10 декабря 2004 | Обновлено 21/07/2006

##### На этой странице

[](#ehaa)[Введение](#ehaa)
[](#egaa)[Прежде чем приступить к работе](#egaa)
[](#efaa)[Применение обновлений для системы безопасности](#efaa)
[](#eeaa)[Обновление существующих объектов групповой политики](#eeaa)
[](#edaa)[Настройка объектов групповой политики](#edaa)
[](#ecaa)[О параметрах безопасности обозревателя Internet Explorer](#ecaa)
[](#ebaa)[Применение новых конфигураций с использованием утилиты GPUpdate](#ebaa)
[](#eaaa)[Дополнительные сведения](#eaaa)

### Введение

Служба каталогов Active Directory® обеспечивает централизованное управление конфигурацией безопасности рабочих станций и серверов на малом предприятии. Служба обеспечивает более безопасную и простую в управлении среду для рабочих станций.

Эта статья описывает централизованное управление рабочими станциями Microsoft® Windows® XP с пакетом обновления 2 (SP2). Применение объектов групповой политики (GPO) для управления настройками безопасности рабочих станций обеспечивается исключительно службой каталогов Active Directory.

#### Назначение данного документа

Различные организации предъявляют различные требования к безопасности. Независимо от жесткости требований к безопасности каждого потребителя, концепции, изложенные в данной статье, могут быть полезны всем потребителям при решении задач управления безопасностью рабочих станций.

[](#mainsection)[К началу страницы](#mainsection)

### Прежде чем приступить к работе

Необходимо войти в систему с помощью учетной записи члена группы администраторов домена, чтобы завершить следующие действия.

**Примечание.**   Если не удается внести изменения в рабочую станцию или сервер, то причиной может быть групповая политика. В таких случаях необходимо внести изменения на уровне групповой политики.

Выполните задания в этом документе, чтобы настроить технологии сетевой защиты Windows XP SP2 с помощью групповой политики:

-   Применение обновлений для системы безопасности

-   Обновление существующих объектов групповой политики (GPO)

-   Настройка параметров Центра обеспечения безопасности

-   Настройка параметров брандмауэра Windows

-   Настройка параметров обозревателя Internet Explorer

-   Настройка параметров управления связью через Интернет

-   Применение параметров с использованием утилиты GPUpdate

[](#mainsection)[К началу страницы](#mainsection)

### Применение обновлений для системы безопасности

Корпорация Майкрософт рекомендует применять самые свежие обновления для системы безопасности на всех рабочих станциях и серверах Windows. Всегда полезно создать резервную копию компьютера или важных файлов перед применением обновлений для системы безопасности.

**Примечание.**   Некоторые функции в этой статье и некоторые критические компоненты безопасности связаны с новейшими обновлениями и исправлениями. Если контроллеры домена не были своевременно обновлены, то в них могут отсутствовать административные шаблоны, необходимые для рабочей станции Windows XP SP2 внутри GPO. Без административных шаблонов новые средства безопасности SP2 будут недоступны.

[](#mainsection)[К началу страницы](#mainsection)

### Обновление существующих объектов групповой политики

Лучший способ управлять объектами GPO в Active Directory — использование [консоли управления группами Microsoft (MMC)](http://www.microsoft.com/windowsserver2003/gpmc/gpmcintro.mspx), которую можно загрузить с веб-узла Майкрософт по адресу www.microsoft.com/windowsserver2003/gpmc/gpmcintro.mspx. Это альтернатива применению консоли Microsoft MMC с оснасткой «Редактор объекта групповой политики» (GPOE).

Консоль GPMC также использует редактор объекта групповой политики, чтобы изменять объекты GPO.

1.  В консоли GPMC дважды щелкните объект GPO, который нужно обновить с использованием нового административного шаблона. Объект GPO будет открыт в редакторе GPOE.

2.  Нажмите кнопку **OK**, а затем нажмите кнопку **Готово**. Данное действие применяет новый шаблон.

3.  Повторите для каждого объекта GPO.

[](#mainsection)[К началу страницы](#mainsection)

### Настройка объектов групповой политики

Выполните следующие процедуры, чтобы настроить объекты GPO в своей среде.

#### Настройка параметров Центра обеспечения безопасности

Можно активизировать Центр обеспечения безопасности на каждой рабочей станции, управляемой групповой политикой. Если Центр обеспечения безопасности установлен, то он может сообщить каждому пользователю рабочей станции о состоянии брандмауэра Windows, антивирусной программы и настройках автоматических обновлений. По умолчанию групповая политика не включает эту функцию.

1.  Откройте консоль GPMC и сделайте двойной щелчок на объекте GPO, который нужно использовать, чтобы задействовать Центр обеспечения безопасности на каждой рабочей станции.

2.  В выбранном объекте GPO откройте **Конфигурация компьютера**, **Административные шаблоны**, **Компоненты Windows**, а затем **Центр обеспечения безопасности**.

3.  Сделайте двойной щелчок на **Включить Центр обеспечения безопасности (только для компьютеров в домене)**.

4.  Включите этот параметр.

5.  Нажмите кнопку **ОК**.

#### Настройка параметров брандмауэра Windows

В этом разделе описаны настройки брандмауэра Windows в объекте GPO и рекомендованные настройки для среды малого предприятия.

1.  В выбранном объекте GPO, откройте **Конфигурация компьютера**, **Административные шаблоны**, **Сеть**, **Сетевые подключения**, **Брандмауэр Windows**, а затем **Профиль домена**.

2.  Сделайте двойной щелчок на каждом параметре и настройте в соответствии со сведениями в следующей таблице.

    **Примечание**   После того как установлен режим **Задать исключения для программ** в профиле домена, необходимо ввести все программы, которым будет разрешено подключаться к компьютеру, прежде чем нажать кнопку **ОК**.

**Таблица 1. Рекомендуемые настройки брандмауэра Windows для малых предприятий**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Параметр</th>
<th style="border:1px solid black;" >Описание</th>
<th style="border:1px solid black;" >Профиль домена</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Защитить все сетевые подключения</td>
<td style="border:1px solid black;">Указывает, что брандмауэр Windows включен для всех сетевых подключений.</td>
<td style="border:1px solid black;">Включен.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Не разрешать исключения</td>
<td style="border:1px solid black;">Указывает, что весь незапрошенный трафик отбрасывается, в том числе трафик, относящийся к исключениям.</td>
<td style="border:1px solid black;">Не определено.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Определить программные исключения</td>
<td style="border:1px solid black;">Определяет исключенный трафик по именам файлов программ.</td>
<td style="border:1px solid black;">Включен и настроен для программ (приложений и служб), используемых компьютерами Windows XP SP2 в сети.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Разрешить исключения для локальных программ</td>
<td style="border:1px solid black;">Разрешает локальную настройку исключений для программ.</td>
<td style="border:1px solid black;">Отключен.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Разрешить исключения для удаленного администрирования</td>
<td style="border:1px solid black;">Включить удаленное управление при помощи инструментов удаленного управления.</td>
<td style="border:1px solid black;">Отключен, если не требуется удаленно управлять компьютерами с использованием оснасток консоли MMC.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Разрешить исключение для совместного использования файлов и принтеров</td>
<td style="border:1px solid black;">Указывает, разрешен ли общий трафик файлов и принтеров.</td>
<td style="border:1px solid black;">Отключен.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Разрешить исключения ICMP</td>
<td style="border:1px solid black;">Указывает разрешенные типы ICMP-сообщений.</td>
<td style="border:1px solid black;">Отключен.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Разрешить исключение для удаленного рабочего стола</td>
<td style="border:1px solid black;">Указывает, может ли компьютер принимать запросы на соединение для удаленного рабочего стола.</td>
<td style="border:1px solid black;">Включен.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Разрешить исключение для среды UPnP</td>
<td style="border:1px solid black;">Указывает, может ли компьютер получать незапрошенные UPnP-сообщения.</td>
<td style="border:1px solid black;">Отключен.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Запретить уведомления</td>
<td style="border:1px solid black;">Отключает уведомления.</td>
<td style="border:1px solid black;">Отключен.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Разрешить ведение журнала</td>
<td style="border:1px solid black;">Разрешает протоколирование трафика и настройку параметров файла журнала.</td>
<td style="border:1px solid black;">Не определено.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Запретить одноадресные ответы на многоадресные или широковещательные запросы</td>
<td style="border:1px solid black;">Отклоняет одноадресные пакеты, полученные в ответ на многоадресные или широковещательные запросы.</td>
<td style="border:1px solid black;">Включен.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Задать исключения портов</td>
<td style="border:1px solid black;">Указывает исключенный трафик для протоколов TCP и UDP.</td>
<td style="border:1px solid black;">Отключен.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Разрешить локальные исключения для портов</td>
<td style="border:1px solid black;">Разрешает локальную настройку исключений для портов.</td>
<td style="border:1px solid black;">Отключен.</td>
</tr>
</tbody>
</table>
  
Дополнительные сведения см. в статье, [посвященной настройке брандмауэра Windows на малом предприятии с помощью групповой политики,](http://www.microsoft.com/technet/security/smallbusiness/prodtech/windowsxp/fwgrppol.mspx) по адресу www.microsoft.com/technet/security/smallbusiness/prodtech/windowsxp/fwgrppol.mspx.
  
[](#mainsection)[К началу страницы](#mainsection)
  
### О параметрах безопасности обозревателя Internet Explorer
  
Параметры политики безопасности позволяют управлять конкретными сценариями, которые могут повлиять на безопасность обозревателя Internet Explorer. В большинстве случаев требуется запретить определенное поведение и поэтому необходимо гарантировать, что функции безопасности включены. Корпорация Майкрософт рекомендует Internet Explorer 6, так как его новые функции повышают безопасность обозревателя.
  
#### Зоны безопасности
  
Обозреватель Internet Explorer разделяет веб-узлы на четыре зоны безопасности, каждая из которых обеспечивает различный уровень защиты. Зоны безопасности «Интернет», «Местная интрасеть», «Надежные узлы» и «Ограниченные узлы». Каждую зону можно независимо настроить с использованием заранее определенных уровней безопасности — от низкого до высокого. Обозреватель Internet Explorer также обеспечивает возможность задать специальный набор параметров защиты для каждой зоны безопасности. Корпорация Майкрософт определила параметры безопасности по умолчанию для каждой зоны. В следующей таблице приведено описание каждой зоны безопасности и назначенные корпорацией Майкрософт параметры по умолчанию для каждой зоны.
  
**Таблица 2. Описания зон безопасности и настройки безопасности по умолчанию**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Зона безопасности</th>
<th style="border:1px solid black;" >Уровень безопасности по умолчанию</th>
<th style="border:1px solid black;" >Описание</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Зона Интернета</td>
<td style="border:1px solid black;">Средний</td>
<td style="border:1px solid black;">Зона Интернета состоит из всех веб-узлов, которые не включены в другие зоны.<br />
<br />
<strong>Примечание.</strong>   Угроза, исходящая из Интернета, очень реальна. Корпорация Майкрософт настолько серьезно относится к защите пользователей от угроз из Интернета, что пользователь не может назначить низкий уровень защиты даже нажатием кнопки <strong>Другой</strong>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Зона «Местная интрасеть»</td>
<td style="border:1px solid black;">Ниже среднего</td>
<td style="border:1px solid black;">Все веб-узлы этой зоны должны находиться внутри брандмауэра.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Зона «Надежные веб-узлы»</td>
<td style="border:1px solid black;">Низкий</td>
<td style="border:1px solid black;">Узлам в зоне «Надежные веб-узлы» разрешено выполнять более широкий набор операций и реже просить пользователей принимать решения о безопасности. В эту зону следует вводить только веб-узлы, относительно всего содержимого которых есть уверенность, что в компьютере никогда не будут выполнены никакие вредные операции.<br />
Для зоны «Надежные веб-узлы» корпорация Майкрософт настоятельно рекомендует использовать протокол HTTPS или иным способом гарантировать полную безопасность подключений с веб-узлом.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Зона «Ограниченные веб-узлы»</td>
<td style="border:1px solid black;">Высокий</td>
<td style="border:1px solid black;">Эта зона предназначена для ввода веб-узлов, которым нельзя доверять. Она контролирует и ограничивает веб-функциональность, но не блокирует доступ к узлу. Веб-узлы могут быть добавлены пользователем или назначены групповой политикой. Чтобы блокировать доступ к веб-узлам, необходимо использовать прокси-сервер, который поддерживает эту функцию.</td>
</tr>
</tbody>
</table>
  
#### Повышение безопасности
  
Каждая зона безопасности содержит более 30 параметров, которые можно изменить по отдельности, чтобы усилить определенные области функциональности. Существует возможность включить или отключить большинство параметров, а также предложить выбор пользователю. Корпорация Майкрософт рекомендует потребителям ограничить число параметров, запрашиваемых у пользователя, во всех зонах безопасности. Строгие политики информационной безопасности ограничивают пользовательские разрешения и предотвращают действия пользователей, которые могут привести к недостаткам обеспечения безопасности. Параметры зоны безопасности должны быть определены и установлены отдельно для каждой зоны — никогда не рекомендуется использовать единый набор определений для всех зон. В следующей таблице приведен выборочный набор параметров по умолчанию для разных зон безопасности. Эти и другие параметры могут быть изменены в соответствии с потребностями организации.
  
**Таблица 3. Параметры политики зоны безопасности**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Зона безопасности</th>
<th style="border:1px solid black;" >Параметры политики</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Зона Интернета</td>
<td style="border:1px solid black;">Блокировать всплывающие окна = Разрешить<br />
Автоматические запросы элементов управления ActiveX = Отключить<br />
Загрузка подписанных элементов ActiveX = Предлагать<br />
Загрузка файла = Разрешить</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Зона «Местная интрасеть»</td>
<td style="border:1px solid black;">Блокировать всплывающие окна = Отключить<br />
Автоматические запросы элементов управления ActiveX = Разрешить<br />
Загрузка подписанных элементов ActiveX = Предлагать<br />
Загрузка файла = Разрешить</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Зона «Надежные узлы»</td>
<td style="border:1px solid black;">Блокировать всплывающие окна = Отключить<br />
Автоматические запросы элементов управления ActiveX = Разрешить<br />
Загрузка подписанных элементов ActiveX = Разрешить<br />
Загрузка файла = Разрешить</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Зона «Ограниченные узлы»</td>
<td style="border:1px solid black;">Блокировать всплывающие окна = Разрешить<br />
Автоматические запросы элементов управления ActiveX = Отключить<br />
Загрузка подписанных элементов ActiveX = Отключить<br />
Загрузка файла = Отключить</td>
</tr>
</tbody>
</table>
 

ActiveX® — мощная платформа расширения для веб-разработки, которая обеспечивает пользователям дополнительные возможности в сети. Многие сотрудники предприятий используют элементы управления ActiveX для внутренних бизнес-приложений, и поэтому элементы управления ActiveX должны быть включены в обозревателе Internet Explorer. В соответствии с действующими на предприятии стандартами безопасности и политиками допустимого использования иногда требуется отключить элементы управления ActiveX для зоны Интернета. Отключение элементов управления ActiveX с использованием групповой политики или установки высокого режима безопасности зоны может привести к некорректному функционированию веб-узлов. Корпорация Майкрософт рекомендует организациям определить политики для решения этой проблемы и подготовить стратегию, чтобы разрешить доступ на основе производственных задач предприятия.

Элементы управления ActiveX представляют опасность из-за их способности запускать команды в консоли обозревателя. Рекомендуется разрешать запуск элементов управления ActiveX только из доверенных веб-узлов.

Более подробное объяснение зон безопасности и параметров конфигурации можно найти в статье, [посвященной настройке зон безопасности,](http://www.microsoft.com/windows/ie/using/howto/security/setup.mspx) по адресу www.microsoft.com/windows/ie/using/howto/security/setup.mspx.

#### Конфиденциальность и «cookie»

С целью обеспечить более эффективное настраиваемое использование возможностей сети некоторые веб-узлы сохраняют данные в маленьких текстовых файлах на компьютере пользователя. Эти файлы называются «cookie». В обозревателе Internet Explorer 6 есть несколько механизмов для управления использованием файлов «cookie».

Различные типы «cookie». Основные файлы «cookie» не могут быть прочитаны веб-узлами, кроме узла, создавшего эти файлы. Другой тип «cookie» называется сторонними «cookie» и используются веб-узлами для записи данных о посетителях. Сторонние «cookie» используются многими веб-узлами. Они могут содержать различные данные от идентификаторов пользователей до почтовых индексов.

-   **Основные «cookie»**. Могут быть прочитаны только узлом, который создал файл.

-   **Сторонние «cookie»**. Могут быть прочитаны и записаны многими веб-узлами.

Пользователи могут не знать о возможности управлять данными, хранимыми в файлах «cookie». Просто установив флажок, чтобы запомнить адрес выставления счета, можно оставить нежелательные данные в основном или стороннем файле «cookie».

Каждая организация должна определить собственную политику в отношении файлов «cookie». Корпорация Майкрософт рекомендует установить по крайней мере режим **Средний**. В этом режиме блокируются сторонние файлы «cookie», для которых отсутствует компактная политика конфиденциальности, блокируются сторонние файлы «cookie», в которых используются персонально идентифицируемые сведения без подразумеваемого согласия, и ограничены основные файлы «cookie», в которых используются персонально идентифицируемые сведения без подразумеваемого согласия. Режим **Высокий** ограничивает «cookie», а в других режимах они разрешены в определенных условиях. В режиме **Низкий** безусловно разрешены все файлы «cookie».

Можно добавить веб-узлы, чтобы обойти общий режим. Варианты для добавления веб-узла — **Всегда запрещать** и **Всегда разрешать**. Независимо от выбранного более жесткого или менее жесткого режима, пользователь может добавлять веб-узлы. Групповая политика может обеспечивать применение как параметров «cookie», так и веб-узлов.

**Примечание.**   Файлами «cookie» нельзя управлять внутри каждой зоны. Режим применяется ко всем четырем зонам безопасности.

#### Блокировщик всплывающих окон

Блокировщик всплывающих окон блокирует большинство нежелательных всплывающих окон. Всплывающие окна, которые открываются, когда пользователь щелкает ссылку, не блокируются. Блокировщик всплывающих окон может быть настроен для каждой зоны, что позволяет блокировать узлы в одной зоне, но не в других. С помощью групповой политики можно обеспечить применение блокировщика всплывающих окон в каждой зоне и добавить список разрешенных веб-узлов.

Всплывающие окна могут вызывать неудобства и быть столь многочисленными и назойливыми, что обозреватель становится практически непригодным для использования. Каждый раз, когда блокируется всплывающее окно, на панели инструментов Internet Explorer появляется соответствующая отметка.

**Примечание.**   Блокировщиком всплывающих окон можно управлять внутри каждой зоны, но разрешенные веб-узлы добавляются во все четыре зоны.

#### Программы Интернета

Обозреватель Internet Explorer может быть настроен на запуск других программ для отправки сообщений электронной почты, управления контактами или просмотра исходного текста страницы. Например, если пользователь щелкает адрес электронной почты на веб-странице, то обозреватель Internet Explorer открывает определенную программу электронной почты с новым адресованным исходящим сообщением. Эта функциональность обеспечивает эффективный способ отправки сообщений электронной почты без необходимости открывать другую программу и вручную вводить адрес электронной почты. Однако эти дополнительные функции связаны с определенным потенциальным риском. Пользователи могут столкнуться с неожиданным поведением или функциональностью, если одна из связанных программ отличается от стандартных приложений организации. С помощью групповой политики можно принудительно применить параметры к этому списку программ и получить определенную уверенность, что не будет запущена нежелательная программа.

#### Надстройки

Надстройки — малые программы, предназначенные для выполнения определенных функций, которые могут быть загружены веб-страницей по требованию. Панели инструментов и объекты поддержки модуля обозревателя (BHO) — программы других типов, которые устанавливают дополнительные кнопки и компоненты, чтобы расширить функциональность изнутри обозревателя. Корпорация Майкрософт рекомендует организациям определить список допустимых панелей инструментов и объектов BHO, а также использовать групповую политику для применения этих параметров.

Многие разработчики используют платформу ActiveX, чтобы построить инструменты для увеличения производительности или расширения функциональности. Корпорация Майкрософт поощряет сообщество разработчиков продолжать выпуск надстроек, но признает необходимость развертывать надстройки из доверенных источников. Internet Explorer 6 использует Authenticode для проверки подлинности надстройки с помощью цифровых подписей. Корпорация Майкрософт рекомендует организациям разрешать только подписанные надстройки в зоне Интернет. Веб-узлам в зоне «Местная интрасеть» может не потребоваться подпись Authenticode, так как эти надстройки, вероятно, были разработаны доверенными внутренними программистами.

#### Настройка групповой политики для Internet Explorer 6

Все функции безопасности Internet Explorer 6 могут быть настроены и защищены с помощью групповой политики. Существует большое число параметров безопасности на базе объектов GPO для управления различными компонентами обозревателя IE, поэтому главное внимание обращено на четыре основные ветви (a, b, c и d в следующей процедуре). Редактор объекта групповой политики обеспечивает подробности о последствиях всех параметров в четырех ветвях. Внимательно прочитайте каждое описание и протестируйте эффективность нужного параметра перед его применением.

1.  Откройте консоль управления групповой политики.

2.  Создайте новый объект групповой политики (GPO), например Internet Explorer 6.

3.  Политики Internet Explorer содержатся в следующих четырех ветвях дерева политики в редакторе объекта групповой политики. Настройте каждый объект политики во всех четырех ветвях в соответствии с потребностями организации.

    1.  **Конфигурация компьютера**, **Административные шаблоны**, **Компоненты Windows**, **Internet Explorer**

        В этой ветви находятся дополнительные политики безопасности для более глубокого блокирования параметров безопасности, нежели в самом обозревателе. Одна из наиболее полезных политик — **Зоны безопасности: не разрешать пользователям изменение политики**. По умолчанию эта политика отключена в объекте GPO. Если включить политику, то она запрещает пользователю изменять любые настройки безопасности в параметрах обозревателя. Корпорация Майкрософт рекомендует установить этот параметр в значение **Включено**. Даже локальные администраторы не могут изменять эти параметры после того, как они заданы групповой политикой. Существует несколько других политик, которые можно включить, некоторые из них предназначены для безопасности, другие нет. Внимательно прочитайте описания перед включением.

    2.  **Конфигурация компьютера**, **Административные шаблоны**, **Система**, **Параметры связи через Интернет**

        Эта ветвь предназначена специально для Window XP SP2. Она содержит 20 новых политик, начиная с предназначенных для функций публикации в веб до поддержки мультимедиа. Одна политика, **Отключить службу сопоставления файлов Интернета**, запрещает обозревателю открывать приложения, связанные с расширениями файлов для содержимого, загружаемого из веб-узла. Эта функция похожа на автоматическое открытие операционной системой программы «Блокнот» для файлов с расширением TXT. Другая политика, **Отключить выполнение печати через HTTP-протокол**, предназначена для того, чтобы запретить пользователю печатать через Интернет или интрасеть с использованием протокола HTTP. Эта политика не влияет на возможность пользователей иметь собственный HTTP-принтер. Внимательно прочитайте описания перед включением.

    3.  **Конфигурация пользователя**, **Конфигурация Windows**, **Настройка Internet Explorer**, **Безопасность**, **Программы**

        Эти два раздела содержат параметры и политики, которые влияют на безопасность обозревателя. Оба раздела содержат параметры пользовательского уровня, которые находятся в отдельных параметрах безопасности/конфиденциальности обозревателя. Рекомендуется использовать минимальные установки Майкрософт, но конфигурации должны соответствовать требованиям организации.

        **Примечание**   Веб-узлы можно добавлять ко всем зонам, кроме Интернет. Тщательно выбирайте веб-узлы, добавляемые в зоны «Местная интрасеть», «Надежные узлы» и «Ограниченные узлы», так как они применяются ко всем рабочим станциям и серверам, связанным с объектом GPO.

    4.  **Конфигурация пользователя**, **Административные шаблоны**, **Компоненты Windows**, **Internet Explorer**

        Эта ветвь содержит детальные настройки для ограничения изменений параметров веб-обозревателя, вместо того чтобы полностью запретить пользователям вносить изменения. Эти параметры применяются к изменениям таких элементов, как элементы управления временными файлами Интернета и домашняя страница. Эта ветвь содержит много параметров, и корпорация Майкрософт рекомендует администраторам читать описание и тестировать параметры перед их использованием в рабочей среде.

4.  Завершив работу с редактором политики, свяжите новый объект GPO со всеми доменами, содержащими рабочие станции и серверы Windows.

5.  Настройте **Фильтры безопасности** для объекта GPO по группам, пользователям и компьютерам, на которые должен воздействовать этот объект GPO. Некоторые политики предназначены для компьютеров, в другие применяются только для пользователей.

[](#mainsection)[К началу страницы](#mainsection)

### Применение новых конфигураций с использованием утилиты GPUpdate

Утилита GPUpdate обновляет настройки групповой политики на базе Active Directory. После настройки групповой политики можно подождать, пока параметры будут применены к клиентским компьютерам в стандартных циклах обновления. По умолчанию обновление повторяется каждые 90 минут, с произвольным отклонением плюс или минус 30 минут. С помощью этой процедуры можно ускорить тестирование применения политики на рабочих станциях.

Чтобы обновить групповую политику между стандартными циклами, используйте утилиту GPUpdate следующим образом:

1.  На рабочем столе Windows XP SP2 нажмите кнопку **Пуск**, а затем выберите пункт **Выполнить**.

2.  В поле **Открыть**, введите **cmd**, а затем нажмите кнопку **ОК**. На экране появится окно командной строки.

3.  В командной строке введите **GPUpdate**, а затем нажмите кнопку **ОК**. Должно появиться сообщение, показанное на следующем снимке экрана:

    [![](images/Cc875819.XPNPT01(ru-ru,TechNet.10).gif)](https://technet.microsoft.com/ru-ru/cc875819.xpnpt01_big(ru-ru,technet.10).gif)

    Чтобы закрыть командную строку, введите **exit**, а затем нажмите ВВОД.

[](#mainsection)[К началу страницы](#mainsection)

### Дополнительные сведения

Определения терминов безопасности см. в

-   [глоссарии терминов, связанных с безопасностью](http://www.microsoft.com/security/glossary.mspx) на веб-узле Майкрософт по адресу http://go.microsoft.com/fwlink/?linkid=35468.

Дополнительные сведения о сетевой защите Windows XP SP2 см. в следующих статьях:

-   [Статья, посвященная функциональным изменениям в Microsoft Windows XP с пакетом обновления 2 (SP2), часть 2: технологии сетевой защиты,](http://www.microsoft.com/technet/prodtechnol/winxppro/maintain/sp2netwk.mspx) на веб-узле Microsoft TechNet по адресу http://go.microsoft.com/fwlink/?linkid=35486.

-   [Статья, посвященная использованию Windows XP Professional с пакетом обновления 2 (SP2) в управляемой среде: контроль коммуникации с помощью Интернета,](http://go.microsoft.com/fwlink/?linkid=35489) на веб-узле Microsoft TechNet по адресу http://go.microsoft.com/fwlink/?linkid=35489.

-   [Статья, посвященная развертыванию настроек брандмауэра Windows для Microsoft Windows XP с пакетом обновления 2 (SP2),](http://go.microsoft.com/fwlink/?linkid=35303) на веб-узле центра загрузки Microsoft по адресу http://go.microsoft.com/fwlink/?linkid=35303.

Дополнительные сведения о безопасности Windows XP SP2 см. в следующих статьях:

-   The [*руководство по обеспечению безопасности в Windows XP*](http://go.microsoft.com/fwlink/?linkid=35309) на веб-узле центра загрузки Майкрософт по адресу http://go.microsoft.com/fwlink/?linkid=35309.

-   [*руководство по обеспечению безопасности Windows XP, Приложение A: ключевые настройки*](http://go.microsoft.com/fwlink/?linkid=35465) на веб-узле Microsoft TechNet по адресу http://go.microsoft.com/fwlink/?linkid=35465.

Дополнительные сведения о групповой политике см. в следующих статьях:

-   [Статья, посвященная групповой политике для решения проблем в Microsoft Windows Server,](http://go.microsoft.com/fwlink/?linkid=35481) на веб-узле центра загрузки Microsoft по адресу http://go.microsoft.com/fwlink/?linkid=35481.

-   [Статья, посвященная управлению предприятием с помощью консоли управления группами,](http://go.microsoft.com/fwlink/?linkid=35479) на веб-узле Microsoft Windows Server System по адресу http://go.microsoft.com/fwlink/?linkID=35479.

**Загрузить**

[Получить статью о том, как настроить технологии сетевой защиты Windows XP SP2 на малом предприятии](http://go.microsoft.com/fwlink/?linkid=70393)

[](#mainsection)[К началу страницы](#mainsection)