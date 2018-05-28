---
TOCTitle: 'MS08-DEC'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Декабрь 2008 г.'
ms:assetid: 'ms08-dec'
ms:contentKeyID: 61236111
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms08-dec(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Декабрь 2008 г.
==================================================================

Дата публикации: 9 декабря 2008 г. | Дата обновления: 29 апреля 2009 г.

**Версия:** 6,0

В этом обзоре описаны бюллетени по безопасности, выпущенные в декабре 2008 г.

После выпуска декабрьских бюллетеней этот обзор заменит предварительное уведомление, выпущенное 4 декабря 2008 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [Предварительное уведомление о бюллетенях по безопасности Microsoft](http://technet.microsoft.com/security/bulletin/advance) (на английском языке).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней по безопасности Microsoft, см. на веб-узле [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

10 декабря 2008 г., в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в ходе которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в декабрьской веб-трансляции, посвященной бюллетеням по безопасности](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374647). После наступления этой даты данная веб-трансляциия будет доступна по запросу. Дополнительные сведения см. на веб-узле [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://technet.microsoft.com/security/bulletin/summary) (на английском языке).

Корпорация Майкрософт проведет веб-трансляции, в которых ответит на вопросы пользователей о внеплановом бюллетене MS08-078, добавленном в версии 3.0 данного обзора бюллетеней. Сроки проведения веб-трансляций: 17 декабря 2008 г. в 13:00 по тихоокеанскому времени (для США и Канады) и 18 декабря 2008 г. в 11:00 по тихоокеанскому времени. Зарегистрируйтесь сейчас для участия в веб-трансляциях [17 декабря](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032399448&culture=en-us) и [18 декабря](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032399449&culture=en-us). Позже это можно будет сделать только по запросу. Дополнительные сведения см. на веб-узле [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://technet.microsoft.com/security/bulletin/summary) (на английском языке).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других важных обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел **Прочие сведения**.

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
<th style="border:1px solid black;" >Максимальный уровень опасности и воздействие уязвимости</th>
<th style="border:1px solid black;" >Необходимость перезагрузки</th>
<th style="border:1px solid black;" >Подвержены уязвимости</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125440">MS08-071</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в GDI делают возможным удаленное выполнение кода (956802)</strong><br />
<br />
Это обновление для системы безопасности устраняет две уязвимости в GDI, о которых сообщалось в частном порядке. Они делают возможным удаленное выполнение кода, если пользователь открывает специально созданный файл изображения в формате WMF. Воспользовавшись этими уязвимостями, злоумышленник может получить полный контроль над системой. что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132148">MS08-075</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в компоненте поиска Windows делают возможным удаленное выполнение кода (959349)</strong><br />
<br />
Это обновление для системы безопасности устраняет две уязвимости в компоненте поиска Windows, о которых сообщалось в частном порядке. Они делают возможным удаленное выполнение кода, если пользователь откроет и сохранит специально созданный файл поискового запроса в проводнике или щелкнет специально созданный URL-адрес страницы результатов поиска. Воспользовавшись этими уязвимостями, злоумышленник может получить полный контроль над системой. что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (958215)</strong><br />
<br />
Это критическое обновление для системы безопасности устраняет четыре уязвимости, о которых сообщалось в частном порядке. Все они делают возможным удаленное выполнение кода при открытии специально созданной веб-страницы в браузере Internet Explorer. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=137335">MS08-078</a></td>
<td style="border:1px solid black;"><strong>Обновление для системы безопасности Internet Explorer (960714)</strong><br />
<br />
Это обновление для системы безопасности устраняет уязвимость, о которой сообщалось в открытых источниках. Она делает возможным удаленное выполнение кода при открытии специально созданной веб-страницы в браузере Internet Explorer. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в расширенных файлах среды выполнения Visual Basic 6.0 (элементах ActiveX) делают возможным удаленное выполнение кода (932349)</strong><br />
<br />
Это обновление для системы безопасности устраняет пять уязвимостей, о которых сообщалось в частном порядке, и одну уязвимость элементов ActiveX в расширенных файлах среды выполнения Microsoft Visual Basic 6.0, о которой сообщалось в открытых источниках. Они делают возможным удаленное выполнение кода, если пользователь открывает веб-узел, содержащий специально созданное содержимое. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Программное обеспечение и средства разработки Microsoft, Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Office Word делают возможным удаленное выполнение кода (957173)</strong><br />
<br />
Это обновление для системы безопасности устраняет восемь уязвимостей в приложениях Microsoft Office Word и Microsoft Office Outlook, которые делают возможным удаленное выполнение кода, если пользователь открывает специально созданный файл Word или RTF-файл. Воспользовавшись этими уязвимостями, злоумышленник может получить полный контроль над системой. что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Приложение Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=131481">MS08-074</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Office Excel делают возможным удаленное выполнение кода (959070)</strong><br />
<br />
Это обновление для системы безопасности устраняет три уязвимости в Microsoft Office Excel, о которых сообщалось в частном порядке и которые делают возможным удаленное выполнение кода, если пользователь открывает специально созданный файл Excel. Воспользовавшись этими уязвимостями, злоумышленник может получить полный контроль над системой. что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Приложение Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126307">MS08-077</a></td>
<td style="border:1px solid black;"><strong>Уязвимость сервера Microsoft Office SharePoint Server делает возможным несанкционированное получение прав (957175)</strong><br />
<br />
Это обновление для системы безопасности устраняет уязвимость, о которой сообщалось в частном порядке. Она может привести к несанкционированному получению прав при обходе злоумышленником проверки подлинности путем открытия на сайте SharePoint URL-адреса административного узла. Успешная атака может привести к несанкционированному получению прав, что в свою очередь может вызвать отказ в обслуживании или раскрытие информации.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
несанкционированное получение прав</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office, серверное программное обеспечение Майкрософт</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125419">MS08-076</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в компонентах Windows Media делают возможным удаленное выполнение кода (959807)</strong><br />
<br />
Это обновление для системы безопасности устраняет две уязвимости, о которых сообщалось в частном порядке, в следующих компонентах Windows Media: проигрывателе Windows Media, исполняющем модуле формата Windows Media Format Runtime и службах Windows Media. Наиболее существенная из них делает возможным удаленное выполнение кода. Если пользователь вошел в систему с правами администратора, то злоумышленник, которому удалось воспользоваться уязвимостью, может установить полный контроль над системой. что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Указатель использования уязвимости  
----------------------------------
  
<span></span>
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать о вероятности выпуска работающего кода использования уязвимости в течение 30 дней после выпуска бюллетеня по безопасности для каждого обновления для системы безопасности, которое потребуется установить. Перед назначением приоритетов развертывания ознакомьтесь с каждой приведенной ниже оценкой, относящейся к конкретной конфигурации. Дополнительные сведения об уровнях опасности и способах их определения см. в [указателе использования уязвимостей корпорации Майкрософт](http://technet.microsoft.com/en-us/security/cc998259.aspx).

 
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Идентификатор бюллетеня</th>
<th style="border:1px solid black;" >Название бюллетеня</th>
<th style="border:1px solid black;" >Код CVE</th>
<th style="border:1px solid black;" >Оценка указателя использования уязвимости</th>
<th style="border:1px solid black;" >Ключевые примечания</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td style="border:1px solid black;">Уязвимости в расширенных файлах среды выполнения Visual Basic 6.0 (элементах управления ActiveX) делают возможным удаленное выполнение кода (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3704">CVE-2008-3704</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">Согласованный код использования опубликован в открытых источниках.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td style="border:1px solid black;">Уязвимости в расширенных файлах среды выполнения Visual Basic 6.0 (элементах управления ActiveX) делают возможным удаленное выполнение кода (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4252">CVE-2008-4252</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td style="border:1px solid black;">Уязвимости в расширенных файлах среды выполнения Visual Basic 6.0 (элементах управления ActiveX) делают возможным удаленное выполнение кода (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4256">CVE-2008-4256</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td style="border:1px solid black;">Уязвимости в расширенных файлах среды выполнения Visual Basic 6.0 (элементах управления ActiveX) делают возможным удаленное выполнение кода (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4253">CVE-2008-4253</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможна несогласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td style="border:1px solid black;">Уязвимости в расширенных файлах среды выполнения Visual Basic 6.0 (элементах управления ActiveX) делают возможным удаленное выполнение кода (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4254">CVE-2008-4254</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможна несогласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td style="border:1px solid black;">Уязвимости в расширенных файлах среды выполнения Visual Basic 6.0 (элементах управления ActiveX) делают возможным удаленное выполнение кода (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4255">CVE-2008-4255</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможна несогласованность кода использования</td>
<td style="border:1px solid black;">Наибольшему риску подвержены системы Windows 2000. Windows XP с пакетом обновления 2 (SP2), Windows Server 2003 с пакетом обновления 1 (SP1) и более поздние версии операционных систем не подвержены риску применения кода использования благодаря более высокому уровню защиты кучи.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125440">MS08-071</a></td>
<td style="border:1px solid black;">Уязвимости в GDI делают возможным удаленное выполнение кода (956802)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3465">CVE-2008-3465</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможна несогласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125440">MS08-071</a></td>
<td style="border:1px solid black;">Уязвимости в GDI делают возможным удаленное выполнение кода (956802)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2249">CVE-2008-2249</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> — возможность работы кода использования отсутствует</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office Word делают возможным удаленное выполнение кода (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4024">CVE-2008-4024</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office Word делают возможным удаленное выполнение кода (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4025">CVE-2008-4025</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможна несогласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office Word делают возможным удаленное выполнение кода (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4026">CVE-2008-4026</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможна несогласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office Word делают возможным удаленное выполнение кода (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4027">CVE-2008-4027</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможна несогласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office Word делают возможным удаленное выполнение кода (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4028">CVE-2008-4028</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможна несогласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office Word делают возможным удаленное выполнение кода (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4030">CVE-2008-4030</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможна несогласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office Word делают возможным удаленное выполнение кода (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4837">CVE-2008-4837</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможна несогласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office Word делают возможным удаленное выполнение кода (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4031">CVE-2008-4031</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> — возможность работы кода использования отсутствует</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td style="border:1px solid black;">Накопительное обновление для системы безопасности браузера Internet Explorer (958215)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4258">CVE-2008-4258</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td style="border:1px solid black;">Накопительное обновление для системы безопасности браузера Internet Explorer (958215)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4259">CVE-2008-4259</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td style="border:1px solid black;">Накопительное обновление для системы безопасности браузера Internet Explorer (958215)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4261">CVE-2008-4261</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td style="border:1px solid black;">Накопительное обновление для системы безопасности браузера Internet Explorer (958215)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4260">CVE-2008-4260</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможна несогласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=131481">MS08-074</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office Excel делают возможным удаленное выполнение кода (959070)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4265">CVE-2008-4265</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=131481">MS08-074</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office Excel делают возможным удаленное выполнение кода (959070)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4266">CVE-2008-4266</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=131481">MS08-074</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office Excel делают возможным удаленное выполнение кода (959070)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4264">CVE-2008-4264</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможна несогласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132148">MS08-075</a></td>
<td style="border:1px solid black;">Уязвимости в компоненте поиска Windows делают возможным удаленное выполнение кода (959349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4269">CVE-2008-4269</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132148">MS08-075</a></td>
<td style="border:1px solid black;">Уязвимости в компоненте поиска Windows делают возможным удаленное выполнение кода (959349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4268">CVE-2008-4268</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможна несогласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125419">MS08-076</a></td>
<td style="border:1px solid black;">Уязвимости в компонентах Windows Media делают возможным удаленное выполнение кода (959807)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3009">CVE-2008-3009</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">Возможно создание согласованного кода использования уязвимости. Однако вероятность атак минимальна за счет ограниченного характера их сценариев.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125419">MS08-076</a></td>
<td style="border:1px solid black;">Уязвимости в компонентах Windows Media делают возможным удаленное выполнение кода (959807)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3010">CVE-2008-3010</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">Возможно создание согласованного кода использования уязвимости. Однако вероятность атак минимальна за счет ограниченного характера их сценариев.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126307">MS08-077</a></td>
<td style="border:1px solid black;">Уязвимость сервера Microsoft Office SharePoint Server делает возможным несанкционированное получение прав (957175)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4032">CVE-2008-4032</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">Возможно создание согласованного кода использования уязвимости. Однако атаки, которые используют эту уязвимость, могут, вероятнее всего, привести только к раскрытию информации, но не к удаленному выполнению кода.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=137335">MS08-078</a></td>
<td style="border:1px solid black;">Накопительное обновление для системы безопасности браузера Internet Explorer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4844">CVE-2008-4844</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования<br />
(Опубликовано после выпуска бюллетеня)</td>
<td style="border:1px solid black;">Согласованный код эксплойта обнаружен в активных атаках. Однако в браузере Internet Explorer в защищенном режиме, по умолчанию устанавливаемом в системах Windows Vista и Windows Server 2008, будет сложно воспользоваться этой уязвимостью.</td>
</tr>
</tbody>
</table>
  
Продукты, подверженные уязвимости и соответствующие обновления  
--------------------------------------------------------------
  
<span></span>
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и выясните, требуют ли они установки обновлений для системы безопасности. Для программ или компонентов, указанных в списке, приведены ссылки на доступные обновления с указанием уровня опасности уязвимостей, которые они устраняют.
  
**Примечание.** Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификационного номера бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.
  
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
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="6">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://go.microsoft.com/fwlink/?linkid=125440)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://go.microsoft.com/fwlink/?linkid=132148)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://go.microsoft.com/fwlink/?linkid=133437)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://go.microsoft.com/fwlink/?linkid=137335)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://go.microsoft.com/fwlink/?linkid=125419)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Отсутствует
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=3b775fb1-1077-455d-af4a-4ccb5237974f)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=c242ba42-556b-4c87-bf33-9d99166ff096)  
(критический)  
[Microsoft Internet Explorer 6 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c0583745-7e57-4265-9429-c3415cb8465f)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=d3e18732-47f1-40ce-999c-d1fd283bf138)  
(критический)  
[Microsoft Internet Explorer 6 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=124c14b6-9323-4f6f-902b-727aa56444bc)  
(критический)
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=c33d558e-45f9-4e85-b48c-03bd0e8cb4bc)  
(KB954600)  
(существенный)  
[Windows Media Format Runtime 7.1 и Windows Media Format Runtime 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=6a459497-0ab8-41cb-87d0-b551631d8d8a)  
(KB952069)  
(существенный)  
[Службы Windows Media 4.1](http://www.microsoft.com/downloads/details.aspx?familyid=58b7d241-cef6-48fa-aa52-017695f71db1)  
(KB952068)  
(существенный)
</td>
</tr>
<tr>
<th colspan="6">
ОС Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://go.microsoft.com/fwlink/?linkid=125440)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://go.microsoft.com/fwlink/?linkid=132148)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://go.microsoft.com/fwlink/?linkid=133437)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://go.microsoft.com/fwlink/?linkid=137335)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://go.microsoft.com/fwlink/?linkid=125419)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Отсутствует
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP с пакетом обновления 2 (SP2) или 3 (SP3)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2) и Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=2151fbba-c464-4d1e-82d4-5b096e82bed0)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=af9a6cb0-725d-490c-9858-16ec40e98560)  
(критический)  
[Обозреватель Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1b582695-b3cc-4c65-bc4b-d673c9a6d82a)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=1d83e0af-46fa-4bfc-ba57-635435a7ef2d)  
(критический)  
[Обозреватель Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0190a289-164e-41a7-8c01-fa1aaed3f531)  
(критический)
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=99241309-e644-4088-a8f3-38837fab4037)  
(KB954600)  
(существенный)  
[Windows Media Format Runtime 9.0, Windows Media Format Runtime 9.5 и Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=504f816c-f554-4b93-ac28-b085574d9bac)  
(только Windows XP с пакетом обновления 2 (SP2)  
(KB952069)  
(существенный)  
[Windows Media Format Runtime 9.0, Windows Media Format Runtime 9.5 и Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=ad76fcf3-a2f9-4e36-bd1b-c1536749173c)  
(только Windows XP с пакетом обновления 3 (SP3)  
(KB952069)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2247f6a5-aa33-4c68-9ea8-a63488d126d3)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=60bf9851-24fe-4658-8333-d353e82063c7)  
(критический)  
[Обозреватель Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=107cf54b-29d4-4c54-b091-2b5b3ffbf49d)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=a585cb73-2c1a-4fa8-862a-ad6aeaeaf2f8)  
(критический)  
[Обозреватель Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=9ba71e23-8cef-4399-b215-983b0dcf5cb5)  
(критический)
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=946d47c9-b208-4fab-8ef6-774413d61bc8)  
(KB954600)  
(существенный)  
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=644ef023-ee40-45b0-9c9d-c76d9fab0005)  
(KB952069)  
(существенный)  
[Windows Media Format Runtime 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=ae9e8b07-5354-42f3-a226-ba2193244524)  
(KB952069)  
(существенный)  
[Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=2dadc017-2be5-4240-ab8f-0291756dca6b)  
(KB952069)  
(существенный)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://go.microsoft.com/fwlink/?linkid=125440)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://go.microsoft.com/fwlink/?linkid=132148)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://go.microsoft.com/fwlink/?linkid=133437)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://go.microsoft.com/fwlink/?linkid=137335)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://go.microsoft.com/fwlink/?linkid=125419)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Отсутствует
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0c396796-0929-4cd2-99e8-3c0f7075a89e)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=d53adf6f-9501-4862-a1ca-57eb4d40cd75)  
(средний)  
[Обозреватель Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=9cdd4f9e-c578-405c-af9e-628f2d77fdf4)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=d81e9cf9-ce0c-463a-a359-49a348cb89ae)  
(критический)  
[Обозреватель Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=388847ec-817e-45cf-8fa7-32c7e1f57f80)  
(критический)
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=2315ce20-2f46-42c2-bb40-045f003409d7)  
(KB954600)  
(существенный)  
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=d8958248-c889-499e-a6a9-3b394cdb27ea)  
(KB952069)  
(существенный)  
[Службы Windows Media серии 9](http://www.microsoft.com/downloads/details.aspx?familyid=e71abc2d-d60e-444a-9b7b-062c5805fe9e)  
(KB952068)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6d5c7d2f-1a82-4cdf-b3f2-b2c2390c6a64)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=5e37cb34-32be-4bbe-87f3-c4e1974e4d00)  
(средний)  
[Обозреватель Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=7c36f92c-d8a0-4b70-b85f-83588a0299a0)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=015df302-d79f-43a1-b5c5-32ac04de0510)  
(критический)  
[Обозреватель Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2ae17caf-6204-470e-8480-380d3d505657)  
(критический)
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=4c29bed9-1b88-4d2f-80a5-305c2bedd89f)  
(KB954600)  
(существенный)  
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=2278022e-a716-46c0-bedf-d626933bd815)  
(KB952069)  
(существенный)  
[Windows Media Format Runtime 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=ae9e8b07-5354-42f3-a226-ba2193244524)  
(KB952069)  
(существенный)  
[Службы Windows Media серии 9](http://www.microsoft.com/downloads/details.aspx?familyid=e0030155-1a9a-46cc-bbc8-6d0d1ed65c1f)  
(KB952068)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium и Windows Server 2003 с пакетом обновления 2 (SP2) для платформы Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium и Windows Server 2003 с пакетом обновления 2 (SP2) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=1edb62b4-3d0f-4891-b4b3-8f8bc4e7bdfe)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=0da4e424-4682-4401-a226-7d8f1be19d44)  
(средний)  
[Обозреватель Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3811030d-5958-4b91-b5b8-20587dc7c4d6)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=18016305-7f72-47f6-ab4c-94282289bf5f)  
(критический)  
[Обозреватель Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=97d6c093-f68d-4ddf-8e3c-f29662a1940f)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://go.microsoft.com/fwlink/?linkid=125440)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://go.microsoft.com/fwlink/?linkid=132148)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://go.microsoft.com/fwlink/?linkid=133437)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://go.microsoft.com/fwlink/?linkid=137335)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://go.microsoft.com/fwlink/?linkid=125419)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista и Windows Vista с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Vista и Windows Vista с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=cddf9cf6-bdeb-4429-823a-879387a428d7)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista и Windows Vista с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=0dcc5373-0435-42d5-864d-298e5bb122d9)  
(KB958623)  
(существенный)  
[Windows Vista и Windows Vista с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5b1b65f0-6848-47c6-bdd5-be3c0621b323)  
(KB958624)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3f62030a-9ce2-4c92-b948-143a6881921e)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=7887111d-4fac-4823-bdd2-a18d9468fdf0)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=1fcdc8dd-26d9-4d1a-8b3f-7b6a21a95999)  
(KB952069)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition и Windows Vista x64 Edition с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition и Windows Vista x64 Edition с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=73dc3775-b6f0-40f1-bd36-6b5fb80eb2fa)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition и Windows Vista x64 Edition с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=2112c5c8-7c9f-4491-b127-b1093085e105)  
(KB958623)  
(существенный)  
[Windows Vista x64 Edition и Windows Vista x64 Edition с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=eb1d0ffe-1644-457b-9e82-768bd4c7f7ab)  
(KB958624)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d8800493-fba4-41f8-bde5-a53eeaf89d54)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=69979d92-8d45-47fe-ac4c-c2f1f23cf1fb)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=8839f6cd-dfbf-448c-bf1e-1da9bb5f3f25)  
(KB952069)  
(существенный)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://go.microsoft.com/fwlink/?linkid=125440)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://go.microsoft.com/fwlink/?linkid=132148)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://go.microsoft.com/fwlink/?linkid=133437)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://go.microsoft.com/fwlink/?linkid=137335)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://go.microsoft.com/fwlink/?linkid=125419)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем ](http://www.microsoft.com/downloads/details.aspx?familyid=bbed9e8b-e75e-44ef-ba1d-fd6f852c1f67)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=90ab7e6f-5ae7-4f55-8838-868fc98d8a16)\*\*\*  
(KB958623)  
(существенный)  
[Windows Server 2008 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=470d506f-77ae-4a44-8598-df645f484295)\*\*\*  
(KB958624)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=45a0de3c-c7d1-4314-a456-1f7428b7c90a)\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5552e564-dd1c-4e2a-9a42-6317522c884d)\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=91ec4195-bc1c-444e-a7b0-ebde46c088fa)  
(KB952069)  
(существенный)  
[Службы Windows Media 2008 ](http://www.microsoft.com/downloads/details.aspx?familyid=ffb5d945-7f98-4849-b020-ed4873fa42df)\*  
(KB952068)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем
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
[Службы Windows Media 2008 ](http://www.microsoft.com/downloads/details.aspx?familyid=ffb5d945-7f98-4849-b020-ed4873fa42df)\*  
(KB952068)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем ](http://www.microsoft.com/downloads/details.aspx?familyid=48aecf4c-1296-490d-ba37-a28e3ec19bd6)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=e1deab57-ada2-4b12-9157-5615e7b0071d) \*\*\*  
(KB958623)  
(существенный)  
[Windows Server 2008 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=e41f23e4-6a2f-4ebb-b425-d241a08da316) \*\*\*  
(KB958624)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=405b28db-47d7-4d6b-90e6-834c0a409323)\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=889c6eb1-7d1f-4e60-b637-535cb6e4e443)\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=8cab6fe8-161d-4d8c-9772-eb3174a2c3c3)  
(KB952069)  
(существенный)  
[Службы Windows Media 2008 ](http://www.microsoft.com/downloads/details.aspx?familyid=0204a366-5641-4036-9cb0-a46d04af9d72)\*  
(KB952068)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
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
[Службы Windows Media 2008 ](http://www.microsoft.com/downloads/details.aspx?familyid=0204a366-5641-4036-9cb0-a46d04af9d72)\*  
(KB952068)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для платформы Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=9bfe15cd-02ff-45cf-85c8-5ff1e6c1a871)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=48bed90d-c243-4969-8e54-326d9a7af343)  
(KB958623)  
(существенный)  
[Windows Server 2008 для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=83de2263-de2a-4c13-96ba-ecfebdaf0bb9)  
(KB958624)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f0d4f321-941e-4da7-958f-582c75542ee8)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=06cb502a-6818-4599-aa24-6eddb83e4b84)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 
**Примечание к бюллетеню MS08-078**

Сведения об уязвимости, устраняемой обновлением MS08-078, поступили после выпуска браузера Windows Internet Explorer 8 (бета-версия 2), поэтому работающим с ним пользователям необходимо загрузить и установить это обновление.

Обновления для системы безопасности доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747) и [Центре обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130). Обновления для системы безопасности также доступны на веб-узле [центра загрузки Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову security update.

**Примечания для сервера Windows Server 2008**

**\* Подверженные уязвимости системы Windows Server 2008, при развертывании которых устанавливались основные компоненты сервера.** Это обновление имеет одинаковый уровень опасности для поддерживаемых выпусков Windows Server 2008, независимо от того, выбиралась ли установка основных компонентов сервера при их развертывании или нет. Дополнительные сведения об этом варианте установки см. в статье [Основные компоненты сервера](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (на английском языке). Обратите внимание, что установка основных компонентов сервера недоступна в определенных выпусках Windows Server 2008; см. статью [Сравнение параметров установки основных компонентов сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (на английском языке).

**\*\* Не подверженные уязвимости системы Windows Server 2008, при развертывании которых устанавливались основные компоненты сервера.** Поддерживаемые выпуски Windows Server 2008, при развертывании которых выбиралась установка основных компонентов сервера, не подвержены уязвимости, устраняемой этим обновлением. Дополнительные сведения об этом варианте установки см. в статье [Основные компоненты сервера](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (на английском языке). Обратите внимание, что установка основных компонентов сервера недоступна в определенных выпусках Windows Server 2008; см. статью [Сравнение параметров установки основных компонентов сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (на английском языке).

**\*\*\* Не подверженные уязвимости системы Windows Server 2008, при развертывании которых устанавливались основные компоненты сервера.** Поддерживаемые выпуски Windows Server 2008, при развертывании которых выбиралась установка основных компонентов, не подвержены уязвимостям, устраняемым этим обновлением (даже если уязвимые файлы находятся в системе). Однако пользователям, в системе которых находятся уязвимые файлы, предлагается установить это обновление, поскольку оно содержит файлы более поздних версий. Дополнительные сведения об этом варианте установки см. в статье [Основные компоненты сервера](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (на английском языке). Обратите внимание, что установка основных компонентов сервера недоступна в определенных выпусках Windows Server 2008; см. статью [Сравнение параметров установки основных компонентов сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (на английском языке).

#### Наборы приложений и прочие программные продукты Office

 
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
<th colspan="5">
Наборы приложений, системы и компоненты Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://go.microsoft.com/fwlink/?linkid=130478)
</td>
<td style="border:1px solid black;">
[**MS08-072**](http://go.microsoft.com/fwlink/?linkid=126306)
</td>
<td style="border:1px solid black;">
[**MS08-074**](http://go.microsoft.com/fwlink/?linkid=131481)
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://go.microsoft.com/fwlink/?linkid=126307)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
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
Отсутствует
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2000 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=43e8c4d8-307b-48f6-ac99-a9617421d40a)  
(KB956328)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2000 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=f39d2a49-f861-4f2d-bf91-94a8a85af40c)  
(KB958435)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=3ef41412-50b3-4077-b0e3-9a3704d2f876)  
(KB956329)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=72076e21-2aa3-48e8-883a-c3cb756fc72a)  
(KB958372)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
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
[Microsoft Office Word 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=45c81c60-4b1b-4246-839b-198ebc4eeae2)  
(KB956357)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=6c0771e5-fcd4-4365-b903-1a3bd95d9e66)  
(KB958436)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
система Microsoft Office 2007
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007](http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37)  
(KB956358)  
(существенный)  
[приложение Microsoft Office Outlook 2007](http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37)  
(KB956358)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007](http://www.microsoft.com/downloads/details.aspx?familyid=68bb8d99-f28b-4efd-9314-3eee0bb00ccf)  
(KB958437) \*\*\*\*  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Выпуск 2007 системы Microsoft Office с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37)  
(KB956358)  
(существенный)  
[Microsoft Office Outlook 2007 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37) (KB956358)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=68bb8d99-f28b-4efd-9314-3eee0bb00ccf)  
(KB958437) \*\*\*\*  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office FrontPage
</td>
<td style="border:1px solid black;">
[Microsoft Office FrontPage 2002 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=0a6130ae-c5b4-43cb-afe3-ab6a55b9d9ea)\*  
(KB957797)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Project
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=89a44042-a629-40f3-800a-0bb45fc36591)  
(KB949045)  
(критический)  
[Microsoft Office Project 2007](http://www.microsoft.com/downloads/details.aspx?familyid=2fbf6a5b-ff35-4a2d-9fa0-4e62b6486fe6)  
(KB949046)  
(критический)  
[Microsoft Office Project 2007 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=2fbf6a5b-ff35-4a2d-9fa0-4e62b6486fe6)  
(KB949046)  
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
</tr>
<tr>
<th colspan="5">
Microsoft Office для Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://go.microsoft.com/fwlink/?linkid=130478)
</td>
<td style="border:1px solid black;">
[**MS08-072**](http://go.microsoft.com/fwlink/?linkid=126306)
</td>
<td style="border:1px solid black;">
[**MS08-074**](http://go.microsoft.com/fwlink/?linkid=131481)
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://go.microsoft.com/fwlink/?linkid=126307)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
Отсутствует
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Отсутствует
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 для Mac
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=eca13ad8-62ae-41a8-b308-41e2d1773820) \*\*  
(KB960402)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=eca13ad8-62ae-41a8-b308-41e2d1773820) \*\*  
(KB960402)  
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
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=ab31a564-43d2-45bd-98bf-19e9ca477b62) \*\*  
(KB960401)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=ab31a564-43d2-45bd-98bf-19e9ca477b62) \*\*  
(KB960401)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Конвертер форматов файлов Open XML для Mac
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Конвертер форматов файлов Open XML для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=edb6cd8f-832c-4123-8982-ac0c601ea0a7) \*\*  
(KB960403)  
(существенный)
</td>
<td style="border:1px solid black;">
[Конвертер форматов файлов Open XML для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=edb6cd8f-832c-4123-8982-ac0c601ea0a7) \*\*  
(KB960403)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="5">
Другое программное обеспечение Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://go.microsoft.com/fwlink/?linkid=130478)
</td>
<td style="border:1px solid black;">
[**MS08-072**](http://go.microsoft.com/fwlink/?linkid=126306)
</td>
<td style="border:1px solid black;">
[**MS08-074**](http://go.microsoft.com/fwlink/?linkid=131481)
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://go.microsoft.com/fwlink/?linkid=126307)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
Отсутствует
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
Microsoft Works
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Works 8](http://www.microsoft.com/downloads/details.aspx?familyid=1537d181-90d9-4bb5-b5ae-8d9990a349af) \*\*\*  
(KB959487)  
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
Средство просмотра Microsoft Office Excel
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Средство просмотра Microsoft Office Excel 2003](http://www.microsoft.com/downloads/details.aspx?familyid=4b3989ef-02b8-4bd2-b2ab-c3716079936e)  
(KB958434)  
(существенный)  
[Microsoft Office Excel Viewer 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=4b3989ef-02b8-4bd2-b2ab-c3716079936e)  
(KB958434)  
(существенный)  
[Средство просмотра Microsoft Office Excel](http://www.microsoft.com/downloads/details.aspx?familyid=9dbb35c1-aa7a-481b-a330-8ba916ddd443)  
(KB958442)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Средство просмотра Microsoft Office Word
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Средство просмотра Microsoft Office Word 2003 с пакетом обновления 3 (SP3) и средство просмотра Microsoft Office Word](http://www.microsoft.com/downloads/details.aspx?familyid=70de7c3c-519f-4f4a-a03f-027f80b5415c)  
(KB956366)  
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
Пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Пакет обеспечения совместимости форматов файлов Microsoft Office Word, Excel и PowerPoint 2007](http://www.microsoft.com/downloads/details.aspx?familyid=55430121-4476-48b8-9f6f-4a60fa0b2970)  
(KB956828)  
(существенный)  
[Пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=55430121-4476-48b8-9f6f-4a60fa0b2970)  
(KB956828)  
(существенный)
</td>
<td style="border:1px solid black;">
[Пакет обеспечения совместимости форматов файлов Microsoft Office Word, Excel и PowerPoint 2007](http://www.microsoft.com/downloads/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f)  
(KB958439)  
(существенный)  
[Пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f)  
(KB958439)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Сервер Microsoft Office SharePoint Server 2007
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
[Microsoft Office SharePoint Server 2007 (32-разрядные выпуски)](http://www.microsoft.com/downloads/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e)  
(KB956716)  
(существенный)  
[Microsoft Office SharePoint Server 2007 с пакетом обновления 1 (SP1) (32-разрядные выпуски)](http://www.microsoft.com/downloads/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e)  
(KB956716)  
(существенный)  
[Microsoft Office SharePoint Server 2007 (64-разрядные выпуски)](http://www.microsoft.com/downloads/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86)  
(KB956716)  
(существенный)  
[Microsoft Office SharePoint Server 2007 с пакетом обновления 1 (SP1) (64-разрядные выпуски)](http://www.microsoft.com/downloads/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86)  
(KB956716)  
(существенный)
</td>
</tr>
</table>
 
**Примечание, относящееся к бюллетеню MS08-070**
Сведения о дополнительных файлах обновления см. также в следующем разделе **Программное обеспечение и средства разработки Microsoft**. Этот бюллетень относится как к пакету Microsoft Office, так и к программному обеспечению и средствам разработки Microsoft.

**Примечание, относящееся к бюллетеню MS08-077**
Сведения о дополнительных файлах обновления см. также в разделе **Серверное программное обеспечение Майкрософт**. Этот бюллетень относится как к наборам приложений и прочим программным продуктам Microsoft Office, так и к серверному программному обеспечению Майкрософт.

**Примечание, которое относится к обновлению для Microsoft Office FrontPage, содержащемуся в бюллетене MS08-070**
\* Это обновление применимо к версиям приложения FrontPage 2002 с пакетом обновления 3 (SP3) на китайском (упрощенное письмо, Китай), пан-китайском (Гонконг), китайском (традиционное письмо, Тайвань) и корейском языках.

**Примечание, которое относится к обновлениям для Microsoft Office для Mac, содержащимся в бюллетенях MS08-072 и MS08-074**
\*\* Обновления, содержащиеся в бюллетенях MS08-072 и MS08-074, идентичны, поскольку уязвимости, для устранения которых они предназначены, связаны с одними и теми же файлами.

**Примечание для приложения Works 8, которое описано в бюллетене MS08-072**
\*\*\* Чтобы получить это обновление для системы безопасности, пользователям приложения Microsoft Works 8.0 необходимо обновить его до версии 8.5, как описано в статье, посвященной [обновлениям для Microsoft Works](http://www.microsoft.com/products/works/international/update_1001.mspx) (на английском языке). Также это касается пользователей Microsoft Works 8.0, Works Suite 2004 и Works Suite 2005. Версия Works 8.5 уже входит в состав набора Works Suite 2006.

**Примечание, относящееся к бюллетеню MS08-074 и касающееся приложений Microsoft Office Excel 2007 и Microsoft Office Excel 2007 с пакетом обновления 1 (SP1)**
\*\*\*\* Пользователям Microsoft Office Excel 2007 и Microsoft Office Excel 2007 с пакетом обновления 1 (SP1), установившим обновление для системы безопасности KB958437, потребуется также установить обновление для системы безопасности [пакета обеспечения совместимости форматов файлов Microsoft Office Word, Excel и PowerPoint 2007](http://www.microsoft.com/downloads/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f) (KB958439), чтобы защитить компьютеры от уязвимостей, описанных в бюллетене MS08-074. Если обновления для системы безопасности KB958437 и KB958439 уже установлены, повторная установка их не требуется.

#### Программное обеспечение и средства разработки Microsoft

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://go.microsoft.com/fwlink/?linkid=130478)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Basic
</td>
<td style="border:1px solid black;">
[Расширенные файлы среды выполнения Microsoft Visual Basic 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e27eebcb-095d-43ec-a19e-4a46e591715c)  
(KB926857)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio .NET
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2002 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=afad980d-7f27-49d9-aa23-b762c7b94cd6)  
(KB958392)  
(критический)  
[Microsoft Visual Studio .NET 2003 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=6ac7cf8f-d046-43a8-b4ef-253153d65aed)  
(KB958393)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 8.0 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=a6977f81-f7f6-486b-96ad-8d296d79f205)  
(KB958369)  
(критический)  
[Microsoft Visual FoxPro 9.0 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=386d27a6-b2c7-4acc-bf3e-edcbc7358172)  
(KB958370)  
(критический)  
[Microsoft Visual Studio .FoxPro 9.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5b1f28a9-da8d-463a-8ae4-dfc8fcc6c41a)  
(KB958371)  
(критический)
</td>
</tr>
</table>
 
**Примечание, относящееся к бюллетеню MS08-070**
Сведения о дополнительных файлах обновления см. также в следующем разделе **Наборы приложений и прочие программные продукты Office**. Этот бюллетень относится как к наборам приложений и прочим программным продуктам Microsoft Office, так и к программному обеспечению и средствам разработки Microsoft.

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
Поисковый сервер
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://go.microsoft.com/fwlink/?linkid=126307)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Поисковый сервер Microsoft
</td>
<td style="border:1px solid black;">
[Microsoft Search Server 2008 (32-разрядные выпуски)](http://www.microsoft.com/downloads/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e) \*  
(KB956716)  
(существенный)  
[Microsoft Search Server 2008 (64-разрядные выпуски)](http://www.microsoft.com/downloads/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86) \*\*  
(KB956716)  
(существенный)
</td>
</tr>
</table>
 
**Примечания, относящиеся к бюллетеню MS08-077**

\* Включает Microsoft Search Server 2008 Express (32-разрядные выпуски)

\*\* Включает Microsoft Search Server 2008 Express (64-разрядные выпуски)

Сведения о дополнительных файлах обновления см. также в следующем разделе **Наборы приложений и прочие программные продукты Office**. Этот бюллетень относится как к наборам приложений и прочим программным продуктам Microsoft Office, так и к серверному программному обеспечению Майкрософт.

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
**В центре безопасности**

Управление программным обеспечением и обновлениями для системы безопасности для установки на серверы, настольные и переносные компьютеры организации. Дополнительные сведения см. на веб-узле [центра TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [Центр безопасности TechNet](http://go.microsoft.com/fwlink/?linkid=21171) содержит дополнительные сведения о безопасности в продуктах Майкрософт. Доступ к этим сведениям можно также получить, посетив веб-узел [Безопасность дома](http://go.microsoft.com/fwlink/?linkid=85102) (на английском языке) и щелкнув ссылку Latest Security Updates (Последние обновления безопасности).

Обновления для системы безопасности доступны на веб-узлах [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747), [Центра обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130) и [центра загрузки Office](http://go.microsoft.com/fwlink/?linkid=21135). Обновления для системы безопасности также доступны на веб-узле [центра загрузки Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову security update.

Наконец, обновления для системы безопасности можно загрузить из [каталога Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=96155). Он обеспечивает возможность поиска содержимого (в том числе обновлений для системы безопасности, драйверов и пакетов обновления), которое предоставляется через Центр обновления Windows и Центр обновления Майкрософт. При поиске по номеру бюллетеня по безопасности (например, MS07-036) можно добавлять нужные обновления в корзину, в том числе на различных языках, и загружать их в указанную папку. Дополнительные сведения см. на веб-узле [Каталог Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=97900) в разделе "Вопросы и ответы".

**Руководство по диагностике и развертыванию**

Корпорация Майкрософт предоставила руководство по диагностике и развертыванию для обновлений безопасности этого месяца. Это руководство также поможет ИТ-специалистам понять, как можно использовать для развертывания обновления для системы безопасности такие средства, как веб-узлы Центра обновления Windows, Центра обновления Майкрософт и центра загрузки Office, анализатор безопасности Microsoft Baseline Security Analyzer (MBSA), средство Office Detection Tool, сервер Microsoft Systems Management Server (SMS) и средство Extended Security Update Inventory Tool (ESUIT). Дополнительные сведения см. в [статье 910723 базы знаний Майкрософт](http://support.microsoft.com/kb/910723).

**Программа Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений безопасности и стандартных ошибок в конфигурации системы безопасности. Дополнительные сведения об анализаторе безопасности MBSA см. на веб-узле [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) (на английском языке).

**Службы Windows Server Update Services**

Службы Windows Server Update Services (WSUS) позволяют администраторам быстро и надежно развертывать последние критические обновления и обновления безопасности для операционных систем Windows 2000 и более поздних версий Windows, для Office XP и более поздних версий Office, для Exchange Server 2003 и для SQL Server 2000 на системах Windows 2000 и более поздних версиях операционных систем.

Дополнительные сведения о развертывании данного обновления для системы безопасности с помощью служб Windows Server Update Services см. на веб-узле [Службы Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) (на английском языке).

**Сервер Systems Management Server**

Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет хорошо сконфигурированное решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей. Последний выпуск сервера SMS — System Center Configuration Manager 2007 — доступен для загрузки; сведения о нем см. также на веб-узле [Диспетчер System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx) (на английском языке). Дополнительные сведения о том, как администраторы могут использовать сервер SMS 2003 для развертывания обновлений для системы безопасности, см. на веб-узле [Управление исправлениями для системы безопасности сервера SMS 2003](http://go.microsoft.com/fwlink/?linkid=22939) (на английском языке). Пользователи сервера SMS 2.0 могут также воспользоваться средствами веб-узла [Пакет возможностей служб Software Updates Services](http://go.microsoft.com/fwlink/?linkid=33340) (на английском языке), позволяющими упростить развертывание обновлений для системы безопасности. Дополнительные сведения о сервере SMS см. на веб-узле [Сервер Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) (на английском языке).

**Примечание.** Для предоставления широкой поддержки при определении необходимости применения и развертывания обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используются средства Microsoft Baseline Security Analyzer и Microsoft Office Detection Tool. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. на веб-узле [Развертывание обновлений программного обеспечения с помощью функции распространения программ сервера SMS](http://go.microsoft.com/fwlink/?linkid=33341) (на английском языке). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакетов [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) и [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

**Средство оценки совместимости обновлений и набор средств для обеспечения совместимости приложений**

Часто обновления записываются в одни те же файлы, а для запуска приложений требуется настроить параметры реестра. Это приводит к возникновению несовместимостей и увеличивает время, затрачиваемое на развертывание обновлений для системы безопасности. Облегчить тестирование и проверку обновлений Windows для установленных приложений можно с помощью [компонентов оценки совместимости обновлений](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true), входящих в состав [набора средств для обеспечения совместимости приложений 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Набор средств для обеспечения совместимости приложений содержит необходимые средства и документацию для выявления проблем совместимости приложений и уменьшения степени воздействия этих проблем перед развертыванием системы Microsoft Windows Vista, обновлений из Центра обновления Windows, обновлений с веб-узла безопасности Майкрософт или новой версии проводника.

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

#### Высокоприоритетные обновления, не относящиеся к безопасности и распространяемые через Центры MU, WU и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-узле Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт](http://support.microsoft.com/kb/894199). Описание изменений содержимого служб Software Update Services и Windows Server Update Services в 2008 г. (включая все содержимое Windows).
-   [Новые, исправленные и выпущенные обновления для продуктов Майкрософт, отличных от Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

#### Microsoft Active Protections Program (MAPP)

Чтобы повысить уровень защиты пользователей, корпорация Майкрософт предоставляет сведения об уязвимостях крупным поставщикам программного обеспечения безопасности перед ежемесячным выпуском обновлений. Эта информация необходима им для усовершенствования программного обеспечения и оборудования для защиты пользователей (антивирусных программ, сетевых систем обнаружения вторжений, а также индивидуальных систем предотвращения вторжений). Сведения о новых средствах защиты, предоставляемых поставщиками программного обеспечения безопасности, доступны на соответствующих веб-сайтах партнеров, перечисленных в списке партнеров [MAPP](http://www.microsoft.com/security/msrc/mapp/partners.mspx).

#### Стратегии безопасности и сообщество

**Стратегии управления обновлениями**

На веб-узле [Рекомендации по безопасности для управления обновлениями](http://go.microsoft.com/fwlink/?linkid=21168) (на английском языке) содержатся дополнительные сведения о рекомендациях корпорации Майкрософт по установке обновлений для системы безопасности.

**Другие обновления для системы безопасности**

Другие обновления безопасности можно загрузить из следующих источников:

-   Обновления для системы безопасности доступны на веб-узле [центра загрузки Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову security update.
-   Обновления для индивидуальных пользователей доступны на веб-узле [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747).
-   Обновления для системы безопасности, доступные в этом месяце на веб-узле Центра обновления Windows, можно получить в виде файлов образа компакт-диска с выпусками обновлений для системы безопасности в Центре загрузки Майкрософт. Дополнительные сведения см. в [статье 913086 базы знаний Майкрософт](http://support.microsoft.com/kb/913086).

**Сообщество ИТ-специалистов, занимающихся вопросами безопасности (на английском языке)**

На веб-узле [Сообщество ИТ-специалистов, занимающихся вопросами безопасности](http://go.microsoft.com/fwlink/?linkid=21164) (на английском языке) можно получить сведения о способах усовершенствования системы безопасности и оптимизации информационной инфраструктуры предприятия, а также обсудить вопросы, связанные с обеспечением безопасности, с другими ИТ-специалистами.

#### Благодарности

Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:

-   ADLab из компании [VenusTech](http://www.venustech.com.cn/) за сообщение о проблемах, описанных в бюллетене по безопасности MS08-070;
-   Джейсона Медейроса (Jason Medeiros) из компании [Affiliated Computer Services](http://www.acs-inc.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-070;
-   Карстена Эйрама (Carsten Eiram) из компании [Secunia Research](http://secunia.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-070;
-   Марка Дауда (Mark Dowd), сотрудничающего с компанией [McAfee Avert Labs](http://www.avertlabs.com/), за сообщение о проблеме, описанной в бюллетене по безопасности MS08-070;
-   Бретта Мура (Brett Moore) из компании [Insomnia Security](http://www.insomniasec.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-070;
-   пользователя CHkr\_D591, сотрудничающего с компаниями [TippingPoint](http://www.tippingpoint.com/) и [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в бюллетене по безопасности MS08-070;
-   Михаля Бако (Michal Bucko), сотрудничающего с компанией [CERT/CC](http://www.cert.org/), за сообщение о проблеме, описанной в бюллетене по безопасности MS08-070;
-   [коллектив аналитиков по безопасности](http://www.symantec.com/) компании Symantec за совместную работу над проблемой, описанной в бюллетене по безопасности MS08-070;
-   Цзюнь Мао (Jun Mao) из компании [VeriSign iDefense Labs](http://labs.idefense.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-071;
-   Хуана Кабальеро (Juan Caballero) из [группы Bitblaze Университета Карнеги-Меллон и Калифорнийского Университета в Беркли](http://bitblaze.cs.berkeley.edu/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-071;
-   Рикардо Нарваху (Ricardo Narvaja) из компании [Core Security Technologies](http://www.coresecurity.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-072;
-   Дайона Болдинга (Dyon Balding) из компании [Secunia Research](http://secunia.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-072;
-   Ямату Ли (Yamata Li) из компании [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-072;
-   Вуши (Wushi), сотрудничающего с организациями [TippingPoint](http://www.tippingpoint.com/) и [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в бюллетене по безопасности MS08-072;
-   Аарона Портного (Aaron Portnoy) из компании [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) за сообщение о проблемах, описанных в бюллетене по безопасности MS08-072;
-   Вуши (Wushi) из компании [team509](http://www.team509.com/), сотрудничающего с компанией [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в бюллетене по безопасности MS08-072;
-   Вуши (Wushi) и Лина (Ling), сотрудничающих с организациями [TippingPoint](http://www.tippingpoint.com/) и [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в бюллетене по безопасности MS08-072;
-   Карло Ди Дато (Carlo Di Dato, aka shinnai) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-073;
-   Бретта Мура (Brett Moore), сотрудничающего с организациями [TippingPoint](http://www.tippingpoint.com/) и [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в бюллетене по безопасности MS08-073;
-   Криса Уэбера (Chris Weber) из компании [Casaba Security](http://www.casabasecurity.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-073;
-   Цзюнь Мао (Jun Mao) из компании [VeriSign iDefense Labs](http://labs.idefense.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-073;
-   Джошуа Дрейка (Joshua J. Drake) из компании [Verisign iDefense Labs](http://labs.idefense.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS07-074;
-   Клаэса М. Нюберга (Claes M Nyberg) из компании [signedness.org](http://www.signedness.org/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-074;
-   Дайона Болдинга (Dyon Balding) из компании [Secunia](http://secunia.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS07-074;
-   Андре Протаса (Andre Protas) из компании [eEye Digital Security](http://www.eeye.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-075;
-   Нейта Макфетерса (Nate McFeters) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-075;
-   анонимного исследователя за сообщение о проблеме, описанной в бюллетене по безопасности MS08-077.

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов можно найти на веб-узле [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).
-   Обращайтесь в [службу поддержки продуктов корпорации Майкрософт](http://go.microsoft.com/fwlink/?linkid=21131) по телефону 1-866-PCSAFETY (для жителей США и Канады). Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно.
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-узел международной поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (9 декабря 2008 г.). Обзор бюллетеней опубликован.
-   Версия 2.0 (10 декабря 2008 г.). В таблицу подверженных уязвимости продуктов бюллетеня MS08-076 внесены изменения: Windows Media Format Runtime 9.5 и Windows Media Format Runtime 11 указаны как отдельные обновления для систем Windows XP Professional x64 Edition и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2); удалены данные о модуле Windows Media Format Runtime 11 x64 Edition в системах Windows XP Professional x64 Edition, Windows XP Professional x64 Edition с пакетом обновления 2 (SP2), Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2).
-   Версия 3.0 (17 декабря 2008 г.). В обзор добавлен бюллетень по безопасности Microsoft MS08-078, обновление для системы безопасности браузера Internet Explorer (960714), а также ссылки на сведения о веб-трансляции, посвященной внеплановому бюллетеню по безопасности.
-   Версия 3.1 (18 декабря 2008 г.). Для обновления MS08-078 добавлены сведения о том, что версия Server Core 32-разрядной и 64-разрядной системы Windows Server 2008 не подвержена уязвимости Windows Internet Explorer 7.
-   Версия 3.2 (7 января 2009 г.). Из таблицы подверженных уязвимости продуктов для бюллетеня MS08-072 удалено средство просмотра Microsoft Office Word 2003.
-   Версия 4.0 (13 января 2009 г.). Корпорация Майкрософт повторно выпустила бюллетень MS08-076, чтобы предложить новые обновления для Windows Media Format Runtime 9.5 в системе Windows XP с пакетом обновления 2 (SP2) (KB952069) и Windows XP с пакетом обновления 3 (SP3) (KB952069). Пользователям, работающим со всеми прочими поддерживаемыми и уязвимыми версиями компонентов Windows Media и применившим исходные обновления для системы безопасности, которые описаны в бюллетене MS08-076, не потребуется предпринимать никаких дополнительных действий. Также в бюллетене MS08-076 сообщается, что проигрыватель Windows Media 6.4 и службы Windows Media 4.1 являются уязвимыми во всех выпусках Microsoft Windows 2000 с пакетом обновления 4 (SP4); пользователи, которым было предложено обновление KB954600 для проигрывателя Windows Media 6.4 или KB952068 для служб Windows Media 4.1 и которые его не применили, необходимо это сделать. Кроме того, средство просмотра Microsoft Office Word отнесено к категории уязвимых продуктов в бюллетене MS08-072; пользователям, установившим обновление для системы безопасности KB956366, не нужно его переустанавливать.
-   Версия 5.0 (28 января 2009 г.). В таблицу **Подвержены уязвимости** добавлено примечание, относящееся к бюллетеню MS08-074, об обновлениях для системы безопасности KB958437 и KB958439 для поддерживаемых версий Microsoft Office Excel 2007. Обновление не вносит изменения в двоичные файлы или процедуру обнаружения. Пользователям Microsoft Office Excel 2007 или Microsoft Office Excel 2007 с пакетом обновления 1 (SP1), установившим обновления для системы безопасности KB958437 и KB958439, переустанавливать их не нужно.
-   Версия 6.0 (29 апреля 2009 г.). В список подверженных уязвимости продуктов бюллетеня MS08-076 добавлены службы Windows Media 2008 (KB952068) в 32- и 64-разрядных выпусках системы Windows Server 2008 с пакетом обновления 2 (SP2). Это обновление касается только обнаружения. Оно не вносит изменения в двоичные файлы. Если обновление KB952068 установлено в системе, переустанавливать его не требуется.

*Built at 2014-04-18T01:50:00Z-07:00*
