---
TOCTitle: 'MS12-APR'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за апрель 2012 года'
ms:assetid: 'ms12-apr'
ms:contentKeyID: 61236155
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms12-apr(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за апрель 2012 года
=================================================================

Дата публикации: 10 апреля 2012 г. | Дата обновления: 26 апреля 2012 г.

**Версия:** 2.0

В этот обзор включены бюллетени по безопасности, выпущенные в апреле 2012 года.

После выпуска бюллетеней за апрель 2012 г. этот обзор заменит предварительное уведомление, выпущенное 5 апреля 2012 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

11 апреля 2012 г. в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проводит веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в апрельской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499650). После наступления этой даты данная веб-трансляция будет доступна по запросу. Дополнительные сведения см. на веб-сайте [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://go.microsoft.com/fwlink/?linkid=217214).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=242739">MS12-023</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (2675157)</strong><br />
<br />
Это обновление для системы безопасности устраняет пять обнаруженных пользователями уязвимостей в браузере Internet Explorer. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь просмотрит особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся любой из этих уязвимостей, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238623">MS12-024</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Windows делает возможным удаленное выполнение кода (2653956)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость делает возможным удаленное выполнение кода, если пользователь или приложение запускает или устанавливает особым образом созданный и подписанный переносимый исполняемый (PE) файл в уязвимой системе.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=242032">MS12-025</a></td>
<td style="border:1px solid black;"><strong>Уязвимость платформы .NET Framework делает возможным удаленное выполнение</strong> <strong>кода (2671605)</strong><br />
<br />
Данное обновление для системы безопасности устраняет обнаруженную пользователями уязвимость Microsoft .NET Framework. Данная уязвимость делает возможным удаленное выполнение кода в клиентской системе, если пользователь просмотрит особым образом созданную веб-страницу в веб-браузере, который может выполнять браузерные приложения XAML (XBAP). Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. Кроме того, данная уязвимость делает возможным удаленное выполнение кода на серверных системах, в которых запущены службы IIS, если на этом сервере разрешена обработка страниц ASP.NET и злоумышленнику удастся загрузить на сервер и выполнить особым образом созданные страницы ASP.NET (например, при атаке через хостинговые службы). Данная уязвимость могла использоваться приложениями Windows .NET для обхода ограничений разграничения доступа кода (CAS). При атаке посредством использования веб-браузеров злоумышленник может разместить в сети веб-сайт, содержащий веб-страницу, предназначенную для использования данной уязвимости. Кроме того, веб-сайты, подвергшиеся атаке злоумышленников, равно как и веб-сайты, принимающие или размещающие пользовательские материалы или объявления, также могут иметь специальное содержимое, рассчитанное на использование данной уязвимости. Однако в любом случае злоумышленник не может заставить пользователей посетить эти веб-сайты. Вместо этого злоумышленник должен будет убедить пользователей посетить веб-сайт, обычно приглашая их перейти по соответствующей ссылке, ведущей на этот веб-сайт, в сообщении электронной почты или программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246275">MS12-027</a></td>
<td style="border:1px solid black;"><strong>Уязвимость общих элементов управления Windows делает возможным удаленное выполнение кода (2664258)</strong><br />
<br />
Данное обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в общих элементах управления Windows. Данная уязвимость делает возможным удаленное выполнение кода, если пользователь посетит веб-сайт, который содержит специально созданное содержимое, предназначенное для использования данной уязвимости. В любом случае злоумышленник не может заставить пользователей посетить такой веб-сайт. Вместо этого злоумышленник должен будет убедить пользователей посетить веб-сайт, обычно приглашая их перейти по соответствующей ссылке, ведущей на этот веб-сайт, в сообщении электронной почты или программы обмена мгновенными сообщениями. Вредоносный файл также может быть выслан во вложении электронной почты, однако для того чтобы использовать эту уязвимость, злоумышленнику необходимо убедить пользователя открыть вложение.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft SQL Server,<br />
Серверное программное обеспечение Майкрософт,<br />
Средства разработки Microsoft</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238519">MS12-026</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Forefront Unified Access Gateway (UAG) могут привести к раскрытию информации (2663860)</strong><br />
<br />
Данное обновление для системы безопасности устраняет две обнаруженных пользователями уязвимости в Microsoft Forefront Unified Access Gateway (UAG). Наиболее серьезная из этих уязвимостей делает возможным раскрытие информации, если злоумышленник отправит специально созданный запрос в сервер UAG.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Раскрытие информации</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Forefront United Access Gateway</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232498">MS12-028</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Office делает возможным удаленное выполнение кода (2639185)</strong><br />
<br />
Данное обновление для системы безопасности устраняет обнаруженную пользователями уязвимость приложений Microsoft Office и Microsoft Works. Эта уязвимость позволяет удаленно выполнять код, когда пользователь открывает специально созданный файл Works. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
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
  
| Идентификатор бюллетеня                                   | Название уязвимости                                                         | Код CVE                                                                          | Оценка возможности использования уязвимостей для последнего выпуска программного обеспечения               | Оценка возможности использования уязвимостей для более старых выпусков программного обеспечения        | Оценка использования уязвимости типа "отказ в обслуживании" | Краткие примечания                                                                                                                   |  
|-----------------------------------------------------------|-----------------------------------------------------------------------------|----------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|  
| [MS12-023](http://go.microsoft.com/fwlink/?linkid=242739) | Уязвимость Jscript9, делающая возможным удаленное выполнение кода           | [CVE-2012-0169](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0169) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) — существование кода эксплойта маловероятно | Не подвержены уязвимости                                                                               | Временный                                                   | (Нет)                                                                                                                                |  
| [MS12-023](http://go.microsoft.com/fwlink/?linkid=242739) | Уязвимость OnReadyStateChange, делающая возможным удаленное выполнение кода | [CVE-2012-0170](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0170) | Не подвержены уязвимости                                                                                   | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Временный                                                   | (Нет)                                                                                                                                |  
| [MS12-023](http://go.microsoft.com/fwlink/?linkid=242739) | Уязвимость SelectAll, делающая возможным удаленное выполнение кода          | [CVE-2012-0171](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0171) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Временный                                                   | (Нет)                                                                                                                                |  
| [MS12-023](http://go.microsoft.com/fwlink/?linkid=242739) | Уязвимость стиля VML, делающая возможным удаленное выполнение кода          | [CVE-2012-0172](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0172) | Не подвержены уязвимости                                                                                   | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Временный                                                   | (Нет)                                                                                                                                |  
| [MS12-024](http://go.microsoft.com/fwlink/?linkid=238623) | Уязвимость WinVerifyTrust, связанная с проверкой подписи                    | [CVE-2012-0151](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0151) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                                                                                                |  
| [MS12-025](http://go.microsoft.com/fwlink/?linkid=242032) | Уязвимость проверки параметров .NET Framework                               | [CVE-2012-0163](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0163) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                                                                                                |  
| [MS12-026](http://go.microsoft.com/fwlink/?linkid=238519) | Уязвимость, связанная с доступом к веб-сайту по умолчанию в UAG             | [CVE-2012-0147](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0147) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) — существование кода эксплойта маловероятно | Не подвержены уязвимости                                                                               | Не применимо                                                | Это уязвимость, делающая возможным раскрытие информации.                                                                             |  
| [MS12-027](http://go.microsoft.com/fwlink/?linkid=246275) | Уязвимость в MSCOMCTL.OCX RCE                                               | [CVE-2012-0158](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0158) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | Корпорации Майкрософт известно об ограниченном количестве направленных атак с целью использования этой уязвимости.                   |  
| [MS12-028](http://go.microsoft.com/fwlink/?linkid=232498) | Уязвимость конвертера изображений WPS, связанная с переполнением кучи       | [CVE-2012-0177](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0177) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) — существование кода эксплойта маловероятно | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | Microsoft Office 2007 с пакетом обновления 3 (SP3) и все поддерживаемые выпуски Microsoft Office 2010 не подвержены этой уязвимости. |
  
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
<th colspan="4">
ОС Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-023**](http://go.microsoft.com/fwlink/?linkid=242739)
</td>
<td style="border:1px solid black;">
[**MS12-024**](http://go.microsoft.com/fwlink/?linkid=238623)
</td>
<td style="border:1px solid black;">
[**MS12-025**](http://go.microsoft.com/fwlink/?linkid=242032)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=2a490c62-16c4-402a-b2d9-3e8cfb5bcebd)  
(KB2675157)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=81b28dd9-87aa-46cc-94c6-2da39d0298db)  
(KB2675157)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=74ce0e29-046b-4ac3-89a1-b292a177972f)  
(KB2675157)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=575afd20-cee4-4fa9-b781-9f8dfdd41ebe)  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=1cfeae57-d4e9-4fff-8956-523e7b71453c)  
(KB2656378)  
(Только Media Center Edition 2005 и Tablet PC Edition 2005)  
(критический)  
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390)  
(KB2656370)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509)  
(KB2656369)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=a1b7be43-a32e-456b-8df0-c26cdf187682)  
(KB2675157)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=29ec7b06-c7aa-4149-bb2c-25af7d38a6a9)  
(KB2675157)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=646c6352-4d99-413a-a75b-71289b5d2b25)  
(KB2675157)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=adc31695-1be6-4976-869c-007df8ac8508)  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390)  
(KB2656370)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509)  
(KB2656369)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-023**](http://go.microsoft.com/fwlink/?linkid=242739)
</td>
<td style="border:1px solid black;">
[**MS12-024**](http://go.microsoft.com/fwlink/?linkid=238623)
</td>
<td style="border:1px solid black;">
[**MS12-025**](http://go.microsoft.com/fwlink/?linkid=242032)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий** **уровень опасности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=020e0d68-dd1c-4297-b565-fcc6dcf5f280)  
(KB2675157)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=17b0c139-2709-424d-9d17-827af468e858)  
(KB2675157)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=3289a80a-d1b1-4494-bede-03d0be579acf)  
(KB2675157)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=f79c8940-ca31-4ff7-924e-847f5eef7864)  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=ffd26218-e149-44ea-a0b9-f2a1315fce9e)  
(KB2656376)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509)  
(KB2656369)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=295292d3-01a3-4574-b994-8cdbcf5a0d2e)  
(KB2675157)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=04656a93-e958-4764-afe8-27c476855506)  
(KB2675157)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=dff4fb63-b319-49ed-8a9d-6b15e43d5bfd)  
(KB2675157)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=03ebf111-1e7b-4dc2-b84f-a26c6b5f0d58)  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390)  
(KB2656370)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509)  
(KB2656369)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=09011393-c7d5-4225-9b8e-5a234d4dbcd1)  
(KB2675157)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a5ef0147-595e-43b5-819f-73780fcef10d)  
(KB2675157)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=734ff97a-7d72-4bfe-9557-7fac91902f8e)  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390)  
(KB2656370)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509)  
(KB2656369)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr>
<th colspan="4">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-023**](http://go.microsoft.com/fwlink/?linkid=242739)
</td>
<td style="border:1px solid black;">
[**MS12-024**](http://go.microsoft.com/fwlink/?linkid=238623)
</td>
<td style="border:1px solid black;">
[**MS12-025**](http://go.microsoft.com/fwlink/?linkid=242032)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f598cad1-4d1a-40ce-a016-bb58778d5dc0)  
(KB2675157)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=44284277-06a7-405d-9187-8f50a042604d)  
(KB2675157)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=51088164-13b7-4216-90f1-20c92c8b8ca9)  
(KB2675157)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c7683919-6d46-4b3e-aa98-1bef20141835)  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390)  
(KB2656370)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80)  
(KB2656374)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2717a997-2066-4a83-ae9b-4611a0851101)  
(KB2675157)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=19684033-ddeb-464f-9a22-f580a9c19f8e)  
(KB2675157)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=bbb99aee-aadd-4ec7-9e27-91cb8d90803e)  
(KB2675157)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4d9f8a6e-17bd-4ed3-8bc7-d5e3b11ca12a)  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390)  
(KB2656370)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80)  
(KB2656374)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-023**](http://go.microsoft.com/fwlink/?linkid=242739)
</td>
<td style="border:1px solid black;">
[**MS12-024**](http://go.microsoft.com/fwlink/?linkid=238623)
</td>
<td style="border:1px solid black;">
[**MS12-025**](http://go.microsoft.com/fwlink/?linkid=242032)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3e361edd-234b-4053-aa49-278b9fde4d5c)\*\*  
(KB2675157)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=6eb6781e-7b38-4679-afbc-4e3bb5747fd8)\*\*  
(KB2675157)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=d34d7981-ed63-460d-95e4-e6da1ac41d2f)\*\*  
(KB2675157)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c36c20f7-a742-4151-b8f2-85ef80479d06)\*  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390)  
(KB2656370)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80)  
(KB2656374)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=60b76a3c-4530-4101-931f-45df621e1eed)\*\*  
(KB2675157)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=fd657467-a45c-4354-b947-3a3cceb9b690)\*\*  
(KB2675157)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c9d773e9-6a2e-45db-8f30-7da0082d909c)\*\*  
(KB2675157)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=330cea47-221d-439e-b106-58a146fc28ee)\*  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390)  
(KB2656370)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80)  
(KB2656374)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3235216f-497f-4934-81b8-1eb9929e98c9)  
(KB2675157)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1ec74522-ec1e-4b3c-bfeb-6a505cc4f11a)  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390)  
(KB2656370)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80)  
(KB2656374)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr>
<th colspan="4">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-023**](http://go.microsoft.com/fwlink/?linkid=242739)
</td>
<td style="border:1px solid black;">
[**MS12-024**](http://go.microsoft.com/fwlink/?linkid=238623)
</td>
<td style="border:1px solid black;">
[**MS12-025**](http://go.microsoft.com/fwlink/?linkid=242032)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9a58ca0b-fad7-418e-80ae-ca478168f887)  
(KB2675157)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=e6724be3-ff4b-4dea-95f3-0b13998b6758)  
(KB2675157)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=ac183b66-0247-4ae5-bda0-e8d0070917c8)  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=c3f521a9-4dc8-46b7-a7f2-696b8759b398)  
(KB2656372)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9a58ca0b-fad7-418e-80ae-ca478168f887)  
(KB2675157)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=e6724be3-ff4b-4dea-95f3-0b13998b6758)  
(KB2675157)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=ac183b66-0247-4ae5-bda0-e8d0070917c8)  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=efccca8d-1371-4cda-96ab-ceef735742e2)  
(KB2656373)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7215f707-c536-4d81-ad66-e7bff592e400)  
(KB2675157)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=0ff822d0-074a-409c-9174-8100618c6171)  
(KB2675157)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=27226e64-266f-499e-8c57-866593fc3430)  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=c3f521a9-4dc8-46b7-a7f2-696b8759b398)  
(KB2656372)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7215f707-c536-4d81-ad66-e7bff592e400)  
(KB2675157)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=0ff822d0-074a-409c-9174-8100618c6171)  
(KB2675157)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=27226e64-266f-499e-8c57-866593fc3430)  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=efccca8d-1371-4cda-96ab-ceef735742e2)  
(KB2656373)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-023**](http://go.microsoft.com/fwlink/?linkid=242739)
</td>
<td style="border:1px solid black;">
[**MS12-024**](http://go.microsoft.com/fwlink/?linkid=238623)
</td>
<td style="border:1px solid black;">
[**MS12-025**](http://go.microsoft.com/fwlink/?linkid=242032)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=237d94e6-b9b9-4177-81fa-a67df2806b0e)\*\*  
(KB2675157)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=d002bfe4-10e9-46d3-a460-06d112201ca5)\*\*  
(KB2675157)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=54db1495-31bb-4435-a442-74e484630b8a)\*  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=c3f521a9-4dc8-46b7-a7f2-696b8759b398)\*  
(KB2656372)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=237d94e6-b9b9-4177-81fa-a67df2806b0e)\*\*  
(KB2675157)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=d002bfe4-10e9-46d3-a460-06d112201ca5)\*\*  
(KB2675157)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=54db1495-31bb-4435-a442-74e484630b8a)\*  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=efccca8d-1371-4cda-96ab-ceef735742e2)\*  
(KB2656373)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)\*<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7bdba902-0a6e-451e-a29b-6d0a03ff5664)  
(KB2675157)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=9a4115bf-028b-4dcc-8995-d3341fdf42f2)  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=c3f521a9-4dc8-46b7-a7f2-696b8759b398)  
(KB2656372)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7bdba902-0a6e-451e-a29b-6d0a03ff5664)  
(KB2675157)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=9a4115bf-028b-4dcc-8995-d3341fdf42f2)  
(KB2653956)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=efccca8d-1371-4cda-96ab-ceef735742e2)  
(KB2656373)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf)<sup>[1]</sup>
(KB2656368)  
(критический)
</td>
</tr>
</table>
 
**Примечания для Windows Server 2008 и Windows Server 2008 R2**

**\*Уязвимости подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Это обновление (с одинаковым уровнем серьезности) применяется к указанным выше поддерживаемым выпускам Windows Server 2008 или Windows Server 2008 R2 независимо от наличия установленных основных компонентов сервера. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Уязвимости не подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Поддерживаемые выпуски Windows Server 2008 или Windows Server 2008 R2, при развертывании которых выбиралась установка только ядра сервера, не подвержены уязвимостям, устраняемым этим обновлением. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Примечания** **к бюллетеню** **MS12-025**

<sup>[1]</sup>**Уязвимости подвержены NET Framework 4 и клиентский профиль .NET Framework 4** Предлагаются два профиля для распространяемых пакетов .NET Framework версии 4: .NET Framework 4 и клиентский профиль .NET Framework 4. Клиентский профиль .NET Framework 4 является частью .NET Framework 4. Уязвимости, устраняемой данным обновлением, подвержены как платформа .NET Framework 4, так и клиентский профиль .NET Framework 4. Дополнительные сведения см. в статье MSDN [Установка .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Пакеты приложений и программные продукты Microsoft Office

 
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Наборы приложений и компоненты Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-027**](http://go.microsoft.com/fwlink/?linkid=246275)
</td>
<td style="border:1px solid black;">
[**MS12-028**](http://go.microsoft.com/fwlink/?linkid=232498)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959)  
(Общие элементы управления Windows)  
(KB2597112)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9)  
(Общие элементы управления Windows)  
(KB2598041)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=fbf24cc6-89e1-48dd-bb83-23eed30195e1)  
(KB2596871)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9)  
(Общие элементы управления Windows)  
(KB2598041)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 (32-разрядные версии)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=23c9d7bf-c9e0-4e01-8b66-da542332a28b)  
(Общие элементы управления Windows)  
(KB2598039)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=23c9d7bf-c9e0-4e01-8b66-da542332a28b)  
(Общие элементы управления Windows)  
(KB2598039)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Веб-компоненты Microsoft Office.
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-027**](http://go.microsoft.com/fwlink/?linkid=246275)
</td>
<td style="border:1px solid black;">
[**MS12-028**](http://go.microsoft.com/fwlink/?linkid=232498)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Веб-компоненты Microsoft Office 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Веб-компоненты Microsoft Office 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959)  
(Общие элементы управления Windows)  
(KB2597112)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Прочие программы Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-027**](http://go.microsoft.com/fwlink/?linkid=246275)
</td>
<td style="border:1px solid black;">
[**MS12-028**](http://go.microsoft.com/fwlink/?linkid=232498)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 9
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Works 9](http://www.microsoft.com/downloads/details.aspx?familyid=94e17a66-cf09-4314-89ec-53deadabfa66)  
(KB2680317)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
конвертером файлов Microsoft Works 6–9
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[конвертером файлов Microsoft Works 6–9](http://www.microsoft.com/downloads/details.aspx?familyid=4605f684-6314-4758-adeb-2a8810dfc8d1)  
(KB2680326)  
(существенный)
</td>
</tr>
</table>
 
**Примечание для MS12-027**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Серверное программное обеспечение Майкрософт

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-027**](http://go.microsoft.com/fwlink/?linkid=246275)
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
Microsoft SQL Server 2000 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Службы анализа Microsoft SQL Server 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=198f1819-818b-4b2e-a424-4a45729746eb)  
(KB983807)  
(критический)  
Обновление GDR:  
[Microsoft SQL Server 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=2a9d97e8-79e0-4997-88fe-1224707e1b37)  
(KB983808)  
(критический)  
Обновление QFE:  
[Microsoft SQL Server 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=8d0cac2f-f227-4e00-9454-4df62be86407)  
(KB983809)  
(критический)
</td>
</tr>
<tr>
<th colspan="2">
Компоненты Microsoft SQL Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2005 для 32-разрядных систем с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 для 32-разрядных систем с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959)<sup>[1]</sup>
(Общие элементы управления Windows)  
(KB2597112)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2005 для систем на базе процессоров Itanium с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 для систем на базе процессоров Itanium с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959)<sup>[1]</sup>
(Общие элементы управления Windows)  
(KB2597112)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2005 для 64-разрядных систем с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 для 64-разрядных систем с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959)<sup>[1]</sup>
(Общие элементы управления Windows)  
(KB2597112)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2005 Express Edition с дополнительными службами и пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 Express Edition с дополнительными службами и пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959)<sup>[1]</sup>
(Общие элементы управления Windows)  
(KB2597112)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2598041)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для 32-разрядных систем с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для 32-разрядных систем с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2598041)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2598041)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для 64-разрядных систем с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для 64-разрядных систем с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2598041)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для систем на базе процессоров Itanium с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для систем на базе процессоров Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2598041)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для систем на базе процессоров Itanium с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для систем на базе процессоров Itanium с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2598041)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2598041)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2598041)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2598041)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2598041)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для систем на базе процессоров Itanium
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 систем на базе процессоров Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2598041)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для систем на базе процессоров Itanium с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 для систем на базе процессоров Itanium с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2598041)  
(критический)
</td>
</tr>
</table>
 
**Примечания** **к бюллетеню** **MS12-027**

<sup>[1]</sup>Это такое же обновление, как обновление KB2597112 для Microsoft Office 2003

<sup>[2]</sup>Это такое же обновление, как обновление KB2598041 для Microsoft Office 2007

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Сервер Microsoft BizTalk Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-027**](http://go.microsoft.com/fwlink/?linkid=246275)
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
Microsoft BizTalk Server 2002 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft BizTalk Server 2002 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d90b78d2-551b-499b-9bd2-85b40646dbc7)  
(KB2645025)  
(критический)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Commerce Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-027**](http://go.microsoft.com/fwlink/?linkid=246275)
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
Microsoft Commerce Server 2002 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2002 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=35de8833-50ae-482d-aa07-497bf68fb38e)  
(KB2658674)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Commerce Server 2007 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3f04fb90-8f11-4392-a4bc-800903091f04)  
(KB2658677)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Commerce Server 2009
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2009](http://www.microsoft.com/downloads/details.aspx?familyid=a8998b6b-e9a4-457e-a34f-0458dda81f2f)  
(KB2655547)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Commerce Server 2009 R2
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2009 R2](http://www.microsoft.com/downloads/details.aspx?familyid=e9221811-8913-412b-ae04-21a55ce7c4c5)  
(KB2658676)  
(критический)
</td>
</tr>
</table>
 
**Примечание для MS12-027**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Программное обеспечение и средства разработки Microsoft

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Visual FoxPro
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-027**](http://go.microsoft.com/fwlink/?linkid=246275)
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
Microsoft Visual FoxPro 8.0 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 8.0 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=3a7ff474-f1e0-4c86-9555-64e8e7357890)  
(KB2647488)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 9.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=53c0132e-7724-4e94-abe9-e79b76ce35d7)  
(KB2647490)  
(критический)
</td>
</tr>
<tr>
<th colspan="2">
Visual Basic
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-027**](http://go.microsoft.com/fwlink/?linkid=246275)
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
Среда выполнения Visual Basic 6.0
</td>
<td style="border:1px solid black;">
[Среда выполнения Visual Basic 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=0afe933a-1e62-45c4-910c-ea94b203df5a)  
(KB2641426)  
(критический)
</td>
</tr>
</table>
 
**Примечание для MS12-027**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Программа Microsoft Remote Access

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Forefront Unified Access Gateway
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-026**](http://go.microsoft.com/fwlink/?linkid=238519)
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
Microsoft Forefront Unified Access Gateway
</td>
<td style="border:1px solid black;">
[Microsoft Forefront Unified Access Gateway 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d4b4ecc4-8bc6-43d0-b872-93673e0d9a6f)<sup>[1]</sup>
(KB2649261)  
(существенный)  
[Microsoft Forefront Unified Access Gateway 2010 с обновлением 1 пакета обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=e0f9acab-bfb8-4758-b60d-64e68a84fba0)<sup>[1]</sup>
(KB2649262)  
(существенный)
</td>
</tr>
</table>
 
**Примечания** **к бюллетеню** **MS12-026**

<sup>[1]</sup>Это обновление можно загрузить только с веб-сайта Центра загрузки Майкрософт.

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

Набор средств для обеспечения совместимости приложений содержит необходимые средства и документацию для выявления проблем совместимости приложений и уменьшения степени воздействия этих проблем перед развертыванием системы Windows Vista, обновлений из Центра обновления Windows, обновлений с веб-сайта безопасности Майкрософт или новой версии проводника.

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

#### Обновления, не относящиеся к безопасности и распространяемые через Центр обновления Майкрософт, Центр обновления Windows и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-сайте Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт](http://support.microsoft.com/kb/894199). Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
-   [Обновления за предыдущие месяцы для служб Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Отображаются все новые, обновленные и повторно выпущенные обновления для продуктов Майкрософт отличных от Microsoft Windows.

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

-   linx2008 из компании [AISec](http://www.aisec.cn/) за сообщение об уязвимости, описанной в MS12-023
-   Роэла Спилкера (Roel Spilker) из компании [TOPdesk](http://www.topdesk.com) за сообщение об уязвимости, описанной в MS12-023
-   Хосе Антонио Васкеса Гонзалеса (Jose Antonio Vazquez Gonzalez) из компании [VeriSign iDefense Labs](http://labs.idefense.com) за сообщение об уязвимости, описанной в MS12-023
-   Анонимного исследователя, сотрудничающего с компанией [TippingPoint](http://www.tippingpoint.com) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS12-023
-   Анонимного исследователя, сотрудничающего с компанией [TippingPoint](http://www.tippingpoint.com) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS12-023
-   Масато Кинугаву (Masato Kinugawa) за совместную работу над изменениями для обеспечения многоуровневой защиты, включенными в бюллетень MS12-023
-   Роберта Зацека (Robert Zacek) и Игоря Глуксмана (Igor Glucksmann) из компании [Avast Software](http://www.avast.com/) за сообщение об уязвимости, описанной в MS12-024
-   Виталия Топорова (Vitaliy Toropov), сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости, описанной в MS12-025
-   Шона Колли (Shaun Colley) из компании [IOActive, Ltd.](http://ioactive.co.uk/) за сообщение об уязвимости, описанной в MS12-028

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617.aspx)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (10 апреля 2012 г.) Обзор бюллетеней опубликован.
-   Вер. 2.0 (26 апреля 2012 г.): В бюллетене MS12-027 в таблицу "Подвержены уязвимостям" добавлены версии продукта SQL Server 2008 R2 с пакетом обновления 1 (SP1), а также добавлена запись, поясняющая, что данное обновление применяется ко всем установленным продуктам Microsoft SQL Server 2000 Analysis Services с пакетом обновления 4 (SP4), поскольку различия между QFE и GDR не относятся к данному продукту. Все изменения носят исключительно информационный характер. Оно не вносит изменения в файлы обновления для системы безопасности или процедуру обнаружения. Поскольку обновление предлагается соответствующим образом начиная с первого выпуска продукта, пользователям, которые уже успешно установили это обновление, не требуется выполнять никаких действий.

*Built at 2014-04-18T01:50:00Z-07:00*
