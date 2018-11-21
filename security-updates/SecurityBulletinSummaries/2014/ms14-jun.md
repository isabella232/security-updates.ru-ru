---
TOCTitle: 'MS14-JUN'
Title: 'Обзор бюллетеней по безопасности Microsoft за июнь 2014 г.'
ms:assetid: 'ms14-jun'
ms:contentKeyID: 62490222
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms14-jun(v=Security.10)'
---

Обзор бюллетеней по безопасности Microsoft за июнь 2014 г.
==========================================================

Дата публикации: 10 июня 2014 г. | Дата обновления: 17 июня 2014 г.

**Версия:** 1.1

В этот обзор включены бюллетени по безопасности, выпущенные в июне 2014 года.

После выпуска бюллетеней по безопасности за июнь 2014 года данный обзор заменит предварительное уведомление, выпущенное 5 июня 2014 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

11 июня 2014 г. в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в июньской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032572980&culture=en-us).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел **Прочие сведения**.

Аннотации
---------

<span id="sectionToggle0"></span>
В приведенной ниже таблице описаны бюллетени по безопасности за этот месяц в порядке, соответствующем уровню опасности.

Сведения об уязвимом программном обеспечении см. в следующем разделе, **Подвержены уязвимости**.

 
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (2969262)<br />
<br />
</strong>Это обновление для системы безопасности устраняет две опубликованных уязвимости и пятьдесят семь уязвимостей в Internet Explorer, о которых сообщалось в частном порядке. Наиболее серьезная из этих уязвимостей делает возможным удаленное выполнение кода, если пользователь просматривает особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;"><strong>Уязвимости компонента Microsoft Graphics делает возможным удаленное выполнение кода (2967487)</strong><br />
<br />
Данное обновление для системы безопасности устраняет две уязвимости, о которых сообщалось в частном порядке, в Microsoft Windows, Microsoft Office и Microsoft Lync. Эти уязвимости делают возможным удаленное выполнение кода в случае, если пользователь откроет особым образом созданный файл или веб-страницу. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office, Microsoft Lync</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400971">MS14-034</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Word делает возможным удаленное выполнение кода (2969261)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Office. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если открыть специально созданный файл в уязвимой версии Microsoft Word. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=398119">MS14-033</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в MSXML может привести к раскрытию информации (2966061)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость может привести к раскрытию информации, если вошедшие в систему пользователи посетят специально созданный веб-сайт, предназначенный для вызова MSXML через Internet Explorer. Однако в любом случае злоумышленник не может заставить пользователей посетить такие веб-сайты. Вместо этого злоумышленник должен будет убедить пользователей посетить веб-сайт, обычно приглашая их перейти по ведущей на него ссылке в сообщении электронной почты или программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Раскрытие информации</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400969">MS14-032</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в пакете Microsoft Lync Server может привести к раскрытию информации (2969258)</strong><br />
<br />
Данное обновление для системы безопасности устраняет обнаруженную пользователями уязвимость Microsoft Lync Server. Данная уязвимость может привести к раскрытию информации, если пользователи пытаются присоединиться к собранию Lync, щелкая по специально созданной ссылке на собрание.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Раскрытие информации</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Lync Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396824">MS14-031</a></td>
<td style="border:1px solid black;"><strong>Уязвимость протокола TCP делает возможной атаку типа &quot;отказ в обслуживании&quot; (2962478)<br />
</strong><br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;, если злоумышленник отправит целевой системе последовательность специально созданных пакетов.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400970">MS14-030</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в удаленном рабочем столе делает возможным подделку (2969259)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Уязвимость делает возможной подделку, если злоумышленник получает доступ к тому же сегменту сети, что и целевая система во время сеанса RDP (Протокол удаленного рабочего стола), а затем посылает целевой системе особым образом созданные пакеты RDP. По умолчанию служба RDP не включена во всех операционных системах Windows. Системы, на которых не включен RDP, не подвержены данной уязвимости.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Подделка</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
 
  
Индекс использования уязвимостей  
--------------------------------
  
<span id="sectionToggle1"></span>
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости сгруппированы по идентификаторам бюллетеней и затем по кодам CVE. Включены только уязвимости, которым в бюллетенях присвоен уровень серьезности "критический" или "существенный".
  
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать о вероятности появления эксплойтов для выполнения произвольного кода и DoS-атаки в течение 30 дней после выпуска бюллетеня по каждому из обновлений безопасности, которые необходимо установить. Чтобы назначить приоритеты развертывания, ознакомьтесь с приведенными ниже оценками в соответствии с вашей конфигурацией. Дополнительные сведения об уровнях опасности и способах их определения см. в [индексе использования уязвимостей](http://technet.microsoft.com/security/cc998259).
  
В приведенной ниже таблице "последний выпуск программного обеспечения" обозначает соответствующее программное обеспечение, а термином "старые выпуски программного обеспечения" обозначены все прежние поддерживаемые выпуски программного обеспечения, указанные в таблице "Подвержены уязвимости" или "Не подвержены уязвимости" в этом бюллетене.
  
<table style="width:100%;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Идентификатор бюллетеня</strong></td>
<td style="border:1px solid black;"><strong>Название уязвимости</strong></td>
<td style="border:1px solid black;"><strong>Код CVE</strong></td>
<td style="border:1px solid black;"><strong>Оценка возможности использования уязвимостей для последнего выпуска программного обеспечения</strong></td>
<td style="border:1px solid black;"><strong>Оценка возможности использования уязвимостей для более старых выпусков программного обеспечения</strong></td>
<td style="border:1px solid black;"><strong>Оценка использования уязвимости типа &quot;отказ в обслуживании&quot;</strong></td>
<td style="border:1px solid black;"><strong>Краткие примечания</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400970">MS14-030</a></td>
<td style="border:1px solid black;">Уязвимость MAC из RDP</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0296">CVE-2014-0296</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Эта уязвимость, приводящая к подделке.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396824">MS14-031</a></td>
<td style="border:1px solid black;">Уязвимость в TCP, делающая возможной атаку типа &quot;отказ в обслуживании&quot;</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1811">CVE-2014-1811</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400969">MS14-032</a></td>
<td style="border:1px solid black;">Уязвимость способа очистки содержимого Lync Server</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1823">CVE-2014-1823</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=398119">MS14-033</a></td>
<td style="border:1px solid black;">Уязвимость URI объектов MSXML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1816">CVE-2014-1816</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400971">MS14-034</a></td>
<td style="border:1px solid black;">Уязвимость внедренных шрифтов</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2778">CVE-2014-2778</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0282">CVE-2014-0282</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1762">CVE-2014-1762</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к несанкционированному повышению привилегий</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1764">CVE-2014-1764</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1766">CVE-2014-1766</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1769">CVE-2014-1769</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1770">CVE-2014-1770</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с повторным согласованием сертификатов серверов TLS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1771">CVE-2014-1771</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.<br />
<br />
О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1772">CVE-2014-1772</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1773">CVE-2014-1773</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1774">CVE-2014-1774</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1775">CVE-2014-1775</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к раскрытию информации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1777">CVE-2014-1777</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к несанкционированному повышению привилегий</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1778">CVE-2014-1778</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1779">CVE-2014-1779</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1780">CVE-2014-1780</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1781">CVE-2014-1781</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1782">CVE-2014-1782</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1783">CVE-2014-1783</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1784">CVE-2014-1784</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1785">CVE-2014-1785</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1786">CVE-2014-1786</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1788">CVE-2014-1788</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1789">CVE-2014-1789</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1790">CVE-2014-1790</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1791">CVE-2014-1791</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1792">CVE-2014-1792</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1794">CVE-2014-1794</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1795">CVE-2014-1795</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1796">CVE-2014-1796</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1797">CVE-2014-1797</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1799">CVE-2014-1799</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1800">CVE-2014-1800</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1802">CVE-2014-1802</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1803">CVE-2014-1803</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1804">CVE-2014-1804</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1805">CVE-2014-1805</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2753">CVE-2014-2753</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2754">CVE-2014-2754</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2755">CVE-2014-2755</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2756">CVE-2014-2756</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2757">CVE-2014-2757</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2758">CVE-2014-2758</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2759">CVE-2014-2759</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2760">CVE-2014-2760</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2761">CVE-2014-2761</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2763">CVE-2014-2763</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2764">CVE-2014-2764</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2765">CVE-2014-2765</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2766">CVE-2014-2766</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2767">CVE-2014-2767</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2768">CVE-2014-2768</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2769">CVE-2014-2769</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2770">CVE-2014-2770</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2771">CVE-2014-2771</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2772">CVE-2014-2772</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2773">CVE-2014-2773</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2775">CVE-2014-2775</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2776">CVE-2014-2776</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к несанкционированному повышению привилегий</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2777">CVE-2014-2777</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2782">CVE-2014-2782</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">Уязвимость в Unicode Script Processor</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1817">CVE-2014-1817</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Оценка возможности использования уязвимости предназначена для уязвимого программного обеспечения Microsoft Windows.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">Уязвимость в Unicode Script Processor</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1817">CVE-2014-1817</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Оценка возможности использования уязвимости предназначена для уязвимого программного обеспечения Microsoft Office.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">Уязвимость в Unicode Script Processor</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1817">CVE-2014-1817</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Оценка возможности использования уязвимости предназначена для уязвимого программного обеспечения Microsoft Lync.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с анализом изображений GDI+</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1818">CVE-2014-1818</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Оценка возможности использования уязвимости предназначена для уязвимого программного обеспечения Microsoft Windows.<br />
<br />
Это уязвимость, делающая возможной атаку типа &quot;отказ в обслуживании&quot;, в последних версиях программного обеспечения.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с анализом изображений GDI+</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1818">CVE-2014-1818</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Оценка возможности использования уязвимости предназначена для уязвимого программного обеспечения Microsoft Office.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с анализом изображений GDI+</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1818">CVE-2014-1818</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Оценка возможности использования уязвимости предназначена для уязвимого программного обеспечения Microsoft Lync.</td>
</tr>
</tbody>
</table>
  
Подвержены уязвимости  
---------------------
  
<span id="sectionToggle2"></span>
В приведенных ниже таблицах перечислены бюллетени в порядке важности категорий программного обеспечения и уровней опасности.
  
**Как пользоваться этими таблицами?**
  
Обращайтесь к этим таблицам, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и узнайте, имеются ли для них обновления для системы безопасности. Если программное обеспечение или компонент содержится в списке, для него также указан уровень важности соответствующего обновления программного обеспечения.
  
**Примечание.** Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификатора бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.
  
### Компоненты операционных систем Windows

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Низкий**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**Нет**

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
Internet Explorer 6  
(2957689)  
(существенный)  
Internet Explorer 7  
(2957689)  
(существенный)  
Internet Explorer 8  
(2957689)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(Windows GDI+)  
(2957503)  
(критический)  
Windows Server 2003 с пакетом обновления 2 (SP2)  
(usp10)  
(2957509)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0  
(2939576)  
(низкий)  
MSXML 6.0  
(2957482)  
(низкий)

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
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2957689)  
(существенный)  
Internet Explorer 7  
(2957689)  
(существенный)  
Internet Explorer 8  
(2957689)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(Windows GDI+)  
(2957503)  
(критический)  
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(usp10)  
(2957509)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0  
(2939576)  
(низкий)  
MSXML 6.0  
(2957482)  
(низкий)

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
Internet Explorer 6  
(2957689)  
(существенный)  
Internet Explorer 7  
(2957689)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(Windows GDI+)  
(2957503)  
(критический)  
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(usp10)  
(2957509)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0  
(2939576)  
(низкий)  
MSXML 6.0  
(2957482)  
(низкий)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
<td style="border:1px solid black;">
**Нет**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2957689)  
(критический)  
Internet Explorer 8  
(2957689)  
(критический)  
Internet Explorer 9  
(2957689)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(Windows GDI+)  
(2957503)  
(критический)  
Windows Vista с пакетом обновления 2 (SP2)  
(usp10)  
(2957509)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0 и MSXML 6.0  
(2939576)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2957189)  
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
Internet Explorer 7  
(2957689)  
(критический)  
Internet Explorer 8  
(2957689)  
(критический)  
Internet Explorer 9  
(2957689)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(Windows GDI+)  
(2957503)  
(критический)  
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(usp10)  
(2957509)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0 и MSXML 6.0  
(2939576)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2957189)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Низкий**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2957689)  
(существенный)  
Internet Explorer 8  
(2957689)  
(существенный)  
Internet Explorer 9  
(2957689)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(Windows GDI+)  
(2957503)  
(критический)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(usp10)  
(2957509)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0 и MSXML 6.0  
(2939576)  
(низкий)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2957189)  
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
Internet Explorer 7  
(2957689)  
(существенный)  
Internet Explorer 8  
(2957689)  
(существенный)  
Internet Explorer 9  
(2957689)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(Windows GDI+)  
(2957503)  
(критический)  
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(usp10)  
(2957509)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0 и MSXML 6.0  
(2939576)  
(низкий)

</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2957189)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2957689)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(Windows GDI+)  
(2957503)  
(критический)  
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(usp10)  
(2957509)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0 и MSXML 6.0  
(2939576)  
(низкий)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2957189)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
(2957689)  
(критический)  
Internet Explorer 9  
(2957689)  
(критический)  
Internet Explorer 10  
(2957689)  
(критический)  
Internet Explorer 11  
(2957689)  
(критический)  
Internet Explorer 11  
(2963950)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(Windows GDI+)  
(2957503)  
(критический)  
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(usp10)  
(2957509)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0 и MSXML 6.0  
(2939576)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2957189)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2965788)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2957689)  
(критический)  
Internet Explorer 9  
(2957689)  
(критический)  
Internet Explorer 10  
(2957689)  
(критический)  
Internet Explorer 11  
(2957689)  
(критический)  
Internet Explorer 11  
(2963950)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(Windows GDI+)  
(2957503)  
(критический)  
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(usp10)  
(2957509)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0 и MSXML 6.0  
(2939576)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2957189)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2965788)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2957689)  
(существенный)  
Internet Explorer 9  
(2957689)  
(существенный)  
Internet Explorer 10  
(2957689)  
(существенный)  
Internet Explorer 11  
(2957689)  
(существенный)  
Internet Explorer 11  
(2963950)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(Windows GDI+)  
(2957503)  
(критический)  
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(usp10)  
(2957509)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0 и MSXML 6.0  
(2939576)  
(низкий)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2957189)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2957689)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(Windows GDI+)  
(2957503)  
(критический)  
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(usp10)  
(2957509)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0 и MSXML 6.0  
(2939576)  
(низкий)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2957189)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 и Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
(2957689)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(gdi32)  
(2964736)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0  
(2939576)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2957189)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2965788)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2957689)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(gdi32)  
(2964736)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0  
(2939576)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2957189)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2965788)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2957689)  
(критический)  
Internet Explorer 11  
(2963950)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(gdi32)  
(2964736)  
(критический)  
Windows 8.1 для 32-разрядных систем  
(gdi32)  
(2965155)  
(критический)  
Windows 8.1 для 32-разрядных систем  
(DirectWrite)  
(2964718)  
(критический)  
Windows 8.1 для 32-разрядных систем  
(DirectWrite)  
(2965161)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0  
(2939576)  
(существенный)  
MSXML 3.0  
(2966631)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(2957189)  
(существенный)  
Windows 8.1 для 32-разрядных систем  
(2961858)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(2965788)  
(существенный)  
Windows 8.1 для 32-разрядных систем  
(2966034)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2957689)  
(критический)  
Internet Explorer 11  
(2963950)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(gdi32)  
(2964736)  
(критический)  
Windows 8.1 для 64-разрядных систем  
(gdi32)  
(2965155)  
(критический)  
Windows 8.1 для 64-разрядных систем  
(DirectWrite)  
(2964718)  
(критический)  
Windows 8.1 для 64-разрядных систем  
(DirectWrite)  
(2965161)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0  
(2939576)  
(существенный)  
MSXML 3.0  
(2966631)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(2957189)  
(существенный)  
Windows 8.1 для 64-разрядных систем  
(2961858)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(2965788)  
(существенный)  
Windows 8.1 для 64-разрядных систем  
(2966034)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 и Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2957689)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(gdi32)  
(2964736)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0  
(2939576)  
(низкий)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2957189)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2965788)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2957689)  
(существенный)  
Internet Explorer 11  
(2963950)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(gdi32)  
(2964736)  
(критический)  
Windows Server 2012 R2  
(gdi32)  
(2965155)  
(критический)  
Windows Server 2012 R2  
(DirectWrite)  
(2964718)  
(критический)  
Windows Server 2012 R2  
(DirectWrite)  
(2965161)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0  
(2939576)  
(низкий)  
MSXML 3.0  
(2966631)  
(низкий)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2957189)  
(существенный)  
Windows Server 2012 R2  
(2961858)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2965788)  
(существенный)  
Windows Server 2012 R2  
(2966034)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT и Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
<td style="border:1px solid black;">
**Нет**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2957689)  
(критический)

</td>
<td style="border:1px solid black;">
Windows RT  
(gdi32)  
(2964736)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0  
(2939576)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows RT  
(2957189)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2957689)  
(критический)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(gdi32)  
(2964736)  
(критический)  
Windows RT 8.1  
(DirectWrite)  
(2964718)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0  
(2939576)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2957189)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Вариант установки ядра сервера**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

</td>
</tr>
<tr>
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
[**Низкий**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов) (Windows GDI+)  
(2957503)  
(критический)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(usp10)  
(2957509)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0 и MSXML 6.0  
(2939576)  
(низкий)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2957189)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(Windows GDI+)  
(2957503)  
(критический)  
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(usp10)  
(2957509)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0 и MSXML 6.0  
(2939576)  
(низкий)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2957189)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

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
(Windows GDI+)  
(2957503)  
(критический)  
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(usp10)  
(2957509)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0 и MSXML 6.0  
(2939576)  
(низкий)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2957189)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

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
Windows Server 2012 (установка основных серверных компонентов)  
(gdi32)  
(2964736)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0  
(2939576)  
(низкий)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(2957189)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(2965788)  
(существенный)

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
Windows Server 2012 R2 (установка основных серверных компонентов)  
(gdi32)  
(2964736)  
(критический)  
Windows Server 2012 R2 (установка основных серверных компонентов)  
(gdi32)  
(2965155)  
(критический)  
Windows Server 2012 R2 (установка основных серверных компонентов)  
(DirectWrite)  
(2964718)  
(критический)  
Windows Server 2012 R2 (установка основных серверных компонентов)  
(DirectWrite)  
(2965161)  
(критический)

</td>
<td style="border:1px solid black;">
MSXML 3.0  
(2939576)  
(низкий)  
MSXML 3.0  
(2966631)  
(низкий)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (установка основных серверных компонентов)  
(2957189)  
(существенный)  
Windows Server 2012 R2 (установка основных серверных компонентов)  
(2961858)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (установка основных серверных компонентов)  
(2965788)  
(существенный)  
Windows Server 2012 R2 (установка основных серверных компонентов)  
(2966034)  
(существенный)

</td>
</tr>
</table>
 
**Примечание для MS14-036**

Это бюллетень относится к нескольким категориям ПО. В других таблицах этого раздела перечислено дополнительное уязвимое программное обеспечение.

 

### Наборы приложений и прочие программные продукты Office

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-034**](http://go.microsoft.com/fwlink/?linkid=400971)

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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 3 (SP3)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 3 (SP3)  
(2878233)  
(существенный)  
Microsoft Office 2007 с пакетом обновления 3 (SP3)  
(2881069)  
(существенный)

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 с пакетом обновления 3 (SP3)  
(2880515)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-034**](http://go.microsoft.com/fwlink/?linkid=400971)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(2863942)  
(существенный)  
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(2767915)  
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
Microsoft Office 2010 с пакетом обновления 2 (SP2) (32-разрядные версии)  
(2863942)  
(существенный)  
Microsoft Office 2010 с пакетом обновления 2 (SP2) (32-разрядные версии)  
(2767915)  
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
Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(2863942)  
(существенный)  
Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(2767915)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 2 (SP2) (64-разрядные версии)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 2 (SP2) (64-разрядные версии)  
(2863942)  
(существенный)  
Microsoft Office 2010 с пакетом обновления 2 (SP2) (64-разрядные версии)  
(2767915)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Пакет обеспечения совместимости Microsoft Office**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-034**](http://go.microsoft.com/fwlink/?linkid=400971)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**

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
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)  
(2880513)  
(существенный)

</td>
</tr>
</table>
 
**Примечание для MS14-036**

Это бюллетень относится к нескольким категориям ПО. В других таблицах этого раздела перечислено дополнительное уязвимое программное обеспечение.

 

### Платформы и программное обеспечение Microsoft Communication

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Live Meeting 2007 Console**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-032**](http://go.microsoft.com/fwlink/?linkid=400969)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console\[

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console  
(2968966)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-032**](http://go.microsoft.com/fwlink/?linkid=400969)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32-разрядная версия)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32-разрядная версия)  
(2963285)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64-разрядная версия)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64-разрядная версия)  
(2963285)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

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
(2963282)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(установка на уровне администратора)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(установка на уровне администратора)  
(2963284)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2010

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2010  
(Веб-компоненты сервера)  
(2963286)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-032**](http://go.microsoft.com/fwlink/?linkid=400969)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32-разрядная версия)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32-разрядная версия)  
(2881013)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 с пакетом обновления 1 (SP1) (32-разрядные версии)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(2881013)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32-разрядная версия)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32-разрядная версия)  
(2881013)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 с пакетом обновления 1 (SP1) (32-разрядные версии)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(2881013)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64-разрядная версия)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64-разрядная версия)  
(2881013)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 с пакетом обновления 1 (SP1) (64-разрядные версии)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(2881013)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (64-разрядные версии)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (64-разрядные версии)  
(2881013)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 с пакетом обновления 1 (SP1) (64-разрядные версии)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(2881013)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2013

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
(Веб-компоненты сервера)  
(2963288)  
(существенный)

</td>
</tr>
</table>
 
**Примечание для MS14-036**

Это бюллетень относится к нескольким категориям ПО. В других таблицах этого раздела перечислено дополнительное уязвимое программное обеспечение.

 

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span id="sectionToggle3"></span>
Доступно несколько ресурсов, чтобы помочь администраторам развернуть обновления для системы безопасности.

Анализатор безопасности Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений для системы безопасности и типичных ошибок в конфигурации системы безопасности.

Службы Windows Server Update Services (WSUS), Systems Management Server (SMS) и System Center Configuration Manager помогают администраторам распространять обновления для системы безопасности.

Компоненты средства оценки совместимости с обновлениями, включенные в набор средств для обеспечения совместимости приложений, облегчают тестирование и проверку совместимости обновлений Windows с установленными приложениями.

Информацию об этих и других доступных инструментах см. в статье [Инструменты обеспечения безопасности](http://technet.microsoft.com/security/cc297183). 

Благодарности
-------------

<span id="sectionToggle4"></span>
Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:

**MS14-030**

-   Андрея Свободу (Andrew Swoboda) и Тайлера Регули (Tyler Reguly) из [Tripwire](http://www.tripwire.com/) за сообщение об уязвимости MAC RDP (CVE-2014-0296)

     

**MS14-033**

-   Кристиана Куленкампфа (Christian Kulenkampff) за сообщение об уязвимости URI объектов MSXML (CVE-2014-1816)

     

**MS14-034**

-   компанию s3tm3m, работающую совместно с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости внедренных шрифтов (CVE-2014-2778)

     

**MS14-035**

-   Саймона Цукербрауна (Simon Zuckerbraun), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0282)
-   Жэньгуан Юаня (Renguang Yuan) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0282)
-   АбдулАзиза Харири (AbdulAziz Hariri), Мэтта Молинио (Matt Molinyawe) и Джазиеля Спелмана (Jasiel Spelman), сотрудничающих с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1762)
-   Компанию [VUPEN](http://www.vupen.com/), сотрудничающую с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/) за сообщение об уязвимости Internet Explorer, приводящей к несанкционированному получению прав (CVE-2014-1764)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1766)
-   Андреаса Шмидта (Andreas Schmidt), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1766)
-   Пользователя IronRock, сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1766)
-   Анонимного исследователя, сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1766)
-   Атте Кеттунен (Atte Kettunen) из компании [OUSPG](https://www.ee.oulu.fi/research/ouspg/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1769)
-   Лю Луна (Liu Long) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1769)
-   Юйцзе Вэнь (Yujie Wen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1769)
-   АбдулАзиза Харири (AbdulAziz Hariri), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1769)
-   [Чен Жанга (Chen Zhang) (demi6od)](http://weibo.com/demi6od) из [отдела безопасности NSFOCUS](http://www.nsfocus.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1769)
-   Питера 'corelanc0d3r' Ван Экуте (Peter 'corelanc0d3r' Van Eeckhoutte) из компании [Corelan](http://www.corelangcv.com/), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1770)
-   Команду Prosecco из INRIA (Institut National de Recherche en Informatique et en Automatique) за сообщение об уязвимости, связанной с повторным согласованием сертификатов серверов TLS (CVE-2014-1771)
-   Пользователя [Omair](http://krash.in/), сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1772)
-   Лю Луна (Liu Long) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1772)
-   Джека Тенга (Jack Tang) из компании [Trend Micro](http://www.trendmicro.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1772)
-   Лабораторию [Venustech Active-Defense Laboratory](http://www.venustech.com.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1772)
-   Джона Вилламила (John Villamil) и Шона Ларссона (Sean Larsson) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1773)
-   [Чен Жанга (Chen Zhang) (demi6od)](http://weibo.com/demi6od) из [отдела безопасности NSFOCUS](http://www.nsfocus.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1773)
-   Амола Найка (AMol NAik), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1774)
-   Стивена Фьюэра (Stephen Fewer) из [Harmony Security](http://www.harmonysecurity.com/), работающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1775)
-   Хой Гао (Hui Gao) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1775)
-   Арезо Хоссеинзада-Амирхизи (Arezou Hosseinzad-Amirkhizi) из отдела исследования уязвимостей, компании TELUS Security Labs, за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1775)
-   Джеймса Форшо (James Forshaw) из компании [Context Information Security](http://www.contextis.com/) за сообщение об уязвимости Internet Explorer, приводящей к раскрытию информации (CVE-2014-1777)
-   Джеймса Форшо (James Forshaw) из компании [Context Information Security](http://www.contextis.com/) за сообщение об уязвимости Internet Explorer, приводящей к несанкционированному повышению привилегий (CVE-2014-1778)
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1779)
-   [Соруша Далили (Soroush Dalili)](http://www.secproject.com/), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1780)
-   [Отдел безопасности NSFOCUS](http://www.nsfocus.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1781)
-   Пользователя lokihardt@ASRT, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1782)
-   Лю Луна (Liu Long) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1782)
-   Чжибинь Ху (Zhibin Hu) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1782)
-   Юки Чен (Yuki Chen) из компании [Trend Micro](http://www.trendmicro.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1782)
-   ZhaoWei компании [knownsec](http://www.knownsec.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1782)
-   пользователя 35c27308b34d55904da10770e5303503, сотрудничающего в рамках программы [iSIGHT Partners GVP](https://gvp.isightpartners.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1782)
-   Пользователя IronRock, сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1782)
-   Юйцзе Вэнь (Yujie Wen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1783)
-   Юйцзе Вэнь (Yujie Wen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1784)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1784)
-   Чжибинь Ху (Zhibin Hu) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1784)
-   Пользователя SkyLined, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1785)
-   Юйцзе Вэнь (Yujie Wen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1785)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1785)
-   Юйцзе Вэнь (Yujie Wen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1786)
-   Юйцзе Вэнь (Yujie Wen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1788)
-   Юйцзе Вэнь (Yujie Wen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1789)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1789)
-   Юйцзе Вэнь (Yujie Wen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1790)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1791)
-   Питера 'corelanc0d3r' Ван Экуте (Peter 'corelanc0d3r' Van Eeckhoutte) из компании [Corelan](http://www.corelangcv.com/), сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1792)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1792)
-   Юйцзе Вэнь (Yujie Wen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1794)
-   Чена Ксайобо (Xiaobo Chen) из компании [FireEye](http://www.fireeye.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1795)
-   Хой Гао (Hui Gao) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1796)
-   Гарета Хейеса (Gareth Heyes), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1797)
-   Чжибинь Ху (Zhibin Hu) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1799)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1799)
-   Пользователя 0016EECD9D7159A949DAD3BC17E0A939, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1799)
-   Пользователя Sweetchip, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1799)
-   Пользователя SkyLined, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1800)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1802)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1803)
-   Ройса Лу (Royce Lu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1804)
-   Юки Чен (Yuki Chen) из компании [Trend Micro](http://www.trendmicro.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1804)
-   Пользователя lokihardt@ASRT, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1805)
-   Лю Луна (Liu Long) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2753)
-   Лю Луна (Liu Long) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2754)
-   Ксинь Оуянг (Xin Ouyang) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2755)
-   Чжибинь Ху (Zhibin Hu) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2755)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2756)
-   Пользователя 0016EECD9D7159A949DAD3BC17E0A939, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2756)
-   Саймона Цукербрауна (Simon Zuckerbraun), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2757)
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2758)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2759)
-   Пользователя Sabre и компании [VeriSign iDefense Labs](http://labs.idefense.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2759)
-   Чжибинь Ху (Zhibin Hu) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2760)
-   Юйцзе Вэнь (Yujie Wen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2761)
-   Пользователя 0016EECD9D7159A949DAD3BC17E0A939, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2761)
-   Юйцзе Вэнь (Yujie Wen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2763)
-   Юйцзе Вэнь (Yujie Wen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2764)
-   [Чен Жанга (Chen Zhang) (demi6od)](http://weibo.com/demi6od) из [отдела безопасности NSFOCUS](http://www.nsfocus.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2764)
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2764)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2765)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2766)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2767)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2768)
-   Юки Чен (Yuki Chen) из компании [Trend Micro](http://www.trendmicro.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2768)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2769)
-   Лабораторию [Venustech Active-Defense Laboratory](http://www.venustech.com.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2769)
-   Ксинь Оуянг (Xin Ouyang) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2770)
-   Ройса Лу (Royce Lu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2771)
-   Стивена Фьюэра (Stephen Fewer) из [Harmony Security](http://www.harmonysecurity.com/), работающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2772)
-   [Keen Team](http://www.k33nteam.org/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2773)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2773)
-   АбдулАзиза Харири (AbdulAziz Hariri), Мэтта Молинио (Matt Molinyawe) и Джазиеля Спелмана (Jasiel Spelman), сотрудничающих с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2775)
-   АбдулАзиза Харири (AbdulAziz Hariri), Мэтта Молинио (Matt Molinyawe) и Джазиеля Спелмана (Jasiel Spelman), сотрудничающих с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2776)
-   Компанию [VUPEN](http://www.vupen.com/), сотрудничающую с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/) за сообщение об уязвимости Internet Explorer, приводящей к несанкционированному получению прав (CVE-2014-2777)
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2782)
-   Нориаки Ивасаки (Noriaki Iwasaki) из [Cyber Defense Institute, Inc.](http://www.cyberdefense.jp/) за совместную работу над изменениями для обеспечения многоуровневой защиты, включенными в бюллетень

     

**MS14-036**

-   Скота Белла (Scott Bell) из компании [Security-Assessment.com](http://www.security-assessment.com/) за сообщение об уязвимости в Unicode Script Processor (CVE-2014-1817)
-   Мэтью Юрчика (Mateusz Jurczyk), Ивана Фратрича (Ivan Fratric) и Бена Хокса (Ben Hawkes) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости GDI+, связанной с анализом изображений (CVE-2014-1818)

Прочие сведения
---------------

<span id="sectionToggle5"></span>
### Средство удаления вредоносных программ для системы Microsoft Windows

Для выпуска бюллетеня, публикуемого каждый второй вторник месяца корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки. Для внеплановых выпусков бюллетеней по безопасности обновленные версии средства удаления вредоносных программ для системы Microsoft Windows недоступны.

### Обновления, не относящиеся к безопасности и распространяемые через Центр обновления Майкрософт, Центр обновления Windows и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-сайте Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт](https://support.microsoft.com/kb/894199). Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
-   [Обновления за предыдущие месяцы для служб Windows Server Update Services](http://technet.microsoft.com/wsus/bb456965). Отображаются все новые, обновленные и повторно выпущенные обновления для продуктов Майкрософт отличных от Microsoft Windows.

### Программа Microsoft Active Protections Program (MAPP)

Чтобы повысить уровень защиты пользователей, корпорация Майкрософт предоставляет сведения об уязвимостях крупным поставщикам программного обеспечения безопасности перед ежемесячным выпуском обновлений. Эта информация необходима им для усовершенствования программного обеспечения и оборудования для защиты пользователей (антивирусных программ, сетевых систем обнаружения вторжений, а также индивидуальных систем предотвращения вторжений). Сведения о средствах защиты, предоставляемых поставщиками программного обеспечения безопасности, доступны на соответствующих веб-сайтах партнеров, перечисленных в списке партнеров [MAPP](http://go.microsoft.com/fwlink/?linkid=215201).

### Стратегии безопасности и сообщество

**Стратегии управления обновлениями**

В статье [Рекомендации по безопасности для управления обновлениями](http://go.microsoft.com/fwlink/?linkid=21168) содержатся дополнительные сведения о рекомендациях Майкрософт по установке обновлений для системы безопасности.

**Другие обновления для системы безопасности**

Другие обновления безопасности можно загрузить из следующих источников:

-   Обновления для системы безопасности доступны в [Центре загрузки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".
-   Обновления для индивидуальных пользователей доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747).
-   Обновления безопасности, предлагаемые в этом месяце в Центре обновления Windows, можно загрузить с веб-сайта Центра загрузки Майкрософт в виде файлов ISO-образа компакт-диска с выпусками обновлений безопасности. Дополнительные сведения см. в [статье 913086 базы знаний Майкрософт](https://support.microsoft.com/kb/913086).

**Сообщество ИТ-специалистов, занимающихся вопросами безопасности**

На веб-сайте [сообщества ИТ-специалистов, занимающихся вопросами безопасности](http://go.microsoft.com/fwlink/?linkid=21164), можно найти сведения о способах улучшения системы безопасности и оптимизации ИТ-инфраструктуры предприятия, а также обсудить вопросы безопасности с другими ИТ-специалистами.

### Поддержка

Подверженное уязвимости программное обеспечение, перечисленное в этом бюллетене, проверено на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).

Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617)

Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)

Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

### Редакции

-   Версия 1.0 (10 июня 2014 г.): Обзор бюллетеней опубликован.
-   Версия 1.1 (17 июня 2014 г.): для MS14-035, в Индекс использования уязвимостей добавлена оценка использования уязвимости CVE-2014-2782. Это изменение носит исключительно информационный характер.

*Время создания страницы: 2014-09-18 16:14Z-07:00.*
