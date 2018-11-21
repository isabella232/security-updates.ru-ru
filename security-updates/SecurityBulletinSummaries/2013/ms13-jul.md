---
TOCTitle: 'MS13-JUL'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за июль 2013 г.'
ms:assetid: 'ms13-jul'
ms:contentKeyID: 61236172
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms13-jul(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за июль 2013 г.
=============================================================

Дата публикации: 9 июля 2013 г. | Дата обновления: 27 августа 2013 г.

**Версия:** 3.0

В этот обзор включены бюллетени по безопасности, выпущенные в июле 2013 года.

После выпуска бюллетеней за июль 2013 года этот обзор заменит предварительное уведомление, выпущенное 4 июля 2013 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

10 июля 2013 года в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в июльской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032556406&culture=en-us). После наступления этой даты данная веб-трансляция будет доступна [по запросу](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538733&culture=en-us).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в .NET Framework и Silverlight делают возможным удаленное выполнение кода (2861561)</strong><br />
<br />
Данное обновление для системы безопасности устраняет пять обнаруженных пользователями уязвимостей и две опубликованных уязвимости в Microsoft .NET Framework и Microsoft Silverlight. Наиболее серьезная из этих уязвимостей делает возможным удаленное выполнение кода, если доверенное приложение использует особый шаблон кода. Злоумышленник, воспользовавшийся этой уязвимостью, может получить те же права, что и вошедший в систему пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework,<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;"><strong>Уязвимости</strong>драйверов режима ядра Windows делают возможным удаленное выполнение кода <strong>(2850851)<br />
<br />
</strong>Это обновление для системы безопасности устраняет две опубликованные и шесть обнаруженных пользователями уязвимостей в Microsoft Windows. Наиболее серьезная из этих уязвимостей делает возможным удаленное выполнение кода, если пользователь просматривает общее содержимое, в котором внедрены особым образом созданные файлы шрифтов TrueType. Воспользовавшись этой уязвимостью, злоумышленник может установить полный контроль над системой.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301531">MS13-054</a></td>
<td style="border:1px solid black;"><strong>Уязвимость</strong> <strong>GDI+</strong> <strong>делает возможным удаленное выполнение кода (2848295)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows, Microsoft Office, Microsoft Lync и Microsoft Visual Studio. Эта уязвимость делает возможным удаленное выполнение кода, если пользователь просматривает общее содержимое, в котором внедрены особым образом созданные файлы шрифтов TrueType.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Office,<br />
Microsoft Visual Studio,<br />
Microsoft Lync</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (2846071)</strong> <strong><br />
<br />
</strong>Это обновление для системы безопасности устраняет 17 обнаруженных пользователями уязвимостей в браузере Internet Explorer. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь просмотрит особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся наиболее серьезными из данных уязвимостей, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309326">MS13-056</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft DirectShow делает возможным удаленное выполнение кода (2845187)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. в том случае, если пользователь откроет специально созданный файл изображения. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которые имеет локальный пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301528">MS13-057</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Windows Media Format Runtime делает возможным удаленное выполнение код (2847883)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным удаленное выполнение кода в том случае, если пользователь откроет особым образом созданный файл мультимедиа. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которые имеет локальный пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=308992">MS13-058</a></td>
<td style="border:1px solid black;"><strong>Уязвимость Защитника Windows делает возможным несанкционированное получение прав (2847927)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Защитнике Windows для Windows 7 и Защитнике Windows, установленном в Windows Server 2008 R2. Данная уязвимость делает возможным несанкционированное получение прав из-за имен путей, используемых Защитником Windows. Злоумышленник, успешно воспользовавшийся ею, может выполнить произвольный код и получить полный контроль над системой. После этого злоумышленник сможет устанавливать программы, просматривать, изменять и удалять данные, а также создавать новые учетные записи с неограниченными правами. Чтобы воспользоваться уязвимостью, злоумышленник должен обладать действительными учетными данными. Этой уязвимостью не могут воспользоваться анонимные пользователи.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Перезагрузка не требуется</td>
<td style="border:1px solid black;">Программное обеспечение корпорации Майкрософт по безопасности</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с анализом шрифтов TrueType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с нарушением прав доступа к массивам</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3131">CVE-2013-3131</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с обходом отражения делегатов</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3132">CVE-2013-3132</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">Уязвимость к заражению анонимным способом</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3133">CVE-2013-3133</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с назначением массивов</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3134">CVE-2013-3134</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с сериализацией делегатов</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3171">CVE-2013-3171</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с пустым указателем</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3178">CVE-2013-3178</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Уязвимость Win32k, связанная с выделением памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1300">CVE-2013-1300</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Уязвимость Win32k, связанная с разыменованием</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1340">CVE-2013-1340</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможной атаку типа &quot;отказ в обслуживании&quot;, в последнем выпуске программного обеспечения.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Уязвимость Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1345">CVE-2013-1345</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможной атаку типа &quot;отказ в обслуживании&quot;, в последнем выпуске программного обеспечения.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с анализом шрифтов TrueType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Уязвимость Win32k, приводящая к раскрытию информации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3167">CVE-2013-3167</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Это уязвимость, которая делает возможным раскрытие информации и последующее несанкционированное повышение привилегий.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Уязвимость Win32k, связанная с перезаписью буфера</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3173">CVE-2013-3173</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Уязвимость, связанная со считыванием Win32k антивирусной программой</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3660">CVE-2013-3660</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.<br />
<br />
Корпорации Майкрософт известно о направленных атаках с целью использования этой уязвимости для несанкционированного повышения привилегий.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301531">MS13-054</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с анализом шрифтов TrueType</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3115">CVE-2013-3115</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3143">CVE-2013-3143</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3144">CVE-2013-3144</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3145">CVE-2013-3145</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3146">CVE-2013-3146</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3147">CVE-2013-3147</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3148">CVE-2013-3148</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3149">CVE-2013-3149</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3150">CVE-2013-3150</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3151">CVE-2013-3151</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3152">CVE-2013-3152</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3153">CVE-2013-3153</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3161">CVE-2013-3161</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3162">CVE-2013-3162</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3163">CVE-2013-3163</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Специалистам Майкрософт известно о направленных атаках с целью использования этой уязвимости через Internet Explorer 8.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3164">CVE-2013-3164</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Уязвимость кодировки символов Shift-JIS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3166">CVE-2013-3166</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=309326">MS13-056</a></td>
<td style="border:1px solid black;">Уязвимость DirectShow, связанная с произвольной перезаписью памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3174">CVE-2013-3174</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301528">MS13-057</a></td>
<td style="border:1px solid black;">Уязвимость видеодекодера WMV, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3127">CVE-2013-3127</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=308992">MS13-058</a></td>
<td style="border:1px solid black;">Уязвимость Защитника Windows для Microsoft Windows 7, связанная с неправильными именами путей</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3154">CVE-2013-3154</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
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
<th colspan="8">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.0 с пакетом обновления 3 (SP3)  
(только Media Center Edition 2005 с пакетом обновления 3 (SP3) и Tablet PC Edition 2005 с пакетом обновления 3 (SP3))  
(2833951)  
(существенный)  
Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)  
(2833941)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2833940)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2844285)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2832411)  
(критический)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2840629)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)  
(Windows GDI+)  
(2834886)  
(критический)  
Windows XP с пакетом обновления 3 (SP3)  
(Только Windows XP Tablet PC Edition 2005)  
(Журнал)  
(2835364)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2846071)  
(критический)  
Internet Explorer 7  
(2846071)  
(критический)  
Internet Explorer 8  
(2846071)  
(критический)
</td>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)  
(2845187)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Format Runtime 11<sup>[1]</sup>
(wmvdecod.dll)  
(только для Media Center Edition)  
(2834904)  
(критический)  
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(только для Media Center Edition)  
(2834905)  
(критический)  
Windows Media Format Runtime 9  
(wmvdmod.dll)  
(2803821)  
(критический)  
Windows Media Format Runtime 9.5<sup>[2]</sup>
(wmvdmod.dll)  
(2834902)  
(критический)  
Windows Media Format Runtime 9.5<sup>[3]</sup>
(wmvdmod.dll)  
(2834903)  
(критический)  
Windows Media Format Runtime 11  
(wmvdecod.dll)  
(2834904)  
(критический)  
wmv9vcm.dll (кодек)  
(2845142)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)  
(2833941)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2833940)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2844285)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2832411)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
  
(2840628)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(Windows GDI+)  
(2834886)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2846071)  
(критический)  
Internet Explorer 7  
(2846071)  
(критический)  
Internet Explorer 8  
(2846071)  
(критический)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2845187)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(2803821)  
(критический)  
Windows Media Format Runtime 9.5 x64  
(wmvdmod.dll)  
(2834902)  
(критический)  
Windows Media Format Runtime 11  
(wmvdecod.dll)  
(2834904)  
(критический)  
wmv9vcm.dll (кодек)  
(2845142)  
(критический)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)  
(2833949)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2833940)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2844285)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2832411)  
(критический)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2840629)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(Windows GDI+)  
(2834886)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2846071)  
(средний)  
Internet Explorer 7  
(2846071)  
(средний)  
Internet Explorer 8  
(2846071)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2845187)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(2803821)  
(критический)  
wmv9vcm.dll (кодек)  
(2845142)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)  
(2833941)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2833940)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2844285)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2832411)  
(критический)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2840629)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(Windows GDI+)  
(2834886)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2846071)  
(средний)  
Internet Explorer 7  
(2846071)  
(средний)  
Internet Explorer 8  
(2846071)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2845187)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(2803821)  
(критический)  
Windows Media Format Runtime 9.5 x64  
(wmvdmod.dll)  
(2834902)  
(критический)  
Windows Media Format Runtime 11  
(wmvdmod.dll)  
(2834904)  
(критический)  
wmv9vcm.dll (кодек)  
(2845142)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)  
(2833941)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2833940)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2844285)  
(существенный)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2840629)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(Windows GDI+)  
(2834886)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2846071)  
(средний)  
Internet Explorer 7  
(2846071)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2845187)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<th colspan="8">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)  
(2833941)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2833947)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2844287)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2832412)  
(критический)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2840629)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(существенный)  
Microsoft .NET Framework 4.5  
(2835622)  
(критический)  
Microsoft .NET Framework 4.5  
(2833957)  
(критический)  
Microsoft .NET Framework 4.5  
(2840642)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(DirectWrite)  
(2835361)  
(критический)  
Windows Vista с пакетом обновления 2 (SP2)  
(Windows GDI+)  
(2834886)  
(критический)  
Windows Vista с пакетом обновления 2 (SP2)  
(Журнал)  
(2835364)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(критический)  
Internet Explorer 8  
(2846071)  
(критический)  
Internet Explorer 9  
(2846071)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2845187)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Проигрыватель Windows Media 11  
(wmvdecod.dll)  
(2803821)  
(критический)  
wmv9vcm.dll (кодек)  
(2845142)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)  
(2833941)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2833947)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2844287)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2832412)  
(критический)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2840629)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(существенный)  
Microsoft .NET Framework 4.5  
(2835622)  
(критический)  
Microsoft .NET Framework 4.5  
(2833957)  
(критический)  
Microsoft .NET Framework 4.5  
(2840642)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(DirectWrite)  
(2835361)  
(критический)  
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(Windows GDI+)  
(2834886)  
(критический)  
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(Журнал)  
(2835364)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(критический)  
Internet Explorer 8  
(2846071)  
(критический)  
Internet Explorer 9  
(2846071)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2845187)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Проигрыватель Windows Media 11  
(wmvdecod.dll)  
(2803821)  
(критический)  
wmv9vcm.dll (кодек)  
(2845142)  
(критический)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)  
(2833941)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2833947)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2844287)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2832412)  
(критический)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2840629)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(существенный)  
Microsoft .NET Framework 4.5  
(2835622)  
(критический)  
Microsoft .NET Framework 4.5  
(2833957)  
(критический)  
Microsoft .NET Framework 4.5  
(2840642)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(DirectWrite)  
(2835361)  
(критический)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(Windows GDI+)  
(2834886)  
(критический)  
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(Журнал)  
(2835364)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(средний)  
Internet Explorer 8  
(2846071)  
(средний)  
Internet Explorer 9  
(2846071)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2845187)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Проигрыватель Windows Media 11\[4\]  
(wmvdecod.dll)  
(2803821)  
(критический)  
wmv9vcm.dll (кодек) \[5\]  
(2845142)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)  
(2833941)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2833947)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2844287)  
(существенный)  
Microsoft .NET Framework 3.0 с пакетом обновления 2 (SP2)  
(2832412)  
(критический)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2840629)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(существенный)  
Microsoft .NET Framework 4.5  
(2835622)  
(критический)  
Microsoft .NET Framework 4.5  
(2833957)  
(критический)  
Microsoft .NET Framework 4.5  
(2840642)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(DirectWrite)  
(2835361)  
(критический)  
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(Windows GDI+)  
(2834886)  
(критический)  
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(Журнал)  
(2835364)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(средний)  
Internet Explorer 8  
(2846071)  
(средний)  
Internet Explorer 9  
(2846071)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2845187)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Проигрыватель Windows Media 11\[4\]  
(wmvdecod.dll)  
(2803821)  
(критический)  
wmv9vcm.dll (кодек) \[5\]  
(2845142)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)  
(2833941)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2833947)  
(критический)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2844287)  
(существенный)  
Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)  
(2840629)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(Windows GDI+)  
(2834886)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<th colspan="8">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
(критический)  
Microsoft .NET Framework 3.5.1  
(2833946)  
(критический)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(существенный)  
Microsoft .NET Framework 4.5  
(2833957)  
(критический)  
Microsoft .NET Framework 4.5  
(2840642)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(DirectWrite)  
(2835361)  
(критический)  
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(Windows GDI+)  
(2834886)  
(критический)  
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(Журнал)  
(2835364)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(критический)  
Internet Explorer 9  
(2846071)  
(критический)  
Internet Explorer 10  
(2846071)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2845187)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Проигрыватель Windows Media 12  
(wmvdecod.dll)  
(2803821)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
(критический)  
Microsoft .NET Framework 3.5.1  
(2833946)  
(критический)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(существенный)  
Microsoft .NET Framework 4.5  
(2833957)  
(критический)  
Microsoft .NET Framework 4.5  
(2840642)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(DirectWrite)  
(2835361)  
(критический)  
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(Windows GDI+)  
(2834886)  
(критический)  
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(Журнал)  
(2835364)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(критический)  
Internet Explorer 9  
(2846071)  
(критический)  
Internet Explorer 10  
(2846071)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2845187)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Проигрыватель Windows Media 12  
(wmvdecod.dll)  
(2803821)  
(критический)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
(критический)  
Microsoft .NET Framework 3.5.1  
(2833946)  
(критический)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(существенный)  
Microsoft .NET Framework 4.5  
(2833957)  
(критический)  
Microsoft .NET Framework 4.5  
(2840642)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(DirectWrite)  
(2835361)  
(критический)  
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(Windows GDI+)  
(2834886)  
(критический)  
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(Журнал)  
(2835364)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(средний)  
Internet Explorer 9  
(2846071)  
(средний)  
Internet Explorer 10  
(2846071)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2845187)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Проигрыватель Windows Media 12\[4\]  
(wmvdecod.dll)  
(2803821)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2833946)  
(критический)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(DirectWrite)  
(2835361)  
(критический)  
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(Windows GDI+)  
(2834886)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<th colspan="8">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(критический)  
Microsoft .NET Framework 3.5  
(2833959)  
(критический)  
Microsoft .NET Framework 3.5  
(2840633)  
(существенный)  
Microsoft .NET Framework 3.5  
(2844289)  
(существенный)  
Microsoft .NET Framework 4.5  
(2833958)  
(критический)  
Microsoft .NET Framework 4.5  
(2840632)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(DirectWrite)  
(2835361)  
(критический)  
Windows 8 для 32-разрядных систем  
(Журнал)  
(2835364)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2846071)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2845187)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Проигрыватель Windows Media 12  
(wmvdecod.dll)  
(2803821)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(критический)  
Microsoft .NET Framework 3.5  
(2833959)  
(критический)  
Microsoft .NET Framework 3.5  
(2840633)  
(существенный)  
Microsoft .NET Framework 3.5  
(2844289)  
(существенный)  
Microsoft .NET Framework 4.5  
(2833958)  
(критический)  
Microsoft .NET Framework 4.5  
(2840632)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(DirectWrite)  
(2835361)  
(критический)  
Windows 8 для 64-разрядных систем  
(Журнал)  
(2835364)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2846071)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2845187)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Проигрыватель Windows Media 12  
(wmvdecod.dll)  
(2803821)  
(критический)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(критический)  
Microsoft .NET Framework 3.5  
(2833959)  
(критический)  
Microsoft .NET Framework 3.5  
(2840633)  
(существенный)  
Microsoft .NET Framework 3.5  
(2844289)  
(существенный)  
Microsoft .NET Framework 4.5  
(2833958)  
(критический)  
Microsoft .NET Framework 4.5  
(2840632)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(DirectWrite)  
(2835361)  
(критический)  
Windows Server 2012  
(Журнал)  
(2835364)  
(критический)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2846071)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2845187)  
(критический)
</td>
<td style="border:1px solid black;" colspan="2">
Проигрыватель Windows Media 12\[4\]  
(wmvdecod.dll)  
(2803821)  
(критический)
</td>
</tr>
<tr>
<th colspan="8">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**
</td>
<td style="border:1px solid black;" colspan="2">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2833958)  
(критический)  
Microsoft .NET Framework 4.5  
(2840632)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows RT  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows RT  
(DirectWrite)  
(2835361)  
(критический)
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2846071)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
Проигрыватель Windows Media 12  
(wmvdecod.dll)  
(2803821)  
(критический)
</td>
</tr>
<tr>
<th colspan="8">
Вариант установки ядра сервера
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](http://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](http://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](http://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](http://go.microsoft.com/fwlink/?linkid=301528)
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
**Нет**
</td>
<td style="border:1px solid black;">
**Нет**
</td>
<td style="border:1px solid black;" colspan="2">
**Нет**
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
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(Windows GDI+)  
(2834886)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
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
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(Windows GDI+)  
(2834886)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2833946)  
(критический)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(существенный)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(критический)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(существенный)  
Microsoft .NET Framework 4.5  
(2833957)  
(критический)  
Microsoft .NET Framework 4.5  
(2840642)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(Windows GDI+)  
(2834886)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(критический)  
Microsoft .NET Framework 3.5  
(2833959)  
(критический)  
Microsoft .NET Framework 3.5  
(2840633)  
(существенный)  
Microsoft .NET Framework 3.5  
(2844289)  
(существенный)  
Microsoft .NET Framework 4.5  
(2833958)  
(критический)  
Microsoft .NET Framework 4.5  
(2840632)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(2850851)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(DirectWrite)  
(2835361)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;" colspan="2">
Не применимо
</td>
</tr>
</table>
 
**Примечания для MS13-052**

<sup>[1]</sup>**Уязвимости подвержены NET Framework 4 и клиентский профиль .NET Framework 4** Предлагаются два профиля для распространяемых пакетов .NET Framework версии 4: .NET Framework 4 и клиентский профиль .NET Framework 4. Клиентский профиль .NET Framework 4 является частью .NET Framework 4. Уязвимости, устраняемой данным обновлением, подвержены как платформа .NET Framework 4, так и клиентский профиль .NET Framework 4. Дополнительные сведения см. в статье MSDN [Установка .NET Framework](http://msdn.microsoft.com/library/5a4x27ek).

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

**Примечание для** **MS13-053** **и** **MS13-055**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

**Примечание** **для** **MS13-054**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

**Примечания** **для MS13-057**

<sup>[1]</sup>Это обновление предлагается только для систем, в которых выполнено обновление до Windows Media Format Runtime 11 или проигрывателя Windows Media 11.
<sup>[2]</sup> Это обновление предлагается только для систем, на которых работает Windows Media Format Runtime 9.5 NL.
<sup>[3]</sup>Это обновление предлагается только для систем, на которых работает Windows Media Format Runtime 9.5 L.
\[4\]Это обновление предлагается, только если включен дополнительный компонент "Возможности рабочего стола".
\[5\]Это обновление предлагается, только если включен дополнительный компонент "Возможности рабочего стола" и присутствует кодек wmv9vcm.dll. Подробную информацию можно найти в бюллетене.

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Пакеты приложений и программные продукты Microsoft Office

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Программное обеспечение Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
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
Microsoft Office 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Microsoft Office 2003 с пакетом обновления 3 (SP3)  
(2817480)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 3 (SP3)  
(2687309)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(2687276)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(2687276)  
(существенный)
</td>
</tr>
</table>
 
**Примечание для MS13-054**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Программное обеспечение и средства разработки Microsoft

 
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 с пакетом обновления 1 (SP1)<sup>[1]</sup>
(2856545)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Silverlight
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
[**MS13-052**](http://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 при установке на Mac  
(2847559)  
(критический)  
Microsoft Silverlight 5 Developer Runtime при установке в Mac  
(2847559)  
(критический)  
Microsoft Silverlight 5 при установке в 32-разрядных выпусках клиентских систем Microsoft Windows  
(2847559)  
(критический)  
Microsoft Silverlight 5 при установке в 64-разрядных выпусках клиентских систем Microsoft Windows  
(2847559)  
(критический)  
Microsoft Silverlight 5 Developer Runtime при установке во всех поддерживаемых выпусках клиентских систем Microsoft Windows  
(2847559)  
(критический)  
Microsoft Silverlight 5 при установке в 32-разрядных выпусках серверных систем Microsoft Windows  
(2847559)  
(критический)  
Microsoft Silverlight 5 при установке в 64-разрядных выпусках серверных систем Microsoft Windows  
(2847559)  
(критический)  
Microsoft Silverlight 5 Developer Runtime при установке во всех поддерживаемых выпусках серверных систем Microsoft Windows  
(2847559)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 
**Примечание для MS13-052**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

**Примечания** **для MS13-054**

<sup>[1]</sup>Это обновление можно загрузить только с веб-сайта Центра загрузки Майкрософт.

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

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
[**MS13-054**](http://go.microsoft.com/fwlink/?linkid=301531)
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
Microsoft Lync 2010 (32-разрядная версия)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32-разрядная версия)  
(2843160)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 (64-разрядная версия)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64-разрядная версия)  
(2843160)  
(критический)
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
(2843162)  
(критический)
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
(2843163)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32-разрядная версия)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32-разрядная версия)  
(2817465)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32-разрядная версия)
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32-разрядная версия)  
(2817465)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64-разрядная версия)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64-разрядная версия)  
(2817465)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (64-разрядная версия)
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (64-разрядная версия)  
(2817465)  
(критический)
</td>
</tr>
</table>
 
**Примечание для MS13-054**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Этот бюллетень относится к нескольким категориям ПО

#### Программное обеспечение корпорации Майкрософт по безопасности

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Антишпионское ПО
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-058**](http://go.microsoft.com/fwlink/?linkid=308992)
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
Защитник Windows для Windows 7 (x86)
</td>
<td style="border:1px solid black;">
Защитник Windows для Windows 7 (x86)  
(2847927)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Защитник Windows для Windows 7 (x64)
</td>
<td style="border:1px solid black;">
Защитник Windows для Windows 7 (x64)  
(2847927)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Защитник Windows, установленный в Windows Server 2008 R2 (x64)
</td>
<td style="border:1px solid black;">
Защитник Windows, установленный в Windows Server 2008 R2 (x64)  
(2847927)  
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

**MS13-052**

-   Линг Чуань Ли (Ling Chuan Lee) и Ли Йи Чана (Lee Yee Chan) из [F-13 Laboratory](http://www.f13-labs.net/) за сообщение об уязвимости, связанной с анализом шрифтов TrueType (CVE-2013-3129)
-   Алона Флисса (Alon Fliess) за сообщение об уязвимости, связанной с нарушением прав доступа к массивам (CVE-2013-3131)
-   Джеймса Форшо (James Forshaw) из компании [Context Information Security](http://www.contextis.com/) за сообщение об уязвимости, связанной с обходом отражения делегатов (CVE-2013-3132)
-   Джеймса Форшо (James Forshaw) из компании [Context Information Security](http://www.contextis.com/) за сообщение об уязвимости к заражению анонимным способом (CVE-2013-3133)
-   Джеймса Форшоу (James Forshaw) из [Context Information Security](http://www.contextis.com/) за сообщение об уязвимости, связанной с сериализацией делегатов (CVE-2013-3171)
-   Виталия Топорова (Vitaliy Toropov) за сообщение об уязвимости, связанной с пустым указателем (CVE-2013-3178)

**MS13-053**

-   Джона Батлера (Jon Butler) и Нильса (Nils) из MWR Labs, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Win32k, связанной с выделением памяти (CVE-2013-1300)
-   Александра Чижова (Alexander Chizhov) из компании [Dr.Web](http://drweb.com/) за сообщение об уязвимости Win32k, связанной с разыменованием (CVE-2013-1340)
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Win32k, связанной с дескрипторами окон (CVE-2013-1345)
-   Линг Чуань Ли (Ling Chuan Lee) и Ли Йи Чана (Lee Yee Chan) из [F13 Laboratory](http://www.f13-labs.net/) за сообщение об уязвимости, связанной с анализом шрифтов TrueType (CVE-2013-3129)
-   Ин Лянь (Yinliang) из [Tencent PC Manager](http://guanjia.qq.com) за сообщение об уязвимости Win32k, приводящей к раскрытию информации (CVE-2013-3167)
-   [Матеуша Юрчика "j00ru" (Mateusz "j00ru" Jurczyk)](http://j00ru.vexillium.org/) из [Google Inc.](http://www.google.com/) за сообщение об уязвимости Win32k, связанной с переполнением буфера (CVE-2013-3172)
-   Вен Ю Дзы (Wen Yujie) и Гуо Пен Фей (Guo Pengfei) из [Qihoo 360 Security Center](http://www.360.cn/) за сообщение об уязвимости Win32k, связанной с перезаписью буфера (CVE-2013-3173)

**MS13-054**

-   Линг Чуань Ли (Ling Chuan Lee) и Ли Йи Чана (Lee Yee Chan) из [F13 Laboratory](http://www.f13-labs.net/) за сообщение об уязвимости, связанной с анализом шрифтов TrueType (CVE-2013-3129)

**MS13-055**

-   Ивана Фратрича (Ivan Fratric) и Бена Хокса (Ben Hawkes) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3115)
-   Пользователя SkyLined, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3143)
-   Саймона Цукербрауна (Simon Zuckerbraun), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3144)
-   Тоан Фам Вана (Toan Pham Van), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3145)
-   Тоан Фам Вана (Toan Pham Van), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3146)
-   Пользователя [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com), сотрудничающего с компании [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3147)
-   Пользователя Bluesea, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3148)
-   Пользователя Bluesea, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3149)
-   Пользователя [Omair](http://krash.in/), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3150)
-   Тоан Фам Вана (Toan Pham Van), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3151)
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3152)
-   Пользователя e6af8de8b1d4b2b6d5ba2610cbf9cd38, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3153)
-   Ивана Фратрича (Ivan Fratric) и Бена Хокса (Ben Hawkes) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3161)
-   Ивана Фратрича (Ivan Fratric) и Бена Хокса (Ben Hawkes) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3162)
-   Хосе Антонио Васкеса Гонзалеса (Jose Antonio Vazquez Gonzalez), сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3163)
-   Скота Белла (Scott Bell) из компании [Security-Assessment.com](http://www.security-assessment.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3164)
-   Масато Кинугаву (Masato Kinugawa) за сообщение об уязвимости кодировки символов Shift JIS (CVE-2013-3166)
-   Марка Ясона (Mark Yason) из IBM X-Force за совместную с нами работу над изменением для обеспечения многоуровневой защиты, описанным в данном бюллетене (CVE-2013-4015)

**MS13-056**

-   Андреса Гомеса Рамиреса (Andrés Gómez Ramírez) за сообщение об уязвимости DirectShow, связанной с произвольной перезаписью памяти (CVE-2013-3174)

**MS13-057**

-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости видеодекодера WMV, делающей возможным удаленное выполнение кода (CVE-2013-3127)

**MS13-058**

-   Альтона Блома (Alton Blom) из [Резервного банка Австралии](http://www.rba.gov.au/) за сообщение об уязвимости Защитника Windows для Microsoft Windows 7, связанной с неправильными именами путей (CVE-2013-3154)

#### Поддержка

-   Подверженное уязвимости программное обеспечение, перечисленное в этом бюллетене, проверено на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (9 июля 2013 г.): Обзор бюллетеней опубликован.
-   Вер. 1.1 (9 июля 2013 г.): Для MS13-055 изменена оценка использования уязвимости в **Индексе использования уязвимостей** для CVE-2013-3163. Специалистам Майкрософт известно о направленных атаках с целью использования этой уязвимости через Internet Explorer 8. Это изменение носит исключительно информационный характер.
-   Вер. 2.0 (13 августа 2013 г.): Для MS13-052 выпущена новая версия бюллетеня, чтобы предложить новую версию обновлений 2840628, 2840632, 2840642, 2844285, 2844286, 2844287 и 2844289. Для MS13-057 выпущена новая версия бюллетеня, чтобы предложить новую версию обновления 2803821 для Windows 7 и Windows 2008 R2. Пользователи должны установить повторно выпущенные обновления, применимые к их системам. Подробнее см. в соответствующих бюллетенях.
-   Вер. 3.0 (27 августа 2013 г.): Для MS13-057 выпущена новая версия бюллетеня, чтобы предложить новые версии обновлений для системы безопасности: 2803821 для Windows XP, Windows Server 2003, Windows Vista и Windows Server 2008; 2834902 для Windows XP и Windows Server 2003; 2834903 для Windows XP; 2834904 для Windows XP и Windows Server 2003; и 2834905 для Windows XP. Пользователи Windows XP, Windows Server 2003, Windows Vista и Windows Server 2008 должны установить повторно выпущенные обновления, применимые к их системам. Подробнее см. в бюллетене.

*Built at 2014-04-18T01:50:00Z-07:00*
