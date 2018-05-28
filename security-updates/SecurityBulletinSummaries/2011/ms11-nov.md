---
TOCTitle: 'MS11-NOV'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за ноябрь 2011 г.'
ms:assetid: 'ms11-nov'
ms:contentKeyID: 61236152
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms11-nov(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за ноябрь 2011 г.
===============================================================

Дата публикации: 8 ноября 2011 г.

**Версия:** 1.0

В этот обзор включены бюллетени по безопасности, выпущенные в ноябре 2011 г.

После выпуска бюллетеней по безопасности за ноябрь 2011 г. данный обзор заменит предварительное уведомление, выпущенное 3 ноября 2011 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

9 ноября 2011 г. в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проводит веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в ноябрьской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032487958). После наступления этой даты данная веб-трансляция будет доступна по запросу. Дополнительные сведения см. на веб-сайте [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://go.microsoft.com/fwlink/?linkid=217214).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел **Прочие сведения**.

### Сведения о бюллетене

Аннотации
---------

<span></span>
В приведенной ниже таблице описаны бюллетени по безопасности за этот месяц в порядке, соответствующем уровню опасности.

Сведения об уязвимом программном обеспечении см. в следующем разделе **Продукты, подверженные уязвимости, и соответствующие обновления**.

 
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Идентификатор бюллетеня</th>
<th style="border:1px solid black;" >Название бюллетеня и аннотация</th>
<th style="border:1px solid black;" >Максимальный уровень серьезности и воздействие уязвимости</th>
<th style="border:1px solid black;" >Необходимость перезагрузки</th>
<th style="border:1px solid black;" >Подвержены уязвимости</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=229071">MS11-083</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в TCP/IP делает возможным удаленное выполнение кода (2588516)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость делает возможным удаленное выполнение кода, если злоумышленник отправляет непрерывный поток специально созданных UDP-пакетов на закрытый порт целевой системы.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=229638">MS11-085</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в программах &quot;Почта Windows&quot; и &quot;Конференц-зал Windows&quot; делает возможным удаленное выполнение кода (2620704)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным удаленное выполнение кода, если пользователь открывает подлинный файл (например, файл .eml или .wcinv), расположенный в той же сетевом каталоге, что и специально созданный DLL-файл. Затем при открытии подлинного файла программы &quot;Почта Windows&quot; или &quot;Конференц-зал Windows&quot; могут попытаться загрузить данный DLL-файл и выполнить заключенный в нем код. Чтобы атака была успешной, пользователь должен посетить недоверенную папку в удаленной файловой системе или общий ресурс WebDAV и открыть находящийся там подлинный файл (например, файл .eml или .wcinv), который затем загружается уязвимым приложением.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=229253">MS11-086</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Active Directory делает возможным несанкционированное получение прав (2630837)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Active Directory, службе ADAM и службе Active Directory облегченного доступа к каталогам (AD LDS). Эта уязвимость делает возможным несанкционированное получение прав, если служба Active Directory настроена на использование LDAP через SSL (LDAPS), злоумышленник получает отозванный сертификат, связанный с действительной учетной записью домена, а затем используется его для прохождения проверки подлинности в домене Active Directory. По умолчанию служба Active Directory не настроена на использование LDAP через SSL.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=229245">MS11-084</a></td>
<td style="border:1px solid black;"><strong>Уязвимость драйверов режима ядра Windows делают возможной атаку типа &quot;отказ в обслуживании&quot; (2617657)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным отказ в обслуживании, если пользователь открывает специально созданный файл шрифта TrueType как вложение электронной почты или переходит в сетевую папку или каталог WebDAV со специально созданным файлом шрифта TrueType. Чтобы атака была успешной, пользователь должен посетить ненадежную папку в удаленной файловой системе или общий ресурс WebDAV со специально созданным файлом шрифта TrueType или открыть такой файл как вложение электронной почты. Однако в любом случае злоумышленник не может заставить пользователей выполнить данные действия. Вместо этого злоумышленнику требуется убедить пользователей сделать это, обычно предлагая перейти по ссылке в сообщении электронной почты или в сообщении, отправленном через программу обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Средний</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Индекс использования уязвимостей  
--------------------------------
  
<span></span>
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости сгруппированы по идентификаторам бюллетеней и затем по кодам CVE. Включены только уязвимости, которым в бюллетенях присвоен уровень серьезности "критический" или "существенный".
  
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать о вероятности появления эксплойтов для выполнения произвольного кода и DoS-атаки в течение 30 дней после выпуска бюллетеня по каждому из обновлений безопасности, которые необходимо установить. Чтобы назначить приоритеты развертывания, ознакомьтесь с приведенными ниже оценками в соответствии с вашей конфигурацией. Дополнительные сведения об уровнях опасности и способах их определения см. в [индексе использования уязвимостей](http://technet.microsoft.com/security/cc998259.aspx).
  
В приведенной ниже таблице "последний выпуск программного обеспечения" обозначает соответствующее программное обеспечение, а термином "старые выпуски программного обеспечения" обозначены все прежние поддерживаемые выпуски программного обеспечения, указанные в таблице "Подвержены уязвимости" или "Не подвержены уязвимости" в этом бюллетене.
  
| Идентификатор бюллетеня                                   | Название уязвимости                                                                 | Код CVE                                                                          | Оценка использования уязвимостей при выполнении кода для последнего выпуска программного обеспечения                 | Оценка использования уязвимостей при выполнении кода для старых выпусков программного обеспечения                    | Оценка использования уязвимости типа "отказ в обслуживании" | Краткие примечания |  
|-----------------------------------------------------------|-------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|--------------------|  
| [MS11-083](http://go.microsoft.com/fwlink/?linkid=229071) | Уязвимость, связанная с переполнением счетчика ссылок                               | [CVE-2011-2013](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2013) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) — Возможно существование нестабильного кода эксплойта | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) — Возможно существование нестабильного кода эксплойта | Перманентное                                                | (Нет)              |  
| [MS11-085](http://go.microsoft.com/fwlink/?linkid=229638) | Уязвимость, связанная с небезопасной загрузкой библиотек программой "Почта Windows" | [CVE-2011-2016](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2016) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование стабильного кода эксплойта   | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование стабильного кода эксплойта   | Не применимо                                                | (Нет)              |  
| [MS11-086](http://go.microsoft.com/fwlink/?linkid=229253) | Уязвимость, связанная с обходом проверки подлинности LDAPS                          | [CVE-2011-2014](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2014) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование стабильного кода эксплойта   | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование стабильного кода эксплойта   | Не применимо                                                | (Нет)              |
  
Продукты, подверженные уязвимости, и соответствующие обновления  
---------------------------------------------------------------
  
<span></span>
В приведенных ниже таблицах перечислены бюллетени в порядке важности категорий программного обеспечения и уровней опасности.
  
**Как пользоваться этими таблицами?**
  
Обращайтесь к этим таблицам, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и узнайте, имеются ли для них обновления для системы безопасности. Для программ или компонентов, указанных в списке, приведены ссылки на доступные обновления с указанием уровня опасности уязвимостей, которые они устраняют.
  
**Примечание.** Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификатора бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.
  
#### Компоненты операционных систем Windows

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="7">
ОС Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-083**](http://go.microsoft.com/fwlink/?linkid=229071)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://go.microsoft.com/fwlink/?linkid=229638)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-086**](http://go.microsoft.com/fwlink/?linkid=229253)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-084**](http://go.microsoft.com/fwlink/?linkid=229245)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Совокупный уровень серьезности**
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;" colspan="2">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
Нет
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=8c7c21c5-677d-4a5d-8f2b-8ca7691b6b00)  
(KB2616310)  
(существенный)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=989cca2d-cce1-4f52-b50e-43152693f240)  
(KB2616310)  
(существенный)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-083**](http://go.microsoft.com/fwlink/?linkid=229071)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://go.microsoft.com/fwlink/?linkid=229638)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-086**](http://go.microsoft.com/fwlink/?linkid=229253)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-084**](http://go.microsoft.com/fwlink/?linkid=229245)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Совокупный уровень серьезности**
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;" colspan="2">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
Нет
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=08b27ce7-c32e-41e4-ad04-481c5eab17a7)  
(KB2601626)  
(существенный)  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=f116824e-ea48-422d-b284-c9ffa7604bf5)  
(KB2616310)  
(существенный)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=de5a74f2-2cc8-4677-b495-3a40fe3d6b9e)  
(KB2601626)  
(существенный)  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=1af1b734-62c7-4e08-91c8-90b6d026da84)  
(KB2616310)  
(существенный)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=6168bc67-3d59-450f-bd8a-02d61dabe16b)  
(KB2601626)  
(существенный)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista;
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-083**](http://go.microsoft.com/fwlink/?linkid=229071)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://go.microsoft.com/fwlink/?linkid=229638)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-086**](http://go.microsoft.com/fwlink/?linkid=229253)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-084**](http://go.microsoft.com/fwlink/?linkid=229245)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Совокупный уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
Нет
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=fc3fe87c-2493-431d-a904-dec9310f6042)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e08266d8-fffa-40bf-b8f6-10a65ee27524)  
(существенный)
</td>
<td style="border:1px solid black;" colspan="2">
[Службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=2bd602cf-ae0d-4790-a5d0-6133fd7d01a0)  
(KB2601626)  
(существенный)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=042c1a8f-834d-4eed-8a59-9e030ccc6d39)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4f2365ed-d50e-44d9-b859-1ec54d3b4d38)  
(существенный)
</td>
<td style="border:1px solid black;" colspan="2">
[Службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=783521ad-5c50-4194-a582-4e5a1c9999e7)  
(KB2601626)  
(существенный)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-083**](http://go.microsoft.com/fwlink/?linkid=229071)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://go.microsoft.com/fwlink/?linkid=229638)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-086**](http://go.microsoft.com/fwlink/?linkid=229253)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-084**](http://go.microsoft.com/fwlink/?linkid=229245)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Совокупный уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
Нет
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=79382bf2-d2cb-42ea-92dc-64f949353521)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=f82dc413-668c-4ca8-a8c8-db74f05346bc)\*\*  
(средний)
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory и службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=b5688923-3914-4f6c-8bc9-036fb4870cc6)\*  
(KB2601626)  
(существенный)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=71ff3a89-d7ad-4dda-9e59-fab54b21bd5d)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для компьютеров на базе x64-процессоров с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=06ad5637-56a1-4478-aaa0-063e877503c9)\*\*  
(средний)
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory и службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=51f47181-08f6-4de1-80e5-253355675965)\*  
(KB2601626)  
(существенный)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=b1c0cb05-c284-49b1-ae4f-92813fdf520f)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=2de5de74-e643-4045-9c22-ff95b0dbcafc)  
(средний)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<th colspan="7">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-083**](http://go.microsoft.com/fwlink/?linkid=229071)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://go.microsoft.com/fwlink/?linkid=229638)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-086**](http://go.microsoft.com/fwlink/?linkid=229253)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-084**](http://go.microsoft.com/fwlink/?linkid=229245)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Совокупный уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Низкий**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=4ddb4c2a-bada-49b0-ad78-e07e7e11ced7)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=2307fa93-8e45-4841-a5a9-7e89960712f9)  
(низкий)
</td>
<td style="border:1px solid black;" colspan="2">
[Службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=b06f9f55-e3b2-4705-83d0-1b9f5de9d378)  
(KB2601626)  
(существенный)
</td>
<td style="border:1px solid black;" colspan="2">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=156c1bd9-55bc-482c-874b-61998d1ef153)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=05eef5d7-acf6-46e4-abfc-dc83f0a7cae5)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=62603d18-1b21-400c-8eba-202193182960)  
(низкий)
</td>
<td style="border:1px solid black;" colspan="2">
[Службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=790f1d99-96a5-438d-b433-895b692912ce)  
(KB2601626)  
(существенный)
</td>
<td style="border:1px solid black;" colspan="2">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5c7db930-5495-43f0-928c-d586ac9e80d0)  
(средний)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-083**](http://go.microsoft.com/fwlink/?linkid=229071)
</td>
<td style="border:1px solid black;">
[**MS11-085**](http://go.microsoft.com/fwlink/?linkid=229638)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-086**](http://go.microsoft.com/fwlink/?linkid=229253)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS11-084**](http://go.microsoft.com/fwlink/?linkid=229245)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Совокупный уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Низкий**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=3f9f74a6-e984-4aab-837c-ef7286e7305f)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновлений 1 (SP 1)](http://www.microsoft.com/downloads/details.aspx?familyid=c9cf6a22-f9ab-427a-9b16-33c60baaabb5)\*\*  
(низкий)
</td>
<td style="border:1px solid black;" colspan="2">
[Active Directory и службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=cc1e99af-fc67-400b-a82c-171f8c4d1ac9)\*  
(KB2601626)  
(существенный)
</td>
<td style="border:1px solid black;" colspan="2">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5d810dae-5c52-4155-b5c2-163d27be6e78)\*\*\*  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b20bfcbd-a515-4074-b56e-b82539fe5bad)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=012777f5-51f2-4944-91af-a9c79b8081a1)  
(низкий)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=395819e2-1028-44b7-ace4-ca754b1a7543)  
(средний)
</td>
</tr>
</table>
 
**Примечаниядля Windows Server 2008 и Windows Server 2008 R2**

**\*Уязвимости подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Это обновление (с одинаковым уровнем серьезности) применяется к указанным выше поддерживаемым выпускам Windows Server 2008 или Windows Server 2008 R2 независимо от наличия установленных основных компонентов сервера. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Уязвимости не подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Поддерживаемые выпуски Windows Server 2008 или Windows Server 2008 R2, при развертывании которых выбиралась установка только ядра сервера, не подвержены уязвимостям, устраняемым этим обновлением. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*\*Системы, при развертывании которых устанавливалось только ядро сервера, не подвержены этой уязвимости.** Уязвимость, устраняемая этим обновлением, не затрагивает поддерживаемые выпуски Windows Server 2008 или Windows Server 2008 R2 (согласно указаниям), при развертывании которых выбиралась установка основных компонентов, хотя уязвимые файлы могут находиться в системе. Однако пользователям, в системе которых находятся уязвимые файлы, предлагается установить это обновление, поскольку оно содержит файлы более поздних версий. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
**В центре безопасности**

Управление программным обеспечением и обновлениями для системы безопасности для установки на серверы, настольные и переносные компьютеры организации. Дополнительные сведения см. на веб-сайте [Центра управления обновлениями TechNet](http://go.microsoft.com/fwlink/?linkid=69903). [Центр безопасности TechNet](http://go.microsoft.com/fwlink/?linkid=21171) содержит дополнительные сведения о безопасности в продуктах Майкрософт. Доступ к этим сведениям можно также получить, посетив веб-сайт [Безопасность дома](http://go.microsoft.com/fwlink/?linkid=85102) и щелкнув ссылку "Последние обновления".

Обновления для системы безопасности доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747) и [Центре обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130). Обновления для системы безопасности также доступны на веб-сайте [Центра загрузки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".

Пользователи пакета Microsoft Office для Mac могут следить за установкой последних версий программного обеспечения Майкрософт при помощи приложения Microsoft AutoUpdate для Mac. Дополнительные сведения об использовании приложения Microsoft AutoUpdate для Mac см. в статье [Автоматическая проверка наличия обновлений для программного обеспечения](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

Наконец, обновления для системы безопасности можно загрузить из [каталога Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=96155). Он обеспечивает возможность поиска содержимого (в том числе обновлений для системы безопасности, драйверов и пакетов обновления), которое предоставляется через Центр обновления Windows и Центр обновления Майкрософт. При поиске по номеру бюллетеня по безопасности (например, MS07-036) можно добавлять необходимые обновления (в том числе на различных языках) в корзину и загружать их в указанную папку. Дополнительные сведения см. на веб-сайте каталога Центра обновления Майкрософт в разделе [вопросов и ответов](http://go.microsoft.com/fwlink/?linkid=97900).

**Руководство по диагностике и развертыванию**

Корпорация Майкрософт предоставляет руководство по диагностике и развертыванию обновлений для системы безопасности. В этом руководстве содержатся рекомендации и сведения, позволяющие ИТ-специалистам оптимальнее использовать различные средства для диагностики и развертывания обновлений для системы безопасности. Дополнительные сведения см. в [статье 961747 базы знаний Майкрософт](http://support.microsoft.com/kb/961747).

**Анализатор безопасности Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений безопасности и стандартных ошибок в конфигурации системы безопасности. Дополнительные сведения об анализаторе безопасности MBSA см. на веб-странице [Анализатор Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Службы Windows Server Update Services**

Службы Windows Server Update Services (WSUS) позволяют администраторам быстрым и надежным образом развертывать последние критические обновления и обновления для систем безопасности операционных систем Microsoft Windows 2000 и более поздних версий, пакетов Office XP и более поздних версий, серверов Exchange Server 2003 и SQL Server 2000 в системах Microsoft Windows 2000 и более поздних версий.

Дополнительные сведения о развертывании данного обновления безопасности с помощью служб WSUS см. на веб-странице [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx).

**System Center Configuration Manager 2007**

Управление обновлениями программного обеспечения с помощью диспетчера конфигураций Configuration Manager 2007 упрощает сложную задачу получения и управления обновлениями ИТ-систем по всему предприятию. С диспетчером конфигураций Configuration Manager 2007 ИТ-администраторы могут получать обновления продуктов Майкрософт на различные устройства, включая настольные и портативные компьютеры и мобильные устройства.

Автоматическая оценка уязвимостей в диспетчере конфигураций Configuration Manager 2007 определяет необходимость в обновлениях и сообщает о рекомендуемых действиях. Управление обновлениями программного обеспечения в диспетчере конфигураций Configuration Manager 2007 встроено в Microsoft Windows Software Update Services (WSUS), проверенную временем инфраструктуру обновления, хорошо знакомую ИТ-администраторам по всему миру. Подробнее о том, как администраторы могут использовать Configuration Manager 2007 для развертывания обновлений, см. [Управление обновлениями программного обеспечения](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). Подробнее о диспетчере конфигураций см. [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет хорошо сконфигурированное решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей.

**Примечание.** Основная поддержка System Management Server 2003 закончена 12 января 2010 г. Подробнее о жизненном цикле продуктов см. на веб-странице [Жизненный цикл поддержки Майкрософт](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Последний выпуск сервера SMS (System Center Configuration Manager 2007) доступен для загрузки; сведения о нем см. в разделе **System Center Configuration Manager 2007**.

Подробнее о том, как администраторы могут использовать SMS 2003 для развертывания обновлений системы безопасности, см. [Сценарии и процедуры для Microsoft Systems Management Server 2003: Распространение программного обеспечения и управление исправлениями](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Дополнительные сведения о сервере SMS см. на веб-странице [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Примечание.** Для предоставления широкой поддержки при определении необходимости применения и развертывания обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используется средство Microsoft Baseline Security Analyzer. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. на веб-странице [Развертывание обновлений программного обеспечения с помощью функции распространения программ сервера SMS](http://go.microsoft.com/fwlink/?linkid=33341) (на английском языке). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакета [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)).

**Средство оценки совместимости обновлений и набор средств для обеспечения совместимости приложений**

Часто обновления записываются в одни те же файлы, а для запуска приложений требуется настроить параметры реестра. Это приводит к возникновению несовместимостей и увеличивает время, затрачиваемое на развертывание обновлений для системы безопасности. Облегчить тестирование и проверку обновлений Windows для установленных приложений можно с помощью [компонентов оценки совместимости обновлений](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true), входящих в состав [набора средств для обеспечения совместимости приложений](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Набор средств для обеспечения совместимости приложений содержит необходимые средства и документацию для выявления проблем совместимости приложений и уменьшения степени воздействия этих проблем перед развертыванием системы Microsoft Windows Vista, обновлений из Центра обновления Windows, обновлений с веб-сайта безопасности Майкрософт или новой версии проводника.

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

#### Обновления, не относящиеся к безопасности и распространяемые через Центр обновления Майкрософт, Центр обновления Windows и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-сайте Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт](http://support.microsoft.com/kb/894199). Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
-   [Обновления за предыдущие месяцы для служб Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Отображаются все новые, обновленные и повторно выпущенные обновления для продуктов Майкрософт отличных от Microsoft Windows.

#### Программа Microsoft Active Protections Program (MAPP)

Чтобы повысить уровень защиты пользователей, корпорация Майкрософт предоставляет сведения об уязвимостях крупным поставщикам программного обеспечения безопасности перед ежемесячным выпуском обновлений. Эта информация необходима им для усовершенствования программного обеспечения и оборудования для защиты пользователей (антивирусных программ, сетевых систем обнаружения вторжений, а также индивидуальных систем предотвращения вторжений). Сведения о новых средствах защиты, предоставляемых поставщиками программного обеспечения безопасности, доступны на соответствующих веб-сайтах партнеров, перечисленных в списке партнеров [MAPP](http://go.microsoft.com/fwlink/?linkid=215201).

#### Стратегии безопасности и сообщество

**Стратегии управления обновлениями**

В статье [Рекомендации по безопасности для управления обновлениями](http://go.microsoft.com/fwlink/?linkid=21168) содержатся дополнительные сведения о рекомендациях Майкрософт по установке обновлений для системы безопасности.

**Другие обновления для системы безопасности**

Другие обновления безопасности можно загрузить из следующих источников:

-   Обновления для системы безопасности доступны в [Центре загрузки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".
-   Обновления для индивидуальных пользователей доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747).
-   Обновления безопасности, предлагаемые в этом месяце в Центре обновления Windows, можно загрузить с веб-сайта Центра загрузки Майкрософт в виде файлов ISO-образа компакт-диска с выпусками обновлений безопасности. Дополнительные сведения см. в [статье 913086 базы знаний Майкрософт](http://support.microsoft.com/kb/913086).

**Сообщество ИТ-специалистов, занимающихся вопросами безопасности**

На веб-сайте [сообщества ИТ-специалистов, занимающихся вопросами безопасности](http://go.microsoft.com/fwlink/?linkid=21164), можно найти сведения о способах улучшения системы безопасности и оптимизации ИТ-инфраструктуры предприятия, а также обсудить вопросы безопасности с другими ИТ-специалистами.

#### Благодарности

Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:

-   Уилла Дормана (Will Dorman) из [CERT/CC](http://www.cert.org/) за сообщение об уязвимости, описанной в MS11-084
-   Ивана Санчеса (Ivan Sanchez) из компании EvilCode за сообщение об уязвимости, описанной в MS11-085
-   Ксавье Лассуа (Xavier Lassoie) и Себастьена Годара (Sébastien Godard) из компании Autosécurité за сообщение об уязвимости, описанной в MS11-086

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Пользователи из США и Канады могут обратиться в службу [поддержки по вопросам безопасности](http://go.microsoft.com/fwlink/?linkid=21131) или позвонить по телефону 1-866-PCSAFETY (1-866-727-2338). Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Дополнительные сведения о вариантах поддержки см. на веб-странице [справки и поддержки корпорации Майкрософт](http://support.microsoft.com/).
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите веб-страницу [международной справки и поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (8 ноября 2011): Обзор бюллетеней опубликован.

*Built at 2014-04-18T01:50:00Z-07:00*
