---
TOCTitle: 'MS13-JAN'
Title: 'Обзор бюллетеней по безопасности Майкрософт за январь 2013 г.'
ms:assetid: 'ms13-jan'
ms:contentKeyID: 61236171
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms13-jan(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности Майкрософт за январь 2013 г.
=============================================================

Дата публикации: 8 января 2013 г. | Дата обновления: 12 марта 2013 г.

**Версия:** 4.0

В этот обзор включены бюллетени по безопасности, выпущенные в январе 2013 года.

После выпуска бюллетеней по безопасности за январь 2013 года этот обзор заменит предварительное уведомление, выпущенное 3 января 2013 года и предварительное уведомление о внеплановых бюллетенях, выпущенное 13 января 2013 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях Майкрософт по безопасности](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

9 января 2013 года в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в январской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538623&culture=en-us). После наступления этой даты данная веб-трансляция будет доступна [по запросу](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538623&culture=en-us).

14 января 2013 года в 13:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей о данном внеплановом бюллетене по безопасности. [Зарегистрируйтесь для участия 14 января 2013 года в веб-трансляции, посвященной внеплановым бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032541648&culture=en-us). После наступления этой даты данная веб-трансляция будет доступна [по запросу](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032541648&culture=en-us).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275222">MS13-008</a></td>
<td style="border:1px solid black;"><strong>Обновление для системы безопасности Internet Explorer (2799329)</strong> <strong><br />
<br />
</strong>Это обновление для системы безопасности устраняет одну опубликованную уязвимость в Internet Explorer. Она делает возможным удаленное выполнение кода, если пользователь открывает специально созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=273848">MS13-001</a></td>
<td style="border:1px solid black;"><strong>Уязвимость</strong> <strong>компонентов диспетчера печати Windows делает возможным удаленное выполнение кода</strong> <strong>(2769369)<br />
<br />
</strong>Это обновление для системы безопасности устраняет одну обнаруженную пользователями уязвимость в Microsoft Windows. Указанная уязвимость делает возможным удаленное выполнение кода в том случае, если сервер печати получит специальным образом созданное задание печати. Стандартные параметры конфигурации брандмауэра позволяют защитить сеть от атак из-за пределов корпоративной среды. В системах, напрямую подключенных к Интернет, рекомендуется держать открытыми лишь минимально необходимое количество портов.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=264923">MS13-002</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в MSXML делают возможным удаленное выполнение кода (2756145)</strong><br />
<br />
Настоящее обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в службах MSXML. Эти уязвимости делают возможным удаленное выполнение кода при открытии специально созданной веб-страницы в браузере Internet Explorer. Однако злоумышленник не может заставить пользователей посетить такой веб-сайт. Вместо этого злоумышленник должен будет убедить пользователей посетить веб-сайт, обычно приглашая их перейти по ведущей на него ссылке в сообщении электронной почты или программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Office,<br />
средства разработки Microsoft,<br />
Серверное программное обеспечение Майкрософт</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=261863">MS13-003</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в System Center Operations Manager делают возможным несанкционированное получение прав (2748552)</strong> <strong><br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженные пользователями две уязвимости в Microsoft System Center Operations Manager. Данные уязвимости делают возможным несанкционированное получение прав, если пользователь посетит зараженный веб-сайт, перейдя по специально созданному URL-адресу. Однако злоумышленник не может заставить пользователей посетить такой веб-сайт. Вместо этого злоумышленник должен будет убедить пользователей посетить веб-сайт, обычно приглашая их перейти по соответствующей ссылке, ведущей на этот веб-сайт и размещенной в сообщении электронной почты или программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Перезагрузка не требуется</td>
<td style="border:1px solid black;">Серверное программное обеспечение Майкрософт</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;"><strong>Уязвимости</strong> <strong>в .NET</strong> <strong>Framework делают возможным несанкционированное получение прав</strong> <strong>(2769324)<br />
<br />
</strong>Настоящее обновление для системы безопасности устраняет<strong></strong>четыре обнаруженных пользователями уязвимостей в .NET Framework. Наиболее серьезные из этих уязвимостей делают возможным несанкционированное получение прав в том случае, если пользователь просмотрит специально созданную веб-страницу с помощью веб-браузера, позволяющего запускать браузерные приложения XAML (XBAP). Данные уязвимости также могут использоваться приложениями Windows .NET для обхода ограничений разграничения доступа к коду (CAS). Злоумышленник, успешно воспользовавшийся этими уязвимостями, может получить те же права, которыми обладает вошедший в систему пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=273826">MS13-005</a></td>
<td style="border:1px solid black;"><strong>Уязвимость драйвера режима ядра Windows делает возможным несанкционированное получение прав</strong> <strong>(2778930)<br />
<br />
</strong>Это обновление для системы безопасности устраняет одну обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным несанкционированное повышение прав в том случае, если злоумышленнику удастся запустить специально созданное приложение.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=273872">MS13-006</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft</strong> <strong>Windowsделает возможным обход функций безопасности(2785220)<br />
<br />
</strong>Настоящее обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в реализациях SSL и TLS в ОС Microsoft Windows. Данная уязвимость делает возможным обход функций безопасности в том случае, если злоумышленнику удастся перехватить зашифрованные пакеты подтверждения веб-соединения.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Обход функции безопасности</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268284">MS13-007</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в протоколе OData делает возможной атаку типа &quot;отказ в обслуживании&quot;</strong> <strong>(2769327)<br />
<br />
</strong>Настоящее обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в протоколе OData. Указанная уязвимость делает возможными атаки типа &quot;отказ в обслуживании&quot; в том случае, если злоумышленник, не прошедший проверку подлинности, пошлет специальным образом созданные HTTP-запросы на уязвимый сайт. Стандартные параметры конфигурации брандмауэра позволяют защитить сеть от атак из-за пределов корпоративной среды. Согласно лучшим методикам, на подключенных к Интернету системах рекомендуется держать открытыми лишь минимально необходимое количество портов.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=273848">MS13-001</a></td>
<td style="border:1px solid black;">Уязвимость компонентов диспетчера печати Windows</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0011">CVE-2013-0011</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=264923">MS13-002</a></td>
<td style="border:1px solid black;">Уязвимость служб MSXML, связанная с усечением целочисленных значений</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0006">CVE-2013-0006</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=264923">MS13-002</a></td>
<td style="border:1px solid black;">Уязвимость служб MSXML, связанная с XSLT</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0007">CVE-2013-0007</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=261863">MS13-003</a></td>
<td style="border:1px solid black;">Уязвимость веб-консоли System Center Operations Manager, приводящая к межсайтовому выполнению сценариев (XSS)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0009">CVE-2013-0009</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=261863">MS13-003</a></td>
<td style="border:1px solid black;">Уязвимость веб-консоли System Center Operations Manager, приводящая к межсайтовому выполнению сценариев (XSS)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0010">CVE-2013-0010</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">Уязвимость WinForms, связанная с переполнением буфера</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0002">CVE-2013-0002</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с переполнением буфера протоколов S.DS.P</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0003">CVE-2013-0003</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с повторным конструированием объектов</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0004">CVE-2013-0004</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=273826">MS13-005</a></td>
<td style="border:1px solid black;">Уязвимость Win32k, связанная с неправильной обработкой сообщений</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0008">CVE-2013-0008</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=273872">MS13-006</a></td>
<td style="border:1px solid black;">Уязвимость протоколов Microsoft SSLv3 и TLS, делающая возможным обход функций безопасности</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0013">CVE-2013-0013</a></td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, связанная с обходом функций безопасности.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268284">MS13-007</a></td>
<td style="border:1px solid black;">Уязвимость функции замены, делающая возможной атаку типа &quot;отказ в обслуживании&quot;</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0005">CVE-2013-0005</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275222">MS13-008</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием Internet Explorer после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4792">CVE-2012-4792</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.<br />
<br />
Специалистам Майкрософт известно о направленных атаках с целью использования этой уязвимости через Internet Explorer 8.</td>
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
<th colspan="8">
Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=20d8d873-a709-4834-a956-f3d9d82dbb73)  
(KB2799329)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=dcdcf814-e39d-4515-bc5d-12e11f214d08)  
(KB2799329)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4e0d584a-c684-408c-bc47-6bd4ecaa9b8a)  
(KB2799329)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(критический)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=137cc5ee-abf0-4a10-b1c4-d464331cbcfd)  
(KB2757638)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=155a2984-2cd9-40a4-abaa-c1ea21e76062)  
(KB2742607)  
(только Media Center Edition 2005 с пакетом обновления 3 (SP3) и Tablet PC Edition 2005 с пакетом обновления 3 (SP3))  
(существенный)  
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(существенный)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=f35f2ea5-d60e-405a-9ed3-248e0d733c2b)  
(KB2799329)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=36c9d6a9-d939-4e19-b9f5-576fee048764)  
(KB2799329)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=396f26bd-8c8b-459d-9467-6ec17a11c9d4)  
(KB2799329)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=d147f865-6a56-4db2-8d78-14f2bee6da18)  
(KB2757638)  
(критический)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(критический)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=0b13a83c-1e51-4604-a09d-afb2e25646f9)  
(KB2758696)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(существенный)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=1a7cfc5a-2872-4516-a371-f42d4d3969a6)  
(KB2799329)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4b7c2bcd-a732-46ba-9d09-cc192efd4755)  
(KB2799329)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7f134d1c-670d-4528-b755-22124aa4d8c9)  
(KB2799329)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(средний)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=6a12de5f-de80-48e4-8276-6c420f5a2948)  
(KB2758696)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=f1a2eb6e-0290-4a53-b93c-017a48b19973)  
(KB2742604)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(существенный)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=00304f3b-069f-49dc-a416-b0b5fb97aa4b)  
(KB2799329)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4911899c-863f-4499-9477-340ef8daad29)  
(KB2799329)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b0cf6516-aea6-4879-9a6e-171d4825ae20)  
(KB2799329)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=29985fdc-8aba-44b2-9420-970ca475052e)  
(KB2757638)  
(средний)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(средний)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=0b13a83c-1e51-4604-a09d-afb2e25646f9)  
(KB2758696)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(существенный)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b2c635b7-56ad-426b-8bd6-4aee9deadb69)  
(KB2799329)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b33197ab-f489-4c11-a229-044b186d7dda)  
(KB2799329)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=bca95077-a28f-406c-9fe4-51dbcf6adee8)  
(KB2757638)  
(средний)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
(средний)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb834cf7-d1fe-4291-8a0d-c866fdbdf0e6)  
(KB2758696)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr>
<th colspan="8">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=95d603e8-9440-4aa6-9765-20c77a55966a)  
(KB2799329)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=64b498a6-54fc-4b88-bcc3-2cc15a16abb5)  
(KB2799329)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(критический)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=d477235d-60f4-420d-8161-82194b4e62e7)  
(KB2757638)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
(существенный)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8b1aef73-cfb2-4998-bca6-35cccfbb2078)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3107fadf-5ba8-48f6-bb23-0c0003b4ba76)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a35ccbff-c476-4ee2-be9c-5b6a4b1664e9)  
(KB2799329)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b427bace-5297-4593-9dd2-66847ae506c6)  
(KB2799329)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=873eba5d-5a8f-410e-bad8-e9d538acf1b3)  
(KB2757638)  
(критический)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(критический)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=873eba5d-5a8f-410e-bad8-e9d538acf1b3)  
(KB2757638)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
(существенный)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4287381f-6f23-4a36-a7dc-f79c44bac124)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=098958e5-83cd-4ed2-b758-e970cef33325)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
**Нет**
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3ce450f1-f71f-4d5d-bf1c-db4742522d18)  
(KB2799329)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2d1266fc-f6b0-4062-9799-7b3721c2cf52)  
(KB2799329)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(средний)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e6439fef-e5e7-479b-8fc4-daacf3a39f3a)  
(KB2757638)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
(существенный)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c635ad51-4e15-461c-8927-a86d79f90b45)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b3ed781e-b740-4153-aaf3-daafdeb91004)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0f87dd60-92c2-444c-a9ea-dfeb106c88fa)  
(KB2799329)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2f71f8e6-309c-4bea-abde-d91040c46611)  
(KB2799329)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735)  
(KB2757638)  
(средний)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(средний)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735)  
(KB2757638)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
(существенный)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=eff3a82e-f3db-4733-95aa-a68621e27068)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=4aa3e3a7-3ebc-4b47-ab62-c22243a4edcc)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e47425e9-f53e-4e20-a7ec-b4c552bd66eb)  
(KB2799329)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=c11ec9cd-1a85-4514-a1b9-9da5cdd0926b)  
(KB2757638)  
(средний)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
(средний)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=c11ec9cd-1a85-4514-a1b9-9da5cdd0926b)  
(KB2757638)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
(существенный)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d949fde9-31e7-4553-a34c-b41625a8cdc8)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ab117984-c4cb-473b-8c20-2b0d0409d8d6)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr>
<th colspan="8">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
Windows 7 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d20f50ed-89c3-48cb-a78d-a44470fa1285)  
(KB2799329)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=abbc3f31-e940-4750-acb6-5af477bc8390)  
(KB2769369)  
(критический)
</td>
<td style="border:1px solid black;">
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(критический)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=3a160fc4-1bf0-4db2-aa8d-6ba4f07d196b)  
(KB2757638)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
(существенный)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=057726d1-cdb4-4488-8cd8-822dabfc62a6)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=6120322b-7e04-4eeb-a9a4-11fe563a9f27)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d20f50ed-89c3-48cb-a78d-a44470fa1285)  
(KB2799329)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=abbc3f31-e940-4750-acb6-5af477bc8390)  
(KB2769369)  
(критический)
</td>
<td style="border:1px solid black;">
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(критический)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=3a160fc4-1bf0-4db2-aa8d-6ba4f07d196b)  
(KB2757638)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
(существенный)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=057726d1-cdb4-4488-8cd8-822dabfc62a6)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=6120322b-7e04-4eeb-a9a4-11fe563a9f27)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c113b67f-42ca-4fea-ba45-aba6f94de154)  
(KB2799329)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=1868c2ca-a184-494e-8eb3-82db45b08e32)  
(KB2769369)  
(критический)
</td>
<td style="border:1px solid black;">
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23)  
(KB2757638)  
(критический)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(критический)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23)  
(KB2757638)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
(существенный)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=64249562-1fc3-436d-a9e1-4c9378b632d7)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=c9e2a55e-170f-4fe1-a306-eda676fd0fdb)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c113b67f-42ca-4fea-ba45-aba6f94de154)  
(KB2799329)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1868c2ca-a184-494e-8eb3-82db45b08e32)  
(KB2769369)  
(критический)
</td>
<td style="border:1px solid black;">
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23)  
(KB2757638)  
(критический)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(критический)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23)  
(KB2757638)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
(существенный)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=64249562-1fc3-436d-a9e1-4c9378b632d7)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c9e2a55e-170f-4fe1-a306-eda676fd0fdb)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
Windows Server 2008 R2 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d2fffc43-a88f-4fe5-9b24-5677258011b8)  
(KB2799329)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19)  
(KB2769369)  
(критический)
</td>
<td style="border:1px solid black;">
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)  
(KB2757638)  
(средний)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(средний)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)  
(KB2757638)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
(существенный)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d2fffc43-a88f-4fe5-9b24-5677258011b8)  
(KB2799329)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19)  
(KB2769369)  
(критический)
</td>
<td style="border:1px solid black;">
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)  
(KB2757638)  
(средний)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(средний)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)  
(KB2757638)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
(существенный)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=fbcee22b-9801-4c9e-ba0c-eb4a54526d38)  
(KB2799329)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=18070321-8635-4c2e-b9f9-0fc58c924136)  
(KB2769369)  
(критический)
</td>
<td style="border:1px solid black;">
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
(средний)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
(средний)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
(существенный)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=12917b84-1f91-4c19-9197-a7d1e7adcdfc)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=86e5b2fc-f530-4259-af90-259b64fcdd73)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=fbcee22b-9801-4c9e-ba0c-eb4a54526d38)  
(KB2799329)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=18070321-8635-4c2e-b9f9-0fc58c924136)  
(KB2769369)  
(критический)
</td>
<td style="border:1px solid black;">
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
(средний)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
(средний)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
(существенный)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=12917b84-1f91-4c19-9197-a7d1e7adcdfc)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=86e5b2fc-f530-4259-af90-259b64fcdd73)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(существенный)
</td>
</tr>
<tr>
<th colspan="8">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 8 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(критический)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e19d1373-a3f3-4f60-9142-c2484726aac8)  
(KB2757638)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998)  
(KB2742616)  
(существенный)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e)  
(KB2756923)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a)  
(KB2742614)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 8 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=1f5441f1-a66d-42c0-bf0e-2f6867d4d43a)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 8 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=9f40864f-5347-44ef-bb08-afea45b5351b)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb)  
(KB2736693)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=c669190d-964c-42d3-b09d-40a397ae3a9c)  
(KB2757638)  
(критический)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(критический)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=c669190d-964c-42d3-b09d-40a397ae3a9c)  
(KB2757638)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998)  
(KB2742616)  
(существенный)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e)  
(KB2756923)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a)  
(KB2742614)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 8 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=9d71dc77-9c01-4a1f-b403-8a18ca10979d)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 8 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=1b40baad-784a-4eba-a4ef-703250248057)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb)  
(KB2736693)  
(существенный)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
Windows Server 2012
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528)  
(KB2757638)  
(средний)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(средний)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528)  
(KB2757638)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998)  
(KB2742616)  
(существенный)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e)  
(KB2756923)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a)  
(KB2742614)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=2ad7872c-a387-41a1-8606-732a6ff0701d)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=4f0b9fb1-f1c4-4773-a956-94c8983c008a)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb)  
(KB2736693)  
(существенный)  
[Management OData IIS Extension](http://www.microsoft.com/downloads/details.aspx?familyid=77b6fb5f-10b8-4bc2-a5c3-97055c92acf1)  
(KB2753596)  
(существенный)
</td>
</tr>
<tr>
<th colspan="8">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
**Нет**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
**Нет**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
MSXML 4.0<sup>[1]</sup>
(KB2758694)  
(критический)  
MSXML 6.0<sup>[1]</sup>
(KB2757638)  
(критический)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5<sup>[3]</sup>
(KB2742614)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="8">
Вариант установки ядра сервера
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-008**](http://go.microsoft.com/fwlink/?linkid=275222)****
</td>
<td style="border:1px solid black;">
[**MS13-001**](http://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-004**](http://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[**MS13-005**](http://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[**MS13-006**](http://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[**MS13-007**](http://go.microsoft.com/fwlink/?linkid=268284)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(средний)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e6439fef-e5e7-479b-8fc4-daacf3a39f3a)  
(KB2757638)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c635ad51-4e15-461c-8927-a86d79f90b45) (установка основных серверных компонентов)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b3ed781e-b740-4153-aaf3-daafdeb91004) (установка основных серверных компонентов)  
(KB2785220)  
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
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735) (установка основных серверных компонентов)  
(KB2757638)  
(средний)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04) (установка основных серверных компонентов)  
(KB2758694)  
(средний)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735) (установка основных серверных компонентов)  
(KB2757638)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=eff3a82e-f3db-4733-95aa-a68621e27068) (установка основных серверных компонентов)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4aa3e3a7-3ebc-4b47-ab62-c22243a4edcc) (установка основных серверных компонентов)  
(KB2785220)  
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
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19) (установка основных серверных компонентов)  
(KB2769369)  
(критический)
</td>
<td style="border:1px solid black;">
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3) (установка основных серверных компонентов)  
(KB2757638)  
(средний)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04) (установка основных серверных компонентов)  
(KB2758694)  
(средний)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3) (установка основных серверных компонентов)  
(KB2757638)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a) (установка основных компонентов сервера)  
(KB2742598)  
(существенный)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127) (установка основных компонентов сервера)  
(KB2756920)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5) (установка основных серверных компонентов)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e) (установка основных серверных компонентов)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4) (установка основных компонентов сервера)  
(KB2736418)  
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
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19) (установка основных серверных компонентов)  
(KB2769369)  
(критический)
</td>
<td style="border:1px solid black;">
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3) (установка основных серверных компонентов)  
(KB2757638)  
(средний)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04) (установка основных серверных компонентов)  
(KB2758694)  
(средний)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3) (установка основных серверных компонентов)  
(KB2757638)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0) (установка основных компонентов сервера)  
(KB2742599)  
(существенный)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3) (установка основных компонентов сервера)  
(KB2756921)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup> (установка основных серверных компонентов)  
(KB2742595)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0) (установка основных серверных компонентов)  
(KB2742613)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5) (установка основных серверных компонентов)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e) (установка основных серверных компонентов)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97) (установка основных компонентов сервера)  
(KB2736422)  
(существенный)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup> (установка основных серверных компонентов)  
(KB2736428)  
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
[MSXML 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528) (установка основных серверных компонентов)  
(KB2757638)  
(средний)  
[MSXML 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04) (установка основных серверных компонентов)  
(KB2758694)  
(средний)  
[MSXML 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528) (установка основных серверных компонентов)  
(KB2757638)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998) (установка основных серверных компонентов)  
(KB2742616)  
(существенный)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e) (установка основных серверных компонентов)  
(KB2756923)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a) (установка основных серверных компонентов)  
(KB2742614)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=2ad7872c-a387-41a1-8606-732a6ff0701d) (установка основных серверных компонентов)  
(KB2778930)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=4f0b9fb1-f1c4-4773-a956-94c8983c008a) (установка основных серверных компонентов)  
(KB2785220)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb) (установка основных серверных компонентов)  
(KB2736693)  
(существенный)  
[Management OData IIS Extension](http://www.microsoft.com/downloads/details.aspx?familyid=77b6fb5f-10b8-4bc2-a5c3-97055c92acf1) (установка основных серверных компонентов)  
(KB2753596)  
(существенный)
</td>
</tr>
</table>
 
**Примечания** **к бюллетеню MS13-002**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

<sup>[1]</sup>Обновления для системы безопасности Windows RT предоставляются через [Центр обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130).

**Примечания к бюллетеню MS13-004**

<sup>[1]</sup>**Уязвимости подвержены NET Framework 4 и клиентский профиль .NET Framework 4** Предлагаются два профиля для распространяемых пакетов .NET Framework версии 4: .NET Framework 4 и клиентский профиль .NET Framework 4. Клиентский профиль .NET Framework 4 является частью .NET Framework 4. Уязвимости, устраняемой данным обновлением, подвержены как платформа .NET Framework 4, так и клиентский профиль .NET Framework 4. Дополнительные сведения см. в статье MSDN [Установка .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

<sup>[2]</sup>Уровни серьезности не применимы к данному обновлению для указанного программного обеспечения, так как описанные в данном бюллетене известные направления атак с использованием этой уязвимости блокированы в конфигурации по умолчанию. Тем не менее, к качестве дополнительной меры защиты корпорация Microsoft рекомендует пользователям данного программного обеспечения установить это обновление безопасности.

<sup>[3]</sup>Обновления для системы безопасности Windows RT предоставляются только через [Центр обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130).

**Примечания** **к бюллетеню MS13-005**

<sup>[1]</sup> Обновления для системы безопасности Windows RT предоставляются через [Центр обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130).

**Примечания** **к бюллетеню MS13-006**

<sup>[1]</sup> Обновления для системы безопасности Windows RT предоставляются через [Центр обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130).

**Примечания к бюллетеню MS13-007**

<sup>[1]</sup>**Уязвимости подвержены NET Framework 4 и клиентский профиль .NET Framework 4** Предлагаются два профиля для распространяемых пакетов .NET Framework версии 4: .NET Framework 4 и клиентский профиль .NET Framework 4. Клиентский профиль .NET Framework 4 является частью .NET Framework 4. Уязвимости, устраняемой данным обновлением, подвержены как платформа .NET Framework 4, так и клиентский профиль .NET Framework 4. Дополнительные сведения см. в статье MSDN [Установка .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Пакеты приложений и программные продукты Microsoft Office

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Наборы приложений и компоненты Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
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
Microsoft Office 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[MSXML 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=d108d56c-f9fb-4823-b38e-3d2f838592de)  
(KB2760574)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[MSXML 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[MSXML 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(критический)
</td>
</tr>
<tr>
<th colspan="2">
Прочие программы Microsoft Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
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
Средство просмотра Microsoft Word
</td>
<td style="border:1px solid black;">
[MSXML 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[MSXML 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[MSXML 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(критический)
</td>
</tr>
</table>
 
**Примечания к бюллетеню MS13-002**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

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
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
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
Microsoft Expression Web с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[MSXML 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[MSXML 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(критический)
</td>
</tr>
</table>
 
**Примечания к бюллетеню MS13-002**

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
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-003**](http://go.microsoft.com/fwlink/?linkid=261863)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 с пакетом обновления 2 (SP2) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
[MSXML 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 с пакетом обновления 2 (SP2) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
[MSXML 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 с пакетом обновления 3 (SP3) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
[MSXML 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
(критический)
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
[MSXML 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(критический)
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
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-003**](http://go.microsoft.com/fwlink/?linkid=261863)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove Server 2007 с пакетом обновлений 2 (SP2)
</td>
<td style="border:1px solid black;">
[MSXML 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2007 с пакетом обновлений 3 (SP3)
</td>
<td style="border:1px solid black;">
[MSXML 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Microsoft System Center Operations Manager
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-002**](http://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[**MS13-003**](http://go.microsoft.com/fwlink/?linkid=261863)
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
Microsoft System Center Operations Manager 2007 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft System Center Operations Manager 2007 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=f848d74d-fdae-4a19-a0f5-12d2d4389db9)<sup>[1]</sup>
(KB2809182)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft System Center Operations Manager 2007 R2
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft System Center Operations Manager 2007 R2](http://www.microsoft.com/downloads/details.aspx?familyid=4e1ab3bd-af0c-41f8-8ebc-1cdc68a3ee37)<sup>[1]</sup><sup>[2]</sup>
(KB2783850)  
(существенный)
</td>
</tr>
</table>
 
**Примечания к бюллетеню MS13-002**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

**Примечания** **к бюллетеню MS13-003**

<sup>[1]</sup>Этот пакет обновления можно загрузить только с веб-сайта Центра загрузки Майкрософт.

<sup>[2]</sup>Это накопительное обновление, которое заменяет предыдущие накопительные обновления для указанного программного обеспечения.

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

-   Николя Грегуару (Nicolas Gregoire) из [Agarri](http://www.agarri.fr/) сообщение об уязвимости, описанной в бюллетене MS13-002
-   Энди Янга (Andy Yang) из BAE Systems Detica за сообщение об уязвимости, описанной в бюллетене MS13-003
-   Йона Эриксона (Jon Erickson) из компании [iSIGHT Partners Labs](http://www.isightpartners.com/) за сообщение об уязвимости, описанной в бюллетене MS13-004
-   Виталия Торопова (Vitaliy Toropov), сотрудничающего с компанией [Tipping Point](http://www.tippingpoint.com/)[в рамках программы Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о двух уязвимостях, описанных в бюллетене MS13-004
-   Джеймса Форшоу (James Forshaw) из компании Context Information Security за сообщение об уязвимости, описанной в MS13-004
-   [Кенитиро Катаяма (Kenichiro Katayama)](https://twitter.com/pin_ptr) за сообщение об уязвимости, описанной в бюллетене MS13-006
-   Компанию [Exodus Intelligence](https://www.exodusintel.com) за совместную работу над устранением уязвимости, описанной в бюллетене MS13-008

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617.aspx)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (8 января 2013 г.): Обзор бюллетеней опубликован.
-   Вер. 1.1 (8 января 2013 г.): В бюллетене MS13-002 в раздел "Подвержены уязвимости" добавлены сведения об установке ядра сервера для Microsoft XML Core Services 4.0 в ОС Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) и Microsoft XML Core Services 6.0 в ОС Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2). Это изменение носит исключительно информационный характер. Пользователям, уже выполнившим успешное обновление компьютеров, не требуется выполнять никаких действий.
-   Версия 2.0 (14 января 2013 г.): Добавлены: бюллетень по безопасности (Майкрософт) MS13-008, обновление для системы безопасности Internet Explorer (2799329), а также ссылка на сведения о веб-трансляции, посвященной внеплановому бюллетеню по безопасности.
-   Версия 3.0 (22 января 2013 г.): Выпущена новая редакция бюллетеня MS13-004, связанная с повторным предоставлением обновления KB2756920 для систем Windows 7 и Windows Server 2008 R2 с определенными конфигурациями, в которых возможны проблемы совместимости. Подробную информацию можно найти в бюллетене.
-   Вер. 4.0 (12 марта 2013): Для MS13-003: бюллетень выпущен повторно, чтобы объявить о выпуске обновления для Microsoft System Center Operations Manager 2007 с пакетом обновления 1 (SP1). Данный повторный выпуск не затрагивает никакие другие пакеты обновления. Подробную информацию можно найти в бюллетене.

*Built at 2014-04-18T01:50:00Z-07:00*
