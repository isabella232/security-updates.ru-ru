---
TOCTitle: 'MS12-AUG'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за август 2012 года.'
ms:assetid: 'ms12-aug'
ms:contentKeyID: 61236156
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms12-aug(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за август 2012 года.
==================================================================

Дата публикации: 14 августа 2012 г. | Дата обновления: 11 декабря 2012 г.

**Версия:** 3.0

В этом обзоре перечислены бюллетени по безопасности, выпущенные в августе 2012 года.

После выпуска бюллетеней за август 2012 года этот обзор заменит предварительное уведомление, выпущенное 9 августа 2012 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

15 августа 2012 года в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проводит веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в августовской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522490&culture=en-us). После наступления этой даты данная веб-трансляция будет доступна по запросу. Дополнительные сведения см. на веб-сайте [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://go.microsoft.com/fwlink/?linkid=217214).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (2722913)</strong><br />
<br />
Это обновление для системы безопасности устраняет четыре обнаруженных пользователями уязвимости в браузере Internet Explorer. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь просмотрит особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся любой из этих уязвимостей, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257906">MS12-053</a></td>
<td style="border:1px solid black;"><strong>Уязвимость клиента удаленного рабочего стола делает возможным удаленное выполнение кода (2723135)</strong><br />
<br />
Настоящее обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в протоколе удаленного рабочего стола. Данная уязвимость делает возможным удаленное выполнение кода, если злоумышленник отправляет в уязвимую систему серию специально созданных пакетов RDP. По умолчанию протокол удаленного рабочего стола (RDP) отключен во всех операционных системах Windows. Системы, на которых не включен RDP, не подвержены данной уязвимости.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257914">MS12-054</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в компонентах сетевой поддержки Windows</strong> <strong>делают возможным удаленное выполнение кода (2733594)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Наиболее серьезная из этих уязвимостей делает возможным удаленное выполнение кода, если на запрос очереди печати принтера злоумышленник отправит специально созданный ответ. Стандартные параметры конфигурации брандмауэра позволяют защитить сеть от атак из-за пределов корпоративной среды. В системах, напрямую подключенных к Интернет, рекомендуется держать открытыми лишь минимально необходимое количество портов.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254386">MS12-060</a></td>
<td style="border:1px solid black;"><strong>Уязвимость общих элементов управления Windows делает возможным удаленное выполнение кода (2720573)</strong><br />
<br />
Данное обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в общих элементах управления Windows. Данная уязвимость делает возможным удаленное выполнение кода, если пользователь посетит веб-сайт, который содержит специально созданное содержимое, предназначенное для использования данной уязвимости. В любом случае злоумышленник не может заставить пользователей посетить такой веб-сайт. Вместо этого злоумышленник должен будет убедить пользователей посетить веб-сайт, обычно приглашая их перейти по соответствующей ссылке, ведущей на этот веб-сайт, в сообщении электронной почты или программы обмена мгновенными сообщениями. Вредоносный файл также может быть выслан во вложении электронной почты, однако для того чтобы использовать эту уязвимость, злоумышленнику необходимо убедить пользователя открыть вложение.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft SQL Server,<br />
Серверное программное обеспечение Майкрософт,<br />
Средства разработки Microsoft</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=259630">MS12-058</a></td>
<td style="border:1px solid black;"><strong>Уязвимости</strong> <strong>при веб-просмотре документов Microsoft Exchange Server делают возможным удаленное выполнение кода (2740358)<br />
</strong>Это обновление для системы безопасности устраняет опубликованные уязвимости, возникающие при веб-просмотре документов Microsoft Exchange Server. Данные уязвимости делают возможным удаленное выполнение кода в контексте безопасности службы перекодировки на сервере Exchange, если пользователь осуществляет предварительный просмотр специально созданного файла с помощью Outlook Web App (OWA). Служба перекодировки в Exchange, которая используется для веб-просмотра документов, выполняется от имени учетной записи LocalService. У учетной записи LocalService минимальные права на локальном компьютере и анонимные учетные данные в сети.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Перезагрузка не требуется</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257907">MS12-055</a></td>
<td style="border:1px solid black;"><strong>Уязвимость драйверов режима ядра Windows делает возможным несанкционированное получение прав (2731847)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну обнаруженную пользователями уязвимость в Microsoft Windows. Эти уязвимости делают возможным несанкционированное получение прав, если злоумышленник войдет в систему и запустит специально созданное приложение. Чтобы воспользоваться этой уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=256487">MS12-056</a></td>
<td style="border:1px solid black;"><strong>Уязвимость обработчиков JScript и VBScript делает возможным удаленное выполнение кода (2706045)</strong><br />
<br />
Настоящее обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в обработчиках сценариев JScript и VBScript в 64-разрядных версиях Microsoft Windows. Данная уязвимость делает возможным удаленное выполнение кода при посещении пользователем особым образом созданного веб-сайта. Злоумышленник не может заставить пользователей посетить свой веб-сайт. Вместо этого злоумышленник должен будет убедить пользователей посетить веб-сайт, обычно приглашая их перейти по соответствующей ссылке, ведущей на этот веб-сайт, в сообщении электронной почты или программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257684">MS12-057</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Office делает возможным удаленное выполнение кода (2731879)<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Office. Эта уязвимость делает возможным удаленное выполнение кода, если пользователь открывает специально созданный файл или внедряет в файл Office специально созданный графический файл Computer Graphics Metafile (CGM). Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255002">MS12-059</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Visio делает возможным удаленное выполнение кода (2733918)<br />
</strong>Это обновление для системы безопасности устраняет уязвимость в пакете Microsoft Office, о которой сообщалось в частном порядке. Эта уязвимость делает возможным удаленное выполнение кода при открытии пользователем особым образом созданного файла Visio. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a></td>
<td style="border:1px solid black;">Уязвимость макета, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1526">CVE-2012-1526</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a></td>
<td style="border:1px solid black;">Уязвимость асинхронного доступа к пустому объекту, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2521">CVE-2012-2521</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a></td>
<td style="border:1px solid black;">Уязвимость повреждения таблицы виртуальных функций, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2522">CVE-2012-2522</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a></td>
<td style="border:1px solid black;">Уязвимость в JavaScript, связанная с переполнением целочисленного значения и делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2523">CVE-2012-2523</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">Эта уязвимость описана также в <a href="http://go.microsoft.com/fwlink/?linkid=256487">MS12-056</a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257906">MS12-053</a></td>
<td style="border:1px solid black;">Уязвимость в протоколе удаленного рабочего стола</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2526">CVE-2012-2526</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257914">MS12-054</a></td>
<td style="border:1px solid black;">Уязвимость протокола удаленного администрирования, приводящая к отказу в обслуживании</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1850">CVE-2012-1850</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257914">MS12-054</a></td>
<td style="border:1px solid black;">Уязвимость строки формата службы очереди печати принтера</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1851">CVE-2012-1851</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257914">MS12-054</a></td>
<td style="border:1px solid black;">Уязвимость протокола удаленного администрирования, связанная с переполнением кучи</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1852">CVE-2012-1852</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257914">MS12-054</a></td>
<td style="border:1px solid black;">Уязвимость протокола удаленного администрирования, связанная с переполнением стека</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1853">CVE-2012-1853</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257907">MS12-055</a></td>
<td style="border:1px solid black;">Уязвимость Win32k, связанная с использованием протокола после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2527">CVE-2012-2527</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=256487">MS12-056</a></td>
<td style="border:1px solid black;">Уязвимость в JavaScript, связанная с переполнением целочисленного значения и делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2523">CVE-2012-2523</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">Эта уязвимость описана также в <a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257684">MS12-057</a></td>
<td style="border:1px solid black;">Уязвимость формата файла CGM, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2524">CVE-2012-2524</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=259630">MS12-058</a></td>
<td style="border:1px solid black;">Oracle Outside In содержит несколько уязвимостей, представляющих опасность</td>
<td style="border:1px solid black;">Множественные*</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">*Множественные уязвимости, для получения дополнительных сведений см. бюллетень <a href="http://go.microsoft.com/fwlink/?linkid=259630">MS12-058</a>.<br />
<br />
О существовании этих уязвимостей было объявлено.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255002">MS12-059</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с переполнением буфера для форматов DXF-файлов Visio</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1888">CVE-2012-1888</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254386">MS12-060</a></td>
<td style="border:1px solid black;">Уязвимость в MSCOMCTL.OCX RCE</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1856">CVE-2012-1856</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">Корпорации Майкрософт известно об ограниченном количестве направленных атак с целью использования этой уязвимости.</td>
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
[**MS12-052**](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[**MS12-053**](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[**MS12-054**](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[**MS12-055**](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[**MS12-056**](http://go.microsoft.com/fwlink/?linkid=256487)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=e1df425a-a67e-42f8-9eb5-a503f684c201)  
(KB2722913)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5afc85e3-a214-4774-93ab-17f9d199ebde)  
(KB2722913)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=213b3590-381e-437c-9391-ff6d7400f250)  
(KB2722913)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=ccc3d8fb-2631-42d0-87ed-5d29d4b1f598)  
(KB2723135)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=5403c78c-6b87-4788-89c3-0140b887ec6f)  
(KB2705219)  
(критический)  
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=c28e01d6-0030-417d-80dd-b34febd22ec1)  
(KB2712808)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=db21a230-0f6b-4d74-9f32-3718a59efd28)  
(KB2731847)  
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=2fdbe657-1810-4c5d-9ba8-5da148272756)  
(KB2722913)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ce5e8621-5457-4a27-9816-9ce719fd6937)  
(KB2722913)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=01784bbc-20fc-4d0f-bfcd-a5a25dd603e8)  
(KB2722913)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a8eb0583-071d-4d8e-92fb-937035411b49)  
(KB2705219)  
(критический)  
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b9e41497-5c49-45fc-8ad0-c853516609df)  
(KB2712808)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a036c343-5c6e-4484-b7f7-c7161c6880fd)  
(KB2731847)  
(существенный)
</td>
<td style="border:1px solid black;">
[JScript 5.8 и VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=e1b9a081-0329-4db6-b026-04a332cb0b4d)  
(KB2706045)  
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
[**MS12-052**](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[**MS12-053**](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[**MS12-054**](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[**MS12-055**](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[**MS12-056**](http://go.microsoft.com/fwlink/?linkid=256487)
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
Нет
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=e5e3e9be-ba36-4fdf-93f6-a30fb087d273)  
(KB2722913)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0bced0f3-9778-4ee3-86fb-7f28b57adbce)  
(KB2722913)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=19393940-2519-4e97-89cd-de993ced31d5)  
(KB2722913)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2847952f-0234-4cf6-820a-1f0a285b2fb7)  
(KB2705219)  
(существенный)  
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c20f475d-5211-4fdc-8a2f-4408f1baaece)  
(KB2712808)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=50090b08-3f82-4680-b871-2b18fc2386d0)  
(KB2731847)  
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=eb92185b-405a-4d96-b119-13f234a9c4ac)  
(KB2722913)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=26cda257-6607-4bd8-9152-cbcc2a753915)  
(KB2722913)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=fe7a78fc-f882-4748-a9e3-04b85d136ca2)  
(KB2722913)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3833d768-1dab-4a85-822f-87c7fa3db261)  
(KB2705219)  
(существенный)  
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ad883d42-d8bb-482b-bf36-e2007cf73f84)  
(KB2712808)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7f72ba9a-80b2-459d-acad-da6a8b900d6f)  
(KB2731847)  
(существенный)
</td>
<td style="border:1px solid black;">
[JScript 5.8 и VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=81f5d8a5-12e5-4227-ae6f-5aea6ffff2a5)  
(KB2706045)  
(низкий)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=6c5edf14-ecb6-40af-a315-b049457415d6)  
(KB2722913)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=c890335b-6ceb-427a-9cc7-95ef8c26d306)  
(KB2722913)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2fba3a11-3621-464d-ab22-d902195205f4)  
(KB2705219) (существенный)  
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2857701f-3447-452c-a986-9f2fe42fe64d)  
(KB2712808)  
(критический)

</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=9e647f22-2e80-4f4a-b648-615243741df2)  
(KB2731847)  
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
[**MS12-052**](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[**MS12-053**](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[**MS12-054**](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[**MS12-055**](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[**MS12-056**](http://go.microsoft.com/fwlink/?linkid=256487)
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=862bd543-2fc5-4c4c-8d18-4623ccc68166)  
(KB2722913)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=709a85b7-d192-4bba-990a-ea98fdf6e882)  
(KB2722913)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=430a43fa-78b8-4273-81e1-3081767ddcf9)  
(KB2722913)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=cbae6606-3721-48b9-ba3e-9d85df7e08b9)  
(KB2705219)  
(средний)  
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b4b216dc-533e-4fb4-acc8-ce5eb231320e)  
(KB2712808)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=41362740-876e-4c9e-9729-67dea6830438)  
(KB2731847)  
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=da933584-40ba-42a0-82fc-b84b41c6c5a4)  
(KB2722913)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ec48d017-d9ed-4b0e-b51f-0f04996088b6)  
(KB2722913)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=5341a615-b737-4e48-8dfd-828725d9d513)  
(KB2722913)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e4b4e53b-69d6-4ab6-98bb-3f8871048abe)  
(KB2705219)  
(средний)  
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=dc966826-83e6-4bdc-bc58-8b6eb8917934)  
(KB2712808)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=007b4d50-b770-4e8f-b8d0-060f7bb58ad5)  
(KB2731847)  
(существенный)
</td>
<td style="border:1px solid black;">
[JScript 5.8 и VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=294a7eb4-c47f-449f-8931-262bec7d6ecc)  
(KB2706045)  
(существенный)
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
[**MS12-052**](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[**MS12-053**](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[**MS12-054**](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[**MS12-055**](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[**MS12-056**](http://go.microsoft.com/fwlink/?linkid=256487)
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
Нет
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Низкий**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=91062e12-401e-472e-a6b6-0eb7216f5264)  
(KB2722913)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=77612ea1-13fb-4c53-bbd2-8796f0d5a9ed)  
(KB2722913)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=f016949d-b931-49f3-867b-f1c64839379e)  
(KB2722913)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=354e502b-3016-4c5e-8611-bc1b35e1a7eb)  
(KB2705219)  
(средний)  
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=35fb03b1-162a-4552-8bb9-6b564acbd57b)  
(KB2712808)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=ec759712-2f38-41a9-8b6d-c6908cc58479)  
(KB2731847)  
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
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a610d606-ca70-4dbd-9971-b6915dc4dc59)  
(KB2722913)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=defe6c53-66d7-4ea5-93b1-7487ccf19f24)  
(KB2722913)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=e5ab43bb-dbdb-4b2b-bbf2-260297ee5518)  
(KB2722913)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=2b8a730c-46ac-49b7-b9ae-73062d5a79f2)  
(KB2705219)  
(средний)  
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=e89024ca-a9e8-4ebf-91eb-cbf8e05398e7)  
(KB2712808)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=caf68d77-3315-4383-a901-ba0385ffe561)  
(KB2731847)  
(существенный)
</td>
<td style="border:1px solid black;">
[JScript 5.8 и VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=47b2e47f-30f1-48e8-a857-70df319011ef)  
(KB2706045)  
(низкий)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6564a6a1-c8ba-4275-81b5-6664c8e3d010)  
(KB2722913)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=cce9a924-a74c-49e0-869f-6b9c1cd12cba)  
(KB2705219)  
(средний)  
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=57153478-4837-438a-8487-929a48fd758a)  
(KB2712808)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=dee601c7-4ab4-4556-8d83-90864b09d365)  
(KB2731847)  
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
[**MS12-052**](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[**MS12-053**](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[**MS12-054**](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[**MS12-055**](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[**MS12-056**](http://go.microsoft.com/fwlink/?linkid=256487)
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=625c45f5-5ad1-4ade-8883-33019587ab49)  
(KB2722913)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b2760784-6163-4a8d-86fb-72c88ed2b8ef)  
(KB2722913)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=f83f6d97-24f1-4ee0-971d-ab79071fede6)  
(KB2705219)  
(средний)  
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=2bcfb574-a7d0-4d7e-b557-41bdcddfde42)  
(KB2712808)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=c709aabf-4b3f-4780-8b82-c6c33a211e31)  
(KB2731847)  
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=625c45f5-5ad1-4ade-8883-33019587ab49)  
(KB2722913)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=b2760784-6163-4a8d-86fb-72c88ed2b8ef)  
(KB2722913)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=f83f6d97-24f1-4ee0-971d-ab79071fede6)  
(KB2705219)  
(средний)  
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=2bcfb574-a7d0-4d7e-b557-41bdcddfde42)  
(KB2712808)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c709aabf-4b3f-4780-8b82-c6c33a211e31)  
(KB2731847)  
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f5bc6713-2540-4571-ae1f-04f427b33019)  
(KB2722913)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=cac3b463-fb9c-474e-9e3d-bb96f7b4c14f)  
(KB2722913)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=f49e3f9e-8a96-43e6-8b0a-5c9b78cd819d)  
(KB2705219)  
(средний)  
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=655182f9-110b-4b81-b140-0a5986d7343f)  
(KB2712808)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=f62cf24a-8926-4dde-95ac-cc5f62e448be)  
(KB2731847)  
(существенный)
</td>
<td style="border:1px solid black;">
[JScript 5.8 и VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=ece661be-4ddf-42cc-a62b-15ce53b9d74b)  
(KB2706045)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f5bc6713-2540-4571-ae1f-04f427b33019)  
(KB2722913)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=cac3b463-fb9c-474e-9e3d-bb96f7b4c14f)  
(KB2722913)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=f49e3f9e-8a96-43e6-8b0a-5c9b78cd819d)  
(KB2705219)  
(средний)  
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=655182f9-110b-4b81-b140-0a5986d7343f)  
(KB2712808)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=f62cf24a-8926-4dde-95ac-cc5f62e448be)  
(KB2731847)  
(существенный)
</td>
<td style="border:1px solid black;">
[JScript 5.8 и VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=ece661be-4ddf-42cc-a62b-15ce53b9d74b)  
(KB2706045)  
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
[**MS12-052**](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[**MS12-053**](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[**MS12-054**](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[**MS12-055**](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[**MS12-056**](http://go.microsoft.com/fwlink/?linkid=256487)
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
Нет
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Низкий**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f6ea664b-575c-4cf0-b479-d1a2653288ee)  
(KB2722913)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=30a43d95-f489-49c2-a48a-a262fa196bbf)  
(KB2722913)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=e15d2bae-1511-4d74-93cb-0d614820e175)  
(KB2705219)  
(средний)  
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=20c9a72f-a8b6-4b4c-a9ea-de93069cff3a)  
(KB2712808)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=fc5b9df9-c836-407a-a1d4-364c1a885242)  
(KB2731847)  
(существенный)
</td>
<td style="border:1px solid black;">
[JScript 5.8 и VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=bbb876e6-a6b9-4193-be5e-d84390d30f1e)  
(KB2706045)  
(низкий)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f6ea664b-575c-4cf0-b479-d1a2653288ee)  
(KB2722913)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=30a43d95-f489-49c2-a48a-a262fa196bbf)  
(KB2722913)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=e15d2bae-1511-4d74-93cb-0d614820e175)  
(KB2705219)  
(средний)  
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=20c9a72f-a8b6-4b4c-a9ea-de93069cff3a)  
(KB2712808)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=fc5b9df9-c836-407a-a1d4-364c1a885242)  
(KB2731847)  
(существенный)
</td>
<td style="border:1px solid black;">
[JScript 5.8 и VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=bbb876e6-a6b9-4193-be5e-d84390d30f1e)  
(KB2706045)  
(низкий)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=05a09f6e-b608-4430-b6d4-bb9d10d8347a)  
(KB2722913)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=be89e6a5-34ef-4c23-8e16-722b9ae92073)  
(KB2705219)  
(средний)  
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=27b52fb5-ff3c-4dca-9752-1517b873c9cb)  
(KB2712808)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=7f17c057-939e-415d-b56a-01082695ab77)  
(KB2731847)  
(существенный)
</td>
<td style="border:1px solid black;">
[JScript 5.8 и VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=97004a96-0c83-421d-91a9-d55be32610c9)  
(KB2706045)  
(низкий)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=05a09f6e-b608-4430-b6d4-bb9d10d8347a)  
(KB2722913)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=be89e6a5-34ef-4c23-8e16-722b9ae92073)  
(KB2705219)  
(средний)  
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=27b52fb5-ff3c-4dca-9752-1517b873c9cb)  
(KB2712808)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=7f17c057-939e-415d-b56a-01082695ab77)  
(KB2731847)  
(существенный)
</td>
<td style="border:1px solid black;">
[JScript 5.8 и VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=97004a96-0c83-421d-91a9-d55be32610c9)  
(KB2706045)  
(низкий)
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
[**MS12-052**](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[**MS12-053**](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[**MS12-054**](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[**MS12-055**](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[**MS12-056**](http://go.microsoft.com/fwlink/?linkid=256487)
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
</tr>
<tr>
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
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=354e502b-3016-4c5e-8611-bc1b35e1a7eb)  
(KB2705219)  
(средний)  
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=35fb03b1-162a-4552-8bb9-6b564acbd57b)  
(KB2712808)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=ec759712-2f38-41a9-8b6d-c6908cc58479)  
(KB2731847)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
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
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=2b8a730c-46ac-49b7-b9ae-73062d5a79f2)  
(KB2705219)  
(средний)  
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=e89024ca-a9e8-4ebf-91eb-cbf8e05398e7)  
(KB2712808)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=caf68d77-3315-4383-a901-ba0385ffe561)  
(KB2731847)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=e15d2bae-1511-4d74-93cb-0d614820e175)  
(KB2705219)  
(средний)  
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=20c9a72f-a8b6-4b4c-a9ea-de93069cff3a)  
(KB2712808)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=fc5b9df9-c836-407a-a1d4-364c1a885242)  
(KB2731847)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=e15d2bae-1511-4d74-93cb-0d614820e175)  
(KB2705219)  
(средний)  
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=20c9a72f-a8b6-4b4c-a9ea-de93069cff3a)  
(KB2712808)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=fc5b9df9-c836-407a-a1d4-364c1a885242)  
(KB2731847)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 

#### Пакеты приложений и программные продукты Microsoft Office

 
<table style="border:1px solid black;">
<tr>
<th colspan="4">
Пакеты приложений и программные продукты Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-060**](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;">
[**MS12-057**](http://go.microsoft.com/fwlink/?linkid=257684)
</td>
<td style="border:1px solid black;">
[**MS12-059**](http://go.microsoft.com/fwlink/?linkid=255002)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)  
(Общие элементы управления Windows)  
(KB2726929)  
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
Microsoft Office 2007 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)  
(Общие элементы управления Windows)  
(KB2687441)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=cc2a0eae-5b7e-465b-ab4c-a93ae7c7c458)  
(KB2596615)  
(существенный)  
[Microsoft Office 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c2b0cb0f-db07-452f-a9a4-886124d3943e)  
(KB2596754)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)  
(Общие элементы управления Windows)  
(KB2687441)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=cc2a0eae-5b7e-465b-ab4c-a93ae7c7c458)  
(KB2596615)  
(существенный)  
[Microsoft Office 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=c2b0cb0f-db07-452f-a9a4-886124d3943e)  
(KB2596754)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=4e08bab7-1408-444d-bad7-a4db76c7f6d3)  
(Общие элементы управления Windows)  
(KB2597986)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=953b9b69-2f66-4f71-b342-467cc05030ba)  
(KB2687501)  
(существенный)  
[Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=a55a33f9-1eb6-469a-967c-a483764772c3)  
(KB2687510)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=de95d8b9-51a5-43cd-8ba3-8cbb1320d099)  
(KB2687508)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=90b99372-4f13-4f3a-ae52-da6543745248)  
(KB2687501)  
(существенный)  
[Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=da8a4d12-d4fc-4b6e-b65f-096dedddf529)  
(KB2687510)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=af690cd8-cb2c-4743-96f0-ffaec77adf10)  
(KB2687508)  
(существенный)
</td>
</tr>
<tr>
<th colspan="4">
Веб-компоненты Microsoft Office.
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-060**](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;">
[**MS12-057**](http://go.microsoft.com/fwlink/?linkid=257684)
</td>
<td style="border:1px solid black;">
[**MS12-059**](http://go.microsoft.com/fwlink/?linkid=255002)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Веб-компоненты Microsoft Office 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Веб-компоненты Microsoft Office 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)  
(Общие элементы управления Windows)  
(KB2726929)  
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
<th colspan="4">
Прочие программы Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-060**](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;">
[**MS12-057**](http://go.microsoft.com/fwlink/?linkid=257684)
</td>
<td style="border:1px solid black;">
[**MS12-059**](http://go.microsoft.com/fwlink/?linkid=255002)
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
Нет
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 с пакетом обновления 1 (SP1) (32-разрядная версия)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 с пакетом обновления 1 (SP1) (32-разрядная версия)](http://www.microsoft.com/downloads/details.aspx?familyid=62e87f7b-f48e-43a7-86d7-cbb8f0603ea3)  
(KB2598287)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 с пакетом обновления 1 (SP1) (64-разрядная версия)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 с пакетом обновления 1 (SP1) (64-разрядная версия)](http://www.microsoft.com/downloads/details.aspx?familyid=3889e1b3-69b2-4a8f-a0d9-de8c7dc6f5ec)  
(KB2598287)  
(существенный)
</td>
</tr>
</table>
 
**Примечание для MS12-060**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Серверное программное обеспечение Майкрософт

 
<table style="border:1px solid black;">
<tr>
<th colspan="5">
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-060**](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS12-058**](http://go.microsoft.com/fwlink/?linkid=259630)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
Нет
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2000 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[Microsoft SQL Server 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=22be7d30-86f8-4a3b-ba46-b08624581c61)  
(KB983812)  
(критический)  
Обновление QFE:  
[Microsoft SQL Server 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=09ebb11b-2b82-4891-8ae9-03481c0d7b29)  
(KB983811)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Службы анализа Microsoft SQL Server 2000 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Службы анализа Microsoft SQL Server 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=3f5f7d2c-1fd1-437d-a74c-f316c2cd7818)  
(KB983813)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2005 для 32-разрядных систем с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 для 32-разрядных систем с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)<sup>[1]</sup>
(Общие элементы управления Windows)  
(KB2726929)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2005 для 64-разрядных систем с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 для 64-разрядных систем с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)<sup>[1]</sup>
(Общие элементы управления Windows)  
(KB2726929)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2005 для систем на базе процессоров Itanium с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 для систем на базе процессоров Itanium с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)<sup>[1]</sup>
(Общие элементы управления Windows)  
(KB2726929)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2005 Express Edition с дополнительными службами и пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 Express Edition с дополнительными службами и пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)<sup>[1]</sup>
(Общие элементы управления Windows)  
(KB2726929)  
(критический)

</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2687441)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для 32-разрядных систем с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для 32-разрядных систем с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2687441)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2687441)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для 64-разрядных систем с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для 64-разрядных систем с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2687441)  
(критический)

</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для систем на базе процессоров Itanium с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для систем на базе процессоров Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2687441)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 для систем на базе процессоров Itanium с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 для систем на базе процессоров Itanium с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2687441)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2687441)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2687441)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2687441)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2687441)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2687441)  
(критический)

</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для 64-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2687441)  
(критический)

</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для систем на базе процессоров Itanium
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 систем на базе процессоров Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2687441)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для систем на базе процессоров Itanium с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 для систем на базе процессоров Itanium с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2687441)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 для систем на базе процессоров Itanium с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 для систем на базе процессоров Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Общие элементы управления Windows)  
(KB2687441)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<th colspan="5">
Microsoft Commerce Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-060**](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS12-058**](http://go.microsoft.com/fwlink/?linkid=259630)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
Нет
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Commerce Server 2002 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2002 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=9ad19d40-16ed-47ad-b907-8a48bb64c6d3)  
(KB2716389)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Commerce Server 2007 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7d972437-f71a-4576-b5c1-a940c0824438)  
(KB2716390)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Commerce Server 2009
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2009](http://www.microsoft.com/downloads/details.aspx?familyid=3879fecd-8360-4c01-b88e-d56e8570cafb)  
(KB2716392)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Commerce Server 2009 R2
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2009 R2](http://www.microsoft.com/downloads/details.aspx?familyid=ce4f9470-e2b2-417e-9015-30355e837fbb)  
(KB2716393)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<th colspan="5">
Microsoft Host Integration Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Host Integration Server 2004 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2004 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=3dde4ef1-d41f-45b0-8660-a546cbe3fc81)  
(KB2711207)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<th colspan="5">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-060**](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS12-058**](http://go.microsoft.com/fwlink/?linkid=259630)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;" colspan="2">
Нет
</td>
<td style="border:1px solid black;" colspan="2">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
[Microsoft Exchange Server 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=21a26e23-9d83-41b6-95be-4b48f6e76023)  
(KB2756497)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
[Microsoft Exchange Server 2010 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=8646aaca-9829-4d3f-a77b-d24673818da7)  
(KB2756496)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
[Microsoft Exchange Server 2010 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4b24182a-cee9-4ca0-9cc5-c4453475999d)  
(KB2756485)  
(критический)
</td>
</tr>
</table>
 
**Примечания** **к бюллетеню** **MS12-060**

<sup>[1]</sup>Это такое же обновление, как обновление KB2726929 для Microsoft Office 2003

<sup>[2]</sup> Это такое же обновление, как обновление KB2687441 для Microsoft Office 2007

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Программное обеспечение и средства разработки Microsoft

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Visual FoxPro
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-060**](http://go.microsoft.com/fwlink/?linkid=254386)
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
Microsoft Visual FoxPro 8.0 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 8.0 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=0bef712a-b9e0-4ea9-98bf-68db366c8b8b)  
(KB2708940)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 9.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1ee09491-4871-41ca-a39c-8360d5a568d4)  
(KB2708941)  
(критический)
</td>
</tr>
<tr>
<th colspan="2">
Visual Basic
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-060**](http://go.microsoft.com/fwlink/?linkid=254386)
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
Среда выполнения Visual Basic 6.0
</td>
<td style="border:1px solid black;">
[Среда выполнения Visual Basic 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=847ec64b-95be-463b-bdfb-969e91fe3207)  
(KB2708437)  
(критический)
</td>
</tr>
</table>
 
**Примечание для MS12-060**

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

**SystemCenter Configuration Manager**

Управление обновлениями программного обеспечения с помощью диспетчера конфигураций System Center Configuration Manager упрощает сложную задачу получения обновлений и управления обновлениями в ИТ-системах всего предприятия. Используя диспетчер конфигураций System Center Configuration Manager, ИТ-администраторы могут получать обновления продуктов Майкрософт на различные устройства, включая настольные и мобильные компьютеры, серверы и мобильные устройства.

Автоматическая оценка уязвимостей в диспетчере конфигураций System Center Configuration Manager определяет необходимость в обновлениях и сообщает о рекомендуемых действиях. Управление обновлениями программного обеспечения в диспетчере конфигураций System Center Configuration Manager встроено в Microsoft Windows Software Update Services (WSUS), проверенную временем инфраструктуру обновления, хорошо знакомую ИТ-администраторам во всем мире. Подробнее о том, как администраторы могут использовать System Center Configuration Manager для развертывания обновлений, см. в статье [Управление обновлениями программного обеспечения](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). Подробнее о диспетчере конфигураций System Center Configuration Manager см. в статье [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет хорошо сконфигурированное решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей.

**Примечание.** Основная поддержка System Management Server 2003 закончена 12 января 2010 г. Подробнее о жизненном цикле продуктов см. на веб-странице [Жизненный цикл поддержки Майкрософт](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Следующий выпуск сервера SMS (System Center Configuration Manager), уже доступен для загрузки; см. предыдущий раздел **System Center Configuration Manager**.

Подробнее о том, как администраторы могут использовать SMS 2003 для развертывания обновлений системы безопасности, см. [Сценарии и процедуры для Microsoft Systems Management Server 2003: Распространение программного обеспечения и управление исправлениями](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Дополнительные сведения о сервере SMS см. на веб-странице [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Примечание.** Для предоставления широкой поддержки при определении необходимости применения и развертывания обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используется средство Microsoft Baseline Security Analyzer. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. на веб-странице [Развертывание обновлений программного обеспечения с помощью функции распространения программ сервера SMS](http://go.microsoft.com/fwlink/?linkid=33341) (на английском языке). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакета [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)).

**Средство оценки совместимости обновлений и набор средств для обеспечения совместимости приложений**

Часто обновления записываются в одни те же файлы, а для запуска приложений требуется настроить параметры реестра. Это приводит к возникновению несовместимостей и увеличивает время, затрачиваемое на развертывание обновлений для системы безопасности. Облегчить тестирование и проверку обновлений Windows для установленных приложений можно с помощью [компонентов оценки совместимости обновлений](http://technet.microsoft.com/library/cc749197), входящих в состав [набора средств для обеспечения совместимости приложений](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Набор средств для обеспечения совместимости приложений содержит необходимые средства и документацию для выявления проблем совместимости приложений и уменьшения степени воздействия этих проблем перед развертыванием системы Windows Vista, обновлений из Центра обновления Windows, обновлений с веб-сайта безопасности Майкрософт или новой версии проводника.

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

#### Обновления, не относящиеся к безопасности и распространяемые через Центр обновления Майкрософт, Центр обновления Windows и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-сайте Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт](http://support.microsoft.com/kb/894199). Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
-   [Обновления за предыдущие месяцы для служб Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Отображаются все новые, обновленные и повторно выпущенные обновления для продуктов Майкрософт отличных от Microsoft Windows.

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

-   GWSlabs, сотрудничающих с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости, описанной в MS12-052
-   Дерека Соудера (Derek Soeder), сотрудничающего в рамках программы [SecuriTeam Secure Disclosure компании Beyond Security](http://www.beyondsecurity.com/ssd.html), за сообщение об уязвимости, описанной в бюллетене MS12-052
-   Синг-тин Цая (Sing-ting Tsai) и Мин-Чи Пана (Ming-Chieh Pan) из компании [Trend Micro](http://www.trendmicro.com/) за сообщение об уязвимости, описанной в бюллетене MS12-052
-   Криса Некара (Cris Neckar) из [отдела безопасности Google Chrome](http://chrome.google.com/) за сообщение об уязвимости, описанной в бюллетене MS12-052
-   Эдварда Торкингтона (Edward Torkington) из NCC Group за сообщение об уязвимости, описанной в бюллетене MS12-053
-   Ямату Ли (Yamata Li) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимостях, описанных в бюллетене MS12-054
-   [Матеуша "j00ru" Юрчук (Mateusz "j00ru" Jurczyk)](http://j00ru.vexillium.org/) из компании [Google Inc.](http://www.google.com/) за сообщение об уязвимости, описанной в бюллетене MS12-055
-   Криса Некара (Cris Neckar) из [отдела безопасности Google Chrome](http://chrome.google.com/) за сообщение об уязвимости, описанной в бюллетене MS12-056
-   [Aндрея Костина (Andrei Costin)](http://www.andreicostin.com) за сообщение об уязвимости, описанной в бюллетене MS12-057
-   Уилла Дормана (Will Dormann) из компании [CERT/CC](http://www.cert.org/) за совместную работу над устранением 13 уязвимостей, описанных в бюллетене MS12-058
-   Александра Гаврана (Alexander Gavrun), сотрудничающего с [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в бюллетене MS12-059

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617.aspx)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (14 августа 2012 г.): Обзор бюллетеней опубликован.
-   Вер. 2.0 (9 октября 2012 г.): Выпуск новой версии обзора бюллетеней совпадает с повторным выпуском пакетов обновлений в MS12-053, MS12-054, MS12-055 и MS12-058. Пользователям требуется установить повторно выпущенные пакеты обновлений для предотвращении проблемы с цифровыми сертификатами, описанными в Советах по безопасности (Microsoft) (2749655). Дополнительные сведения см. в этих бюллетенях.
-   Версия 3.0 (11 декабря 2012 г.): В бюллетене MS12-057 обновления KB2553260 и KB2589322 заменены обновлениями KB2687501 и KB2687510 соответственно для всех уязвимых выпусков Microsoft Office 2010. В бюллетене MS12-059 обновление KB2597171 заменено обновлением KB2687508 для всех уязвимых выпусков Microsoft Visio 2010. В бюллетене MS12-060 обновление KB2687323 заменено обновлением KB2726929 для общих элементов управления Windows во всех уязвимых выпусках Microsoft Office 2003, Microsoft Office 2003 Web Components и Microsoft SQL Server 2005.

*Built at 2014-04-18T01:50:00Z-07:00*
