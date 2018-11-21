---
TOCTitle: 'MS11-DEC'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за декабрь 2011 г.'
ms:assetid: 'ms11-dec'
ms:contentKeyID: 61236145
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms11-dec(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за декабрь 2011 г.
================================================================

Дата публикации: 13 декабря 2011 г. | Дата обновления: 22 февраля 2012 г.

**Версия:** 2.1

В этот обзор включены бюллетени по безопасности, выпущенные в декабре 2011 г.

В связи с публикацией бюллетеней по безопасности за декабрь 2011 года настоящий обзор заменяет предварительное уведомление, выпущенное 28 декабря 2011 года. Дополнительные сведения о службе предварительного уведомления см. на веб-сайте [службы предварительного уведомления о бюллетенях Майкрософт по безопасности](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

14 декабря 2011 г. в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в декабрьской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032487961). После наступления этой даты данная веб-трансляция будет доступна по запросу. Дополнительные сведения см. на веб-сайте [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://go.microsoft.com/fwlink/?linkid=217214).

29 декабря 2011 года в 13:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей о данном внеплановом бюллетене по безопасности. [Зарегистрируйтесь для участия в веб-трансляции, посвященной бюллетеням по безопасности (29 декабря, 13:00)](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032502798&culture=en-us). После наступления этой даты данная веб-трансляция будет доступна по запросу. Дополнительные сведения см. на веб-сайте [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://go.microsoft.com/fwlink/?linkid=217214).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=233008">MS11-087</a></td>
<td style="border:1px solid black;"><strong>Уязвимость драйверов режима ядра Windows делает возможным удаленное выполнение кода (2639417)</strong><br />
<br />
Это обновление для системы безопасности устраняет опубликованную уязвимость в Microsoft Windows. Эта уязвимость делает возможным удаленное выполнение кода, если пользователь откроет специально созданный документ или посетит вредоносную веб-страницу с внедренными файлами шрифтов TrueType.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232507">MS11-090</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление системы безопасности для битов аннулирования ActiveX (2618451)</strong><br />
<br />
Это обновление системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Exchange. Эта уязвимость делает возможным удаленное выполнение кода, если пользователь просмотрит специально созданную веб-страницу, использующую определенный функциональный компонент в браузере Internet Explorer. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. Это обновление также включает биты аннулирования для четырех сторонних элементов ActiveX.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232517">MS11-092</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Windows Media</strong> <strong>делает возможным удаленное выполнение кода (2648048)</strong><br />
<br />
Данное обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в проигрывателе Windows Media и Windows Media Center. Эта уязвимость делает возможным удаленное выполнение кода при открытии пользователем особым образом созданного файла цифровой видеозаписи Microsoft (.dvr-ms). Однако в любом случае злоумышленник не может заставить пользователя открыть файл; чтобы атака была успешной, злоумышленнику необходимо убедить пользователя сделать это.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=227070">MS11-088</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Office IME</strong> <strong>(китайский язык) делает возможным несанкционированное получение прав (2652016)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость приложения Microsoft Office IME (для китайского языка). Данная уязвимость делает возможным несанкционированное получение прав, если вошедший пользователь выполнил специальные действия в системе, в которой установлена уязвимая версия редактора метода ввода (IME) Microsoft Pinyin (MSPY) для китайского языка (упрощенное письмо). Воспользовавшийся ею злоумышленник может запустить произвольный код в режиме ядра. После этого злоумышленник сможет устанавливать программы, просматривать, изменять и удалять данные или создавать новые учетные записи с полными правами администратора. Этой уязвимости подвержены только реализации Microsoft Pinyin IME 2010. Другие версии редактора метода ввода для китайского языка (упрощенное письмо) и другие реализации редактора метода ввода не подвержены данной уязвимости.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225739">MS11-089</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft</strong> <strong>Office делает возможным удаленное выполнение кода (2590602)</strong><br />
<br />
Это обновление для системы безопасности устраняет уязвимость в пакете Microsoft Office, о которой сообщалось в частном порядке. Эта уязвимость делает возможным удаленное выполнение кода при открытии пользователем особым образом созданного файла Word. Злоумышленник, воспользовавшийся этой уязвимостью, может получить те же права, что и вошедший в систему пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235287">MS11-091</a></td>
<td style="border:1px solid black;"><strong>Уязвимости приложения Microsoft Publisher делают возможным удаленное</strong> <strong>выполнение кода (2607702)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну опубликованную и три обнаруженных пользователями уязвимостей в Microsoft Office. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь откроет особым образом созданный файл Publisher. Воспользовавшись некоторыми из этих уязвимостей, злоумышленник может получить полный контроль над системой, подверженной уязвимости. После этого злоумышленник сможет устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными правами. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232516">MS11-093</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в OLE делает возможным удаленное выполнение кода (2624667)</strong><br />
<br />
Настоящее обновление для системы безопасности устраняет обнаруженную пользователями уязвимость во всех поддерживаемых выпусках Windows XP и Windows Server 2003. Уровень важности этого обновления определен как &quot;существенный&quot; для всех выпусков Windows XP и Windows Server 2003. Операционные системы Windows Vista, Windows Server 2008, Windows 7 и Windows Server 2008 R2 не подвержены данной уязвимости.<br />
<br />
Данная уязвимость делает возможным удаленное выполнение кода, если пользователь откроет файл, содержащий особым образом созданный объект OLE. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которые имеет локальный пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232493">MS11-094</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft PowerPoint делают возможным удаленное выполнение кода (2639142)</strong><br />
<br />
Это обновление для системы безопасности устраняет две<strong></strong>обнаруженных пользователями уязвимости в Microsoft Office. Эти уязвимости делают возможным удаленное выполнение кода при открытии пользователем особым образом созданного файла PowerPoint. Злоумышленник, успешно воспользовавшийся любой из этих уязвимостей, может получить полный контроль над уязвимой системой. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232666">MS11-095</a></td>
<td style="border:1px solid black;"><strong>Уязвимость службы Active Directory делает возможным удаленное выполнение кода (2640045)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Active Directory, службе ADAM и службе Active Directory облегченного доступа к каталогам (AD LDS). Эта уязвимость делает возможным удаленное выполнение кода, если злоумышленник войдет в домен Active Directory и выполнит специально созданное приложение. Для использования этой уязвимости злоумышленнику потребуется получить учетные данные для входа в домен Active Directory.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232696">MS11-096</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Excel делают возможным удаленное выполнение кода (2640241)</strong><br />
<br />
Это обновление для системы безопасности устраняет уязвимость в пакете Microsoft Office, о которой сообщалось в частном порядке. Эта уязвимость делает возможным удаленное выполнение кода, если пользователь открывает особым образом созданный файл Excel. Злоумышленник, воспользовавшийся этой уязвимостью, может получить те же права, что и вошедший в систему пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. Установка и настройка средства проверки файлов Office (OFV) для предотвращения открытия подозрительных файлов блокирует направления атак связанных с уязвимостями, описанными в CVE-2011-3403.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232663">MS11-097</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в подсистеме исполнения клиент-сервер Windows</strong> <strong>делает возможным несанкционированное получение прав (2620712)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Уязвимость делает возможным несанкционированное получение прав, если злоумышленник вошел в уязвимую систему и запустил специально созданное приложение, разработанное для отправки сообщения о событии, связанном с устройством, процессу с более высоким уровнем целостности. Чтобы воспользоваться этой уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232424">MS11-098</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в ядре Windows делает возможным несанкционированное получение прав (2633171)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным несанкционированное получение прав, если злоумышленник вошел в систему и запустил приложение, специально разработанное для использования данной уязвимости. Чтобы воспользоваться этой уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему. Данной уязвимостью не могут воспользоваться удаленные или анонимные пользователи.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232505">MS11-099</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление</strong> <strong>для системы безопасности браузера Internet Explorer (2618444)</strong><br />
<br />
Это обновление для системы безопасности устраняет три обнаруженных пользователями уязвимости в браузере Internet Explorer. Эти уязвимости делают возможным удаленное выполнение кода при условии, что злоумышленник сможет убедить пользователя открыть подлинный HTML-файл, который размещается в том же сетевом каталоге, что и особым образом созданный DLL-файл.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232432">MS11-100</a></td>
<td style="border:1px solid black;"><strong>Уязвимости</strong> <strong>в .NET Framework</strong> <strong>делают</strong> <strong>возможным</strong> <strong>несанкционированное</strong> <strong>получение прав</strong> <strong>(2638420)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну опубликованную и три обнаруженных пользователями уязвимостей в Microsoft .NET Framework. Наиболее серьезная из этих уязвимостей делает возможным несанкционированное получение прав, если злоумышленник, не прошедший проверку подлинности, отправляет специально созданный веб-запрос целевому веб-сайту. Воспользовавшись этой уязвимостью, злоумышленник может выполнить любое действие в контексте существующей учетной записи на сайте ASP.NET, включая выполнение произвольных команд. Для использования этой уязвимости злоумышленник должен обладать возможностью регистрации учетной записи на сайте ASP.NET и знать имя существующего пользователя.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
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
  
<table style="width:100%;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=233008">MS11-087</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с анализом шрифтов TrueType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3402">CVE-2011-3402</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Данная уязвимость была открыто опубликована.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=227070">MS11-088</a></td>
<td style="border:1px solid black;">Уязвимость в Pinyin IME, приводящая к несанкционированному получению прав</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2010">CVE-2011-2010</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225739">MS11-089</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием Word после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1983">CVE-2011-1983</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232507">MS11-090</a></td>
<td style="border:1px solid black;">Уязвимость в Microsoft Time, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3397">CVE-2011-3397</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235287">MS11-091</a></td>
<td style="border:1px solid black;">Уязвимость Publisher, связанная с записью в индекс массивов вне допустимого диапазона</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3410">CVE-2011-3410</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235287">MS11-091</a></td>
<td style="border:1px solid black;">Уязвимость Publisher, связанная с недопустимой функцией указателя</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3411">CVE-2011-3411</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235287">MS11-091</a></td>
<td style="border:1px solid black;">Уязвимость в Publisher, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3412">CVE-2011-3412</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232517">MS11-092</a></td>
<td style="border:1px solid black;">Уязвимость DVR-MS проигрывателя Windows Media, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3401">CVE-2011-3401</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232516">MS11-093</a></td>
<td style="border:1px solid black;">Уязвимость свойства OLE</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3400">CVE-2011-3400</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232493">MS11-094</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с небезопасной загрузкой PowerPoint внешних библиотек</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3396">CVE-2011-3396</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Продукт Microsoft PowerPoint 2010 подвержен уязвимости, только если не установлен последний пакет обновления.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232493">MS11-094</a></td>
<td style="border:1px solid black;">Уязвимость OfficeArt Shape, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3413">CVE-2011-3413</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232666">MS11-095</a></td>
<td style="border:1px solid black;">Уязвимость в Active Directory, связанная с переполнением буфера</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3406">CVE-2011-3406</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Подвержены уязвимости только системы, в которых работают Active Directory, AD LDS или ADAM.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232696">MS11-096</a></td>
<td style="border:1px solid black;">Уязвимость записей, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3403">CVE-2011-3403</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232663">MS11-097</a></td>
<td style="border:1px solid black;">Уязвимость CSRSS, приводящая к несанкционированному получению локальных прав</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3408">CVE-2011-3408</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232424">MS11-098</a></td>
<td style="border:1px solid black;">Уязвимость обработчика исключений ядра Windows</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2018">CVE-2011-2018</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232505">MS11-099</a></td>
<td style="border:1px solid black;">Уязвимость XSS-фильтра, приводящая к раскрытию информации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1992">CVE-2011-1992</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232505">MS11-099</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с небезопасной загрузкой библиотек в Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2019">CVE-2011-2019</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232432">MS11-100</a></td>
<td style="border:1px solid black;">Коллизии в хэш-таблицах могут стать причиной уязвимости, делающей возможной атаку типа &quot;отказ в обслуживании&quot;</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3414">CVE-2011-3414</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">Данная опубликованная уязвимость делает возможной только атаку типа &quot;отказ в обслуживании&quot;.
<div>
  
</div>
<div>
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">Уязвимостям, делающим возможной атаки типа &quot;отказ в обслуживании&quot;, присваивается индекс использования &quot;3&quot;.</a>
</div></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232432">MS11-100</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с обходом проверки подлинности с помощью форм ASP.Net</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3416">CVE-2011-3416</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Несанкционированное получение прав — получение контроля над учетной записью</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232432">MS11-100</a></td>
<td style="border:1px solid black;">Уязвимость кэширования билетов проверки подлинности с помощью форм ASP.NET</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3417">CVE-2011-3417</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Несанкционированное получение прав — получение контроля над учетной записью</td>
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
  
**Таблица 1**

 
<table style="border:1px solid black;">
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
[**MS11-087**](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](http://go.microsoft.com/fwlink/?linkid=232663)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=b01bb041-005c-48c4-a606-66aa264ba0fa)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=21b4b999-2dbf-4921-80bd-cc7ab2cd1190)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=d85091b5-69bb-4d0f-839a-a65cd94e2887)  
(KB2619339)  
(критический)  
[Windows XP Media Center Edition 2005 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=03bc6446-7cf3-47c4-8ed1-a53a4d53a429)  
(KB2619340)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=73531165-f299-4b62-b738-52fca410eaae)  
(существенный)
</td>
<td style="border:1px solid black;">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=3b816964-d3c3-4f05-94c3-f54a6f54ca73)  
(KB2626416)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=edb594a4-14d2-4ffe-8d1c-2c283689fe8c)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0a872cd2-5f4d-400c-a1c4-a2d194746fb6)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=126e8092-980d-471a-867d-d5939671b7df)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7d1d1e9a-603c-4895-a69f-b61186a75ad5)  
(KB2619339)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a98bb7cf-9939-4927-8d21-ccb3845e7cb7)  
(существенный)
</td>
<td style="border:1px solid black;">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=986f0087-c674-4060-8710-af3496adbfdd)  
(KB2626416)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=9e1273e2-7775-40b4-b939-ab530677cd4a)  
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
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-087**](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](http://go.microsoft.com/fwlink/?linkid=232663)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e84e6964-1580-41ef-9d3e-4d0c3ad4cb69)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=dfb948c5-8aee-4bcd-babf-3564b78712dd)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6b555040-1117-4b06-a48c-02f0e1b686d8)  
(существенный)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=01caf06f-777d-4ea8-95ca-e11d60a973ad)  
(KB2621146)  
(существенный)  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=6f7c7ccd-22a3-4fbc-bf21-bd0e42ab1da5)  
(KB2626416)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a14057e5-e2c2-4dde-8d26-542a9f162e98)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=9d9f3667-3fd6-4948-83db-282783599f41)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2d37a8cb-2316-4db4-980c-11b6dcbdc696)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=eb17782c-f754-42ab-905b-6f141df008c3)  
(существенный)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=e1ba50cf-fc6b-4668-b71c-e9f75a8ac638)  
(KB2621146)  
(существенный)  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=1b610eb3-456c-4125-94b7-1ead4face8e3)  
(KB2626416)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7f595fd6-bdfd-4075-97e5-70efb7d49dff)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1ecf72cd-6732-4cf3-aa22-8caf15ea633e)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7726ddbe-0578-44fb-a40f-49b804a45989)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4cdde8a9-6d44-41fa-82c0-a25404cdfbb5)  
(существенный)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=74099261-60ad-4c68-906c-60e131818955)  
(KB2621146)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=147ec6d3-3401-4aa3-a409-55346bcc7bd7)  
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
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-087**](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](http://go.microsoft.com/fwlink/?linkid=232663)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7f69ec9d-43ad-4106-90ef-c191e7ec43af)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1dd069a2-fb1a-4f31-88cc-bc031c3e2c80)  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e9130fad-de8c-4be0-aea1-62cbaa310b76)  
(KB2619339)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=470da512-2c8b-4ba9-b7bb-b9e6c45cd33f)  
(KB2621146)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=fa6e6d91-4aca-49a6-a6e8-c33ec413097e)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ae1f1f86-6f13-4e1e-9f93-4f70b6c9927e)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=60fd5bf6-e820-44f6-8081-b98c0103acc1)  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b7c4bf05-eb2d-48ac-a6df-8afd88e811d8)  
(KB2619339)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=8daf9a49-60cb-4813-ac7a-e9a4bf296889)  
(KB2621146)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c9794756-803d-48ba-86db-350fb577f01b)  
(существенный)
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
[**MS11-087**](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](http://go.microsoft.com/fwlink/?linkid=232663)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c4ba344d-dd0d-4cfb-81d9-d364d7f37e25)\*\*\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=f485d4c3-a4af-4ae6-9404-e79afcbb4f6e)\*\*  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Active Directory и службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=6f9ddcdb-a471-4e00-a697-92a24e4ea8d4)\*  
(KB2621146)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6f934885-b134-400c-a452-50fd4eeedd5e)\*  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для компьютеров на базе x64-процессоров с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=058963f6-9654-41d0-86d2-f25a0c2ad416)\*\*\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для компьютеров на базе x64-процессоров с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=28598ef6-13fb-44fd-8c76-599af7b0a01d)\*\*  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Active Directory и службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=5253477b-422f-404a-941e-8b69da5a2670)\*  
(KB2621146)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7ade3832-bc20-4fce-8eac-8a3d072d2f1c)\*  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=42cd1c33-11a7-4a29-ae85-f7272a626f91)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5915e19c-b576-453b-b621-5737774f5955)  
(Уровень опасности не определен<sup>[1]</sup>)
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
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4bd7a02b-c6d8-4eb5-a46d-e494a1233dc8)  
(существенный)
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
[**MS11-087**](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](http://go.microsoft.com/fwlink/?linkid=232663)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=0526727a-f2fb-4846-9b04-f1899f52f1f6)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d112623c-86ce-434a-8fe1-ec3e3e632763)  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b6e44069-dec5-48f6-8fc4-8ab375a10b4e)  
(KB2619339)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=d2e87199-6469-4bc0-a721-f43e817e4344)  
(KB2621146)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=0666bdf5-9eed-44c9-84ee-b45f9b3e14b3)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=cfd42c42-1595-419a-bf04-b23b64663629)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=81114ecd-0c73-4ca6-8a66-09c6c636a5db)  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=f7997ab8-27e0-4714-845a-d237f4326587)  
(KB2619339)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=ba8d7aa9-8299-49a3-b0c0-b8b5eab48434)  
(KB2621146)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=620f94f9-1f61-45a0-a22e-e7510b56b9b8)  
(существенный)
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
[**MS11-087**](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](http://go.microsoft.com/fwlink/?linkid=232663)
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
<td style="border:1px solid black;">
Нет
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
Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d64a31ca-cccd-488a-98fd-c059b9e9e1ea)\*\*\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновлений 1 (SP 1)](http://www.microsoft.com/downloads/details.aspx?familyid=bc018647-08cb-431a-8e7c-5dc04980eaa9)\*\*  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Active Directory и службы Active Directory облегченного доступа к каталогам (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=a3e0d27c-8b29-4981-bdef-bcd037fd3408)\*  
(KB2621146)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=04878e9a-539a-4549-a5af-11d45add91da)\*  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b46f6da7-6d24-4262-8e55-3b657db39813)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=9323b9b9-e9b0-4941-afe0-196d22df9ab4)  
(Уровень опасности не определен<sup>[1]</sup>)
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
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5b2ebec4-cebb-47b6-864a-12d59a9a3e18)  
(существенный)
</td>
</tr>
</table>
 
**Примечания для Windows Server 2008 и Windows Server 2008 R2**

**\*Уязвимости подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Это обновление (с одинаковым уровнем серьезности) применяется к указанным выше поддерживаемым выпускам Windows Server 2008 или Windows Server 2008 R2 независимо от наличия установленных основных компонентов сервера. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Уязвимости не подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Поддерживаемые выпуски Windows Server 2008 или Windows Server 2008 R2, при развертывании которых выбиралась установка только ядра сервера, не подвержены уязвимостям, устраняемым этим обновлением. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*\*\*Уязвимости подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Это обновление (с более низким уровнем серьезности) применяется к поддерживаемым выпускам Windows Server 2008 или Windows Server 2008 R2 (согласно указаниям), при развертывании которых выбиралась установка только ядра сервера. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Примечание для MS11-090**

<sup>[1]</sup>Эта конкретная операционная система не подвержена уязвимости, описанной в данном бюллетене. Доступное обновление устанавливает биты аннулирования для элементов управления сторонних производителей.

**Таблица 2**

 
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
[**MS11-098**](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](http://go.microsoft.com/fwlink/?linkid=232432)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=7a6fcf8d-8c7b-4882-90d3-02db79a75238)  
(существенный)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=caa9360b-2fd8-4f46-99e6-2decf1b60ca7)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=dc6dcd8c-c39f-4c4b-b5b2-b4c18c36973b)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f3906245-b6f6-464a-84b6-e1b6b195df95)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=2fa77733-70f5-46ff-9cfe-2262d292b870)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a0c55d9b-8529-4d3d-910d-1a822a825be2)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=3e60e996-8850-4d25-b994-39646e2cc25e)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
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
[**MS11-098**](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](http://go.microsoft.com/fwlink/?linkid=232432)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий **уровень** опасности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Низкий**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=281e5bd4-4582-4aa9-af88-518ad3152132)  
(существенный)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=759041cf-fd8b-4e04-b289-d74112bf978b)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b1b4af92-3ff1-4727-9ba3-52764a7b81bb)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=1cbe9469-05f4-4305-bbfd-76b4a04cd598)  
(низкий)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=7538762a-50e9-4f13-a60e-ff99aa8fbbf8)  
(KB2656358)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=5587eca8-86e9-4a63-81cb-81f68178a6c0)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=7a87f890-f106-41ab-bc53-4ca44dc99cb1)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=a42fa727-482c-4578-9a30-61fdf14ed4da)  
(низкий)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=02d5c057-d551-411b-917b-43d7795111bc)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2fccb214-6c79-4ef6-9d6e-df4f16ef792e)  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
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
[**MS11-098**](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](http://go.microsoft.com/fwlink/?linkid=232432)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a6c7c960-768d-40d4-8fe5-7d59f48ead1d)  
(существенный)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0adc422f-73f2-46ee-973f-9b7603a76d1e)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4327147b-0481-4172-a835-8786abc50596)  
(существенный)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=a0b19b35-1d48-4419-ba3d-66063cc472a7)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)  
(KB2656362)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8a3f2351-380b-4566-b186-906dca426d39)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=987f0966-01de-4edf-a0d6-4032d1d72966)  
(существенный)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c951044b-4596-462f-bc8f-bdd9d6734297)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)  
(KB2656362)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
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
[**MS11-098**](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](http://go.microsoft.com/fwlink/?linkid=232432)
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
[**Низкий**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5a4443f8-fec8-42be-ad67-8475920f1460)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=eaf587f0-9951-4480-a08b-377e61aaf72b)\*\*  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8f5af52f-dece-4f0c-9fc0-d4973e4f7b1a)\*\*  
(низкий)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c03e65d6-4f92-4bc1-94b5-2f0183d0133e)\*\*  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)\*\*  
(KB2656353)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)\*\*  
(KB2656362)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)\*\*  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)\*\*<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2f18fc98-984a-4c02-951f-b8438a9e4f6b)\*\*  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=808d26f7-c8fa-446d-9d2f-e8c0babb0c4a)\*\*  
(низкий)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b7a582f3-0a18-4fbf-9b99-21c664bfd979)\*\*  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)\*\*  
(KB2656353)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)\*\*  
(KB2656362)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)\*\*  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)\*\*<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=fc62df39-7185-448b-b356-25a5a07886ec)  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=49050cf2-949a-40e5-b2ee-6257a3837294)  
(KB2656362)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
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
[**MS11-098**](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](http://go.microsoft.com/fwlink/?linkid=232432)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий** **уровень опасности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=eb2bd108-5ef1-45be-9157-e7cbfc8afd2a)  
(существенный)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=018610bb-e80a-432a-8f32-f50451f71ad9)  
(существенный)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=ec2046a6-f069-4f02-9600-7640e57be0a3)  
(существенный)
</td>
<td style="border:1px solid black;">
Только Windows 7 для 32-разрядных систем:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c)  
(KB2656355)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)  
Только для Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1):  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9)  
(KB2656356)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=dbe85b05-e252-4029-8e25-f2452db1c017)  
(существенный)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=4c773b3d-0ca3-4b9b-af9a-9d6edcd261f7)  
(существенный)
</td>
<td style="border:1px solid black;">
Только Windows 7 для 64-разрядных систем:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c)  
(KB2656355)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)  
Только для Windows 7 для 64-разрядных систем с пакетом обновления 1 (SP1):  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9)  
(KB2656356)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
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
[**MS11-098**](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](http://go.microsoft.com/fwlink/?linkid=232432)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2108b4ef-942f-4727-a1fc-ee7d0abb427c)\*\*  
(низкий)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=72c1654e-526f-4ece-b7ad-767a0710e076)\*\*  
(существенный)
</td>
<td style="border:1px solid black;">
Только Windows Server 2008 R2 для 64-разрядных систем:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c)\*  
(KB2656355)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)  
Только для Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1):  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9)\*  
(KB2656356)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)\*<sup>[1]</sup>
(KB2656351)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=74614510-e13c-43e8-90e7-d81e63895cf2)  
(низкий)
</td>
<td style="border:1px solid black;">
Только для Windows Server 2008 R2 for Itanium-based Systems:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=2de28d32-1efd-4177-82e6-19a08266096c)  
(KB2656355)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)  
Только для Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1):  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=26e0b56d-9228-49cf-9276-0741257567a9)  
(KB2656356)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>
(KB2656351)
</td>
</tr>
</table>
 
**Примечания для Windows Server 2008 и Windows Server 2008 R2**

**\*Уязвимости подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Это обновление (с одинаковым уровнем серьезности) применяется к указанным выше поддерживаемым выпускам Windows Server 2008 или Windows Server 2008 R2 независимо от наличия установленных основных компонентов сервера. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Уязвимости не подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Поддерживаемые выпуски Windows Server 2008 или Windows Server 2008 R2, при развертывании которых выбиралась установка только ядра сервера, не подвержены уязвимостям, устраняемым этим обновлением. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Примечание для MS11-099**

<sup>[1]</sup>Уровни серьезности не применимы к данному обновлению для указанного программного обеспечения, так как описанные в данном бюллетене известные направления атак с использованием этой уязвимости блокированы в конфигурации по умолчанию. Тем не менее, к качестве дополнительной меры защиты корпорация Microsoft рекомендует пользователям данного программного обеспечения установить это обновление безопасности.

**Примечание для MS11-100**

<sup>[1]</sup>**Уязвимости подвержены NET Framework 4 и клиентский профиль .NET Framework 4** Предлагаются два профиля для распространяемых пакетов .NET Framework версии 4: .NET Framework 4 и клиентский профиль .NET Framework 4. Клиентский профиль .NET Framework 4 является частью .NET Framework 4. Уязвимости, устраняемой данным обновлением, подвержены как платформа .NET Framework 4, так и клиентский профиль .NET Framework 4. Дополнительные сведения см. в статье MSDN [Установка .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Наборы приложений и прочие программные продукты Office

 
<table style="border:1px solid black;">
<tr>
<th colspan="6">
Наборы приложений и компоненты Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-088**](http://go.microsoft.com/fwlink/?linkid=227070)
</td>
<td style="border:1px solid black;">
[**MS11-089**](http://go.microsoft.com/fwlink/?linkid=225739)
</td>
<td style="border:1px solid black;">
[**MS11-091**](http://go.microsoft.com/fwlink/?linkid=235287)
</td>
<td style="border:1px solid black;">
[**MS11-094**](http://go.microsoft.com/fwlink/?linkid=232493)
</td>
<td style="border:1px solid black;">
[**MS11-096**](http://go.microsoft.com/fwlink/?linkid=232696)
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
Microsoft Office 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=13f3e884-37bf-4ed2-b3ed-a0e7fb48e44f)  
(KB2553084)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=5859014f-afc5-4958-82ea-6ba45a5ad4b3)  
(KB2596954)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Outlook 2007 с пакетом обновления 2 (SP2) и Microsoft Office Outlook 2007 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office Outlook 2007 с пакетом обновления 2 (SP2) и Microsoft Office Outlook 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=e924cd85-5764-4056-bd32-b0e57dc25146)  
(KB2596785)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2007 с пакетом обновления 2 (SP2) и Microsoft Publisher 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=2856821e-f1fd-424b-b03c-e443685eea6d)  
(KB2596705)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d0c3156c-c87c-4d3e-aca2-3fab9ff78711)  
(KB2596764)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 и Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
[Microsoft Pinyin IME 2010 (32-разрядная версия)](http://www.microsoft.com/downloads/details.aspx?familyid=d812621e-c35a-4cb0-ba26-928363f3422d)  
(KB2596511)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 и Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=e47c0694-a9a5-4dd7-bfba-e470d9855c28)  
(KB2589320)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2010 (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=fd32d083-46e7-4835-ba83-c33332b920bd)  
(KB2553185)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 и Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
[Microsoft Pinyin IME 2010 (64-разрядная версия)](http://www.microsoft.com/downloads/details.aspx?familyid=c8d3ac17-5aca-4da3-961f-b753be4a3634)  
(KB2596511)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 и Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=6c2d5273-eef9-4ff6-be6f-8d86f417f004)  
(KB2589320)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2010 (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=f28b8cf6-8946-448a-ae4e-d11f8a76a679)  
(KB2553185)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="6">
Microsoft Office для Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-088**](http://go.microsoft.com/fwlink/?linkid=227070)
</td>
<td style="border:1px solid black;">
[**MS11-089**](http://go.microsoft.com/fwlink/?linkid=225739)
</td>
<td style="border:1px solid black;">
[**MS11-091**](http://go.microsoft.com/fwlink/?linkid=235287)
</td>
<td style="border:1px solid black;">
[**MS11-094**](http://go.microsoft.com/fwlink/?linkid=232493)
</td>
<td style="border:1px solid black;">
[**MS11-096**](http://go.microsoft.com/fwlink/?linkid=232696)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий** **уровень опасности**
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 для Mac
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
[Microsoft Office 2004 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=ef3b559c-0bd2-45dd-8049-6946f6431a2a)  
(KB2644358)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 для Mac
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
[Microsoft Office 2008 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=2c4d0381-f7ab-49ed-a0c0-b381387d1e68)  
(KB2644354)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office для Mac 2011
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office для Mac 2011](http://www.microsoft.com/downloads/details.aspx?familyid=3c8017d6-232c-42a6-a133-96efe3ad3385)  
(KB2644347)  
(существенный)
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
</tr>
<tr>
<th colspan="6">
Прочие программы Microsoft Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-088**](http://go.microsoft.com/fwlink/?linkid=227070)
</td>
<td style="border:1px solid black;">
[**MS11-089**](http://go.microsoft.com/fwlink/?linkid=225739)
</td>
<td style="border:1px solid black;">
[**MS11-091**](http://go.microsoft.com/fwlink/?linkid=235287)
</td>
<td style="border:1px solid black;">
[**MS11-094**](http://go.microsoft.com/fwlink/?linkid=232493)
</td>
<td style="border:1px solid black;">
[**MS11-096**](http://go.microsoft.com/fwlink/?linkid=232696)
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
Средство просмотра Microsoft PowerPoint 2007 с пакетом обновления 2 (SP2)
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
[Средство просмотра Microsoft PowerPoint 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4417592a-8db0-4e35-9895-d589bc341077)  
(KB2596912)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007 с пакетом обновления 2 (SP2)
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
[Пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e799f654-7e2d-40c7-a3b8-32e44d1aa6ee)  
(KB2596843)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 и Microsoft Office Pinyin New Experience Style 2010 (32-разрядная версия)
</td>
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 и Microsoft Office Pinyin New Experience Style 2010 (32-разрядная версия)<sup>[1]</sup>
(существенный)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 и Microsoft Office Pinyin New Experience Style 2010 (64-разрядная версия)
</td>
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 и Microsoft Office Pinyin New Experience Style 2010 (64-разрядная версия)<sup>[1]</sup>
(существенный)
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
</tr>
</table>
 
**Примечание для MS11-088**

<sup>[1]</sup>Эта версия Microsoft Office Pinyin больше не поддерживается.

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

-   Компанию Symantec и компанию Laboratory of Cryptography and System Security (CrySyS) за совместную работу над уязвимостью, описанной в MS11-087
-   Янь Янбея (Yang Yanbei) за сообщение об уязвимости, описанной в MS11-088
-   Никиту Тараканова (CISS Research Team) и Алексея Синцова (Digital Security Research Group), сотрудничающих с [TippingPoint](http://www.tippingpoint.com/) в рамках инициативы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS11-089
-   Анонимного исследователя, сотрудничающего с [VeriSign iDefense Labs](http://labs.idefense.com), за сообщение об уязвимости, описанной в MS11-090
-   Уилла Дормана (Will Dormann) из [CERT/CC](http://www.cert.org/) за сообщение о трех уязвимостях, описанных в MS11-091
-   Анонимного исследователя, сотрудничающего с [VeriSign iDefense Labs](http://labs.idefense.com), за сообщение об уязвимости, описанной в MS11-092
-   Анонимного исследователя, сотрудничающего с [VeriSign iDefense Labs](http://labs.idefense.com), за сообщение об уязвимости, описанной в MS11-093
-   Грега МакМануса (Greg MacManus) из компании [iSIGHT Partners Labs](http://www.isightpartners.com/) за сообщение об уязвимости, описанной в MS11-094
-   Анонимного исследователя, сотрудничающего с компанией [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS11-094
-   Анонимного исследователя, сотрудничающего с [VeriSign iDefense Labs](http://labs.idefense.com), за сообщение об уязвимости, описанной в MS11-096
-   Алекса Ионеску (Alex Ionescu) из компании Winsider Seminars & Solutions Inc. за сообщение о проблеме, описанной в бюллетене MS11-097
-   Мэтью Юрчика (Matthew Jurczyk), работающего с [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости, описанной в MS11-098
-   Томаса Штеле (Thomas Stehle) за сообщение об уязвимости, описанной в MS11-099
-   Энди Купера (Andy Cooper) из [Отдела безопасности Citrix](http://www.citrix.com) за сообщение об уязвимости, описанной в MS11-099
-   [Роберта Свецки (Robert Swiecki)](http://www.swiecki.net/) из [Google Inc.](http://www.google.com/) за сообщение об уязвимости, описанной в MS11-099
-   [Йосукэ Хасэгаву (Yosuke Hasegawa)](http://utf-8.jp/) за совместную работу над уязвимостью, описанной в MS11-099
-   [Яна Шейбала (Jan Schejbal)](http://janschejbal.wordpress.com/) за совместную работу над изменениями для обеспечения многоуровневой защиты, включенными в MS11-099
-   Ирен Абезгауз (Irene Abezgauz) из компании [Seeker](http://www.seekersec.com) за сообщение об уязвимости, описанной в MS11-100
-   Кестутиса Гудинавичюса (Kestutis Gudinavicius) из компании[SEC Consult](https://www.sec-consult.com/) за сообщение об уязвимости, описанной в MS11-100
-   Оливера Дьюдни (Oliver Dewdney) из агентства [LBi](http://www.lbi.com/) за сообщение об уязвимости, описанной в MS11-100

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Пользователи из США и Канады могут обратиться в службу [поддержки по вопросам безопасности](http://go.microsoft.com/fwlink/?linkid=21131) или позвонить по телефону 1-866-PCSAFETY (1-866-727-2338). Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Дополнительные сведения о вариантах поддержки см. на веб-странице [справки и поддержки корпорации Майкрософт](http://support.microsoft.com/).
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите веб-страницу [международной справки и поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (13 декабря 2011): Обзор бюллетеней опубликован.
-   Вер. 1.1 (13 декабря 2011): Для MS11-099 исправлены уровни серьезности в таблице "Подвержены уязвимости". Для MS11-088 исправлено важное примечание в разделе "Индекс использования уязвимостей". Все изменения носят исключительно информационный характер. Оно не вносит изменения в файлы обновления для системы безопасности или процедуру обнаружения.
-   Вер. 2.0 (29 декабря 2011 г.): Добавлен бюллетень по безопасности Microsoft MS11-100, уязвимости в .NET Framework делают возможным несанкционированное получение прав (2638420). а также ссылка на сведения о веб-трансляции, посвященной внеплановому бюллетеню по безопасности.
-   Вер. 2.1 (22 февраля 2012): Для MS11-088 добавлено объяснение состояния поддержки продуктов Microsoft Office Pinyin SimpleFast Style 2010 и Microsoft Office Pinyin New Experience Style 2010. Срок поддержки этих версий Microsoft Office Pinyin истек. Подробнее см. в бюллетене.

*Built at 2014-04-18T01:50:00Z-07:00*
