---
TOCTitle: 'MS13-FEB'
Title: 'Обзор бюллетеней по безопасности Майкрософт за февраль 2013 г.'
ms:assetid: 'ms13-feb'
ms:contentKeyID: 61236170
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms13-feb(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности Майкрософт за февраль 2013 г.
==============================================================

Дата публикации: 12 февраля 2013 г. | Дата обновления: 13 февраля 2013 г.

**Версия:** 1.2

В этом обзоре перечислены бюллетени по безопасности, выпущенные в феврале 2013 г.

После выпуска бюллетеней за февраль 2013 года этот обзор заменит предварительное уведомление, выпущенное 7 февраля 2013 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

13 февраля 2013 г. в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в февральской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538626&culture=en-us). После наступления этой даты данная веб-трансляция будет доступна [по запросу](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538626&culture=en-us).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (2792100)<br />
<br />
</strong>Это обновление для системы безопасности устраняет 13 обнаруженных пользователями уязвимостей в браузере Internet Explorer. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь просмотрит особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275837">MS13-010</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в языке VML делает возможным удаленное выполнение кода (2797052)</strong><br />
<br />
Данное обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в реализации языка VML, предложенной корпорацией Майкрософт. Она делает возможным удаленное выполнение кода, если пользователь открывает специально созданную веб-страницу в браузере Internet Explorer. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271307">MS13-011</a></td>
<td style="border:1px solid black;"><strong>Уязвимость при распаковке мультимедийных данных делает возможным удаленное выполнение кода (2780091)<br />
<br />
</strong>Это обновление для системы безопасности устраняет одну опубликованную уязвимость в Microsoft Windows. Эта уязвимость делает возможным удаленное выполнение кода в случае, если пользователь откроет специально созданный медиафайл (например, файл с расширением .mpg) либо документ Microsoft Office (например, файл с расширением .ppt) со встроенным специально созданным медиафайлом, или получит специально созданный потоковый контент. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=279801">MS13-012</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Exchange Server делают возможным удаленное выполнение кода (2809279)<br />
<br />
</strong>Данное обновление для системы безопасности устраняет опубликованные уязвимости в Microsoft Exchange Server. Наиболее серьезна уязвимость при веб-просмотре документов Microsoft Exchange Server, которая делает возможным удаленное выполнение кода в контексте безопасности службы перекодировки на сервере Exchange при предварительном просмотре специально созданных файлов с помощью Outlook Web App (OWA). Служба перекодировки в Exchange, которая используется для веб-просмотра документов, выполняется от имени учетной записи LocalService. У учетной записи LocalService минимальные права на локальном компьютере и анонимные учетные данные в сети.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Серверное программное обеспечение Майкрософт</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=279005">MS13-020</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в OLE-автоматизации делает возможным удаленное выполнение кода (2802968)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в OLE-автоматизации Microsoft Windows. Эта уязвимость делает возможным удаленное выполнение кода при открытии пользователем особым образом созданного файла. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=272434">MS13-013</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в анализе FAST Search</strong> <strong>Server 2010 для SharePoint делают возможным удаленное выполнение кода (2784242)<br />
<br />
</strong>Это обновление для системы безопасности устраняет опубликованные уязвимости в Microsoft FAST Search Server 2010 для SharePoint. Эти уязвимости делают возможным удаленное выполнение кода в контексте безопасности учетной записи пользователя с маркером ограниченного доступа. Сервер FAST Search Server для SharePoint подвержен этим уязвимостям, только если включен расширенный пакет фильтров. По умолчанию расширенный пакет фильтров отключен.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Серверное программное обеспечение Майкрософт</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=276948">MS13-014</a></td>
<td style="border:1px solid black;"><strong>Уязвимость сервера NFS</strong> <strong>делает возможной атаку типа &quot;отказ в обслуживании&quot; (2790978)</strong> <strong><br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным отказ в обслуживании, если злоумышленник пытается выполнить операцию с файлами в общем ресурсе, доступном только для чтения. Воспользовавшись ею, злоумышленник может заставить систему перестать отвечать на запросы и выполнить перезагрузку. Данной уязвимости подвержены только серверы Windows с включенной ролью NFS.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275736">MS13-015</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в .NET Framework делает возможным несанкционированное получение прав (2800277)<br />
<br />
</strong>Данное обновление для системы безопасности устраняет обнаруженную пользователями уязвимость<strong></strong>.NET Framework. Данная уязвимость делает возможным несанкционированное получение прав, если пользователь просматривает специально созданную веб-страницу в веб-браузере, который поддерживает запуск браузерных приложений XAML. Данная уязвимость также может использоваться приложениями Windows .NET для обхода ограничений разграничения доступа к коду (CAS). Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;"><strong>Уязвимости драйвера режима ядра Windows</strong> <strong>делают возможным несанкционированное получение прав (2778344)</strong><br />
Это обновление для системы безопасности устраняет 30 обнаруженных пользователями уязвимостей в Microsoft Windows. Эти уязвимости делают возможным несанкционированное получение прав, если злоумышленник войдет в систему и запустит специально созданное приложение. Чтобы воспользоваться этими уязвимостями, злоумышленник должен обладать действительными учетными данными для входа и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=278914">MS13-017</a></td>
<td style="border:1px solid black;"><strong>Уязвимости ядра Windows делают возможным несанкционированное получение прав (2799494)</strong><br />
Это обновление для системы безопасности устраняет три обнаруженные пользователями уязвимости во всех поддерживаемых выпусках Microsoft Windows. Эти уязвимости делают возможным несанкционированное получение прав, если злоумышленник войдет в систему и запустит специально созданное приложение. Чтобы воспользоваться этими уязвимостями, злоумышленник должен обладать действительными учетными данными для входа и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=278912">MS13-018</a></td>
<td style="border:1px solid black;"><strong>Уязвимость TCP/IP делает возможной атаку типа &quot;отказ в обслуживании&quot; (2790655)<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным отказ в обслуживании, если злоумышленник, не прошедший проверку подлинности, отправляет серверу специально созданный запрос о завершении подключения.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=278896">MS13-019</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в подсистеме исполнения клиент-сервер (CSRSS) Windows делает возможным несанкционированное получение прав (2790113)<br />
</strong>Это обновление для системы безопасности устраняет опубликованную уязвимость в Microsoft Windows. Эта уязвимость делает возможным несанкционированное получение прав, если злоумышленник войдет в систему и запустит специально созданное приложение. Чтобы воспользоваться этой уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное повышение привилегий</td>
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
  
Используйте эту таблицу, чтобы узнать о вероятности появления эксплойтов для выполнения произвольного кода и DoS-атаки в течение 30 дней после выпуска бюллетеня по каждому из обновлений безопасности, которые необходимо установить. Чтобы назначить приоритеты развертывания, ознакомьтесь с приведенными ниже оценками в соответствии с вашей конфигурацией. Дополнительные сведения об уровнях опасности и способах их определения см. в [индексе использования уязвимостей](http://technet.microsoft.com/security/cc998259).
  
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Уязвимость кодировки символов Shift-JIS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0015">CVE-2013-0015</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, связанная с использованием SetCapture после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0018">CVE-2013-0018</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, связанная с использованием COmWindowProxy после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0019">CVE-2013-0019</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, связанная с использованием CMarkup после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0020">CVE-2013-0020</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, связанная с использованием vtable после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0021">CVE-2013-0021</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, связанная с использованием LsGetTrailInfo после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0022">CVE-2013-0022</a></td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, связанная с использованием CDispNode после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0023">CVE-2013-0023</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, связанная с использованием pasteHTML после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0024">CVE-2013-0024</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, связанная с использованием SLayoutRun после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0025">CVE-2013-0025</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, связанная с использованием InsertElement после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0026">CVE-2013-0026</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, связанная с использованием CPasteCommand после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0027">CVE-2013-0027</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, связанная с использованием CObjectElement после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0028">CVE-2013-0028</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, связанная с использованием CHTML после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0029">CVE-2013-0029</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275837">MS13-010</a></td>
<td style="border:1px solid black;">Уязвимость VML, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0030">CVE-2013-0030</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Корпорации Майкрософт известно о фактах использования данной уязвимости в ограниченном числе целевых атак, направленных на раскрытие информации.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271307">MS13-011</a></td>
<td style="border:1px solid black;">Уязвимость при распаковке мультимедийных данных</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0077">CVE-2013-0077</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=279801">MS13-012</a></td>
<td style="border:1px solid black;">Oracle Outside In содержит несколько уязвимостей, представляющих опасность</td>
<td style="border:1px solid black;">Множественные*</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">*Несколько уязвимостей, подробную информацию см. в бюллетене MS13-012.<br />
<br />
О существовании этих уязвимостей было объявлено.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=272434">MS13-013</a></td>
<td style="border:1px solid black;">Oracle Outside In содержит несколько уязвимостей, представляющих опасность</td>
<td style="border:1px solid black;">Множественные*</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">*Несколько уязвимостей, подробную информацию см. в бюллетене MS13-013.<br />
<br />
О существовании этих уязвимостей было объявлено.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=276948">MS13-014</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с разыменованием NULL</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1281">CVE-2013-1281</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275736">MS13-015</a></td>
<td style="border:1px solid black;">Уязвимость WinForms, приводящая к несанкционированному получению прав при обратном вызове</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0073">CVE-2013-0073</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1248">CVE-2013-1248</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Мера обеспечения многоуровневой защиты последних версий программного обеспечения.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1249">CVE-2013-1249</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Мера обеспечения многоуровневой защиты последних версий программного обеспечения.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1250">CVE-2013-1250</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1251">CVE-2013-1251</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1252">CVE-2013-1252</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1253">CVE-2013-1253</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1254">CVE-2013-1254</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1255">CVE-2013-1255</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1256">CVE-2013-1256</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1257">CVE-2013-1257</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1258">CVE-2013-1258</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1259">CVE-2013-1259</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1260">CVE-2013-1260</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1261">CVE-2013-1261</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1262">CVE-2013-1262</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1263">CVE-2013-1263</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1264">CVE-2013-1264</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1265">CVE-2013-1265</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1266">CVE-2013-1266</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1267">CVE-2013-1267</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1268">CVE-2013-1268</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1269">CVE-2013-1269</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1270">CVE-2013-1270</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1271">CVE-2013-1271</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1272">CVE-2013-1272</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1273">CVE-2013-1273</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1274">CVE-2013-1274</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1275">CVE-2013-1275</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1276">CVE-2013-1276</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1277">CVE-2013-1277</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=278914">MS13-017</a></td>
<td style="border:1px solid black;">Уязвимость в ядре Windows, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1278">CVE-2013-1278</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=278914">MS13-017</a></td>
<td style="border:1px solid black;">Уязвимость в ядре Windows, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1279">CVE-2013-1279</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=278914">MS13-017</a></td>
<td style="border:1px solid black;">Уязвимость в ядре Windows, связанная со счетчиком ссылок</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1280">CVE-2013-1280</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=278912">MS13-018</a></td>
<td style="border:1px solid black;">Уязвимость TCP FIN WAIT</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0075">CVE-2013-0075</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=278896">MS13-019</a></td>
<td style="border:1px solid black;">Уязвимость, связанная со счетчиком ссылок</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0076">CVE-2013-0076</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=279005">MS13-020</a></td>
<td style="border:1px solid black;">Уязвимость OLE-автоматизации, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1313">CVE-2013-1313</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
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
<th colspan="11">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий** **уровень опасности**
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
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
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
<td style="border:1px solid black;">
Нет
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=9bf087e7-4487-48bf-84e9-04b816411a0f)  
(KB2792100)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4501ef62-7d06-49b7-af86-c84e399e6275)  
(KB2792100)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2ab64eac-8ecf-4178-9a01-5f10fc2f049e)  
(KB2792100)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=daed0c2e-bd9a-4685-a5f9-1c01f7fdeccf)  
(KB2797052)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=fd693211-bcc8-4267-9aa1-86bac45e25bf)  
(KB2797052)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e8924d23-f6e2-41bf-9542-f8991d084db9)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=95f5acea-32a0-42a5-a14d-837edf313984)  
(KB2780091)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=3a8ddbab-5999-48b7-9de8-423954f345b6)  
(KB2802968)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=cdaa7282-c354-4d70-938a-a025631205a2)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=9100bf70-8723-4635-9b78-f7c3048a950f)  
(KB2799494)  
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
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=c42347dd-5ec8-4760-a685-2cd7b6bb7bb2)  
(KB2792100)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6513176c-e9cb-4863-a228-5bc369135996)  
(KB2792100)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=25e15457-ffd2-4466-aff9-1d0830e967d7)  
(KB2792100)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=dd9383b9-a6df-44a7-bea9-8f7d088bc488)  
(KB2797052)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b042e717-bf4e-44a1-a1ba-6359bf551e8e)  
(KB2797052)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c8618c96-25c0-415b-b147-5713ec5ab5b1)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=06ef35a1-f76f-4e99-a8b2-6b086c7e51be)  
(KB2780091)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=f72228df-8379-4bd9-b446-cb9505e9d228)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=9a945336-b037-4ee6-9ea2-dfb885747b97)  
(KB2799494)  
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
<th colspan="11">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
Нет
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
<td style="border:1px solid black;">
Нет
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=35b58c7a-aae3-4445-957a-42ee708d77a5)  
(KB2792100)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3ee73b80-b8f6-4843-afba-41c7b55faf17)  
(KB2792100)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d67754e2-7ebd-484d-a008-ed8719e0c72d)  
(KB2792100)  
(средний)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=9b96ebfc-93e9-41bb-81f9-35c433ca5479)  
(KB2797052)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b902617d-1f35-4b17-9a44-235c0d3c27d2)  
(KB2797052)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=47ca5d22-b957-4ac9-91e9-c440b0614728)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=e3b0b928-0f76-4b51-871a-aeda2ee3b7d5)  
(KB2780091)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8daebdb5-eba2-4685-b781-ead5c2185548)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c005c0a0-4025-4a07-a76d-c57ed5afbd68)  
(KB2799494)  
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
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=075de724-b996-413f-8ff3-74f435d94b9b)  
(KB2792100)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a90d6861-7ff6-4501-9200-f72b5a9f1817)  
(KB2792100)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=319a7a93-c03e-4c0b-a5c4-6a4f379d781e)  
(KB2792100)  
(средний)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b3ca28b1-9d3c-4df5-b8d7-f31d70f6e714)  
(KB2797052)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e13c9366-9cb6-4e62-bf6c-a09fe7842463)  
(KB2797052)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=80aab9c7-4511-4d44-b570-c77cdb50e542)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=493377a4-4ce2-4dd9-ba84-090466248669)  
(KB2780091)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e7d03ef2-517b-4442-a968-5aaa300dd2ba)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=dc004424-61f9-49ed-9cb3-b89ed9e98aef)  
(KB2799494)  
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
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=92ce1fa1-4b12-4fd5-9a02-21fc9b119fb9)  
(KB2792100)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5965ce09-c5d7-4072-bad3-df46f9b76478)  
(KB2792100)  
(средний)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=63791740-00e2-4569-967e-36086efe6ca6)  
(KB2797052)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d1a9b2b2-191c-4ffe-9c8a-8ef641a45eb7)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=8e9a09fd-f360-4471-ac89-481dc2935cec)  
(KB2780091)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2a3039a4-9b46-4db8-a539-07d52bbf1b92)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3cad66f1-6651-4948-9579-9df050fdaa1b)  
(KB2799494)  
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
<th colspan="11">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
Нет
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
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=eea43429-2691-4a31-a640-d74035145d2d)  
(KB2792100)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5c195229-8e63-4fff-a304-13c13b2fa132)  
(KB2792100)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7f7ce868-28ce-497e-882f-3abfdd9b89e8)  
(KB2792100)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4f946407-cd81-48b5-a279-1ab81388b70b)  
(KB2797052)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e0cfc24f-293c-4817-a69c-f9cfd514e1c1)  
(KB2797052)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=4fab0417-5c9a-4e5d-864d-b1b3bee6fc89)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=d730eacf-e30a-45aa-89da-dfec5e87906a)  
(KB2780091)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477)  
(KB2789646)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0ff0475c-cc1b-4886-971e-1a71e6b311c3)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4de1249f-012e-47cb-ad08-4fd5bddb0879)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=80b766e7-3b7f-4d04-9a80-71864a13df8c)  
(KB2790655)  
(средний)
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=308d99ff-7575-4d70-958f-0d57fd6bffab)  
(KB2792100)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d9d4987e-95ad-4246-a52b-7ac859a40e67)  
(KB2792100)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=74b370c0-29f5-4acb-a3cd-bd2c2b708bb7)  
(KB2792100)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6ffb3215-1c90-4eb2-9143-0866efc98374)  
(KB2797052)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=649dbf4e-654b-48a2-bd35-2df7f34fbb56)  
(KB2797052)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=44fbe00c-eeb4-4a80-a934-7ce58c02d6ec)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=4cd6b10c-b310-4aee-bbca-f23049c14455)  
(KB2780091)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477)  
(KB2789646)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e5043a08-a9e4-422b-8455-80a5091d38b9)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=448ac43a-0a6f-4049-be2b-c853b5dbfab3)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=92bad797-5b66-422c-a096-8070d02bb8b2)  
(KB2790655)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="11">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
</td>
</tr>
<tr>
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
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
Нет
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
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=71c805ed-a68b-4d3e-97ca-922557cfbf67)  
(KB2792100)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=775ea105-4a71-4b7b-9dc0-50f1eecab96d)  
(KB2792100)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=ccdf8abc-9657-4aff-8d73-4824a558c168)  
(KB2792100)  
(средний)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d432acb3-10a0-4f4c-a793-381aedd4bdd1)  
(KB2797052)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b91ce04a-a464-4388-9386-54dd2815b8dd)  
(KB2797052)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=58f0810c-f253-4740-ac9f-75b8a4506b06)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=86cc3b51-818a-49a6-abab-488ac316e021)  
(KB2780091)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477)  
(KB2789646)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=850e319f-dd6e-4480-86c3-a5129f084817)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6d7a74c8-de4b-4bcb-8b3f-581858d0776b)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c24aa6f3-82a5-4b1f-adc8-4aece948161c)  
(KB2790655)  
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=de1b96b7-a5ac-4a39-9808-c00c6b1a4325)  
(KB2792100)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e5775802-e529-4894-b1cf-2839948706c2)  
(KB2792100)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=51df1e78-f014-4492-8a3d-83b3c821458b)  
(KB2792100)  
(средний)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=152f90b3-efae-42e6-a845-59052383a8a0)  
(KB2797052)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=304ac41e-b4e5-4bf8-94d2-f2bd9a07bcff)  
(KB2797052)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7b85336a-d3f7-4077-b6eb-55b3042f5335)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=fe239f9b-d986-4828-a01d-8abd494037ec)  
(KB2780091)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477)  
(KB2789646)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=8978769b-447b-4b01-848a-cbcdf692f17a)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=c9fbb7cc-c33b-4af9-8416-9d16015e79c1)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=2738fbe4-2163-4e77-82e6-208a7a08a70c)  
(KB2790655)  
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=61c1964f-9307-4128-9470-bcb20e07856b)  
(KB2792100)  
(средний)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1a2af9dc-e9a7-477e-9943-8132eb7fea81)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=4b3e48e3-0dbe-449b-9bca-0ba8bbdcbab0)  
(KB2780091)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477)  
(KB2789646)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0f84e24c-43f4-4851-932c-8849171b2505)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=f3e18038-b8a1-4eba-9542-8396903a3709)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c269c175-f47c-456a-9360-f38bbdfd7ed0)  
(KB2790655)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="11">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
Нет
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
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)****
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)****
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)****
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4df9414b-02da-4254-ab29-5091151e2900)  
(KB2792100)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b21bd7b3-2eb8-433a-b6c2-8243c5128038)  
(KB2792100)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d7d64177-deec-4fd3-9716-b7816fe3c623)  
(KB2797052)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=04a101c6-d553-426f-b3cd-412eefeec580)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9)  
(KB2789644)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=631adede-ba0f-461f-85e1-82b60a7efec1)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=912ac2e1-e737-43fb-acc8-a01a918a8475)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=cb4270c4-cec5-49e0-a56b-97539d6352a0)  
(KB2790655)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=d4d02ef9-b0a4-46a3-ad92-7508aa26ad3b)  
(KB2790113)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4df9414b-02da-4254-ab29-5091151e2900)  
(KB2792100)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b21bd7b3-2eb8-433a-b6c2-8243c5128038)  
(KB2792100)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d7d64177-deec-4fd3-9716-b7816fe3c623)  
(KB2797052)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=04a101c6-d553-426f-b3cd-412eefeec580)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062)  
(KB2789645)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=631adede-ba0f-461f-85e1-82b60a7efec1)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=912ac2e1-e737-43fb-acc8-a01a918a8475)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=cb4270c4-cec5-49e0-a56b-97539d6352a0)  
(KB2790655)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d4d02ef9-b0a4-46a3-ad92-7508aa26ad3b)  
(KB2790113)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=6ef9cbf9-d131-420d-b566-6b0f94f2e1c1)  
(KB2792100)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=4b2402ff-035a-47c4-b982-00d428eab379)  
(KB2792100)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d503795a-b1a3-48dc-b1e6-27628aeb150a)  
(KB2797052)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=36eb59be-6703-40c0-b01c-0fffb1456719)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9)  
(KB2789644)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=8dab3aca-fde1-4bd9-b82a-e4805a2e8d39)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=0d1601cc-fb76-4276-bf0b-a46b7f8055ae)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=5d93cb19-7854-4b49-9743-8d6a11be2dd6)  
(KB2790655)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=77277398-c5b4-4ba4-8425-465710b0bef2)  
(KB2790113)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=6ef9cbf9-d131-420d-b566-6b0f94f2e1c1)  
(KB2792100)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=4b2402ff-035a-47c4-b982-00d428eab379)  
(KB2792100)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d503795a-b1a3-48dc-b1e6-27628aeb150a)  
(KB2797052)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=36eb59be-6703-40c0-b01c-0fffb1456719)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062)  
(KB2789645)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=8dab3aca-fde1-4bd9-b82a-e4805a2e8d39)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=0d1601cc-fb76-4276-bf0b-a46b7f8055ae)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5d93cb19-7854-4b49-9743-8d6a11be2dd6)  
(KB2790655)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=77277398-c5b4-4ba4-8425-465710b0bef2)  
(KB2790113)  
(существенный)
</td>
</tr>
<tr>
<th colspan="11">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
Нет
</td>
<td style="border:1px solid black;">
Нет
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
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e7b455a3-6a44-430c-a7d1-30c03ef7f141)  
(KB2792100)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7e9d97f2-c006-4e5a-bc80-10450069b8c5)  
(KB2792100)  
(средний)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7a36109b-f1e2-4cde-9ede-9f7449c5412c)  
(KB2797052)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=be2fd20a-4c37-47a6-a322-e16acd99db2c)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=aadb2003-ed7b-46ee-afd0-33cec4ac39b4)  
(KB2790978)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9)  
(KB2789644)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=ca5a8735-1568-454d-8b4c-b83107eac036)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=201e6d1f-425b-406e-84a1-37cee035dddb)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=01284b28-043a-4e27-b363-c1e641164a01)  
(KB2790655)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=97241fdb-991d-4411-8fe1-ea56172360ab)  
(KB2790113)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e7b455a3-6a44-430c-a7d1-30c03ef7f141)  
(KB2792100)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7e9d97f2-c006-4e5a-bc80-10450069b8c5)  
(KB2792100)  
(средний)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7a36109b-f1e2-4cde-9ede-9f7449c5412c)  
(KB2797052)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=be2fd20a-4c37-47a6-a322-e16acd99db2c)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=aadb2003-ed7b-46ee-afd0-33cec4ac39b4)  
(KB2790978)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062)  
(KB2789645)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=ca5a8735-1568-454d-8b4c-b83107eac036)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=201e6d1f-425b-406e-84a1-37cee035dddb)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=01284b28-043a-4e27-b363-c1e641164a01)  
(KB2790655)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=97241fdb-991d-4411-8fe1-ea56172360ab)  
(KB2790113)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c1eb941e-833d-46f0-bf65-d9701d67bc20)  
(KB2792100)  
(средний)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c2e1c1b3-5b75-47cf-91d5-82d413b358e6)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=8e37196c-2f43-457d-8d87-336d8775c0bf)  
(KB2790978)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9)  
(KB2789644)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=99320f36-1481-446c-bc3e-d33fcfd1f2c1)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=9f0b132a-8616-49cd-8927-393f35d0cf21)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=e1be5dea-dd13-42b5-a37f-4bcd828cc65f)  
(KB2790655)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=9fbc37dd-53ec-4de1-b1c1-9761a8f83ab8)  
(KB2790113)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c1eb941e-833d-46f0-bf65-d9701d67bc20)  
(KB2792100)  
(средний)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c2e1c1b3-5b75-47cf-91d5-82d413b358e6)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=8e37196c-2f43-457d-8d87-336d8775c0bf)  
(KB2790978)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062)  
(KB2789645)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(KB2789642)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=99320f36-1481-446c-bc3e-d33fcfd1f2c1)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=9f0b132a-8616-49cd-8927-393f35d0cf21)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=e1be5dea-dd13-42b5-a37f-4bcd828cc65f)  
(KB2790655)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=9fbc37dd-53ec-4de1-b1c1-9761a8f83ab8)  
(KB2790113)  
(существенный)
</td>
</tr>
<tr>
<th colspan="11">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
Нет
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
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=7966de38-c6a6-4137-8b7e-8ccd3306521a)  
(KB2792100)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=0389b515-59bf-4733-aab4-ffb822efdbea)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=639674a0-12a3-4185-9858-b2a31ed2f014)  
(KB2789650)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=27d83684-d4f7-4fe0-a54d-25a3d2009be0)  
(KB2789649)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 8 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=d5395864-1822-4151-a10c-f6a036f8853f)  
(KB2778344)  
(Уровень серьезности отсутствует <sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows 8 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=5b74e5b3-7b8d-4669-b403-c776e70bf072)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 8 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=e7739ba6-9c62-4180-a095-47fdb6c741e9)  
(KB2790655)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=d6720d21-269b-4605-b95e-573bc327afd9)  
(KB2792100)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=c1859853-d43f-4497-b212-e6a4daa43485)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=639674a0-12a3-4185-9858-b2a31ed2f014)  
(KB2789650)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=27d83684-d4f7-4fe0-a54d-25a3d2009be0)  
(KB2789649)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 8 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=79aaaa3a-747a-4320-9fd2-5f4a6de3d13c)  
(KB2778344)  
(Уровень серьезности отсутствует <sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows 8 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=a41a2b38-5e5c-48bc-8727-e19402519f12)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 8 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=dd2042b8-c784-4dfc-8fca-61905693cda5)  
(KB2790655)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="11">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
Нет
</td>
<td style="border:1px solid black;">
Нет
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
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=8e3fdcd0-ab75-4500-aac7-7ecb4f39fca7)  
(KB2792100)  
(средний)
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=3b39813e-5ee2-412e-b1f1-a16617a70f43)  
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=b284296a-1db5-47dc-af2c-bf55d0ad09e6)  
(KB2790978)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=639674a0-12a3-4185-9858-b2a31ed2f014)  
(KB2789650)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=27d83684-d4f7-4fe0-a54d-25a3d2009be0)  
(KB2789649)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=aac38d33-fad6-4060-bad4-61cf7c059af9)  
(KB2778344)  
(Уровень серьезности отсутствует <sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=4e427f56-436e-43d0-b4f8-eee8427b3741)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=f74a104d-4749-4dd5-b144-2e4ce9c284a2)  
(KB2790655)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="11">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
Нет
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
Нет
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
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10<sup>[1]</sup>
(KB2792100)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 10<sup>[1]</sup>
(KB2797052)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2778344)  
(Уровень серьезности отсутствует <sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2790655)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="11">
Вариант установки ядра сервера
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-009**](http://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](http://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](http://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](http://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](http://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](http://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](http://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](http://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](http://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](http://go.microsoft.com/fwlink/?linkid=278896)
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
Нет
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
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=850e319f-dd6e-4480-86c3-a5129f084817) (установка основных серверных компонентов)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6d7a74c8-de4b-4bcb-8b3f-581858d0776b) (установка основных серверных компонентов)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c24aa6f3-82a5-4b1f-adc8-4aece948161c) (установка основных серверных компонентов)  
(KB2790655)  
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
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8978769b-447b-4b01-848a-cbcdf692f17a) (установка основных серверных компонентов)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c9fbb7cc-c33b-4af9-8416-9d16015e79c1) (установка основных серверных компонентов)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2738fbe4-2163-4e77-82e6-208a7a08a70c) (установка основных серверных компонентов)  
(KB2790655)  
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
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=aadb2003-ed7b-46ee-afd0-33cec4ac39b4) (установка основных серверных компонентов)  
(KB2790978)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9) (установка основных компонентов сервера)  
(KB2789644)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=ca5a8735-1568-454d-8b4c-b83107eac036) (установка основных серверных компонентов)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=201e6d1f-425b-406e-84a1-37cee035dddb) (установка основных серверных компонентов)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=01284b28-043a-4e27-b363-c1e641164a01) (установка основных серверных компонентов)  
(KB2790655)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=97241fdb-991d-4411-8fe1-ea56172360ab) (установка основных серверных компонентов)  
(KB2790113)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=aadb2003-ed7b-46ee-afd0-33cec4ac39b4) (установка основных серверных компонентов)  
(KB2790978)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062) (установка основных компонентов сервера)  
(KB2789645)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>
(Установка ядра сервера) (KB2789642)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139) (установка основных серверных компонентов)  
(KB2789648)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=ca5a8735-1568-454d-8b4c-b83107eac036) (установка основных серверных компонентов)  
(KB2778344)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=201e6d1f-425b-406e-84a1-37cee035dddb) (установка основных серверных компонентов)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=01284b28-043a-4e27-b363-c1e641164a01) (установка основных серверных компонентов)  
(KB2790655)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=97241fdb-991d-4411-8fe1-ea56172360ab) (установка основных серверных компонентов)  
(KB2790113)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=b284296a-1db5-47dc-af2c-bf55d0ad09e6) (установка основных серверных компонентов)  
(KB2790978)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=639674a0-12a3-4185-9858-b2a31ed2f014) (установка основных серверных компонентов)  
(KB2789650)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=27d83684-d4f7-4fe0-a54d-25a3d2009be0) (установка основных серверных компонентов)  
(KB2789649)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=aac38d33-fad6-4060-bad4-61cf7c059af9) (установка основных серверных компонентов)  
(KB2778344)  
(Уровень серьезности отсутствует <sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=4e427f56-436e-43d0-b4f8-eee8427b3741) (установка основных серверных компонентов)  
(KB2799494)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=f74a104d-4749-4dd5-b144-2e4ce9c284a2) (установка основных серверных компонентов)  
(KB2790655)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 
**Примечания** **к бюллетеням MS13-009, MS13-010,** **MS13-017 и MS13-018**

<sup>[1]</sup>Обновления для системы безопасности Windows RT предоставляются через [Центр обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130).

**Примечания к бюллетеню MS13-015**

<sup>[1]</sup>**Уязвимости подвержены NET Framework 4 и клиентский профиль .NET Framework 4** Предлагаются два профиля для распространяемых пакетов .NET Framework версии 4: .NET Framework 4 и клиентский профиль .NET Framework 4. Клиентский профиль .NET Framework 4 является частью .NET Framework 4. Уязвимости, устраняемой данным обновлением, подвержены как платформа .NET Framework 4, так и клиентский профиль .NET Framework 4. Дополнительные сведения см. в статье MSDN [Установка .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

**Примечания к бюллетеню MS13-016**

<sup>[1]</sup> Обновления для системы безопасности Windows RT предоставляются через [Центр обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130).

<sup>[2]</sup>К данному обновлению не применяются уровни серьезности в отношении указанного программного обеспечения. Тем не менее, к качестве дополнительной меры защиты корпорация Microsoft рекомендует пользователям данного программного обеспечения установить это обновление безопасности.

#### Серверное программное обеспечение Майкрософт

 
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-012**](http://go.microsoft.com/fwlink/?linkid=279801)
</td>
<td style="border:1px solid black;">
[**MS13-013**](http://go.microsoft.com/fwlink/?linkid=272434)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=316a1aff-b72d-4d96-8ee5-bd86b0e29e6f)  
(KB2788321)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=498e7612-73b5-4e28-99a4-b3157ac69932)  
(KB2746164)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Microsoft FAST Search Server 2010 для SharePoint
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-012**](http://go.microsoft.com/fwlink/?linkid=279801)
</td>
<td style="border:1px solid black;">
[**MS13-013**](http://go.microsoft.com/fwlink/?linkid=272434)
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
Microsoft FAST Search Server 2010 для SharePoint с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Расширенный пакет фильтров](http://www.microsoft.com/downloads/details.aspx?familyid=0ae86754-69a8-4c82-855c-2ee2b7887fa5)<sup>[1]</sup>
(KB2553234)  
(существенный)
</td>
</tr>
</table>
 
**Примечание к бюллетеню MS13-013**

<sup>[1]</sup>Это обновление можно загрузить только с веб-сайта Центра загрузки Майкрософт.

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
**В центре безопасности**

Управление программным обеспечением и обновлениями для системы безопасности для установки на серверы, настольные и переносные компьютеры организации. Дополнительные сведения см. на веб-сайте [Центра управления обновлениями TechNet](http://go.microsoft.com/fwlink/?linkid=69903). [Центр безопасности TechNet](http://go.microsoft.com/fwlink/?linkid=21171) предоставляет дополнительные сведения о безопасности в продуктах Майкрософт. Также эта информация доступна на веб-сайте [Центра безопасности Майкрософт](http://go.microsoft.com/fwlink/?linkid=85102) в разделе "Обновления для системы безопасности".

Обновления для системы безопасности доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747) и [Центре обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130). Обновления для системы безопасности также доступны на веб-сайте [Центра загрузки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".

Пользователи пакета Microsoft Office для Mac могут следить за установкой последних версий программного обеспечения Майкрософт при помощи приложения Microsoft AutoUpdate для Mac. Дополнительные сведения об использовании приложения Microsoft AutoUpdate для Mac см. в статье [Автоматическая проверка наличия обновлений для программного обеспечения](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

Наконец, обновления для системы безопасности можно загрузить из [каталога Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=96155). Он обеспечивает возможность поиска содержимого (в том числе обновлений для системы безопасности, драйверов и пакетов обновления), которое предоставляется через Центр обновления Windows и Центр обновления Майкрософт. При поиске по номеру бюллетеня по безопасности (например, "MS13-001") можно добавить в корзину все необходимые обновления (в том числе несколько языковых версий одного обновления) и загрузить их в указанную папку. Дополнительные сведения см. на веб-сайте каталога Центра обновления Майкрософт в разделе [вопросов и ответов](http://go.microsoft.com/fwlink/?linkid=97900).

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

Для выпуска бюллетеня, публикуемого каждый второй вторник месяца корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки. Для внеплановых выпусков бюллетеней по безопасности обновленные версии средства удаления вредоносных программ для системы Microsoft Windows недоступны.

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

-   Масато Кинугаву (Masato Kinugawa) за сообщение об уязвимости, описанной в бюллетене MS13-009
-   [Пользователя Omair](http://krash.in/), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о двух уязвимостях, описанных в MS13-009
-   Пользователя SkyLined, сотрудничающего с [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS13-009
-   Артура Геркиса (Arthur Gerkis), сотрудничающего с компанией Exodus Intelligence, за сообщение об уязвимости, описанной в MS13-009
-   Стивена Фьюера (Stephen Fewer) из [Harmony Security](http://www.harmonysecurity.com), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о двух уязвимостях, описанных в MS13-009
-   [Пользователя Aniway.Aniway@gmail.com](mailto:aniway.aniway@gmail.com), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS13-009
-   Группу Tencent PC Manager за сообщение об уязвимости, описанной в MS13-009
-   Артура Геркиса (Arthur Gerkis), сотрудничающего с [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS13-009
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS13-009
-   Скота Белла (Scott Bell) из компании [Security-Assessment.com](http://www.security-assessment.com) за сообщение о двух уязвимостях, описанных в MS13-009
-   Хосе А. Васкеса (Jose A. Vazquez) из Yenteasy Security Research, сотрудничающего с компанией Exodus Intelligence, за сообщение об уязвимости, описанной в MS13-009
-   Хосе А. Васкеса (Jose A. Vazquez) из Yenteasy Security Research, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS13-009
-   Марка Ясона (Mark Yason) из IBM X-Force за сообщение об уязвимости, описанной в MS13-009
-   Олли Уайтхауса (Ollie Whitehouse) из [NCC Group](http://www.nccgroup.com/) за совместную работу над дополнительными изменениями для обеспечения многоуровневой защиты, включенными в бюллетень MS13-009
-   [Отдел безопасности Tencent](http://security.tencent.com/) за сообщение об уязвимости, описанной в MS13-011
-   Джеймса Форшоу (James Forshaw) из [Context Information Security](http://www.contextis.com/) за сообщение об уязвимости, описанной в MS13-015
-   [Мэтью "j00ru" Юрчика (Mateusz "j00ru" Jurczyk)](http://j00ru.vexillium.org/) из [Google Inc](http://www.google.com), и [Отдел безопасности Tencent](http://security.tencent.com/) за сообщение о двух уязвимостях, описанных в MS13-016
-   [Мэтью Юрчика ("j00ru") (Matthew 'j00ru' Jurczyk)](http://j00ru.vexillium.org/) из [Google Inc](http://www.google.com/) за сообщение о 25 уязвимостях, описанных в MS13-016
-   [Гинваэля Колдвинда (Gynvael Coldwind)](http://gynvael.coldwind.pl/) и [Мэтью Юрчика ("j00ru") (Matthew 'j00ru' Jurczyk)](http://j00ru.vexillium.org/) из [Google Inc](http://www.google.com) за сообщение о трех уязвимостях, описанных в MS13-016
-   [Гинваэля Колдвинда (Gynvael Coldwind)](http://gynvael.coldwind.pl/) и [Мэтью Юрчика ("j00ru") (Matthew 'j00ru' Jurczyk)](http://j00ru.vexillium.org/) из [Google Inc](http://www.google.com) за сообщение о двух уязвимостях, описанных в MS13-017
-   Макса ДеЛисо (Max DeLiso) за совместную работу над уязвимостью, описанной в MS13-019
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS13-020

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617.aspx)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (12 февраля 2013 г.): Обзор бюллетеней опубликован.
-   Версия 1.1 (12 февраля 2013 г.): В бюллетене MS13-009 внесены исправления в запись "Оценка возможности использования уязвимостей для последнего выпуска программного обеспечения" в **Индексе использования уязвимостей** для уязвимости CVE-2013-0022.
-   Версия 1.2 (13 февраля 2013 г.): В бюллетене MS13-014 внесены исправления в раздел "Оценка возможности использования уязвимостей для последнего выпуска программного обеспечения" в **Индексе использования уязвимостей** для уязвимости CVE-2013-1281.

*Built at 2014-04-18T01:50:00Z-07:00*
