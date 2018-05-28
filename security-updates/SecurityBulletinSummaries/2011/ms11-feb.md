---
TOCTitle: 'MS11-FEB'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Февраль 2011 г.'
ms:assetid: 'ms11-feb'
ms:contentKeyID: 61236146
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms11-feb(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Февраль 2011 г.
==================================================================

Дата публикации: 8 февраля 2011 г. | Дата обновления: 18 марта 2011 г.

**Версия:** 4.0

В этот обзор включены бюллетени по безопасности, выпущенные в феврале 2011 г.

После выпуска бюллетеней за февраль 2011 г. этот обзор заменит предварительное уведомление, выпущенное 3 февраля 2011 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://technet.microsoft.com/security/bulletin/advance).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

9 февраля 2011 г. в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проводит веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в февральской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032455047&eventcategory=4). После наступления этой даты данная веб-трансляция будет доступна по запросу. Дополнительные сведения см. на веб-сайте [обзоров и веб-трансляций, посвященных бюллетеням Майкрософт по безопасности](http://technet.microsoft.com/security/bulletin/summary).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208304">MS11-003</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (2482017)</strong><br />
<br />
Данное обновление для системы безопасности устраняет две обнаруженных пользователями уязвимости и две опубликованных уязвимости в браузере Internet Explorer. Все они делают возможным удаленное выполнение кода при открытии специально созданной веб-страницы в браузере Internet Explorer или при открытии подлинного файла HTML, который загрузит специально созданный файл библиотеки. Злоумышленник, успешно воспользовавшийся любой из этих уязвимостей, может получить те же права, которыми обладает локальный пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208146">MS11-006</a></td>
<td style="border:1px solid black;"><strong>Уязвимость обработки графики в оболочке Windows делает возможным удаленное выполнение кода (2483185)</strong><br />
<br />
Это обновление для системы безопасности устраняет опубликованную уязвимость в графическом процессоре оболочки Windows. Данная уязвимость делает возможным удаленное выполнение кода, если пользователь просматривает специально созданное изображение эскиза. Злоумышленник, воспользовавшийся этой уязвимостью, может получить те же права, что и вошедший в систему пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208059">MS11-007</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в драйвере OpenType CFF (Compact Font Format) делает возможным удаленное выполнение кода (2485376)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в драйвере Windows OpenType CFF (Compact Font Format). Эта уязвимость делает возможным удаленное выполнение кода, если пользователь просмотрит содержимое, отображенное особым образом созданным шрифтом CFF. Однако в любом случае злоумышленник не может заставить пользователей просмотреть особым образом созданное содержимое. Вместо этого злоумышленник попытается убедить пользователей посетить веб-сайт, обычно приглашая их щелкнуть соответствующую ссылку, ведущую на этот веб-сайт, в сообщении электронной почты или в запросе программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208522">MS11-004</a></td>
<td style="border:1px solid black;"><strong>Уязвимость службы FTP Microsoft IIS делает возможным удаленное выполнение кода (2489256)</strong><br />
<br />
Это обновление безопасности устраняет опубликованную уязвимость в службе FTP Microsoft IIS. Эта уязвимость делает возможным удаленное выполнение кода, если FTP-сервер получит особым образом созданную команду FTP. По умолчанию служба FTP не установлена в IIS.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207843">MS11-005</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в службе Active Directory делает возможной атаку типа &quot;отказ в обслуживании&quot; (2478953)</strong><br />
<br />
Это обновление для системы безопасности устраняет опубликованную уязвимость в Active Directory. Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;, если злоумышленник отправляет на уязвимый сервер Active Directory особым образом созданный пакет. Чтобы воспользоваться уязвимостью, злоумышленник должен иметь действительные права локального администратора на компьютере, подключенном к домену.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204799">MS11-008</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Visio делают возможным удаленное выполнение кода (2451879)</strong><br />
<br />
Это обновление для системы безопасности устраняет две обнаруженные пользователями уязвимости в Microsoft Visio. Эти уязвимости делают возможным удаленное выполнение кода при открытии пользователем особым образом созданного файла Visio. Злоумышленник, успешно воспользовавшийся любой из этих уязвимостей, может получить те же права, которыми обладает вошедший в систему пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207839">MS11-009</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в обработчиках сценариев JScript и VBScript может привести к раскрытию информации (2475792)</strong><br />
<br />
Настоящее обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в обработчиках сценариев JScript и VBScript. Данная уязвимость может привести к раскрытию информации, если пользователь посетит специально созданный веб-сайт. Злоумышленник не может заставить пользователей посетить эти веб-сайты. Вместо этого злоумышленник попытается убедить пользователей посетить веб-сайт, обычно приглашая их щелкнуть соответствующую ссылку, ведущую на этот веб-сайт, в сообщении электронной почты или в запросе программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Раскрытие информации</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207840">MS11-010</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в подсистеме исполнения клиент-сервер Windows делает возможным несанкционированное получение прав (2476687)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в подсистеме CSRSS Microsoft Windows в Windows XP и Windows Server 2003.<br />
<br />
Эта уязвимость делает возможным несанкционированное получение прав, если злоумышленник войдет в систему пользователя и запустит специально созданное приложение, которое продолжит работать после выхода злоумышленника из системы с целью получения учетных данных последующих пользователей. Чтобы воспользоваться этой уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему. Данной уязвимостью не могут воспользоваться удаленные или анонимные пользователи.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208365">MS11-011</a></td>
<td style="border:1px solid black;"><strong>Уязвимости ядра Windows делают возможным несанкционированное получение прав (2393802)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну опубликованную и одну обнаруженную пользователями уязвимость в Microsoft Windows. Эти уязвимости делают возможным несанкционированное получение прав, если злоумышленник вошел в систему и запустил особым образом созданное приложение. Чтобы воспользоваться данными уязвимостями, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему. Данными уязвимостями не могут воспользоваться удаленные или анонимные пользователи.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208362">MS11-012</a></td>
<td style="border:1px solid black;"><strong>Уязвимости драйверов режима ядра Windows делают возможным несанкционированное получение прав (2479628)</strong><br />
<br />
Это обновление для системы безопасности устраняет пять обнаруженных пользователями уязвимостей в Microsoft Windows. Эти уязвимости делают возможным несанкционированное получение прав, если злоумышленник вошел в систему и запустил особым образом созданное приложение. Чтобы воспользоваться данными уязвимостями, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему. Данными уязвимостями не могут воспользоваться удаленные или анонимные пользователи.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208523">MS11-013</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Kerberos делают возможным несанкционированное получение прав (2496930)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну обнаруженную пользователями и одну опубликованную уязвимость в Microsoft Windows. Наиболее серьезные из этих уязвимостей делают возможным несанкционированное получение прав в случае, если локальный злоумышленник, прошедший проверку подлинности, установит вредоносную службу на компьютере, подключенном к домену.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208395">MS11-014</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в службе LSASS делает возможным несанкционированное получение локальных прав (2478960)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в службе LSASS в Windows XP и Windows Server 2003.<br />
<br />
Эта уязвимость делает возможным несанкционированное получение прав, если злоумышленник войдет в систему и запустит специально созданное приложение. Чтобы воспользоваться этой уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему. Данной уязвимостью не могут воспользоваться удаленные или анонимные пользователи.</td>
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
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости перечислены в порядке убывания оценки индекса использования, затем по коду CVE. Включены только уязвимости, которым в бюллетенях присвоен уровень серьезности "критический" или "существенный".
  
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать о вероятности появления стабильно работающего кода эксплойта в течение 30 дней после выпуска бюллетеня по каждому из обновлений для системы безопасности, которые необходимо установить. Перед назначением приоритетов развертывания ознакомьтесь с каждой приведенной ниже оценкой, относящейся к конкретной конфигурации. Дополнительные сведения об уровнях опасности и способах их определения см. в [индексе использования уязвимостей](http://technet.microsoft.com/en-us/security/cc998259.aspx).

 
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Идентификатор бюллетеня</th>
<th style="border:1px solid black;" >Название уязвимости</th>
<th style="border:1px solid black;" >Код CVE</th>
<th style="border:1px solid black;" >Оценка индекса использования уязвимостей</th>
<th style="border:1px solid black;" >Краткие примечания</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208146">MS11-006</a></td>
<td style="border:1px solid black;">Уязвимость графического процессора оболочки Windows, приводящая к переполнению буфера</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3970">CVE-2010-3970</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><strong>О данной уязвимости сообщалось в открытых источниках, и код эксплойта доступен</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208304">MS11-003</a></td>
<td style="border:1px solid black;">Уязвимость CSS, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3971">CVE-2010-3971</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><strong>Эта уязвимость открыто опубликована и в используется в Интернете</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208365">MS11-011</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с неправильным взаимодействием драйверов с ядром Windows</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-4398">CVE-2010-4398</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><strong>О данной уязвимости сообщалось в открытых источниках</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207840">MS11-010</a></td>
<td style="border:1px solid black;">Уязвимость подсистемы CSRSS, приводящая к несанкционированному получению прав</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0030">CVE-2011-0030</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208304">MS11-003</a></td>
<td style="border:1px solid black;">Уязвимость, приводящая к повреждению неинициализированной области памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0035">CVE-2011-0035</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208304">MS11-003</a></td>
<td style="border:1px solid black;">Уязвимость, приводящая к повреждению неинициализированной области памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0036">CVE-2011-0036</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208395">MS11-014</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с проверкой длины LSASS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0039">CVE-2011-0039</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208523">MS11-013</a></td>
<td style="border:1px solid black;">Уязвимость Kerberos, связанная с контрольной суммой без использования ключа</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0043">CVE-2011-0043</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;"><strong>О данной уязвимости сообщалось в открытых источниках</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208365">MS11-011</a></td>
<td style="border:1px solid black;">Уязвимость ядра Windows, связанная с усечением целых чисел</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0045">CVE-2011-0045</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208362">MS11-012</a></td>
<td style="border:1px solid black;">Уязвимость Win32k, связанная с неправильной проверкой пользовательского ввода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0086">CVE-2011-0086</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208362">MS11-012</a></td>
<td style="border:1px solid black;">Уязвимость Win32k, связанная с недостаточной проверкой пользовательского ввода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0087">CVE-2011-0087</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208362">MS11-012</a></td>
<td style="border:1px solid black;">Уязвимость Win32k, связанная со смешением указателей в классах окон</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0088">CVE-2011-0088</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208362">MS11-012</a></td>
<td style="border:1px solid black;">Уязвимость Win32k, связанная с неправильной проверкой указателей в классах окон</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0089">CVE-2011-0089</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208362">MS11-012</a></td>
<td style="border:1px solid black;">Уязвимость Win32k, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0090">CVE-2011-0090</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204799">MS11-008</a></td>
<td style="border:1px solid black;">Уязвимость проверки объектов Visio, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0092">CVE-2011-0092</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204799">MS11-008</a></td>
<td style="border:1px solid black;">Уязвимость типа данных Visio, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0093">CVE-2011-0093</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208522">MS11-004</a></td>
<td style="border:1px solid black;">Уязвимость переполнения буфера кучи службы FTP в IIS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3972">CVE-2010-3972</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Возможно существование нестабильного кода эксплойта</td>
<td style="border:1px solid black;"><strong>О данной уязвимости сообщалось в открытых источниках, и демонстрационный код (PoC) доступен</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208059">MS11-007</a></td>
<td style="border:1px solid black;">Уязвимость анализа кодированных символов шрифтов OpenType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0033">CVE-2011-0033</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Возможно существование нестабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207839">MS11-009</a></td>
<td style="border:1px solid black;">Уязвимость обработчика сценариев, приводящая к раскрытию информации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0031">CVE-2011-0031</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Эта уязвимость связана с возможностью утечки информации</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207843">MS11-005</a></td>
<td style="border:1px solid black;">Уязвимость Active Directory, связанная с проверкой SPN</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0040">CVE-2011-0040</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><strong>О данной уязвимости сообщалось в открытых источниках</strong><br />
<br />
Эта уязвимость позволяет провести атаку типа &quot;отказ в обслуживании&quot;</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208523">MS11-013</a></td>
<td style="border:1px solid black;">Уязвимость Kerberos, приводящая к спуфингу</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0091">CVE-2011-0091</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Это уязвимость, которая делает возможным только спуфинг.</td>
</tr>
</tbody>
</table>
  
Продукты, подверженные уязвимости, и соответствующие обновления  
---------------------------------------------------------------
  
<span></span>
В приведенных ниже таблицах перечислены бюллетени в порядке важности категорий программного обеспечения и уровней опасности.
  
**Как пользоваться этими таблицами?**
  
Обращайтесь к этим таблицам, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и узнайте, имеются ли для них обновления для системы безопасности. Для программ или компонентов, указанных в списке, приведены ссылки на доступные обновления с указанием уровня опасности уязвимостей, которые они устраняют.
  
**Примечание**. Для устранения одной уязвимости может потребоваться установка нескольких обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификатора бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.
  
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
<th colspan="12">
ОС Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://go.microsoft.com/fwlink/?linkid=208304)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://go.microsoft.com/fwlink/?linkid=208146)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://go.microsoft.com/fwlink/?linkid=208059)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://go.microsoft.com/fwlink/?linkid=208522)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://go.microsoft.com/fwlink/?linkid=207843)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://go.microsoft.com/fwlink/?linkid=207839)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://go.microsoft.com/fwlink/?linkid=207840)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://go.microsoft.com/fwlink/?linkid=208365)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://go.microsoft.com/fwlink/?linkid=208362)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://go.microsoft.com/fwlink/?linkid=208523)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://go.microsoft.com/fwlink/?linkid=208395)
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
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=ae343de6-ec61-4891-b136-cfc4234d97d9)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=85bf88b7-2dd9-4204-8492-b2c1d8d2264e)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c72fbb97-2313-45f6-842d-99db373822dd)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=bbea7ead-6c5c-4da8-aa03-a40325fd2de3)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=f86e9e64-801a-431a-b24e-772011dfa66d)  
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
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=cfa10178-9859-4e03-bedc-e3f5297a0251)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=a511d33a-9ae0-46ee-a225-9d97390de7d1)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=56f4f43e-c313-49dc-a278-e3e8a83a907e)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=486d1969-6814-4556-8dc0-5bfbaee528b0)  
(KB2478971)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=541f228f-79b3-402a-8ff9-366c1e595227)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=d431100d-a627-4ea0-b75b-2d4157e38df2)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a795de21-13f4-4035-a4d5-4257ddc92fe7)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=69dfa24b-7c56-4521-850c-1485b062154a)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=bcb7217e-624a-4d61-86a1-f2440a1afd57)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=074396f0-a68c-4190-8dac-0b883d56e3f1)  
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
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=9f0b7b77-5b90-4a4b-97a4-0c1ce6a70126)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e7273a85-ce96-464b-8c4f-2710701213e3)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e80db313-b470-4d71-bc34-70bfbfb6579f)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a210c796-7077-4617-a9a8-9ea99fe11a5e)  
(KB2478971)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=82189bf2-3f34-4949-92da-eea98036d18e)  
(существенный)
</td>
</tr>
<tr>
<th colspan="12">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://go.microsoft.com/fwlink/?linkid=208304)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://go.microsoft.com/fwlink/?linkid=208146)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://go.microsoft.com/fwlink/?linkid=208059)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://go.microsoft.com/fwlink/?linkid=208522)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://go.microsoft.com/fwlink/?linkid=207843)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://go.microsoft.com/fwlink/?linkid=207839)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://go.microsoft.com/fwlink/?linkid=207840)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://go.microsoft.com/fwlink/?linkid=208365)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://go.microsoft.com/fwlink/?linkid=208362)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://go.microsoft.com/fwlink/?linkid=208523)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://go.microsoft.com/fwlink/?linkid=208395)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=5e0f4bf2-f727-483a-af3a-9a2abf0c36bb)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=45e504d4-c17d-4b73-b08e-d9c0cb3f4918)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=74238e08-fae2-4f17-ac72-681226a53a40)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2aa94528-5063-427b-97f7-2a0a55cbb6bf)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a99c2b13-db81-4f18-9cf7-c20614ba0132)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=651c1f4f-4e69-4d17-8aa2-72681dfc5463)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=aed08b96-24cc-4e23-8fd5-c7e52f8ef41a)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6bf2eeec-8225-477f-a606-263d3ee434d6)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=54fe2669-8a63-4d96-8b82-5b10f45b293e)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8a1e2675-0bf0-4d94-b48a-6e846dd6d9f5)  
(KB2478971)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4e31e6b1-577e-468e-9c94-67227d2273c2)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=0592b520-88d1-45bc-8b15-d3f0c8fa2181)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=29adcfb5-540f-4980-b2ca-9a22aa7bba13)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ebef4869-9812-46ce-9c01-2fb8c866ec90)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6e740922-6ce4-46ec-a35e-e94201a9e398)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=aeed45fb-9395-4c2b-a674-e38b04fe0914)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=ec962b0e-e951-4e70-8d97-8c2afd360c28)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ca7879e1-e295-445d-a658-0a31be1928cc)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ec544894-ee98-4a2b-ac4d-33b0c3754213)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4632e1ce-6ae8-431c-9104-9a8840e5ac63)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e79bbbd4-8d5a-4c4c-8427-21c14400f041)  
(KB2478971)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=76e3c229-d812-433c-ad05-7cbd1f9c6a6d)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b2298b32-238a-4970-bc1f-2ede51a6c361)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=c41a0094-204b-4d05-ab39-a32915201af1)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 для систем с процессорами Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a4f9ec46-35b2-44c9-abf6-647f7a474b99)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 для систем с процессорами Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=bc09e42b-2eed-41b3-a03f-cb8cc94adfee)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=4ac66eae-e6d8-4e8b-b4ea-e7a77cc74db0)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 для систем с процессорами Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=50855101-a15c-4c81-ad81-a7fe3f1d2026)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 для систем с процессорами Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=fcd48499-1bb4-4304-b9cc-27d9d92e11cd)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 для систем с процессорами Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a09c3e6e-c55c-492a-b7ad-3e3d35711643)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 для систем с процессорами Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=856fbcc2-ead9-4ec1-92dd-988e6d22dae9)  
(KB2478971)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 для систем с процессорами Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a0cde8d8-7c85-4fcb-bcf7-205064970b41)  
(существенный)
</td>
</tr>
<tr>
<th colspan="12">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://go.microsoft.com/fwlink/?linkid=208304)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://go.microsoft.com/fwlink/?linkid=208146)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://go.microsoft.com/fwlink/?linkid=208059)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://go.microsoft.com/fwlink/?linkid=208522)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://go.microsoft.com/fwlink/?linkid=207843)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://go.microsoft.com/fwlink/?linkid=207839)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://go.microsoft.com/fwlink/?linkid=207840)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://go.microsoft.com/fwlink/?linkid=208365)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://go.microsoft.com/fwlink/?linkid=208362)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://go.microsoft.com/fwlink/?linkid=208523)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://go.microsoft.com/fwlink/?linkid=208395)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Нет
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b176777e-4897-4cf1-9fc0-dd608930bb4c)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=77971c3c-55ec-4a9c-bcb8-8fb8c61431e3)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0c18ecca-afb9-4738-bc7b-76a0e815dfb8)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d60a2098-7351-4fce-83b2-2c1c3a24faa0)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.0 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=c09ccc72-8f94-416b-9a7f-ed16e90342a2)<sup>[1]</sup>
(существенный)  
[Служба Microsoft FTP 7.5 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=da9b7982-1c6b-45ac-8dd0-d7101bb83949)<sup>[1]</sup>
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
[Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=66978514-bb7f-42cc-9360-2fd1c686f4e6)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6fb7ebcc-2052-457b-b5bc-1bbcb17696b9)  
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
Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=20ad0136-c6df-4c7b-811f-d6b3dd9e2c56)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d3580784-aada-4118-b7f2-3a23aec2ed04)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=62dc454f-4b1e-4ac0-8ffe-6c73112f8d4d)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=065ad8fe-1caf-488e-a2e1-96db29f2fa57)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.0 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=e88d072f-0f5f-4c85-ad2f-91b9b8bf6b3a)<sup>[1]</sup>
(существенный)  
[Служба Microsoft FTP 7.5 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=6e4b9878-b5d2-4025-8839-b41515932cf2)<sup>[1]</sup>
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
[Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8fdb8c37-1b22-457b-bdc0-21f6a5061dd3)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=88d68757-1ab0-4585-9578-52a474b10882)  
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
<th colspan="12">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://go.microsoft.com/fwlink/?linkid=208304)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://go.microsoft.com/fwlink/?linkid=208146)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://go.microsoft.com/fwlink/?linkid=208059)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://go.microsoft.com/fwlink/?linkid=208522)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://go.microsoft.com/fwlink/?linkid=207843)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://go.microsoft.com/fwlink/?linkid=207839)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://go.microsoft.com/fwlink/?linkid=207840)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://go.microsoft.com/fwlink/?linkid=208365)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://go.microsoft.com/fwlink/?linkid=208362)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://go.microsoft.com/fwlink/?linkid=208523)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://go.microsoft.com/fwlink/?linkid=208395)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ee61f0dd-9797-4e11-8281-a05b201d0c0b)\*\*  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ef1ae382-8835-4f60-83bd-e84a3400d55c)\*\*  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=253c47a0-69ac-437a-ad3e-778c37fa37cb)\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=88ba83b9-c14e-499a-8335-04bac1c49c0c)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.0 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=3cc55af7-5cd9-4923-8ec5-462ff201d734)<sup>[1]</sup>\*  
(существенный)  
[Служба Microsoft FTP 7.5 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=4dfa0a25-b7e3-4fb6-a351-58ec3f8a8435)<sup>[1]</sup>\*  
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
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4b37418a-e044-415e-b566-4507f157934a)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=80494972-db45-475f-97cd-dac46b9486a1)\*  
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
Windows Server 2008 для 64-разрядных систем и Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=558bc86a-a49d-4d6c-b5e4-f12956f6b61b)\*\*  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5607df02-93fa-45fe-a928-e5f6329851f3)\*\*  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных (x64) систем и Windows Server 2008 для 64-разрядных (x64) систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ec7101aa-96c2-4931-a3e4-0c55cbc74d9c)\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных (x64) систем и Windows Server 2008 для 64-разрядных (x64) систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7c74d7f4-6372-4809-89b8-c79b05e54cdd)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.0 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=f485b30d-dcaf-47c3-ac62-982b14670a1f)<sup>[1]</sup>\*  
(существенный)  
[Служба Microsoft FTP 7.5 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=a98a74c1-0c91-446d-b822-fe57ff06d90b)<sup>[1]</sup>\*  
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
[Windows Server 2008 для 64-разрядных (x64) систем и Windows Server 2008 для 64-разрядных (x64) систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=163d3aca-3703-452e-b1cb-73932e2bcf8c)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных (x64) систем и Windows Server 2008 для 64-разрядных (x64) систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5597d449-17e3-440f-8b0e-56a902a96569)\*  
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
Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8c2abba5-0597-4565-9b87-a37e574690e0)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для систем на базе процессоров Itanium и Windows Server 2008 для систем с процессорами Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e62493cb-8d25-4975-bbe6-a368e039872b)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для систем на базе процессоров Itanium и Windows Server 2008 для систем с процессорами Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=91d5d34b-9d7e-4e83-89a4-f1aa388dc4e4)  
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
[Windows Server 2008 для систем на базе процессоров Itanium и Windows Server 2008 для систем с процессорами Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=55b07bc0-dff5-4cd7-87c9-c08e5a49197d)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для систем на базе процессоров Itanium и Windows Server 2008 для систем с процессорами Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d10eda21-b3c3-4d8e-8596-bc45e4165f93)  
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
<th colspan="12">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://go.microsoft.com/fwlink/?linkid=208304)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://go.microsoft.com/fwlink/?linkid=208146)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://go.microsoft.com/fwlink/?linkid=208059)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://go.microsoft.com/fwlink/?linkid=208522)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://go.microsoft.com/fwlink/?linkid=207843)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://go.microsoft.com/fwlink/?linkid=207839)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://go.microsoft.com/fwlink/?linkid=207840)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://go.microsoft.com/fwlink/?linkid=208365)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://go.microsoft.com/fwlink/?linkid=208362)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://go.microsoft.com/fwlink/?linkid=208523)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://go.microsoft.com/fwlink/?linkid=208395)
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
Нет
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=07aa7ffc-47c7-4611-b32c-ecb3fbcad32f)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1da57fbc-9ea4-4fc4-911d-d5c7825e012c)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.5 для IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=9dabd1d1-3f1e-46d1-b171-aafd3f08d291)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=54a64215-e407-4b7b-8536-28817ef23bac)  
(существенный)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=54a64215-e407-4b7b-8536-28817ef23bac)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=e1224c90-b0bc-4e4b-999a-efae327213b4)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=078fe6c0-1b2c-4896-a345-25cc1b1105e2)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=ffed7c76-0b75-4f57-9b63-3961a8b449f6)  
(KB2425227)  
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2b8ffafe-78bb-4fa7-aea2-01208b6a3dfe)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=587adb89-2f6a-4893-9906-b6d6d9ada2bd)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.5 для IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=66fb4efe-bcd3-4e90-8e35-b013e014a952)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=b854d76e-6891-426d-8c09-0ed8243a3b8d)  
(существенный)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=b854d76e-6891-426d-8c09-0ed8243a3b8d)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=ddcf352e-742c-485e-9ed5-19cdba673562)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b42642b3-fb78-4700-bfe8-bfa997b90c16)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c26cebcf-683f-4a51-be75-76535fb979a7)  
(KB2425227)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="12">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://go.microsoft.com/fwlink/?linkid=208304)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://go.microsoft.com/fwlink/?linkid=208146)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://go.microsoft.com/fwlink/?linkid=208059)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://go.microsoft.com/fwlink/?linkid=208522)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://go.microsoft.com/fwlink/?linkid=207843)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://go.microsoft.com/fwlink/?linkid=207839)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://go.microsoft.com/fwlink/?linkid=207840)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://go.microsoft.com/fwlink/?linkid=208365)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://go.microsoft.com/fwlink/?linkid=208362)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://go.microsoft.com/fwlink/?linkid=208523)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://go.microsoft.com/fwlink/?linkid=208395)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=38b67efb-dd4b-4e8c-8460-0f40f0367441)\*\*  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=638318ed-4000-4b1a-bb4b-65b795f59784)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.5 для IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=1e075f57-1723-4933-9b8e-7bce4a44a1c1)\*  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=f482bd40-f0b9-4534-a768-45879f1e7285)\*\*  
(средний)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=f482bd40-f0b9-4534-a768-45879f1e7285)\*\*  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=70f5056a-72ad-46ff-a43f-ee151639b9a7)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d2c53f44-12eb-4293-9fa5-2a14075b636e)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=46bb3ef1-24c3-41cb-8141-0fdbd85093f7)\*  
(KB2425227)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0e41cbe5-5e5e-4ece-a71a-71f4b6319f0d)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=4688ea0d-a467-4f24-ac52-104d05c8cae8)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.5 для IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=bfddd539-c64f-4467-88ee-6bdfe645b478)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=f05a3de0-381c-4d17-83ee-ca4f6da1bdb0)  
(средний)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=f05a3de0-381c-4d17-83ee-ca4f6da1bdb0)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=1646b3a5-714f-4ea5-b109-566fa9b933b6)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=8c6bf720-f544-4f58-9b1c-2399957ec43d)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=01737933-e7de-451b-b02f-b7ca24693965)  
(KB2425227)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 
**Примечания для Windows Server 2008 и Windows Server 2008 R2**

**\*Системы, при развертывании которых устанавливалось только ядро сервера, подвержены уязвимости.** Это обновление (с одинаковым уровнем серьезности) применяется к указанным выше поддерживаемым выпускам Windows Server 2008 или Windows Server 2008 R2 независимо от наличия установленных основных компонентов сервера. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Уязвимости не подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Поддерживаемые выпуски Windows Server 2008 или Windows Server 2008 R2, при развертывании которых выбиралась установка только ядра сервера, не подвержены уязвимостям, устраняемым этим обновлением. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Примечание для MS11-004**

<sup>[1]</sup>Не является службой FTP по умолчанию для данной операционной системы

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
Программы Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-008**](http://go.microsoft.com/fwlink/?linkid=204799)
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
Microsoft Visio 2002 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2002 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=273d8078-0dc7-43d8-bcae-54c811e49e0e)  
(KB2434711)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=f1067eaa-d18d-4bff-a02e-1d990c36ca7f)  
(KB2434733)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Visio 2007 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=097a642b-b786-4724-a907-79f37cded836)  
(KB2434737)  
(существенный)
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

Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений безопасности и стандартных ошибок в конфигурации системы безопасности. Дополнительные сведения об анализаторе безопасности MBSA см. на веб-сайте [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Службы Windows Server Update Services**

Службы Windows Server Update Services (WSUS) позволяют администраторам быстрым и надежным образом развертывать последние критические обновления и обновления для систем безопасности операционных систем Microsoft Windows 2000 и более поздних версий, пакетов Office XP и более поздних версий, серверов Exchange Server 2003 и SQL Server 2000 в системах Microsoft Windows 2000 и более поздних версий.

Дополнительные сведения о развертывании данного обновления безопасности с помощью служб WSUS см. на веб-сайте [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**System Center Configuration Manager 2007**

Управление обновлениями программного обеспечения с помощью диспетчера конфигураций Configuration Manager 2007 упрощает сложную задачу получения и управления обновлениями ИТ-систем по всему предприятию. С диспетчером конфигураций Configuration Manager 2007 ИТ-администраторы могут получать обновления продуктов Майкрософт на различные устройства, включая настольные и портативные компьютеры и мобильные устройства.

Автоматическая оценка уязвимостей в диспетчере конфигураций Configuration Manager 2007 определяет необходимость в обновлениях и сообщает о рекомендуемых действиях. Управление обновлениями программного обеспечения в диспетчере конфигураций Configuration Manager 2007 встроено в Microsoft Windows Software Update Services (WSUS), проверенную временем инфраструктуру обновления, хорошо знакомую ИТ-администраторам по всему миру. Подробнее о том, как администраторы могут использовать Configuration Manager 2007 для развертывания обновлений, см. [Управление обновлениями программного обеспечения](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). Подробнее о диспетчере конфигураций см. [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет хорошо сконфигурированное решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей.

**Примечание.** Основная поддержка System Management Server 2003 закончена 12 января 2010. Подробнее о жизненном цикле продуктов см. на веб-странице[Жизненный цикл поддержки Майкрософт](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Последний выпуск сервера SMS (System Center Configuration Manager 2007) доступен для загрузки; сведения о нем см. в разделе **System Center Configuration Manager 2007**.

Подробнее о том, как администраторы могут использовать SMS 2003 для развертывания обновлений системы безопасности, см. [Сценарии и процедуры для Microsoft Systems Management Server 2003: Распространение программного обеспечения и управление исправлениями](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Дополнительные сведения о сервере SMS см. на веб-сайте [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Примечание**. Для предоставления широкой поддержки при определении необходимости применения и развертывания обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используется средство Microsoft Baseline Security Analyzer. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. в статье [Развертывание обновлений программного обеспечения с помощью функции распространения программ сервера SMS](http://go.microsoft.com/fwlink/?linkid=33341). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакета [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)).

**Средство оценки совместимости обновлений и набор средств для обеспечения совместимости приложений**

Часто обновления записываются в одни те же файлы, а для запуска приложений требуется настроить параметры реестра. Это приводит к возникновению несовместимостей и увеличивает время, затрачиваемое на развертывание обновлений для системы безопасности. Облегчить тестирование и проверку обновлений Windows для установленных приложений можно с помощью [компонентов оценки совместимости обновлений](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true), входящих в состав [набора средств для обеспечения совместимости приложений](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Набор средств для обеспечения совместимости приложений содержит необходимые средства и документацию для выявления проблем совместимости приложений и уменьшения степени воздействия этих проблем перед развертыванием системы Microsoft Windows Vista, обновлений из Центра обновления Windows, обновлений с веб-сайта безопасности Майкрософт или новой версии проводника.

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

#### Обновления, не относящиеся к безопасности и распространяемые через Центр обновления Майкрософт, Центр обновления Windows и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-сайте Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт:](http://support.microsoft.com/kb/894199) Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
-   [Обновления за предыдущие месяцы для служб Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Отображаются все новые, обновленные и повторно выпущенные обновления для продуктов Майкрософт отличных от Microsoft Windows.

#### Программа Microsoft Active Protections Program (MAPP)

Чтобы повысить уровень защиты пользователей, корпорация Майкрософт предоставляет сведения об уязвимостях крупным поставщикам программного обеспечения безопасности перед ежемесячным выпуском обновлений. Эта информация необходима им для усовершенствования программного обеспечения и оборудования для защиты пользователей (антивирусных программ, сетевых систем обнаружения вторжений, а также индивидуальных систем предотвращения вторжений). Сведения о новых средствах защиты, предоставляемых поставщиками программного обеспечения безопасности, доступны на соответствующих веб-сайтах партнеров, перечисленных в списке партнеров [MAPP](http://www.microsoft.com/security/msrc/mapp/partners.mspx).

#### Стратегии безопасности и сообщество

**Стратегии управления обновлениями**

В статье [Рекомендации по безопасности для управления обновлениями](http://go.microsoft.com/fwlink/?linkid=21168) содержатся дополнительные сведения о рекомендациях Майкрософт по установке обновлений для системы безопасности.

**Другие обновления для системы безопасности**

Другие обновления безопасности можно загрузить из следующих источников:

-   Обновления для системы безопасности доступны на веб-сайте [Центра загрузки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".
-   Обновления для индивидуальных пользователей доступны на веб-сайте [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747).
-   Обновления безопасности, предлагаемые в этом месяце в Центре обновления Windows, можно загрузить с веб-сайта Центра загрузки Майкрософт в виде файлов ISO-образа компакт-диска с выпусками обновлений безопасности. Дополнительные сведения см. в [статье 913086 базы знаний Майкрософт](http://support.microsoft.com/kb/913086).

**Сообщество ИТ-специалистов, занимающихся вопросами безопасности**

На веб-сайте [сообщества ИТ-специалистов, занимающихся вопросами безопасности](http://go.microsoft.com/fwlink/?linkid=21164), можно найти сведения о способах улучшения системы безопасности и оптимизации ИТ-инфраструктуры предприятия, а также обсудить вопросы безопасности с другими ИТ-специалистами.

#### Благодарности

Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:

-   Юки Чен (Yuki Chen) из компании [Trend Micro](http://www.trendmicro.com) за сообщение об уязвимости, описанной в бюллетене MS11-003
-   Пользователя SkyLined из компании [Google Inc.](http://www.google.com/) за сообщение об уязвимости, описанной в бюллетене MS11-003
-   Хайфэя Ли (Haifei Li) из [отдела FortiGuard Labs компании Fortinet](http://www.fortiguard.com/) за сообщение об уязвимости, описанной в MS11-003
-   Коби Париенте (Kobi Pariente) и Янив Мирон (Yaniv Miron), сотрудничающих с [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение о проблеме, описанной в бюллетене MS11-006
-   Пользователя Procyun, работающего с [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в бюллетене MS11-008
-   Ксин Оуянг (Xin Ouyang) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение о двух проблемах, описанных в бюллетене MS11-008
-   Ямату Ли (Yamata Li) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение о проблеме, описанной в бюллетене MS11-009
-   Профессора Сайхана Квинга (Sihan Qing), доцента Вайпинга Вена (Weiping Wen) и аспирантов Лианг Йин (Liang Yin) и Хушенга Чжоу (Husheng Zhou), [Факультет информационной безопасности, Пекинский университет](http://www.ss.pku.edu.cn/en/), за сообщение об уязвимости, описанной в бюллетене MS11-010
-   Пользователя Zhengwenbin из компании [360safe](http://www.360.cn) за сообщение об уязвимости, описанной в бюллетене MS11-011
-   Гуо Боджуна (Guo Bojun) за сообщение об уязвимости, описанной в бюллетене MS11-011
-   Вай Жанг (Wei Zhang) за сообщение об уязвимости, описанной в бюллетене MS11-011
-   Марко Джулиани (Marco Giuliani) из компании [PrevX](http://www.prevx.com/) за совместную работу над устранением проблемы, описанной в бюллетене MS11-011
-   Пользователя std\_logic, работающего с [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в бюллетене MS11-011
-   Таржея Мандта (Tarjei Mandt) из компании [Norman](http://www.norman.com) за сообщение о пяти уязвимостях, описанных в бюллетене MS11-012
-   [Группе Kerberos MIT](http://web.mit.edu/kerberos) за сообщение об уязвимости, описанной в бюллетене MS11-013
-   Скотта Стендера (Scott Stender) из компании [iSEC Partners](http://www.isecpartners.com/) за сообщение об уязвимости, описанной в MS11-013
-   Тестировщика безопасности Йорге Моура (Jorge Moura) из компании Primavera BSS за сообщение об уязвимости, описанной в бюллетене MS11-014

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Пользователи из США и Канады могут обратиться в службу [поддержки по вопросам безопасности](http://go.microsoft.com/fwlink/?linkid=21131) или позвонить по телефону 1-866-PCSAFETY. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Дополнительные сведения о вариантах поддержки см. на веб-сайте [справки и поддержки корпорации Майкрософт](http://support.microsoft.com/).
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-сайт международной справки и поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (8 февраля 2011): Обзор бюллетеней опубликован.
-   Вер. 1.1 (9 февраля 2011): В бюллетене MS11-013 оценка индекса использования для уязвимости CVE-2011-0091 исправлена на "3 — существование функционирующего кода эксплойта маловероятно". Это изменение носит исключительно информационный характер.
-   Вер. 2.0 (8 марта 2011): В таблицу "Подвержены уязвимости" внесено уточнение, включающее Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1), Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1), Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1) и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1) для MS11-003, MS11-004, MS11-007 и MS11-009. Дополнительные сведения см. в обновленном разделе ответов на часто задаваемые вопросы данных бюллетеней по безопасности.
-   Вер. 3.0 (16 марта 2011): Исправлена таблица "Подвержены уязвимости", которая содержит Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1), Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1), Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1) и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1) для MS11-013. Дополнительные сведения см. в обновленном разделе "Часто задаваемые вопросы" в этом бюллетене.
-   Вер. 4.0 (18 марта 2011): Исправлена таблица "Подвержены уязвимости", которая содержит Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1), Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1), Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1) и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1) для MS11-012. Дополнительные сведения см. в обновленном разделе "Часто задаваемые вопросы" в этом бюллетене.

*Built at 2014-04-18T01:50:00Z-07:00*
