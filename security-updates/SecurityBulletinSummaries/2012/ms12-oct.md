---
TOCTitle: 'MS12-OCT'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за октябрь 2012 г.'
ms:assetid: 'ms12-oct'
ms:contentKeyID: 61236165
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms12-oct(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за октябрь 2012 г.
================================================================

Дата публикации: 9 октября 2012 г. | Дата обновления: 23 октября 2012 г.

**Версия:** 1.3

В этом обзоре перечислены бюллетени по безопасности, выпущенные в октябре 2012 г.

После выпуска бюллетеней за октябрь 2012 г. этот обзор заменит предварительное уведомление, выпущенное 4 октября 2012 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

10 октября 2012 г. в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в октябрьской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522558&culture=en-us). После наступления этой даты данная веб-трансляция будет доступна [по запросу](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522558&culture=en-us).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел **Прочие сведения**.

### Сведения о бюллетене

#### Аннотации

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=260965">MS12-064</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в приложении Microsoft Word делают возможным удаленное выполнение кода (2742319)</strong><br />
<br />
Это обновление для системы безопасности устраняет две обнаруженных пользователями уязвимости в Microsoft Office. Более серьезная из этих уязвимостей делает возможным удаленное выполнение кода, если пользователь откроет или просмотрит специально созданный RTF-файл. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Серверное программное обеспечение Майкрософт</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263959">MS12-065</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Works делает</strong> <strong>возможным удаленное выполнение кода (KB2754670)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Works. Данная уязвимость делает возможным удаленное выполнение кода, если пользователь откроет в Microsoft Works специально созданный файл Microsoft Word. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=260957">MS12-066</a></td>
<td style="border:1px solid black;"><strong>Уязвимость компонента очистки HTML делает возможным несанкционированное получение прав (2741517)</strong><br />
<br />
Это обновление для системы безопасности устраняет опубликованную уязвимость в Microsoft Office, платформах Microsoft Communications Platforms, программном обеспечении Microsoft Server и Microsoft Office Web Apps. Эта уязвимость делает возможным несанкционированное получение прав, если злоумышленник отправляет пользователю специально созданное содержимое.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Серверное программное обеспечение Майкрософт,<br />
Microsoft Lync</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=259736">MS12-067</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в анализе FAST Search Server 2010 для SharePoint делают возможным удаленное выполнение кода (2742321)</strong><br />
<br />
Это обновление для системы безопасности устраняет опубликованные уязвимости в Microsoft FAST Search Server 2010 для SharePoint. Эти уязвимости делают возможным удаленное выполнение кода в контексте безопасности учетной записи пользователя с маркером ограниченного доступа. Сервер FAST Search Server для SharePoint подвержен этим уязвимостям, только если включен расширенный пакет фильтров. По умолчанию расширенный пакет фильтров отключен.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Серверное программное обеспечение Майкрософт</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257912">MS12-068</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в ядре Windows делает возможным несанкционированное получение прав (2724197)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость во всех поддерживаемых выпусках Microsoft Windows, кроме Windows 8 и Windows Server 2012. Уровень важности этого обновления определен как &quot;существенный&quot; для всех поддерживаемых выпусков Windows XP, Windows Server 2003, Windows Vista, Windows Server 2008, Windows 7 и Windows Server 2008 R2.<br />
<br />
Эти уязвимости делают возможным несанкционированное получение прав, если злоумышленник войдет в систему и запустит специально созданное приложение. Чтобы воспользоваться этой уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263962">MS12-069</a></td>
<td style="border:1px solid black;"><strong>Уязвимость Kerberos делает возможной атаку типа &quot;отказ в обслуживании&quot; (2743555)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным отказ в обслуживании, если удаленный злоумышленник отправляет серверу Kerberos специально созданный запрос сеанса. Стандартные параметры конфигурации брандмауэра позволяют защитить сеть от атак из-за пределов корпоративной среды. Согласно лучшим методикам, на подключенных к Интернету системах рекомендуется держать открытыми лишь минимально необходимое количество портов.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263997">MS12-070</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в SQL Server делает возможным несанкционированное получение прав (2754849)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость Microsoft SQL Server в системах, в которых выполняются службы SQL Server Reporting Services (SSRS). Это уязвимость межузловых сценариев (XSS), которая делает возможным несанкционированное получение прав, позволяя злоумышленнику выполнить произвольные команды на SSRS-сайте в контексте целевого пользователя. Злоумышленник может использовать эту уязвимость, отправив пользователю особым образом созданную ссылку и убедив его перейти по ней. Злоумышленник может также разместить в сети веб-сайт, содержащий веб-страницу, предназначенную для использования данной уязвимости. Кроме того, веб-сайты, подвергшиеся атаке злоумышленников, равно как и веб-сайты, принимающие или размещающие пользовательские материалы или объявления, также могут иметь специальное содержимое, рассчитанное на использование данной уязвимости.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=260965">MS12-064</a></td>
<td style="border:1px solid black;">Уязвимость в Word, связанная с повреждением раздела PAPX</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0182">CVE-2012-0182</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=260965">MS12-064</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием listid RTF-файла после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2528">CVE-2012-2528</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263959">MS12-065</a></td>
<td style="border:1px solid black;">Уязвимость кучи в Works</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2550">CVE-2012-2550</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=260957">MS12-066</a></td>
<td style="border:1px solid black;">Уязвимость способа очистки HTML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2520">CVE-2012-2520</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=259736">MS12-067</a></td>
<td style="border:1px solid black;">Расширенный пакет фильтров для FAST Search Server 2010 для SharePoint содержит несколько уязвимостей, представляющих опасность</td>
<td style="border:1px solid black;">Oracle Outside In содержит несколько уязвимостей, представляющих опасность</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">*Несколько уязвимостей, подробнее см. в бюллетене MS12-067.<br />
<br />
О существовании этих уязвимостей было объявлено.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257912">MS12-068</a></td>
<td style="border:1px solid black;">Уязвимость ядра Windows, связанная с переполнением целочисленного значения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2529">CVE-2012-2529</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263962">MS12-069</a></td>
<td style="border:1px solid black;">Уязвимость Kerberos, связанная с разыменованием NULL</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2551">CVE-2012-2551</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263997">MS12-070</a></td>
<td style="border:1px solid black;">Уязвимость, приводящая к отраженному межсайтовому выполнению сценариев (XSS)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2552">CVE-2012-2552</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
</tbody>
</table>
  
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
<th colspan="3">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://go.microsoft.com/fwlink/?linkid=257912)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://go.microsoft.com/fwlink/?linkid=263962)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=6aa1e4b3-273a-49ff-8086-0d2c16dd14f3)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3c509cc0-63a1-4cc7-b7f9-cc9f0f12b378)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://go.microsoft.com/fwlink/?linkid=257912)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://go.microsoft.com/fwlink/?linkid=263962)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6c7dd00a-a983-477b-88b1-dc16f1b5e42a)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=eaac4dae-62e6-4020-8b4d-a95e7e0e11f1)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=315cc115-1496-471f-8887-f334a1ca8246)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://go.microsoft.com/fwlink/?linkid=257912)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://go.microsoft.com/fwlink/?linkid=263962)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=828ca8a2-777c-4b41-8d97-caed894a37cb)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=731d67dc-e028-42e4-8ef3-454f74835593)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://go.microsoft.com/fwlink/?linkid=257912)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://go.microsoft.com/fwlink/?linkid=263962)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=526f786b-7aef-4a1f-b03d-587baadf3f5b)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=5697076c-541f-42b7-8dc3-e8bd4a25fda8)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6216b875-c7a6-4d62-8062-49996ac7a478)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://go.microsoft.com/fwlink/?linkid=257912)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://go.microsoft.com/fwlink/?linkid=263962)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=593a29c3-c459-4a39-9f25-016a5268fc7d)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=4ffa9c0e-26b1-4309-bfb4-fa5374f28d6c)  
(KB2743555)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=593a29c3-c459-4a39-9f25-016a5268fc7d)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=4ffa9c0e-26b1-4309-bfb4-fa5374f28d6c)  
(KB2743555)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=2d273f99-3460-4e84-9f2d-2a349bfc7ce6)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=d5584b7d-434f-49fc-9c30-ef16c40d475f)  
(KB2743555)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=2d273f99-3460-4e84-9f2d-2a349bfc7ce6)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d5584b7d-434f-49fc-9c30-ef16c40d475f)  
(KB2743555)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://go.microsoft.com/fwlink/?linkid=257912)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://go.microsoft.com/fwlink/?linkid=263962)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=848af16d-c5f7-4a70-b6a9-39f4e7999f1f)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=d7210047-788c-4b33-953d-e3134f52f897)  
(KB2743555)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=848af16d-c5f7-4a70-b6a9-39f4e7999f1f)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d7210047-788c-4b33-953d-e3134f52f897)  
(KB2743555)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=ded1f351-022a-463c-9f5f-84b6081e6173)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=7dc47f1d-8af8-4f31-9f96-3ae226632723)  
(KB2743555)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=ded1f351-022a-463c-9f5f-84b6081e6173)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=7dc47f1d-8af8-4f31-9f96-3ae226632723)  
(KB2743555)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Вариант установки ядра сервера
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-068**](http://go.microsoft.com/fwlink/?linkid=257912)
</td>
<td style="border:1px solid black;">
[**MS12-069**](http://go.microsoft.com/fwlink/?linkid=263962)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=526f786b-7aef-4a1f-b03d-587baadf3f5b) (установка основных серверных компонентов)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5697076c-541f-42b7-8dc3-e8bd4a25fda8) (установка основных серверных компонентов)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем (установка основных серверных компонентов)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=848af16d-c5f7-4a70-b6a9-39f4e7999f1f) (установка основных серверных компонентов)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=d7210047-788c-4b33-953d-e3134f52f897) (установка основных серверных компонентов)  
(KB2743555)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=848af16d-c5f7-4a70-b6a9-39f4e7999f1f) (установка основных серверных компонентов)  
(KB2724197)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d7210047-788c-4b33-953d-e3134f52f897) (установка основных серверных компонентов)  
(KB2743555)  
(существенный)
</td>
</tr>
</table>
 

#### Пакеты приложений и программные продукты Microsoft Office

 
<table style="border:1px solid black;">
<tr>
<th colspan="4">
Наборы приложений и компоненты Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://go.microsoft.com/fwlink/?linkid=260965)
</td>
<td style="border:1px solid black;">
[**MS12-065**](http://go.microsoft.com/fwlink/?linkid=263959)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
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
Нет
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=e49eadec-0fe1-43ce-9c25-a92aad17d940)  
(KB2687483)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
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
[Microsoft Word 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=be58b650-ee4f-405e-ab3c-c28aca48345b)<sup>[1]</sup>
(KB2687315)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=be58b650-ee4f-405e-ab3c-c28aca48345b)<sup>[1]</sup>
(KB2687315)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=27e07115-d569-438c-b95f-203e444d4408)  
(KB2553488)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=30f9efac-3ecd-48a6-adcf-922f4d4d18d4)  
(KB2553488)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="4">
Прочие программы Microsoft Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://go.microsoft.com/fwlink/?linkid=260965)
</td>
<td style="border:1px solid black;">
[**MS12-065**](http://go.microsoft.com/fwlink/?linkid=263959)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Средство просмотра Microsoft Word
</td>
<td style="border:1px solid black;">
[Средство просмотра Microsoft Word](http://www.microsoft.com/downloads/details.aspx?familyid=1e392ff8-92e9-408d-bb14-1e0a6b4b6c9d)  
(KB2687485)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=301446f7-991e-4abd-a06e-4a854f05ac84)  
(KB2687314)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=301446f7-991e-4abd-a06e-4a854f05ac84)  
(KB2687314)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2007 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a0989a9f-3a7a-4343-9dd0-b2d694a0813b)  
(KB2687439)  
(существенный)  
[Microsoft InfoPath 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=29330e1a-6bac-4c54-98ef-b9a831801247)  
(KB2687440)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2007 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=a0989a9f-3a7a-4343-9dd0-b2d694a0813b)  
(KB2687439)  
(существенный)  
[Microsoft InfoPath 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=29330e1a-6bac-4c54-98ef-b9a831801247)  
(KB2687440)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=724b12b9-84bf-4102-912e-56aa9ee0878c)  
(KB2687436)  
(существенный)  
[Microsoft InfoPath 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=b0be62c6-4eae-458e-8cf5-754742393e4c)  
(KB2687417)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=17b36fa3-9964-480a-bff8-b028619c5dfd)  
(KB2687436)  
(существенный)  
[Microsoft InfoPath 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=6e5a7817-345e-4b75-aeca-94f74691c0e0)  
(KB2687417)  
(существенный)
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
[Microsoft Works 9](http://www.microsoft.com/downloads/details.aspx?familyid=7e48cd96-4b91-4f7b-b8a0-2b88131ba51d)  
(KB2754670)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 
**Примечания** **к бюллетеню** **MS12-064**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

<sup>[1]</sup>В дополнение к пакету обновления безопасности KB2687315 для Microsoft Office Word 2007, чтобы защититься от уязвимостей, описанных в данном бюллетене, пользователям необходимо установить обновление безопасности для пакета обеспечения совместимости Microsoft Office (KB2687314).

**Примечания** **к бюллетеню** **MS12-066**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Серверное программное обеспечение Майкрософт

 
<table style="border:1px solid black;">
<tr>
<th colspan="4">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://go.microsoft.com/fwlink/?linkid=260965)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
</td>
<td style="border:1px solid black;">
[**MS12-067**](http://go.microsoft.com/fwlink/?linkid=259736)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 с пакетом обновления 2 (SP2) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2007 с пакетом обновления 2 (SP2) (coreserver) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=a8a818bb-67a3-4558-aac1-aaa33c6f4584)<sup>[1]</sup>
(KB2687405)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 с пакетом обновления 3 (SP3) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2007 с пакетом обновления 3 (SP2) (coreserver) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=a8a818bb-67a3-4558-aac1-aaa33c6f4584)<sup>[1]</sup>
(KB2687405)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 с пакетом обновления 2 (SP2) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2007 с пакетом обновления 2 (SP2) (coreserver) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=93f4e385-880a-4edc-9cde-24f38a11a41d)<sup>[1]</sup>
(KB2687405)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 с пакетом обновления 3 (SP3) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2007 с пакетом обновления 3 (SP2) (coreserver) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=93f4e385-880a-4edc-9cde-24f38a11a41d)<sup>[1]</sup>
(KB2687405)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Word Automation Services](http://www.microsoft.com/downloads/details.aspx?familyid=3582ab6c-930b-4660-afcd-e2423ce56d8f)  
(KB2598237)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 с пакетом обновления 1 (SP1) (wosrv)](http://www.microsoft.com/downloads/details.aspx?familyid=af3ade8e-349f-4eec-a5c3-c5a70071582d)  
(KB2687435)  
(существенный)  
[Microsoft SharePoint Server 2010 с пакетом обновления 1 (SP1) (coreserver)](http://www.microsoft.com/downloads/details.aspx?familyid=5518b70b-cac9-4aff-b049-156d3c08b04b)  
(KB2589280)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="4">
Microsoft FAST Search Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://go.microsoft.com/fwlink/?linkid=260965)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
</td>
<td style="border:1px solid black;">
[**MS12-067**](http://go.microsoft.com/fwlink/?linkid=259736)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft FAST Search Server 2010 для SharePoint
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Расширенный пакет фильтров](http://www.microsoft.com/downloads/details.aspx?familyid=17909d1f-c679-4a20-b39d-b99f9cc7dbc1)  
(KB2553402)  
(существенный)
</td>
</tr>
<tr>
<th colspan="4">
Microsoft Groove Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://go.microsoft.com/fwlink/?linkid=260965)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
</td>
<td style="border:1px solid black;">
[**MS12-067**](http://go.microsoft.com/fwlink/?linkid=259736)
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
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove Server 2010 с пакетом обновлений 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010 с пакетом обновлений 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=80552d2c-98f2-4c99-bfc6-e091fd1d51c4)  
(KB2687402)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="4">
Службы Windows SharePoint Services и Microsoft SharePoint Foundation
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://go.microsoft.com/fwlink/?linkid=260965)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
</td>
<td style="border:1px solid black;">
[**MS12-067**](http://go.microsoft.com/fwlink/?linkid=259736)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Службы Microsoft Windows SharePoint Services 3.0 с пакетом обновления 2 (SP2) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Службы Microsoft Windows SharePoint Services 3.0 с пакетом обновления 2 (SP2) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=e3a31cd4-bba3-4572-ab24-7b1dd0c4c01c)  
(KB2687356)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 с пакетом обновления 3 (SP3) (32-разрядная версия)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 с пакетом обновления 3 (SP3) (32-разрядная версия)](http://www.microsoft.com/downloads/details.aspx?familyid=e3a31cd4-bba3-4572-ab24-7b1dd0c4c01c)  
(KB2687356)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Службы Microsoft Windows SharePoint Services 3.0 с пакетом обновления 2 (SP2) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Службы Microsoft Windows SharePoint Services 3.0 с пакетом обновления 2 (SP2) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=77cab67c-be97-4808-9fb4-4defad563851)  
(KB2687356)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 с пакетом обновления 3 (SP3) (64-разрядная версия)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 с пакетом обновления 3 (SP3) (64-разрядная версия)](http://www.microsoft.com/downloads/details.aspx?familyid=77cab67c-be97-4808-9fb4-4defad563851)  
(KB2687356)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=79724c7c-7cdf-44c9-9e25-577104c5004b)  
(KB2687434)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="4">
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-064**](http://go.microsoft.com/fwlink/?linkid=260965)
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
</td>
<td style="border:1px solid black;">
[**MS12-067**](http://go.microsoft.com/fwlink/?linkid=259736)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=e7a2dd61-36d5-4313-a8dc-15456b275b9c)  
(KB2687401)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=e7a2dd61-36d5-4313-a8dc-15456b275b9c)  
(KB2687401)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 
**Примечания к бюллетеню MS12-064**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

**Примечания** **к бюллетеню MS12-066**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

<sup>[1]</sup>Для поддерживаемых выпусков Microsoft SharePoint Server 2007: чтобы обеспечить защиту от уязвимостей, описанных в данном бюллетене, помимо пакета обновления для Microsoft SharePoint 2007 (KB2687405) необходимо также установить обновление безопасности для служб Microsoft Windows SharePoint Services 3.0 (KB2687356).

#### Платформы и программное обеспечение Microsoft Communications

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Communicator
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
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
Microsoft Communicator 2007 R2
</td>
<td style="border:1px solid black;">
[Microsoft Communicator 2007 R2](http://www.microsoft.com/downloads/details.aspx?familyid=a228c1dd-9e57-48cb-8db4-896d6c499b46)  
(KB2726391)  
(существенный)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Lync
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-066**](http://go.microsoft.com/fwlink/?linkid=260957)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 (32-разрядная версия)
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 (32-разрядная версия)](http://www.microsoft.com/downloads/details.aspx?familyid=6ea3afea-baa2-4b74-9747-8051c544ddf7)  
(KB2726382)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64-разрядная версия)
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 (64-разрядная версия)](http://www.microsoft.com/downloads/details.aspx?familyid=670c20e6-4f26-47b9-b6e0-25f195bf7000)  
(KB2726382)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 Attendee](http://www.microsoft.com/downloads/details.aspx?familyid=7f98cb55-027a-40bf-b539-d8fa38ffcc83)  
(установка на уровне администратора)  
(KB2726388)  
(существенный)  
[Microsoft Lync 2010 Attendee](http://www.microsoft.com/downloads/details.aspx?familyid=32860684-998e-4e55-b719-c44532bc753d)<sup>[1]</sup>
(установка на уровне пользователя)  
(KB2726384)  
(существенный)
</td>
</tr>
</table>
 
**Примечания** **к бюллетеню MS12-066**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

<sup>[1]</sup>Это обновление можно загрузить только с веб-сайта Центра загрузки Майкрософт.

#### Microsoft SQL Server

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
SQL Server 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-070**](http://go.microsoft.com/fwlink/?linkid=263997)
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
Службы отчетов Microsoft SQL Server 2000 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Службы отчетов Microsoft SQL Server 2000 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1c70a2cb-e8a9-439f-b34a-7d1641daf325)  
(KB983814)  
(существенный)
</td>
</tr>
<tr>
<th colspan="2">
SQL Server 2005
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-070**](http://go.microsoft.com/fwlink/?linkid=263997)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2005 Express Edition с дополнительными службами и пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 Express Edition с дополнительными службами и пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=623841cc-06f7-4475-b2c0-531aed9972a3)<sup>[1]</sup>
(GDR)  
(KB2716429)  
(существенный)  
[Microsoft SQL Server 2005 Express Edition с дополнительными службами и пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=16cc7b80-ea4c-4b17-9ac2-250b771a569a)<sup>[1]</sup>
(QFE)  
(KB2716427)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2005 для 32-разрядных систем с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 для 32-разрядных систем с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=623841cc-06f7-4475-b2c0-531aed9972a3)<sup>[1]</sup>
(GDR)  
(KB2716429)  
(существенный)  
[Microsoft SQL Server 2005 для 32-разрядных систем с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=16cc7b80-ea4c-4b17-9ac2-250b771a569a)<sup>[1]</sup>
(QFE)  
(KB2716427)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2005 для 64-разрядных систем с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 для 64-разрядных систем с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=623841cc-06f7-4475-b2c0-531aed9972a3)<sup>[1]</sup>
(GDR)  
(KB2716429)  
(существенный)  
[Microsoft SQL Server 2005 для 64-разрядных систем с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=16cc7b80-ea4c-4b17-9ac2-250b771a569a)<sup>[1]</sup>
(QFE)  
(KB2716427)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2005 для систем на базе процессоров Itanium с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 для систем на базе процессоров Itanium с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=623841cc-06f7-4475-b2c0-531aed9972a3)<sup>[1]</sup>
(GDR)  
(KB2716429)  
(существенный)  
[Microsoft SQL Server 2005 для систем на базе процессоров Itanium с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=16cc7b80-ea4c-4b17-9ac2-250b771a569a)<sup>[1]</sup>
(QFE)  
(KB2716427)  
(существенный)
</td>
</tr>
<tr>
<th colspan="2">
SQL Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-070**](http://go.microsoft.com/fwlink/?linkid=263997)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1bf8dc30-2a90-4196-814c-717ccd74ea13)<sup>[1]</sup>
(GDR)  
(KB2716434)  
(существенный)  
[Microsoft SQL Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7d8b1b25-45ad-4f19-ba50-e77debf2b463)<sup>[1]</sup>
(QFE)  
(KB2716433)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для 32-разрядных систем с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для 32-разрядных систем с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=04621a83-c2e2-4a60-9198-10104372b120)<sup>[1]</sup>
(GDR)  
(KB2716436)  
(существенный)  
[Microsoft SQL Server 2008 для 32-разрядных систем с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=4c4597d2-dea0-49b9-a5a9-a7771a3d64c0)<sup>[1]</sup>
(QFE)  
(KB2716435)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1bf8dc30-2a90-4196-814c-717ccd74ea13)<sup>[1]</sup>
(GDR)  
(KB2716434)  
(существенный)  
[Microsoft SQL Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7d8b1b25-45ad-4f19-ba50-e77debf2b463)<sup>[1]</sup>
(QFE)  
(KB2716433)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для 64-разрядных систем с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для 64-разрядных систем с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=04621a83-c2e2-4a60-9198-10104372b120)<sup>[1]</sup>
(GDR)  
(KB2716436)  
(существенный)  
[Microsoft SQL Server 2008 для 64-разрядных систем с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=4c4597d2-dea0-49b9-a5a9-a7771a3d64c0)<sup>[1]</sup>
(QFE)  
(KB2716435)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для систем на базе процессоров Itanium с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для систем на базе процессоров Itanium с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1bf8dc30-2a90-4196-814c-717ccd74ea13)<sup>[2]</sup>
(GDR)  
(KB2716434)  
(существенный)  
[Microsoft SQL Server 2008 для систем на базе процессоров Itanium с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=7d8b1b25-45ad-4f19-ba50-e77debf2b463)<sup>[2]</sup>
(QFE)  
(KB2716433)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для систем на базе процессоров Itanium с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для систем на базе процессоров Itanium с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=04621a83-c2e2-4a60-9198-10104372b120)<sup>[3]</sup>
(GDR)  
(KB2716436)  
(существенный)  
[Microsoft SQL Server 2008 для систем на базе процессоров Itanium с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=4c4597d2-dea0-49b9-a5a9-a7771a3d64c0)<sup>[3]</sup>
(QFE)  
(KB2716435)  
(существенный)
</td>
</tr>
<tr>
<th colspan="2">
SQL Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-070**](http://go.microsoft.com/fwlink/?linkid=263997)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=215a9184-71c5-41e6-b4d5-03602182a88f)<sup>[1]</sup>
(GDR)  
(KB2716440)  
(существенный)  
[Microsoft SQL Server 2008 R2 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=cdc4fc03-dfba-41d4-b651-d7967a067eea)<sup>[1]</sup>
(QFE)  
(KB2716439)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=215a9184-71c5-41e6-b4d5-03602182a88f)<sup>[1]</sup>
(GDR)  
(KB2716440)  
(существенный)  
[Microsoft SQL Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=cdc4fc03-dfba-41d4-b651-d7967a067eea)<sup>[1]</sup>
(QFE)  
(KB2716439)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для систем на базе процессоров Itanium с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 для систем на базе процессоров Itanium с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=215a9184-71c5-41e6-b4d5-03602182a88f)<sup>[1]</sup>
(GDR)  
(KB2716440)  
(существенный)  
[Microsoft SQL Server 2008 R2 для систем на базе процессоров Itanium с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=cdc4fc03-dfba-41d4-b651-d7967a067eea)<sup>[1]</sup>
(QFE)  
(KB2716439)  
(существенный)
</td>
</tr>
<tr>
<th colspan="2">
SQL Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-070**](http://go.microsoft.com/fwlink/?linkid=263997)
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
Microsoft SQL Server 2012 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2012 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=e79b4e5b-1549-4e76-afef-b771b432365b)<sup>[1]</sup>
(GDR)  
(KB2716442)  
(существенный)  
[Microsoft SQL Server 2012 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=ebfcb341-e240-4107-92f1-ab75cc28151a)<sup>[1]</sup>
(QFE)  
(KB2716441)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2012 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2012 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=e79b4e5b-1549-4e76-afef-b771b432365b)<sup>[1]</sup>
(GDR)  
(KB2716442)  
(существенный)  
[Microsoft SQL Server 2012 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=ebfcb341-e240-4107-92f1-ab75cc28151a)<sup>[1]</sup>
(QFE)  
(KB2716441)  
(существенный)
</td>
</tr>
</table>
 
**Примечания к бюллетеню MS12-070**

<sup>[1]</sup>Это обновление предлагается только пользователям SQL Server Reporting Services (SSRS).

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

#### Средство удаления вредоносных программ для системы Microsoft Windows

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

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

-   Анонимного исследователя, сотрудничающего с [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в бюллетене MS12-064
-   Анонимного исследователя, сотрудничающего в рамках программы [SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) компании Beyond Security, за сообщение об уязвимости, описанной в бюллетене MS12-064
-   Дрю Хинца (Drew Hintz) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости, описанной в бюллетене MS12-066
-   Уилла Дормана (Will Dormann) из компании [CERT/CC](http://www.cert.org/) за совместную работу над устранением 13 уязвимостей, описанных в бюллетене MS12-067
-   Анонимного исследователя, сотрудничающего с [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости, описанной в бюллетене MS12-068

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617.aspx)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (9 октября 2012 г.): Обзор бюллетеней опубликован.
-   Вер. 1.1 (10 октября 2012 г.): Для MS12-068 и MS12-069 исправлена оценка использования уязвимости для последнего выпуска ПО в **Индекс использования уязвимостей** для CVE-2012-2529 и CVE-2012-2551 соответственно. Для MS12-066 исправлены номера KB для Microsoft Lync 2010 Attendee (установка на уровне администратора) и Microsoft Lync 2010 Attendee (установка на уровне пользователя).
-   Вер. 1.2 (17 октября 2012 г.): Для MS12-066 исправлены номера KB для Microsoft Lync 2010 Attendee (установка на уровне администратора) и Microsoft Lync 2010 Attendee (установка на уровне пользователя).
-   Вер. 1.3 (23 октября 2012 г.): В раздел **Продукты, подверженные уязвимости, и соответствующие обновления** бюллетеня MS12-066 добавлены Microsoft Windows SharePoint Services 3.0 с пакетом обновления 3 (SP3) (32-разрядная версия) и Microsoft Windows SharePoint Services 3.0 с пакетом обновления 3 (SP3) (64-разрядная версия). Это изменение носит исключительно информационный характер. Логика обнаружения и файлы обновления безопасности не изменялись.

*Built at 2014-04-18T01:50:00Z-07:00*
