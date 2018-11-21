---
TOCTitle: 'MS14-APR'
Title: Обзор бюллетеней по безопасности Microsoft за апрель 2014 года
ms:assetid: 'ms14-apr'
ms:contentKeyID: 62169781
ms:mtpsurl: 'https://technet.microsoft.com/ru-ru/library/ms14-apr(v=Security.10)'
---

Обзор бюллетеней по безопасности Microsoft за апрель 2014 года
==============================================================

Дата публикации: 8 апреля 2014 г.

**Версия:** 1.0

В этом обзоре описаны бюллетени по безопасности, выпущенные в апреле 2014 года.

После выпуска бюллетеней за апрель 2014 года этот обзор заменит предварительное уведомление, выпущенное 3 апреля 2014 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

9 апреля 2014 года в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в апрельской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032572978&culture=en-us).

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
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Идентификатор бюллетеня</strong></td>
<td style="border:1px solid black;"><strong>Название бюллетеня и аннотация</strong></td>
<td style="border:1px solid black;"><strong>Максимальный уровень серьезности и воздействие уязвимости</strong></td>
<td style="border:1px solid black;"><strong>Необходимость перезагрузки</strong></td>
<td style="border:1px solid black;"><strong>Подвержены уязвимости</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393531">MS14-017</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Word и Office Web Apps делают возможным удаленное выполнение кода (2949660)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну опубликованную и две обнаруженные пользователями уязвимости в Microsoft Office. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если открыть или предварительно просмотреть специально созданный файл в уязвимой версии Microsoft Office. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office,<br />
службы Microsoft Office,<br />
Microsoft Office Web Apps</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393743">MS14-018</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (2950467)<br />
<br />
</strong>Это обновление для системы безопасности устраняет 6 обнаруженных пользователями уязвимостей в Internet Explorer. Данные уязвимости делают возможным удаленное выполнение кода при открытии специально созданной веб-страницы в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392069">MS14-019</a></td>
<td style="border:1px solid black;"><strong>Уязвимость компонента обработки файлов в Windows делает возможным удаленное выполнение кода (2922229)</strong><br />
<br />
Это обновление для системы безопасности устраняет опубликованную уязвимость в Microsoft Windows. Данная уязвимость делает возможным удаленное выполнение кода, если пользователи выполняют специально созданные BAT- и CMD-файлы из доверенного или частично доверенного сетевого каталога. Злоумышленник не может заставить пользователей посетить такой сетевой каталог или выполнить специально созданные файлы. Вместо этого злоумышленник необходимо убедить пользователей выполнить такое действие. Например, злоумышленник может обманом склонить пользователей перейти по ссылке к местоположению специально созданных файлов злоумышленника, а затем убедить их выполнять данные файлы.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393603">MS14-020</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в приложении Microsoft Publisher делает возможным удаленное выполнение кода (2950145)<br />
</strong><br />
Это обновление для системы безопасности устраняет уязвимость в пакете Microsoft Office, о которой сообщалось в частном порядке. Эта уязвимость делает возможным удаленное выполнение кода, если пользователь откроет специально созданный файл в уязвимой версии Microsoft Publisher. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393531">MS14-017</a></td>
<td style="border:1px solid black;">Уязвимость конвертера форматов файлов Microsoft Office</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1757">CVE-2014-1757</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393531">MS14-017</a></td>
<td style="border:1px solid black;">Уязвимость в Microsoft Word, связанная с переполнением стека</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1758">CVE-2014-1758</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393531">MS14-017</a></td>
<td style="border:1px solid black;">Уязвимость Word при использовании RTF-файлов, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1761">CVE-2014-1761</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Данная уязвимость была открыто опубликована.<br />
<br />
Корпорации Майкрософт известно об ограниченных направленных атаках с целью использования этой уязвимости.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393743">MS14-018</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0325">CVE-2014-0325</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393743">MS14-018</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1751">CVE-2014-1751</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393743">MS14-018</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1752">CVE-2014-1752</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393743">MS14-018</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1753">CVE-2014-1753</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393743">MS14-018</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1755">CVE-2014-1755</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393743">MS14-018</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1760">CVE-2014-1760</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392069">MS14-019</a></td>
<td style="border:1px solid black;">Уязвимость обработки файлов в Windows</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0315">CVE-2014-0315</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Данная уязвимость была открыто опубликована.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=393603">MS14-020</a></td>
<td style="border:1px solid black;">Уязвимость разыменования произвольного указателя</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1759">CVE-2014-1759</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
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
<td style="border:1px solid black;" colspan="3">
**Windows XP**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
Windows XP с пакетом обновления 3 (SP3)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2936068)  
(критический)  
Internet Explorer 7   
(2936068)  
(критический)  
Internet Explorer 8   
(2936068)  
(критический)

</td>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2936068)  
(критический)  
Internet Explorer 7   
(2936068)  
(критический)  
Internet Explorer 8   
(2936068)  
(критический)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2936068)  
(средний)  
Internet Explorer 7  
(2936068)  
(средний)  
Internet Explorer 8  
(2936068)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2936068)  
(средний)  
Internet Explorer 7  
(2936068)  
(средний)  
Internet Explorer 8  
(2936068)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2936068)  
(средний)  
Internet Explorer 7  
(2936068)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
Windows Vista с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2936068)  
(критический)  
Internet Explorer 8  
(2936068)  
(критический)  
Internet Explorer 9   
(2936068)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2936068)  
(критический)  
Internet Explorer 8  
(2936068)  
(критический)  
Internet Explorer 9   
(2936068)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2936068)  
(средний)  
Internet Explorer 8  
(2936068)  
(средний)  
Internet Explorer 9   
(2936068)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2936068)  
(средний)  
Internet Explorer 8  
(2936068)  
(средний)  
Internet Explorer 9   
(2936068)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2936068)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2936068)  
(критический)  
Internet Explorer 9   
(2936068)  
(критический)  
Internet Explorer 11   
(2936068)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2936068)  
(критический)  
Internet Explorer 9   
(2936068)  
(критический)  
Internet Explorer 11   
(2936068)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2936068)  
(средний)  
Internet Explorer 9   
(2936068)  
(средний)  
Internet Explorer 11   
(2936068)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2936068)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows 8 и Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
Windows 8 для 32-разрядных систем

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2936068)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2936068)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2012 и Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2936068)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows RT и Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
Windows RT

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows RT  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2936068)  
(критический)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2922229)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Вариант установки ядра сервера**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-018**](http://go.microsoft.com/fwlink/?linkid=393743)

</td>
<td style="border:1px solid black;">
[**MS14-019**](http://go.microsoft.com/fwlink/?linkid=392069)

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
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2922229)  
(существенный)

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
(2922229)  
(существенный)

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
(2922229)  
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
Windows Server 2012 (установка основных серверных компонентов)  
(2922229)  
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
(2922229)  
(существенный)

</td>
</tr>
</table>
 
 

**Пакеты приложений и программные продукты Microsoft Office**

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

</td>
<td style="border:1px solid black;">
[**MS14-020**](http://go.microsoft.com/fwlink/?linkid=393603)

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
Microsoft Office 2003 с пакетом обновления 3 (SP3)

</td>
<td style="border:1px solid black;">
Microsoft Word 2003 с пакетом обновления 3 (SP3)  
(2878303)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft Office Publisher 2003 с пакетом обновления 3 (SP3)  
(2878299)  
(существенный)

</td>
</tr>
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
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

</td>
<td style="border:1px solid black;">
[**MS14-020**](http://go.microsoft.com/fwlink/?linkid=393603)

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
Microsoft Office 2007 с пакетом обновления 3 (SP3)

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 с пакетом обновления 3 (SP3)  
(2878237)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft Publisher 2007 с пакетом обновления 3 (SP3)  
(2817565)  
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
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

</td>
<td style="border:1px solid black;">
[**MS14-020**](http://go.microsoft.com/fwlink/?linkid=393603)

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
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)

</td>
<td style="border:1px solid black;">
Microsoft Word 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(2863926)  
(критический)  
Microsoft Word 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(2863919)  
(критический)

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
Microsoft Word 2010 с пакетом обновления 2 (SP2) (32-разрядные версии)  
(2863926)  
(критический)  
Microsoft Word 2010 с пакетом обновления 2 (SP2) (32-разрядные версии)  
(2863919)  
(критический)

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
Microsoft Word 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(2863926)  
(критический)  
Microsoft Word 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(2863919)  
(критический)

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
Microsoft Word 2010 с пакетом обновления 2 (SP2) (64-разрядные версии)  
(2863926)  
(критический)  
Microsoft Word 2010 с пакетом обновления 2 (SP2) (64-разрядные версии)  
(2863919)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 и Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

</td>
<td style="border:1px solid black;">
[**MS14-020**](http://go.microsoft.com/fwlink/?linkid=393603)

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
Microsoft Office 2013 (32-разрядные версии)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 (32-разрядные версии)  
(2863910)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 с пакетом обновления 1 (SP1) (32-разрядные версии)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(2863910)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (64-разрядные версии)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 (64-разрядные версии)  
(2863910)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 с пакетом обновления 1 (SP1) (64-разрядные версии)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(2863910)  
(критический)

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
Microsoft Word 2013 RT  
(2863910)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT с пакетом обновления 1 (SP1)  
(2863910)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office для Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

</td>
<td style="border:1px solid black;">
[**MS14-020**](http://go.microsoft.com/fwlink/?linkid=393603)

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
Microsoft Office для Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Office для Mac 2011  
(2939132)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Другое программное обеспечение Microsoft Office**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

</td>
<td style="border:1px solid black;">
[**MS14-020**](http://go.microsoft.com/fwlink/?linkid=393603)

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
Средство просмотра Microsoft Word

</td>
<td style="border:1px solid black;">
Средство просмотра Microsoft Word  
(2878304)  
(критический)

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
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)  
(2878236)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
</table>
 
**Примечания к бюллетеню MS14-017**

Это бюллетень относится к нескольким категориям ПО. В других таблицах этого раздела перечислено дополнительное уязвимое программное обеспечение.

 

**Службы Microsoft Office и Web Apps**

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

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
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2878220)  
(критический)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2878220)  
(критический)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

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
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2863907)  
(критический)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2863907)  
(критический)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 с пакетом обновления 1 (SP1)  
(2878221)  
(критический)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 с пакетом обновления 2 (SP2)  
(2878221)  
(критический)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-017**](http://go.microsoft.com/fwlink/?linkid=393531)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2878219)  
(критический)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 с пакетом обновления 1 (SP1)  
(2878219)  
(критический)

</td>
</tr>
</table>
 
**Примечания к бюллетеню MS14-017**

Это бюллетень относится к нескольким категориям ПО. В других таблицах этого раздела перечислено дополнительное уязвимое программное обеспечение.

 

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span id="sectionToggle3"></span>
Доступно несколько ресурсов, чтобы помочь администраторам развернуть обновления для системы безопасности.

-   Анализатор безопасности Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений для системы безопасности и типичных ошибок в конфигурации системы безопасности.
-   Службы Windows Server Update Services (WSUS), Systems Management Server (SMS) и System Center Configuration Manager помогают администраторам распространять обновления для системы безопасности.
-   Компоненты средства оценки совместимости с обновлениями, включенные в набор средств для обеспечения совместимости приложений, облегчают тестирование и проверку совместимости обновлений Windows с установленными приложениями.

Информацию об этих и других доступных инструментах см. в статье [Инструменты обеспечения безопасности](http://technet.microsoft.com/security/cc297183). 

Благодарности
-------------

<span id="sectionToggle4"></span>
Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:

**MS14-017**

-   Уилла Дормана (Will Dormann) из [CERT/CC](http://www.cert.org/) за сообщение об уязвимости конвертера форматов файлов Microsoft Office (CVE-2014-1757)
-   Юйхун Бао (Yuhong Bao) за сообщение об уязвимости Microsoft Word, связанной с переполнением стека (CVE-2014-1758)
-   Дрю Хинца (Drew Hintz), Шейна Хантли (Shane Huntley) и Мэтти Пеллегрино (Matty Pellegrino) из отдела безопасности [Google](http://www.google.com/) за сообщение об уязвимости Word при использовании RTF-файлов, приводящей к повреждению памяти (CVE-2014-1761)

**MS14-018**

-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0325)
-   Д-р. Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1751)
-   Д-р. Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1752)
-   Юки Чэня (Yuki Chen) из компании [Trend Micro](http://www.trendmicro.com/), работающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1753)
-   Пользователям 096dc2a463051c0ac4b7caaf233f7eff и Амол Найка (Amol Naik), сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1755)
-   Абдула Азиза Харири (Abdul Aziz Hariri), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1760)

**Для MS14-019**

-   Стефана Канзака (Stefan Kanthak) за совместную работу с нами над устранением уязвимости обработки файлов в Windows (CVE-2014-0315)

**Для MS14-020**

-   анонимного исследователя, сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости разыменования произвольного указателя (CVE-2014-1759).

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

-   Версия 1.0 (8 апреля 2014 г.). Обзор бюллетеней опубликован.

 

*Время создания страницы: 2014-06-30 14:26Z-07:00.*
