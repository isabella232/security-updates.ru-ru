---
TOCTitle: 'MS09-APR'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Апрель 2009 г.'
ms:assetid: 'ms09-apr'
ms:contentKeyID: 61236119
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms09-apr(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Апрель 2009 г.
=================================================================

Дата публикации: 14 апреля 2009 г. | Дата обновления: 16 апреля 2009 г.

**Версия:** 1.1

В этом обзоре описаны бюллетени по безопасности, выпущенные в апреле 2009 г.

После выпуска апрельских бюллетеней данный обзор заменит предварительное уведомление, выпущенное 9 апреля 2009 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [Предварительное уведомление о бюллетенях по безопасности Microsoft](http://technet.microsoft.com/security/bulletin/advance) (на английском языке).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней по безопасности Microsoft, см. на веб-узле [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

15 апреля 2009 г. в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в апрельской веб-трансляции, посвященной бюллетеням по безопасности](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395126). После наступления этой даты данная веб-трансляциия будет доступна по запросу. Дополнительные сведения см. на веб-узле [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://technet.microsoft.com/security/bulletin/summary) (на английском языке).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139849">MS09-010</a></td>
<td style="border:1px solid black;"><strong>Уязвимости текстовых конвертеров WordPad и Office делают возможным удаленное выполнение кода (960477)</strong><br />
<br />
Это обновление для системы безопасности устраняет две уязвимости текстовых конвертеров Microsoft WordPad и Microsoft Office, о которых сообщалось в открытых источниках, и две уязвимости, сведения о которых предоставлялись в частном порядке. Они делают возможным удаленное выполнение кода при открытии специально созданного файла в WordPad или Microsoft Office Word. Не открывайте файлы Microsoft Office, RTF, Write или WordPerfect, полученные из ненадежных источников, с помощью уязвимых версий WordPad или Microsoft Office Word.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139852">MS09-013</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в службах Windows HTTP делают возможным удаленное выполнение кода (960803)</strong><br />
<br />
Это обновление для системы безопасности устраняет уязвимости служб Microsoft Windows HTTP (WinHTTP). Об одной из них сообщалось в открытых источниках, а о двух других сведения предоставлялись в частном порядке. Наиболее существенная из них делает возможным удаленное выполнение кода. Воспользовавшись этой уязвимостью, злоумышленник может захватить полный контроль над системой, что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139107">MS09-011</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft DirectShow делает возможным удаленное выполнение кода (961373)</strong><br />
<br />
Это обновление для системы безопасности устраняет уязвимость в Microsoft DirectX, о которой сообщалось в частном порядке. Она делает возможным удаленное выполнение кода в случае открытия пользователем специально созданного MJPEG-файла. Воспользовавшись этой уязвимостью, злоумышленник может захватить полный контроль над системой, что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=146659">MS09-014</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (963027)</strong><br />
<br />
Данное обновление для системы безопасности устраняет четыре уязвимости браузера Internet Explorer, о которых сообщалось в частном порядке, и две уязвимости, о которых сообщалось в открытых источниках. Все они делают возможным удаленное выполнение кода при открытии специально созданной веб-страницы в браузере Internet Explorer или при подключении пользователя к серверу злоумышленника по протоколу HTTP. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=143568">MS09-009</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Office Excel делают возможным удаленное выполнение кода (968557)</strong><br />
<br />
Это обновление для системы безопасности устраняет две уязвимости в Microsoft Office Excel. Об одной из них сообщалось в частном порядке, о другой сообщалось в открытых источниках. Обе уязвимости делают возможным удаленное выполнение кода при открытии пользователем специально созданного файла Excel. Воспользовавшись этими уязвимостями, злоумышленник может получить полный контроль над системой. что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Приложение Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132587">MS09-012</a></td>
<td style="border:1px solid black;"><strong>Уязвимости системы Windows могут привести к несанкционированному получению прав (959454)</strong><br />
<br />
Данное обновление для системы безопасности устраняет четыре уязвимости в системе Microsoft Windows, о которых сообщалось в открытых источниках. Уязвимости могут привести к несанкционированному получению прав, если злоумышленник войдет в систему и запустит специально созданное приложение. Чтобы использовать эти уязвимости, злоумышленник должен запустить код на локальном компьютере. Злоумышленник, успешно воспользовавшийся любой из этих уязвимостей, может получить полный контроль над системой.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141639">MS09-016</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft ISA Server и Forefront Threat Management Gateway (версия Medium Business Edition) могут приводить к отказу в обслуживании (961759)</strong><br />
<br />
Это обновление для системы безопасности устраняет уязвимости в Microsoft Internet Security and Acceleration Server (ISA-сервер) и Microsoft Forefront Threat Management Gateway (TMG) версии Medium Business Edition (MBE), о которых сообщалось в частном порядке и в открытых источниках. Данные уязвимости могут привести к отказу в обслуживании, если злоумышленник отправит специально созданные сетевые пакеты в уязвимую систему, или к раскрытию информации, если пользователь щелкнет вредоносный URL-адрес либо посетит подконтрольный злоумышленнику веб-сайт.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Forefront Edge Security</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=146803">MS09-015</a></td>
<td style="border:1px solid black;"><strong>Уязвимость для смешанных угроз в функции SearchPath делает возможным несанкционированное получение прав (959426)</strong><br />
<br />
Данное обновление для системы безопасности устраняет уязвимость в функции SearchPath системы Windows, о которой сообщалось в открытых источниках. Она может привести к несанкционированному получению прав при загрузке пользователем специально созданного файла в определенное расположение и последующем открытии приложения, которое при определенных обстоятельствах может загрузить файл.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Средний</a><br />
несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Указатель использования уязвимости  
----------------------------------
  
<span></span>
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости сгруппированы по идентификаторам бюллетеней и кодам CVE.
  
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать о вероятности выпуска работающего кода использования уязвимости в течение 30 дней после выпуска бюллетеня по безопасности для каждого обновления для системы безопасности, которое потребуется установить. Перед назначением приоритетов развертывания ознакомьтесь с каждой приведенной ниже оценкой, относящейся к конкретной конфигурации. Дополнительные сведения об уровнях опасности и способах их определения см. в [указателе использования уязвимостей корпорации Майкрософт](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| Идентификатор бюллетеня                                   | Название бюллетеня                                                                                                                                        | Код CVE                                                                               | Оценка указателя использования уязвимости                                                                              | Ключевые примечания                                                                                                                                                                                                                                                                                           |  
|-----------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-009](http://go.microsoft.com/fwlink/?linkid=143568) | Уязвимости в Microsoft Office Excel делают возможным удаленное выполнение кода (968557)                                                                   | [CVE-2009-0100](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0100)      | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна несогласованность кода использования     | (отсутствует)                                                                                                                                                                                                                                                                                                 |  
| [MS09-009](http://go.microsoft.com/fwlink/?linkid=143568) | Уязвимости в Microsoft Office Excel делают возможным удаленное выполнение кода (968557)                                                                   | [CVE-2009-0238](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0238)      | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода использования       | **Примеры использования данной уязвимости известны в экосистеме Интернета.**                                                                                                                                                                                                                                  |  
| [MS09-010](http://go.microsoft.com/fwlink/?linkid=139849) | Уязвимости текстовых конвертеров WordPad и Office делают возможным удаленное выполнение кода (960477)                                                     | [CVE-2008-4841](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4841)      | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода использования       | **Примеры использования данной уязвимости известны в экосистеме Интернета.**                                                                                                                                                                                                                                  |  
| [MS09-010](http://go.microsoft.com/fwlink/?linkid=139849) | Уязвимости текстовых конвертеров WordPad и Office делают возможным удаленное выполнение кода (960477)                                                     | [CVE-2009-0087](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0087)      | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна несогласованность кода использования     | Эта уязвимость является сложной в связи с многочисленными путями кода. Большинство кодов использования уязвимости приведет к несогласованным результатам. Стандартные факторы, снижающие опасность уязвимости, обеспечивают защиту от данного направления атаки.                                              |  
| [MS09-010](http://go.microsoft.com/fwlink/?linkid=139849) | Уязвимости текстовых конвертеров WordPad и Office делают возможным удаленное выполнение кода (960477)                                                     | [CVE-2009-0088](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0088)      | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода использования       | Этой уязвимостью можно воспользоваться, но она затрагивает только старые версии систем и устаревшие, редко используемые форматы файлов. Более современные версии систем, такие как выпуск 2007 системы Microsoft Office и Microsoft Office 2003 с пакетом обновления 3 (SP3) не подвержены данной уязвимости. |  
| [MS09-010](http://go.microsoft.com/fwlink/?linkid=139849) | Уязвимости текстовых конвертеров WordPad и Office делают возможным удаленное выполнение кода (960477)                                                     | [CVE-2009-0235](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0235)      | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода использования       | Этой уязвимостью, связанной с повреждением памяти, легко воспользоваться.                                                                                                                                                                                                                                     |  
| [MS09-011](http://go.microsoft.com/fwlink/?linkid=139107) | Уязвимость в Microsoft DirectShow делает возможным удаленное выполнение кода (961373)                                                                     | [CVE-2009-0084](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0084)      | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна несогласованность кода использования     | (отсутствует)                                                                                                                                                                                                                                                                                                 |  
| [MS09-012](http://go.microsoft.com/fwlink/?linkid=132587) | Уязвимости системы Windows могут привести к несанкционированному получению прав (959454)                                                                  | [CVE-2008-1436](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-1436)      | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода использования       | **Примеры использования данной уязвимости известны в экосистеме Интернета.**                                                                                                                                                                                                                                  |  
| [MS09-012](http://go.microsoft.com/fwlink/?linkid=132587) | Уязвимости системы Windows могут привести к несанкционированному получению прав (959454)                                                                  | [CVE-2009-0078](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0078)      | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода использования       | **Примеры использования данной уязвимости известны в экосистеме Интернета.**                                                                                                                                                                                                                                  |  
| [MS09-012](http://go.microsoft.com/fwlink/?linkid=132587) | Уязвимости системы Windows могут привести к несанкционированному получению прав (959454)                                                                  | [CVE-2009-0079](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0079)      | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода использования       | **Примеры использования данной уязвимости известны в экосистеме Интернета.**                                                                                                                                                                                                                                  |  
| [MS09-012](http://go.microsoft.com/fwlink/?linkid=132587) | Уязвимости системы Windows могут привести к несанкционированному получению прав (959454)                                                                  | [CVE-2009-0080](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0080)      | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода использования       | **Примеры использования данной уязвимости известны в экосистеме Интернета.**                                                                                                                                                                                                                                  |  
| [MS09-013](http://go.microsoft.com/fwlink/?linkid=139852) | Уязвимости в службах Windows HTTP делают возможным удаленное выполнение кода (960803)                                                                     | [CVE-2009-0086](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0086)      | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода использования       | Эта уязвимость памяти легко управляема и имеет несколько направлений атаки и возможностей использования в связи с широким распространением данной технологии.                                                                                                                                                 |  
| [MS09-013](http://go.microsoft.com/fwlink/?linkid=139852) | Уязвимости в службах Windows HTTP делают возможным удаленное выполнение кода (960803)                                                                     | [CVE-2009-0089](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0089)      | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода использования       | (отсутствует)                                                                                                                                                                                                                                                                                                 |  
| [MS09-013](http://go.microsoft.com/fwlink/?linkid=139852) | Уязвимости в службах Windows HTTP делают возможным удаленное выполнение кода (960803)                                                                     | [CVE-2009-0550](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0550) \*\* | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода использования       | Код использования уязвимости опубликован.                                                                                                                                                                                                                                                                     |  
| [MS09-014](http://go.microsoft.com/fwlink/?linkid=146659) | Накопительное обновление для системы безопасности браузера Internet Explorer (963027)                                                                     | [CVE-2008-2540 ](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2540)\*   | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможность работы кода использования отсутствует | Сведения об атаке опубликованы, но в данный момент известных направлений атак нет. Чтобы воспользоваться этой уязвимостью, злоумышленнику и пользователю необходимо выполнить ряд сложных действий, в том числе сохранить определенные файлы на рабочий стол.                                                 |  
| [MS09-014](http://go.microsoft.com/fwlink/?linkid=146659) | Накопительное обновление для системы безопасности браузера Internet Explorer (963027)                                                                     | [CVE-2009-0550](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0550) \*\* | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода использования       | Код использования уязвимости опубликован.                                                                                                                                                                                                                                                                     |  
| [MS09-014](http://go.microsoft.com/fwlink/?linkid=146659) | Накопительное обновление для системы безопасности браузера Internet Explorer (963027)                                                                     | [CVE-2009-0551](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0551)      | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна несогласованность кода использования     | (отсутствует)                                                                                                                                                                                                                                                                                                 |  
| [MS09-014](http://go.microsoft.com/fwlink/?linkid=146659) | Накопительное обновление для системы безопасности браузера Internet Explorer (963027)                                                                     | [CVE-2009-0552](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0552)      | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможность работы кода использования отсутствует | Факторы, снижающие опасность уязвимости для Internet Explorer 7, предотвращают выполнение кода. Internet Explorer 6 и предыдущие версии более подвержены уязвимости, если для них не установлены все необходимые обновления системы безопасности.                                                             |  
| [MS09-014](http://go.microsoft.com/fwlink/?linkid=146659) | Накопительное обновление для системы безопасности браузера Internet Explorer (963027)                                                                     | [CVE-2009-0553](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0553)      | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможность работы кода использования отсутствует | (отсутствует)                                                                                                                                                                                                                                                                                                 |  
| [MS09-014](http://go.microsoft.com/fwlink/?linkid=146659) | Накопительное обновление для системы безопасности браузера Internet Explorer (963027)                                                                     | [CVE-2009-0554](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0554)      | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода использования       | (отсутствует)                                                                                                                                                                                                                                                                                                 |  
| [MS09-015](http://go.microsoft.com/fwlink/?linkid=146803) | Уязвимость для смешанных угроз в функции SearchPath делает возможным несанкционированное получение прав (959426)                                          | [CVE-2008-2540 ](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2540)\*   | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна несогласованность кода использования     | Сведения об атаке опубликованы, но в данный момент известных направлений атак нет. Чтобы воспользоваться этой уязвимостью, злоумышленнику и пользователю необходимо выполнить ряд сложных действий, в том числе сохранить определенные файлы на рабочий стол.                                                 |  
| [MS09-016](http://go.microsoft.com/fwlink/?linkid=141639) | Уязвимости в Microsoft ISA Server и Forefront Threat Management Gateway (версия Medium Business Edition) могут приводить к отказу в обслуживании (961759) | [CVE-2009-0077](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0077)      | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможность работы кода использования отсутствует | Атака типа "отказ в обслуживании", основанная на использовании служб, весьма вероятна. Однако выполнение кода невозможно.                                                                                                                                                                                     |  
| [MS09-016](http://go.microsoft.com/fwlink/?linkid=141639) | Уязвимости в Microsoft ISA Server и Forefront Threat Management Gateway (версия Medium Business Edition) могут приводить к отказу в обслуживании (961759) | [CVE-2009-0237](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-0237)           | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможность работы кода использования отсутствует | Вероятно раскрытие информации. Выполнение кода маловероятно.                                                                                                                                                                                                                                                  |
  
\* Этим двум уязвимостям присвоен один номер CVE. Они устраняются с помощью двух обновлений для системы безопасности. Дополнительные сведения см. в соответствующих бюллетенях.
  
\*\* Этим двум уязвимостям присвоен один номер CVE. Они устраняются с помощью двух обновлений для системы безопасности. Дополнительные сведения см. в соответствующих бюллетенях.
  
Продукты, подверженные уязвимости и соответствующие обновления  
--------------------------------------------------------------
  
<span></span>
В приведенных ниже таблицах перечислены бюллетени в порядке важности категорий программного обеспечения и уровней опасности.
  
**Как пользоваться этими таблицами?**
  
Обращайтесь к этим таблицам, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и узнайте, имеются ли для них обновления для системы безопасности. Для программ или компонентов, указанных в списке, приведены ссылки на доступные обновления с указанием уровня опасности уязвимостей, которые они устраняют.
  
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
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="7">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://go.microsoft.com/fwlink/?linkid=139849)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://go.microsoft.com/fwlink/?linkid=139852)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://go.microsoft.com/fwlink/?linkid=139107)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://go.microsoft.com/fwlink/?linkid=146659)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://go.microsoft.com/fwlink/?linkid=132587)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://go.microsoft.com/fwlink/?linkid=146803)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
(уровень опасности не определен)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=552d322a-5282-42c7-9c1e-1d8c494a7318)  
(KB923561)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=39d5468e-5733-4c3e-9e75-3adac8ac8cb9)  
(критический)
</td>
<td style="border:1px solid black;">
[DirectX 8.1](http://www.microsoft.com/downloads/details.aspx?familyid=0ec5b7c7-13d3-467a-b24e-3cc6fb47adf6)  
(критический)  
[DirectX 9.0 ](http://www.microsoft.com/downloads/details.aspx?familyid=8b98ed5c-a3ab-45a7-a61e-349eae304bc6)\*\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=7799fd05-5b26-449f-8a14-50227c9164d1)  
(критический)  
[Microsoft Internet Explorer 6 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=87f0c380-5c31-4099-a6a9-c12f9d69b03b)  
(критический)
</td>
<td style="border:1px solid black;">
Обновление для средства проведения транзакций MSDTC:  
[Microsoft Windows 2000 с пакетом обновления 4 (SP4);](http://www.microsoft.com/downloads/details.aspx?familyid=52b756e7-636f-4d9e-8a17-dbf467bfbe4d)  
(KB952004)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=c4e408d7-6716-4a12-ad3a-8029667f5c84)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<th colspan="7">
ОС Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://go.microsoft.com/fwlink/?linkid=139849)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://go.microsoft.com/fwlink/?linkid=139852)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://go.microsoft.com/fwlink/?linkid=139107)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://go.microsoft.com/fwlink/?linkid=146659)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://go.microsoft.com/fwlink/?linkid=132587)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://go.microsoft.com/fwlink/?linkid=146803)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP с пакетом обновления 2 (SP2) или 3 (SP3)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2) и Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=50a8519a-503e-43dd-a78a-c1bc764fd213)  
(KB923561)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2) и Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=35af4151-1858-4c9a-85e4-9ff45feca1a4)  
(критический)
</td>
<td style="border:1px solid black;">
[DirectX 9.0 ](http://www.microsoft.com/downloads/details.aspx?familyid=feb5d821-f210-40e8-b1aa-2ca3170df8df)\*\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=052c29fc-e8df-402c-9ab1-1079bc738e1b)  
(критический)  
[Обозреватель Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=55d6729a-9f96-4da4-b564-676c0a0c9390)  
(критический)
</td>
<td style="border:1px solid black;">
Обновление для средства проведения транзакций MSDTC:  
[Windows XP с пакетом обновления 2 (SP2) или 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=90fe715e-8190-43e9-9c43-df5be564d923)  
(KB952004)  
(существенный)  
Обновление для изоляции служб Windows:  
[Windows XP с пакетом обновления 2 (SP2) или 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=73d2324f-be59-4b0c-b1ac-9876a13c2c03)  
(KB956572)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2) и Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=3de0684d-605c-489b-bdc7-08bce9b2d4f6)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=323f4211-5add-4e02-bce1-e5a1b489982c)  
(KB923561)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=49b16f0f-f6c3-4ca8-8041-392f4f7b5bbb)  
(критический)
</td>
<td style="border:1px solid black;">
[DirectX 9.0 ](http://www.microsoft.com/downloads/details.aspx?familyid=f1be8b7c-4874-4342-99b3-76ff725fbb9a)\*\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=84c62211-2e82-4ccc-9f9b-26462b026d86)  
(критический)  
[Обозреватель Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=191c2f20-89ae-4e1c-bdd4-24b4abfe6b6c)  
(критический)
</td>
<td style="border:1px solid black;">
Обновление для средства проведения транзакций MSDTC:  
[Windows XP Professional x64 Edition и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a794c32a-9a0c-47d9-9c57-ff5d4a8e4944)  
(KB952004)  
(существенный)  
Обновление для изоляции служб Windows:  
[Windows XP Professional x64 Edition и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b2f12ae5-0e46-47e1-ac5b-93550d030189)  
(KB956572)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b743a7fe-7bf4-420d-a72e-39471e5659fa)  
(средний)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://go.microsoft.com/fwlink/?linkid=139849)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://go.microsoft.com/fwlink/?linkid=139852)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://go.microsoft.com/fwlink/?linkid=139107)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://go.microsoft.com/fwlink/?linkid=146659)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://go.microsoft.com/fwlink/?linkid=132587)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://go.microsoft.com/fwlink/?linkid=146803)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2233a4d2-7c8a-4c89-b020-100d9afb43c8)  
(KB923561)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=42509f5a-d0f9-444a-9445-5eabdb555011)  
(критический)
</td>
<td style="border:1px solid black;">
[DirectX 9.0 ](http://www.microsoft.com/downloads/details.aspx?familyid=c1b4cd76-1dd6-43fa-bb9a-20c428985bfd)\*\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=f73a3669-c17f-4b18-8456-96cb7d52ed86)  
(существенный)  
[Обозреватель Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6a45dbd0-0520-4d9b-b76e-3f5109dd310d)  
(существенный)
</td>
<td style="border:1px solid black;">
Обновление для средства проведения транзакций MSDTC:  
[Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=25adec10-db8c-4cac-bf74-2c784678150a)  
(KB952004)  
(существенный)  
Обновление для изоляции служб Windows:  
[Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=42aba890-8b76-4c5a-8fb6-609797d19831)  
(KB956572)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=992bb0cd-fbc7-4a7c-9088-f7f9d9a3ead0)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=323f4211-5add-4e02-bce1-e5a1b489982c)  
(KB923561)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7373ea32-bc2e-49f1-8b9f-4eeda5acc74c)  
(критический)
</td>
<td style="border:1px solid black;">
[DirectX 9.0 ](http://www.microsoft.com/downloads/details.aspx?familyid=f0e1e1db-94a5-451c-ab11-6b431fa065f1)\*\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=03a9d581-2bd5-4151-9826-17b96e16f606)  
(существенный)  
[Обозреватель Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=60ccc1d6-ea31-420c-b630-d7878a8dc527)  
(существенный)
</td>
<td style="border:1px solid black;">
Обновление для средства проведения транзакций MSDTC:  
[Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b014c399-f404-4cb2-8f9d-864df382efeb)  
(KB952004)  
(существенный)  
Обновление для изоляции служб Windows:  
[Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a0609f65-82d9-4d82-9f48-f3266e8de123)  
(KB956572)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=f0a58e8c-7d63-4d7d-ba95-b3787cf408f0)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium и Windows Server 2003 с пакетом обновления 2 (SP2) для платформы Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium и Windows Server 2003 с пакетом обновления 2 (SP2) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=e840b9cb-f1f4-482a-aa07-eb6b42b477c4)  
(KB923561)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium и Windows Server 2003 с пакетом обновления 2 (SP2) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=05e33cc5-cff6-4c71-be71-285f66a95e01)  
(критический)
</td>
<td style="border:1px solid black;">
[DirectX 9.0 ](http://www.microsoft.com/downloads/details.aspx?familyid=8f36c215-fa8a-40c2-b680-6b1fece03b8d)\*\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=53d13c07-80b0-4f05-b372-a2dac17e6157)  
(существенный)  
[Обозреватель Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0abaa2fb-7c4f-4149-993d-1575888bfc84)  
(существенный)
</td>
<td style="border:1px solid black;">
Обновление для средства проведения транзакций MSDTC:  
[Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium и Windows Server 2003 с пакетом обновления 2 (SP2) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=6ada372b-ba17-433e-b022-d2c57b35af8a)  
(KB952004)  
(существенный)  
Обновление для изоляции служб Windows:  
[Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium и Windows Server 2003 с пакетом обновления 2 (SP2) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=fda8837c-e5d2-4489-9b44-4c24a1102e77)  
(KB956572)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium и Windows Server 2003 с пакетом обновления 2 (SP2) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=00c6479d-f81f-445d-b8e4-7b71d77d540a)  
(средний)
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://go.microsoft.com/fwlink/?linkid=139849)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://go.microsoft.com/fwlink/?linkid=139852)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://go.microsoft.com/fwlink/?linkid=139107)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://go.microsoft.com/fwlink/?linkid=146659)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://go.microsoft.com/fwlink/?linkid=132587)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://go.microsoft.com/fwlink/?linkid=146803)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Отсутствует
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista и Windows Vista с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Vista и Windows Vista с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=f071d770-3b6b-4040-9911-d4de8cde4c68)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d743849d-f3b5-4114-adef-ade2716d55ac)  
(критический)
</td>
<td style="border:1px solid black;">
Обновление для средства проведения транзакций MSDTC:  
[Windows Vista и Windows Vista с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=f111b99a-e555-4f29-8d1f-e9ec03d5cf1f)  
(KB952004)  
(существенный)  
Обновление для изоляции служб Windows:  
[Windows Vista и Windows Vista с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d0ea1598-45cb-4c79-8945-caae98969675)  
(KB956572)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista и Windows Vista с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=2b672d45-f33b-4edc-9f22-2f2c8c726a8b)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition и Windows Vista x64 Edition с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition и Windows Vista x64 Edition с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=7ceef2d0-f316-48d1-aecc-d74f91cc5e1f)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d191c8dc-a965-4a6a-b6d8-1470505eb55f)  
(критический)
</td>
<td style="border:1px solid black;">
Обновление для средства проведения транзакций MSDTC:  
[Windows Vista x64 Edition и Windows Vista x64 Edition с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=fa153bdc-6b48-4df2-9e5e-abacd6da782c)  
(KB952004)  
(существенный)  
Обновление для изоляции служб Windows:  
[Windows Vista x64 Edition и Windows Vista x64 Edition с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=6dd82f4b-bb33-41ec-90a7-9ef91329b240)  
(KB956572)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition и Windows Vista x64 Edition с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=7576e7d5-5bb1-4a53-b568-1ee0500ce721)  
(средний)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://go.microsoft.com/fwlink/?linkid=139849)
</td>
<td style="border:1px solid black;">
[**MS09-013**](http://go.microsoft.com/fwlink/?linkid=139852)
</td>
<td style="border:1px solid black;">
[**MS09-011**](http://go.microsoft.com/fwlink/?linkid=139107)
</td>
<td style="border:1px solid black;">
[**MS09-014**](http://go.microsoft.com/fwlink/?linkid=146659)
</td>
<td style="border:1px solid black;">
[**MS09-012**](http://go.microsoft.com/fwlink/?linkid=132587)
</td>
<td style="border:1px solid black;">
[**MS09-015**](http://go.microsoft.com/fwlink/?linkid=146803)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем ](http://www.microsoft.com/downloads/details.aspx?familyid=4c36548f-c8c9-4318-91e2-9e0501339548)\*  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e2c6313c-3ba9-4f7c-b259-b4582a390146)\*\*  
(существенный)
</td>
<td style="border:1px solid black;">
Обновление для средства проведения транзакций MSDTC:  
[Windows Server 2008 для 32-разрядных систем ](http://www.microsoft.com/downloads/details.aspx?familyid=9e3c7b52-65a7-42fb-beb5-1b374934737f)\*  
(KB952004)  
(существенный)  
Обновление для изоляции служб Windows:  
[Windows Server 2008 для 32-разрядных систем ](http://www.microsoft.com/downloads/details.aspx?familyid=d58702af-bbf8-4f1b-ae72-ced9ef23d581)\*  
(KB956572)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем ](http://www.microsoft.com/downloads/details.aspx?familyid=6b73cf5e-66fe-4b7d-95fc-91a1c262c1e5)\*  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем ](http://www.microsoft.com/downloads/details.aspx?familyid=1c3f0997-a8a9-4340-ae0c-2c4d6792c65c)\*  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ebbade9d-704c-440b-8796-6d64225ac01a)\*\*  
(существенный)
</td>
<td style="border:1px solid black;">
Обновление для средства проведения транзакций MSDTC:  
[Windows Server 2008 для 64-разрядных систем ](http://www.microsoft.com/downloads/details.aspx?familyid=eebb4d4d-29d2-4247-8cbb-63a3b17585ec)\*  
(KB952004)  
(существенный)  
Обновление для изоляции служб Windows:  
[Windows Server 2008 для 64-разрядных систем ](http://www.microsoft.com/downloads/details.aspx?familyid=20bf4e9b-909b-4bc3-ae43-322d74a4f1c3)\*  
(KB956572)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем ](http://www.microsoft.com/downloads/details.aspx?familyid=7e60847c-b341-4c38-bc25-2e3cf2d4ae14)\*  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для платформы Itanium
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=0885b3b0-b78e-4980-902d-dff3886bcaac)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1b04aa6f-b787-4122-bf82-0d150618fe7a)  
(существенный)
</td>
<td style="border:1px solid black;">
Обновление для средства проведения транзакций MSDTC:  
[Windows Server 2008 для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=cc383c24-b0f6-47c1-9e89-6a378b09e82f)  
(KB952004)  
(существенный)  
Обновление для изоляции служб Windows:  
[Windows Server 2008 для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=bcc2b18f-67db-4109-a9f4-764f985423ee)  
(KB956572)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=de1c2b4b-af47-4b9a-8363-720e5527573c)  
(средний)
</td>
</tr>
</table>
 
**Примечания для сервера Windows Server 2008**

**\* Подверженные уязвимости системы Windows Server 2008, при развертывании которых устанавливались основные компоненты сервера.** Это обновление имеет одинаковый уровень опасности для поддерживаемых выпусков Windows Server 2008, независимо от того, выбиралась ли установка основных компонентов сервера при их развертывании или нет. Дополнительные сведения об этом варианте установки см. в статье [Основные компоненты сервера](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (на английском языке). Обратите внимание, что установка основных компонентов сервера недоступна в определенных выпусках Windows Server 2008; см. статью [Сравнение параметров установки основных компонентов сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (на английском языке).

**\*\* Не подверженные уязвимости системы Windows Server 2008, при развертывании которых устанавливались основные компоненты сервера.** Поддерживаемые выпуски Windows Server 2008, при развертывании которых выбиралась установка основных компонентов сервера, не подвержены уязвимости, устраняемой этим обновлением. Дополнительные сведения об этом варианте установки см. в статье [Основные компоненты сервера](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (на английском языке). Обратите внимание, что установка основных компонентов сервера недоступна в определенных выпусках Windows Server 2008; см. статью [Сравнение параметров установки основных компонентов сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (на английском языке).

**Примечание к бюллетеню MS09-010**

Сведения о дополнительных файлах обновления см. также в следующем разделе **Наборы приложений и прочие программные продукты Office**. Этот бюллетень относится как к операционной системе Windows и ее компонентам, так и к наборам приложений и прочим программным продуктам Microsoft Office.

**Примечание к бюллетеню MS09-011**

\*\*\* Обновление для компонента DirectX 9.0 также применимо к DirectX 9.0a, DirectX 9.0b и DirectX 9.0c.

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
Наборы приложений, системы и компоненты Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://go.microsoft.com/fwlink/?linkid=139849)
</td>
<td style="border:1px solid black;">
[**MS09-009**](http://go.microsoft.com/fwlink/?linkid=143568)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2000 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=95876927-e612-414c-bdec-3632a3100415)  
(KB921606)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2000 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=3dc8b670-25a5-4f46-b7de-12bc693b628a)  
(KB959964)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=e1db55c6-78fb-498d-89a5-9ad54d971546)  
(KB933399)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=9a52bf4b-05f6-4b73-94b9-28ed7e20f86c)  
(KB959988)  
(существенный)
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
[Microsoft Office Excel 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=d9dbfa63-c0cb-4c84-9b8a-6e52568045b0)  
(KB959995)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Выпуск 2007 системы Microsoft Office с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 с пакетом обновления 1 (SP1) ](http://www.microsoft.com/downloads/details.aspx?familyid=50d8630b-1365-4007-81a0-18c0d6d4b86e)\*  
(KB959997)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office для Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-010**](http://go.microsoft.com/fwlink/?linkid=139849)
</td>
<td style="border:1px solid black;">
[**MS09-009**](http://go.microsoft.com/fwlink/?linkid=143568)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 для Mac
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=52271140-89be-4b9c-baa2-cea09097d703)  
(KB968695)  
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
[Microsoft Office 2008 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=f6e407eb-11a5-433f-8006-4b822953ca98)  
(KB968694)  
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
[**MS09-010**](http://go.microsoft.com/fwlink/?linkid=139849)
</td>
<td style="border:1px solid black;">
[**MS09-009**](http://go.microsoft.com/fwlink/?linkid=143568)
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
</tr>
<tr>
<td style="border:1px solid black;">
Средство просмотра Microsoft Office Excel
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Средство просмотра Microsoft Office Excel 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=c72e6087-b48f-4d2d-8366-01d9f5ff6b6c)  
(KB959993)  
(существенный)  
[Средство просмотра Microsoft Office Excel](http://www.microsoft.com/downloads/details.aspx?familyid=58b3929c-5373-47a4-aa97-66d179758792)  
(KB960000)  
(существенный)
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
[Пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=05f7c517-e551-4dcd-b24a-5d548f2d09cf)  
(KB960003)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Converter Pack
</td>
<td style="border:1px solid black;">
[Microsoft Office Converter Pack](http://www.microsoft.com/downloads/details.aspx?familyid=d763fae3-b2af-47f9-a554-ec786766b3c3)  
(KB960476)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 
**Примечание к бюллетеню MS09-010**

Сведения о дополнительных файлах обновления см. также в разделе **Компоненты операционных систем Windows**. Этот бюллетень относится как к операционной системе Windows и ее компонентам, так и к серверному программному обеспечению Майкрософт.

**Примечание к бюллетеню MS09-009**

\* Пользователям Microsoft Office Excel 2007 с пакетом обновления 1 (SP1) потребуется также установить обновление для системы безопасности пакета обеспечения совместимости форматов файлов Microsoft Office Word, Excel и PowerPoint 2007 с пакетом обновления 1 (SP1), чтобы защитить компьютеры от уязвимостей, описанных в этом бюллетене.

#### Серверное программное обеспечение Майкрософт и программы для обеспечения безопасности

 
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
[**MS09-016**](http://go.microsoft.com/fwlink/?linkid=141639)
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
Microsoft Forefront Threat Management Gateway
</td>
<td style="border:1px solid black;">
[Microsoft Forefront Threat Management Gateway Medium Business Edition ](http://www.microsoft.com/downloads/details.aspx?familyid=6abf9fb4-42d0-4c67-935f-8dc67850148b)\*  
(KB968075)  
(существенный)
</td>
</tr>
<tr>
<th colspan="2">
Internet Security and Acceleration Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-016**](http://go.microsoft.com/fwlink/?linkid=141639)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2004 Standard Edition с пакетом обновления 3 (SP3) ](http://www.microsoft.com/downloads/details.aspx?familyid=adf623fa-2d74-4f2a-9835-4b8debdb0e1b)\*\*  
(KB960995)  
(существенный)  
[Microsoft Internet Security and Acceleration Server 2004 Enterprise Edition с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=d1d55ab6-3de5-4811-9693-8d43f49f5fe8)  
(KB960995)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006](http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770)  
(KB968078)  
(существенный)  
[Обновление по поддержке для Microsoft Internet Security and Acceleration Server 2006](http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770)  
(KB968078)  
(существенный)  
[Microsoft Internet Security and Acceleration Server 2006 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770)  
(KB968078)  
(существенный)
</td>
</tr>
</table>
 
**Примечание к бюллетеню MS09-016**

\* Microsoft Forefront Threat Management Gateway Medium Business Edition может предоставляться как автономный продукт и как компонент Windows Essential Business Server 2008.

\*\* Microsoft ISA Server 2004 Standard Edition предоставляется как автономный продукт. Microsoft ISA Server 2004 Standard Edition также предоставляется как компонент Windows Small Business Server 2003 Enterprise Edition с пакетом обновления 1 (SP1) и Windows Small Business Server 2003 R2 Enterprise Edition.

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
**В центре безопасности**

Управление программным обеспечением и обновлениями для системы безопасности для установки на серверы, настольные и переносные компьютеры организации. Дополнительные сведения см. на веб-узле [центра TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [Центр безопасности TechNet](http://go.microsoft.com/fwlink/?linkid=21171) содержит дополнительные сведения о безопасности в продуктах Майкрософт. Доступ к этим сведениям можно также получить, посетив веб-сайт [Безопасность дома](http://go.microsoft.com/fwlink/?linkid=85102) и щелкнув ссылку "Последние обновления".

Обновления для системы безопасности доступны на веб-узлах [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747), [Центра обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130) и [центра загрузки Office](http://go.microsoft.com/fwlink/?linkid=21135). Обновления для системы безопасности также доступны на веб-узле [центра загрузки Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову security update.

Наконец, обновления для системы безопасности можно загрузить из [каталога Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=96155). Он обеспечивает возможность поиска содержимого (в том числе обновлений для системы безопасности, драйверов и пакетов обновления), которое предоставляется через Центр обновления Windows и Центр обновления Майкрософт. При поиске по номеру бюллетеня по безопасности (например, MS07-036) можно добавлять необходимые обновления (в том числе на различных языках) в корзину и загружать их в указанную папку. Дополнительные сведения см. на веб-узле [Каталог Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=97900) в разделе "Вопросы и ответы".

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

-   [Статья 894199 базы знаний Майкрософт](http://support.microsoft.com/kb/894199). Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
-   [Новые, исправленные и выпущенные обновления для продуктов Майкрософт, отличных от Microsoft Windows](http://technet.microsoft.com/en-us/wsus/dd573344.aspx).

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

-   Хайфэя Ли (Haifei Li) из отдела [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-009;
-   Шона Ларсона (Sean Larsson) и Цзюнь Мао (Jun Mao) из компании [VeriSign iDefense Labs](http://labs.idefense.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-010;
-   исследователя из отдела [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) компании Fortinet за сообщение о проблеме, описанной в бюллетене по безопасности MS09-010;
-   исследователя из отдела [VeriSign iDefense Labs](http://labs.idefense.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-010;
-   Петра Баню (Piotr Bania) из компании [Kryptos Logic](http://www.kryptoslogic.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-011;
-   Цезаря Черрудо (Cesar Cerrudo) из компании [Argeniss](http://www.argeniss.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-012;
-   Грега Мак-Мануса (Greg MacManus) из компании [iSIGHT Partners Labs](http://www.isightpartners.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-013;
-   Вань Дэ Чжан (Wan-Teh Chang) и Джема Пайю (Cem Paya) из компании [Google Inc.](http://www.google.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-013;
-   [Авива Раффа (Aviv Raff](http://aviv.raffon.net/)) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-014;
-   Михаля Залевски (Michal Zalewski) компании [Google Inc.](http://www.google.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-014;
-   Ивана Фратрича (Ivan Fratric) из компании [iSIGHT Partners Labs](http://www.isightpartners.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-014;
-   пользователя Skylined из компании [Google Inc.](http://www.google.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-014;
-   пользователя ADLab из компании [Venustech](http://www.venustech.com.cn/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-014;
-   [Авива Раффа (Aviv Raff)](http://aviv.raffon.net/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-015;
-   ИТ-директора (шт. Нью-Йорк)/агентство New York State Office for Technology за сообщение о проблеме, описанной в бюллетене по безопасности MS09-016.

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов можно найти на веб-узле [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).
-   Пользователи из США и Канады могут обратиться в службу [поддержки по вопросам безопасности](http://go.microsoft.com/fwlink/?linkid=21131) или позвонить по телефону 1-866-PCSAFETY. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Дополнительные сведения о вариантах поддержки см. на веб-узле [справки и поддержки корпорации Майкрософт](http://support.microsoft.com?ln=ru).
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-узел международной поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (14 апреля 2009 г.). Обзор бюллетеней опубликован.
-   Версия 1.1 (16 апреля 2009 г.). Обновлен указатель использования уязвимости: удалены ключевые примечания для уязвимости CVE-2009-0089 и изменены ключевые примечания для уязвимости CVE-2008-2540 в бюллетенях MS09-014 и MS09-015.

*Built at 2014-04-18T01:50:00Z-07:00*
