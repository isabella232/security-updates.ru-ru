---
TOCTitle: 'MS11-AUG'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за август 2011 г.'
ms:assetid: 'ms11-aug'
ms:contentKeyID: 61236144
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms11-aug(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за август 2011 г.
===============================================================

Дата публикации: 9 августа 2011 г. | Дата обновления: 26 октября 2011 г.

**Версия:** 1.2

В этом обзоре перечислены бюллетени по безопасности, выпущенные в августе 2011 г.

После выпуска бюллетеней за август 2011 г. этот обзор заменит предварительное уведомление, выпущенное 4 августа 2011 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

10 августа 2011 г. в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проводит веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в августовской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?culture=en-us&eventid=1032487857). После наступления этой даты данная веб-трансляция будет доступна по запросу. Дополнительные сведения см. на веб-узле [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://go.microsoft.com/fwlink/?linkid=217214) (на английском языке).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление безопасности для браузера Internet Explorer (2559049)</strong><br />
<br />
Данное обновление для системы безопасности устраняет пять обнаруженных пользователями уязвимостей и две опубликованных уязвимости в браузере Internet Explorer. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь просмотрит особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся любой из этих уязвимостей, может получить те же права, которыми обладает локальный пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221812">MS11-058</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в сервере DNS делают возможным удаленное выполнение кода (2562485)</strong><br />
<br />
Это обновление для системы безопасности устраняет две обнаруженные пользователями уязвимости в DNS-сервере Windows. Наиболее опасная из этих уязвимостей делает возможным удаленное выполнение кода в том случае, если злоумышленник регистрирует домен, создает запись ресурса NAPTR DNS, а затем посылает особым образом созданный запрос NAPTR на целевой DNS-сервер. Сервера, на которых роль DNS не включена, не подвержены данной уязвимости.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221539">MS11-059</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в компонентах доступа к данным MDAC делает возможным удаленное выполнение кода (2560656)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость делает возможным удаленное выполнение кода при условии, что пользователь откроет подлинный файл Excel (например, .xlsx), расположенный в том же сетевом каталоге, что и особым образом созданный файл библиотеки. Злоумышленник, воспользовавшийся этой уязвимостью, может получить те же права, что и вошедший в систему пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223425">MS11-060</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Visio делают возможным удаленное выполнение кода (2560978)</strong><br />
<br />
Это обновление для системы безопасности устраняет две обнаруженные пользователями уязвимости в Microsoft Visio. Эти уязвимости делают возможным удаленное выполнение кода при открытии пользователем особым образом созданного файла Visio. Злоумышленник, воспользовавшийся этой уязвимостью, может получить те же права, что и вошедший в систему пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217099">MS11-061</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в службе веб-подключения к удаленному рабочему столу делает возможным несанкционированное получение прав (2546250)</strong><br />
<br />
Данное обновление для системы безопасности устраняет обнаруженную пользователями уязвимость службы веб-подключения к удаленному рабочему столу. Это уязвимость межузловых сценариев (XSS), которая делает возможным несанкционированное получение прав, позволяя злоумышленнику выполнить произвольные команды на веб-сайте в контексте целевого пользователя. Фильтр XSS в Internet Explorer 8 и Internet Explorer 9 предотвращает такую атаку при переходе на сервер в зоне &quot;Интернет&quot; через веб-подключение к удаленному рабочему столу . Фильтр XSS в Internet Explorer 8 и Internet Explorer 9 по умолчанию не включен в зоне &quot;интрасеть&quot;.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223669">MS11-062</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в драйвере службы удаленного доступа NDISTAPI делает возможным несанкционированное получение прав</strong> <strong>(2566454)</strong><br />
<br />
Настоящее обновление для системы безопасности устраняет обнаруженную пользователями уязвимость во всех поддерживаемых выпусках Windows XP и Windows Server 2003. Уровень важности этого обновления определен как &quot;существенный&quot; для всех выпусков Windows XP и Windows Server 2003. Операционные системы Windows Vista, Windows Server 2008, Windows 7 и Windows Server 2008 R2 не подвержены данной уязвимости.<br />
<br />
Уязвимость делает возможным несанкционированное получение прав, если злоумышленник вошел в уязвимую систему и запустил специально созданное приложение, разработанное для использования данной уязвимости и получения полного контроля над уязвимой системой. Чтобы воспользоваться этой уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221864">MS11-063</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в подсистеме исполнения клиент-сервер Windows делает возможным несанкционированное получение прав (2567680)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Уязвимость делает возможным несанкционированное получение прав, если злоумышленник вошел в уязвимую систему и запустил специально созданное приложение, разработанное для отправки сообщения о событии, связанном с устройством, процессу с более высоким уровнем целостности. Чтобы воспользоваться этой уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221808">MS11-064</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в стеке TCP/IP могут привести к отказу в обслуживании (2563894)</strong><br />
<br />
Это обновление для системы безопасности устраняет две обнаруженных пользователями уязвимости в Microsoft Windows. Эти уязвимости могут привести к отказу в обслуживании, если злоумышленник посылает целевой системе последовательность специально созданных сообщений ICMP (Internet Control Message Protocol) или отправляет специально созданный запрос URL на сервер, который обслуживает веб-контент и у которого включена функция качества обслуживания (QoS) на основе URL-адресов.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221880">MS11-065</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в протоколе удаленного рабочего стола делает возможным отказ в обслуживании (2570222)</strong><br />
<br />
Настоящее обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в протоколе удаленного рабочего стола. Уязвимость делает возможным отказ от обслуживания, если уязвимая система получает последовательность специально созданных пакетов RDP. В корпорацию Майкрософт также поступили отчеты об ограниченном количестве целевых атак с использованием данной уязвимости. По умолчанию протокол удаленного рабочего стола (RDP) отключен во всех операционных системах Windows.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221536">MS11-066</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в элементе управления Microsoft Chart может привести к раскрытию информации (2567943)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в элементах управления ASP.NET Chart. Уязвимость делает возможным раскрытие информации, если злоумышленник посылает специально созданный запрос GET на уязвимый сервер, на котором размещены элементы управления Chart. Данная уязвимость не позволяет злоумышленнику выполнить код или напрямую повысить уровень своих пользовательских прав, но может быть использована для получения сведений, которые понадобятся для дальнейших атак на уязвимую систему. Данной уязвимости подвержены только веб-приложения, использующие элементы управления Microsoft Chart. Установки .NET Framework по умолчанию не подвержены данной уязвимости.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Раскрытие информации</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft .NET Framework,<br />
Средства разработки Microsoft</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223643">MS11-067</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в программе просмотра отчетов Microsoft Report Viewer может привести к раскрытию информации (2578230)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Report Viewer. Данная уязвимость может привести к раскрытию информации, если пользователь посетит специально созданный веб-сайт. В любом случае злоумышленник не может заставить пользователя посетить такой веб-сайт. Вместо этого злоумышленник должен убедить пользователя посетить вредоносный веб-сайт, обычно предлагая перейти на уязвимый веб-сайт по ссылке, содержащейся в сообщении электронной почты или запросе программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Раскрытие информации</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Средства разработки Microsoft</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223578">MS11-068</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в ядре Windows делает возможным атаку типа &quot;отказ в обслуживании&quot; (2556532)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным атаку типа &quot;отказ в обслуживании&quot;, если пользователь посетит общий сетевой ресурс (или веб-сайт со ссылкой на общий сетевой ресурс), содержащий специально созданный файл. В любом случае злоумышленник не может заставить пользователей посетить такой веб-сайт или общий сетевой ресурс. Вместо этого злоумышленнику нужно убедить пользователей посетить такой веб-сайт или общий сетевой ресурс; обычно ловушка принимает форму перехода по ссылке, содержащейся в электронном письме или мгновенном сообщении.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Средний</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221537">MS11-069</a></td>
<td style="border:1px solid black;"><strong>Уязвимость .NET Framework, приводящая к утечке информации (2567951)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость Microsoft .NET Framework. Уязвимость приводит к утечке информации в случае, если пользователь просмотрит специально созданную страницу в браузере, который поддерживает запуск браузерных приложений XAML. В случае атаки через Интернет злоумышленник может разместить в сети веб-сайт, содержащий веб-страницу, предназначенную для использования данной уязвимости. Кроме того, веб-сайты, подвергшиеся атаке злоумышленников, равно как и веб-сайты, принимающие или размещающие пользовательские материалы, также могут иметь специальное содержимое, рассчитанное на использование данной уязвимости. Однако в любом случае злоумышленник не может заставить пользователей посетить эти веб-сайты. Вместо этого злоумышленник попытается убедить пользователей посетить веб-сайт, обычно приглашая их щелкнуть соответствующую ссылку, ведущую на этот веб-сайт, в сообщении электронной почты или в запросе программы обмена мгновенными сообщениями. Данная уязвимость могла использоваться приложениями Windows .NET для обхода ограничений разграничения доступа кода (CAS).</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Средний</a><br />
Раскрытие информации</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft .NET Framework</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;">Уязвимость окна, приводящая к состоянию гонки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1257">CVE-2011-1257</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;">Уязвимость обработчиков событий, приводящая к раскрытию информации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1960">CVE-2011-1960</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;">Уязвимость обработчика Telnet, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1961">CVE-2011-1961</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;">Уязвимость XSLT, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1963">CVE-2011-1963</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td style="border:1px solid black;">Уязвимость объектов стиля, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1964">CVE-2011-1964</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221812">MS11-058</a></td>
<td style="border:1px solid black;">Уязвимость DNS, связанная с запросами NAPTR</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1966">CVE-2011-1966</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221812">MS11-058</a></td>
<td style="border:1px solid black;">Уязвимость DNS, связанная с повреждением неинициализированной памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1970">CVE-2011-1970</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость позволяет провести атаку типа &quot;отказ в обслуживании&quot;</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221539">MS11-059</a></td>
<td style="border:1px solid black;">Уязвимость компонентов Data Access, связанная с небезопасной загрузкой библиотек</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1975">CVE-2011-1975</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223425">MS11-060</a></td>
<td style="border:1px solid black;">Уязвимость в версии pStream, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1972">CVE-2011-1972</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223425">MS11-060</a></td>
<td style="border:1px solid black;">Уязвимость в Move Around the Block, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1979">CVE-2011-1979</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217099">MS11-061</a></td>
<td style="border:1px solid black;">Уязвимость в службе веб-подключения к удаленному рабочему столу</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1263">CVE-2011-1263</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223669">MS11-062</a></td>
<td style="border:1px solid black;">Уязвимость подсистемы NDISTAPI, приводящая к несанкционированному получению прав</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1974">CVE-2011-1974</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221864">MS11-063</a></td>
<td style="border:1px solid black;">Уязвимость подсистемы CSRSS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1967">CVE-2011-1967</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221808">MS11-064</a></td>
<td style="border:1px solid black;">Уязвимость в протоколе ICMP, приводящая к отказу от обслуживания</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1871">CVE-2011-1871</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость позволяет провести атаку типа &quot;отказ в обслуживании&quot;</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221808">MS11-064</a></td>
<td style="border:1px solid black;">Уязвимость в протоколе TCP/IP QOS, приводящая к отказу от обслуживания</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1965">CVE-2011-1965</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость позволяет провести атаку типа &quot;отказ в обслуживании&quot;</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221880">MS11-065</a></td>
<td style="border:1px solid black;">Уязвимость в протоколе удаленного рабочего стола</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1968">CVE-2011-1968</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Сообщается об ограниченных направленных атаках, использующих данную уязвимость<br />
<br />
Эта уязвимость позволяет провести атаку типа &quot;отказ в обслуживании&quot;</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=221536">MS11-066</a></td>
<td style="border:1px solid black;">Уязвимость в элементах управления Chart, приводящая к раскрытию информации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1977">CVE-2011-1977</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223643">MS11-067</a></td>
<td style="border:1px solid black;">Уязвимость элементов управления Report Viewer, связанная с XSS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1976">CVE-2011-1976</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации</td>
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
</tr>
<tr>
<th colspan="7">
ОС Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://go.microsoft.com/fwlink/?linkid=221864)
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
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=90312c78-1fbd-4143-b2e6-ae5c48af6f57)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a771c93b-55a4-456f-a315-d0d1f2696960)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5feb8ed7-99d2-4dd6-986f-57a7fd0c6f19)  
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
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=6bc1f0ac-223d-4b0b-86cd-2ba3863955c4)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=0231c103-c0cb-4705-9d92-5356b8cbb265)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=23d77f3b-13f8-49f3-9c3c-27ad217cd59e)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=acb14d82-a801-4ec7-84cc-9f131009ebcb)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=272c813b-bd39-4e63-9fa7-c5b8ed0b08d7)  
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
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d5ee6787-408d-4870-af70-9338158b161b)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=09276f6e-e3f4-4b7e-996e-4ec376c103e1)  
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
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://go.microsoft.com/fwlink/?linkid=221864)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий **уровень** опасности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=26b5fb48-346a-49f1-840f-03f218a41c20)  
(существенный)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=042552ad-f46a-4bfc-9e5c-58f095eba1de)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=648596fc-fd97-438a-97be-d5d590f1c561)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c2d4aa38-9241-465d-8d65-aba73e936d0f)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8de0f2db-aa09-48cd-a13b-e26a973e9cdc)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=870fdfdd-16bf-42a2-a23b-ed6045438d5e)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=9c3d14d8-6716-4423-91a9-a05373227237)  
(существенный)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=c9e283d8-d4a2-41e2-a73c-92fae957ba3d)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=470d56d1-5789-42cc-a088-a2c8ac934ab3)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2db4098a-f4f9-4211-b55d-5d0df1409c43)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8f208407-4bb3-41fe-b0d6-fc8a5e30e667)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=31af27b8-7b73-4090-94bd-2fb89d3970fc)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=64496a87-2225-402a-a94a-a8e92b17ac83)  
(существенный)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5aa3a493-4188-48a9-a549-cf9ba01ed32a)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1934acfa-5637-4ae9-9e9a-fc7e58930b7a)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ef140089-d022-4ee8-9cc4-7fb25295a39d)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=410c72d8-3b78-4c4a-ad61-acb7f854ffc2)  
(существенный)
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista;
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://go.microsoft.com/fwlink/?linkid=221864)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=66ddc7ce-5280-494d-bb3c-dab06e27fb5c)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=a080f36e-c24f-40ac-bb40-b26cb31bcae3)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c82417ec-232f-4f84-ba2c-0ffad77e9bb5)  
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
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8f25ced5-ef86-4b9d-91fb-443c9a2c1458)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3f119902-8398-4814-8229-9eb9f0980e87)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=704c1c9c-d1c1-40cb-97a7-fbb1f195f9f8)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=a6ff7b27-bc21-4945-8b2e-757b6f83fa58)  
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
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d5b8ff09-237e-49f1-a566-e323ca11fbc3)  
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
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://go.microsoft.com/fwlink/?linkid=221864)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=da9c98d1-973c-44d9-aee5-f5c4a8e8c0e1)\*\*  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d65ae4cc-d82a-42da-829f-d9479e23b7a5)\*\*  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=70065bd0-7c97-4ffc-828f-2cc245d04429)\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ac2d5122-6f9b-46f5-9840-77aa7ff84308)\*  
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
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1fbaabb9-8601-4760-813d-aeedfdcafb8b)\*  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=9facff69-618f-4a64-8665-5dd6cde07de9)\*\*  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=00f28d81-3714-403c-bcd7-55f2ac97f75b)\*\*  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=9ce60689-ca85-4c9f-af96-a73b1e43c10b)\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5f605f6f-3854-403d-878b-637626aef78f)\*  
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
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2e7253d8-fdc7-4563-9714-21ca3c77e4b1)\*  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=01885624-cfb1-4918-abef-ab0ea765cb04)  
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
[Windows Server 2008 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=fe37eb6d-b1fa-496c-a0d3-19a6d35a6cb9)  
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
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://go.microsoft.com/fwlink/?linkid=221864)
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
Нет
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
Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7019de24-8c58-4565-ada1-ca8755115096)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=12292081-23f7-4968-8cd7-17aaef2aed6a)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=6bc168d9-6664-41fb-914f-dbd7514a4b0e)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=f4551b77-eb09-448a-9dc5-66de846035e7)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=fcdb872f-2ee2-4f74-b7ae-1b82daf66761)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=ef664114-6582-49d3-b332-078a7d075337)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=aafeff2d-db9a-4b3b-b620-be4ec5f5bdcc)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=0fc9a501-523d-4cbb-8d99-a773089afc4c)  
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
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-057**](http://go.microsoft.com/fwlink/?linkid=221946)
</td>
<td style="border:1px solid black;">
[**MS11-058**](http://go.microsoft.com/fwlink/?linkid=221812)
</td>
<td style="border:1px solid black;">
[**MS11-059**](http://go.microsoft.com/fwlink/?linkid=221539)
</td>
<td style="border:1px solid black;">
[**MS11-061**](http://go.microsoft.com/fwlink/?linkid=217099)
</td>
<td style="border:1px solid black;">
[**MS11-062**](http://go.microsoft.com/fwlink/?linkid=223669)
</td>
<td style="border:1px solid black;">
[**MS11-063**](http://go.microsoft.com/fwlink/?linkid=221864)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=14fe68eb-2aa6-4a59-b9d8-deeae5236af2)\*\*  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=dd709da2-4cb1-482f-88eb-dfab4d3c59c6)\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=6a86e2cf-4e7d-4012-88c3-6957a3842dd3)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c29deec3-4672-4658-a550-dce244434cd4)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновлений 1 (SP 1)](http://www.microsoft.com/downloads/details.aspx?familyid=777f3bbe-094c-411d-879d-34a5a20ae7f3)\*\*  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=2f4043df-c07c-4611-b06a-7fcbb7416e7d)\*  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=82403fd3-ed75-4ea8-aa3f-ed9dda75612a)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1d6b8036-d38f-408a-a36c-027553faefc1)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b420cae3-de30-4c6c-8ed9-7431ad7ab4da)  
(существенный)
</td>
</tr>
</table>
 
**Примечания для Windows Server 2008 и Windows Server 2008 R2**

**\*Системы, при развертывании которых устанавливалось только ядро сервера, подвержены уязвимости.** Это обновление (с одинаковым уровнем серьезности) применяется к указанным выше поддерживаемым выпускам Windows Server 2008 или Windows Server 2008 R2 независимо от наличия установленных основных компонентов сервера. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Уязвимости не подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Поддерживаемые выпуски Windows Server 2008 или Windows Server 2008 R2, при развертывании которых выбиралась установка только ядра сервера, не подвержены уязвимостям, устраняемым этим обновлением. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

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
</tr>
<tr>
<th colspan="6">
ОС Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://go.microsoft.com/fwlink/?linkid=221537)
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=c07e1630-43ba-491e-bd59-9eb53105986c)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(средний)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(средний)
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
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=797a01dc-39fb-4511-832a-42d2975133f5)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(средний)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(средний)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://go.microsoft.com/fwlink/?linkid=221537)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
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
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=694ba1a6-7512-497d-a572-646a6e07b13b)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(средний)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(средний)
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
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=308da543-d49d-4591-8bbc-d65c524bb0ad)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(средний)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(средний)
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
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3b459bf0-7844-4740-895c-d149d56e781f)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(средний)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(средний)
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista;
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://go.microsoft.com/fwlink/?linkid=221537)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Совокупный уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=114c2835-921a-4d3e-be91-dfd217fd26a9)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=9713b7b8-f260-440d-a994-845f17683fe9)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)  
(KB2539633)  
(средний)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0fcee476-8d7e-49a7-b6ea-89043304a653)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4d67ec00-e86a-49b6-a9a2-85b2520fa4bb)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)  
(KB2539633)  
(средний)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(средний)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://go.microsoft.com/fwlink/?linkid=221537)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Совокупный уровень серьезности**
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c01d9132-af5f-4039-8195-95f6761f2d0e)\*  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)\*\*<sup>[1]</sup>
(KB2487367)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=da219735-b8b7-4f97-b8a8-7c253838de6b)\*\*\*  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)\*\*  
(KB2539633)  
(средний)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)\*\*<sup>[1]</sup>
(KB2539636)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=70797adb-d693-4102-9e7c-ba1ea8fb07d0)\*  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)\*\*<sup>[1]</sup>
(KB2487367)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для компьютеров на базе x64-процессоров с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8e077af5-5823-4377-a997-44b022a694d8)\*\*\*  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)\*\*  
(KB2539633)  
(средний)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)\*\*<sup>[1]</sup>
(KB2539636)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=9babf81a-8b21-42ae-a65c-f414793516ab)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=560efa6f-c956-47cb-a2f4-a1f45278b7cd)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)  
(KB2539633)  
(средний)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(средний)
</td>
</tr>
<tr>
<th colspan="6">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://go.microsoft.com/fwlink/?linkid=221537)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Совокупный уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=814bbdfa-7cbc-40e5-8ca3-8fed9d13ff00)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=6c8dd72b-abf8-4e1f-aafc-777c1a3ef3db)  
(средний)
</td>
<td style="border:1px solid black;">
Только Windows 7 для 32-разрядных систем:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)  
(KB2539634)  
(средний)  
Только Windows 7 для 32-разрядных систем:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(средний)  
Только для Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1):  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b)  
(KB2539635)  
(средний)  
Только для Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1):  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=085ee785-b6ad-4c68-835a-e17bc8f12a53)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d90c07c1-3c07-4989-825c-fb8453541a0e)  
(средний)
</td>
<td style="border:1px solid black;">
Только Windows 7 для 64-разрядных систем:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)  
(KB2539634)  
(средний)  
Только Windows 7 для 64-разрядных систем:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(средний)  
Только для Windows 7 для 64-разрядных систем с пакетом обновления 1 (SP1):  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b)  
(KB2539635)  
(средний)  
Только для Windows 7 для 64-разрядных систем с пакетом обновления 1 (SP1):  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(средний)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-064**](http://go.microsoft.com/fwlink/?linkid=221808)
</td>
<td style="border:1px solid black;">
[**MS11-065**](http://go.microsoft.com/fwlink/?linkid=221880)
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-068**](http://go.microsoft.com/fwlink/?linkid=223578)
</td>
<td style="border:1px solid black;">
[**MS11-069**](http://go.microsoft.com/fwlink/?linkid=221537)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Совокупный уровень серьезности**
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=9fd2b4ba-d98e-4ad6-99f2-c471335042d3)\*  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Только Windows Server 2008 R2 для 64-разрядных систем:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(существенный)  
Только для Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1):  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)\*<sup>[1]</sup>
(KB2487367)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=67cccd09-5b82-4546-884a-d2a9e2400820)\*\*\*  
(средний)
</td>
<td style="border:1px solid black;">
Только Windows Server 2008 R2 для 64-разрядных систем:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)\*  
(KB2539634)  
(средний)  
Только Windows Server 2008 R2 для 64-разрядных систем:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(средний)  
Только для Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1):  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b)\*  
(KB2539635)  
(средний)  
Только для Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1):  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)\*<sup>[1]</sup>
(KB2539636)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=93752c8f-5461-4e6f-9cab-6401b985ef17)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=a1edf843-9a2a-4334-a95f-78e75a9b3ef1)  
(средний)
</td>
<td style="border:1px solid black;">
Только для Windows Server 2008 R2 for Itanium-based Systems:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)  
(KB2539634)  
(средний)  
Только для Windows Server 2008 R2 for Itanium-based Systems:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(средний)  
Только для Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1):  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b)  
(KB2539635)  
(средний)  
Только для Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1):  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(средний)
</td>
</tr>
</table>
 
**Примечания для Windows Server 2008 и Windows Server 2008 R2**

**\*Системы, при развертывании которых устанавливалось только ядро сервера, подвержены уязвимости.** Это обновление (с одинаковым уровнем серьезности) применяется к указанным выше поддерживаемым выпускам Windows Server 2008 или Windows Server 2008 R2 независимо от наличия установленных основных компонентов сервера. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Уязвимости не подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Поддерживаемые выпуски Windows Server 2008 или Windows Server 2008 R2, при развертывании которых выбиралась установка только ядра сервера, не подвержены уязвимостям, устраняемым этим обновлением. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*\*Системы, при развертывании которых устанавливалось только ядро сервера, не подвержены этой уязвимости.** Уязвимость, устраняемая этим обновлением, не затрагивает поддерживаемые выпуски Windows Server 2008 или Windows Server 2008 R2 (согласно указаниям), при развертывании которых выбиралась установка основных компонентов, хотя уязвимые файлы могут находиться в системе. Однако пользователям, в системе которых находятся уязвимые файлы, предлагается установить это обновление, поскольку оно содержит файлы более поздних версий. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Примечания к MS11-066**

<sup>[1]</sup>**Клиентский профиль .NET Framework 4 не подвержен уязвимости.** Предлагаются два профиля для распространяемых пакетов .NET Framework версии 4: .NET Framework 4 и клиентский профиль .NET Framework 4. Клиентский профиль .NET Framework 4 является подмножеством .NET Framework 4. Уязвимости, устраняемой данным обновлением, подвержена только платформа .NET Framework 4, но не клиентский профиль .NET Framework 4. Дополнительные сведения см. в статье MSDN [Установка .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

**Примечание для MS11-069**

<sup>[1]</sup>**Уязвимости подвержены NET Framework 4 и клиентский профиль .NET Framework 4** Предлагаются два профиля для распространяемых пакетов .NET Framework версии 4: .NET Framework 4 и клиентский профиль .NET Framework 4. Клиентский профиль .NET Framework 4 является частью .NET Framework 4. Уязвимости, устраняемой данным обновлением, подвержены как платформа .NET Framework 4, так и клиентский профиль .NET Framework 4. Дополнительные сведения см. в статье MSDN [Установка .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Наборы приложений и прочие программные продукты Office

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Visio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-060**](http://go.microsoft.com/fwlink/?linkid=223425)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Совокупный уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=866d64b3-7147-4b5f-80fe-4d3317f140df)  
(KB2553009)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Visio 2007 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a0eeabde-5a92-45ae-aef6-81b7bdb4e0cd)  
(KB2553010)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2010 и Microsoft Visio 2010 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 и Microsoft Visio 2010 с пакетом обновления 1 (SP1) (32-разрядные выпуски)](http://www.microsoft.com/downloads/details.aspx?familyid=6da236c2-0ef5-4c13-8393-673b70298a77)  
(KB2553008)  
(существенный)  
[Microsoft Visio 2010 и Microsoft Visio 2010 с пакетом обновления 1 (SP1) (64-разрядные выпуски)](http://www.microsoft.com/downloads/details.aspx?familyid=b7f5f2a9-116a-41ef-a19e-a7dd0947d2cb)  
(KB2553008)  
(существенный)
</td>
</tr>
</table>
 

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
Chart Control
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-067**](http://go.microsoft.com/fwlink/?linkid=223643)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Совокупный уровень серьезности**
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
Элементы управления Chart для Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Элементы управления Chart для Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=8a80cc03-0db9-4446-9ce6-159ad02cab52)  
(KB2500170)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Visual Studio и средство просмотра файлов Microsoft Report
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-066**](http://go.microsoft.com/fwlink/?linkid=221536)
</td>
<td style="border:1px solid black;">
[**MS11-067**](http://go.microsoft.com/fwlink/?linkid=223643)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Совокупный уровень серьезности**
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
[Microsoft Visual Studio 2005 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=59231988-5413-4238-a3aa-32a127871430)  
(KB2548826)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Распространяемый пакет Microsoft Report Viewer 2005 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Распространяемый пакет Microsoft Report Viewer 2005 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=28bf2ae0-9e21-4201-b7f1-a207abc2866f)  
(KB2579115)  
(существенный)
</td>
</tr>
</table>
 
**Примечание для MS11-066**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

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

-   Юнгве Н. Петтерсена (Yngve N. Pettersen) из [Opera Software ASA](http://www.opera.com/security/) за сообщение об уязвимости, описанной в MS11-057
-   Группу [Lostmon Lords](http://lostmon.blogspot.com/) за сообщение об уязвимости, описанной в MS11-057
-   Макото Сиоцуки (Makoto Shiotsuki) из [Security Professionals Network Inc.](http://www.sec-pro.net/) за сообщение об уязвимости, описанной в MS11-057
-   Анонимного исследователя, сотрудничающего с компанией [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS11-057
-   Стивена Фьюера (Stephen Fewer) из [Harmony Security](http://www.harmonysecurity.com/), сотрудничающего с компанией [Tipping Point](http://www.tippingpoint.com/) в рамках инициативы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о двух уязвимостях, описанных в MS11-057
-   Михаля Залевского (Michal Zalewski) из [Google Inc.](http://www.google.com/) за совместную работу над изменениями для обеспечения многоуровневой защиты, содержащимися в бюллетене ms11-057
-   Гришу Ценгеля (Grischa Zengel) из компании [Zengel Medizintechnik GmbH](http://www.zmt.info/) за сообщение об уязвимости, описанной в MS11-058
-   Линлин Джао (Linlin Zhao) из [Отдела безопасности Baidu](http://www.baidu.com) за сообщение о двух уязвимостях, описанных в MS11-060
-   Свена Таута (Sven Taute) за сообщение о проблеме, описанной в бюллетене MS11-061
-   Люфенг Ли (Lufeng Li) из компании за сообщение об уязвимости, описанной в MS11-062
-   Алекса Ионеску (Alex Ionescu) из компании Winsider Seminars & Solutions Inc. за сообщение о проблеме, описанной в бюллетене MS11-063
-   Нико Лайдекера (Nico Leidecker) и Джеймся Форшо из Context Information Security за сообщение о проблеме, описанной в бюллетене MS11-066
-   Адама Биксби (Adam Bixby) из [Gotham Digital Science](http://www.gdssecurity.com/) за сообщение об уязвимости, описанной в MS11-067
-   Чжэнь Венбина (Zheng Wenbin) из [Qihoo 360 Security Center](http://www.360.cn/) за сообщение об уязвимости, описанной в MS11-068
-   Майкла Дж. Лю (Michael J. Liu) за сообщение о проблеме, описанной в бюллетене MS11-069

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Пользователи из США и Канады могут обратиться в службу [поддержки по вопросам безопасности](http://go.microsoft.com/fwlink/?linkid=21131) или позвонить по телефону 1-866-PCSAFETY. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Дополнительные сведения о вариантах поддержки см. на веб-странице [справки и поддержки корпорации Майкрософт](http://support.microsoft.com/).
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите веб-страницу [международной справки и поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (9 августа 2011): Обзор бюллетеней опубликован.
-   Вер. 1.1 (10 августа 2011): Для MS11-059 в разделе **Аннотации** исправлено требование перезагрузки. Для MS11-065 в **Индексе использования уязвимостей** исправлено краткое примечание для CVE-2011-1968. Для MS11-068 исправление указание "Уязвимости не подвержены системы, при развертывании которых устанавливалось только ядро сервера" для Windows Server 2008 и Windows Server 2008 R2.
-   Вер. 1.2 (26 октября 2011): Для MS11-066 и MS11-069 исправлена информация об уязвимости систем, при развертывании которых устанавливалось только ядро сервера, для .NET Framework 4 в ОС Windows Server 2008 R2 для 64-разрядных систем.

*Built at 2014-04-18T01:50:00Z-07:00*
