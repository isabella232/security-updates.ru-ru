---
TOCTitle: 'MS13-APR'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за апрель 2013 года'
ms:assetid: 'ms13-apr'
ms:contentKeyID: 61236167
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms13-apr(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за апрель 2013 года
=================================================================

Дата публикации: 9 апреля 2013 г. | Дата обновления: 25 июня 2013 г.

**Версия:** 4.0

В этот обзор включены бюллетени по безопасности, выпущенные в апреле 2013 года.

После выпуска бюллетеней за апрель 2013 года этот обзор заменит предварительное уведомление, выпущенное 4 апреля 2013 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

10 апреля 2013 года в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в апрельской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538640&culture=en-us). После наступления этой даты данная веб-трансляция будет доступна [по запросу](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538640&culture=en-us).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=285215">MS13-028</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (2817183)<br />
<br />
</strong>Это обновление для системы безопасности устраняет две обнаруженные пользователями уязвимости в браузере Internet Explorer. Данные уязвимости делают возможным удаленное выполнение кода при открытии специально созданной веб-страницы в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=286679">MS13-029</a></td>
<td style="border:1px solid black;"><strong>Уязвимость клиента удаленного</strong> <strong>рабочего стола делает возможным удаленное выполнение кода (2828223)</strong> <strong><br />
<br />
</strong>Данное обновление для системы безопасности устраняет обнаруженную пользователями уязвимость клиента удаленного рабочего стола. Она делает возможным удаленное выполнение кода, если пользователь открывает специально созданную веб-страницу. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=286577">MS13-030</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в SharePoint может привести к раскрытию информации (2827663)</strong> <strong><br />
<br />
</strong>Это обновление для системы безопасности устраняет опубликованную уязвимость Microsoft SharePoint Server. Данная уязвимость может привести к раскрытию информации, если злоумышленник определил адрес или местоположение конкретного списка SharePoint и получил доступ к сайту SharePoint, на котором этот список хранится. Чтобы использовать данную уязвимость, злоумышленник должен быть способен удовлетворить запросы проверки подлинности данного сайта SharePoint.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Раскрытие информации</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Серверное программное обеспечение Майкрософт</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=282388">MS13-031</a></td>
<td style="border:1px solid black;"><strong>Уязвимости ядра Windows делают возможным несанкционированное получение прав (2813170)<br />
<br />
</strong>Это обновление для системы безопасности устраняет две обнаруженных пользователями уязвимости в Microsoft Windows. Эти уязвимости делают возможным несанкционированное получение прав, если злоумышленник войдет в систему и запустит специально созданное приложение. Чтобы воспользоваться данными уязвимостями, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=280660">MS13-032</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в службе Active Directory может вызвать отказ в обслуживании (2830914)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Active Directory. Она делает возможной атаку типа &quot;отказ в обслуживании&quot;, если злоумышленник отправил специально созданный запрос службе LDAP (Lightweight Directory Access Protocol).</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=286700">MS13-033</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в подсистеме исполнения клиент-сервер (CSRSS) Windows делает возможным несанкционированное получение прав (2820917)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость во всех поддерживаемых выпусках Windows XP, Windows Vista, Windows Server 2003 и Windows Server 2008. Эта уязвимость делает возможным несанкционированное получение прав, если злоумышленник войдет в систему и запустит специально созданное приложение. Чтобы воспользоваться этой уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=276805">MS13-034</a></td>
<td style="border:1px solid black;"><strong>Уязвимость клиента Microsoft Antimalware делает возможным несанкционированное получение прав (2823482)</strong> <strong><br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость клиента Microsoft Antimalware. Данная уязвимость делает возможным несанкционированное получение прав из-за имен путей, используемых клиентом Microsoft Antimalware. Злоумышленник, успешно воспользовавшийся ею, может выполнить произвольный код и получить полный контроль над системой. После этого злоумышленник сможет устанавливать программы, просматривать, изменять и удалять данные, а также создавать новые учетные записи с неограниченными правами. Чтобы воспользоваться уязвимостью, злоумышленник должен обладать действительными учетными данными. Этой уязвимостью не могут воспользоваться анонимные пользователи.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Программное обеспечение корпорации Майкрософт по безопасности</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=285672">MS13-035</a></td>
<td style="border:1px solid black;"><strong>Уязвимость компонента очистки HTML делает возможным несанкционированное получение прав (2821818)</strong> <strong><br />
<br />
</strong>Это обновление для системы безопасности устраняет уязвимость в пакете Microsoft Office, о которой сообщалось в частном порядке. Эта уязвимость делает возможным несанкционированное получение прав, если злоумышленник отправляет пользователю специально созданное содержимое.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Серверное программное обеспечение Майкрософт</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=281927">MS13-036</a></td>
<td style="border:1px solid black;"><strong>Уязвимости драйвера в режиме ядра делают возможным несанкционированное получение прав (2829996)</strong><br />
<br />
Это обновление для системы безопасности устраняет три обнаруженных пользователями и одну опубликованную уязвимость в Microsoft Windows. Наиболее серьезная из этих уязвимостей делает возможным несанкционированное получение прав, если злоумышленник вошел в уязвимую систему и запустил специально созданное приложение. Чтобы воспользоваться наиболее серьезными из этих уязвимостей, злоумышленник должен обладать действительными учетными данными для входа и возможностью локального входа в систему.</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=285215">MS13-028</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием Internet Explorer после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1303">CVE-2013-1303</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=285215">MS13-028</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием Internet Explorer после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1304">CVE-2013-1304</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=285215">MS13-028</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием Internet Explorer после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1338">CVE-2013-1338</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=286679">MS13-029</a></td>
<td style="border:1px solid black;">Уязвимость элемента ActiveX в RDP, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1296">CVE-2013-1296</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=286577">MS13-030</a></td>
<td style="border:1px solid black;">Связанная с неправильными правами доступа уязвимость, приводящая к раскрытию информации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1290">CVE-2013-1290</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.<br />
<br />
О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=282388">MS13-031</a></td>
<td style="border:1px solid black;">Уязвимость в ядре Windows, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1284">CVE-2013-1284</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=282388">MS13-031</a></td>
<td style="border:1px solid black;">Уязвимость в ядре Windows, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1294">CVE-2013-1294</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=280660">MS13-032</a></td>
<td style="border:1px solid black;">Уязвимость, приводящая к потреблению большого объема памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1282">CVE-2013-1282</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=286700">MS13-033</a></td>
<td style="border:1px solid black;">Уязвимость CSRSS, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1295">CVE-2013-1295</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">В Windows Server 2003 и Windows XP Professional x64 Edition эта уязвимость может приводить к несанкционированному получению прав.<br />
<br />
В Windows XP, Windows Vista и Windows Server 2008 эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=276805">MS13-034</a></td>
<td style="border:1px solid black;">Уязвимость Microsoft Antimalware, связанная с неправильными именами путей</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0078">CVE-2013-0078</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=285672">MS13-035</a></td>
<td style="border:1px solid black;">Уязвимость способа очистки HTML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1289">CVE-2013-1289</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Корпорации Майкрософт известно об ограниченном количестве направленных атак с целью использования этой уязвимости.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=281927">MS13-036</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1283">CVE-2013-1283</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=281927">MS13-036</a></td>
<td style="border:1px solid black;">Уязвимость в Win32k, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1292">CVE-2013-1292</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
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
<th colspan="7">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Низкий**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=f7b699b1-7655-4c8f-bd1a-535ff210b338)  
(2817183)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e9f9848e-b926-4487-9dc2-b2a6b6f5f98e)  
(2817183)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4cf0de09-2e8d-4be0-bbbf-d040164f22e0)  
(2817183)  
(критический)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=353812de-b1eb-4245-82e3-7829cb72bba3)  
(2813345)  
(критический)  
[Клиент подключения к удаленному рабочему столу 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=1754fdde-4744-4783-b6d3-e38eb2874b58)  
(2813347)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=69de7e3c-d99b-432a-b286-f45841edc4a7)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=8adb6ced-6065-454b-ba67-b0acd621df76)  
(2801109)  
(низкий)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=f47a73d3-05f6-4c7d-b063-c83dd0070c2d)  
(2820917)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=75914c2a-37bb-4541-81ed-a602acb27a14)  
(2808735)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=4496bce8-809e-458c-b199-49b32eef7b21)  
(2817183)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=9d792ad9-c2d7-4972-9f27-4580af04571c)  
(2817183)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c3bdbbb8-57a2-4474-9b86-239f7a77e658)  
(2817183)  
(критический)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=f413845a-84e0-48d9-b5bc-56a37109ab33)  
(2813345)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=74855fb1-cad1-463f-a02d-1c27a39667c9)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=9fb780b9-bbca-45ec-98db-da413f0ccddf)  
(2801109)  
(низкий)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c143a028-2c38-469f-a563-be8030ec76e3)  
(2820917)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=20a1f311-5cdc-4675-a228-32993d8be3f9)  
(2808735)  
(существенный)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=8d834fd2-eaa0-4742-a8a2-93277ca41f91)  
(2817183)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b0cbbaaf-be40-4088-b3d3-ca85410807b7)  
(2817183)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=cd2731b3-406e-4b73-bd70-4f2bb16dfb08)  
(2817183)  
(средний)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=75b00750-80c3-4ffa-adbf-5f40a41309b9)  
(2813345)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2c242d48-8dbe-4474-ba39-f7e3ebe9a604)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=c27666a5-67ff-4e2d-b9d7-2cef19da1edd)  
(2772930)  
(существенный)  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=13eb9459-0a39-4652-b577-6d8509801f62)  
(2801109)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=63ffbd1a-79a9-47c8-a904-b6e9a0fb626f)  
(2820917)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0722d681-eda8-48af-b079-36d45eb20f98)  
(2808735)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=7149ecda-78d3-4289-81b2-5133cd9b4564)  
(2817183)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f22de9fa-96e0-4a09-8923-8731e0de38c9)  
(2817183)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=08c55acd-4c5e-4d5e-b524-19fd449e5c50)  
(2817183)  
(средний)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=7efb8816-ca23-4a75-a0cc-53a663eac3a9)  
(2813345)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b7af0c30-0d09-434a-85d6-69e7e9ee9e29)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=1b009894-8503-42b6-85d1-1285ed14bef9)  
(2772930)  
(существенный)  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=30c0c8d8-df70-4637-bea4-96e2e4d2cb28)  
(2801109)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=bf96696e-13a4-4b01-a8d9-60654d7d1ac5)  
(2820917)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=fc5f39a7-e89b-4ef0-887c-873ad546fb65)  
(2808735)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b10b94db-b281-46b6-b301-58f14de327d2)  
(2817183)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=9d799925-5f8e-43c8-8674-19437a7a6c99)  
(2817183)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=54e286a0-22f5-4b34-a246-c98c0647f093)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=0b65be9e-724d-469d-ba3b-93d8b174aecb)  
(2772930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c56d776a-4293-4d3c-bcac-cd5f50eeb328)  
(2820917)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=dd159949-e0f0-4515-876d-837758a3fd51)  
(2808735)  
(существенный)
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Низкий**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5591feef-5bc6-4e3e-9bbb-cd2205757340)  
(2817183)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e244c3f1-3c4e-4648-b1f9-e216b0009f1e)  
(2817183)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=190a78a5-e557-44f3-b214-7d3c904f7bd8)  
(2817183)  
(критический)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=20500712-2c0f-41e2-95a8-db1a5dcf717a)  
(2813345)  
(критический)  
[Клиент подключения к удаленному рабочему столу 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=1bf2935a-2fa4-4a26-bccf-fe0b63a16b37)  
(2813347)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7f1aa4bd-a14e-4797-b542-4220e3d9d0d7)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=e1b1a3b4-7aae-4934-96cc-990cd1ce962d)  
(2772930)  
(низкий)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=10664eeb-f759-4a0e-b1df-c463aae43902)  
(2820917)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3881a7f9-a5f1-4a28-b652-7b7f20c05259)  
(2808735)  
(существенный)  
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=55d753f3-b912-401c-bca6-61c212ffa0df)  
(2840149)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1bcd238f-2758-49f7-a347-7ec998637d5c)  
(2817183)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c35f53d6-eceb-4966-9487-2dfc2652c775)  
(2817183)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=6cfdb0d5-9c47-405f-bc60-0e4dd3eaff12)  
(2817183)  
(критический)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=4c6f006c-fcb8-499f-bd91-9c8acb3ec3c3)  
(2813345)  
(критический)  
[Клиент подключения к удаленному рабочему столу 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=201eb194-e7c9-479c-bb03-646b22f2bbd1)  
(2813347)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d6b3ef0e-16e3-42cb-bffe-4b046f995771)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=ca2182ae-cd47-48d7-9bb0-4aeda4ee26cc)  
(2772930)  
(низкий)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c12ce8b7-e8e2-47ac-bdaa-874dff5a6115)  
(2820917)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e5ba88a4-e0ec-45d7-8c0a-611521351890)  
(2808735)  
(существенный)  
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=89f1556f-442f-4888-b21a-ffbedaa8792e)  
(2840149)  
(средний)
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
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=09bd431a-e94f-4fc5-bea9-569ebc17b0f3)  
(2817183)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=76f96697-0f07-49ad-9169-47cfe2f6a362)  
(2817183)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=2d8c4080-ff7a-42ef-95f4-36b642c0a089)  
(2817183)  
(средний)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=92bd1819-46f9-4a9b-bf2b-ea6aaaee9890)  
(2813345)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=527ea8cd-88db-448a-b8e4-0fdf87fa369c)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory и службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=dd955bf1-e51f-4738-82bf-759e9dea0895)  
(2772930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=31561241-07c8-4396-ad80-9c62a2394658)  
(2820917)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e598863e-7ca1-42a6-9cb4-3f3a10f0ce71)  
(2808735)  
(существенный)  
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a4bdfe68-4de2-41fa-a593-2e07de105081)  
(2840149)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e46e002e-40b2-4bb3-89ad-63d320273ffa)  
(2817183)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b93153dc-f83a-4891-8230-765e3472614d)  
(2817183)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=08abb2ce-0a07-4f25-b9ad-5ec87c07f0bf)  
(2817183)  
(средний)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=6518cdc6-10a6-46ed-a2f6-6f58216fe319)  
(2813345)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=604709f7-8712-4162-ab86-5988b19084f9)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory и службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=38d1cd8c-977b-47be-b703-a326a1b4f445)  
(2772930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=46ef3ace-30b2-4099-aa9d-142de82b0257)  
(2820917)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=a9dd92b5-4137-47d1-85a3-506f1eaacee0)  
(2808735)  
(существенный)  
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=1c36a50c-023d-420d-830a-d4cb2eda6ef2)  
(2840149)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b0d20b3f-f6cb-4cbc-9af1-1d33b4a6dfb2)  
(2817183)  
(средний)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=4807c3fe-bc54-4db6-a9b0-ee21bdd9820f)  
(2813345)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6133c84a-b2ce-4a2e-8afc-7386caf80cc8)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=94971d7b-df42-4566-97eb-0a7572b0e2da)  
(2820917)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3e9ccb95-284a-478e-b521-f3a0acbae8da)  
(2808735)  
(существенный)  
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=738b2263-e1eb-4ada-a7f0-5165f42bc5c9)  
(2840149)  
(средний)
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
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Низкий**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ec9c221a-065b-4f5c-95b6-9b650c24cffa)  
(2817183)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=041fd330-0998-44b5-bedd-d3e47965370d)  
(2817183)  
(критический)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=d7623f17-783d-431a-8274-17d71df72202)  
(2813347)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=90d2c454-c31c-4ac4-ab94-b341d1244ee6)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=37b3e861-35fb-471b-b81a-a8b58bd26647)  
(2772930)  
(низкий)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=1abeaf49-c458-4046-a001-8aee0ba35b3a)  
(2808735)  
(существенный)  
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=808ac8c6-394d-406b-b34e-07d03c760c27)  
(2840149)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ec9c221a-065b-4f5c-95b6-9b650c24cffa)  
(2817183)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=041fd330-0998-44b5-bedd-d3e47965370d)  
(2817183)  
(критический)  
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=cf49622e-8494-4082-a9aa-a6699711d827)  
(2817183)  
(критический)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 7.1](http://www.microsoft.com/downloads/details.aspx?familyid=d7623f17-783d-431a-8274-17d71df72202)  
(2813347)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=90d2c454-c31c-4ac4-ab94-b341d1244ee6)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=37b3e861-35fb-471b-b81a-a8b58bd26647)  
(2772930)  
(низкий)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1abeaf49-c458-4046-a001-8aee0ba35b3a)  
(2808735)  
(существенный)  
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=808ac8c6-394d-406b-b34e-07d03c760c27)  
(2840149)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=01f4b588-38e3-43a7-ae5c-674b9c03fc42)  
(2817183)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=ac93c656-2c9c-4378-9ae3-a60636b8ce6f)  
(2817183)  
(критический)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=5595efaa-3d57-4c9a-8b53-7cfa06093f1e)  
(2813347)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=ebc1ea79-158f-4c81-ab49-3d3fca870363)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=94d19c2a-2457-4fa7-ade6-ad37d0e7f56a)  
(2772930)  
(низкий)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=84275cfd-f5a3-4830-895d-beaf162cdc27)  
(2808735)  
(существенный)  
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=737a0cd0-eee6-4095-b9b1-2822024dd825)  
(2840149)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=01f4b588-38e3-43a7-ae5c-674b9c03fc42)  
(2817183)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=ac93c656-2c9c-4378-9ae3-a60636b8ce6f)  
(2817183)  
(критический)  
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=775536fa-a8a2-4733-a0f0-08e742be1122)  
(2817183)  
(критический)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 7.1](http://www.microsoft.com/downloads/details.aspx?familyid=5595efaa-3d57-4c9a-8b53-7cfa06093f1e)  
(2813347)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=ebc1ea79-158f-4c81-ab49-3d3fca870363)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=94d19c2a-2457-4fa7-ade6-ad37d0e7f56a)  
(2772930)  
(низкий)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=84275cfd-f5a3-4830-895d-beaf162cdc27)  
(2808735)  
(существенный)  
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=737a0cd0-eee6-4095-b9b1-2822024dd825)  
(2840149)  
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
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d8ffa592-6336-494d-bcd0-535ea2821525)  
(2817183)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7f68500e-6699-4341-b129-2dbd5bc508ac)  
(2817183)  
(средний)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=79c870b9-b800-4f59-a5ea-19a5c890af52)  
(2813347)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=dbbd2e3d-1b37-4173-9955-e6fceb7bcd45)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory и службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=78d11246-06b0-4a22-a2b0-c772aa60e726)  
(2772930)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=cbaac7fb-b673-4cf5-8c6f-57bedcb5285d)  
(2808735)  
(существенный)  
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=3e96483f-ec2d-4335-8c50-8686eed06018)  
(2840149)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d8ffa592-6336-494d-bcd0-535ea2821525)  
(2817183)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7f68500e-6699-4341-b129-2dbd5bc508ac)  
(2817183)  
(средний)  
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=752ffe45-b251-4cdf-9848-4d15f75d4452)  
(2817183)  
(средний)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 7.1](http://www.microsoft.com/downloads/details.aspx?familyid=79c870b9-b800-4f59-a5ea-19a5c890af52)  
(2813347)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=dbbd2e3d-1b37-4173-9955-e6fceb7bcd45)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory и службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=78d11246-06b0-4a22-a2b0-c772aa60e726)  
(2772930)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=cbaac7fb-b673-4cf5-8c6f-57bedcb5285d)  
(2808735)  
(существенный)  
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=3e96483f-ec2d-4335-8c50-8686eed06018)  
(2840149)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2dec754b-4d51-4792-bee6-67e94a1a8157)  
(2817183)  
(средний)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=c7047403-8c2a-42de-bea5-d7354847730a)  
(2813347)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=5cfc2f18-4cde-4e21-8604-f694d69da535)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=6c577423-cd17-4317-98a3-5f6e767513c0)  
(2808735)  
(существенный)  
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=3f1abf13-14c3-4a92-b4c1-4caa40e29e7b)  
(2840149)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2dec754b-4d51-4792-bee6-67e94a1a8157)  
(2817183)  
(средний)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 7.1](http://www.microsoft.com/downloads/details.aspx?familyid=c7047403-8c2a-42de-bea5-d7354847730a)  
(2813347)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5cfc2f18-4cde-4e21-8604-f694d69da535)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=6c577423-cd17-4317-98a3-5f6e767513c0)  
(2808735)  
(существенный)  
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=3f1abf13-14c3-4a92-b4c1-4caa40e29e7b)  
(2840149)  
(средний)
</td>
</tr>
<tr>
<th colspan="7">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
**Нет**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Низкий**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=159c43ec-beaf-4ac3-8c3a-06a9716ac9ae)  
(2817183)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 8 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=02d6d10e-3708-4424-8618-88414694c973)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=c7a7ba4d-1fe1-40ed-81f2-6fbb6dde2cf6)  
(2772930)  
(низкий)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 8 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=882f2d67-b8e0-4859-871b-6a7cef27e3e5)  
(2808735)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=3309f621-4087-4688-b991-c2ef54532cb6)  
(2817183)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 8 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=18992e76-70f3-43a2-b47f-199c9728c7ca)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=bafaac33-2bef-4a5e-9451-23ca69c0a132)  
(2772930)  
(низкий)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 8 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=852dac0f-75fe-443f-9b3d-1dbcac166b3d)  
(2808735)  
(существенный)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
**Нет**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=5015e763-6fb8-4737-9305-2e5850ef853d)  
(2817183)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=ef106525-c42b-4b25-83bf-e290e2bcad5a)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=209e3d5f-9333-469e-8b2c-212dc4ec764a)  
(2772930)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=fbf53f06-1ee2-49c4-a5a8-3b1e9823b1b9)  
(2808735)  
(существенный)
</td>
</tr>
<tr>
<th colspan="7">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
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
**Нет**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**
</td>
<td style="border:1px solid black;">
**Нет**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10<sup>[1]</sup>
(2817183)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(2808735)  
(существенный)
</td>
</tr>
<tr>
<th colspan="7">
Вариант установки ядра сервера
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-028**](http://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](http://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](http://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](http://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](http://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](http://go.microsoft.com/fwlink/?linkid=281927)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
**Нет**
</td>
<td style="border:1px solid black;">
**Нет**
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
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=527ea8cd-88db-448a-b8e4-0fdf87fa369c) (установка основных серверных компонентов)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory и службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=dd955bf1-e51f-4738-82bf-759e9dea0895)  
(2772930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=31561241-07c8-4396-ad80-9c62a2394658) (установка основных серверных компонентов)  
(2820917)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e598863e-7ca1-42a6-9cb4-3f3a10f0ce71) (установка основных серверных компонентов)  
(2808735)  
(существенный)  
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a4bdfe68-4de2-41fa-a593-2e07de105081) (установка основных серверных компонентов)  
(2840149)  
(средний)
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
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=604709f7-8712-4162-ab86-5988b19084f9) (установка основных серверных компонентов)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory и службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=38d1cd8c-977b-47be-b703-a326a1b4f445)  
(2772930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=46ef3ace-30b2-4099-aa9d-142de82b0257) (установка основных серверных компонентов)  
(2820917)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a9dd92b5-4137-47d1-85a3-506f1eaacee0) (установка основных серверных компонентов)  
(2808735)  
(существенный)  
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1c36a50c-023d-420d-830a-d4cb2eda6ef2) (установка основных серверных компонентов)  
(2840149)  
(средний)
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
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=dbbd2e3d-1b37-4173-9955-e6fceb7bcd45) (установка основных серверных компонентов)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory и службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=78d11246-06b0-4a22-a2b0-c772aa60e726)  
(2772930)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=cbaac7fb-b673-4cf5-8c6f-57bedcb5285d) (установка основных серверных компонентов)  
(2808735)  
(существенный)  
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=3e96483f-ec2d-4335-8c50-8686eed06018) (установка основных серверных компонентов)  
(2840149)  
(средний)
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
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=dbbd2e3d-1b37-4173-9955-e6fceb7bcd45) (установка основных серверных компонентов)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory и службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=78d11246-06b0-4a22-a2b0-c772aa60e726)  
(2772930)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=cbaac7fb-b673-4cf5-8c6f-57bedcb5285d) (установка основных серверных компонентов)  
(2808735)  
(существенный)  
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=3e96483f-ec2d-4335-8c50-8686eed06018) (установка основных серверных компонентов)  
(2840149)  
(средний)
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
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=ef106525-c42b-4b25-83bf-e290e2bcad5a) (установка основных серверных компонентов)  
(2813170)  
(существенный)
</td>
<td style="border:1px solid black;">
[Службы Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=209e3d5f-9333-469e-8b2c-212dc4ec764a)  
(2772930)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=fbf53f06-1ee2-49c4-a5a8-3b1e9823b1b9) (установка основных серверных компонентов)  
(2808735)  
(существенный)
</td>
</tr>
</table>
 
**Примечание к бюллетеням MS13-028, MS13-031и MS13-036**

<sup>[1]</sup>Обновления для системы безопасности Windows RT предоставляются через [Центр обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130).

#### Пакеты приложений и программные продукты Microsoft Office

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Программное обеспечение Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-035**](http://go.microsoft.com/fwlink/?linkid=285672)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
**Нет**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=63f6a338-a195-4923-908e-8c21713c7373)  
(2687422)  
(Уровень опасности не определен)<sup>[1]</sup>
[Microsoft InfoPath 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=f1cd73d2-411b-4a58-b8c0-04fd58922dae)  
(2760406)  
(Уровень опасности не определен)<sup>[1]</sup>
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=ae2069d0-55b5-4dfe-9131-41888d6bbec3)  
(2687422)  
(Уровень опасности не определен)<sup>[1]</sup>
[Microsoft InfoPath 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=f206071a-4502-432a-9e5b-50bb4e3f1757)  
(2760406)  
(Уровень опасности не определен)<sup>[1]</sup>
</td>
</tr>
</table>
 
**Примечания** **к бюллетеню MS13-035**

<sup>[1]</sup>К данному обновлению не применяются уровни серьезности в отношении указанного программного обеспечения, поскольку известные направления атак с использованием данной уязвимости блокируются.

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

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
[**MS13-030**](http://go.microsoft.com/fwlink/?linkid=286577)
</td>
<td style="border:1px solid black;">
[**MS13-035**](http://go.microsoft.com/fwlink/?linkid=285672)
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
Microsoft SharePoint Server 2010 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 с пакетом обновления 1 (SP1) (wosrv)](http://www.microsoft.com/downloads/details.aspx?familyid=6c7d007f-5c8d-464c-af04-4e7800a2e2a6)<sup>[1]</sup>
(2687421)  
(существенный)  
[Microsoft SharePoint Server 2010 с пакетом обновления 1 (SP1) (coreserver)](http://www.microsoft.com/downloads/details.aspx?familyid=c59c0d25-8d6c-4dda-a06b-e42891a9ddae)<sup>[1]</sup>
(2760408)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2013 (coreserverloc)](http://www.microsoft.com/downloads/details.aspx?familyid=2e5b1e49-0355-4111-a464-224bb2192029)<sup>[1]</sup>
(2737969)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Groove Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-030**](http://go.microsoft.com/fwlink/?linkid=286577)
</td>
<td style="border:1px solid black;">
[**MS13-035**](http://go.microsoft.com/fwlink/?linkid=285672)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
**Нет**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Microsoft Groove Server 2010 с пакетом обновлений 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d63ee461-b823-4eb1-9e6d-82f380627fb5)  
(2687424)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft SharePoint Foundation
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-030**](http://go.microsoft.com/fwlink/?linkid=286577)
</td>
<td style="border:1px solid black;">
[**MS13-035**](http://go.microsoft.com/fwlink/?linkid=285672)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
**Нет**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Microsoft SharePoint Foundation 2010 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=ac805c46-8661-4e99-84da-c395dc05beb0)  
(2810059)  
(существенный)
</td>
</tr>
</table>
 
**Примечание к бюллетеню MS13-030**

<sup>[1]</sup>Перед установкой этого обновления необходимо установить накопительное обновление Project Server 2013 (2768001). Дополнительные сведения об обновлении, включая ссылки для загрузки, см. в [статье 2768001 базы знаний Майкрософт](http://support.microsoft.com/kb/2768001).

**Примечания** **к бюллетеню MS13-035**

<sup>[1]</sup>Для поддерживаемых выпусков Microsoft SharePoint Server 2010: чтобы обеспечить защиту от уязвимостей, описанных в данном бюллетене, помимо пакетов обновления системы безопасности для Microsoft SharePoint 2010 (2687421 и 2760408) необходимо также установить обновление системы безопасности для Microsoft Windows SharePoint Foundation 2010 (2810059).

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Microsoft Office Web Apps

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Программное обеспечение Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-035**](http://go.microsoft.com/fwlink/?linkid=285672)
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
Microsoft Office Web Apps 2010 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1d35b235-305a-45c8-a395-7658792d177e)  
(2760777)  
(существенный)
</td>
</tr>
</table>
 
**Примечание** **к бюллетеню MS13-035**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Программное обеспечение корпорации Майкрософт по безопасности

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Программное обеспечение для защиты от вредоносных программ
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-034**](http://go.microsoft.com/fwlink/?linkid=276805)
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
Защитник Windows для Windows 8 и Windows RT
</td>
<td style="border:1px solid black;">
Защитник Windows для Windows 8 и Windows RT<sup>[1]</sup>
(2781197)  
(существенный)
</td>
</tr>
</table>
 
**Примечание к бюллетеню MS13-034**

<sup>[1]</sup>Это обновление доступно в [Центре обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130).

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

**MS13-028**

-   Ивана Фратрича (Ivan Fratric) и Бена Хокса (Ben Hawkes) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости, связанной с использованием Internet Explorer после освобождения (CVE-2013-1303)
-   Ивана Фратрича (Ivan Fratric) и Бена Хокса (Ben Hawkes) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости, связанной с использованием Internet Explorer после освобождения (CVE-2013-1304)
-   Анонимного исследователя, сотрудничающего с группой [Zero Day Initiative](http://www.zerodayinitiative.com/) компании [HP](http://www.hpenterprisesecurity.com/products) за сообщение об уязвимости, связанной с использованием Internet Explorer после освобождения (CVE-2013-1338)
-   Анонимного исследователя за совместную работу над изменениями для обеспечения многоуровневой защиты, которые включены в данный бюллетень

**MS13-029**

-   c1d2d9acc746ae45eeb477b97fa74688, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/) за сообщение об уязвимости элемента управления ActiveX RDP, делающей возможным удаленное выполнение кода (CVE-2013-1296)

**MS13-031**

-   [Гинваэля Колдвинда (Gynvael Coldwind)](http://gynvael.coldwind.pl/) и [Мэтью Юрчика "j00ru" (Matthew 'j00ru' Jurczyk)](http://j00ru.vexillium.org/) из [Google Inc](http://www.google.com/) за сообщение об уязвимости в ядра, приводящей к состоянию гонки (CVE-2013-1284)
-   [Гинваэля Колдвинда (Gynvael Coldwind)](http://gynvael.coldwind.pl/) и [Мэтью Юрчика "j00ru" (Matthew 'j00ru' Jurczyk)](http://j00ru.vexillium.org/) из [Google Inc.](http://www.google.com/) за сообщение об уязвимости в ядра, приводящей к состоянию гонки (CVE-2013-1294)

**MS13-033**

-   Георгия Георгиевича Валькова (George Georgiev Valkov) за сообщение об уязвимости CSRSS, приводящей к повреждению памяти (CVE-2013-1295)

**MS13-034**

-   Брюса Монро (Bruce Monroe) из корпорации [Intel](http://www.intel.com/) за сообщение об уязвимости Microsoft Antimalware, связанной с неправильными именами путей (CVE-2013-0078)
-   Шайя Сарфати (Shai Sarfaty) за сообщение об уязвимости Microsoft Antimalware, связанной с неправильными именами путей (CVE-2013-0078)
-   Тони Роуботема (Tony Robotham) из компании Centrica за сообщение об уязвимости Microsoft Antimalware, связанной с неправильными именами путей (CVE-2013-0078)

**MS13-035**

-   Дрю Хинца (Drew Hintz) и Эндрю Лайонса (Andrew Lyons) из [отдела обеспечения безопасности Google](http://www.google.com/) за сообщение об уязвимости способа очистки HTML (CVE-2013-1289)

**MS13-036**

-   [Гинваэля Колдвинда (Gynvael Coldwind)](http://gynvael.coldwind.pl/) и [Мэтью Юрчика "j00ru" (Matthew 'j00ru' Jurczyk)](http://j00ru.vexillium.org/) из [Google Inc](http://www.google.com/) за сообщение об уязвимости Win32k, приводящей к состоянию гонки (CVE-2013-1283)
-   Ван Юйя (Wang Yu) из компании [Qihoo 360 Security Center](http://www.360.cn/) за сообщение об уязвимости Win32k, связанной с анализом шрифтов (CVE-2013-1291)
-   [Гинваэля Колдвинда (Gynvael Coldwind)](http://gynvael.coldwind.pl/) и [Мэтью Юрчика "j00ru" (Matthew 'j00ru' Jurczyk)](http://j00ru.vexillium.org/) из [Google Inc](http://www.google.com/) за сообщение об уязвимости Win32k, приводящей к состоянию гонки (CVE-2013-1292)
-   [Гинваэля Колдвинда (Gynvael Coldwind)](http://gynvael.coldwind.pl/) и [Мэтью Юрчика ("j00ru") (Matthew 'j00ru' Jurczyk)](http://j00ru.vexillium.org/) из [Google Inc.](http://www.google.com/) за совместную работу над устранением уязвимости NTFS, связанной с разыменованием пустого указателя (CVE-2013-1293)

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (9 апреля 2013 г.): Обзор бюллетеней опубликован.
-   Вер. 1.1 (10 апреля 2013 г.): для MS13-029, исправлен номер версии клиента подключения к удаленному рабочему столу в Windows 7 с пакетом обновления 1 (SP1) и Windows Server 2008 R2 с пакетом обновления 1 (SP1) с 7.0 на 7.1. Это изменение носит исключительно информационный характер. Файлы обновления остались без изменений.
-   Вер. 2.0 (11 апреля 2013 г.): для MS13-036, удалены ссылки на обновление для системы безопасности 2823324 из-за известной проблемы с установкой. Подробнее см. в бюллетене.
-   Вер. 3.0 (23 апреля 2013 г.): в бюллетене MS13-036 обновление 2823324 заменено обновлением 2840149 для NTFS.sys при установке в поддерживаемых выпусках Windows Vista, Windows Server 2008, Windows 7 и Windows Server 2008 R2. Подробнее см. в бюллетене.
-   Вер. 3.1 (24 апреля 2013 г.): для MS13-028, в **Индекс использования уязвимостей** добавлена оценка использования уязвимости CVE-2013-1338. Это изменение носит исключительно информационный характер.
-   Вер. 4.0 (25 июня 2013 г.): Для MS13-029 выпущена новая версия бюллетеня, чтобы предложить новую версию обновления 2813347 для Клиента подключения к удаленному рабочему столу 7.0 в Windows XP с пакетом обновления 3 (SP3). Подробнее см. в бюллетене.

*Built at 2014-04-18T01:50:00Z-07:00*
