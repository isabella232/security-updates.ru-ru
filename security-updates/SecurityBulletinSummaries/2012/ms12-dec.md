---
TOCTitle: 'MS12-DEC'
Title: 'Обзор бюллетеней по безопасности Майкрософт за декабрь 2012 года.'
ms:assetid: 'ms12-dec'
ms:contentKeyID: 61236157
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms12-dec(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности Майкрософт за декабрь 2012 года.
=================================================================

Дата публикации: 11 декабря 2012 г. | Дата обновления: 20 декабря 2012 г.

**Версия:** 2.0

В этом обзоре перечислены бюллетени по безопасности за декабрь 2012 года.

После выпуска бюллетеней по безопасности за декабрь 2012 года этот обзор заменит предварительное уведомление, выпущенное 6 декабря 2012 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

12 декабря 2012 года в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в декабрьской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522564&culture=en-us). После наступления этой даты данная веб-трансляция будет доступна [по запросу](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522564&culture=en-us).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268393">MS12-077</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление системы безопасности для браузера Internet Explorer (2761465)<br />
<br />
</strong>Это обновление для системы безопасности устраняет три обнаруженных пользователями уязвимости в браузере Internet Explorer. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь просмотрит особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271624">MS12-078</a></td>
<td style="border:1px solid black;"><strong>Уязвимости драйверов режима ядра Windows делают возможным удаленное выполнение кода<br />
(2783534)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну опубликованную и одну обнаруженную пользователями уязвимость в Microsoft Windows. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь откроет специально созданный документ или посетит вредоносную веб-страницу с внедренными файлами шрифтов TrueType или OpenType. Злоумышленник должен будет убедить пользователей посетить веб-сайт, обычно приглашая их перейти по соответствующей ссылке, ведущей на этот веб-сайт, в сообщении электронной почты.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271609">MS12-079</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Word делает возможным удаленное выполнение кода (2780642)</strong> <strong><br />
<br />
</strong>Это обновление для системы безопасности устраняет уязвимость в пакете Microsoft Office, о которой сообщалось в частном порядке. Эта уязвимость делает возможным удаленное выполнение кода, если пользователь открывает специально созданный RTF-файл в уязвимой версии Microsoft Office либо предварительно просматривает или открывает специально созданное сообщение электронная почты в формате RTF в Outlook с приложением Microsoft Word в качестве программы чтения сообщений электронной почты. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=272389">MS12-080</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Exchange Server делают возможным удаленное выполнение кода (2784126)<br />
<br />
</strong>Это обновление для системы безопасности устраняет опубликованные уязвимости и одну обнаруженную пользователями уязвимость в Microsoft Exchange Server. Наиболее серьезны уязвимости при веб просмотре документов Microsoft Exchange Server, которые делают возможным удаленное выполнение кода в контексте безопасности службы перекодировки на сервере Exchange при предварительном просмотре специально созданных файлов с помощью Outlook Web App (OWA). Служба перекодировки в Exchange, которая используется для веб-просмотра документов, выполняется от имени учетной записи LocalService. У учетной записи LocalService минимальные права на локальном компьютере и анонимные учетные данные в сети.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Серверное программное обеспечение Майкрософт</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=266541">MS12-081</a></td>
<td style="border:1px solid black;"><strong>Уязвимость компонента обработки файлов в Windows делает возможным удаленное выполнение кода (2758857)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость делает возможным удаленное выполнение кода, если пользователь просматривает папку, содержащую файл или папку со специально созданным именем. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271751">MS12-082</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в DirectPlay делает возможным удаленное выполнение кода (2770660)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость делает возможным удаленное выполнение кода при условии, что злоумышленник сможет убедить пользователя просмотреть специально созданный документ Office с внедренным содержимым. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263950">MS12-083</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в компоненте IP-HTTPS делает возможным обход функций безопасности (2765809)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость делает возможным обход функций безопасности, если злоумышленник предоставит отозванный сертификат серверу IP-HTTPS, широко используемому в развертываниях Microsoft DirectAccess. Для прохождения проверки подлинности сервера IP-HTTPS злоумышленник должен использовать сертификат, выпущенный из данного домена. При входе в систему внутри организации все равно потребуются учетные данные системы или домена.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Обход функции безопасности</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268393">MS12-077</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием InjectHTMLStream после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4781">CVE-2012-4781</a></td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268393">MS12-077</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с использованием CMarkup после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4782">CVE-2012-4782</a></td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268393">MS12-077</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с неправильным использованием подсчета ссылок после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4787">CVE-2012-4787</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271624">MS12-078</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с анализом шрифтов OpenType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2556">CVE-2012-2556</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271624">MS12-078</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с анализом шрифтов TrueType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4786">CVE-2012-4786</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271609">MS12-079</a></td>
<td style="border:1px solid black;">Уязвимость RTF 'listoverridecount' в Word, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2539">CVE-2012-2539</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=272389">MS12-080</a></td>
<td style="border:1px solid black;">Oracle Outside In содержит несколько уязвимостей, представляющих опасность</td>
<td style="border:1px solid black;">Множественные*</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">*Несколько уязвимостей, подробнее см. в бюллетене MS12-080.<br />
<br />
О существовании этих уязвимостей было объявлено.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=272389">MS12-080</a></td>
<td style="border:1px solid black;">RSS-каналы могут сделать Exchange уязвимым к атакам типа &quot;отказ в обслуживании&quot;</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4791">CVE-2012-4791</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=266541">MS12-081</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с анализом имен файлов в Windows</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4774">CVE-2012-4774</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271751">MS12-082</a></td>
<td style="border:1px solid black;">Уязвимость в DirectPlay, связанная с переполнением кучи</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1537">CVE-2012-1537</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=263950">MS12-083</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с обходом отозванных сертификатов</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2549">CVE-2012-2549</a></td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, связанная с обходом функций безопасности.</td>
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
<th colspan="6">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=e39c8368-9cd3-4f29-8c9c-aa784122bef0)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d1881d12-2a40-4cb1-9428-31d6633746be)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8359ec5a-07f8-4b29-8576-7356a84daf82)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=e4a2cd3b-598b-4cf4-8b42-2582d369bab5)  
(KB2753842)  
(критический)  
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=7a7a68cf-42a2-49a4-bf0c-88dd582ddd0d)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=f189ee1c-1457-4d50-87cd-5be268b04f16)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=98ceaf36-ef87-4ea3-8b73-bb0a1a624fe0)  
(KB2770660)  
(существенный)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=ed2d3c6e-b90a-49a7-867e-9549b14eb0bf)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=18e165e9-346b-4337-81d2-77f3bf5f5f3f)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5d0a76e1-80d3-4f81-be5e-8d235babaa61)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=27e6c4df-7988-4d03-b2f6-bc9ce37483f9)  
(KB2753842)  
(критический)  
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d2a59846-74fd-4166-9d65-1cc98cb7d934)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2bf25fc8-6458-4807-bb7d-1c07ec424638)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=421b0c02-e572-4362-b690-73ad63b028de)  
(KB2770660)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
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
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=478f4789-0f5e-4bfb-9536-94314f84f12c)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5ca71c15-0add-45cd-991f-e5810791c434)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0157c9ee-58c5-419f-ba97-6c4334318b75)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=efe4755b-3bc4-4a65-9826-7ecaa3856093)  
(KB2753842)  
(критический)  
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=74847cb5-a092-4818-bf7a-912ccaed7a12)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2242a927-cafb-41eb-8bf2-01302b5a5d94)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1b487137-8b5a-4f22-8395-f3fc4f25f00b)  
(KB2770660)  
(существенный)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=66b552b4-8b55-45de-ba0a-940dc24e6f56)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e9fb2cf9-3acb-48ac-80ac-f61f1a47a188)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=23c4962c-8526-4e18-9b8d-50f3c3a2bf6d)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=019d80e2-7622-4951-9437-5d613c5fb2fb)  
(KB2753842)  
(критический)  
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b0c9df15-857f-490a-96df-3883a11c3234)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4d97b0a5-1ba7-44f0-88b6-1e0a8039b9b1)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=39d79b5b-f11c-465a-8ddd-aecb571c711f)  
(KB2770660)  
(существенный)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=890d1149-7bb3-4d6e-a4ce-f9116c658eda)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d8025298-be72-4ef2-8914-7698494f4368)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=419b9fd2-dbe6-45b5-b025-9712bb9319d6)  
(KB2753842)  
(критический)  
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=323c122b-be77-45e9-805d-ab14f5cc76f9)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e74713fd-e1bc-4a63-9a00-2f33000eac27)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=312975f6-2269-4c6f-996b-8fb04e8c08d6)  
(KB2770660)  
(существенный)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
**Нет**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3701a40d-e423-4204-9527-26e527f47fb0)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=394963e9-edd6-4b5d-b9d4-e6fb86d7eb54)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=bd3a6f9b-7bfd-40e1-9393-a125030f2964)  
(KB2761465)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0cadef72-625f-4c91-8289-c10a96bb3423)  
(KB2753842)  
(критический)  
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=f2854a4e-2597-49ab-8a85-715ea9194208)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ebd25f89-e6d9-4c48-a673-f665d189905c)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=cd60c749-bb24-4147-9699-a1a75939a28f)  
(KB2770660)  
(существенный)
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2856c7b8-d5c0-444d-8273-5bd116f8898b)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7a0c6dbd-e537-43d7-97cc-0d3df354e46a)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=482fadb3-0974-40f3-af35-f29210913c81)  
(KB2761465)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=dd5eb06a-c805-4518-a784-5e29d7636037)  
(KB2753842)  
(критический)  
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b6baf170-65b0-4068-b2a0-196c3e4b3aed)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e7629d85-5c18-4979-a8e2-054a6175cf21)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[](http://www.microsoft.com/downloads/details.aspx?familyid=?...?)[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d6f2c1d9-b775-48a0-b154-cf61b1e2674c)</a>
(KB2770660)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
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
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a4824a10-4011-4ce5-9454-693d42acddf3)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e3d584f5-fc25-4e66-a911-4595018c51e3)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=ffff647e-8d05-4c77-aea6-542ab8d76c57)  
(KB2761465)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=9a51b84d-2200-42c5-a6ab-4d570fa20609)  
(KB2753842)  
(критический)  
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=bdad28e8-987e-492e-a405-b3be552d2d7a)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=ced1ffc6-7d30-480a-a3e0-8071981d1863)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=20ffdbfd-c786-41ca-9367-d7499108d711)  
(KB2770660)  
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=750797e5-1da7-49a9-8c27-ff35fe7516a1)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ca4a5972-faec-412a-b51a-130253cebcab)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=8f22603d-3a0d-49da-9691-671c0c950867)  
(KB2761465)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=9c60014b-133e-455e-b03f-d73f6e36d3de)  
(KB2753842)  
(критический)  
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=6298d55c-2ed2-4a90-9dfe-43bae0932e27)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=b9a687e6-9ab7-4dae-9771-5f7bb3123e06)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=cfeb7a06-5812-4a49-b69b-88be06d63d71)  
(KB2770660)  
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4d49cd73-feea-44c7-86f2-048dd69233a4)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=68e6d5c4-cb20-4291-8864-4270db36ead0)  
(KB2753842)  
(критический)  
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2293a5fb-4a1c-41d9-ab67-b89e00078029)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=202b3919-0075-4c54-a189-123de852fc7b)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0345e31f-6d0d-4d46-8f02-8b2ffbf795f0)  
(KB2770660)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
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
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
**Нет**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5b461a22-6ca4-4ab9-8874-84d7928cc668)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=38b15264-1a1d-41a6-8803-2d3facdb2dc3)  
(KB2761465)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=d1894fc3-603a-4a94-9e27-e1c564688294)  
(KB2753842)  
(критический)  
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=48f7d41e-f1c4-428d-9889-543fcb1e272b)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=cdaae723-6287-4607-9dc2-c23e1fb31f80)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=27e57b08-8616-4eb3-9724-3647e6841296)  
(KB2770660)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5b461a22-6ca4-4ab9-8874-84d7928cc668)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=38b15264-1a1d-41a6-8803-2d3facdb2dc3)  
(KB2761465)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d1894fc3-603a-4a94-9e27-e1c564688294)  
(KB2753842)  
(критический)  
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=48f7d41e-f1c4-428d-9889-543fcb1e272b)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=cdaae723-6287-4607-9dc2-c23e1fb31f80)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=27e57b08-8616-4eb3-9724-3647e6841296)  
(KB2770660)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d19dfe38-77ef-4479-b3d9-8f6385ddee80)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7accb5a9-98a1-4358-90ba-534d197885c1)  
(KB2761465)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=d7b5c43d-b659-4843-8944-62bf52738bbc)  
(KB2753842)  
(критический)  
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=ae9f0c19-169b-4bcd-92f7-654b84bab01f)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=4a389411-bf52-4cb2-9051-ba7344b58474)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=5f7c21b9-7dd3-4b9f-84af-1450af6c7ee3)  
(KB2770660)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d19dfe38-77ef-4479-b3d9-8f6385ddee80)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7accb5a9-98a1-4358-90ba-534d197885c1)  
(KB2761465)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d7b5c43d-b659-4843-8944-62bf52738bbc)  
(KB2753842)  
(критический)  
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=ae9f0c19-169b-4bcd-92f7-654b84bab01f)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=4a389411-bf52-4cb2-9051-ba7344b58474)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=5f7c21b9-7dd3-4b9f-84af-1450af6c7ee3)  
(KB2770660)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
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
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8968122d-d3b9-404e-ba23-846be9041e3f)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=14bd26c2-b006-4465-88cc-4ecdc5de540f)  
(KB2761465)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=fedee43c-0065-42bf-9714-171b5b74f099)  
(KB2753842)  
(критический)  
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=3dfa40ef-86a2-44a0-b523-f4a85c7ac82c)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=9e06181f-de06-423b-bbeb-df1f451fb817)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=efe0d293-9cfb-46cb-b52e-0b90bde3f8e9)  
(KB2770660)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=d3fb096b-87b5-4715-a093-9ec9b021a40f)  
(KB2765809)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8968122d-d3b9-404e-ba23-846be9041e3f)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=14bd26c2-b006-4465-88cc-4ecdc5de540f)  
(KB2761465)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=fedee43c-0065-42bf-9714-171b5b74f099)  
(KB2753842)  
(критический)  
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=3dfa40ef-86a2-44a0-b523-f4a85c7ac82c)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=9e06181f-de06-423b-bbeb-df1f451fb817)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=efe0d293-9cfb-46cb-b52e-0b90bde3f8e9)  
(KB2770660)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d3fb096b-87b5-4715-a093-9ec9b021a40f)  
(KB2765809)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9191365d-5541-4277-9079-f4e72e98fd19)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=f26098f5-6b6c-48f9-8737-345ad4956cb0)  
(KB2753842)  
(критический)  
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=51b562f4-8b1a-416e-88dc-93b561ad850a)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=2a0a6f92-c4bf-45a3-b103-b7937121b675)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=33096b07-bfa3-4879-b214-dfa81cd73cae)  
(KB2770660)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=88a3452c-b416-41cf-867a-fdc64666c0a6)  
(KB2765809)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9191365d-5541-4277-9079-f4e72e98fd19)  
(KB2761465)  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=f26098f5-6b6c-48f9-8737-345ad4956cb0)  
(KB2753842)  
(критический)  
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=51b562f4-8b1a-416e-88dc-93b561ad850a)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=2a0a6f92-c4bf-45a3-b103-b7937121b675)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=33096b07-bfa3-4879-b214-dfa81cd73cae)  
(KB2770660)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=88a3452c-b416-41cf-867a-fdc64666c0a6)  
(KB2765809)  
(существенный)
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
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
**Нет**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=28fb32a1-12fd-420d-94ff-570742a02b8d)  
(KB2761465)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 8 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=385265c4-f920-4ac1-b474-a166b3d3ab42)  
(KB2753842)  
(критический)  
[Windows 8 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=75969782-d3f8-40dd-8922-4408eefad6f3)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 8 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=15f86dbf-d8db-445c-8996-cc789c8a894d)  
(KB2770660)  
(существенный)
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
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=ad0ee30f-b550-434b-9fe0-ff418e052d3f)  
(KB2761465)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 8 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=543af274-d6cf-4f85-a120-b7f3936d7fc2)  
(KB2753842)  
(критический)  
[Windows 8 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=2332059d-30d3-4b44-b172-f054e26d8971)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 8 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=dfdda0c8-a440-49ab-832b-cdd343c57770)  
(KB2770660)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
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
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=96fda694-876a-45e9-911a-b68b3bd03290)  
(KB2761465)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=15298129-8f1c-47d7-a7e9-efb40823d91a)  
(KB2753842)  
(критический)  
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=f8e84ff9-a9c0-4363-b5a6-1b90254edd73)  
(KB2779030)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=59be5ec7-df5a-4f01-8e27-ad76f1fe76bb)  
(KB2770660)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=d6654bf1-1ab9-4691-8729-793eb6d0e563)  
(KB2765809)  
(существенный)
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
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
**Нет**
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
Internet Explorer 10<sup>[2]</sup>
(KB2761465)  
(критический)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2753842)  
(критический)  
Windows RT<sup>[1]</sup>
(KB2779030)  
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
<th colspan="6">
Вариант установки ядра сервера
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-077**](http://go.microsoft.com/fwlink/?linkid=268393)
</td>
<td style="border:1px solid black;">
[**MS12-078**](http://go.microsoft.com/fwlink/?linkid=271624)
</td>
<td style="border:1px solid black;">
[**MS12-081**](http://go.microsoft.com/fwlink/?linkid=266541)
</td>
<td style="border:1px solid black;">
[**MS12-082**](http://go.microsoft.com/fwlink/?linkid=271751)
</td>
<td style="border:1px solid black;">
[**MS12-083**](http://go.microsoft.com/fwlink/?linkid=263950)
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
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=9a51b84d-2200-42c5-a6ab-4d570fa20609) (установка основных серверных компонентов)  
(KB2753842)  
(существенный)  
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=bdad28e8-987e-492e-a405-b3be552d2d7a) (установка основных серверных компонентов)  
(KB2779030)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ced1ffc6-7d30-480a-a3e0-8071981d1863) (установка основных серверных компонентов)  
(KB2758857)  
(критический)
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
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=9c60014b-133e-455e-b03f-d73f6e36d3de) (установка основных серверных компонентов)  
(KB2753842)  
(существенный)  
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6298d55c-2ed2-4a90-9dfe-43bae0932e27) (установка основных серверных компонентов)  
(KB2779030)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b9a687e6-9ab7-4dae-9771-5f7bb3123e06) (установка основных серверных компонентов)  
(KB2758857)  
(критический)
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
Windows Server 2008 R2 для 64-разрядных систем (установка основных серверных компонентов)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=fedee43c-0065-42bf-9714-171b5b74f099) (установка основных серверных компонентов)  
(KB2753842)  
(существенный)  
[Windows Server 2008 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=3dfa40ef-86a2-44a0-b523-f4a85c7ac82c) (установка основных серверных компонентов)  
(KB2779030)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=9e06181f-de06-423b-bbeb-df1f451fb817) (установка основных серверных компонентов)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=d3fb096b-87b5-4715-a093-9ec9b021a40f) (установка основных серверных компонентов)  
(KB2765809)  
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
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=fedee43c-0065-42bf-9714-171b5b74f099) (установка основных серверных компонентов)  
(KB2753842)  
(существенный)  
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=3dfa40ef-86a2-44a0-b523-f4a85c7ac82c) (установка основных серверных компонентов)  
(KB2779030)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=9e06181f-de06-423b-bbeb-df1f451fb817) (установка основных серверных компонентов)  
(KB2758857)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d3fb096b-87b5-4715-a093-9ec9b021a40f) (установка основных серверных компонентов)  
(KB2765809)  
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
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=15298129-8f1c-47d7-a7e9-efb40823d91a) (установка основных серверных компонентов)  
(KB2753842)  
(существенный)  
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=f8e84ff9-a9c0-4363-b5a6-1b90254edd73) (установка основных серверных компонентов)  
(KB2779030)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=d6654bf1-1ab9-4691-8729-793eb6d0e563) (установка основных серверных компонентов)  
(KB2765809)  
(существенный)
</td>
</tr>
</table>
 
**Примечания к бюллетеню MS12-077**

<sup>[1]</sup>Уровни серьезности не применимы к данному обновлению для указанного программного обеспечения, так как описанные в данном бюллетене известные направления атак с использованием этой уязвимости блокированы в конфигурации по умолчанию. Тем не менее, к качестве дополнительной меры защиты корпорация Microsoft рекомендует пользователям данного программного обеспечения установить это обновление безопасности.

<sup>[2]</sup>Это обновление доступно только в [Центре обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130).

**Примечание** **к бюллетеню MS12-078**

<sup>[1]</sup>Это обновление доступно только в [Центре обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130).

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
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
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
[Microsoft Word 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=6947d500-f197-4001-bb39-1c4221af1b36)  
(KB2760497)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=52aad8a5-14d9-4c02-828a-5c1164a01f27)<sup>[1]</sup>
(KB2760421)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=52aad8a5-14d9-4c02-828a-5c1164a01f27)<sup>[1]</sup>
(KB2760421)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=68c69b37-c544-4f24-8589-4212b868dd69)  
(KB2760410)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=9d776c2b-1a9a-4ccb-9e76-dd2cb0f9a80d)  
(KB2760410)  
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
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Средство просмотра Microsoft Word
</td>
<td style="border:1px solid black;">
[Средство просмотра Microsoft Word](http://www.microsoft.com/downloads/details.aspx?familyid=4ccaabd9-5128-4505-ba2f-20bcf02b97ec)  
(KB2760498)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c82de87d-3457-423e-9bfc-ec3f950049e7)  
(KB2760416)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=c82de87d-3457-423e-9bfc-ec3f950049e7)  
(KB2760416)  
(существенный)
</td>
</tr>
</table>
 
**Примечания** **к бюллетеню MS12-079**

<sup>[1]</sup>В дополнение к пакету обновления безопасности KB2760421 для Microsoft Office Word 2007 для обеспечения защиты от уязвимости, описанной в данном бюллетене, пользователям необходимо установить обновление безопасности для пакета обеспечения совместимости Microsoft Office (KB2760416).

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Серверное программное обеспечение Майкрософт

 
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
<td style="border:1px solid black;">
[**MS12-080**](http://go.microsoft.com/fwlink/?linkid=272389)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=605fc9bc-a05c-4466-ace6-9c2af087d797)  
(KB2746157)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=e43b1164-d768-4152-b9a3-d1491e2f3cba)  
(KB2787763)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2a49ed58-9dab-4d48-ae8a-c7139e3b34ba)  
(KB2785908)  
(критический)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft SharePoint Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
<td style="border:1px solid black;">
[**MS12-080**](http://go.microsoft.com/fwlink/?linkid=272389)
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
**Нет**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Word Automation Services](http://www.microsoft.com/downloads/details.aspx?familyid=62007dcd-80db-42e4-8478-9e81f89cab98)  
(KB2760405)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-079**](http://go.microsoft.com/fwlink/?linkid=271609)
</td>
<td style="border:1px solid black;">
[**MS12-080**](http://go.microsoft.com/fwlink/?linkid=272389)
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
**Нет**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c98d8ef3-e9a8-4e7c-9e0a-02e192bab39c)  
(KB2687412)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 
**Примечание к** **бюллетеню MS12-079**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
**В центре безопасности**

Управление программным обеспечением и обновлениями для системы безопасности для установки на серверы, настольные и переносные компьютеры организации. Дополнительные сведения см. на веб-сайте [Центра управления обновлениями TechNet](http://go.microsoft.com/fwlink/?linkid=69903). [Центр безопасности TechNet](http://go.microsoft.com/fwlink/?linkid=21171) предоставляет дополнительные сведения о безопасности в продуктах Майкрософт. Также эта информация доступна на веб-сайте [Центра безопасности Майкрософт](http://go.microsoft.com/fwlink/?linkid=85102) в разделе "Обновления для системы безопасности".

Обновления для системы безопасности доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747) и [Центре обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130). Обновления для системы безопасности также доступны на веб-сайте [Центра загрузки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".

Пользователи пакета Microsoft Office для Mac могут следить за установкой последних версий программного обеспечения Майкрософт при помощи приложения Microsoft AutoUpdate для Mac. Дополнительные сведения об использовании приложения Microsoft AutoUpdate для Mac см. в статье [Автоматическая проверка наличия обновлений для программного обеспечения](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

Наконец, обновления для системы безопасности можно загрузить из [каталога Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=96155). Он обеспечивает возможность поиска содержимого (в том числе обновлений для системы безопасности, драйверов и пакетов обновления), которое предоставляется через Центр обновления Windows и Центр обновления Майкрософт. При поиске по номеру бюллетеня по безопасности (например, "MS12-001") можно добавить в корзину все необходимые обновления (в том числе несколько языковых версий одного обновления) и загрузить их в указанную папку. Дополнительные сведения см. на веб-сайте каталога Центра обновления Майкрософт в разделе [вопросов и ответов](http://go.microsoft.com/fwlink/?linkid=97900).

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

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

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

-   [Росарио Валотта (Rosario Valotta)](https://sites.google.com/site/tentacoloviola) за сообщение о двух уязвимостях, описанных в бюллетене MS12-077
-   Фермин Дж. Серна (Fermin J. Serna) из компании [Google Inc](http://www.google.com) за сообщение об уязвимости, описанной в бюллетене MS12-077
-   Иту Люодема (Eetu Luodemaa) и Йони Вахамаки (Joni Vähämäki) из компании [Documill](http://www.documill.com), участвующих в программе Chromium Security Rewards, за сообщение об уязвимости, описанной в бюллетене MS12-078
-   Анонимного исследователя, сотрудничающего с Beyond Security в рамках программы [SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html), за сообщение об уязвимости, описанной в бюллетене MS12-079
-   Лукаса Апа (Lucas Apa) из компании [IOActive](http://ioactive.co.uk/) за сообщение об уязвимости, описанной в бюллетене MS12-081
-   Пользователя [Aniway](mailto:aniway.anyway@gmail.com), сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости, описанной в бюллетене MS12-082

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617.aspx)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (11 декабря 2012 г.): Обзор бюллетеней опубликован.
-   Версия 1.1 (12 декабря 2012 г.): Исправлена информация о необходимости перезагрузки системы в бюллетене MS12-082. Это изменение носит исключительно информационный характер. Файлы обновления остались без изменений.
-   Версия 2.0 (20 декабря 2012 г.): Для бюллетеня MS12-078 повторно выпущено обновление KB2753842, устраняющее проблему, связанную с некорректным отображением ширфтов OpenType после установки исходного обновления. Пользователям, ранее установившим исходное обновление KB2753842, необходимо установить повторно выпущенное обновление.

*Built at 2014-04-18T01:50:00Z-07:00*
