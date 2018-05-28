---
TOCTitle: 'MS12-SEP'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за сентябрь 2012 года.'
ms:assetid: 'ms12-sep'
ms:contentKeyID: 61236166
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms12-sep(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за сентябрь 2012 года.
====================================================================

Дата публикации: 11 сентября 2012 г. | Дата обновления: 21 сентября 2012 г.

**Версия:** 2.0

В этом обзоре перечислены бюллетени по безопасности, выпущенные в сентябре 2012 года.

После выпуска бюллетеней по безопасности за сентябрь 2012 года этот обзор заменит предварительное уведомление, выпущенное 19 сентября 2012 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [Службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

12 сентября 2012 года в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в сентябрьской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522555&culture=en-us). После наступления этой даты данная веб-трансляция будет доступна [по запросу](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522555&culture=en-us).

21 сентября 2012 года в 12:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей о данном внеплановом бюллетене по безопасности. [Зарегистрируйтесь для участия в сентябрьской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032529852&culture=en-us). После наступления этой даты данная веб-трансляция будет доступна [по запросу](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032529852&culture=en-us).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255505">MS12-063</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление системы безопасности для браузера Internet Explorer (2744842)</strong><br />
<br />
Это обновление системы безопасности устраняет одну опубликованную и четыре обнаруженных пользователями уязвимости в Internet Explorer. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь просмотрит особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся любой из этих уязвимостей, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254184">MS12-061</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Visual Studio Team Foundation Server делает возможным несанкционированное получение прав (2719584)</strong><br />
<br />
Это обновление для системы безопасности устраняет уязвимость в Visual Studio Team Foundation Server, о которой сообщалось в частном порядке. Данная уязвимость делает возможным несанкционированное получение прав, если пользователь перейдет по специально созданной ссылке в сообщении электронной почты или откроет веб-страницу, созданной для использования данной уязвимости. Однако в любом случае злоумышленник не может заставить пользователей выполнить данные действия. Вместо этого злоумышленник должен будет убедить пользователей посетить веб-сайт, обычно приглашая их перейти по соответствующей ссылке, ведущей на этот веб-сайт, в сообщении электронной почты или программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Перезагрузка не требуется</td>
<td style="border:1px solid black;">Средства разработки Microsoft</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=261858">MS12-062</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в System Center Configuration Manager</strong> <strong>делает возможным несанкционированное получение прав (2741528)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft System Center Configuration Manager. Данная уязвимость делает возможным несанкционированное получение прав, если пользователь посетит зараженный веб-сайт, перейдя по специально созданному URL-адресу. Однако злоумышленник не может заставить пользователей посетить такой веб-сайт. Вместо этого злоумышленник должен будет убедить пользователей посетить веб-сайт, обычно приглашая их перейти по соответствующей ссылке, ведущей на этот веб-сайт, в сообщении электронной почты или программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Перезагрузка не требуется</td>
<td style="border:1px solid black;">Серверное программное обеспечение Майкрософт</td>
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

 
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Идентификатор бюллетеня</th>
<th style="border:1px solid black;" >Название уязвимости</th>
<th style="border:1px solid black;" >Код CVE</th>
<th style="border:1px solid black;" >Оценка возможности использования уязвимостей для последнего выпуска программного обеспечения</th>
<th style="border:1px solid black;" >Оценка возможности использования уязвимостей для более старых выпусков программного обеспечения</th>
<th style="border:1px solid black;" >Оценка использования уязвимости типа &quot;отказ в обслуживании&quot;</th>
<th style="border:1px solid black;" >Краткие примечания</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254184">MS12-061</a></td>
<td style="border:1px solid black;">Уязвимость XSS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1892">CVE-2012-1892</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=261858">MS12-062</a></td>
<td style="border:1px solid black;">Уязвимость, приводящая к отраженному межсайтовому выполнению сценариев (XSS)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2536">CVE-2012-2536</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255505">MS12-063</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием протокола OnMove после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1529">CVE-2012-1529</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости[1]</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255505">MS12-063</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием прослушивателя событий после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2546">CVE-2012-2546</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости[1]</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255505">MS12-063</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием раскладки клавиатуры после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2548">CVE-2012-2548</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости[1]</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255505">MS12-063</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием cloneNode после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2557">CVE-2012-2557</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости[1]</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255505">MS12-063</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием execCommand после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4969">CVE-2012-4969</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости[1]</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.<br />
<br />
Корпорации Майкрософт известно об ограниченном количестве атак, направленных на использование данной уязвимости.</td>
</tr>
</tbody>
</table>
 

<sup>[1]</sup>Internet Explorer 10 не подвержен данной уязвимости.

Продукты, подверженные уязвимости, и соответствующие обновления
---------------------------------------------------------------

<span></span>
В приведенных ниже таблицах перечислены бюллетени в порядке важности категорий программного обеспечения и уровней опасности.

**Как пользоваться этими таблицами?**

Обращайтесь к этим таблицам, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и узнайте, имеются ли для них обновления для системы безопасности. Для программ или компонентов, указанных в списке, приведены ссылки на доступные обновления с указанием уровня опасности уязвимостей, которые они устраняют.

**Примечание.** Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификатора бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.

#### Компоненты операционных систем Windows

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
ОС Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-063**](http://go.microsoft.com/fwlink/?linkid=255505)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=967c9ef3-db48-4c2f-9a67-87851fd54962)  
(KB2744842)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6ba78d4c-3657-4963-b2da-7a3763c6b5c9)  
(KB2744842)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ac71ffe3-f077-4753-a238-47a2e9623363)  
(KB2744842)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=020b36c6-7050-4458-8762-bae35eb713cd)  
(KB2744842)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1e2e412a-be97-407e-9f02-fc074db3bb07)  
(KB2744842)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c727d956-be3e-4cd2-913c-f26cb6c33227)  
(KB2744842)  
(критический)
</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-063**](http://go.microsoft.com/fwlink/?linkid=255505)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий** **уровень опасности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=7aaaa15b-87d8-4afc-b183-8ce5becda026)  
(KB2744842)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=aef34ce4-a6ce-4f5e-9892-0a7fbd90c3b4)  
(KB2744842)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d63e25ad-ab8c-425f-89cd-29cd2b7b69d6)  
(KB2744842)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=366feacb-16ad-455c-b2ad-5038f998c432)  
(KB2744842)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=baa47c53-2724-43ef-8590-d3733b47e75b)  
(KB2744842)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=84144e56-f653-4c92-bf49-d44d9ba10489)  
(KB2744842)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=c28d6dc3-c2f0-4505-a545-85b7a0e3e2dc)  
(KB2744842)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=86c28695-86a5-4c17-82d6-7f98b3162aa6)  
(KB2744842)  
(средний)
</td>
</tr>
<tr>
<th colspan="2">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-063**](http://go.microsoft.com/fwlink/?linkid=255505)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=053546fc-ed41-43c2-b4f2-b76334314f5c)  
(KB2744842)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0a5a446d-0a48-4eec-b424-87339b34a3be)  
(KB2744842)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=daba1ef1-62db-43db-9d5b-495aa2d3550f)  
(KB2744842)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=cbe5681b-c28e-4a6a-9b97-0bfe44acf077)  
(KB2744842)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5642136e-68f6-42e8-b48e-1549733c6e7d)  
(KB2744842)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=aae496ef-fca2-4632-9a8f-2108722d2b28)  
(KB2744842)  
(критический)
</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-063**](http://go.microsoft.com/fwlink/?linkid=255505)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=df861b42-bcf2-4f7a-9019-f49e6725f5dc)  
(KB2744842)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=1d4f0f25-9539-4c38-babb-4af7f0f4c6cf)  
(KB2744842)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=0b2965d7-e0b2-4035-a9e4-f6badb389098)  
(KB2744842)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=fa9878c0-b7e5-43ac-b1eb-679e62cf62fc)  
(KB2744842)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=10bab7d4-0dd8-4fa7-b26c-715a68553707)  
(KB2744842)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=612a94ef-0950-41e8-9875-a8f0e71eba6f)  
(KB2744842)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ded887a4-a06d-4447-b19d-19d0f4928523)  
(KB2744842)  
(средний)
</td>
</tr>
<tr>
<th colspan="2">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-063**](http://go.microsoft.com/fwlink/?linkid=255505)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=93591461-39ff-4cbd-8df3-88cb80ed6255)  
(KB2744842)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b303f86a-df17-4961-b677-0c38bd6a86d3)  
(KB2744842)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=93591461-39ff-4cbd-8df3-88cb80ed6255)  
(KB2744842)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b303f86a-df17-4961-b677-0c38bd6a86d3)  
(KB2744842)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e2083388-19a9-4754-9449-1dad2a7f7543)  
(KB2744842)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=01045ee2-c7c4-4078-969f-905fd7e8774f)  
(KB2744842)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e2083388-19a9-4754-9449-1dad2a7f7543)  
(KB2744842)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=01045ee2-c7c4-4078-969f-905fd7e8774f)  
(KB2744842)  
(критический)
</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-063**](http://go.microsoft.com/fwlink/?linkid=255505)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d46ec8ea-b8c8-42d9-a201-f36eb97b91b8)  
(KB2744842)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c44a0253-fefc-4ce6-9cfd-396fdea71f8d)  
(KB2744842)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d46ec8ea-b8c8-42d9-a201-f36eb97b91b8)  
(KB2744842)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c44a0253-fefc-4ce6-9cfd-396fdea71f8d)  
(KB2744842)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c132173b-f869-47ec-bb70-6307081473fe)  
(KB2744842)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c132173b-f869-47ec-bb70-6307081473fe)  
(KB2744842)  
(средний)
</td>
</tr>
</table>
 

#### Программное обеспечение и средства разработки Microsoft

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Visual Studio Team Foundation Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-061**](http://go.microsoft.com/fwlink/?linkid=254184)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio Team Foundation Server 2010 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio Team Foundation Server 2010 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=721c4a38-b255-4792-83a5-7526a680a79a)<sup>[1]</sup>
(KB2719584)  
(существенный)
</td>
</tr>
</table>
 
**Примечания к бюллетеню MS12-061**

<sup>[1]</sup>Это накопительное обновление, которое заменяет предыдущие накопительные обновления для указанного программного обеспечения.

#### Серверное программное обеспечение Майкрософт

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft System Center Configuration Manager
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-062**](http://go.microsoft.com/fwlink/?linkid=261858)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Systems Management Server 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Systems Management Server 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=f3a3d8e1-d551-43b4-9d54-9536f30c074d)<sup>[1]</sup>
(KB2733631)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft System Center Configuration Manager 2007 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft System Center Configuration Manager 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=89890c0e-118b-49ea-9fd1-6d23c674f9e8)<sup>[1]</sup>
(KB2721642)  
(существенный)
</td>
</tr>
</table>
 
**Примечания к бюллетеню MS12-062**

<sup>[1]</sup>Это обновление можно загрузить только с веб-сайта Центра загрузки Майкрософт.

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
**В центре безопасности**

Управление программным обеспечением и обновлениями для системы безопасности для установки на серверы, настольные и переносные компьютеры организации. Дополнительные сведения см. на веб-сайте [Центра управления обновлениями TechNet](http://go.microsoft.com/fwlink/?linkid=69903). [Центр безопасности TechNet](http://go.microsoft.com/fwlink/?linkid=21171) предоставляет дополнительные сведения о безопасности в продуктах Майкрософт. Также эта информация доступна на веб-сайте [Центра безопасности Майкрософт](http://go.microsoft.com/fwlink/?linkid=85102) в разделе "Обновления для системы безопасности".

Обновления для системы безопасности доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747) и [Центре обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130). Обновления для системы безопасности также доступны на веб-сайте [Центра загрузки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".

Пользователи пакета Microsoft Office для Mac могут следить за установкой последних версий программного обеспечения Майкрософт при помощи приложения Microsoft AutoUpdate для Mac. Дополнительные сведения об использовании приложения Microsoft AutoUpdate для Mac см. в статье [Автоматическая проверка наличия обновлений для программного обеспечения](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

Наконец, обновления для системы безопасности можно загрузить из [каталога Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=96155). Он обеспечивает возможность поиска содержимого (в том числе обновлений для системы безопасности, драйверов и пакетов обновления), которое предоставляется через Центр обновления Windows и Центр обновления Майкрософт. При поиске по номеру бюллетеня по безопасности (например, "MS12-001") можно добавить в корзину все необходимые обновления (в том числе несколько языковых версий одного обновления) и загрузить их в указанную папку. Дополнительные сведения см. на веб-сайте каталога Центра обновления Майкрософт в разделе [вопросов и ответов](http://go.microsoft.com/fwlink/?linkid=97900).

**Руководство по диагностике и развертыванию**

Корпорация Майкрософт предоставляет руководство по диагностике и развертыванию обновлений для системы безопасности. В этом руководстве содержатся рекомендации и сведения, позволяющие ИТ-специалистам оптимальнее использовать различные средства для диагностики и развертывания обновлений для системы безопасности. Дополнительные сведения см. в [статье 961747 базы знаний Майкрософт](http://support.microsoft.com/kb/961747).

**Анализатор безопасности Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений безопасности и стандартных ошибок в конфигурации системы безопасности. Дополнительные сведения об анализаторе безопасности MBSA см. на веб-сайте [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Службы Windows Server Update Services**

Службы Windows Server Update Services (WSUS) позволяют администраторам быстрым и надежным образом развертывать последние критические обновления и обновления для систем безопасности операционных систем Microsoft Windows 2000 и более поздних версий, пакетов Office XP и более поздних версий, серверов Exchange Server 2003 и SQL Server 2000 в системах Microsoft Windows 2000 и более поздних версий.

Дополнительные сведения о развертывании данного обновления безопасности с помощью служб WSUS см. на веб-странице [Windows Server Update Services](http://technet.microsoft.com/wsus/default).

**SystemCenter Configuration Manager**

Управление обновлениями программного обеспечения с помощью диспетчера конфигураций System Center Configuration Manager упрощает сложную задачу получения обновлений и управления обновлениями в ИТ-системах всего предприятия. Используя диспетчер конфигураций System Center Configuration Manager, ИТ-администраторы могут получать обновления продуктов Майкрософт на различные устройства, включая настольные и мобильные компьютеры, серверы и мобильные устройства.

Автоматическая оценка уязвимостей в диспетчере конфигураций System Center Configuration Manager определяет необходимость в обновлениях и сообщает о рекомендуемых действиях. Управление обновлениями программного обеспечения в диспетчере конфигураций System Center Configuration Manager встроено в Microsoft Windows Software Update Services (WSUS), проверенную временем инфраструктуру обновления, хорошо знакомую ИТ-администраторам во всем мире. Подробнее о диспетчере конфигураций System Center Configuration Manager см. в статье [Технические ресурсы по System Center](http://technet.microsoft.com/systemcenter/bb980621).

**Systems Management Server 2003**

Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет хорошо сконфигурированное решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей.

**Примечание.** Основная поддержка System Management Server 2003 закончена 12 января 2010 г. Подробнее о жизненном цикле продуктов см. на веб-странице [Жизненный цикл поддержки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742). Следующий выпуск сервера SMS (System Center Configuration Manager), уже доступен для загрузки; см. предыдущий раздел **System Center Configuration Manager**.

Подробнее о том, как администраторы могут использовать SMS 2003 для развертывания обновлений системы безопасности, см. [Сценарии и процедуры для Microsoft Systems Management Server 2003: Распространение программного обеспечения и управление исправлениями](http://www.microsoft.com/downloads/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f). Дополнительные сведения о сервере SMS см. на веб-странице [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/systemcenter/bb545936).

**Примечание.** Для предоставления широкой поддержки при определении необходимости применения и развертывания обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используется средство Microsoft Baseline Security Analyzer. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. на веб-странице [Развертывание обновлений программного обеспечения с помощью функции распространения программ сервера SMS](http://go.microsoft.com/fwlink/?linkid=33341) (на английском языке). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакета [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)).

**Средство оценки совместимости обновлений и набор средств для обеспечения совместимости приложений**

Часто обновления записываются в одни те же файлы, а для запуска приложений требуется настроить параметры реестра. Это приводит к возникновению несовместимостей и увеличивает время, затрачиваемое на развертывание обновлений для системы безопасности. Облегчить тестирование и проверку обновлений Windows для установленных приложений можно с помощью [компонентов оценки совместимости обновлений](http://technet.microsoft.com/library/cc749197), входящих в состав [набора средств для обеспечения совместимости приложений](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971).

Набор средств для обеспечения совместимости приложений содержит необходимые средства и документацию для выявления проблем совместимости приложений и уменьшения степени воздействия этих проблем перед развертыванием системы Windows Vista, обновлений из Центра обновления Windows, обновлений с веб-сайта безопасности Майкрософт или новой версии проводника.

### Прочие сведения

#### Обновления, не относящиеся к безопасности и распространяемые через Центр обновления Майкрософт, Центр обновления Windows и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-сайте Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт](http://support.microsoft.com/kb/894199). Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
-   [Обновления за предыдущие месяцы для служб Windows Server Update Services](http://technet.microsoft.com/wsus/bb456965). Отображаются все новые, обновленные и повторно выпущенные обновления для продуктов Майкрософт отличных от Microsoft Windows.

#### Программа Microsoft Active Protections Program (MAPP)

Чтобы повысить уровень защиты пользователей, корпорация Майкрософт предоставляет сведения об уязвимостях крупным поставщикам программного обеспечения безопасности перед ежемесячным выпуском обновлений. Эта информация необходима им для усовершенствования программного обеспечения и оборудования для защиты пользователей (антивирусных программ, сетевых систем обнаружения вторжений, а также индивидуальных систем предотвращения вторжений). Сведения о средствах защиты, предоставляемых поставщиками программного обеспечения безопасности, доступны на соответствующих веб-сайтах партнеров, перечисленных в списке партнеров [MAPP](http://go.microsoft.com/fwlink/?linkid=215201).

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

-   Сунил Ядав (Sunil Yadav) из компании INR Labs ([Network Intelligence India](http://niiconsulting.com/)) за сообщение об уязвимости, описанной в бюллетене MS12-061
-   Энди Янг (Andy Yang) из компании [Stratsec](http://www.stratsec.net) за сообщение об уязвимости, описанной в бюллетене MS12-062
-   Анонимного исследователя, сотрудничающего с [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости, описанной в бюллетене MS12-063
-   [Росарио Валотта (Rosario Valotta)](https://sites.google.com/site/tentacoloviola) за сообщение об уязвимости, описанной в бюллетене MS12-063
-   Стивена Фьюера (Stephen Fewer) из компании [Harmony Security](http://www.harmonysecurity.com/), сотрудничающего с [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в бюллетене MS12-063
-   Анонимного исследователя, сотрудничающего с [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в бюллетене MS12-063
-   Анонимного исследователя, сотрудничающего с [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в бюллетене MS12-063
-   [Компанию Mitre](http://www.mitre.org/) за совместную работу над устранением уязвимости, описанной в бюллетене MS12-063

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617.aspx)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (11 сентября 2012 г.): Обзор бюллетеней опубликован.
-   Вер. 2.0 (21 сентября 2012 г.): Добавлен бюллетень по безопасности Майкрософт MS12-063, Накопительное обновление системы безопасности для Internet Explorer (2744842). а также ссылка на сведения о веб-трансляции, посвященной внеплановому бюллетеню по безопасности.

*Built at 2014-04-18T01:50:00Z-07:00*
