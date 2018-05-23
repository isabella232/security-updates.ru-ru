---
TOCTitle: 'MS14-OCT'
Title: 'Обзор бюллетеней по безопасности Microsoft за октябрь 2014 г.'
ms:assetid: 'ms14-oct'
ms:contentKeyID: 63172085
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms14-oct(v=Security.10)'
---

Обзор бюллетеней по безопасности Microsoft за октябрь 2014 г.
=============================================================

Дата публикации: 14 октября 2014 г.

**Версия:** 1.0

В этом обзоре описаны бюллетени по безопасности, выпущенные в октябре 2014 года.

После выпуска бюллетеней по безопасности за октябрь 2014 года этот обзор заменит предварительное уведомление, выпущенное 9 октября 2014 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [Службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

15 октября 2014 года в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Ежемесячную веб-трансляцию и ссылки на дополнительные веб-трансляции бюллетеня по безопасности см. в статье [Веб-трансляция бюллетеня по безопасности (Майкрософт)](http://technet.microsoft.com/security/dn756352).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (2987107)</strong><br />
<br />
Это обновление для системы безопасности устраняет 14 обнаруженных пользователями уязвимостей в браузере Internet Explorer. Наиболее серьезная из этих уязвимостей делает возможным удаленное выполнение кода, если пользователь просматривает особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513095">MS14-057</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в .NET Framework делают возможным удаленное выполнение кода (3000414)<br />
<br />
</strong>Это обновление для системы безопасности устраняет три обнаруженных пользователями уязвимости в Microsoft .NET Framework. Наиболее опасная из этих уязвимостей делает возможным удаленное выполнение кода, если злоумышленник отправляет веб-приложению .NET специально созданный URI-запрос с международными символами. В приложениях .NET 4.0 уязвимая функция (iriParsing) по умолчанию отключена. Для использования этой уязвимости в приложении эта функция должна быть включена явным образом. В приложениях .NET 4.5 функция iriParsing по умолчанию включена без возможности отключения.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513104">MS14-058</a></td>
<td style="border:1px solid black;"><strong>Уязвимость работающего в режиме ядра драйвера делают возможным удаленное выполнение кода (3000061)<br />
<br />
</strong>Это обновление для системы безопасности устраняет две обнаруженных пользователями уязвимости в Microsoft Windows. Наиболее серьезная из этих уязвимостей делает возможным удаленное выполнение кода, если злоумышленник убедит пользователя открыть специально созданный документ или посетить ненадежный веб-сайт с внедренными шрифтами TrueType. Однако в любом случае злоумышленник не может заставить пользователей выполнить данные действия. Вместо этого злоумышленнику придется убедить пользователей сделать это, обычно отправляя им электронное письмо или мгновенное сообщение через службу мгновенных сообщений.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507673">MS14-059</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в ASP.NET MVC делает возможным обход функций безопасности (2990942)<br />
<br />
</strong>Это обновление для системы безопасности устраняет уязвимость в ASP.NET MVC, о которой сообщалось в открытых источниках. Данная уязвимость делает возможным обход функций безопасности, если злоумышленник убедит пользователя перейти по специально созданной ссылке или посетить веб-страницу с содержимым, специально созданным для использования этой уязвимости. В случае атаки через Интернет злоумышленник может создать специальный веб-сайт, предназначенный для использования этой уязвимости через веб-браузер, а затем убедить пользователя посетить этот веб-сайт. Кроме того, он может воспользоваться уязвимостью через веб-сайты, которые уже подверглись атаке, и веб-сайты, которые принимают или размещают сведения или рекламу. Веб-сайты могут включать особым образом созданное содержимое, использующее данную уязвимость. Однако в любом случае злоумышленник не может заставить пользователей просмотреть контролируемое злоумышленником содержимое. Вместо этого злоумышленнику придется убедить пользователей совершить какое-либо действие: например, перейти по ссылке на веб-сайт в сообщении электронной почты или программы обмена мгновенными сообщениями или открыть вложение сообщения электронной почты.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Обход функции безопасности</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Средства разработки Microsoft</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513097">MS14-060</a></td>
<td style="border:1px solid black;"><strong>Уязвимость Windows OLE делает возможным удаленное выполнение кода (3000869)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость делает возможным удаленное выполнение кода, если пользователь откроет файл Microsoft Office, содержащий специально созданный объект OLE. Злоумышленник, успешно воспользовавшийся этой уязвимостью, может выполнить произвольный код в контексте текущего пользователя. Если у текущего пользователя есть права администратора, то злоумышленник сможет устанавливать программы, просматривать, изменять, удалять данные или создавать новые учетные записи с полными правами пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513106">MS14-061</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Word и Office Web Apps делает возможным удаленное выполнение кода (3000434)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Office. Данная уязвимость делает возможным удаленное выполнение кода, если злоумышленник убедит пользователя открыть специально созданный файл Microsoft Word. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить такие же права, что и у локального пользователя. Если у текущего пользователя есть права администратора, то злоумышленник сможет устанавливать программы, просматривать, изменять, удалять данные или создавать новые учетные записи с полными правами пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office,<br />
службы Microsoft Office,<br />
Microsoft Office Web Apps</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513107">MS14-062</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в службе очереди сообщений делает возможным несанкционированное повышение привилегий (2993254)<br />
<br />
</strong>Это обновление для системы безопасности устраняет опубликованную уязвимость в Microsoft Windows. Эта уязвимость делает возможным несанкционированное повышение привилегий, если злоумышленник отправляет службе очереди сообщений специально созданный запрос контроля ввода-вывода (IOCTL). Если злоумышленник воспользуется этой уязвимостью, он получит неограниченный доступ к уязвимой системе. По умолчанию компонент очереди сообщений не установлен в уязвимых выпусках операционных систем, это может сделать только пользователь с правами администратора. Этой уязвимости подвержены только те системы, в которых вручную включен компонент службы очереди сообщений.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513102">MS14-063</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в драйвере разделов диска FAT32 делает возможным несанкционированное повышение привилегий (2998579)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. В способе взаимодействия системного драйвера Windows FASTFAT с разделами дисков FAT32 существует уязвимость, делающая возможным несанкционированное получение привилегий. Воспользовавшийся ею злоумышленник может выполнить произвольный код с более высоким уровнем привилегий.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к несанкционированному повышению привилегий</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4123">CVE-2014-4123</a></td>
<td style="border:1px solid black;">0- использование обнаружено</td>
<td style="border:1px solid black;">0- использование обнаружено</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Эта уязвимость делает возможным несанкционированное повышение привилегий путем обхода песочницы IE.<br />
<br />
Корпорации Майкрософт известно об ограниченном количестве атак, направленных на использование данной уязвимости.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к несанкционированному повышению привилегий</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4124">CVE-2014-4124</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Эта уязвимость может приводить к несанкционированному повышению привилегий.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4126">CVE-2014-4126</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4127">CVE-2014-4127</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4128">CVE-2014-4128</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4129">CVE-2014-4129</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4130">CVE-2014-4130</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4132">CVE-2014-4132</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4133">CVE-2014-4133</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4134">CVE-2014-4134</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4137">CVE-2014-4137</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4138">CVE-2014-4138</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, делающая возможным обход функции безопасности ASLR</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4140">CVE-2014-4140</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, связанная с обходом функций безопасности.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4141">CVE-2014-4141</a></td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513095">MS14-057</a></td>
<td style="border:1px solid black;">Уязвимость .NET ClickOnce, приводящая к несанкционированному повышению привилегий</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4073">CVE-2014-4073</a></td>
<td style="border:1px solid black;">2 - использование менее вероятно</td>
<td style="border:1px solid black;">2 - использование менее вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Эта уязвимость может приводить к несанкционированному повышению привилегий.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513095">MS14-057</a></td>
<td style="border:1px solid black;">Уязвимость .NET Framework, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4121">CVE-2014-4121</a></td>
<td style="border:1px solid black;">2 - использование менее вероятно</td>
<td style="border:1px solid black;">2 - использование менее вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513095">MS14-057</a></td>
<td style="border:1px solid black;">Уязвимость ASLR из .NET</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4122">CVE-2014-4122</a></td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, связанная с обходом функций безопасности.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513104">MS14-058</a></td>
<td style="border:1px solid black;">Уязвимость Win32k.sys, приводящая к несанкционированному повышению привилегий</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4113">CVE-2014-4113</a></td>
<td style="border:1px solid black;">0- использование обнаружено</td>
<td style="border:1px solid black;">0- использование обнаружено</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость может приводить к несанкционированному повышению привилегий.<br />
<br />
Корпорации Майкрософт известно об ограниченном количестве атак, направленных на использование данной уязвимости.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513104">MS14-058</a></td>
<td style="border:1px solid black;">Уязвимость анализа шрифтов TrueType, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4148">CVE-2014 -4148</a></td>
<td style="border:1px solid black;">0- использование обнаружено</td>
<td style="border:1px solid black;">0- использование обнаружено</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Корпорации Майкрософт известно об ограниченном количестве атак, направленных на использование данной уязвимости.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=507673">MS14-059</a></td>
<td style="border:1px solid black;">Уязвимость MVC XSS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4075">CVE-2014-4075</a></td>
<td style="border:1px solid black;">3- использование маловероятно</td>
<td style="border:1px solid black;">3- использование маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, связанная с обходом функций безопасности.<br />
<br />
О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513097">MS14-060</a></td>
<td style="border:1px solid black;">Уязвимость Windows OLE, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4114">CVE-2014-4114</a></td>
<td style="border:1px solid black;">0- использование обнаружено</td>
<td style="border:1px solid black;">0- использование обнаружено</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Корпорации Майкрософт известно об ограниченном количестве атак, направленных на использование данной уязвимости.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513106">MS14-061</a></td>
<td style="border:1px solid black;">Уязвимость формата файлов Microsoft Word </td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4117">CVE-2014-4117</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513107">MS14-062</a></td>
<td style="border:1px solid black;">Уязвимость произвольной записи MQAC, делающая возможным несанкционированное повышение привилегий</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4971">CVE-2014-4971</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">1- использование более вероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость может приводить к несанкционированному повышению привилегий.<br />
<br />
О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=513102">MS14-063</a></td>
<td style="border:1px solid black;">Уязвимость драйвера Microsoft Windows для разделов диска, делающая возможным несанкционированное повышение привилегий</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4115">CVE-2014-4115</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">2 - использование менее вероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость может приводить к несанкционированному повышению привилегий.</td>
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
(2987107)  
(средний)  
Internet Explorer 7  
(2987107)  
(средний)  
Internet Explorer 8  
(2987107)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2972105)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2979574)  
(существенный)  
Microsoft .NET Framework 4  
(2972106)  
(критический)  
Microsoft .NET Framework 4  
(2979575)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2993254)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2998579)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2987107)  
(средний)  
Internet Explorer 7  
(2987107)  
(средний)  
Internet Explorer 8  
(2987107)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2972105)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2979574)  
(существенный)  
Microsoft .NET Framework 4  
(2972106)  
(критический)  
Microsoft .NET Framework 4  
(2979575)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2993254)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2998579)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2987107)  
(средний)  
Internet Explorer 7  
(2987107)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2972105)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2979574)  
(существенный)  
Microsoft .NET Framework 4  
(2972106)  
(критический)  
Microsoft .NET Framework 4  
(2979575)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2993254)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2998579)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
(2987107)  
(критический)  
Internet Explorer 8  
(2987107)  
(критический)  
Internet Explorer 9  
(2987107)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2968292)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2972098)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2979568)  
(существенный)  
Microsoft .NET Framework 4  
(2972106)  
(критический)  
Microsoft .NET Framework 4  
(2979575)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(критический)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(3000869)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2998579)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
(критический)  
Internet Explorer 8  
(2987107)  
(критический)  
Internet Explorer 9  
(2987107)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2968292)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2972098)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2979568)  
(существенный)  
Microsoft .NET Framework 4  
(2972106)  
(критический)  
Microsoft .NET Framework 4  
(2979575)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(критический)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(3000869)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2998579)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
(2987107)  
(средний)  
Internet Explorer 8  
(2987107)  
(средний)  
Internet Explorer 9  
(2987107)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2968292)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2972098)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2979568)  
(существенный)  
Microsoft .NET Framework 4  
(2972106)  
(критический)  
Microsoft .NET Framework 4  
(2979575)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(критический)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(3000869)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2998579)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
(средний)  
Internet Explorer 8  
(2987107)  
(средний)  
Internet Explorer 9  
(2987107)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2968292)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2972098)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2979568)  
(существенный)  
Microsoft .NET Framework 4  
(2972106)  
(критический)  
Microsoft .NET Framework 4  
(2979575)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(критический)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(3000869)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2998579)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2968292)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2972098)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2979568)  
(существенный)  
Microsoft .NET Framework 4  
(2972106)  
(критический)  
Microsoft .NET Framework 4  
(2979575)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(3000869)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2998579)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
(2987107)  
(критический)  
Internet Explorer 9  
(2987107)  
(критический)  
Internet Explorer 10  
(2987107)  
(критический)  
Internet Explorer 11  
(2987107)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2972100)  
(критический)  
Microsoft .NET Framework 3.5.1  
(2979570)  
(существенный)  
Microsoft .NET Framework 4  
(2972106)  
(критический)  
Microsoft .NET Framework 4  
(2979575)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(критический)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(3000869)  
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
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2987107)  
(критический)  
Internet Explorer 9  
(2987107)  
(критический)  
Internet Explorer 10  
(2987107)  
(критический)  
Internet Explorer 11  
(2987107)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2972100)  
(критический)  
Microsoft .NET Framework 3.5.1  
(2979570)  
(существенный)  
Microsoft .NET Framework 4  
(2972106)  
(критический)  
Microsoft .NET Framework 4  
(2979575)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(критический)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(3000869)  
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
(2987107)  
(средний)  
Internet Explorer 9  
(2987107)  
(средний)  
Internet Explorer 10  
(2987107)  
(средний)  
Internet Explorer 11  
(2987107)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2972100)  
(критический)  
Microsoft .NET Framework 3.5.1  
(2979570)  
(существенный)  
Microsoft .NET Framework 4  
(2972106)  
(критический)  
Microsoft .NET Framework 4  
(2979575)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(критический)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(3000869)  
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
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2987107)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2972100)  
(критический)  
Microsoft .NET Framework 3.5.1  
(2979570)  
(существенный)  
Microsoft .NET Framework 4  
(2972106)  
(критический)  
Microsoft .NET Framework 4  
(2979575)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(3000869)  
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
<td style="border:1px solid black;" colspan="7">
**Windows 8 и Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
<td style="border:1px solid black;">
**Нет**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2987107)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968295)  
(существенный)  
Microsoft .NET Framework 3.5  
(2972101)  
(критический)  
Microsoft .NET Framework 3.5  
(2979571)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
(критический)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(3000869)  
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
Windows 8 для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2987107)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968295)  
(существенный)  
Microsoft .NET Framework 3.5  
(2972101)  
(критический)  
Microsoft .NET Framework 3.5  
(2979571)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
(критический)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(3000869)  
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
Windows 8.1 для 32-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2987107)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968296)  
(существенный)  
Microsoft .NET Framework 3.5  
(2972103)  
(критический)  
Microsoft .NET Framework 3.5  
(2979573)  
(существенный)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
(критический)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(3000869)  
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
Windows 8.1 для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2987107)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968296)  
(существенный)  
Microsoft .NET Framework 3.5  
(2972103)  
(критический)  
Microsoft .NET Framework 3.5  
(2979573)  
(существенный)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
(критический)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(3000869)  
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 и Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
<td style="border:1px solid black;">
**Нет**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2987107)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968295)  
(существенный)  
Microsoft .NET Framework 3.5  
(2972101)  
(критический)  
Microsoft .NET Framework 3.5  
(2979571)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
(критический)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3000869)  
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
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2987107)  
(средний)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968296)  
(существенный)  
Microsoft .NET Framework 3.5  
(2972103)  
(критический)  
Microsoft .NET Framework 3.5  
(2979573)  
(существенный)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
(критический)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3000869)  
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
<td style="border:1px solid black;" colspan="7">
**Windows RT и Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
(2987107)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
(критический)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows RT  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows RT  
(3000869)  
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
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2987107)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
(критический)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3000869)  
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
<td style="border:1px solid black;" colspan="7">
**Вариант установки ядра сервера**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-056**](http://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](http://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](http://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](http://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](http://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](http://go.microsoft.com/fwlink/?linkid=513102)

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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2998579)  
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
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(3000061)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2998579)  
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
Microsoft .NET Framework 3.5.1  
(2968294)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2972100)  
(критический)  
Microsoft .NET Framework 3.5.1  
(2979570)  
(существенный)  
Microsoft .NET Framework 4  
(2972106)  
(критический)  
Microsoft .NET Framework 4  
(2979575)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(критический)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(3000061)  
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
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968295)  
(существенный)  
Microsoft .NET Framework 3.5  
(2972101)  
(критический)  
Microsoft .NET Framework 3.5  
(2979571)  
(существенный)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
(критический)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(3000061)  
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
<td style="border:1px solid black;">
Windows Server 2012 R2 (установка основных серверных компонентов)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968296)  
(существенный)  
Microsoft .NET Framework 3.5  
(2972103)  
(критический)  
Microsoft .NET Framework 3.5  
(2979573)  
(существенный)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
(критический)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (установка основных серверных компонентов)  
(3000061)  
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
</table>
 
 

### Программное обеспечение и средства разработки Microsoft

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**ASP.NET MVC**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-059**](http://go.microsoft.com/fwlink/?linkid=507673)

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
ASP.NET MVC 2.0

</td>
<td style="border:1px solid black;">
ASP.NET MVC 2.0  
(2993939)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 3.0

</td>
<td style="border:1px solid black;">
ASP.NET MVC 3.0  
(2993937)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 4.0

</td>
<td style="border:1px solid black;">
ASP.NET MVC 4.0  
(2993928)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 5.0

</td>
<td style="border:1px solid black;">
ASP.NET MVC 5.0  
(2992080)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 5.1

</td>
<td style="border:1px solid black;">
ASP.NET MVC 5.1  
(2994397)  
(существенный)

</td>
</tr>
</table>
 
 

### Пакеты приложений и программные продукты Microsoft Office

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-061**](http://go.microsoft.com/fwlink/?linkid=513106)

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
Microsoft Office 2007 с пакетом обновления 3 (SP3)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 3 (SP3)  
(2883031)  
(существенный)  
Microsoft Word 2007 с пакетом обновления 3 (SP3)  
(2883032)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-061**](http://go.microsoft.com/fwlink/?linkid=513106)

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
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(2883008)  
(существенный)  
Microsoft Word 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(2883013)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 2 (SP2) (32-разрядные версии)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 2 (SP2) (32-разрядные версии)  
(2883008)  
(существенный)  
Microsoft Word 2010 с пакетом обновления 2 (SP2) (32-разрядные версии)  
(2883013)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(2883008)  
(существенный)  
Microsoft Word 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(2883013)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 2 (SP2) (64-разрядные версии)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 2 (SP2) (64-разрядные версии)  
(2883008)  
(существенный)  
Microsoft Word 2010 с пакетом обновления 2 (SP2) (64-разрядные версии)  
(2883013)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office для Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-061**](http://go.microsoft.com/fwlink/?linkid=513106)

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
Microsoft Office для Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Office для Mac 2011  
(3004865)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Другое программное обеспечение Microsoft Office**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-061**](http://go.microsoft.com/fwlink/?linkid=513106)

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
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)

</td>
<td style="border:1px solid black;">
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)  
(2883031)  
(существенный)

</td>
</tr>
</table>
 
**Примечание для MS14-061**

Эти бюллетени распространяются на несколько категорий программного обеспечения. В других таблицах этого раздела перечислено дополнительное уязвимое программное обеспечение.

 

### Службы Microsoft Office и Web Apps

 
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
[**MS14-061**](http://go.microsoft.com/fwlink/?linkid=513106)

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
Microsoft SharePoint Server 2010 с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2883098)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2883098)  
(существенный)

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
[**MS14-061**](http://go.microsoft.com/fwlink/?linkid=513106)

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
Microsoft Office Web Apps 2010

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2010  
(2889827)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2010 с пакетом обновления 1 (SP1)  
(2889827)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2010 с пакетом обновления 2 (SP2)  
(2889827)  
(существенный)

</td>
</tr>
</table>
 
**Примечание для MS14-061**

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

**MS14-056**

-   Джеймса Форшо (James Forshaw) из компании [Context Information Security](http://www.contextis.com/) за сообщение об уязвимости Internet Explorer, приводящей к несанкционированному повышению привилегий (CVE-2014-4123)
-   Джеймса Форшо (James Forshaw) из компании [Context Information Security](http://www.contextis.com/) за сообщение об уязвимости Internet Explorer, приводящей к несанкционированному повышению привилегий (CVE-2014-4124)
-   Рохит Мот (Rohit Mothe), сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4126)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4127)
-   Пользователя Omair, сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4128)
-   Джейсона Кратцера (Jason Kratzer) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4128)
-   Лабораторию [Adlab компании Venustech](http://www.venustech.com.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4129)
-   Пользователя Sky, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4130)
-   Чжибинь Ху (Zhibin Hu) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4132)
-   Хосе А. Васкеса (José A. Vázquez) из Yenteasy Security Research, сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4132)
-   Чжибинь Ху (Zhibin Hu) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4133)
-   Чжибинь Ху (Zhibin Hu) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4134)
-   Лю Луна (Liu Long) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4137)
-   Пользователя SkyLined, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4138)
-   Джона Вилламила (John Villamil, @day6reak) за сообщение об уязвимости Internet Explorer, делающей возможным обход функции безопасности ASLR (CVE-2014-4140)
-   Питера 'corelanc0d3r' Ван Экуте (Peter 'corelanc0d3r' Van Eeckhoutte) из компании [Corelan](http://www.corelangcv.com/), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4141)

**MS14-057**

-   Джеймса Форшо (James Forshaw) из компании [Context Information Security](http://www.contextis.com/) за сообщение об уязвимости .NET-приложения ClickOnce, приводящей к несанкционированному повышению привилегий (CVE-2014-4073)

**MS14-058**

-   коллектив аналитиков [CrowdStrike](http://www.crowdstrike.com/) за совместную работу по устранению уязвимости Win32k.sys, приводящей к несанкционированному повышению привилегию (CVE-2014-4113)
-   корпорацию [FireEye](http://www.fireeye.com/) за совместную работу по устранению уязвимости Win32k.sys, приводящей к несанкционированному повышению привилегию (CVE-2014-4113)
-   корпорацию [FireEye](http://www.fireeye.com/) за совместную работу по устранению уязвимости анализа шрифтов TrueType, делающей возможным несанкционированное повышение привилегий (CVE-2014-4148)

**MS14-060**

-   компанию [iSIGHT Partners](http://www.isightpartners.com/) за сообщение об уязвимости Windows OLE, делающей возможным удаленное выполнение кода (CVE-2014-4114)

**MS14-061**

-   компанию 3S Labs, сотрудничающую с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости формата файлов Microsoft Word (CVE-2014-4117)

**MS14-063**

-   Марсина "Айсвол" Нога из компании [Cisco Talos](http://www.sourcefire.com/solutions/research) за сообщение об уязвимости драйвера Windows для разделов диска, делающей возможным несанкционированное повышение привилегий (CVE-2014-4115)

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

-   Версия 1.0 (14 октября 2014 г.) Обзор бюллетеней опубликован.

*Время создания страницы: 2014-10-13 14:39Z-07:00.*
