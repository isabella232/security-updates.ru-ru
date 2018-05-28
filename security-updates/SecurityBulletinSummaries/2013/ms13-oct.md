---
TOCTitle: 'MS13-OCT'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за Октябрь 2013 года'
ms:assetid: 'ms13-oct'
ms:contentKeyID: 61236177
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms13-oct(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за Октябрь 2013 года
==================================================================

Дата публикации: 8 октября 2013 г. | Дата обновления: 6 ноября 2013 г.

**Версия:** 1.2

В этом обзоре перечислены бюллетени по безопасности, выпущенные в октябре 2013 г.

После выпуска бюллетеней по безопасности за октябрь 2013 года этот обзор заменит предварительное уведомление, выпущенное 3 октября 2013 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [Службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

9 октября 2013 года в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в октябрьской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557381&culture=en-us).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел Прочие сведения.

### Сведения о бюллетене

#### Аннотации

В приведенной ниже таблице описаны бюллетени по безопасности за этот месяц в порядке, соответствующем уровню опасности.

Сведения об уязвимом программном обеспечении см. в следующем разделе, Подвержены уязвимости.

 
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Накопительное обновление для системы безопасности браузера Internet Explorer (2879017)<br />
<br />
Это обновление для системы безопасности устраняет одну опубликованную и восемь обнаруженных пользователями уязвимостей в Internet Explorer. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь просмотрит особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся наиболее серьезными из данных уязвимостей, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Уязвимости драйверов режима ядра Windows делают возможным удаленное выполнение кода (2870008)<br />
<br />
Это обновление для системы безопасности устраняет семь обнаруженных пользователями уязвимостей в Microsoft Windows. Наиболее серьезная из этих уязвимостей делает возможным удаленное выполнение кода, если пользователь просматривает общее содержимое, в котором внедрены специально созданные файлы шрифтов OpenType или TrueType. Воспользовавшись этими уязвимостями, злоумышленник может получить полный контроль над системой.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">Уязвимости в .NET Framework делают возможным удаленное выполнение кода (2878890)<br />
<br />
Это обновление для системы безопасности устраняет две обнаруженные пользователями и одну опубликованную уязвимости в Microsoft .NET Framework. Наиболее опасная из этих уязвимостей делает возможным удаленное выполнение кода, если пользователи посетят веб-сайт, содержащий специально созданный файл Open Type Font (OTF), используя браузер, который способен создавать экземпляры XBAP-приложений.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314045">MS13-083</a></td>
<td style="border:1px solid black;">Уязвимость в библиотеке общих элементов управления Windows делает возможным удаленное выполнение кода (2864058)<br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость делает возможным удаленное выполнение кода, если злоумышленник отправит специально созданный веб-запрос приложению ASP.NET, которое выполняется в уязвимой системе. Злоумышленник может воспользоваться уязвимостью, чтобы выполнить произвольный код, не проходя проверку подлинности.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft SharePoint Server делают возможным удаленное выполнение кода (2885089)<br />
<br />
Это обновление для системы безопасности устраняет две обнаруженные пользователями уязвимости в программном обеспечении Microsoft Office Server. Наиболее серьезная из этих уязвимостей делает возможным удаленное выполнение кода, если пользователь откроет специально созданный файл Office в уязвимой версии Microsoft SharePoint Server, служб Microsoft Office или Web Apps.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Серверное программное обеспечение Майкрософт</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Excel делают возможным удаленное выполнение кода (2885080)<br />
<br />
Это обновление для системы безопасности устраняет две обнаруженные пользователями уязвимости в Microsoft Office. Данные уязвимости делают возможным удаленное выполнение кода, если пользователи открывают специально созданный файл Office в уязвимой версии Microsoft Excel или другом уязвимом приложении Microsoft Office. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324027">MS13-086</a></td>
<td style="border:1px solid black;">Уязвимости в приложении Microsoft Word делают возможным удаленное выполнение кода (2885084)<br />
<br />
Это обновление для системы безопасности устраняет две обнаруженные пользователями уязвимости в Microsoft Office. Данные уязвимости делают возможным удаленное выполнение кода, если открыть специально созданный файл в уязвимой версии Microsoft Word или другой уязвимой программе Microsoft Office. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324590">MS13-087</a></td>
<td style="border:1px solid black;">Уязвимость в Silverlight может привести к раскрытию информации (2890788)<br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Silverlight. Эта уязвимость может привести к раскрытию информации, если злоумышленник разместит веб-сайт со специально созданным приложением Silverlight, которое способно использовать эту уязвимости, и убедит пользователя посетить веб-сайт. Кроме того, он может воспользоваться уязвимостью через веб-сайты, которые уже подверглись атаке, и веб-сайты, которые принимают или размещают сведения или рекламу. Такие веб-сайты могут включать специальное содержимое, использующее данную уязвимость. В любом случае злоумышленник не может заставить пользователей посетить такой веб-сайт. Вместо этого злоумышленник должен склонить пользователей к посещению веб-сайта, как правило, убеждая их щелкнуть ссылку в сообщении электронной почты или программы обмена мгновенными сообщениями. Специально созданное веб-содержимое можно также отобразить и передать на уязвимые системы посредством рекламных объявлений или иными способами.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Раскрытие информации</td>
<td style="border:1px solid black;">Перезагрузка не требуется</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
</tbody>
</table>
  
Индекс использования уязвимостей  
--------------------------------
  
<span></span>
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости сгруппированы по идентификаторам бюллетеней и затем по кодам CVE. Включены только уязвимости, которым в бюллетенях присвоен уровень серьезности "критический" или "существенный".
  
Как пользоваться этой таблицей?
  
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3872">CVE-2013-3872</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3873">CVE-2013-3873</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3874">CVE-2013-3874</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3875">CVE-2013-3875</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3882">CVE-2013-3882</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3885">CVE-2013-3885</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3886">CVE-2013-3886</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3893">CVE-2013-3893</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Данная уязвимость была открыто опубликована.<br />
<br />
Специалистам Майкрософт известно о направленных атаках с целью использования этой уязвимости в Internet Explorer 8 и Internet Explorer 9.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324021">MS13-080</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3897">CVE-2013-3897</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Специалистам Майкрософт известно о направленных атаках с целью использования этой уязвимости в Internet Explorer 8.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с анализом шрифтов OpenType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3128">CVE-2013-3128</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость также затрагивает <a href="http://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Уязвимость дескриптора Windows USB</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3200">CVE-2013-3200</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Уязвимость Win32k, связанная с использованием протокола после освобождения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3879">CVE-2013-3879</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Уязвимость подсистемы App Container, приводящая к несанкционированному получению прав</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3880">CVE-2013-3880</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">Это уязвимость, которая делает возможным раскрытие информации и последующее несанкционированное повышение привилегий.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Уязвимость Win32k, связанная с пустой страницей</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3881">CVE-2013-3881</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Уязвимость подсистемы графического ядра DirectX, связанная с двойной выборкой</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3888">CVE-2013-3888</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с таблицей TrueType Font CMAP</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3894">CVE-2013-3894</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с анализом шрифтов OpenType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3128">CVE-2013-3128</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Эта уязвимость также затрагивает <a href="http://go.microsoft.com/fwlink/?linkid=314048">MS13-081</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с расширением сущностей</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3860">CVE-2013-3860</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318048">MS13-082</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с анализом</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3861">CVE-2013-3861</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.<br />
<br />
Данная уязвимость была открыто опубликована.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314045">MS13-083</a></td>
<td style="border:1px solid black;">Уязвимость Comctl32, связанная с переполнением целочисленного значения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3195">CVE-2013-3195</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a></td>
<td style="border:1px solid black;">Уязвимость в Microsoft Excel, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3889">CVE-2013-3889</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Эта уязвимость также затрагивает <a href="http://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a></td>
<td style="border:1px solid black;">Уязвимость введения параметра</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3895">CVE-2013-3895</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a></td>
<td style="border:1px solid black;">Уязвимость в Microsoft Excel, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3889">CVE-2013-3889</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Эта уязвимость также затрагивает <a href="http://go.microsoft.com/fwlink/?linkid=324028">MS13-084</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324026">MS13-085</a></td>
<td style="border:1px solid black;">Уязвимость в Microsoft Excel, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3890">CVE-2013-3890</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324027">MS13-086</a></td>
<td style="border:1px solid black;">Уязвимость, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3891">CVE-2013-3891</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324027">MS13-086</a></td>
<td style="border:1px solid black;">Уязвимость, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3892">CVE-2013-3892</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324590">MS13-087</a></td>
<td style="border:1px solid black;">Уязвимость в Silverlight</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3896">CVE-2013-3896</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, которая делает возможным раскрытие информации и последующий обход функций безопасности.</td>
</tr>
</tbody>
</table>
  
Подвержены уязвимости  
---------------------
  
<span></span>
В приведенных ниже таблицах перечислены бюллетени в порядке важности категорий программного обеспечения и уровней опасности.
  
Как пользоваться этими таблицами?
  
Обращайтесь к этим таблицам, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и узнайте, имеются ли для них обновления для системы безопасности. Если программное обеспечение или компонент содержится в списке, для него также указан уровень важности соответствующего обновления программного обеспечения.
  
Примечание. Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификатора бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.
  
#### Компоненты операционных систем Windows

 
<table style="border:1px solid black;">
<tr>
<th colspan="5">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-080](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(критический)  
Internet Explorer 7   
(2879017)  
(критический)  
Internet Explorer 8   
(2879017)  
(критический)
</td>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)  
(2847311)  
(критический)  
Windows XP с пакетом обновления 3 (SP3)  
(2862330)  
(существенный)  
Windows XP с пакетом обновления 3 (SP3)  
(2862335)  
(существенный)  
Windows XP с пакетом обновления 3 (SP3)  
(2868038)  
(существенный)  
Windows XP с пакетом обновления 3 (SP3)  
(2883150)  
(критический)  
Windows XP с пакетом обновления 3 (SP3)  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2863239)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2861189)  
(критический)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2861697)  
(существенный)  
Microsoft .NET Framework 4  
(2858302)  
(существенный)  
Microsoft .NET Framework 4  
(2861188)  
(критический)
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
Internet Explorer 6   
(2879017)  
(критический)  
Internet Explorer 7   
(2879017)  
(критический)  
Internet Explorer 8   
(2879017)  
(критический)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2847311)  
(критический)  
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2862330)  
(существенный)  
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2862335)  
(существенный)  
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2868038)  
(существенный)  
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2883150)  
(критический)  
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2863239)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2861189)  
(критический)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2861697)  
(существенный)  
Microsoft .NET Framework 4  
(2858302)  
(существенный)  
Microsoft .NET Framework 4  
(2861188)  
(критический)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2864058)  
(критический)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-080](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Средний](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(средний)  
Internet Explorer 7  
(2879017)  
(средний)  
Internet Explorer 8  
(2879017)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2847311)  
(критический)  
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2862330)  
(существенный)  
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2862335)  
(существенный)  
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2868038)  
(существенный)  
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2883150)  
(критический)  
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2863239)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2861189)  
(критический)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2861697)  
(существенный)  
Microsoft .NET Framework 4  
(2858302)  
(существенный)  
Microsoft .NET Framework 4  
(2861188)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2864058)  
(уровень опасности не определен)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(средний)  
Internet Explorer 7  
(2879017)  
(средний)  
Internet Explorer 8  
(2879017)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2847311)  
(критический)  
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2862330)  
(существенный)  
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2862335)  
(существенный)  
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2868038)  
(существенный)  
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2883150)  
(критический)  
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2863239)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2861189)  
(критический)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2861697)  
(существенный)  
Microsoft .NET Framework 4  
(2858302)  
(существенный)  
Microsoft .NET Framework 4  
(2861188)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2864058)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2879017)  
(средний)  
Internet Explorer 7  
(2879017)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2847311)  
(критический)  
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2862330)  
(существенный)  
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2862335)  
(существенный)  
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2868038)  
(существенный)  
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2883150)  
(критический)  
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2863239)  
(существенный)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2861697)  
(существенный)  
Microsoft .NET Framework 4  
(2858302)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2864058)  
(критический)
</td>
</tr>
<tr>
<th colspan="5">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-080](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(критический)  
Internet Explorer 8  
(2879017)  
(критический)  
Internet Explorer 9   
(2879017)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2847311)  
(критический)  
Windows Vista с пакетом обновления 2 (SP2)  
(2855844)  
(критический)  
Windows Vista с пакетом обновления 2 (SP2)  
(2862330)  
(существенный)  
Windows Vista с пакетом обновления 2 (SP2)  
(2862335)  
(существенный)  
Windows Vista с пакетом обновления 2 (SP2)  
(2864202)  
(существенный)  
Windows Vista с пакетом обновления 2 (SP2)  
(2868038)  
(существенный)  
Windows Vista с пакетом обновления 2 (SP2)  
(2876284)  
(существенный)  
Windows Vista с пакетом обновления 2 (SP2)  
(2883150)  
(критический)  
Windows Vista с пакетом обновления 2 (SP2)  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2863253)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2861190)  
(критический)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2861697)  
(существенный)  
Microsoft .NET Framework 4  
(2858302)  
(существенный)  
Microsoft .NET Framework 4  
(2861188)  
(критический)  
Microsoft .NET Framework 4.5  
(2861193)  
(критический)  
Microsoft .NET Framework 4.5  
(2861208)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2864058)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(критический)  
Internet Explorer 8  
(2879017)  
(критический)  
Internet Explorer 9   
(2879017)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2847311)  
(критический)  
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2855844)  
(критический)  
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2862330)  
(существенный)  
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2862335)  
(существенный)  
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2864202)  
(существенный)  
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2868038)  
(существенный)  
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2876284)  
(существенный)  
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2883150)  
(критический)  
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2863253)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2861190)  
(критический)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2861697)  
(существенный)  
Microsoft .NET Framework 4  
(2858302)  
(существенный)  
Microsoft .NET Framework 4  
(2861188)  
(критический)  
Microsoft .NET Framework 4.5  
(2861193)  
(критический)  
Microsoft .NET Framework 4.5  
(2861208)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2864058)  
(критический)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-080](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Средний](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(средний)  
Internet Explorer 8  
(2879017)  
(средний)  
Internet Explorer 9   
(2879017)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2847311)  
(критический)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2855844)  
(критический)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2862330)  
(существенный)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2862335)  
(существенный)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2864202)  
(существенный)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2868038)  
(существенный)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2876284)  
(существенный)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2883150)  
(критический)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2863253)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2861190)  
(критический)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2861697)  
(существенный)  
Microsoft .NET Framework 4  
(2858302)  
(существенный)  
Microsoft .NET Framework 4  
(2861188)  
(критический)  
Microsoft .NET Framework 4.5  
(2861193)  
(критический)  
Microsoft .NET Framework 4.5  
(2861208)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2864058)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(средний)  
Internet Explorer 8  
(2879017)  
(средний)  
Internet Explorer 9   
(2879017)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2847311)  
(критический)  
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2855844)  
(критический)  
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2862330)  
(существенный)  
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2862335)  
(существенный)  
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2864202)  
(существенный)  
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2868038)  
(существенный)  
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2876284)  
(существенный)  
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2883150)  
(критический)  
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2863253)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2861190)  
(критический)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2861697)  
(существенный)  
Microsoft .NET Framework 4  
(2858302)  
(существенный)  
Microsoft .NET Framework 4  
(2861188)  
(критический)  
Microsoft .NET Framework 4.5  
(2861193)  
(критический)  
Microsoft .NET Framework 4.5  
(2861208)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2864058)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2879017)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2847311)  
(критический)  
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2862330)  
(существенный)  
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2862335)  
(существенный)  
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2864202)  
(существенный)  
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2868038)  
(существенный)  
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2876284)  
(существенный)  
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2883150)  
(критический)  
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2863253)  
(существенный)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2861697)  
(существенный)  
Microsoft .NET Framework 4  
(2858302)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2864058)  
(критический)
</td>
</tr>
<tr>
<th colspan="5">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-080](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(критический)  
Internet Explorer 9   
(2879017)  
(критический)  
Internet Explorer 10   
(2879017)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2847311)  
(критический)  
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2855844)  
(критический)  
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2862330)  
(существенный)  
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2862335)  
(существенный)  
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2864202)  
(существенный)  
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2868038)  
(существенный)  
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2876284)  
(существенный)  
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2883150)  
(критический)  
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(критический)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(существенный)  
Microsoft .NET Framework 4  
(2858302)  
(существенный)  
Microsoft .NET Framework 4.5  
(2861208)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2864058)  
(уровень опасности не определен)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(критический)  
Internet Explorer 9   
(2879017)  
(критический)  
Internet Explorer 10   
(2879017)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2847311)  
(критический)  
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2855844)  
(критический)  
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2862330)  
(существенный)  
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2862335)  
(существенный)  
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2864202)  
(существенный)  
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2868038)  
(существенный)  
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2876284)  
(существенный)  
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2883150)  
(критический)  
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(критический)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(существенный)  
Microsoft .NET Framework 4  
(2858302)  
(существенный)  
Microsoft .NET Framework 4.5  
(2861208)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2864058)  
(критический)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-080](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Средний](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(средний)  
Internet Explorer 9   
(2879017)  
(средний)  
Internet Explorer 10   
(2879017)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2847311)  
(критический)  
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2855844)  
(критический)  
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2862330)  
(существенный)  
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2862335)  
(существенный)  
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2864202)  
(существенный)  
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2868038)  
(существенный)  
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2876284)  
(существенный)  
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2883150)  
(критический)  
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861191)  
(критический)  
Microsoft .NET Framework 3.5.1  
(2861698)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(существенный)  
Microsoft .NET Framework 4  
(2858302)  
(существенный)  
Microsoft .NET Framework 4.5  
(2861208)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2864058)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2879017)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2847311)  
(критический)  
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2855844)  
(критический)  
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2862330)  
(существенный)  
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2862335)  
(существенный)  
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2864202)  
(существенный)  
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2868038)  
(существенный)  
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2876284)  
(существенный)  
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2883150)  
(критический)  
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861698)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(существенный)  
Microsoft .NET Framework 4  
(2858302)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2864058)  
(критический)
</td>
</tr>
<tr>
<th colspan="5">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-080](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2847311)  
(критический)  
Windows 8 для 32-разрядных систем  
(2862330)  
(существенный)  
Windows 8 для 32-разрядных систем  
(2862335)  
(существенный)  
Windows 8 для 32-разрядных систем  
(2863725)  
(существенный)  
Windows 8 для 32-разрядных систем  
(2864202)  
(существенный)  
Windows 8 для 32-разрядных систем  
(2868038)  
(существенный)  
Windows 8 для 32-разрядных систем  
(2883150)  
(критический)  
Windows 8 для 32-разрядных систем  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(критический)  
Microsoft .NET Framework 3.5  
(2861704)  
(существенный)  
Microsoft .NET Framework 3.5  
(2863243)  
(существенный)  
Microsoft .NET Framework 4.5  
(2861702)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2864058)  
(уровень опасности не определен)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2847311)  
(критический)  
Windows 8 для 64-разрядных систем  
(2862330)  
(существенный)  
Windows 8 для 64-разрядных систем  
(2862335)  
(существенный)  
Windows 8 для 64-разрядных систем  
(2863725)  
(существенный)  
Windows 8 для 64-разрядных систем  
(2864202)  
(существенный)  
Windows 8 для 64-разрядных систем  
(2868038)  
(существенный)  
Windows 8 для 64-разрядных систем  
(2883150)  
(критический)  
Windows 8 для 64-разрядных систем  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(критический)  
Microsoft .NET Framework 3.5  
(2861704)  
(существенный)  
Microsoft .NET Framework 3.5  
(2863243)  
(существенный)  
Microsoft .NET Framework 4.5  
(2861702)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2864058)  
(критический)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-080](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Средний](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2847311)  
(критический)  
Windows Server 2012  
(2862330)  
(существенный)  
Windows Server 2012  
(2862335)  
(существенный)  
Windows Server 2012  
(2863725)  
(существенный)  
Windows Server 2012  
(2864202)  
(существенный)  
Windows Server 2012  
(2868038)  
(существенный)  
Windows Server 2012  
(2883150)  
(критический)  
Windows Server 2012  
(2884256)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(критический)  
Microsoft .NET Framework 3.5  
(2861704)  
(существенный)  
Microsoft .NET Framework 3.5  
(2863243)  
(существенный)  
Microsoft .NET Framework 4.5  
(2861702)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2864058)  
(критический)
</td>
</tr>
<tr>
<th colspan="5">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-080](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2879017)  
(критический)
</td>
<td style="border:1px solid black;">
Windows RT  
(2847311)  
(критический)  
Windows RT  
(2862330)  
(существенный)  
Windows RT  
(2862335)  
(существенный)  
Windows RT  
(2863725)  
(существенный)  
Windows RT  
(2864202)  
(существенный)  
Windows RT  
(2868038)  
(существенный)  
Windows RT  
(2883150)  
(критический)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2861702)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows RT  
(2864058)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<th colspan="5">
Windows 8.1
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-080](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 8.1 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
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
Windows Server 2012 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-080](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Средний](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
(средний)
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
Windows RT 8.1
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-080](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11<sup>[1]</sup>   
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
Вариант установки ядра сервера
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-080](http://go.microsoft.com/fwlink/?linkid=324021)
</td>
<td style="border:1px solid black;">
[MS13-081](http://go.microsoft.com/fwlink/?linkid=314048)
</td>
<td style="border:1px solid black;">
[MS13-082](http://go.microsoft.com/fwlink/?linkid=318048)
</td>
<td style="border:1px solid black;">
[MS13-083](http://go.microsoft.com/fwlink/?linkid=314045)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень опасности
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2847311)  
(критический)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2862330)  
(существенный)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2862335)  
(существенный)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2864202)  
(существенный)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2876284)  
(существенный)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2883150)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2864058)  
(уровень опасности не определен)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2847311)  
(критический)  
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2862330)  
(существенный)  
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2862335)  
(существенный)  
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2864202)  
(существенный)  
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2876284)  
(существенный)  
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2883150)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2864058)  
(критический)
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
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2847311)  
(критический)  
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2862330)  
(существенный)  
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2862335)  
(существенный)  
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2864202)  
(существенный)  
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2876284)  
(существенный)  
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2883150)  
(критический)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2861698)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2863240)  
(существенный)  
Microsoft .NET Framework 4  
(2858302)  
(существенный)  
Microsoft .NET Framework 4.5  
(2861208)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2864058)  
(критический)
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
Windows Server 2012 (установка основных серверных компонентов)  
(2847311)  
(критический)  
Windows Server 2012 (установка основных серверных компонентов)  
(2862330)  
(существенный)  
Windows Server 2012 (установка основных серверных компонентов)  
(2862335)  
(существенный)  
Windows Server 2012 (установка основных серверных компонентов)  
(2863725)  
(существенный)  
Windows Server 2012 (установка основных серверных компонентов)  
(2864202)  
(существенный)  
Windows Server 2012 (установка основных серверных компонентов)  
(2883150)  
(критический)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2861194)  
(критический)  
Microsoft .NET Framework 3.5  
(2861704)  
(существенный)  
Microsoft .NET Framework 3.5  
(2863243)  
(существенный)  
Microsoft .NET Framework 4.5  
(2861702)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(2864058)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (установка основных серверных компонентов)
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
 
Примечание для MS13-080

<sup>[1]</sup>Пользователям Internet Explorer 11 необходимо применить накопительный пакет обновления Windows RT 8.1, Windows 8.1 и Windows Server 2012 R2: Октябрь 2013 г. (2883200). Обратите внимание, что накопительный пакет обновления 2883200 содержит как связанные с безопасностью, так и не связанные с ней изменения. Дополнительные сведения и доступные ссылки для загрузки см. в [статье 2883200 базы знаний Майкрософт](http://support.microsoft.com/kb/2883200).

#### Пакеты приложений и программные продукты Microsoft Office

 
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Office 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-085](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](http://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
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
Microsoft Word 2003 с пакетом обновления 3 (SP3)  
(2826020)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2007
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-085](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](http://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 с пакетом обновления 3 (SP3)  
(2827324)  
(существенный)  
Microsoft Office 2007 с пакетом обновления 3 (SP3)  
(2760585)  
(существенный)  
Microsoft Office 2007 с пакетом обновления 3 (SP3)  
(2760591)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft Word 2007 с пакетом обновления 3 (SP3)  
(2827330)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-085](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](http://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(2826033)  
(существенный)  
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(2826023)  
(существенный)  
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(2826035)  
(существенный)
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
Microsoft Excel 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(2826033)  
(существенный)  
Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(2826023)  
(существенный)  
Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(2826035)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 2 (SP2) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 с пакетом обновления 2 (SP2) (32-разрядные версии)  
(2826033)  
(существенный)  
Microsoft Office 2010 с пакетом обновления 2 (SP2) (32-разрядные версии)  
(2826023)  
(существенный)  
Microsoft Office 2010 с пакетом обновления 2 (SP2) (32-разрядные версии)  
(2826035)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 2 (SP2) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 с пакетом обновления 2 (SP2) (64-разрядные версии)  
(2826033)  
(существенный)  
Microsoft Office 2010 с пакетом обновления 2 (SP2) (64-разрядные версии)  
(2826023)  
(существенный)  
Microsoft Office 2010 с пакетом обновления 2 (SP2) (64-разрядные версии)  
(2826035)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-085](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](http://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (32-разрядные версии)  
(2827238)  
(существенный)  
Microsoft Office 2013 (32-разрядные версии)  
(2817623)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2013 (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (64-разрядные версии)  
(2827238)  
(существенный)  
Microsoft Office 2013 (64-разрядные версии)  
(2817623)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT  
(2827238)  
(существенный)  
Microsoft Office 2013 RT  
(2817623)  
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
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-085](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](http://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office для Mac 2011
</td>
<td style="border:1px solid black;">
Microsoft Office для Mac 2011  
(2889496)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Прочие программы Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-085](http://go.microsoft.com/fwlink/?linkid=324026)
</td>
<td style="border:1px solid black;">
[MS13-086](http://go.microsoft.com/fwlink/?linkid=324027)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)  
(2827326)  
(существенный)
</td>
<td style="border:1px solid black;">
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)  
(2827329)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Средство просмотра Microsoft Excel
</td>
<td style="border:1px solid black;">
Средство просмотра Microsoft Excel  
(2827328)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 

#### Серверное программное обеспечение Майкрософт

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft SharePoint Server 2007
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-084](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 с пакетом обновления 3 (SP3) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Службы Microsoft Windows SharePoint Services 3.0 с пакетом обновления 3 (SP3) (wssloc) (32-разрядные версии)  
(2596741)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 с пакетом обновления 3 (SP3) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Службы Microsoft Windows SharePoint Services 3.0 с пакетом обновления 3 (SP3) (wssloc) (64-разрядные версии)  
(2596741)  
(существенный)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office SharePoint Server 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-084](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 с пакетом обновления 1 (SP1) (wssloc)  
(2589365)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 с пакетом обновления 2 (SP2) (wssloc)  
(2589365)  
(существенный)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-084](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 (pptserver)  
(2760561)  
(существенный)
</td>
</tr>
</table>
 
Примечание для MS13-084

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе Продукты, подверженные уязвимости, и соответствующие обновления. Это бюллетень относится к нескольким категориям ПО.

#### Службы Microsoft Office и Web Apps

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft SharePoint Server 2007
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-084](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 с пакетом обновления 3 (SP3) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Службы Excel  
(2827327)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 с пакетом обновления 3 (SP3) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Службы Excel  
(2827327)  
(существенный)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office SharePoint Server 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-084](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Службы Excel  
(2826029)  
(существенный)  
Word Automation Services  
(2826022)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Службы Excel  
(2826029)  
(существенный)  
Word Automation Services  
(2826022)  
(существенный)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-084](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Службы Excel  
(2752002)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Word Automation Services  
(2826036)  
(существенный)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office Web Apps 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-084](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 с пакетом обновления 1 (SP1)  
(2826030)  
(существенный)  
Microsoft Excel Web App 2010 с пакетом обновления 1 (SP1)  
(2826028)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 с пакетом обновления 2 (SP2)  
(2826030)  
(существенный)  
Microsoft Excel Web App 2010 с пакетом обновления 2 (SP2)  
(2826028)  
(существенный)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office Web Apps 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-084](http://go.microsoft.com/fwlink/?linkid=324028)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2827222)  
(существенный)
</td>
</tr>
</table>
 
Примечание для MS13-084

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе Продукты, подверженные уязвимости, и соответствующие обновления. Это бюллетень относится к нескольким категориям ПО.

#### Программное обеспечение и средства разработки Microsoft

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня
</td>
<td style="border:1px solid black;">
[MS13-087](http://go.microsoft.com/fwlink/?linkid=324590)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Общий уровень серьезности
</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 при установке на Mac  
(2890788)  
(существенный)  
Microsoft Silverlight 5 Developer Runtime при установке в Mac  
(2890788)  
(существенный)  
Microsoft Silverlight 5 при установке на всех поддерживаемых выпусках клиентских систем Microsoft Windows  
(2890788)  
(существенный)  
Microsoft Silverlight 5 Developer Runtime при установке во всех поддерживаемых выпусках клиентских систем Microsoft Windows  
(2890788)  
(существенный)  
Microsoft Silverlight 5 при установке на всех поддерживаемых выпусках серверов Microsoft Windows  
(2890788)  
(существенный)  
Microsoft Silverlight 5 Developer Runtime при установке во всех поддерживаемых выпусках серверных систем Microsoft Windows  
(2890788)  
(существенный)
</td>
</tr>
</table>
 

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
Доступно несколько ресурсов, чтобы помочь администраторам развернуть обновления для системы безопасности.

-   Анализатор безопасности Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений для системы безопасности и типичных ошибок в конфигурации системы безопасности.
-   Службы Windows Server Update Services (WSUS), Systems Management Server (SMS) и System Center Configuration Manager помогают администраторам распространять обновления для системы безопасности.
-   Компоненты средства оценки совместимости с обновлениями, включенные в набор средств для обеспечения совместимости приложений, облегчают тестирование и проверку совместимости обновлений Windows с установленными приложениями.

Информацию об этих и других доступных инструментах см. в статье [Инструменты обеспечения безопасности](http://technet.microsoft.com/security/cc297183).

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Для выпуска бюллетеня, публикуемого каждый второй вторник месяца корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки. Для внеплановых выпусков бюллетеней по безопасности обновленные версии средства удаления вредоносных программ для системы Microsoft Windows недоступны.

#### Обновления, не относящиеся к безопасности и распространяемые через Центр обновления Майкрософт, Центр обновления Windows и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-сайте Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт](http://support.microsoft.com/kb/894199)
-   . Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
-   [Обновления за предыдущие месяцы для служб Windows Server Update Services](http://technet.microsoft.com/wsus/bb456965)
-   . Отображаются все новые, обновленные и повторно выпущенные обновления для продуктов Майкрософт отличных от Microsoft Windows.

#### Программа Microsoft Active Protections Program (MAPP)

Чтобы повысить уровень защиты пользователей, корпорация Майкрософт предоставляет сведения об уязвимостях крупным поставщикам программного обеспечения безопасности перед ежемесячным выпуском обновлений. Эта информация необходима им для усовершенствования программного обеспечения и оборудования для защиты пользователей (антивирусных программ, сетевых систем обнаружения вторжений, а также индивидуальных систем предотвращения вторжений). Сведения о средствах защиты, предоставляемых поставщиками программного обеспечения безопасности, доступны на соответствующих веб-сайтах партнеров, перечисленных в списке партнеров [MAPP](http://go.microsoft.com/fwlink/?linkid=215201).

#### Стратегии безопасности и сообщество

Стратегии управления обновлениями

В статье [Рекомендации по безопасности для управления обновлениями](http://go.microsoft.com/fwlink/?linkid=21168) содержатся дополнительные сведения о рекомендациях Майкрософт по установке обновлений для системы безопасности.

Другие обновления для системы безопасности

Другие обновления безопасности можно загрузить из следующих источников:

-   Обновления для системы безопасности доступны в [Центре загрузки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".
-   Обновления для индивидуальных пользователей доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747).
-   Обновления безопасности, предлагаемые в этом месяце в Центре обновления Windows, можно загрузить с веб-сайта Центра загрузки Майкрософт в виде файлов ISO-образа компакт-диска с выпусками обновлений безопасности. Дополнительные сведения см. в [статье 913086 базы знаний Майкрософт](http://support.microsoft.com/kb/913086).

Сообщество ИТ-специалистов, занимающихся вопросами безопасности

На веб-сайте [сообщества ИТ-специалистов, занимающихся вопросами безопасности](http://go.microsoft.com/fwlink/?linkid=21164), можно найти сведения о способах улучшения системы безопасности и оптимизации ИТ-инфраструктуры предприятия, а также обсудить вопросы безопасности с другими ИТ-специалистами.

#### Благодарности

Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:

MS13-080

-   Пользователя [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3872)
-   Хосе А. Васкеса (Jose A. Vazquez) из Yenteasy Security Research, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3873)
-   Амол Найка (Amol Naik), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3874)
-   Анонимного исследователя, сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3874)
-   Хосе А. Васкеса (Jose A. Vazquez) из Yenteasy Security Research, сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3875)
-   Ивана Фратрича (Ivan Fratric) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3882)
-   Хосе А. Васкеса (Jose A. Vazquez) из Yenteasy Security Research за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3882)
-   Хосе А. Васкеса (Jose A. Vazquez) из Yenteasy Security Research за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3885)
-   Хосе А. Васкеса (Jose A. Vazquez) из Yenteasy Security Research, сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3886)
-   Йоширо Ишикава (Yoshihiro Ishikawa) из компании [LAC Co.](http://www.lac.co.jp/) за совместную работу над устранением уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3893)
-   Пользователя Hoodie22, сотрудничающего с Национальным центром информационной безопасности Нидерландов, за совместную работу над устранением уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3897)
-   Даниеля Чечика (Daniel Chechik) из группы Trustwave SpiderLabs за совместную работу над устранением уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3897)
-   Ренато Еттисбергера (Renato Ettisberger) из компании [IOprotect GmbH](http://ioprotect.ch/) за совместную работу над устранением уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3897)

MS13-081

-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, связанной с анализом шрифтов OpenType (CVE-2013-3128)
-   Энди Девиса (Andy Davis) из [NCC Group](http://www.nccgroup.com/) за сообщение об уязвимости дескриптора Windows USB (CVE-2013-3200)
-   Лукаса Бульоте (Lucas Bouillot) из ANSSI Group за сообщение об уязвимости дескриптора Windows USB (CVE-2013-3200)
-   Сета Гибсона (Seth Gibson) и Дана Центнера (Dan Zentner) их компании [Endgame](http://www.endgame.com/) за сообщение об уязвимости Win32k, связанной с пустой страницей (CVE-2013-3881)
-   Пользователя ZombiE, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости таблицы CMAP шрифтов TrueType (CVE-2013-3895)

MS13-082

-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, связанной с анализом шрифтов OpenType (CVE-2013-3128)
-   Джеймса Форшоу (James Forshaw) из [Context Information Security](http://www.contextis.com/) за сообщение об уязвимости, связанной с расширением сущностей (CVE-2013-3860)

MS13-083

-   孙晓山ТСА институт программного обеспечения китайской академии наук за сообщение об уязвимости в Comctl32, связанной с переполнением целочисленного значения (CVE-2013-3195)

MS13-084

-   Мэтью Юрчика (Mateusz Jurczyk), Ивана Фратрича (Ivan Fratric) и Бена Хокса (Ben Hawkes) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости Microsoft Excel, приводящей к повреждению памяти (CVE-2013-3889)
-   Нутар Кумар Панда (Nutan kumar panda) за сообщение об уязвимости введения параметра (CVE-2013-3895)
-   Ари Элиса-Бахраша (Ari Elias-Bachrach) и Анжелу Кельзо (Angela Kelso) из [национального института здравоохранения](http://nih.gov/) за совместную работу над изменениями для обеспечения многоуровневой защиты, которые включены в данный бюллетень

MS13-085

-   Мэтью Юрчика (Mateusz Jurczyk), Ивана Фратрича (Ivan Fratric) и Бена Хокса (Ben Hawkes) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости Microsoft Excel, приводящей к повреждению памяти (CVE-2013-3889)
-   Мэтью Юрчика (Mateusz Jurczyk), Ивана Фратрича (Ivan Fratric) и Бена Хокса (Ben Hawkes) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости Microsoft Excel, приводящей к повреждению памяти (CVE-2013-3890)

MS13-086

-   Юхонга Бао (Yuhong Bao) за сообщение об уязвимости, приводящей к повреждению памяти (CVE-2013-3891)
-   Мэтью Юрчика (Mateusz Jurczyk), Ивана Фратрича (Ivan Fratric) и Бена Хокса (Ben Hawkes) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3892)

MS13-087

-   Виталия Топорова (Vitaliy Toropov) за сообщение об уязвимости в Silverlight (CVE-2013-3896)

#### Поддержка

-   Подверженное уязвимости программное обеспечение, перечисленное в этом бюллетене, проверено на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (8 октября 2013 г.): Обзор бюллетеней опубликован.
-   Вер. 1.1 (10 октября 2013 г.): для MS13-080, из Индекса использования уязвимостей удалена оценка использования уязвимости CVE-2013-3871. Включение этой уязвимости CVE в исходный индекс использования уязвимостей было ошибкой в документации. CVE-2013-3871 планируется устранить в будущем обновлении для системы безопасности. Это изменение носит исключительно информационный характер. Для MS13-082, в новой версии бюллетеня указано, что установки основных серверных компонентов Windows Server 2012 подвержены уязвимостям, устраняемым обновлением 2861194. Алгоритм обнаружения и файлы обновления для системы безопасности не изменялись. Пользователям, уже выполнившим успешное обновление компьютеров, не требуется выполнять никаких действий.
-   Вер. 1.2 (6 ноября 2013 г.): Для MS13-084 исправлено название продукта для обновления Microsoft Office Web Apps Server 2013 (2827222).

*Built at 2014-04-18T01:50:00Z-07:00*
