---
TOCTitle: 'MS11-JUN'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за июнь 2011 г.'
ms:assetid: 'ms11-jun'
ms:contentKeyID: 61236149
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms11-jun(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за июнь 2011 г.
=============================================================

Дата публикации: 14 июня 2011 г. | Дата обновления: 18 января 2012 г.

**Версия:** 3.1

В этом обзоре перечислены бюллетени по безопасности, выпущенные в июне 2011 г.

После выпуска бюллетеней по безопасности за июнь 2011 г. данный обзор заменит предварительное уведомление, выпущенное 9 июня 2011 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

15 июня 2011 г. в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в июньской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032455073&eventcategory=4). После наступления этой даты данная веб-трансляция будет доступна по запросу. Дополнительные сведения см. на веб-сайте [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://go.microsoft.com/fwlink/?linkid=217214).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212284">MS11-038</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в OLE-автоматизации делает возможным удаленное выполнение кода (2476490)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в OLE-автоматизации Microsoft Windows. Эта уязвимость делает возможным удаленное выполнение кода, если пользователь посетит веб-сайт, содержащий специально созданное изображение WMF (Windows Metafile). В любом случае злоумышленник не может заставить пользователей посетить такой веб-сайт. Вместо этого злоумышленнику требуется убедить пользователей посетить вредоносный веб-сайт, обычно, предлагая перейти по ссылке в сообщении электронной почты или запросе программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212287">MS11-039</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в .NET Framework и Microsoft Silverlight делает возможным удаленное выполнение кода (2514842)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в платформах Microsoft .NET Framework и Microsoft Silverlight. Эта уязвимость делает возможным удаленное выполнение кода в клиентской системе, если пользователь просмотрит особым образом созданную веб-страницу в веб-браузере, который может выполнять приложения XAML для веб-браузера (XBAP). Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. Кроме того, эта уязвимость делает возможным удаленное выполнение кода на серверных системах, в которых запущены службы IIS, если на этом сервере разрешена обработка страниц ASP.NET и злоумышленнику удастся загрузить на сервер и выполнить особым образом созданные страницы ASP.NET (например, в службах размещения веб-сайтов). Данная уязвимость могла использоваться приложениями Windows .NET для обхода ограничений разграничения доступа кода (CAS).</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework,<br />
Microsoft Silverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217470">MS11-040</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в клиенте брандмауэра Threat Management Gateway делает возможным удаленное выполнение кода (2520426)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в клиенте Microsoft Forefront Threat Management Gateway (TMG) 2010 (раньше назывался клиент брандмауэра Microsoft Forefront Threat Management Gateway). Эта уязвимость делает возможным удаленное выполнение кода в том случае, если злоумышленник использовал клиентский компьютер для отправки определенных запросов на систему, в которой используется клиент брандмауэра TMG.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Forefront Threat Management Gateway</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217499">MS11-041</a></td>
<td style="border:1px solid black;"><strong>Уязвимость драйверов режима ядра Windows делает возможным удаленное выполнение кода (2525694)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным удаленное выполнение кода, если пользователь посетит общий сетевой ресурс (или веб-сайт со ссылкой на общий сетевой ресурс), содержащий специально созданный шрифт OpenType (OTF). В любом случае злоумышленник не может заставить пользователей посетить такой веб-сайт или общий сетевой ресурс. Вместо этого злоумышленнику требуется убедить пользователей посетить такой веб-сайт или общий сетевой ресурс, обычно предлагая перейти по ссылке в сообщении электронной почты или запросе программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=215838">MS11-042</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в распределенной файловой системе делают возможным удаленное выполнение кода (2535512)</strong><br />
<br />
Это обновление для системы безопасности устраняет две обнаруженные пользователями уязвимости в распределенной файловой системе Microsoft. Наиболее опасная из этих уязвимостей делает возможным удаленное выполнение кода в том случае, если злоумышленник отправил особым образом созданный DFS-ответ на инициированный клиентом DFS-запрос. Злоумышленник, успешно воспользовавшийся ею, может выполнить произвольный код и получить полный контроль над системой. Стандартные параметры конфигурации брандмауэра позволяют защитить сеть от атак из-за пределов корпоративной среды. Согласно лучшим методикам, на подключенных к Интернету системах рекомендуется держать открытыми лишь минимально необходимое количество портов.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=215841">MS11-043</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в SMB-клиенте делает возможным удаленное выполнение кода (2536276)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным удаленное выполнение кода, если злоумышленник отправит специально созданный SMB-ответ на инициированный клиентом SMB-запрос. Для использования этой уязвимости злоумышленник должен убедить пользователя инициировать SMB-соединение с вредоносным SMB-сервером.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=216436">MS11-044</a></td>
<td style="border:1px solid black;"><strong>Уязвимость платформы .NET Framework делает возможным удаленное выполнение кода (2538814)</strong><br />
<br />
Это обновление для системы безопасности устраняет опубликованную уязвимость Microsoft .NET Framework. Эта уязвимость делает возможным удаленное выполнение кода в клиентской системе, если пользователь просмотрит особым образом созданную веб-страницу в веб-браузере, который может выполнять приложения XAML для веб-браузера (XBAP). Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. Кроме того, эта уязвимость делает возможным удаленное выполнение кода на серверных системах, в которых запущены службы IIS, если на этом сервере разрешена обработка страниц ASP.NET и злоумышленнику удастся загрузить на сервер и выполнить особым образом созданные страницы ASP.NET (например, в службах размещения веб-сайтов). Данная уязвимость могла использоваться приложениями Windows .NET для обхода ограничений разграничения доступа кода (CAS).</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление безопасности для браузера Internet Explorer (2530548)</strong><br />
<br />
Это обновление для системы безопасности устраняет 11 обнаруженных пользователями уязвимостей в Internet Explorer. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь просмотрит особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся любой из этих уязвимостей, может получить те же права, которыми обладает локальный пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=218115">MS11-052</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в языке VML делает возможным удаленное выполнение кода (2544521)</strong><br />
<br />
Данное обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в реализации языка VML, предложенной корпорацией Майкрософт. Данное обновление для системы безопасности имеет уровень серьезности &quot;критический&quot; для браузеров Internet Explorer 6, Internet Explorer 7 и Internet Explorer 8, установленных на клиентских компьютерах Windows, и уровень серьезности &quot;средний&quot; для браузеров Internet Explorer 6, Internet Explorer 7 и Internet Explorer 8, установленных на серверах Windows. Браузер Internet Explorer 9 не подвержен данной уязвимости.<br />
<br />
Она делает возможным удаленное выполнение кода, если пользователь открывает специально созданную веб-страницу в браузере Internet Explorer. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217912">MS11-037</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в MHTML может привести к раскрытию информации (2544893)</strong><br />
<br />
Это обновление для системы безопасности устраняет опубликованную уязвимость в обработчике протокола MHTML в Microsoft Windows. Данная уязвимость может привести к раскрытию информации, если пользователь откроет специально созданный URL-адрес с веб-сайта злоумышленника. Злоумышленник требуется убедить пользователя посетить такой веб-сайт, обычно предлагая перейти по ссылке в сообщении электронной почты или запросе программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Раскрытие информации</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Excel делают возможным удаленное выполнение кода (2537146)</strong><br />
<br />
Это обновление безопасности устраняет восемь обнаруженных пользователями уязвимостей в Microsoft Office. Эти уязвимости делают возможным удаленное выполнение кода при открытии пользователем особым образом созданного файла Excel. Злоумышленник, успешно воспользовавшийся любой из этих уязвимостей, может получить те же права, которыми обладает вошедший в систему пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. Установка и настройка средства проверки файлов Office (OFV) для предотвращения открытия подозрительных файлов блокирует направления атак связанных с уязвимостями, описанными в CVE-2011-1272, CVE-2011-1273 и CVE-2011-1279.Приложение Microsoft Excel 2010 подвержено только уязвимости CVE-2011-1273, описанной в данном бюллетене. Автоматическое решение Microsoft Fix it (&quot;Отключение редактирования в режиме защищенного просмотра для Excel 2010&quot;), доступное в статье 2501584 базы знаний Майкрософт, блокирует направления атак, основанные на использовании уязвимости CVE-2011-1273.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217464">MS11-046</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в драйвере вспомогательной функции может привести к несанкционированному получению прав (2503665)</strong><br />
<br />
Это обновление для системы безопасности устраняет уязвимость в драйвере вспомогательной функции (AFD), о которой сообщалось в открытых источниках. Эта уязвимость делает возможным несанкционированное получение прав, если злоумышленник войдет в систему пользователя и запустит специально созданное приложение. Чтобы воспользоваться этой уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217468">MS11-047</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Hyper-V делает возможной атаку типа &quot;отказ в обслуживании&quot; (2525835)</strong><br />
<br />
Данное обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Windows Server 2008 Hyper-V и Windows Server 2008 R2 Hyper-V. Эта уязвимость делает возможным отказ в обслуживании, если прошедший проверку пользователь отправит особым образом созданный пакет в VMBus в одной из гостевых виртуальных машин, размещенных на сервере Hyper-V. Чтобы воспользоваться уязвимостью, злоумышленник должен обладать действительными учетными данными и иметь возможность отправить особым образом созданное содержимое с гостевой виртуальной машины. Данной уязвимостью не могут воспользоваться удаленные или анонимные пользователи.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=215840">MS11-048</a></td>
<td style="border:1px solid black;"><strong>Уязвимость сервера SMB делает возможной атаку типа &quot;отказ в обслуживании&quot; (2536275)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Она делает возможной атаку типа &quot;отказ в обслуживании&quot;, если злоумышленник создает специальный пакет SMB и отправляет его уязвимой системе. Лучшие методики использования брандмауэра и устанавливаемые по умолчанию стандартные конфигурации брандмауэра позволяют защитить сети от атак извне периметра корпоративной среды, основанных на использовании этих уязвимостей.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217077">MS11-049</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в редакторе Microsoft XML Editor делает возможным раскрытие информации (2543893)</strong><br />
<br />
Данное обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в редакторе Microsoft XML Editor. Данная уязвимость делает возможным раскрытие информации в том случае, если пользователь откроет специально созданный файл Web Service Discovery (.disco) в одном из уязвимых приложений, перечисленных в данном бюллетене. Данная уязвимость не позволяет злоумышленнику выполнить код или напрямую повысить уровень своих пользовательских прав, но может быть использована для получения сведений, которые понадобятся для дальнейших атак на уязвимую систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Раскрытие информации</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft SQL Server,<br />
Microsoft Visual Studio</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217101">MS11-051</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в службе регистрации сертификатов Active Directory через Интернет делает возможным несанкционированное получение прав (2518295)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в службах подачи заявок на сертификат Active Directory через Интернет. Это уязвимость межузловых сценариев (XSS), которая делает возможным несанкционированное получение прав, позволяя злоумышленнику выполнить произвольные команды на веб-сайте в контексте целевого пользователя. Для успешного использования этой уязвимости злоумышленнику необходимо отправить пользователю специально созданную ссылку и убедить его перейти по ней. В любом случае злоумышленник не может заставить пользователя посетить такой веб-сайт. Вместо этого злоумышленник должен убедить пользователя посетить вредоносный веб-сайт, обычно предлагая перейти на уязвимый веб-сайт по ссылке, содержащейся в сообщении электронной почты или запросе программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Индекс использования уязвимостей  
--------------------------------
  
<span></span>
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости сгруппированы по идентификаторам бюллетеней и затем по кодам CVE. Включены только уязвимости, которым в бюллетенях присвоен уровень серьезности "критический" или "существенный".
  
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать о вероятности появления эксплойтов для выполнения произвольного кода и DoS-атаки в течение 30 дней после выпуска бюллетеня по каждому из обновлений безопасности, которые необходимо установить. Чтобы назначить приоритеты развертывания, ознакомьтесь с приведенными ниже оценками в соответствии с вашей конфигурацией. Дополнительные сведения об уровнях опасности и способах их определения см. в [индексе использования уязвимостей](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
В приведенной ниже таблице "последний выпуск программного обеспечения" обозначает соответствующее программное обеспечение, а термином "старые выпуски программного обеспечения" обозначены все прежние поддерживаемые выпуски программного обеспечения, указанные в таблице "Подвержены уязвимости" или "Не подвержены уязвимости" в этом бюллетене.

 
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Идентификатор бюллетеня</th>
<th style="border:1px solid black;" >Название уязвимости</th>
<th style="border:1px solid black;" >Код CVE</th>
<th style="border:1px solid black;" >Оценка использования уязвимостей при выполнении кода для последнего выпуска программного обеспечения</th>
<th style="border:1px solid black;" >Оценка использования уязвимостей при выполнении кода для старых выпусков программного обеспечения</th>
<th style="border:1px solid black;" >Оценка использования уязвимости типа &quot;отказ в обслуживании&quot;</th>
<th style="border:1px solid black;" >Краткие примечания</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217912">MS11-037</a></td>
<td style="border:1px solid black;">Уязвимость запросов MHTML формата MIME</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1894">CVE-2011-1894</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.<br />
<br />
Это уязвимость, делающая возможным раскрытие информации</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212284">MS11-038</a></td>
<td style="border:1px solid black;">Уязвимость OLE-автоматизации, связанная с потерей значимости</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0658">CVE-2011-0658</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212287">MS11-039</a></td>
<td style="border:1px solid black;">Уязвимость смещения массива .NET Framework</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0664">CVE-2011-0664</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217470">MS11-040</a></td>
<td style="border:1px solid black;">Уязвимость клиента брандмауэра TMG, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1889">CVE-2011-1889</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217499">MS11-041</a></td>
<td style="border:1px solid black;">Уязвимость проверки шрифтов OTF Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1873">CVE-2011-1873</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Возможно существование нестабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Возможно существование нестабильного кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=215838">MS11-042</a></td>
<td style="border:1px solid black;">Уязвимость DFS, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1868">CVE-2011-1868</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=215838">MS11-042</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с ответом на ссылки DFS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1869">CVE-2011-1869</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость позволяет провести атаку типа &quot;отказ в обслуживании&quot;</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=215841">MS11-043</a></td>
<td style="border:1px solid black;">Уязвимость анализа SMB-ответов</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1268">CVE-2011-1268</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=216436">MS11-044</a></td>
<td style="border:1px solid black;">Уязвимость оптимизации JIT-компилятора в .NET Framework</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1271">CVE-2011-1271</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Возможно существование нестабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Возможно существование нестабильного кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;">Уязвимость Excel, связанная с недостаточной проверкой записей</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1272">CVE-2011-1272</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;">Уязвимость Excel, связанная с неправильным анализом записей</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1273">CVE-2011-1273</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;">Уязвимость Excel, связанная с выходом за пределы массива</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1274">CVE-2011-1274</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Возможно существование нестабильного кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;">Уязвимость Excel, связанная с перезаписью памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1275">CVE-2011-1275</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Возможно существование нестабильного кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;">Уязвимость Excel, приводящая к переполнению буфера</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1276">CVE-2011-1276</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;">Уязвимость Excel, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1277">CVE-2011-1277</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;">Уязвимость WriteAV в Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1278">CVE-2011-1278</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;">Уязвимость Excel, связанная с выходом за пределы WriteAV</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1279">CVE-2011-1279</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217464">MS11-046</a></td>
<td style="border:1px solid black;">Уязвимость драйвера вспомогательной функции, приводящая к несанкционированному получению прав</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1249">CVE-2011-1249</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.<br />
<br />
Эта уязвимость может приводить к несанкционированному получению прав.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217468">MS11-047</a></td>
<td style="border:1px solid black;">Уязвимость VMBus, делающая возможной персистентную DoS-атаку</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1872">CVE-2011-1872</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">Эта уязвимость позволяет провести атаку типа &quot;отказ в обслуживании&quot;</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=215840">MS11-048</a></td>
<td style="border:1px solid black;">Уязвимость обработки запросов SMB</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1267">CVE-2011-1267</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость позволяет провести атаку типа &quot;отказ в обслуживании&quot;</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217077">MS11-049</a></td>
<td style="border:1px solid black;">Уязвимость разрешения внешних сущностей XML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1280">CVE-2011-1280</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Уязвимость обработки свойств ссылок, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1250">CVE-2011-1250</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Возможно существование нестабильного кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Уязвимость манипулирования DOM, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1251">CVE-2011-1251</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Уязвимость toStaticHTML, приводящая к раскрытию информации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1252">CVE-2011-1252</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Уязвимость операции перетаскивания, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1254">CVE-2011-1254</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Уязвимость элементов времени, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1255">CVE-2011-1255</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Уязвимость модификации DOM, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1256">CVE-2011-1256</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Возможно существование нестабильного кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Уязвимость макета, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1260">CVE-2011-1260</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Уязвимость выделенных объектов, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1261">CVE-2011-1261</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Уязвимость перенаправления HTTP, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1262">CVE-2011-1262</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Возможно существование нестабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217101">MS11-051</a></td>
<td style="border:1px solid black;">Уязвимость службы регистрации сертификатов Active Directory</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1264">CVE-2011-1264</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Эта уязвимость может приводить к несанкционированному получению прав.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=218115">MS11-052</a></td>
<td style="border:1px solid black;">Уязвимость VML, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1266">CVE-2011-1266</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
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
  
**Таблица 1**

 
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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="8">
ОС Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-038**](http://go.microsoft.com/fwlink/?linkid=212284)
</td>
<td style="border:1px solid black;">
[**MS11-039**](http://go.microsoft.com/fwlink/?linkid=212287)
</td>
<td style="border:1px solid black;">
[**MS11-041**](http://go.microsoft.com/fwlink/?linkid=217499)
</td>
<td style="border:1px solid black;">
[**MS11-042**](http://go.microsoft.com/fwlink/?linkid=215838)
</td>
<td style="border:1px solid black;">
[**MS11-043**](http://go.microsoft.com/fwlink/?linkid=215841)
</td>
<td style="border:1px solid black;">
[**MS11-044**](http://go.microsoft.com/fwlink/?linkid=216436)
</td>
<td style="border:1px solid black;">
[**MS11-050**](http://go.microsoft.com/fwlink/?linkid=217212)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=2371079f-fb20-4fd5-999e-e73f3701818c)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f)  
(KB2478656)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125)  
(KB2478658)  
(критический)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=67a25abd-f43c-4b01-b507-a109b739238f)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=492310d3-bbb4-4fff-b5fe-3470c17e7681)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d)  
(KB2530095)  
(критический)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(критический)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=26ec66af-9727-4423-90da-012ed5b30856)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4203a59a-a809-45db-a234-fef0ff5063f9)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4a49ec89-2a8f-41d9-8f0b-ee57fdf21f50)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b53d6631-4ded-48f5-a503-925b89b322b2)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f)  
(KB2478656)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125)  
(KB2478658)  
(критический)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=035d5115-54b6-41d3-b9f0-890041ead178)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=af6b7627-c462-45fe-8948-70da37e60659)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e10a4c3c-2ef8-4cfc-ac9b-4d97bfa79ac1)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d)  
(KB2530095)  
(критический)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(критический)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=f6e05fef-ee8c-44ff-a106-d7b8659c8d91)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=9fc734db-a177-43d2-a74a-b1fe6ea6f779)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4e4e18a4-97dc-4c5e-a078-8466913aa29e)  
(критический)
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
[**MS11-038**](http://go.microsoft.com/fwlink/?linkid=212284)
</td>
<td style="border:1px solid black;">
[**MS11-039**](http://go.microsoft.com/fwlink/?linkid=212287)
</td>
<td style="border:1px solid black;">
[**MS11-041**](http://go.microsoft.com/fwlink/?linkid=217499)
</td>
<td style="border:1px solid black;">
[**MS11-042**](http://go.microsoft.com/fwlink/?linkid=215838)
</td>
<td style="border:1px solid black;">
[**MS11-043**](http://go.microsoft.com/fwlink/?linkid=215841)
</td>
<td style="border:1px solid black;">
[**MS11-044**](http://go.microsoft.com/fwlink/?linkid=216436)
</td>
<td style="border:1px solid black;">
[**MS11-050**](http://go.microsoft.com/fwlink/?linkid=217212)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7e6ff410-4552-4687-81ab-83d9c91f8af5)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f)  
(KB2478656)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125)  
(KB2478658)  
(критический)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3aa8f1bc-07de-451a-8244-1733247e6f2e)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2719e0fb-3cfd-47b2-906d-3e07b0e3c978)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d)  
(KB2530095)  
(критический)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(критический)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=638f6dd6-bea0-4356-b23a-45e865a6b28b)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a3bd0012-4a45-4f96-8a51-3ff1f85d1e37)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=19557984-5088-44cc-b5ba-9bab33df8e7e)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=9c1a539f-1472-4394-8354-bd549d8332e0)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f)  
(KB2478656)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125)  
(KB2478658)  
(критический)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4aa8c003-0353-4a5b-8aea-c01a103af393)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e9018258-5a72-47a1-8584-3d1aa52317c3)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c962531e-f580-4195-989b-cf348cc96fa7)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d)  
(KB2530095)  
(критический)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(критический)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=ce616970-343d-49f1-994d-4269b9a11448)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=70ece3b4-e5bb-469c-bfef-c8310681f5a7)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c92d94c5-5e8f-45aa-a24a-f4d0efd93732)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c194dd35-b9db-44a5-a252-38f9f803802f)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f)  
(KB2478656)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125)  
(KB2478658)  
(критический)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2e07b5fa-c9fa-495b-9352-c07ce46a7e8b)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=96309c49-4822-4c47-b364-2ba65327cac5)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ea18a916-03cf-4eac-bacc-ceb006491f24)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d)  
(KB2530095)  
(критический)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(критический)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=f58ebc9e-00e1-413c-8076-d7a44003d0c7)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=80231a27-b37c-4101-a34f-19a26a040836)  
(критический)
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
[**MS11-038**](http://go.microsoft.com/fwlink/?linkid=212284)
</td>
<td style="border:1px solid black;">
[**MS11-039**](http://go.microsoft.com/fwlink/?linkid=212287)
</td>
<td style="border:1px solid black;">
[**MS11-041**](http://go.microsoft.com/fwlink/?linkid=217499)
</td>
<td style="border:1px solid black;">
[**MS11-042**](http://go.microsoft.com/fwlink/?linkid=215838)
</td>
<td style="border:1px solid black;">
[**MS11-043**](http://go.microsoft.com/fwlink/?linkid=215841)
</td>
<td style="border:1px solid black;">
[**MS11-044**](http://go.microsoft.com/fwlink/?linkid=216436)
</td>
<td style="border:1px solid black;">
[**MS11-050**](http://go.microsoft.com/fwlink/?linkid=217212)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=f33c9e54-c2e5-498d-a798-5bbfe9e4249c)  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows Vista с пакетом обновления 1 (SP1): [Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1) и Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9)  
(KB2478657)  
(критический)  
Только Windows Vista с пакетом обновления 1 (SP1): [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390)  
(KB2478659)  
(критический)  
Только Windows Vista с пакетом обновления 2 (SP2): [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b)  
(KB2478660)  
(критический)  
Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=aded8f20-479d-40c1-9560-c0581c6f77a2)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a62edfd8-9016-4bb5-bf48-885498fa0042)  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows Vista с пакетом обновления 1 (SP1): [Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)  
(KB2518863)  
(Уровень опасности не определен<sup>[2]</sup>)  
Только Windows Vista с пакетом обновления 1 (SP1): [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)  
(KB2518865)  
(Уровень опасности не определен<sup>[2]</sup>)  
Только Windows Vista с пакетом обновления 1 (SP1): [Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)  
(KB2518863)  
(критический)  
Только Windows Vista с пакетом обновления 1 (SP1): [Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)  
(KB2518865)  
(критический)  
Только Windows Vista с пакетом обновления 2 (SP2): [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)  
(KB2518866)  
(Уровень опасности не определен<sup>[2]</sup>)  
Только Windows Vista с пакетом обновления 2 (SP2): [Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)  
(KB2518866)  
(критический)  
Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=fea735a8-032b-4fa6-8337-1fa411df0b88)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4cddfc68-eff6-4587-8607-63307d039489)  
(критический)  
Только Windows Vista с пакетом обновления 2 (SP2): [Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=392316fc-f531-469c-aa60-4ecf061a5354)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4566528f-62ee-4d78-b3af-131a7cc15e1f)  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows Vista x64 Edition с пакетом обновления 1 (SP1) [Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1) и Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9)  
(KB2478657)  
(критический)  
Только Windows Vista x64 Edition с пакетом обновления 1 (SP1) [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390)  
(KB2478659)  
(критический)  
Только Windows Vista x64 Edition с пакетом обновления 2 (SP2) [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b)  
(KB2478660)  
(критический)  
Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a519a5d7-bfe3-4e53-99e9-d85f7e34237f)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=962cb40c-680c-4c37-98d4-ca9789ca7270)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=cb561ba6-af4d-40cc-947c-923f9cca9a7e)  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows Vista x64 Edition с пакетом обновления 1 (SP1) [Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)  
(KB2518863)  
(Уровень опасности не определен<sup>[2]</sup>)  
Только Windows Vista x64 Edition с пакетом обновления 1 (SP1) [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)  
(KB2518865)  
(Уровень опасности не определен<sup>[2]</sup>)  
Только Windows Vista x64 Edition с пакетом обновления 1 (SP1) [Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)  
(KB2518863)  
(критический)  
Только Windows Vista x64 Edition с пакетом обновления 1 (SP1) [Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)  
(KB2518865)  
(критический)  
Только Windows Vista x64 Edition с пакетом обновления 2 (SP2) [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)  
(KB2518866)  
(Уровень опасности не определен<sup>[2]</sup>)  
Только Windows Vista x64 Edition с пакетом обновления 2 (SP2) [Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)  
(KB2518866)  
(критический)  
Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=49dcb47b-3c79-4f69-ba07-f471304c16e2)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e0a8fbac-2c31-4cf8-9967-6171edabd560)  
(критический)  
Только Windows Vista x64 Edition с пакетом обновления 2 (SP2) [Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=44b2aa73-c318-47ac-ad87-0d24afd9cdd7)  
(критический)
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
[**MS11-038**](http://go.microsoft.com/fwlink/?linkid=212284)
</td>
<td style="border:1px solid black;">
[**MS11-039**](http://go.microsoft.com/fwlink/?linkid=212287)
</td>
<td style="border:1px solid black;">
[**MS11-041**](http://go.microsoft.com/fwlink/?linkid=217499)
</td>
<td style="border:1px solid black;">
[**MS11-042**](http://go.microsoft.com/fwlink/?linkid=215838)
</td>
<td style="border:1px solid black;">
[**MS11-043**](http://go.microsoft.com/fwlink/?linkid=215841)
</td>
<td style="border:1px solid black;">
[**MS11-044**](http://go.microsoft.com/fwlink/?linkid=216436)
</td>
<td style="border:1px solid black;">
[**MS11-050**](http://go.microsoft.com/fwlink/?linkid=217212)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0c9614d9-6f61-463d-b1fa-bd5eb2c1a5c5)\*\*  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows Server 2008 для 32-разрядных систем: [Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1) и Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9)\*\*  
(KB2478657)  
(критический)  
Только Windows Server 2008 для 32-разрядных систем: [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390)\*\*  
(KB2478659)  
(критический)  
Только Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2): [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b)\*\*  
(KB2478660)  
(критический)  
Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)\*\*<sup>[1]</sup>
(KB2478663)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=8ebfa067-0236-4454-8605-df1b99742f90)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=8ab9679e-6a69-4ca3-9210-7ca4fb1980c2)\*  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows Server 2008 для 32-разрядных систем: [Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)\*\*  
(KB2518863)  
(Уровень опасности не определен<sup>[2]</sup>)  
Только Windows Server 2008 для 32-разрядных систем: [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)\*\*  
(KB2518865)  
(Уровень опасности не определен<sup>[2]</sup>)  
Только Windows Server 2008 для 32-разрядных систем: [Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)\*\*  
(KB2518863)  
(критический)  
Только Windows Server 2008 для 32-разрядных систем: [Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)\*\*  
(KB2518865)  
(критический)  
Только Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2): [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)\*\*  
(KB2518866)  
(критический)  
Только Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2): [Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)\*\*  
(KB2518866)  
(критический)  
Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)\*\*<sup>[1]</sup>
(KB2518870)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b6547ff0-b059-495d-8816-bb094ac11be7)\*\*  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c9650c47-ac52-433d-b409-ce1cfe8d3e87)\*\*  
(критический)  
Только Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2): [Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7f9b1ba2-8247-494b-990c-f62003188c5a)\*\*  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем и Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=36698775-0e4e-4980-ae4c-43542de424ca)\*\*  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows Server 2008 для 64-разрядных систем: [Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1) и Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9)\*\*  
(KB2478657)  
(критический)  
Только Windows Server 2008 для 64-разрядных систем: [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390)\*\*  
(KB2478659)  
(критический)  
Только Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2): [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b)\*\*  
(KB2478660)  
(критический)  
Windows Server 2008 для 64-разрядных систем и Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)\*\*<sup>[1]</sup>
(KB2478663)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=cd8f3713-b408-4db6-aecd-7eed2176a715)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=f1d76b82-9996-4d08-894b-9c16a4b3bb1e)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=22c63fc3-2c5a-4e50-9026-2e04a6e74210)\*  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows Server 2008 для 64-разрядных систем: [Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)\*\*  
(KB2518863)  
(Уровень опасности не определен<sup>[2]</sup>)  
Только Windows Server 2008 для 64-разрядных систем: [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)\*\*  
(KB2518865)  
(Уровень опасности не определен<sup>[2]</sup>)  
Только Windows Server 2008 для 64-разрядных систем: [Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)\*\*  
(KB2518863)  
(критический)  
Только Windows Server 2008 для 64-разрядных систем: [Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)\*\*  
(KB2518865)  
(критический)  
Только Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2): [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)\*\*  
(KB2518866)  
(критический)  
Только Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2): [Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)\*\*  
(KB2518866)  
(критический)  
Windows Server 2008 для 64-разрядных систем и Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)\*\*<sup>[1]</sup>
(KB2518870)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=feff3364-4bfd-45f5-99da-9192b47ef5d4)\*\*  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7dff9f08-19cb-41dd-a315-84c1dac81510)\*\*  
(критический)  
Только Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2): [Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=fdf88a52-c099-44eb-95a0-650129c0e678)\*\*  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3edb613f-5bf0-4e28-9835-4afbb6ef0e01)  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows Server 2008 for Itanium-based Systems: [Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1) и Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9)  
(KB2478657)  
(критический)  
Только Windows Server 2008 for Itanium-based Systems: [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390)  
(KB2478659)  
(критический)  
Только Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2): [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b)  
(KB2478660)  
(критический)  
Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5a61f888-c81e-4b8a-8932-2fe67df4b2ad)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=f80c89c6-27ab-4f6a-afad-9c8e92cbbce4)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5bb889de-8ff6-4587-8ef9-ffb13e8d60fd)  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows Server 2008 for Itanium-based Systems: [Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)  
(KB2518863)  
(Уровень опасности не определен<sup>[2]</sup>)  
Только Windows Server 2008 for Itanium-based Systems: [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)  
(KB2518865)  
(Уровень опасности не определен<sup>[2]</sup>)  
Только Windows Server 2008 for Itanium-based Systems: [Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)  
(KB2518863)  
(критический)  
Только Windows Server 2008 for Itanium-based Systems: [Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)  
(KB2518865)  
(критический)  
Только Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2): [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)  
(KB2518866)  
(критический)  
Только Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2): [Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)  
(KB2518866)  
(критический)  
Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d81a9219-da95-4fbf-af7f-898f553b0572)  
(критический)
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
[**MS11-038**](http://go.microsoft.com/fwlink/?linkid=212284)
</td>
<td style="border:1px solid black;">
[**MS11-039**](http://go.microsoft.com/fwlink/?linkid=212287)
</td>
<td style="border:1px solid black;">
[**MS11-041**](http://go.microsoft.com/fwlink/?linkid=217499)
</td>
<td style="border:1px solid black;">
[**MS11-042**](http://go.microsoft.com/fwlink/?linkid=215838)
</td>
<td style="border:1px solid black;">
[**MS11-043**](http://go.microsoft.com/fwlink/?linkid=215841)
</td>
<td style="border:1px solid black;">
[**MS11-044**](http://go.microsoft.com/fwlink/?linkid=216436)
</td>
<td style="border:1px solid black;">
[**MS11-050**](http://go.microsoft.com/fwlink/?linkid=217212)
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
Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=50ae36ff-2406-48a4-97cc-12782b6d30ac)  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows 7 для 32-разрядных систем: [Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=9720a317-ca4c-4a47-b99c-2c66301e62c6)  
(KB2478661)  
(критический)  
Только для Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1): [Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=c8152a18-0367-4c00-a3c7-669325a899f4)  
(KB2478662)  
(критический)  
Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=9de1bf5d-6f25-496d-bc44-a32c5e8920fe)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=19a15098-1754-4536-a9ca-ff07d16464b7)  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows 7 для 32-разрядных систем: [Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=bff13134-ed84-4370-beb4-340c340a5d98)  
(KB2518867)  
(критический)  
Только для Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1): [Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=dab623bf-d23d-42a9-9e74-ae75d779b980)  
(KB2518869)  
(критический)  
Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=91b98f02-a09e-48f1-9f78-a949f7268542)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=79f846da-3b17-43c9-9016-a055c2c56975)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1241f0f8-a5c7-420a-a5b7-b6c3caa9e5e2)  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows 7 для 64-разрядных систем: [Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=9720a317-ca4c-4a47-b99c-2c66301e62c6)  
(KB2478661)  
(критический)  
Только для Windows 7 для 64-разрядных систем с пакетом обновления 1 (SP1): [Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=c8152a18-0367-4c00-a3c7-669325a899f4)  
(KB2478662)  
(критический)  
Windows 7 для 64-разрядных систем и Windows 7 для 64-разрядных систем с пакетом обновления 1 (SP1): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=e7f52b13-5b3d-438c-ae14-86da50c8b67a)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=50d1c677-57aa-4e3f-bdfc-6f01b5d3bfe2)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b449f23e-b3df-46e5-bfe3-98268d20ad54)  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows 7 для 64-разрядных систем: [Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=bff13134-ed84-4370-beb4-340c340a5d98)  
(KB2518867)  
(критический)  
Только для Windows 7 для 64-разрядных систем с пакетом обновления 1 (SP1): [Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=dab623bf-d23d-42a9-9e74-ae75d779b980)  
(KB2518869)  
(критический)  
Windows 7 для 64-разрядных систем и Windows 7 для 64-разрядных систем с пакетом обновления 1 (SP1): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=264107cc-68b4-401c-82f7-de64b535c18d)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=e87a09f2-b755-48ef-9b85-fc78d0bfce43)  
(критический)
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
[**MS11-038**](http://go.microsoft.com/fwlink/?linkid=212284)
</td>
<td style="border:1px solid black;">
[**MS11-039**](http://go.microsoft.com/fwlink/?linkid=212287)
</td>
<td style="border:1px solid black;">
[**MS11-041**](http://go.microsoft.com/fwlink/?linkid=217499)
</td>
<td style="border:1px solid black;">
[**MS11-042**](http://go.microsoft.com/fwlink/?linkid=215838)
</td>
<td style="border:1px solid black;">
[**MS11-043**](http://go.microsoft.com/fwlink/?linkid=215841)
</td>
<td style="border:1px solid black;">
[**MS11-044**](http://go.microsoft.com/fwlink/?linkid=216436)
</td>
<td style="border:1px solid black;">
[**MS11-050**](http://go.microsoft.com/fwlink/?linkid=217212)
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
Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновлений 1 (SP 1)](http://www.microsoft.com/downloads/details.aspx?familyid=8181c359-cd79-438a-87be-093b363d0b04)\*\*  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows Server 2008 R2 для 64-разрядных систем: [Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=9720a317-ca4c-4a47-b99c-2c66301e62c6)\*  
(KB2478661)  
(критический)  
Только Windows Server 2008 R2 для 64-разрядных систем: [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(критический)  
Только для Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1): [Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=c8152a18-0367-4c00-a3c7-669325a899f4)\*  
(KB2478662)  
(критический)  
Только для Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)\*<sup>[1]</sup>
(KB2478663)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b77e5be6-d3eb-4e3a-9be2-831578f0447c)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=9d66b1e7-dbf9-4475-a973-49fb85557eca)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=06008192-3cac-477b-a913-83eed39d8718)\*  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows Server 2008 R2 для 64-разрядных систем: [Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=bff13134-ed84-4370-beb4-340c340a5d98)\*  
(KB2518867)  
(критический)  
Только Windows Server 2008 R2 для 64-разрядных систем: [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(критический)  
Только для Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1): [Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=dab623bf-d23d-42a9-9e74-ae75d779b980)\*  
(KB2518869)  
(критический)  
Только для Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)\*<sup>[1]</sup>
(KB2518870)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8b18e6f9-96b8-4dec-bcd0-d71f1bac3eb0)\*\*  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=81814b15-ebdf-4817-932b-5ea7a37fa6ed)\*\*  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=6b63a1eb-445a-4cd3-b357-9a1dd82d7a35)  
(критический)
</td>
<td style="border:1px solid black;">
Только для Windows Server 2008 R2 for Itanium-based Systems: [Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=9720a317-ca4c-4a47-b99c-2c66301e62c6)  
(KB2478661)  
(критический)  
Только для Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1): [Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=c8152a18-0367-4c00-a3c7-669325a899f4)  
(KB2478662)  
(критический)  
Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c00a33bc-c874-4693-b0f7-5034c5df9424)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=3c8455f1-b8a0-4ba2-84a2-043d25ef75c5)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=93a32bd9-7e67-4ace-8c45-116f91b032f9)  
(критический)
</td>
<td style="border:1px solid black;">
Только для Windows Server 2008 R2 for Itanium-based Systems: [Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=bff13134-ed84-4370-beb4-340c340a5d98)  
(KB2518867)  
(критический)  
Только для Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1): [Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=dab623bf-d23d-42a9-9e74-ae75d779b980)  
(KB2518869)  
(критический)  
Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1): [Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(критический)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ab2406a8-06f7-4f88-9af4-dc136d64bc35)  
(критический)
</td>
</tr>
</table>
 
**Примечания для Windows Server 2008 и Windows Server 2008 R2**

**\*Уязвимости подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Это обновление (с одинаковым уровнем серьезности) применяется к указанным выше поддерживаемым выпускам Windows Server 2008 или Windows Server 2008 R2 независимо от наличия установленных основных компонентов сервера. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Уязвимости не подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Поддерживаемые выпуски Windows Server 2008 или Windows Server 2008 R2, при развертывании которых выбиралась установка только ядра сервера, не подвержены уязвимостям, устраняемым этим обновлением. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Примечания для MS11-039**

<sup>[1]</sup>**Уязвимости подвержены NET Framework 4.0 и клиентский профиль .NET Framework 4.0** Предлагаются два профиля для распространяемых пакетов .NET Framework версии 4: .NET Framework 4.0 и клиентский профиль .NET Framework 4.0. Клиентский профиль .NET Framework 4.0 является частью .NET Framework 4.0. Уязвимости, устраняемой данным обновлением, подвержены как платформа .NET Framework 4.0, так и клиентский профиль .NET Framework 4.0. Дополнительные сведения см. в статье MSDN [Установка .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

**Примечания для MS11-044**

<sup>[1]</sup>**Уязвимости подвержены NET Framework 4.0 и клиентский профиль .NET Framework 4.0** Предлагаются два профиля для распространяемых пакетов .NET Framework версии 4: .NET Framework 4.0 и клиентский профиль .NET Framework 4.0. Клиентский профиль .NET Framework 4.0 является частью .NET Framework 4.0. Уязвимости, устраняемой данным обновлением, подвержены как платформа .NET Framework 4.0, так и клиентский профиль .NET Framework 4.0. Дополнительные сведения см. в статье MSDN [Установка .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

<sup>[2]</sup>Уровни серьезности неприменимы к этому обновлению, поскольку уязвимость, описанная в этом бюллетене, не затрагивает это программное обеспечение. Однако в качестве дополнительной меры защиты от возможных новых направлений атаки в будущем корпорация Майкрософт рекомендует пользователям этого программного обеспечения установить это обновление для системы безопасности.

**Таблица 2**

 
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
[**MS11-052**](http://go.microsoft.com/fwlink/?linkid=218115)
</td>
<td style="border:1px solid black;">
[**MS11-037**](http://go.microsoft.com/fwlink/?linkid=217912)
</td>
<td style="border:1px solid black;">
[**MS11-046**](http://go.microsoft.com/fwlink/?linkid=217464)
</td>
<td style="border:1px solid black;">
[**MS11-047**](http://go.microsoft.com/fwlink/?linkid=217468)
</td>
<td style="border:1px solid black;">
[**MS11-048**](http://go.microsoft.com/fwlink/?linkid=215840)
</td>
<td style="border:1px solid black;">
[**MS11-051**](http://go.microsoft.com/fwlink/?linkid=217101)
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
Нет
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=6c760c7f-94f1-437f-a645-fd33b50d03f4)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0b88f9e9-3439-44e5-92c8-66a3c97cb03d)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=03b45ad8-cc6b-473b-8112-bd513ed97f5d)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=ce5bc2d7-9438-4bf0-be5e-be9dd00c3286)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=a1db7736-f3e4-45df-af1d-52746978a0a8)  
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=c94c0d17-fdbe-41b3-a23d-98f43f907b89)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ff955dc3-58ca-40ea-b7f1-9ff40c37f997)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ed502ece-737e-44cb-84fd-8a0d1bc321c8)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7b211b02-a005-46a3-ad1d-d4baaeec8289)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=71497891-41a2-476d-b524-4eb5cecb9639)  
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
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-052**](http://go.microsoft.com/fwlink/?linkid=218115)
</td>
<td style="border:1px solid black;">
[**MS11-037**](http://go.microsoft.com/fwlink/?linkid=217912)
</td>
<td style="border:1px solid black;">
[**MS11-046**](http://go.microsoft.com/fwlink/?linkid=217464)
</td>
<td style="border:1px solid black;">
[**MS11-047**](http://go.microsoft.com/fwlink/?linkid=217468)
</td>
<td style="border:1px solid black;">
[**MS11-048**](http://go.microsoft.com/fwlink/?linkid=215840)
</td>
<td style="border:1px solid black;">
[**MS11-051**](http://go.microsoft.com/fwlink/?linkid=217101)
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
[**Низкий**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=5dafb455-969e-4be9-8735-d4ee0682d22f)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ba3beb80-a921-489e-a6ff-a7b2d665ada6)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=a8038325-0d14-445b-a5d9-ce7ac1fa44b5)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6427ea5d-05d0-4367-805c-9cb305802b3c)  
(низкий)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c614cb8b-223e-4f84-b94c-f15747760aa5)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ef90d6c1-ea7f-4c32-9c90-0303e04c7436)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=e78829d0-8215-4e56-8959-ebd3bc8e9a91)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3bec943e-5758-4439-a947-a8fafd30edec)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5f7bcbad-f647-4fbb-88d4-b19c54db6f00)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e7f65891-32c0-4817-b3b2-d8be73145df9)  
(низкий)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=9a951087-25c5-4f5c-8407-a1585491ae0b)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=62944095-33d6-4131-be32-a79d9ec4d4a9)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=1e822515-9f0a-4ef0-bb70-d4889d200f47)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=47a0fdc6-7576-4c32-b8fd-cbb05d57599d)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ca8b1d09-9f80-417b-99b1-8f86e86e1f11)  
(низкий)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=dd48b93b-24fa-45a3-91fb-9f9f9418c49f)  
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
<th colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-052**](http://go.microsoft.com/fwlink/?linkid=218115)
</td>
<td style="border:1px solid black;">
[**MS11-037**](http://go.microsoft.com/fwlink/?linkid=217912)
</td>
<td style="border:1px solid black;">
[**MS11-046**](http://go.microsoft.com/fwlink/?linkid=217464)
</td>
<td style="border:1px solid black;">
[**MS11-047**](http://go.microsoft.com/fwlink/?linkid=217468)
</td>
<td style="border:1px solid black;">
[**MS11-048**](http://go.microsoft.com/fwlink/?linkid=215840)
</td>
<td style="border:1px solid black;">
[**MS11-051**](http://go.microsoft.com/fwlink/?linkid=217101)
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
Нет
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e541f1bb-c9bf-4dc8-96ec-58a3de5ba7fd)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=cd059690-52b0-4b37-9fbb-d9906ae46fed)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ebea38a7-1fbe-4141-a529-52d7a7326d6a)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b69e3bda-940b-4524-a724-0af4ae0ec719)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5f0007c3-8d11-4940-8766-1112e3777aae)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6c7d7162-ef19-49f4-a8fc-5db7415445a4)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=256bb26f-df9e-4259-881b-e8313a9fafa8)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=54833350-a385-4a31-995a-9ddc38798c21)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e3a26bc5-1757-4b38-9cae-419c919f4877)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=fadf6f12-1f09-4d49-93b1-8fce01400b4f)  
(существенный)
</td>
<td style="border:1px solid black;">
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
[**MS11-052**](http://go.microsoft.com/fwlink/?linkid=218115)
</td>
<td style="border:1px solid black;">
[**MS11-037**](http://go.microsoft.com/fwlink/?linkid=217912)
</td>
<td style="border:1px solid black;">
[**MS11-046**](http://go.microsoft.com/fwlink/?linkid=217464)
</td>
<td style="border:1px solid black;">
[**MS11-047**](http://go.microsoft.com/fwlink/?linkid=217468)
</td>
<td style="border:1px solid black;">
[**MS11-048**](http://go.microsoft.com/fwlink/?linkid=215840)
</td>
<td style="border:1px solid black;">
[**MS11-051**](http://go.microsoft.com/fwlink/?linkid=217101)
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
[**Низкий**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4446121a-0aab-4fbc-ba74-68d7650e8bca)\*\*  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ed089de4-c9ec-4ac7-a711-5f7cb29c05bc)\*\*  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6a3bbd67-94db-40b2-8786-cb39a493ec92)\*\*  
(низкий)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=e34e4cf9-cdae-4240-8574-950c0be00822)\*  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=8960dd62-7cf7-41cb-97b2-b082bd1750aa)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=46ade106-e0cb-4c71-8230-793a15062823)\*\*  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем и Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=01399fc7-dc2b-461e-a1a5-751a3b61bde0)\*\*  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=dd32b7c6-daa1-47aa-807f-25a678790cf2)\*\*  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=4cb870f3-9878-4075-b8fd-2ee90c8e3bc8)\*\*  
(низкий)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=a3604f05-26b2-451b-9153-0e718158371e)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=24789423-72b7-48d1-bdc1-f0e5174d99bb)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=0abc6908-ac6a-4da3-843a-af6841ccc1db)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=6141a1c5-ecaf-4553-9d27-dd6e5c4a13fd)\*\*  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=16a8b78a-3979-4cc7-bbe5-6d962aa64336)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e1243011-00e6-49f2-a676-c04cb805d36a)  
(низкий)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e8a82b44-e1d8-45f8-b8b8-b1f74e1efce0)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=057f1356-9c70-4457-a1df-69334fdab467)  
(существенный)
</td>
<td style="border:1px solid black;">
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
[**MS11-052**](http://go.microsoft.com/fwlink/?linkid=218115)
</td>
<td style="border:1px solid black;">
[**MS11-037**](http://go.microsoft.com/fwlink/?linkid=217912)
</td>
<td style="border:1px solid black;">
[**MS11-046**](http://go.microsoft.com/fwlink/?linkid=217464)
</td>
<td style="border:1px solid black;">
[**MS11-047**](http://go.microsoft.com/fwlink/?linkid=217468)
</td>
<td style="border:1px solid black;">
[**MS11-048**](http://go.microsoft.com/fwlink/?linkid=215840)
</td>
<td style="border:1px solid black;">
[**MS11-051**](http://go.microsoft.com/fwlink/?linkid=217101)
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
Нет
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=27e767d8-84e3-434f-bb8d-3b2303774ad0)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c3647646-658a-423b-b0cb-bba7613b67e7)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=63d8b801-5178-474b-a21e-72a0ce501d3e)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=cf9e5ecd-68f7-4982-b4ed-be80859b757c)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=747ba56a-0d47-4946-99a4-bae1f11ea748)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=7996511d-4b8e-49c3-a0fa-4da907a6c947)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=cd7d3cb9-cb60-4b62-b0df-a38fe21802e9)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=2707650a-604c-4044-acc4-07a30b5640d8)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
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
[**MS11-052**](http://go.microsoft.com/fwlink/?linkid=218115)
</td>
<td style="border:1px solid black;">
[**MS11-037**](http://go.microsoft.com/fwlink/?linkid=217912)
</td>
<td style="border:1px solid black;">
[**MS11-046**](http://go.microsoft.com/fwlink/?linkid=217464)
</td>
<td style="border:1px solid black;">
[**MS11-047**](http://go.microsoft.com/fwlink/?linkid=217468)
</td>
<td style="border:1px solid black;">
[**MS11-048**](http://go.microsoft.com/fwlink/?linkid=215840)
</td>
<td style="border:1px solid black;">
[**MS11-051**](http://go.microsoft.com/fwlink/?linkid=217101)
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
[**Низкий**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=cff7f53d-0fd6-48f8-a9d6-bf19e0a32905)\*\*  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновлений 1 (SP 1)](http://www.microsoft.com/downloads/details.aspx?familyid=40354f73-4f4d-4a4a-abac-f8a3d4c3ae5f)\*\*  
(низкий)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=e67c73ca-d0f9-40c1-8b6e-25b1b13caa3a)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c9c6c36d-a455-42f7-b7d4-9fb9824c07cb)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=f9824310-772d-4e1e-980e-11e2db3ac53e)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновлений 1 (SP 1)](http://www.microsoft.com/downloads/details.aspx?familyid=1da04414-6210-43ea-8e0a-cf21cf144076)\*\*  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4dd2c0f4-b29c-4648-a123-83d3ae6a878f)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=22853823-8f63-4258-8991-1ad50e58a0d9)  
(низкий)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=72d1d6b6-e8bd-492b-b65a-82060beef441)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=0533d293-e186-4d39-a925-ab3d9ed46290)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 
**Примечание для Windows Server 2008 и Windows Server 2008 R2**

**\*Уязвимости подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Это обновление (с одинаковым уровнем серьезности) применяется к указанным выше поддерживаемым выпускам Windows Server 2008 или Windows Server 2008 R2 независимо от наличия установленных основных компонентов сервера. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Уязвимости не подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Поддерживаемые выпуски Windows Server 2008 или Windows Server 2008 R2, при развертывании которых выбиралась установка только ядра сервера, не подвержены уязвимостям, устраняемым этим обновлением. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Наборы приложений и прочие программные продукты Office

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
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
[**MS11-045**](http://go.microsoft.com/fwlink/?linkid=217502)
</td>
<td style="border:1px solid black;">
[**MS11-049**](http://go.microsoft.com/fwlink/?linkid=217077)
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
Microsoft Office XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2002 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=853c0663-94f7-4634-98ad-47ca4b1f7b1e)  
(KB2541003)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=f38f183a-9c64-406b-9bf6-807cb2d55e56)  
(KB2541025)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5b271f87-a279-419f-9437-ded224fa19f1)<sup>[1]</sup>
(KB2541007)  
(существенный)
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
[Microsoft Excel 2010 (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=baba7ec1-4a5e-4e13-9d0e-9085a39a0554)  
(KB2523021)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 (64-разрядные версии)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=d6e9f422-43b0-4da5-8356-c38482e8eebb)  
(KB2523021)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office для Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-045**](http://go.microsoft.com/fwlink/?linkid=217502)
</td>
<td style="border:1px solid black;">
[**MS11-049**](http://go.microsoft.com/fwlink/?linkid=217077)
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
Microsoft Office 2004 для Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=d12d0868-4f28-4c0a-ab61-338878064b70)  
(KB2555786)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 для Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=9e2d348b-c753-4eab-838c-370cd5af5e14)  
(KB2555785)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office для Mac 2011
</td>
<td style="border:1px solid black;">
[Microsoft Office для Mac 2011](http://www.microsoft.com/downloads/details.aspx?familyid=3c58555c-1eba-42fe-a10f-b30af9031e44)  
(KB2555784)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Конвертер форматов файлов Open XML для Mac
</td>
<td style="border:1px solid black;">
[Конвертер форматов файлов Open XML для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=6118d5f5-b6fd-4584-be25-209534772379)  
(KB2555787)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Microsoft InfoPath
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-045**](http://go.microsoft.com/fwlink/?linkid=217502)
</td>
<td style="border:1px solid black;">
[**MS11-049**](http://go.microsoft.com/fwlink/?linkid=217077)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2007 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=88eedb0b-a2cf-4a1b-b1b9-0b2926c25872)  
(KB2510061)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2010 (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=90ffe910-bd9c-48aa-8007-2b43e1a99999)  
(KB2510065)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2010 (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=f3244003-fb63-44d8-bedc-6399c39aacba)  
(KB2510065)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Другое программное обеспечение Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-045**](http://go.microsoft.com/fwlink/?linkid=217502)
</td>
<td style="border:1px solid black;">
[**MS11-049**](http://go.microsoft.com/fwlink/?linkid=217077)
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
Средство просмотра Microsoft Excel
</td>
<td style="border:1px solid black;">
[Средство просмотра Microsoft Excel с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=77c1e7e2-207f-46fd-81f2-43a25eddc010)  
(KB2541015)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3512a033-871d-49ec-a8d2-1b9c7dec4936)  
(KB2541012)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 
**Примечание для MS11-045**

<sup>[1]</sup>Для Microsoft Office Excel 2007 с пакетом обновления 2 (SP2): для обеспечения защиты от уязвимостей, описанных в данном бюллетене, пользователи должны помимо обновления безопасности KB2541007 установить обновление безопасности для пакета обеспечения совместимости форматов файлов Microsoft Office Word, Excel и PowerPoint 2007 с пакетом обновления 2 (SP2) (KB2541012).

**Примечание для MS11-049**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Серверное программное обеспечение Майкрософт

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
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
[**MS11-049**](http://go.microsoft.com/fwlink/?linkid=217077)
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
SQL Server 2005 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e)  
(KB2494113)  
(существенный)  
Обновление QFE:  
[SQL Server 2005 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867)  
(KB2494112)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 x64 Edition с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e)  
(KB2494113)  
(существенный)  
Обновление QFE:  
[SQL Server 2005 x64 Edition с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867)  
(KB2494112)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 для систем с процессорами Itanium с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 для систем с процессорами Itanium с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e)  
(KB2494113)  
(существенный)  
Обновление QFE:  
[SQL Server 2005 для систем с процессорами Itanium с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867)  
(KB2494112)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad)  
(KB2494120)  
(существенный)  
Обновление QFE:  
[SQL Server 2005 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57)  
(KB2494123)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 x64 Edition с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad)  
(KB2494120)  
(существенный)  
Обновление QFE:  
[SQL Server 2005 x64 Edition с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57)  
(KB2494123)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 для систем с процессорами Itanium с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 для систем с процессорами Itanium с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad)  
(KB2494120)  
(существенный)  
Обновление QFE:  
[SQL Server 2005 для систем с процессорами Itanium с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57)  
(KB2494123)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Express Edition с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 Express Edition с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e)  
(KB2494113)  
(существенный)  
Обновление QFE:  
[SQL Server 2005 Express Edition с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867)  
(KB2494112)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Express Edition с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 Express Edition с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad)  
(KB2494120)  
(существенный)  
Обновление QFE:  
[SQL Server 2005 Express Edition с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57)  
(KB2494123)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Express Edition с дополнительными службами и пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 Express Edition с дополнительными службами и пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e)  
(KB2494113)  
(существенный)  
Обновление QFE:  
[SQL Server 2005 Express Edition с дополнительными службами и пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867)  
(KB2494112)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Express Edition с дополнительными службами и пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 Express Edition с дополнительными службами и пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad)  
(KB2494120)  
(существенный)  
Обновление QFE:  
[SQL Server 2005 Express Edition с дополнительными службами и пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57)  
(KB2494123)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server Management Studio Express (SSMSE) 2005
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server Management Studio Express (SSMSE) 2005](http://www.microsoft.com/downloads/details.aspx?familyid=34c3ba21-b158-4e6d-82ba-831053d41161)  
(KB2546869)  
(существенный)  
Обновление QFE:  
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server Management Studio Express (SSMSE) 2005 x64 Edition
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server Management Studio Express (SSMSE) 2005 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=34c3ba21-b158-4e6d-82ba-831053d41161)  
(KB2546869)  
(существенный)  
Обновление QFE:  
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2008 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2008 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=ae7db514-d96b-4cff-a13d-c74f4cf8cf0c)<sup>[1]</sup>
(KB2494096)  
(существенный)  
Обновление QFE:  
[SQL Server 2008 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=312a39c4-cb32-4216-8672-1b1c0937ba6c)<sup>[1]</sup>
(KB2494100)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2008 для 64-разрядных (x64) систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2008 для 64-разрядных (x64) систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=ae7db514-d96b-4cff-a13d-c74f4cf8cf0c)<sup>[1]</sup>
(KB2494096)  
(существенный)  
Обновление QFE:  
[SQL Server 2008 для 64-разрядных (x64) систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=312a39c4-cb32-4216-8672-1b1c0937ba6c)<sup>[1]</sup>
(KB2494100)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2008 для систем с процессорами Itanium с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2008 для систем с процессорами Itanium с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=ae7db514-d96b-4cff-a13d-c74f4cf8cf0c)  
(KB2494096)  
(существенный)  
Обновление QFE:  
[SQL Server 2008 для систем с процессорами Itanium с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=312a39c4-cb32-4216-8672-1b1c0937ba6c)  
(KB2494100)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6f4767bf-257d-4822-b768-7b6702261276)<sup>[1]</sup>
(KB2494089)  
(существенный)  
Обновление QFE:  
[SQL Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=23240963-e2c6-4d40-8179-661117b53e91)<sup>[1]</sup>
(KB2494094)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2008 для 64-разрядных (x64) систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2008 для 64-разрядных (x64) систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6f4767bf-257d-4822-b768-7b6702261276)<sup>[1]</sup>
(KB2494089)  
(существенный)  
Обновление QFE:  
[SQL Server 2008 для 64-разрядных (x64) систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=23240963-e2c6-4d40-8179-661117b53e91)<sup>[1]</sup>
(KB2494094)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6f4767bf-257d-4822-b768-7b6702261276)  
(KB2494089)  
(существенный)  
Обновление QFE:  
[SQL Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=23240963-e2c6-4d40-8179-661117b53e91)  
(KB2494094)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2008 R2 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2008 R2 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=80e98567-1b28-49b1-a646-579f8c115a41)<sup>[1]</sup>
(KB2494088)  
(существенный)  
Обновление QFE:  
[SQL Server 2008 R2 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=9df95137-d1b3-4fac-8958-8042aa2010c4)<sup>[1]</sup>
(KB2494086)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2008 R2 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2008 R2 для 64-разрядных (x64) систем](http://www.microsoft.com/downloads/details.aspx?familyid=80e98567-1b28-49b1-a646-579f8c115a41)<sup>[1]</sup>
(KB2494088)  
(существенный)  
Обновление QFE:  
[SQL Server 2008 R2 для 64-разрядных (x64) систем](http://www.microsoft.com/downloads/details.aspx?familyid=9df95137-d1b3-4fac-8958-8042aa2010c4)<sup>[1]</sup>
(KB2494086)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=80e98567-1b28-49b1-a646-579f8c115a41)  
(KB2494088)  
(существенный)  
Обновление QFE:  
[SQL Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=9df95137-d1b3-4fac-8958-8042aa2010c4)  
(KB2494086)  
(существенный)
</td>
</tr>
</table>
 
**Примечания** **для MS11-049**

<sup>[1]</sup>Это обновление также относится к соответствующему экспресс-выпуску и экспресс-выпуску с дополнительными службами.

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Программное обеспечение и средства разработки Microsoft

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-039**](http://go.microsoft.com/fwlink/?linkid=212287)
</td>
<td style="border:1px solid black;">
[**MS11-049**](http://go.microsoft.com/fwlink/?linkid=217077)
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
Microsoft Silverlight 4
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 4](http://www.microsoft.com/downloads/details.aspx?familyid=2f71b104-b66f-4146-9d70-fcde766c91b8) в случае установки в ОС Mac  
(KB2512827)  
(критический)  
[Microsoft Silverlight 4](http://www.microsoft.com/downloads/details.aspx?familyid=2f71b104-b66f-4146-9d70-fcde766c91b8) в случае установки в любых выпусках клиентских систем Microsoft Windows  
(KB2512827)  
(критический)  
[Microsoft Silverlight 4](http://www.microsoft.com/downloads/details.aspx?familyid=2f71b104-b66f-4146-9d70-fcde766c91b8) во всех выпусках серверных систем Microsoft Windows\*\*  
(KB2512827)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Visual Studio
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-039**](http://go.microsoft.com/fwlink/?linkid=212287)
</td>
<td style="border:1px solid black;">
[**MS11-049**](http://go.microsoft.com/fwlink/?linkid=217077)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=e5ce8a9a-e89b-4095-9f21-7e6f307fbf2b)  
(KB2251481)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2008 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=cc01bce9-3f38-4590-9c6e-a4048c886d33)  
(KB2251487)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2010
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2010](http://www.microsoft.com/downloads/details.aspx?familyid=213b820f-dcba-4895-b339-b50eeb92524d)  
(KB2251489)  
(существенный)
</td>
</tr>
</table>
 
**Примечания для MS11-039**

**\*\*Уязвимости не подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Поддерживаемые выпуски Windows Server 2008 или Windows Server 2008 R2, при развертывании которых выбиралась установка только ядра сервера, не подвержены уязвимостям, устраняемым этим обновлением. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

**Примечание для MS11-049**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Программное обеспечение корпорации Майкрософт по безопасности

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Forefront
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-040**](http://go.microsoft.com/fwlink/?linkid=217470)
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
Клиент Microsoft Forefront Threat Management Gateway 2010
</td>
<td style="border:1px solid black;">
[Клиент Microsoft Forefront Threat Management Gateway 2010](http://www.microsoft.com/downloads/details.aspx?familyid=d1c85acd-a6df-4634-9cd4-c562ad92097e)  
(критический)
</td>
</tr>
</table>
 

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

-   Билли Риоса (Billy Rios) и Эдуардо Велу Наву (Eduardo Vela Nava) из [отдела безопасности Google](http://www.google.com/) за совместную работу над изменением бюллетеня MS11-037.
-   Ямату Ли (Yamata Li) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости, описанной в MS11-038
-   Майкла Дж. Лью (Michael J. Liu) за сообщение об уязвимости, описанной в бюллетене MS11-039
-   Коро (Koro) из [www.korosoft.net](http://www.korosoft.net/) за сообщение об уязвимости, описанной в MS11-041
-   Лорана Гаффье (Laurent Gaffié) из компании [NGS Software](http://www.ngssoftware.com/) за сообщение об уязвимости, описанной в MS11-042
-   Дэна Камински (Dan Kaminsky) за совместную работу по решению проблемы, описанной в бюллетене MS11-044
-   Бина Лю (Bing Liu) из отдела [FortiGuard Labs](http://www.fortiguard.com/) компании Fortinet за сообщение об уязвимости, описанной в MS11-045
-   Анонимного исследователя, сотрудничающего с [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости, описанной в MS11-045
-   Пользователя Omair, работающего с [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости, описанной в MS11-045
-   Анонимного исследователя, сотрудничающего с [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости, описанной в MS11-045
-   Никола Грегуара (Nicolas Gregoire) из [Agarri](http://www.agarri.fr/), работающего с [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости, описанной в MS11-045
-   Пользователя Omair за сообщение об уязвимости, описанной в MS11-045
-   Уилла Дормана (Will Dormann) из [CERT/CC](http://www.cert.org/) за сообщение о двух уязвимостях, описанных в MS11-045
-   Стивена Адэра (Steven Adair) из [Shadowserver Foundation](http://www.shadowserver.org) и Криса С. (Chris S.) за сообщение об уязвимости, описанной в ms11-046
-   Николаса Эконому (Nicolas Economou) из компании [Core Security Technologies](http://www.coresecurity.com/) за сообщение об уязвимости, описанной в MS11-047
-   Джесси Оу (Jesse Ou) из [Cigital](http://www.cigital.com) за сообщение об уязвимости, описанной в MS11-049
-   Роберта Свецки (Robert Swiecki) из [Google Inc.](http://www.google.com/) за сообщение об уязвимости, описанной в MS11-050
-   [Отдел безопасности компании NSFOCUS](http://www.nsfocus.com/) за сообщение об уязвимости, описанной в MS11-050
-   Анонимного исследователя, сотрудничающего в рамках программы [SecuriTeam Secure Disclosure компании Beyond Security](http://www.beyondsecurity.com/ssd.html), за сообщение об уязвимости, описанной в MS11-050
-   Ади Коэна (Adi Cohen) из [IBM Rational Application Security](http://blog.watchfire.com/) за сообщение об уязвимости, описанной в MS11-050
-   Компанию [Trend Micro](http://www.trendmicro.com/) за совместную работу над устранением проблемы, описанной в MS11-050
-   Нирмала Сингха Бхари (Nirmal Singh Bhary) из [Norman](http://www.norman.com) за сообщение об уязвимости, описанной в MS11-050
-   Анонимного исследователя, сотрудничающего с [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости, описанной в MS11-050
-   Дэмиэна Пата (Damian Put), работающего с [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS11-050
-   Йоела Глюка (Yoel Gluck), Йогеш Бадве (Yogesh Badwe) и Варуна Бадхвара (Varun Badhwar) из отдела безопасности продуктов [salesforce.com](http://www.salesforce.com/) за сообщение об уязвимости, описанной в MS11-050
-   Хосе Антонио Васкеса Гонсалеса (Jose Antonio Vazquez Gonzalez), работающего с [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS11-050
-   Анонимного исследователя, сотрудничающего с компанией [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в MS11-050
-   Питера Уинтер-Смита (Peter Winter-Smith), работающего с [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS11-050
-   Стивена Фьюера (Stephen Fewer) из [Harmony Security](http://www.harmonysecurity.com/), сотрудничающего с компанией [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за совместную работу над многоуровневой защитой от уязвимостей, описанных в бюллетене MS11-050
-   Руджеро Страблу (Ruggero Strabla), [Emaze Networks](http://www.emaze.net/); [отдел безопасности Saipem](http://www.saipem.com/) за сообщение об уязвимости, описанной в MS11-051
-   Анонимного исследователя, сотрудничающего с компанией [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS11-052

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Пользователи из США и Канады могут обратиться в службу [поддержки по вопросам безопасности](http://go.microsoft.com/fwlink/?linkid=21131) или позвонить по телефону 1-866-PCSAFETY. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Дополнительные сведения о вариантах поддержки см. на веб-странице [справки и поддержки корпорации Майкрософт](http://support.microsoft.com/).
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите веб-страницу [международной справки и поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (14 июня 2011): Обзор бюллетеней опубликован.
-   Вер. 1.1 (14 июня 2011): В бюллетене MS11-042 Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1), Windows 7 для 64-разрядных систем с пакетом обновления 1 (SP1), Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1) удалены из подраздела **Продукты, подверженные уязвимости, и соответствующие обновления**. Это изменение носит исключительно информационный характер. Оно не вносит изменения в файлы обновления для системы безопасности или процедуру обнаружения.
-   Вер. 2.0 (9 августа 2011): Повторно выпущен бюллетень MS11-043, чтобы повторно предложить обновление для всех поддерживаемых операционных систем для устранения проблемы стабильности. Пользователи, уже обновившие свои системы, должны повторно установить обновление MS11-043. Также повторно выпущен бюллетень MS11-049, в котором добавлено объявление об изменении логики обнаружения в обновлении для Microsoft Visual Studio 2005 с пакетом обновления 1 (SP1) для добавления обнаружения соответствующего программного обеспечения. В файлы обновления безопасности в MS11-049 изменений не вносилось. Пользователям, успешно обновившим свои системы, не нужно переустанавливать MS11-049.
-   Вер. 2.1 (26 октября 2011): Для MS11-039 и MS11-044 исправлена информация об уязвимости систем, при развертывании которых устанавливалось только ядро сервера, для .NET Framework 4 в ОС Windows Server 2008 R2 для 64-разрядных систем.
-   Вер. 3.0 (8 ноября 2011): Повторно выпущен бюллетень MS11-037, чтобы повторно предложить обновление для всех поддерживаемых выпусков Windows XP и Windows Server 2003. Пользователи, у которых установлены операционные системы Windows XP или Windows Server 2003 (в том числе и те пользователи, которые уже успешно установили исходное обновление от 14 июня 2011 г.), должны установить повторно предлагаемое обновление.
-   Вер. 3.1 (18 января 2012): В бюллетене MS11-049 в раздел "Продукты, подверженные уязвимости, и соответствующие обновления" добавлено пояснение, что данное обновление также относится к 32-разрядным и 64-разрядным (x64) выпускам SQL Server 2008 и SQL Server 2008 R2, включая экспресс-выпуск и экспресс-выпуск с дополнительными службами.

*Built at 2014-04-18T01:50:00Z-07:00*
