---
TOCTitle: 'MS12-MAY'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за май 2012 г.'
ms:assetid: 'ms12-may'
ms:contentKeyID: 61236163
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms12-may(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за май 2012 г.
============================================================

Дата публикации: 8 мая 2012 г. | Дата обновления: 22 мая 2012 г.

**Версия:** 2.1

В этот обзор включены бюллетени по безопасности, выпущенные в мае 2012 года.

После выпуска бюллетеней за май 2012 г. этот обзор заменит предварительное уведомление, выпущенное 3 мая 2012 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

9 мая 2012 г. в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в майской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499667). После наступления этой даты данная веб-трансляция будет доступна по запросу. Дополнительные сведения см. на веб-сайте [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://go.microsoft.com/fwlink/?linkid=217214).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=248419"><strong>MS12-029</strong></a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Word делает возможным удаленное выполнение кода (2680352)</strong><br />
<br />
Это обновление для системы безопасности устраняет уязвимость в пакете Microsoft Office, о которой сообщалось в частном порядке. Эта уязвимость делает возможным удаленное выполнение кода при открытии пользователем особым образом созданного файла RTF. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;"><strong>Комбинированное обновление системы безопасности для Microsoft Office, Windows, .NET Framework и Silverlight (2681578)</strong><br />
<br />
Это обновление для системы безопасности устраняет три опубликованных и семь обнаруженных пользователями уязвимостей в Microsoft Office, Microsoft Windows, Microsoft .NET Framework и Microsoft Silverlight. Эти уязвимости делают возможным удаленное выполнение кода, если пользователь откроет специально созданный документ или посетит вредоносную веб-страницу с внедренными файлами шрифтов TrueType. Злоумышленник не может заставить пользователей посетить вредоносный веб-сайт. Вместо этого злоумышленник должен будет убедить пользователей посетить веб-сайт, обычно приглашая их перейти по соответствующей ссылке, ведущей на этот веб-сайт, в сообщении электронной почты или программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework, Microsoft Silverlight,<br />
Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246970"><strong>MS12-035</strong></a></td>
<td style="border:1px solid black;"><strong>Уязвимости в .NET Framework делают возможным удаленное выполнение кода (2693777)</strong><br />
<br />
Настоящее обновление для системы безопасности устраняет две обнаруженные пользователями уязвимости в .NET Framework. Данная уязвимость делает возможным удаленное выполнение кода в клиентской системе, если пользователь просмотрит особым образом созданную веб-страницу в веб-браузере, который может выполнять браузерные приложения XAML (XBAP). Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft</strong> <strong>Office</strong> <strong>делают возможным удаленное выполнение кода (2663830)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну опубликованную и пять обнаруженных пользователями уязвимостей в Microsoft Office. Эти уязвимости делают возможным удаленное выполнение кода в случае, если пользователь откроет особым образом созданный файл Office. Злоумышленник, успешно воспользовавшийся этими уязвимостями, может получить те же права, которыми обладает вошедший в систему пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=248385"><strong>MS12-031</strong></a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Visio Viewer 2010 делает возможным удаленное выполнение кода (2597981)</strong><br />
<br />
Это обновление для системы безопасности устраняет уязвимость в пакете Microsoft Office, о которой сообщалось в частном порядке. Эта уязвимость делает возможным удаленное выполнение кода при открытии пользователем особым образом созданного файла Visio. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246964"><strong>MS12-032</strong></a></td>
<td style="border:1px solid black;"><strong>Уязвимость в TCP/IP делает возможным несанкционированное получение прав (2688338)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну обнаруженную пользователями и одну опубликованную уязвимость в Microsoft Windows. Наиболее серьезные из этих уязвимостей делают возможным несанкционированное получение прав в том случае, если злоумышленник войдет в систему пользователя и запустит особым образом созданное приложение.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=247902"><strong>MS12-033</strong></a></td>
<td style="border:1px solid black;"><strong>Уязвимость в приложении Windows Partition Manager делает возможным несанкционированное получение прав (2690533)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным несанкционированное получение прав, если злоумышленник войдет в систему и запустит специально созданное приложение. Чтобы воспользоваться этой уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему.</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=248419"><strong>MS12-029</strong></a></td>
<td style="border:1px solid black;">Уязвимость библиотеки RTF, связанная с несовпадением типов объектов</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0183">CVE-2012-0183</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td style="border:1px solid black;">Уязвимость формата файла Excel, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0141">CVE-2012-0141</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td style="border:1px solid black;">Уязвимость формата файла Excel в записи OBJECTLINK, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0142">CVE-2012-0142</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td style="border:1px solid black;">Уязвимость Excel, приводящая к повреждению памяти посредством использования различных модифицированных байт</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0143">CVE-2012-0143</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Только Microsoft Office 2003 подвержен уязвимости.<br />
<br />
О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td style="border:1px solid black;">Уязвимость записи SXLI в Excel, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0184">CVE-2012-0184</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td style="border:1px solid black;">Уязвимость в Excel, связанная с переполнением кучи записями MergeCells</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0185">CVE-2012-0185</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238499"><strong>MS12-030</strong></a></td>
<td style="border:1px solid black;">Уязвимость Excel, связанная с несовпадением типов при анализе серии записей</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1847">CVE-2012-1847</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=248385"><strong>MS12-031</strong></a></td>
<td style="border:1px solid black;">Уязвимость формата файла VSD, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0018">CVE-2012-0018</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это затрагивает Visio Viewer 2010 и Visio Viewer 2010 с пакетом обновления 1 (SP1) (единственные поддерживаемые версии Visio Viewer).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246964"><strong>MS12-032</strong></a></td>
<td style="border:1px solid black;">Уязвимость, связанная с обходом функций Windows Firewall</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0174">CVE-2012-0174</a></td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, связанная с обходом функции безопасности.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246964"><strong>MS12-032</strong></a></td>
<td style="border:1px solid black;">Уязвимость TCP/IP, связанная с двойным освобождением</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0179">CVE-2012-0179</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=247902"><strong>MS12-033</strong></a></td>
<td style="border:1px solid black;">Уязвимость Plug and Play (PnP) Configuration Manager</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0178">CVE-2012-0178</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Уязвимость, связанная с анализом шрифтов TrueType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3402">CVE-2011-3402</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Уязвимость, связанная с анализом шрифтов TrueType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0159">CVE-2012-0159</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Уязвимость .NET Framework при выделении буферного пространства</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0162">CVE-2012-0162</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Уязвимость в GDI+, связанная с типом записей</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0165">CVE-2012-0165</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Уязвимость в GDI+, связанная с переполнением кучи</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0167">CVE-2012-0167</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Уязвимость Silverlight, связанная с двойным освобождением</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0176">CVE-2012-0176</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Уязвимость, связанная с окнами и сообщениями</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0180">CVE-2012-0180</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Уязвимость файла раскладки клавиатуры</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0181">CVE-2012-0181</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251038"><strong>MS12-034</strong></a></td>
<td style="border:1px solid black;">Уязвимость при расчете полосы прокрутки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1848">CVE-2012-1848</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246970"><strong>MS12-035</strong></a></td>
<td style="border:1px solid black;">Уязвимость в .NET Framework при сериализации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0160">CVE-2012-0160</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246970"><strong>MS12-035</strong></a></td>
<td style="border:1px solid black;">Уязвимость в .NET Framework при сериализации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0161">CVE-2012-0161</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
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

 
<table style="border:1px solid black;">
<tr>
<th colspan="5">
ОС Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-035**](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[**MS12-032**](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[**MS12-033**](http://go.microsoft.com/fwlink/?linkid=247902)
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
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=b2ea7a8d-a537-441c-8e80-2ba4ac37e320)  
(KB2660649)  
(только Tablet PC Edition 2005 с пакетом обновления 3 (SP3))  
(существенный)  
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=9a4db1b4-15b2-4fae-83c4-a86331425c9e)  
(KB2659262)  
(существенный)  
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=8d341077-8fcd-4666-a27e-2141a04a321e)  
(KB2676562)  
(критический)  
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=954e8ae9-9247-496a-bbde-76981c49e3b3)  
(KB2686509)  
(существенный)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c9bf7fde-3b6f-44fe-93b3-8a4dc01c1cc5)  
(KB2656407)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=b0803633-7fda-4862-a908-3450180cdaaa)  
(KB2604042)  
(только Media Center Edition 2005 с пакетом обновления 3 (SP3) и Tablet PC Edition 2005 с пакетом обновления 3 (SP3))  
(критический)  
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e)  
(KB2604092)  
(критический)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=18a66b7c-f062-4236-8340-a867b1e31b78)  
(KB2604110)  
(критический)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
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
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6ebaccbc-512b-4f2f-bf2a-8958f012e13f)  
(KB2659262)  
(существенный)  
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e0357165-4400-40a6-a7a4-7b762a1793ba)  
(KB2676562)  
(критический)  
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=f3b1568f-d7ad-4e6e-b45b-53b16b303d9d)  
(KB2686509)  
(существенный)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c9bf7fde-3b6f-44fe-93b3-8a4dc01c1cc5)  
(KB2656407)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e)  
(KB2604092)  
(критический)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=18a66b7c-f062-4236-8340-a867b1e31b78)  
(KB2604110)  
(критический)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
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
<th colspan="5">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-035**](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[**MS12-032**](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[**MS12-033**](http://go.microsoft.com/fwlink/?linkid=247902)
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
Нет
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=bc7bfb79-8eaf-4c22-b1c9-e774c55eb06d)  
(KB2659262)  
(существенный)  
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6287b994-041f-45b7-a230-d689bf1901a8)  
(KB2676562)  
(критический)  
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=167e8c49-f9f6-488b-86ad-4056d3d20213)  
(KB2686509)  
(существенный)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c9bf7fde-3b6f-44fe-93b3-8a4dc01c1cc5)  
(KB2656407)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b0df42a4-7444-4da6-a9b2-35a56bdc64a4)  
(KB2604078)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e)  
(KB2604092)  
(критический)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=18a66b7c-f062-4236-8340-a867b1e31b78)  
(KB2604110)  
(критический)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
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
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=bf7c9aea-dc18-499f-b456-2c29e9a74a15)  
(KB2659262)  
(существенный)  
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=f9f49cd0-24db-4438-afde-aa7113ec2035)  
(KB2676562)  
(критический)  
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4614161c-ae05-43ad-8dd3-85975ec2bc4c)  
(KB2686509)  
(существенный)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c9bf7fde-3b6f-44fe-93b3-8a4dc01c1cc5)  
(KB2656407)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e)  
(KB2604092)  
(критический)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=18a66b7c-f062-4236-8340-a867b1e31b78)  
(KB2604110)  
(критический)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
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
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6414b607-6fb1-4527-b218-c3cb5adfd4d1)  
(KB2659262)  
(существенный)  
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2563425d-4f6e-4f33-b775-a8d421b0e254)  
(KB2676562)  
(критический)  
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=67f659ee-0d28-40f3-ae2f-f8fceeac8bff)  
(KB2686509)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=cb5afeaf-a500-4b71-a91b-a300884b040e)  
(KB2604092)  
(критический)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
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
<th colspan="5">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-035**](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[**MS12-032**](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[**MS12-033**](http://go.microsoft.com/fwlink/?linkid=247902)
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
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e11d8738-379a-4dfe-b21c-495041d9523a)  
(KB2658846)  
(существенный)  
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d8068e95-ac4d-45e8-84b7-b12d633c70b5)  
(KB2659262)  
(существенный)  
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=02c857c6-5dfa-46fb-adef-35eac2bf5f41)  
(KB2660649)  
(существенный)  
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=292d1f3b-a065-4d7d-9046-f35ab7f0591b)  
(KB2676562)  
(критический)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0511303a-79f6-4bd9-8f50-b5836c9c476f)  
(KB2656409)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace)  
(KB2604094)  
(критический)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=06273728-7f22-40db-be11-8fb03e7e0bfb)  
(KB2604105)  
(критический)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b1dc6e10-34eb-45ea-92b3-9983c00f6cb5)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d9d5e290-dc57-4587-b31d-706b541924ec)  
(KB2690533)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=838f588b-2a0d-4dae-b54d-782e6985fd83)  
(KB2658846)  
(существенный)  
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3bde7f59-163c-4491-abc9-a822daa8142f)  
(KB2659262)  
(существенный)  
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=9f97c5a4-62ee-4e4f-8811-a43545d76327)  
(KB2660649)  
(существенный)  
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8f90c09c-a2cb-4adb-ace7-a8bc38d78ba6)  
(KB2676562)  
(критический)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0511303a-79f6-4bd9-8f50-b5836c9c476f)  
(KB2656409)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace)  
(KB2604094)  
(критический)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=06273728-7f22-40db-be11-8fb03e7e0bfb)  
(KB2604105)  
(критический)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d65565d4-d865-438a-bfb7-d71af9dd884e)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=827b9f15-b67d-4dd4-a39b-7c148bae5041)  
(KB2690533)  
(существенный)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-035**](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[**MS12-032**](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[**MS12-033**](http://go.microsoft.com/fwlink/?linkid=247902)
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
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=360adbed-a451-44ed-8675-ca5624ef1cf3)  
(KB2658846)  
(существенный)  
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=47a0df29-f42e-463b-9c15-a93385ff8705)  
(KB2659262)  
(существенный)  
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=278c378b-6ee4-4f80-b9c3-ede885f4bbda)<sup>[3]</sup>
(KB2660649)  
(существенный)  
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=728a84b9-c1b8-46e2-8365-1b542963508a)  
(KB2676562)  
(критический)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0511303a-79f6-4bd9-8f50-b5836c9c476f)  
(KB2656409)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace)  
(KB2604094)  
(критический)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=06273728-7f22-40db-be11-8fb03e7e0bfb)  
(KB2604105)  
(критический)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=7ef72aab-7fd2-4330-bb6a-0c77c3943345)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=46e6e960-b700-4154-b91d-aca74ea9e5df)  
(KB2690533)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=d5a6d617-8ef6-42fa-a325-c15fa7ece7aa)  
(KB2658846)  
(существенный)  
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=4e6d29e1-17fc-4670-9e69-988c040f06e2)  
(KB2659262)  
(существенный)  
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=98c4ac87-eec2-4e02-b0e1-00626bcb0ffd)<sup>[3]</sup>
(KB2660649)  
(существенный)  
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=ab897da8-a927-42eb-87da-1e5cd820f4c0)  
(KB2676562)  
(критический)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0511303a-79f6-4bd9-8f50-b5836c9c476f)  
(KB2656409)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace)  
(KB2604094)  
(критический)  
[Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=06273728-7f22-40db-be11-8fb03e7e0bfb)  
(KB2604105)  
(критический)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=9569d980-766d-4825-bd1c-f30c93d4b035)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=e4ab05ae-3a1c-4d6b-8c84-1165ed741356)  
(KB2690533)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c65df271-8b7d-46d3-81b3-87c0ad05e8d0)  
(KB2659262)  
(существенный)  
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=11da5031-1733-43ea-9204-294eb483c858)  
(KB2676562)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=88501ecb-dcf6-4956-8eab-e1076a975846)  
(KB2656353)  
(критический)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8b504a01-1e6b-42c0-b974-811350302ace)  
(KB2604094)  
(критический)  
[Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d6f0ccd6-c8ec-45a0-beba-155989ca19b3)  
(KB2604111)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c5f7ee25-2fc1-44c7-b3e6-e2c969ecf1bc)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c081b058-b95e-4467-a2fc-fb1a68345c8f)  
(KB2690533)  
(существенный)
</td>
</tr>
<tr>
<th colspan="5">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-035**](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[**MS12-032**](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[**MS12-033**](http://go.microsoft.com/fwlink/?linkid=247902)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=f4d52649-4afc-4c01-b275-93818152f6b7)  
(KB2658846)  
(существенный)  
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=31607fd8-fae8-47a0-971e-0e68be67fb5a)  
(KB2659262)  
(существенный)  
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=35443cfc-0f51-412a-a9d9-91bfb19d805e)  
(KB2660649)  
(существенный)  
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=572af8d4-effb-41a6-8448-7576b03f18fd)  
(KB2676562)  
(критический)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=d04bfc77-d05f-4890-9175-27ad00e84c4a)  
(KB2656410)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337)  
(KB2604114)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=46b8749e-3d8f-472f-a1ea-419f44c6bc00)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=2a4433e4-7f3f-4083-b3e1-eff2d18483af)  
(KB2690533)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=f4d52649-4afc-4c01-b275-93818152f6b7)  
(KB2658846)  
(существенный)  
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=31607fd8-fae8-47a0-971e-0e68be67fb5a)  
(KB2659262)  
(существенный)  
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=35443cfc-0f51-412a-a9d9-91bfb19d805e)  
(KB2660649)  
(существенный)  
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=572af8d4-effb-41a6-8448-7576b03f18fd)  
(KB2676562)  
(критический)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=c06506e6-5838-4bba-9b12-b54dfa30a944)  
(KB2656411)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486)  
(KB2604115)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=46b8749e-3d8f-472f-a1ea-419f44c6bc00)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=2a4433e4-7f3f-4083-b3e1-eff2d18483af)  
(KB2690533)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=7aa0b61b-b42c-4d60-8a7f-c61cbd25d6d9)  
(KB2658846)  
(существенный)  
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=fa38b001-eef8-4153-b077-ea524e8a1e18)  
(KB2659262)  
(существенный)  
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=7e551e0f-3f02-49ee-a5a1-8a7480722a6b)  
(KB2660649)  
(существенный)  
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=c09cbb73-7814-4946-8c0a-323d304dd633)  
(KB2676562)  
(критический)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=d04bfc77-d05f-4890-9175-27ad00e84c4a)  
(KB2656410)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337)  
(KB2604114)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=e89fb3f1-44cb-4fc0-bbc2-8e94d6933322)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=dfa13df5-9e4e-4cf6-b56d-af7db0a0f5ea)  
(KB2690533)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=7aa0b61b-b42c-4d60-8a7f-c61cbd25d6d9)  
(KB2658846)  
(существенный)  
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=fa38b001-eef8-4153-b077-ea524e8a1e18)  
(KB2659262)  
(существенный)  
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=7e551e0f-3f02-49ee-a5a1-8a7480722a6b)  
(KB2660649)  
(существенный)  
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c09cbb73-7814-4946-8c0a-323d304dd633)  
(KB2676562)  
(критический)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=c06506e6-5838-4bba-9b12-b54dfa30a944)  
(KB2656411)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486)  
(KB2604115)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=e89fb3f1-44cb-4fc0-bbc2-8e94d6933322)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=dfa13df5-9e4e-4cf6-b56d-af7db0a0f5ea)  
(KB2690533)  
(существенный)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-035**](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[**MS12-032**](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[**MS12-033**](http://go.microsoft.com/fwlink/?linkid=247902)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=6f815b10-c60d-4e9b-8283-494036985e93)  
(KB2658846)  
(существенный)  
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=34824de4-0f26-4627-8ddb-23d6b9d6671a)  
(KB2659262)  
(существенный)  
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=6dab7283-81ba-4362-adb1-0db25e1f055e)\[4\]  
(KB2660649)  
(существенный)  
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=1a179bf7-17fa-4dc7-b0c1-af6d911373cd)  
(KB2676562)  
(критический)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=d04bfc77-d05f-4890-9175-27ad00e84c4a)  
(KB2656410)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337)  
(KB2604114)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=08ba4320-6c47-4f82-a54f-61a32629b985)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=095c20b3-8e6c-4846-9ba1-6ce0af5e9850)  
(KB2690533)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=6f815b10-c60d-4e9b-8283-494036985e93)  
(KB2658846)  
(существенный)  
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=34824de4-0f26-4627-8ddb-23d6b9d6671a)  
(KB2659262)  
(существенный)  
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=6dab7283-81ba-4362-adb1-0db25e1f055e)\[4\]  
(KB2660649)  
(существенный)  
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1a179bf7-17fa-4dc7-b0c1-af6d911373cd)  
(KB2676562)  
(критический)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=c06506e6-5838-4bba-9b12-b54dfa30a944)  
(KB2656411)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)<sup>[1]</sup>
(KB2656405)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486)  
(KB2604115)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=08ba4320-6c47-4f82-a54f-61a32629b985)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=095c20b3-8e6c-4846-9ba1-6ce0af5e9850)  
(KB2690533)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=b9172218-8a3f-4b0f-a14d-64db3778f4cc)  
(KB2658846)  
(существенный)  
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=d9abec73-150e-40cf-a108-1d8ee89aac92)  
(KB2659262)  
(существенный)  
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=e075c03e-91db-4974-a6ea-8edeba583293)  
(KB2676562)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337)  
(KB2604114)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=34643abe-2905-4ac1-a5f3-3f6ea8724b7a)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=9b66a74a-7022-49ac-89da-8c9ab8105812)  
(KB2690533)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b9172218-8a3f-4b0f-a14d-64db3778f4cc)  
(KB2658846)  
(существенный)  
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d9abec73-150e-40cf-a108-1d8ee89aac92)  
(KB2659262)  
(существенный)  
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=e075c03e-91db-4974-a6ea-8edeba583293)  
(KB2676562)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486)  
(KB2604115)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=34643abe-2905-4ac1-a5f3-3f6ea8724b7a)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=9b66a74a-7022-49ac-89da-8c9ab8105812)  
(KB2690533)  
(существенный)
</td>
</tr>
<tr>
<th colspan="5">
Вариант установки ядра сервера
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-035**](http://go.microsoft.com/fwlink/?linkid=246970)
</td>
<td style="border:1px solid black;">
[**MS12-032**](http://go.microsoft.com/fwlink/?linkid=246964)
</td>
<td style="border:1px solid black;">
[**MS12-033**](http://go.microsoft.com/fwlink/?linkid=247902)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=47a0df29-f42e-463b-9c15-a93385ff8705)  
(KB2659262)  
(существенный)  
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=728a84b9-c1b8-46e2-8365-1b542963508a)  
(KB2676562)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=7ef72aab-7fd2-4330-bb6a-0c77c3943345)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=46e6e960-b700-4154-b91d-aca74ea9e5df)  
(KB2690533)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=4e6d29e1-17fc-4670-9e69-988c040f06e2)  
(KB2659262)  
(существенный)  
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=ab897da8-a927-42eb-87da-1e5cd820f4c0)  
(KB2676562)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=9569d980-766d-4825-bd1c-f30c93d4b035)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=e4ab05ae-3a1c-4d6b-8c84-1165ed741356)  
(KB2690533)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=34824de4-0f26-4627-8ddb-23d6b9d6671a)  
(KB2659262)  
(существенный)  
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=1a179bf7-17fa-4dc7-b0c1-af6d911373cd)  
(KB2676562)  
(существенный)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=d04bfc77-d05f-4890-9175-27ad00e84c4a)  
(KB2656410)  
(Уровень опасности не определен<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=cd42511f-788c-4473-84cc-19bb1623e337)  
(KB2604114)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=08ba4320-6c47-4f82-a54f-61a32629b985)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=095c20b3-8e6c-4846-9ba1-6ce0af5e9850)  
(KB2690533)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=34824de4-0f26-4627-8ddb-23d6b9d6671a)  
(KB2659262)  
(существенный)  
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1a179bf7-17fa-4dc7-b0c1-af6d911373cd)  
(KB2676562)  
(существенный)  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=c06506e6-5838-4bba-9b12-b54dfa30a944)  
(KB2656411)  
(Уровень опасности не определен<sup>[2]</sup>)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4ee3cb61-542e-4e42-aa0e-0cbf8dd89648)  
(KB2656405)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=85e0f8be-cdc7-464b-be43-da23d82b3486)  
(KB2604115)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=38b389d8-d534-4b0a-8dd4-b72a5ce7c4e8)<sup>[1]</sup>
(KB2604121)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=08ba4320-6c47-4f82-a54f-61a32629b985)  
(KB2688338)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=095c20b3-8e6c-4846-9ba1-6ce0af5e9850)  
(KB2690533)  
(существенный)
</td>
</tr>
</table>
 
**Примечания** **к бюллетеню** **MS12-034**

<sup>[1]</sup>**Уязвимости подвержены NET Framework 4 и клиентский профиль .NET Framework 4** Предлагаются два профиля для распространяемых пакетов .NET Framework версии 4: .NET Framework 4 и клиентский профиль .NET Framework 4. Клиентский профиль .NET Framework 4 является частью .NET Framework 4. Уязвимости, устраняемой данным обновлением, подвержены как платформа .NET Framework 4, так и клиентский профиль .NET Framework 4. Дополнительные сведения см. в статье MSDN [Установка .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

<sup>[2]</sup>Уровни серьезности не применимы к данному обновлению для указанного программного обеспечения, так как нет известных направлений атаки с использованием уязвимости, описанной в данном бюллетене. Тем не менее, к качестве дополнительной меры защиты корпорация Microsoft рекомендует пользователям данного программного обеспечения установить это обновление безопасности.

<sup>[3]</sup>Это обновление применимо только для систем Windows Server 2008, если в системе не установлен или не включен дополнительный компонент "Возможности рабочего стола". Для получения дополнительных сведений см. раздел часто задаваемых вопросов об обновлении бюллетеня MS12-034.

\[4\]Это обновление применимо только для систем Windows Server 2008 R2, если в системе не установлен или не включен компонент "Поддержка рукописного ввода" дополнительных Служб рукописного ввода. Для получения дополнительных сведений см. раздел часто задаваемых вопросов об обновлении бюллетеня MS12-034.

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

**Примечания** **к бюллетеню** **MS12-035**

<sup>[1]</sup>**Уязвимости подвержены NET Framework 4 и клиентский профиль .NET Framework 4** Предлагаются два профиля для распространяемых пакетов .NET Framework версии 4: .NET Framework 4 и клиентский профиль .NET Framework 4. Клиентский профиль .NET Framework 4 является частью .NET Framework 4. Уязвимости, устраняемой данным обновлением, подвержены как платформа .NET Framework 4, так и клиентский профиль .NET Framework 4. Дополнительные сведения см. в статье MSDN [Установка .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Пакеты приложений и программные продукты Microsoft Office

 
<table style="border:1px solid black;">
<tr>
<th colspan="5">
Наборы приложений и компоненты Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-029**](http://go.microsoft.com/fwlink/?linkid=248419)
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-030**](http://go.microsoft.com/fwlink/?linkid=238499)
</td>
<td style="border:1px solid black;">
[**MS12-031**](http://go.microsoft.com/fwlink/?linkid=248385)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=9819899d-7f7f-4ddd-9fc8-816a57d2979e)  
(KB2598332)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=0abbf09c-8828-4524-8b38-e34faefa2ae4)  
(KB2598253)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=162901b1-4c1d-476f-99e9-218780897f92)  
(KB2597086)  
(существенный)
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
[Microsoft Word 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c6f79d01-8735-4b0f-a50b-90cde3fba4ee)<sup>[1]</sup>
(KB2596917)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b9a27671-883a-4ab7-b86f-99730a9af729)  
(KB2596672)  
(существенный)  
[Microsoft Office 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=fa054591-b202-47f2-9610-f3cd288d34c0)  
(KB2596792)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=22b9b3a6-ad09-4397-892c-2190a86baf3e)<sup>[1]</sup>
(KB2597161)  
(существенный)  
[Microsoft Office 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6ff6650c-eaf4-4c7d-986c-c4d9e5324dac)  
(KB2597969)  
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
[Microsoft Word 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=c6f79d01-8735-4b0f-a50b-90cde3fba4ee)<sup>[1]</sup>
(KB2596917)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=b9a27671-883a-4ab7-b86f-99730a9af729)  
(KB2596672)  
(существенный)  
[Microsoft Office 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=fa054591-b202-47f2-9610-f3cd288d34c0)  
(KB2596792)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=22b9b3a6-ad09-4397-892c-2190a86baf3e)<sup>[1]</sup>
(KB2597161)  
(существенный)  
[Microsoft Office 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=6ff6650c-eaf4-4c7d-986c-c4d9e5324dac)  
(KB2597969)  
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
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=c355d598-ff4d-4cac-afa9-2de3236a7d71)  
(KB2589337)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=f537f6d0-be63-42af-8b39-fa6f38715f84)  
(KB2597166)  
(существенный)  
[Microsoft Office 2010 (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=2e1060fa-c43d-42df-be5f-f536d9b39ba4)  
(KB2553371)  
(существенный)
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
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=c355d598-ff4d-4cac-afa9-2de3236a7d71)  
(KB2589337)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=f537f6d0-be63-42af-8b39-fa6f38715f84)  
(KB2597166)  
(существенный)  
[Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=2e1060fa-c43d-42df-be5f-f536d9b39ba4)  
(KB2553371)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=91619bcc-9d5d-4011-a185-c405758782be)  
(KB2589337)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=123b96d9-de3f-4aab-bcf8-bf9089fef400)  
(KB2597166)  
(существенный)  
[Microsoft Office 2010 (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=ec4371f6-644d-430d-880f-12425f1b36d4)  
(KB2553371)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
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
[Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=91619bcc-9d5d-4011-a185-c405758782be)  
(KB2589337)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=123b96d9-de3f-4aab-bcf8-bf9089fef400)  
(KB2597166)  
(существенный)  
[Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=ec4371f6-644d-430d-880f-12425f1b36d4)  
(KB2553371)  
(существенный)
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
[**MS12-029**](http://go.microsoft.com/fwlink/?linkid=248419)
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-030**](http://go.microsoft.com/fwlink/?linkid=238499)
</td>
<td style="border:1px solid black;">
[**MS12-031**](http://go.microsoft.com/fwlink/?linkid=248385)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 для Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=8f85fc23-480e-4835-9ce5-0aa56702ef59)  
(KB2665346)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=8f85fc23-480e-4835-9ce5-0aa56702ef59)  
(KB2665346)  
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
[Microsoft Office для Mac 2011](http://www.microsoft.com/downloads/details.aspx?familyid=5d88d3d4-89bd-44c3-9e5a-657998223e2f)  
(KB2665351)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office для Mac 2011](http://www.microsoft.com/downloads/details.aspx?familyid=5d88d3d4-89bd-44c3-9e5a-657998223e2f)  
(KB2665351)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="5">
Прочие программы Microsoft Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-029**](http://go.microsoft.com/fwlink/?linkid=248419)
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
</td>
<td style="border:1px solid black;">
[**MS12-030**](http://go.microsoft.com/fwlink/?linkid=238499)
</td>
<td style="border:1px solid black;">
[**MS12-031**](http://go.microsoft.com/fwlink/?linkid=248385)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Средство просмотра Microsoft Excel
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=9dedfb18-a651-49f7-b1fc-78f7b6cb234a)<sup>[2]</sup>
(KB2596842)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010
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
[Microsoft Visio Viewer 2010 (32-разрядная версия)](http://www.microsoft.com/downloads/details.aspx?familyid=0d21d110-c787-49b6-8384-6eaf9da5a38f)  
(KB2597981)  
(существенный)  
[Microsoft Visio Viewer 2010 с пакетом обновления 1 (SP1) (32-разрядная версия)](http://www.microsoft.com/downloads/details.aspx?familyid=0d21d110-c787-49b6-8384-6eaf9da5a38f)  
(KB2597981)  
(существенный)  
[Microsoft Visio Viewer 2010 (64-разрядная версия):](http://www.microsoft.com/downloads/details.aspx?familyid=331d8247-559c-4040-bdea-84cb6fd5dee2)  
(KB2597981)  
(существенный)  
[Microsoft Visio Viewer 2010 с пакетом обновления 1 (SP1) (64-разрядная версия)](http://www.microsoft.com/downloads/details.aspx?familyid=331d8247-559c-4040-bdea-84cb6fd5dee2)  
(KB2597981)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=80d5a86a-33b0-4464-af76-0fe13bd07a5c)  
(KB2596880)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a8386ad9-635f-45a7-b33e-ac9a3ca55f82)  
(KB2597162)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=80d5a86a-33b0-4464-af76-0fe13bd07a5c)  
(KB2596880)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=a8386ad9-635f-45a7-b33e-ac9a3ca55f82)  
(KB2597162)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 
**Примечание к бюллетеню MS12-029**

<sup>[1]</sup> В дополнение к пакету обновления безопасности KB2596917 для Microsoft Word 2007 для обеспечения защиты от уязвимости, описанной в данном бюллетене, пользователям необходимо установить обновление безопасности для пакета обеспечения совместимости Microsoft Office (KB2596880).

**Примечания** **к бюллетеню** **MS12-030**

<sup>[1]</sup> В дополнение к пакету обновления системы безопасности KB2597161 для Microsoft Excel 2007 для обеспечения защиты от уязвимостей, описанных в данном бюллетене, пользователям необходимо установить обновление безопасности для пакета обеспечения совместимости Microsoft Office (KB2597162).

<sup>[2]</sup>Перед установкой данного обновления безопасности необходимо обновить Microsoft Excel Viewer до уровня поддерживаемого пакета обновления (пакет обновления 2 (SP2) для Excel Viewer 2007 или пакет обновления 3 (SP3) для Excel Viewer 2007). Дополнительные сведения о поддерживаемых программах просмотра Office см. [в статье 979860 базы знаний Майкрософт](http://support.microsoft.com/kb/979860).

**Примечание** **к бюллетеню** **MS12-034**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Программное обеспечение и средства разработки Microsoft

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Silverlight 4
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
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
Microsoft Silverlight 4
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 4](http://www.microsoft.com/downloads/details.aspx?familyid=8ea4fc68-7b03-43f6-bc41-af47e7aa8c7b) в случае установки в ОС Mac  
(KB2690729)  
(критический)  
[Microsoft Silverlight 4](http://www.microsoft.com/downloads/details.aspx?familyid=8ea4fc68-7b03-43f6-bc41-af47e7aa8c7b) в случае установки во всех поддерживаемых выпусках клиентских систем Microsoft Windows  
(KB2690729)  
(критический)  
[Microsoft Silverlight 4](http://www.microsoft.com/downloads/details.aspx?familyid=8ea4fc68-7b03-43f6-bc41-af47e7aa8c7b) в случае установки во всех поддерживаемых выпусках серверных систем Microsoft Windows  
(KB2690729)  
(критический)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Silverlight 5
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-034**](http://go.microsoft.com/fwlink/?linkid=251038)
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
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 5](http://www.microsoft.com/downloads/details.aspx?familyid=fb1258e2-f3df-4a3d-b809-abec619a0c63) при установке на Mac  
(KB2636927)  
(критический)  
[Microsoft Silverlight 5](http://www.microsoft.com/downloads/details.aspx?familyid=fb1258e2-f3df-4a3d-b809-abec619a0c63) при установке на всех поддерживаемых выпусках клиентских систем Microsoft Windows  
(KB2636927)  
(критический)  
[Microsoft Silverlight 5](http://www.microsoft.com/downloads/details.aspx?familyid=fb1258e2-f3df-4a3d-b809-abec619a0c63) при установке на всех поддерживаемых выпусках серверов Microsoft Windows  
(KB2636927)  
(критический)
</td>
</tr>
</table>
 
**Примечание** **к бюллетеню** **MS12-034**

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

-   Анонимного исследователя, сотрудничающего с компанией [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS12-029
-   Пользователя [Omair](http://krash.in/) за сообщение о двух уязвимостях, описанных в MS12-030
-   Пользователя Omair, сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости, описанной в MS12-030
-   Шона Ларссона (Sean Larsson) и Цзюнь Мао (Jun Mao), сотрудничающих с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение о двух увзяимостях, описанных в MS12-030
-   Анонимного исследователя, сотрудничающего с компанией [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS12-030
-   Луиджи Ауриемму (Luigi Auriemma), сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости, описанной в MS12-031
-   Бояна Здрня (Bojan Zdrnja) из компании [INFIGO IS](http://www.infigo.hr/) за сообщение об уязвимости, описанной в MS12-032
-   Анатолия Глаголева (Anatoliy Glagolev) из компании [Genesys Telecommunications](http://www.genesyslab.com/) за совместную работу над устранением уязвимости, описанной в MS12-032
-   Алина Рад Попа (Alin Rad Pop), сотрудничающего с компанией [Tipping Point](http://www.tippingpoint.com/)[в рамках программы Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS12-034
-   Виталия Торопова (Vitaliy Toropov), сотрудничающего с компанией [Tipping Point](http://www.tippingpoint.com/)[в рамках программы Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS12-034
-   Пользователя [Omair](http://krash.in/) за сообщение об уязвимости, описанной в MS12-034
-   Анонимного исследователя, сотрудничающего с [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости, описанной в MS12-034
-   Анонимного исследователя, сотрудничающего с [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости, описанной в MS12-034
-   Алекса Пласкетта (Alex Plaskett) из компании [MWR InfoSecurity](http://www.mwrinfosecurity.com/) за сообщение об уязвимости, описанной в MS12-034
-   Тарджея Мандта (Tarjei Mandt) из компании [Azimuth Security](http://www.azimuthsecurity.com/) за сообщение об уязвимости, описанной в MS12-034
-   Николаса Эконому (Nicolas Economou) из компании [Core Security Technologies](http://www.coresecurity.com/) за сообщение об уязвимости, описанной в MS12-034
-   Джеффа Макдональда (Geoff McDonald) из компании Symantec за сообщение об уязвимости, описанной в MS12-034
-   Пользователя h4ckmp за сообщение об уязвимости, описанной в MS12-034
-   Джеймса Форшо (James Forshaw) из компании [Context Information Security](http://www.contextis.co.uk/) за сообщение о двух увзяимостях, описанных в MS12-035

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617.aspx)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (8 мая 2012 г.) Обзор бюллетеней опубликован.
-   Версия 1.1 (9 мая 2012 г.) Обновлен заголовок записи CVE-2012-1847 в **Индексе использования уязвимостей**.
-   Версия 2.0 (11 мая 2012 г.) В бюллетене MS12-035 исправлен номер обновления безопасности KB2656353 для всех поддерживаемых систем с установленным Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1), кроме системы Windows Server 2003 с пакетом обновления 2 (SP2). В файлы обновления безопасности изменений не вносилось. Пользователям, успешно установившим это обновление ранее, не требуется выполнять никаких действий.
-   Версия 2.1 (22 мая 2012 г.) В бюллетене MS12-034 добавлены сноски для обновления KB2660649 для Windows Server 2008 и Windows Server 2008 R2. В файлы обновления безопасности изменений не вносилось. Пользователям, успешно установившим это обновление ранее, не требуется выполнять никаких действий.

*Built at 2014-04-18T01:50:00Z-07:00*
