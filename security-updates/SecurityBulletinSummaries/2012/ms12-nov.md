---
TOCTitle: 'MS12-NOV'
Title: 'Обзор бюллетеней по безопасности Майкрософт за ноябрь 2012 года.'
ms:assetid: 'ms12-nov'
ms:contentKeyID: 61236164
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms12-nov(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности Майкрософт за ноябрь 2012 года.
================================================================

Дата публикации: 13 ноября 2012 г. | Дата обновления: 14 ноября 2012 г.

**Версия:** 2.0

В этом обзоре перечислены бюллетени по безопасности, выпущенные в ноябре 2012 года.

После выпуска бюллетеней за ноябрь 2012 года этот обзор заменит предварительное уведомление, выпущенное 8 ноября 2012 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

14 ноября 2012 года в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в ноябрьской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522560&culture=en-us). После наступления этой даты данная веб-трансляция будет доступна [по запросу](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522560&culture=en-us).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=268299">MS12-071</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление системы безопасности для браузера Internet Explorer (2761451)<br />
<br />
</strong>Это обновление для системы безопасности устраняет три обнаруженных пользователями уязвимости в браузере Internet Explorer. Эти уязвимости делают возможным удаленное выполнение кода при открытии специально созданной веб-страницы в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=260820">MS12-072</a></td>
<td style="border:1px solid black;"><strong>Уязвимости оболочки Windows делают возможным удаленное выполнение кода (2727528)</strong> <strong><br />
<br />
</strong>Это обновление для системы безопасности устраняет две обнаруженных пользователями уязвимости в Microsoft Windows. Данные уязвимости делают возможным удаленное выполнение кода, если пользователь просматривает в Проводнике Windows специально созданный портфель. Воспользовавшись ею, злоумышленник может выполнить произвольный код как текущий пользователь. Если пользователь вошел в систему с правами администратора, злоумышленник может получить полный контроль над уязвимой системой. После этого злоумышленник сможет устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными правами. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255026">MS12-074</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в .NET Framework делают возможным удаленное выполнение кода (2745030)</strong> <strong><br />
<br />
</strong>Настоящее обновление для системы безопасности устраняет пять обнаруженных пользователями уязвимостей в .NET Framework. Наиболее серьезная из этих уязвимостей делает возможным удаленное выполнение кода, если злоумышленник убедит пользователя целевой системы воспользоваться вредоносным файлом автонастройки прокси-сервера, а затем внесет код в выполняемое в данный момент приложение.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=270856">MS12-075</a></td>
<td style="border:1px solid black;"><strong>Уязвимости драйверов режима ядра Windows делают возможным удаленное выполнение кода (2761226)</strong> <strong><br />
<br />
</strong>Это обновление для системы безопасности устраняет три обнаруженных пользователями уязвимости в Microsoft Windows. Эти уязвимости делают возможным удаленное выполнение кода, если пользователь откроет специально созданный документ или посетит вредоносную веб-страницу с внедренными файлами шрифтов TrueType. Злоумышленник должен будет убедить пользователей посетить веб-сайт, обычно приглашая их перейти по соответствующей ссылке, ведущей на этот веб-сайт, в сообщении электронной почты.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=260964">MS12-076</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Excel делают возможным удаленное выполнение кода (2720184)</strong> <strong><br />
<br />
</strong>Это обновление для системы безопасности устраняет четыре обнаруженных пользователями уязвимости в Microsoft Office. Эти уязвимости делают возможным удаленное выполнение кода в случае, если пользователь откроет особым образом созданный файл Excel в уязвимой версии Microsoft Excel. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=258247">MS12-073</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Internet Information Services (IIS) могут привести к раскрытию информации (2733829)<br />
<br />
</strong>Это обновление для системы безопасности устраняет одну открыто опубликованную и одну обнаруженную пользователями уязвимость в службах Microsoft IIS. Более серьезная из этих уязвимостей может привести к раскрытию информации, если злоумышленник отправит серверу специально созданные команды FTP.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Средний</a><br />
Раскрытие информации</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
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
  
| Идентификатор бюллетеня                                   | Название уязвимости                                                                    | Код CVE                                                                          | Оценка возможности использования уязвимостей для последнего выпуска программного обеспечения           | Оценка возможности использования уязвимостей для более старых выпусков программного обеспечения            | Оценка использования уязвимости типа "отказ в обслуживании" | Краткие примечания                                       |  
|-----------------------------------------------------------|----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|----------------------------------------------------------|  
| [MS12-071](http://go.microsoft.com/fwlink/?linkid=268299) | Уязвимость, связанная с использованием CFormElement после освобождения                 | [CVE-2012-1538](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1538) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | Не применимо                                                | (Нет)                                                    |  
| [MS12-071](http://go.microsoft.com/fwlink/?linkid=268299) | Уязвимость, связанная с использованием CTreePos после освобождения                     | [CVE-2012-1539](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1539) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | Временный                                                   | (Нет)                                                    |  
| [MS12-071](http://go.microsoft.com/fwlink/?linkid=268299) | Уязвимость, связанная с использованием CTreeNode после освобождения                    | [CVE-2012-4775](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4775) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | Не применимо                                                | (Нет)                                                    |  
| [MS12-072](http://go.microsoft.com/fwlink/?linkid=260820) | Уязвимость портфеля Windows, связанная с потерей точности целых чисел                  | [CVE-2012-1527](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1527) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | Не применимо                                                | (Нет)                                                    |  
| [MS12-072](http://go.microsoft.com/fwlink/?linkid=260820) | Уязвимость портфеля Windows, связанная с переполнением целочисленного значения         | [CVE-2012-1528](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1528) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | Временный                                                   | (Нет)                                                    |  
| [MS12-074](http://go.microsoft.com/fwlink/?linkid=255026) | Уязвимость, связанная с обходом отражения                                              | [CVE-2012-1895](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1895) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | Не применимо                                                | (Нет)                                                    |  
| [MS12-074](http://go.microsoft.com/fwlink/?linkid=255026) | Уязвимость разграничения доступа кода, приводящая к раскрытию информации               | [CVE-2012-1896](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1896) | Не подвержены уязвимости                                                                               | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) — существование кода эксплойта маловероятно | Не применимо                                                | Это уязвимость, делающая возможным раскрытие информации. |  
| [MS12-074](http://go.microsoft.com/fwlink/?linkid=255026) | Уязвимость .NET Framework, связанная с небезопасной загрузкой библиотек                | [CVE-2012-2519](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2519) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | Не применимо                                                | (Нет)                                                    |  
| [MS12-074](http://go.microsoft.com/fwlink/?linkid=255026) | Уязвимость автообнаружения веб-прокси                                                  | [CVE-2012-4776](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4776) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | Перманентное                                                | (Нет)                                                    |  
| [MS12-074](http://go.microsoft.com/fwlink/?linkid=255026) | Уязвимость оптимизации отражения в WPF                                                 | [CVE-2012-4777](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4777) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | Не применимо                                                | (Нет)                                                    |  
| [MS12-075](http://go.microsoft.com/fwlink/?linkid=270856) | Уязвимость Win32k, связанная с использованием протокола после освобождения             | [CVE-2012-2530](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2530) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | Перманентное                                                | (Нет)                                                    |  
| [MS12-075](http://go.microsoft.com/fwlink/?linkid=270856) | Уязвимость Win32k, связанная с использованием протокола после освобождения             | [CVE-2012-2553](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2553) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | Перманентное                                                | (Нет)                                                    |  
| [MS12-075](http://go.microsoft.com/fwlink/?linkid=270856) | Уязвимость, связанная с анализом шрифтов TrueType                                      | [CVE-2012-2897](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2897) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) — код эксплойта создать сложно          | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) — код эксплойта создать сложно              | Перманентное                                                | (Нет)                                                    |  
| [MS12-076](http://go.microsoft.com/fwlink/?linkid=260964) | Уязвимость Excel, связанная с переполнением кучи SerAuxErrBar                          | [CVE-2012-1885](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1885) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | Не применимо                                                | (Нет)                                                    |  
| [MS12-076](http://go.microsoft.com/fwlink/?linkid=260964) | Уязвимость Excel, приводящая к повреждению памяти                                      | [CVE-2012-1886](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1886) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | Не применимо                                                | (Нет)                                                    |  
| [MS12-076](http://go.microsoft.com/fwlink/?linkid=260964) | Уязвимость Excel, связанная с использованием недопустимой длины SST после освобождения | [CVE-2012-1887](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1887) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | Не применимо                                                | (Нет)                                                    |  
| [MS12-076](http://go.microsoft.com/fwlink/?linkid=260964) | Уязвимость Excel, связанная с переполнением стека                                      | [CVE-2012-2543](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2543) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта     | Не применимо                                                | (Нет)                                                    |
  
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
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-071**](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://go.microsoft.com/fwlink/?linkid=266541)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Не применимо
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=fcc633d6-fe18-4220-9b68-ff1479e4dec5)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=f5472e86-2b2f-42bd-abca-6adf84973efa)  
(KB2698035)  
(только Media Center Edition 2005 с пакетом обновления 3 (SP3) и Tablet PC Edition 2005 с пакетом обновления 3 (SP3))  
(существенный)  
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=31f2c645-b171-4f11-884b-f5056ef57b4f)  
(KB2761226)  
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
Не применимо
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a736c3f0-0326-4a0a-9c12-f61bafa537bb)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=828699ac-eb88-4ff8-9110-69c206f5ef54)  
(KB2761226)  
(критический)
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
[**MS12-071**](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://go.microsoft.com/fwlink/?linkid=266541)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0383bdea-53d1-4799-b380-14da1595882a)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=efe0de22-8ca3-474e-acda-7203bf66d0a3)  
(KB2698032)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=73f5dec6-ccda-426d-8d2c-a2db3e59734a)  
(KB2761226)  
(критический)
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
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=615a96fe-88a5-498b-ae20-bbfc43e3b652)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=dc9cd62a-c42d-4c54-bc14-7abd34aeb865)  
(KB2761226)  
(критический)
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
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=36962e96-0eaa-45a9-b2d6-6bec3242c73e)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e4ec19ea-06f2-4164-8e39-84f1d7a47ae7)  
(KB2761226)  
(критический)
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
[**MS12-071**](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://go.microsoft.com/fwlink/?linkid=266541)
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=205f1cf3-5431-4740-96c2-eaf019edeeeb)  
(KB2761451)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c19585e3-a358-40b0-80a3-8dbb25ba8557)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c4b3fb44-338d-48be-9981-53fa2cf3094a)  
(KB2761226)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP Service 7.0 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=e1785af2-a211-467e-a696-d53840581bca)<sup>[1]</sup>
(KB2716513)  
(средний)  
[Служба Microsoft FTP 7.5 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=b91091d0-176f-4ff9-98d2-74768b747c3a)<sup>[1]</sup>
(KB2716513)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7e7b681c-c580-4671-a515-e5b469002c93)  
(KB2761451)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=31f5ad28-ffe9-4370-b3fc-62eb9fc0c4dd)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7a58e874-f3fc-4db8-8de0-cbfc6ebbf349)  
(KB2761226)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP Service 7.0 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=2db93767-f364-49c6-9a03-39604173771f)<sup>[1]</sup>
(KB2716513)  
(средний)  
[Служба Microsoft FTP 7.5 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=0c499445-595f-459f-86cf-b821cbb5fa65)<sup>[1]</sup>
(KB2716513)  
(средний)
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
[**MS12-071**](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://go.microsoft.com/fwlink/?linkid=266541)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=0161baaa-5d7b-4442-a202-41c64a73c9a8)  
(KB2761451)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=258048b5-d992-4821-8836-72262a7b5bb7)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=17b987db-0551-45c3-aab1-0cc11ae60dcc)  
(KB2761226)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP Service 7.0 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=cb3598ae-b647-4aaa-90fb-b4d8aa1cf211)<sup>[1]</sup>
(KB2716513)  
(средний)  
[Служба Microsoft FTP 7.5 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=8b135d6f-0f6c-4bd5-bf64-d79ae16ac6a5)<sup>[1]</sup>
(KB2716513)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=52f652bd-edc4-4450-91b4-f19401d2201c)  
(KB2761451)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=1c067cb2-71a5-4f8d-9b11-243c9e5318ce)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=dd9bd994-41e3-46a1-9dfb-c6d89a3ef883)  
(KB2761226)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP Service 7.0 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=74d130a4-f42a-48af-87fc-349a1e107529)<sup>[1]</sup>
(KB2716513)  
(средний)  
[Служба Microsoft FTP 7.5 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=b061a0b0-66e2-49a2-8d20-0c5a6948aecf)<sup>[1]</sup>
(KB2716513)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
(существенный)  
[Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=fab87b20-398f-4043-9cbe-ffcae8e19ff0)  
(KB2761226)  
(критический)
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
[**MS12-071**](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://go.microsoft.com/fwlink/?linkid=266541)
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=279ac887-2420-48d7-bb85-c7cab49f7ff8)  
(KB2761451)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=22ab8987-2506-433f-9f12-0ab60d569949)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=c222943e-9888-4fb9-b9a2-7a035311c887)  
(KB2761226)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.5 для IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=77a4ae4e-a75c-490a-a0b1-137816ed5c89)  
(KB2716513)  
(средний)  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=fb265aa5-0e09-411a-a0fe-bbb42c409a81)  
(KB2719033)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=279ac887-2420-48d7-bb85-c7cab49f7ff8)  
(KB2761451)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=22ab8987-2506-433f-9f12-0ab60d569949)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c222943e-9888-4fb9-b9a2-7a035311c887)  
(KB2761226)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.5 для IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=77a4ae4e-a75c-490a-a0b1-137816ed5c89)  
(KB2716513)  
(средний)  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=fb265aa5-0e09-411a-a0fe-bbb42c409a81)  
(KB2719033)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=eb9babdc-3fac-4ce9-a7ca-85e26a9cb11d)  
(KB2761451)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=fc70708e-9de9-4618-b0ab-d9aa3e2baea0)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=50d7c25f-a67f-4946-b6db-70d9bd4dc178)  
(KB2761226)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.5 для IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=bda21ea5-f160-4361-8ede-40f6a53a30da)  
(KB2716513)  
(средний)  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=52b6ed39-b7c1-4d49-a6a7-e6208fab24fa)  
(KB2719033)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=eb9babdc-3fac-4ce9-a7ca-85e26a9cb11d)  
(KB2761451)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=fc70708e-9de9-4618-b0ab-d9aa3e2baea0)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=50d7c25f-a67f-4946-b6db-70d9bd4dc178)  
(KB2761226)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.5 для IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=bda21ea5-f160-4361-8ede-40f6a53a30da)  
(KB2716513)  
(средний)  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=52b6ed39-b7c1-4d49-a6a7-e6208fab24fa)  
(KB2719033)  
(средний)
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
[**MS12-071**](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://go.microsoft.com/fwlink/?linkid=266541)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=3d0a4455-b788-4ad7-be0c-5824f6103694)  
(KB2761451)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=800cd622-d271-41a4-bd21-a76177d2b272)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30)  
(KB2761226)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.5 для IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
(средний)  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=3d0a4455-b788-4ad7-be0c-5824f6103694)  
(KB2761451)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=800cd622-d271-41a4-bd21-a76177d2b272)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30)  
(KB2761226)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.5 для IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
(средний)  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=70447115-957d-48a4-bc27-395abaf22149)  
(KB2761226)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.5 для IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=92cd0488-03c2-400d-a506-eb2eb8fce7c7)  
(KB2716513)  
(средний)  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=1eea7e7f-83bf-40fc-a978-a4d08af8162a)  
(KB2719033)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=70447115-957d-48a4-bc27-395abaf22149)  
(KB2761226)  
(критический)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.5 для IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=92cd0488-03c2-400d-a506-eb2eb8fce7c7)  
(KB2716513)  
(средний)  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=1eea7e7f-83bf-40fc-a978-a4d08af8162a)  
(KB2719033)  
(средний)
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
[**MS12-071**](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://go.microsoft.com/fwlink/?linkid=266541)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 8 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=d7c93ade-f7e3-4b6f-b93d-894ca313282f)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
(критический)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=b120a7a2-0eff-41d6-981e-60e5ecd55869)<sup>[2]</sup>
(KB2756872)  
(уровень опасности не определен)
</td>
<td style="border:1px solid black;">
[Windows 8 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=24ce3f78-fb25-4f51-8bb0-8cebf19d8843)  
(KB2761226)  
(критический)
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
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 8 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=7c4a17b7-bb7f-456c-9cb3-3a355e192734)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
(критический)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=c7a417e6-72e5-4087-bb89-fb8e7f57894c)<sup>[2]</sup>
(KB2756872)  
(уровень опасности не определен)
</td>
<td style="border:1px solid black;">
[Windows 8 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=72c49d94-757c-4a4-a895-96efe0830ad667)  
(KB2761226)  
(критический)
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
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-071**](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://go.microsoft.com/fwlink/?linkid=266541)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=ad6189ae-9341-409b-a53e-486fef094fd0)  
(KB2727528)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
(критический)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=0a7da3d1-a0ac-42a2-9929-b6d831deb9e3)<sup>[2]</sup>
(KB2756872)  
(уровень опасности не определен)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=2e69d496-25b4-4f24-97e0-47cb59c178aa)  
(KB2761226)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
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
[**MS12-071**](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://go.microsoft.com/fwlink/?linkid=266541)
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
**Нет**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)****
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)****
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
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5<sup>[3]</sup>
(KB2737084)  
(существенный)  
Microsoft .NET Framework 4.5<sup>[2]</sup><sup>[3]</sup>
(KB2756872)  
(уровень опасности не определен)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2761226)  
(критический)
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
[**MS12-071**](http://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](http://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](http://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](http://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](http://go.microsoft.com/fwlink/?linkid=266541)
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
**Нет**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=17b987db-0551-45c3-aab1-0cc11ae60dcc) (установка основных серверных компонентов)  
(KB2761226)  
(существенный)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP Service 7.0 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=cb3598ae-b647-4aaa-90fb-b4d8aa1cf211)<sup>[1]</sup>
(KB2716513)  
(средний)  
[Служба Microsoft FTP 7.5 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=8b135d6f-0f6c-4bd5-bf64-d79ae16ac6a5)<sup>[1]</sup>
(KB2716513)  
(средний)
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
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=dd9bd994-41e3-46a1-9dfb-c6d89a3ef883) (установка основных серверных компонентов)  
(KB2761226)  
(существенный)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP Service 7.0 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=74d130a4-f42a-48af-87fc-349a1e107529)<sup>[1]</sup>
(KB2716513)  
(средний)  
[Служба Microsoft FTP 7.5 для IIS 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=b061a0b0-66e2-49a2-8d20-0c5a6948aecf)<sup>[1]</sup>
(KB2716513)  
(средний)
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
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30) (установка основных серверных компонентов)  
(KB2761226)  
(существенный)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.5 для IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
(средний)  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
(средний)
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
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>
(KB2729449)  
(критический)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
(критический)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>
(KB2737019)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30) (установка основных серверных компонентов)  
(KB2761226)  
(существенный)
</td>
<td style="border:1px solid black;">
[Служба Microsoft FTP 7.5 для IIS 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
(средний)  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
(средний)
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
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
(критический)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
(существенный)  
[Microsoft .NET Framework 4.5](http://www.microsoft.com/downloads/details.aspx?familyid=0a7da3d1-a0ac-42a2-9929-b6d831deb9e3)<sup>[2]</sup>
(KB2756872)  
(уровень опасности не определен)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=2e69d496-25b4-4f24-97e0-47cb59c178aa) (установка основных серверных компонентов)  
(KB2761226)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 
**Примечание** **к бюллетеню MS12-073**

<sup>[1]</sup>Не является службой FTP по умолчанию для данной операционной системы.

**Примечания к бюллетеню MS12-074**

<sup>[1]</sup>**Уязвимости подвержены NET Framework 4 и клиентский профиль .NET Framework 4** Предлагаются два профиля для распространяемых пакетов .NET Framework версии 4: .NET Framework 4 и клиентский профиль .NET Framework 4. Клиентский профиль .NET Framework 4 является частью .NET Framework 4. Уязвимости, устраняемой данным обновлением, подвержены как платформа .NET Framework 4, так и клиентский профиль .NET Framework 4. Дополнительные сведения см. в статье MSDN [Установка .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

<sup>[2]</sup>Пользователи Microsoft .NET Framework 4.5 в Windows 8, Windows Server 2012 и Windows RT не подвержены данной проблеме. Накопительное обновление для клиентских систем Windows 8 и серверных систем Windows Server 2012 (KB2756872), выпущенное 10 октября 2012 года,включает дополнительные изменения для обеспечения многоуровневой защиты. Пользователя, которые еще не установили данное обновление, рекомендуется сделать это в качестве дополнительной меры защиты. Более подробные сведения см. в разделе "Дополнительные сведения" [статьи 2745030 базы знаний Майкрософт](http://support.microsoft.com/kb/2745030). Для получения дополнительной информации и ссылок для загрузки см. [статью базы знаний Майкрософт 2756872](http://support.microsoft.com/kb/2756872). Обратите внимание, что данное обновление содержит информацию, не относящуюся к системе безопасности.

<sup>[3]</sup>Обновления системы безопасности для Windows RT предоставляются только через [Центр обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130).

**Примечание** **к бюллетеню MS12-075**

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
[**MS12-076**](http://go.microsoft.com/fwlink/?linkid=260964)
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
[Microsoft Excel 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=5bb12b2b-a8e2-4324-afee-e4d26dbc658f)  
(KB2687481)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e12aafe1-4445-4047-ad05-3db151a6fa4e)<sup>[1]</sup>
(KB2687307)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=e12aafe1-4445-4047-ad05-3db151a6fa4e)<sup>[1]</sup>
(KB2687307)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=37a1074d-bf4f-4b96-b394-1edc581748d0)  
(KB2597126)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=5db02eae-966e-41a9-8b64-ddda5f8b2e2a)  
(KB2597126)  
(существенный)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office для Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS12-076**](http://go.microsoft.com/fwlink/?linkid=260964)
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
Microsoft Office 2008 для Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=d3d801a2-d57f-4b4c-970a-c296bc716521)  
(KB2764048)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office для Mac 2011
</td>
<td style="border:1px solid black;">
[Microsoft Office для Mac 2011](http://www.microsoft.com/downloads/details.aspx?familyid=0f4e073f-4fec-440d-a9bf-1e01ee9e92ad)  
(KB2764047)  
(существенный)
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
[**MS12-076**](http://go.microsoft.com/fwlink/?linkid=260964)
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
Средство просмотра Microsoft Excel
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=a0917aeb-1e94-4142-bc20-5f1998ac249c)<sup>[2]</sup>
(KB2687313)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=79686714-9418-4516-81c3-555fe1ea9e84)  
(KB2687311)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Пакет обеспечения совместимости для Microsoft Office с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=79686714-9418-4516-81c3-555fe1ea9e84)  
(KB2687311)  
(существенный)
</td>
</tr>
</table>
 
**Примечания** **к бюллетеню MS12-076**

<sup>[1]</sup> В дополнение к пакету обновления системы безопасности KB2687307 для Microsoft Excel 2007 для обеспечения защиты от уязвимостей, описанных в данном бюллетене, пользователям необходимо установить обновление безопасности для пакета обеспечения совместимости Microsoft Office (KB2687311).

<sup>[2]</sup>Перед установкой данного обновления безопасности необходимо обновить Microsoft Excel Viewer до уровня поддерживаемого пакета обновления (пакет обновления 2 (SP2) для Excel Viewer 2007 или пакет обновления 3 (SP3) для Excel Viewer 2007). Дополнительные сведения о поддерживаемых программах просмотра Office см. [в статье 979860 базы знаний Майкрософт](http://support.microsoft.com/kb/979860).

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

-   Хосе А. Васкеса (Jose A. Vazquez) из spa-s3c.blogspot.com, сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение о двух уязвимостях, описанных в MS12-071
-   [Omair](http://krash.in/) за сообщение об уязвимости, описанной в MS12-071
-   Чен-да Цай (Cheng-da Tsai (Orange)), Сунг-тин Цай (Sung-ting Tsai) и Мин-чен Пан (Ming-chieh Pan, Nanika) из [Trend Micro](http://www.trendmicro.com/) за сообщение об уязвимости, описанной в MS12-071
-   Тал Зельцера (Tal Zeltzer), сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение о двух уязвимостях, описанных в MS12-072
-   Джастина Ройса (Justin Royce) из компании ProDX за сообщение об уязвимости, описанной в MS12-073
-   Джеймса Форшо (James Forshaw) из компании Context Information Security за сообщение о четырех уязвимостях, описанных в MS12-074
-   [Матеуша "j00ru" Юрчук (Mateusz "j00ru" Jurczyk)](http://j00ru.vexillium.org/) из компании [Google Inc.](http://www.google.com) за сообщение об уязвимости, описанной в бюллетене MS12-075
-   Иту Люодема (Eetu Luodemaa) и Джони Вахамаки (Joni Vähämäki) из компании [Documill](http://www.documill.com) за сообщение об уязвимости, описанной в MS12-075
-   Шона Ларссона (Sean Larsson), сотрудничающего с компанией [iDefense VCP](http://labs.idefense.com), за сообщение об уязвимости, описанной в MS12-076
-   Анонимного исследователя, сотрудничающего с компанией [iDefense VCP](http://labs.idefense.com), за сообщение об уязвимости, описанной в MS12-076
-   Анонимного исследователя, сотрудничающего с компанией [iDefense VCP](http://labs.idefense.com), за сообщение об уязвимости, описанной в MS12-076
-   Анонимного исследователя, сотрудничающего с [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости, описанной в MS12-076

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617.aspx)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (13 ноября 2012 г.): Обзор бюллетеней опубликован.
-   Вер. 1.1 (13 ноября 2012 г.): В бюллетене MS12-075 испавлен заголовок записи CVE и запись "Оценка использования уязвимости типа "отказ в обслуживании" в **Индексе использования уязвимостей** для CVE-2012-2897.
-   Вер. 2.0 (14 ноября 2012 г.): В бюллетене MS12-073 внесены изменения в раздел "Обзор бюллетеней". Добавлена информация о том, что обновление KB2716513 для Windows Vista и Windows Server 2008 теперь доступно через все каналы распространения, включая Центр обновления Windows и Центр обновления Microsoft. Дополнительные сведения см. в бюллетене MS12-073.

*Built at 2014-04-18T01:50:00Z-07:00*
