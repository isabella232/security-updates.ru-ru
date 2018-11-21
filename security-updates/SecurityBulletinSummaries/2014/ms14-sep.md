---
TOCTitle: 'MS14-SEP'
Title: Обзор бюллетеней по безопасности Microsoft за сентябрь 2014 года
ms:assetid: 'ms14-sep'
ms:contentKeyID: 62841271
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms14-sep(v=Security.10)'
---

Обзор бюллетеней по безопасности Microsoft за сентябрь 2014 года
================================================================

Дата публикации: 9 сентября 2014 г.

**Версия:** 1.0

В этом обзоре описаны бюллетени по безопасности, выпущенные в сентябре 2014 года.

После выпуска бюллетеней по безопасности за сентябрь 2014 года этот обзор заменит предварительное уведомление, выпущенное 4 сентября 2014 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [Службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

10 сентября 2014 года в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Ежемесячную веб-трансляцию и ссылки на дополнительные веб-трансляции бюллетеня по безопасности см. в статье [Веб-трансляция бюллетеня по безопасности (Майкрософт)](http://technet.microsoft.com/security/dn756352).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (2977629)<br />
<br />
</strong>Это обновление для системы безопасности устраняет одну опубликованную и 36 обнаруженных пользователями уязвимостей в Internet Explorer. Наиболее серьезная из этих уязвимостей делает возможным удаленное выполнение кода, если пользователь просматривает особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507670">MS14-053</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в .NET Framework делают возможной атаку типа &quot;отказ в обслуживании&quot; (2990931)</strong><br />
<br />
Данное обновление для системы безопасности устраняет обнаруженную пользователями уязвимость Microsoft .NET Framework. Эта уязвимость делает возможным отказ в обслуживании, если злоумышленник отправляет уязвимому веб-сайту с поддержкой .NET небольшое количество специально созданных запросов. По умолчанию компонент ASP.NET не устанавливается вместе с платформой Microsoft .NET Framework в поддерживаемых выпусках Microsoft Windows. Пользователи уязвимы только после установки ASP.NET вручную и включения этого компонента, регистрируя в IIS.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507672">MS14-054</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в планировщике заданий Windows делает возможным несанкционированное повышение привилегий (2988948)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным несанкционированное повышение привилегий, если злоумышленник вошел в систему и запустил специально созданное приложение. Чтобы воспользоваться этой уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему. Данной уязвимостью не могут воспользоваться удаленные или анонимные пользователи.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507669">MS14-055</a></td>
<td style="border:1px solid black;"><strong>Уязвимости Microsoft Lync Server делают возможным отказ в обслуживании (DoS) (2990928)</strong><br />
<br />
Это обновление для системы безопасности устраняет три обнаруженных пользователями уязвимости в Microsoft Lync Server. Наиболее опасная из этих уязвимостей делает возможной атаку типа &quot;отказ в обслуживании&quot;, если злоумышленник отправил специально созданный запрос на Lync Server.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Перезагрузка не требуется</td>
<td style="border:1px solid black;">Microsoft Lync Server</td>
</tr>
</tbody>
</table>
  
 
  
Индекс использования уязвимостей  
--------------------------------
  
<span id="sectionToggle1"></span>
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости сгруппированы по идентификаторам бюллетеней и затем по кодам CVE. Включены только уязвимости, которым в бюллетенях присвоен уровень серьезности "критический" или "существенный".
  
Как пользоваться этой таблицей?
  
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к раскрытию информации о ресурсах</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-7331">CVE-2013-7331</a></td>
<td style="border:1px solid black;">0- использование обнаружено</td>
<td style="border:1px solid black;">0- использование обнаружено</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках. Корпорации Майкрософт известно об ограниченных активных атаках с целью использования этой уязвимости.<br />
Это уязвимость, делающая возможным раскрытие информации: злоумышленник может сделать вывод о наличии файлов на локальных дисках.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2799">CVE-2014-2799</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4059">CVE-2014-4059</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4065">CVE-2014-4065</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4079">CVE-2014-4079</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4080">CVE-2014-4080</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4081">CVE-2014-4081</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4082">CVE-2014-4082</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4083">CVE-2014-4083</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4084">CVE-2014-4084</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4085">CVE-2014-4085</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4086">CVE-2014-4086</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4087">CVE-2014-4087</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4088">CVE-2014-4088</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4089">CVE-2014-4089</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4090">CVE-2014-4090</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4091">CVE-2014-4091</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4092">CVE-2014-4092</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4093">CVE-2014-4093</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4094">CVE-2014-4094</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4095">CVE-2014-4095</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4096">CVE-2014-4096</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4097">CVE-2014-4097</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4098">CVE-2014-4098</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4099">CVE-2014-4099</a></td>
<td style="border:1px solid black;">3- использование маловероятно</td>
<td style="border:1px solid black;">3- использование маловероятно</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">Это Уязвимость, приводящая к повреждению памяти, делает возможной атаку типа &quot;отказ в обслуживании&quot;.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4100">CVE-2014-4100</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4101">CVE-2014-4101</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4102">CVE-2014-4102</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4103">CVE-2014-4103</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4104">CVE-2014-4104</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4105">CVE-2014-4105</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4106">CVE-2014-4106</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4107">CVE-2014-4107</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4108">CVE-2014-4108</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4109">CVE-2014-4109</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4110">CVE-2014-4110</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=509961">MS14-052</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4111">CVE-2014-4111</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507670">MS14-053</a></td>
<td style="border:1px solid black;">Уязвимость .NET Framework, делающая возможной атаку типа &quot;отказ в обслуживании&quot;</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4072">CVE-2014-4072</a></td>
<td style="border:1px solid black;">3- использование маловероятно</td>
<td style="border:1px solid black;">3- использование маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507672">MS14-054</a></td>
<td style="border:1px solid black;">Уязвимость планировщика заданий</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4074">CVE-2014-4074</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507669">MS14-055</a></td>
<td style="border:1px solid black;">Уязвимость в Lync, делающая возможной атаку типа &quot;отказ в обслуживании&quot;</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4068">CVE-2014-4068</a></td>
<td style="border:1px solid black;">3- использование маловероятно</td>
<td style="border:1px solid black;">3- использование маловероятно</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507669">MS14-055</a></td>
<td style="border:1px solid black;">Уязвимость Lync XSS, приводящая к раскрытию информации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4070">CVE-2014-4070</a></td>
<td style="border:1px solid black;">3- использование маловероятно</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507669">MS14-055</a></td>
<td style="border:1px solid black;">Уязвимость в Lync, делающая возможной атаку типа &quot;отказ в обслуживании&quot;</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4071">CVE-2014-4071</a></td>
<td style="border:1px solid black;">3- использование маловероятно</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.</td>
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
  
**Компоненты операционных систем Windows**

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
Internet Explorer 6  
(2977629)  
(средний)  
Internet Explorer 7  
(2977629)  
(средний)  
Internet Explorer 8  
(2977629)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)  
(2972207)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2972214)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2973115)  
(существенный)  
Microsoft .NET Framework 4  
(2972215)  
(существенный)

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
(2977629)  
(средний)  
Internet Explorer 7  
(2977629)  
(средний)  
Internet Explorer 8  
(2977629)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2972214)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2973115)  
(существенный)  
Microsoft .NET Framework 4  
(2972215)  
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
Internet Explorer 6  
(2977629)  
(средний)  
Internet Explorer 7  
(2977629)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2972214)  
(существенный)  
Microsoft .NET Framework 4  
(2972215)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
(2977629)  
(критический)  
Internet Explorer 8  
(2977629)  
(критический)  
Internet Explorer 9  
(2977629)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2974268)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2974269)  
(существенный)  
Microsoft .NET Framework 4  
(2972215)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
(2977629)  
(критический)  
Internet Explorer 8  
(2977629)  
(критический)  
Internet Explorer 9  
(2977629)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2974268)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2974269)  
(существенный)  
Microsoft .NET Framework 4  
(2972215)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
(2977629)  
(средний)  
Internet Explorer 8  
(2977629)  
(средний)  
Internet Explorer 9  
(2977629)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2974268)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2974269)  
(существенный)  
Microsoft .NET Framework 4  
(2972215)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
(2977629)  
(средний)  
Internet Explorer 8  
(2977629)  
(средний)  
Internet Explorer 9  
(2977629)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2974268)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2974269)  
(существенный)  
Microsoft .NET Framework 4  
(2972215)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
(2977629)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2974268)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2974269)  
(существенный)  
Microsoft .NET Framework 4  
(2972215)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
<td style="border:1px solid black;">
**Нет**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2977629)  
(критический)  
Internet Explorer 9  
(2977629)  
(критический)  
Internet Explorer 10  
(2977629)  
(критический)  
Internet Explorer 11  
(2977629)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(существенный)  
Microsoft .NET Framework 4  
(2972215)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2977629)  
(критический)  
Internet Explorer 9  
(2977629)  
(критический)  
Internet Explorer 10  
(2977629)  
(критический)  
Internet Explorer 11  
(2977629)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(существенный)  
Microsoft .NET Framework 4  
(2972215)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**Нет**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2977629)  
(средний)  
Internet Explorer 9  
(2977629)  
(средний)  
Internet Explorer 10  
(2977629)  
(средний)  
Internet Explorer 11  
(2977629)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(существенный)  
Microsoft .NET Framework 4  
(2972215)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
(2977629)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(существенный)  
Microsoft .NET Framework 4  
(2972215)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 8 и Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
(2977629)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972212)  
(существенный)  
Microsoft .NET Framework 3.5  
(2973113)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2988948)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2977629)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972212)  
(существенный)  
Microsoft .NET Framework 3.5  
(2973113)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2988948)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972213)  
(существенный)  
Microsoft .NET Framework 3.5  
(2973114)  
(существенный)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(2988948)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972213)  
(существенный)  
Microsoft .NET Framework 3.5  
(2973114)  
(существенный)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(2988948)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2012 и Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
(2977629)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972212)  
(существенный)  
Microsoft .NET Framework 3.5  
(2973113)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2988948)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2972213)  
(существенный)  
Microsoft .NET Framework 3.5  
(2973114)  
(существенный)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2988948)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows RT и Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2977629)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows RT  
(2988948)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2977629)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2988948)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Вариант установки ядра сервера**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-052**](http://go.microsoft.com/fwlink/?linkid=509961)

</td>
<td style="border:1px solid black;">
[**MS14-053**](http://go.microsoft.com/fwlink/?linkid=507670)

</td>
<td style="border:1px solid black;">
[**MS14-054**](http://go.microsoft.com/fwlink/?linkid=507672)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)

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
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2972211)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2973112)  
(существенный)  
Microsoft .NET Framework 4  
(2972215)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972216)  
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
Microsoft .NET Framework 3.5  
(2972212)  
(существенный)  
Microsoft .NET Framework 3.5  
(2973113)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2977766)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(2988948)  
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
Microsoft .NET Framework 3.5  
(2972213)  
(существенный)  
Microsoft .NET Framework 3.5  
(2973114)  
(существенный)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2977765)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (установка основных серверных компонентов)  
(2988948)  
(существенный)

</td>
</tr>
</table>
 
 

**Платформы и программное обеспечение Microsoft Communication**

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
**Microsoft Lync Server**

</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-055**](http://go.microsoft.com/fwlink/?linkid=507669)

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
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2010

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2010  
(Сервер)  
(2982385)  
(Уровень опасности не определен)<sup>[1]</sup>
Microsoft Lync Server 2010  
(Служба групп ответов)  
(2982388)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
(Сервер)  
(2986072)  
(существенный)  
Microsoft Lync Server 2013  
(Служба групп ответов)  
(2982389)  
(существенный)  
Microsoft Lync Server 2013  
(Основные компоненты)  
(2992965)  
(существенный)  
Microsoft Lync Server 2013  
(Веб-компоненты сервера)  
(2982390)  
(существенный)

</td>
</tr>
</table>
 
**Примечание для MS14-055**

<sup>[1]</sup>К данному обновлению не применяются уровни серьезности в отношении указанного программного обеспечения; тем не менее, в качестве дополнительной меры защиты корпорация Microsoft рекомендует пользователям данного программного обеспечения установить это обновление безопасности для защиты от любых возможных новых способов атак, которые могут быть идентифицированы в будущем.

 

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

**MS14-052**

-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2799)
-   [Лабораторию Adlab компании Venustech](http://www.venustech.com.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2799)
-   [Adlab компании Venustech](http://www.venustech.com.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4059)
-   АбдулАзиза Харири (AbdulAziz Hariri), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4065)
-   Пользователя 56e7aec02099b976120abfda31254b05, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4079)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4080)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4081)
-   [Adlab компании Venustech](http://www.venustech.com.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4081)
-   Юки Чен (Yuki Chen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4082)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4082)
-   [Adlab компании Venustech](http://www.venustech.com.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4083)
-   [Adlab компании Venustech](http://www.venustech.com.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4084)
-   [Группу KnownSec](http://www.knownsec.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4084)
-   Пользователя Sky, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4085)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4086)
-   Лю Луна (Liu Long) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4086)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4087)
-   Чжибинь Ху (Zhibin Hu) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4087)
-   Хой Гао (Hui Gao) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4088)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4089)
-   Пользователя Garage4Hackers, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4090)
-   Юки Чен (Yuki Chen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4091)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4092)
-   Пользователя A3F2160DCA1BDE70DA1D99ED267D5DC1EC336192, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4092)
-   Джейсона Кратцера (Jason Kratzer), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4092)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4093)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4094)
-   Юки Чэня (Yuki Chen) из компании [Trend Micro](http://www.trendmicro.com/), работающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4095)
-   Пользователя cloudfuzzer, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4096)
-   АбдулАзиза Харири (AbdulAziz Hariri), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4096)
-   Юки Чэня (Yuki Chen) из компании [Trend Micro](http://www.trendmicro.com/), работающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4096)
-   Юки Чэня (Yuki Chen) из компании [Trend Micro](http://www.trendmicro.com/), работающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4097)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4097)
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4098)
-   Пользователя SkyLined, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4099)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4100)
-   Ксинь Оуянг (Xin Ouyang) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4101)
-   Хосе А. Васкеса (José A. Vázquez) из Yenteasy, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4101)
-   Лю Луна (Liu Long) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4102)
-   АбдулАзиза Харири (AbdulAziz Hariri), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4103)
-   Лю Луна (Liu Long) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4104)
-   Юки Чэня (Yuki Chen) из компании [Trend Micro](http://www.trendmicro.com/), работающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4105)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4106)
-   АбдулАзиза Харири (AbdulAziz Hariri), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4107)
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4108)
-   Джона Вилламила (John Villamil, @day6reak) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4109)
-   [Группу KnownSec](http://www.knownsec.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4110)
-   Юйцзе Вэнь (Yujie Wen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4111)
-   Масато Кинугаву (Masato Kinugawa) и [отдел безопасности Google](http://www.google.com/) за совместную работу над изменениями для обеспечения многоуровневой защиты, которые включены в данный бюллетень

**MS14-053**

-   Александра Клинка (Alexander Klink) из компании [Cynops GmbH](http://www.cynops.de/) за сообщение об уязвимости .NET Framework, приводящей к отказу в обслуживании (CVE-2014-4072)

**MS14-054**

-   Джеймса Форшо (James Forshaw) из компании [Context Information Security](http://www.contextis.com/) за сообщение об уязвимости планировщика заданий (CVE-2014-4074)

**MS14-055**

-   Питера Шраффла (Peter Schraffl) из компании [Telecommunication Software GmbH](http://www.telecomsoftware.com/) за сообщение об уязвимости Lync, приводящей к отказу от обслуживания (CVE-2014-4068)
-   Ноама Ратхауса (Noam Rathaus), сотрудничающего с группой [SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) компании Beyond Security, за сообщение об уязвимости Lync XSS, приводящей к отказу от обслуживания (CVE-2014-4070)

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

-   Версия 1.0 (9 сентября 2014 г.): Обзор бюллетеней опубликован.

*Время создания страницы: 2014-09-18 16:20Z-07:00.*
