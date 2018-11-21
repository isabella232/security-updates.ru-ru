---
TOCTitle: 'MS13-MAY'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за май 2013 года'
ms:assetid: 'ms13-may'
ms:contentKeyID: 61236175
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms13-may(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за май 2013 года
==============================================================

Дата публикации: 14 мая 2013 г. | Дата обновления: 22 мая 2013 г.

**Версия:** 1.1

В этот обзор включены бюллетени по безопасности, выпущенные в мае 2013 года.

После выпуска бюллетеней за май 2013 года этот обзор заменит предварительное уведомление, выпущенное 9 мая 2013 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

15 мая 2013 года в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в майской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538728&culture=en-us). После наступления этой даты данная веб-трансляция будет доступна [по запросу](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538728&culture=en-us).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел **Прочие сведения**.

### Сведения о бюллетене

#### Аннотации

В приведенной ниже таблице описаны бюллетени по безопасности за этот месяц в порядке, соответствующем уровню опасности.

Сведения об уязвимом программном обеспечении см. в следующем разделе, **Подвержены уязвимости**.

 
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (2829530)<br />
<br />
</strong>Это обновление для системы безопасности устраняет 11 обнаруженных пользователями уязвимостей в Internet Explorer. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь просмотрит особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся наиболее серьезными из данных уязвимостей, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299892">MS13-038</a></td>
<td style="border:1px solid black;"><strong>Обновление для системы безопасности Internet Explorer (2847204)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну опубликованную уязвимость в Internet Explorer. Она делает возможным удаленное выполнение кода, если пользователь открывает специально созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293363">MS13-039</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в HTTP.sys делает возможной атаку типа &quot;отказ в обслуживании&quot; (2829254)</strong> <strong><br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным отказ в обслуживании, если злоумышленник отправляет уязвимому серверу или клиенту Windows специально созданный HTTP-пакет.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296485">MS13-040</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в .NET Framework делают возможной подмену содержимого (2836440)<br />
<br />
</strong>Это обновление для системы безопасности устраняет одну обнаруженную пользователями и одну опубликованную уязвимость<strong></strong>в .NET Framework. Наиболее серьезная из этих уязвимостей делает возможной подмену содержимого, если приложение .NET получит специально созданный XML-файл. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может изменить содержимое XML-файла без нарушения подписи файла и получить доступ к функциям конечной точки, как если бы он был пользователем, прошедшим проверку подлинности.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Спуфинг</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293445">MS13-041</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Lync делает возможным удаленное выполнение кода (2834695)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Lync. Эта уязвимость делает возможным удаленное выполнение кода, если злоумышленник предоставляет общий доступ к специально созданному содержимому, такому как файл или программа, как презентации в Lync или Communicator, а затем убеждает пользователя принять приглашение просмотреть используемое в презентации содержимое или предоставить к нему общий доступ. Во всех случаях злоумышленник не может заставить пользователя просмотреть подконтрольные злоумышленнику файл или программу, или предоставить к ним общий доступ. Вместо этого злоумышленнику придется убедить их выполнить некоторое действие: обычно предлагается принять приглашение в Lync или Communicator просмотреть используемый в презентации содержимое или предоставить к нему доступ.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Lync</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;"><strong>Уязвимости приложения Microsoft Publisher делают возможным удаленное выполнение кода (2830397)<br />
<br />
</strong>Это обновление для системы безопасности устраняет 11 обнаруженных пользователями уязвимостей в Microsoft Office. Эти уязвимости делают возможным удаленное выполнение кода в случае, если пользователь откроет специально созданный файл Publisher в уязвимой версии Microsoft Publisher. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287107">MS13-043</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Word делает возможным удаленное выполнение кода (2830399)</strong> <strong><br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Office. Данная уязвимость делает возможным выполнение кода, если пользователь открывает специально созданный файл или предварительно просматривает специально созданное сообщение электронной почты в уязвимой версии программного обеспечения Microsoft Office. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293446">MS13-044</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Visio может привести к раскрытию информации (2834692)<br />
<br />
</strong>Это обновление для системы безопасности устраняет уязвимость в пакете Microsoft Office, о которой сообщалось в частном порядке. Данная уязвимость может привести к раскрытию информации, если пользователь открывает специально созданный файл Visio. Данная уязвимость не позволяет злоумышленнику выполнить код или напрямую повысить уровень своих пользовательских прав, но может быть использована для получения сведений, которые понадобятся для дальнейших атак на уязвимую систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Раскрытие информации</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=280675">MS13-045</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Windows Essentials может привести к раскрытию информации (2813707)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Windows Essentials. Данная уязвимость может привести к раскрытию информации, если пользователь открывает Редактор блогов Windows с помощью специально созданного URL-адреса. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может переопределить настройки прокси Редактора блогов Windows и перезаписать файлы, доступные пользователю в целевой системе. В случае атаки через Интернет на веб-сайте злоумышленника должна быть размещена специально созданная ссылка, которая служит для использования этой уязвимости. Чтобы атака достигла цели, злоумышленник должен убедить пользователя посетить этот веб-сайт и перейти по специально созданной ссылке.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Раскрытие информации</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows Essentials</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296427">MS13-046</a></td>
<td style="border:1px solid black;"><strong>Уязвимости</strong> <strong>драйверов в режиме ядра делают возможным несанкционированное получение прав (2840221)</strong><br />
<br />
Это обновление для системы безопасности устраняет три обнаруженных пользователями уязвимости в Microsoft Windows. Эти уязвимости делают возможным несанкционированное получение прав, если злоумышленник войдет в систему и запустит специально созданное приложение. Чтобы воспользоваться данными уязвимостями, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием Internet Explorer после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0811">CVE-2013-0811</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Уязвимость массива JSON, приводящая к раскрытию информации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1297">CVE-2013-1297</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием Internet Explorer после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1306">CVE-2013-1306</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием Internet Explorer после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1307">CVE-2013-1307</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием Internet Explorer после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1308">CVE-2013-1308</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием Internet Explorer после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1309">CVE-2013-1309</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием Internet Explorer после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1310">CVE-2013-1310</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием Internet Explorer после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1311">CVE-2013-1311</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием Internet Explorer после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1312">CVE-2013-1312</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием Internet Explorer после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-2551">CVE-2013-2551</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием Internet Explorer после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3140">CVE-2013-3140</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299892">MS13-038</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием Internet Explorer после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1347">CVE-2013-1347</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.<br />
<br />
Специалистам Майкрософт известно об атаках с целью использования этой уязвимости через Internet Explorer 8.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293363">MS13-039</a></td>
<td style="border:1px solid black;">Уязвимость в HTTP.sys, приводящая к отказу в обслуживании</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1305">CVE-2013-1305</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296485">MS13-040</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с подменой цифровых подписей XML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1336">CVE-2013-1336</a></td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, которая делает возможным спуфинг.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296485">MS13-040</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с обходом проверки подлинности</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1337">CVE-2013-1337</a></td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.<br />
<br />
Это уязвимость, связанная с обходом функций безопасности.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293445">MS13-041</a></td>
<td style="border:1px solid black;">Уязвимость Lync RCE</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1302">CVE-2013-1302</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Уязвимость Publisher, связанная с назначением отрицательных значений</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1316">CVE-2013-1316</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Уязвимость Publisher, связанная с переполнением целочисленного значения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1317">CVE-2013-1317</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Уязвимость Publisher, связанная с поврежденным указателем на интерфейс</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1318">CVE-2013-1318</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Уязвимость Publisher, связанная с обработкой возвращенных значений</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1319">CVE-2013-1319</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Уязвимость Publisher, приводящая к переполнению буфера</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1320">CVE-2013-1320</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Уязвимость Publisher, связанная с проверкой возвращенных значений</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1321">CVE-2013-1321</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Уязвимость Publisher, связанная с проверкой недопустимых диапазонов</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1322">CVE-2013-1322</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Уязвимость Publisher, связанная с неверной обработкой ПУСТОГО значения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1323">CVE-2013-1323</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Уязвимость Publisher, связанная со знаковыми целыми числами</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1327">CVE-2013-1327</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Уязвимость Publisher, связанная с обработкой указателя</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1328">CVE-2013-1328</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Уязвимость Publisher, приводящая к незаполнению буфера</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1329">CVE-2013-1329</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287107">MS13-043</a></td>
<td style="border:1px solid black;">Уязвимость Word, приводящая к повреждению фигуры</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1335">CVE-2013-1335</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293446">MS13-044</a></td>
<td style="border:1px solid black;">Уязвимость разрешения внешних сущностей XML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1301">CVE-2013-1301</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=280675">MS13-045</a></td>
<td style="border:1px solid black;">Уязвимость в Windows Essentials, связанная с неправильной обработкой URI</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0096">CVE-2013-0096</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296427">MS13-046</a></td>
<td style="border:1px solid black;">Уязвимость подсистемы графического ядра DirectX, связанная с двойной выборкой</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1332">CVE-2013-1332</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296427">MS13-046</a></td>
<td style="border:1px solid black;">Уязвимость Win32k, связанная с переполнением буфера</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1333">CVE-2013-1333</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296427">MS13-046</a></td>
<td style="border:1px solid black;">Уязвимость в Win32K, связанная с дескрипторами окон</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1334">CVE-2013-1334</a></td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
</tbody>
</table>
  
Подвержены уязвимости  
---------------------
  
<span></span>
В приведенных ниже таблицах перечислены бюллетени в порядке важности категорий программного обеспечения и уровней опасности.
  
**Как пользоваться этими таблицами?**
  
Обращайтесь к этим таблицам, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и узнайте, имеются ли для них обновления для системы безопасности. Если программное обеспечение или компонент содержится в списке, для него также указан уровень важности соответствующего обновления программного обеспечения.
  
**Примечание.** Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификатора бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.
  
#### Компоненты операционных систем Windows

 
<table style="border:1px solid black;">
<tr>
<th colspan="6">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
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
**Нет**
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
Internet Explorer 6  
(2829530)  
(критический)  
Internet Explorer 7  
(2829530)  
(критический)  
Internet Explorer 8  
(2829530)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2804577)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)  
(2829361)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2829530)  
(критический)  
Internet Explorer 7  
(2829530)  
(критический)  
Internet Explorer 8  
(2829530)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2804577)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2829361)  
(существенный)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
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
**Нет**
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
Internet Explorer 6  
(2829530)  
(средний)  
Internet Explorer 7  
(2829530)  
(средний)  
Internet Explorer 8  
(2829530)  
(средний)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2804577)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2829530)  
(средний)  
Internet Explorer 7  
(2829530)  
(средний)  
Internet Explorer 8  
(2829530)  
(средний)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2804577)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2829530)  
(средний)  
Internet Explorer 7  
(2829530)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2804577)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
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
**Нет**
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
Internet Explorer 7  
(2829530)  
(критический)  
Internet Explorer 8  
(2829530)  
(критический)  
Internet Explorer 9  
(2829530)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(критический)  
Internet Explorer 9  
(2847204)  
(уровень опасности не определен)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2804580)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(существенный)  
Microsoft .NET Framework 4.5  
(2804582)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2830290)  
(существенный)  
Windows Vista с пакетом обновления 2 (SP2)  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
(критический)  
Internet Explorer 8  
(2829530)  
(критический)  
Internet Explorer 9  
(2829530)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(критический)  
Internet Explorer 9  
(2847204)  
(уровень опасности не определен)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2804580)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(существенный)  
Microsoft .NET Framework 4.5  
(2804582)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2830290)  
(существенный)  
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
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
**Нет**
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
Internet Explorer 7  
(2829530)  
(средний)  
Internet Explorer 8  
(2829530)  
(средний)  
Internet Explorer 9  
(2829530)  
(средний)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(средний)  
Internet Explorer 9  
(2847204)  
(уровень опасности не определен)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2804580)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(существенный)  
Microsoft .NET Framework 4.5  
(2804582)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2830290)  
(существенный)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
(средний)  
Internet Explorer 8  
(2829530)  
(средний)  
Internet Explorer 9  
(2829530)  
(средний)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(средний)  
Internet Explorer 9  
(2847204)  
(уровень опасности не определен)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2804580)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(существенный)  
Microsoft .NET Framework 4.5  
(2804582)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2830290)  
(существенный)  
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2804580)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2830290)  
(существенный)  
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<th colspan="6">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
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
**Нет**
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
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2829530)  
(критический)  
Internet Explorer 9  
(2829530)  
(критический)  
Internet Explorer 10  
(2829530)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(критический)  
Internet Explorer 9  
(2847204)  
(уровень опасности не определен)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(существенный)  
Microsoft .NET Framework 4.5  
(2804582)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2830290)  
(существенный)  
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2829361)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2829530)  
(критический)  
Internet Explorer 9  
(2829530)  
(критический)  
Internet Explorer 10  
(2829530)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(критический)  
Internet Explorer 9  
(2847204)  
(уровень опасности не определен)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(существенный)  
Microsoft .NET Framework 4.5  
(2804582)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2830290)  
(существенный)  
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2829361)  
(существенный)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
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
**Нет**
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
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2829530)  
(средний)  
Internet Explorer 9  
(2829530)  
(средний)  
Internet Explorer 10  
(2829530)  
(средний)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(средний)  
Internet Explorer 9  
(2847204)  
(уровень опасности не определен)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(существенный)  
Microsoft .NET Framework 4.5  
(2804582)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2830290)  
(существенный)  
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2829530)  
(средний)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2830290)  
(существенный)  
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<th colspan="6">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
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
Internet Explorer 10  
(2829530)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2829254)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2804584)  
(существенный)  
Microsoft .NET Framework 4.5  
(2804583)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2830290)  
(существенный)  
Windows 8 для 32-разрядных систем  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2829530)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2829254)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2804584)  
(существенный)  
Microsoft .NET Framework 4.5  
(2804583)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2830290)  
(существенный)  
Windows 8 для 64-разрядных систем  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2829530)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2829254)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2804584)  
(существенный)  
Microsoft .NET Framework 4.5  
(2804583)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2830290)  
(существенный)  
Windows Server 2012  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<th colspan="6">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2829530)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows RT  
(2829254)  
(средний)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2804583)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows RT  
(2830290)  
(существенный)  
Windows RT  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<th colspan="6">
Вариант установки ядра сервера
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
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
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2830290)  
(существенный)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2829361)  
(уровень опасности не определен)
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
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2830290)  
(существенный)  
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
<tr>
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
Microsoft .NET Framework 3.5.1  
(2804579)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2804576)  
(существенный)  
Microsoft .NET Framework 4.5  
(2804582)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2830290)  
(существенный)  
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
<tr class="alternateRow">
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
Windows Server 2012 (установка основных серверных компонентов)  
(2829254)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2804584)  
(существенный)  
Microsoft .NET Framework 4.5  
(2804583)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(2830290)  
(существенный)  
Windows Server 2012 (установка основных серверных компонентов)  
(2829361)  
(уровень опасности не определен)
</td>
</tr>
</table>
 
**Примечание к бюллетеню MS13-040**

<sup>[1]</sup>**Уязвимости подвержены NET Framework 4 и клиентский профиль .NET Framework 4** Предлагаются два профиля для распространяемых пакетов .NET Framework версии 4: .NET Framework 4 и клиентский профиль .NET Framework 4. Клиентский профиль .NET Framework 4 является частью .NET Framework 4. Уязвимости, устраняемой данным обновлением, подвержены как платформа .NET Framework 4, так и клиентский профиль .NET Framework 4. Дополнительные сведения см. в статье MSDN [Установка .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Пакеты приложений и программные продукты Microsoft Office

 
<table style="border:1px solid black;">
<tr>
<th colspan="4">
Программное обеспечение Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-042**](http://go.microsoft.com/fwlink/?linkid=287106)
</td>
<td style="border:1px solid black;">
[**MS13-043**](http://go.microsoft.com/fwlink/?linkid=287107)
</td>
<td style="border:1px solid black;">
[**MS13-044**](http://go.microsoft.com/fwlink/?linkid=293446)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Microsoft Office Publisher 2003 с пакетом обновления 3 (SP3)  
(2810047)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft Word 2003 с пакетом обновления 3 (SP3)  
(2810046)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Microsoft Publisher 2007 с пакетом обновления 3 (SP3)  
(2597971)  
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
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Microsoft Publisher 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(2553147)  
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
Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Microsoft Publisher 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(2553147)  
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
Средство просмотра Microsoft Word
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Средство просмотра Microsoft Word  
(2817361)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft Visio 2003 с пакетом обновления 3 (SP3)  
(2810062)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2007 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft Visio 2007 с пакетом обновления 3 (SP3)  
(2596595)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft Visio 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(2810068)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft Visio 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(2810068)  
(существенный)
</td>
</tr>
</table>
 

#### Платформы и программное обеспечение Microsoft Communication

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Lync
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-041**](http://go.microsoft.com/fwlink/?linkid=293445)
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
Microsoft Communicator 2007 R2  
(2827753)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 (32-разрядная версия)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32-разрядная версия)  
(2827750)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64-разрядная версия)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64-разрядная версия)  
(2827750)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(установка на уровне администратора)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(установка на уровне администратора)  
(2827752)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(установка на уровне пользователя)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(установка на уровне пользователя)  
(2827751)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
(Веб-компоненты сервера)
</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
(Веб-компоненты сервера)  
(2827754)  
(существенный)
</td>
</tr>
</table>
 

#### Программное обеспечение и средства Microsoft Consumer

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Windows Essentials
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-045**](http://go.microsoft.com/fwlink/?linkid=280675)
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
Windows Essentials 2011
</td>
<td style="border:1px solid black;">
Windows Essentials 2011  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Essentials 2012
</td>
<td style="border:1px solid black;">
Windows Essentials 2012  
(2813707)  
(существенный)
</td>
</tr>
</table>
 

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

**MS13-037**

-   Хосе Антонио Васкеса Гонзалеса (Jose Antonio Vazquez Gonzalez), сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com), за сообщение об уязвимости, связанной с использованием Internet Explorer после освобождения (CVE-2013-0811)
-   Йосукэ Хасэгаву (Yosuke Hasegawa) и Масахиро Ямада (Masahiro Yamada) за сообщение об уязвимости массива JSON, приводящей к раскрытию информации (CVE-2013-1297)
-   Пользователя SkyLined, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, связанной с использованием Internet Explorer после освобождения (CVE-2013-1306)
-   Скота Белла (Scott Bell) из компании [Security-Assessment.com](http://www.security-assessment.com/) за сообщение об уязвимости, связанной с использованием Internet Explorer после освобождения (CVE-2013-1306)
-   Ивана Фратрича (Ivan Fratric) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости, связанной с использованием Internet Explorer после освобождения (CVE-2013-1307)
-   Пользователя [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com), сотрудничающего с компании [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, связанной с использованием Internet Explorer после освобождения (CVE-2013-1308)
-   Пользователя SkyLined, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, связанной с использованием Internet Explorer после освобождения (CVE-2013-1309)
-   Юхонга Бао (Yuhong Bao) за сообщение об уязвимости, связанной с использованием Internet Explorer после освобождения (CVE-2013-1310)
-   Скота Белла (Scott Bell) из компании [Security-Assessment.com](http://www.security-assessment.com/) за сообщение об уязвимости, связанной с использованием Internet Explorer после освобождения (CVE-2013-1311)
-   Стивена Фьюера (Stephen Fewer) из [Harmony Security](http://www.harmonysecurity.com), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, связанной с использованием Internet Explorer после освобождения (CVE-2013-1312)
-   Компанию [VUPEN Security](http://www.vupen.com) (Pwn2Own 2013), сотрудничающую с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, связанной с использованием Internet Explorer после освобождения (CVE-2013-2551)
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, связанной с использованием Internet Explorer после освобождения (CVE-2013-3140)
-   Масато Кинугаву (Masato Kinugawa) за совместную работу над изменениями для обеспечения многоуровневой защиты, которые включены в данный бюллетень
-   Компанию [VUPEN Security](http://www.vupen.com) (Pwn2Own 2013), сотрудничающую с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за совместную работу над изменениями для обеспечения многоуровневой защиты, которые включены в данный бюллетень.

**MS13-038**

-   Даниель Кейсельден (Daniel Caselden) из компании [FireEye](http://www.fireeye.com/) за сообщение об уязвимости, связанной с использованием Internet Explorer после освобождения (CVE-2013-1347)
-   Компанию [iSIGHT Partners](http://www.isightpartners.com/) за совместную работу над устранением уязвимости, связанной с использованием Internet Explorer после освобождения (CVE-2013-1347)

**MS13-039**

-   Марека Кроемеке (Marek Kroemeke), 22733db72ab3ed94b5f8a1ffcde850251fe6f466, AKAT-1, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимость в HTTP.sys, приводящей к отказу в обслуживании (CVE-2013-1305)

**MS13-040**

-   Джеймса Форшо (James Forshaw) из компании [Context Information Security](http://www.contextis.com/) за сообщение об уязвимости, связанной с подменой цифровых подписей XML (CVE-2013-1336)

**MS13-042**

-   Уилла Дормана (Will Dormann) из [CERT/CC](http://www.cert.org/) за совместную работу над устранением нескольких уязвимостей в Microsoft Publisher, делающих возможным удаленное выполнение кода (CVE-2013-1316, CVE-2013-1317, CVE-2013-1318, CVE-2013-1319, CVE-2013-1320, CVE-2013-1321, CVE-2013-1322, CVE-2013-1323, CVE-2013-1327, CVE-2013-1328 и CVE-2013-1329)

**MS13-043**

-   Уилла Дормана (Will Dormann) из [CERT/CC](http://www.cert.org/) за сообщение об уязвимости Word, приводящей к повреждению фигуры (CVE-2013-1335)

**MS13-044**

-   Тимура Юнусова (Timur Yunusov) из компании [Positive Technologies](http://www.ptsecurity.com/) за сообщение об уязвимости разрешения внешних сущностей XML (CVE-2013-1301)

**MS13-045**

-   Андреа Микализзи (Andrea Micalizzi), сотрудничающего с группой [SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) компании Beyond Security, за сообщение об уязвимости в Windows Essentials, связанной с неправильной обработкой URI (CVE-2013-0096)

**MS13-046**

-   [Гинваэля Колдвинда (Gynvael Coldwind)](http://gynvael.coldwind.pl/) и [Матеуша "j00ru" Юрчук (Matthew 'j00ru' Jurczyk)](http://j00ru.vexillium.org/) из корпорации [Google Inc](http://www.google.com/) за сообщение об уязвимости подсистемы графического ядра DirectX, связанной с двойной выборкой (CVE-2013-1332)
-   Сотрудников [Qihoo 360 Security Center](http://www.360.cn/) за сообщение об уязвимости Win32k, связанной с переполнением буфера (CVE-2013-1333)
-   Анонимного исследователя, сотрудничающего с компанией [iDefense VCP](http://labs.idefense.com/), за сообщение об уязвимости в Win32K, связанной с дескрипторами окон (CVE-2013-1334)

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (14 мая 2013 г.): Обзор бюллетеней опубликован.
-   Вер. 1.1 (22 мая 2013 г.): Для MS13-037, в перечне Common Vulnerabilities and Exposures исправлен номер для CVE-2013-3140. Это изменение носит исключительно информационный характер.

*Built at 2014-04-18T01:50:00Z-07:00*
