---
TOCTitle: 'MS13-MAR'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за март 2013 года'
ms:assetid: 'ms13-mar'
ms:contentKeyID: 61236174
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms13-mar(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за март 2013 года
===============================================================

Дата публикации: 12 марта 2013 г. | Дата обновления: 15 марта 2013 г.

**Версия:** 1.1

В этот обзор включены бюллетени по безопасности, выпущенные в марте 2013 года.

После выпуска бюллетеней за март 2013 года этот обзор заменит предварительное уведомление, выпущенное 7 марта 2013 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

13 марта 2013 года в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проводит веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в мартовской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538636&culture=en-us). После наступления этой даты данная веб-трансляция будет доступна [по запросу](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538636&culture=en-us).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=279923">MS13-021</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (2809289)<br />
<br />
</strong>Это обновление для системы безопасности устраняет восемь обнаруженных пользователями и одну опубликованную уязвимость в браузере Internet Explorer. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь просмотрит особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275737">MS13-022</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Silverlight делает возможным удаленное выполнение кода (2814124)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Silverlight. Эта уязвимость делает возможным удаленное выполнение кода, если злоумышленник разместит веб-сайт со специально созданным приложением Silverlight, способным использовать эту уязвимость, и убедит пользователя посетить веб-сайт. Кроме того, он может воспользоваться уязвимостью через веб-сайты, которые уже подверглись атаке, и веб-сайты, которые принимают или размещают сведения или рекламу. Такие веб-сайты могут включать специальное содержимое, использующее данную уязвимость. В любом случае злоумышленник не может заставить пользователей посетить такой веб-сайт. Вместо этого злоумышленник должен склонить пользователей к посещению веб-сайта, как правило, убеждая их щелкнуть ссылку в сообщении электронной почты или программы обмена мгновенными сообщениями. Специально созданное веб-содержимое можно также отобразить и передать на уязвимые системы посредством рекламных объявлений или иными способами.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Перезагрузка не требуется</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=276801">MS13-023</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Visio Viewer 2010 делает возможным удаленное выполнение кода (2801261)<br />
<br />
</strong>Это обновление для системы безопасности устраняет уязвимость в пакете Microsoft Office, о которой сообщалось в частном порядке. Эта уязвимость делает возможным удаленное выполнение кода при открытии пользователем особым образом созданного файла Visio. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271610">MS13-024</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в SharePoint делают возможным несанкционированное получение прав (2780176)<br />
<br />
</strong>Это обновление для системы безопасности устраняет четыре обнаруженные пользователями уязвимости в Microsoft SharePoint и Microsoft SharePoint Foundation. Наиболее серьезные уязвимости делают возможным несанкционированное получение прав, если пользователь переходит по специально созданному URL-адресу, ведущему на целевой сайт SharePoint.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office, серверное программное обеспечение Майкрософт</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=282355">MS13-025</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft OneNote может привести к раскрытию информации (2816264)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft OneNote. Уязвимость делает возможным раскрытие информации, если злоумышленник убедит пользователя открыть специально созданный файл OneNote.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Раскрытие информации</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=280673">MS13-026</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в</strong> <strong>Microsoft Office</strong> <strong>для Mac может привести к раскрытию информации (2813682)<br />
<br />
</strong>Это обновление для системы безопасности устраняет одну обнаруженную пользователями уязвимость в Microsoft Office для Mac. Данная уязвимость может привести к раскрытию информации, если пользователь открывает специально созданное сообщение электронной почты.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Раскрытие информации</td>
<td style="border:1px solid black;">Перезагрузка не требуется</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=282639">MS13-027</a></td>
<td style="border:1px solid black;"><strong>Уязвимости драйверов в режиме ядра делают возможным несанкционированное получение прав (2807986)</strong> <strong><br />
<br />
</strong>Это обновление для системы безопасности устраняет три обнаруженных пользователями уязвимости в Microsoft Windows. Данные уязвимости делают возможным несанкционированное получение прав, если злоумышленник получает доступ к системе.</td>
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
  
Используйте эту таблицу, чтобы узнать о вероятности появления эксплойтов для выполнения произвольного кода и DoS-атаки в течение 30 дней после выпуска бюллетеня по каждому из обновлений безопасности, которые необходимо установить. Чтобы назначить приоритеты развертывания, ознакомьтесь с приведенными ниже оценками в соответствии с вашей конфигурацией. Дополнительные сведения об уровнях опасности и способах их определения см. в [индексе использования уязвимостей](http://technet.microsoft.com/security/cc998259).
  
В приведенной ниже таблице "последний выпуск программного обеспечения" обозначает соответствующее программное обеспечение, а термином "старые выпуски программного обеспечения" обозначены все прежние поддерживаемые выпуски программного обеспечения, указанные в таблице "Подвержены уязвимости" или "Не подвержены уязвимости" в этом бюллетене.
  
| Идентификатор бюллетеня                                   | Название уязвимости                                                                                | Код CVE                                                                          | Оценка возможности использования уязвимостей для последнего выпуска программного обеспечения           | Оценка возможности использования уязвимостей для более старых выпусков программного обеспечения        | Оценка использования уязвимости типа "отказ в обслуживании" | Краткие примечания                                                 |  
|-----------------------------------------------------------|----------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|--------------------------------------------------------------------|  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Уязвимость Internet Explorer, связанная с использованием OnResize после освобождения               | [CVE-2013-0087](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0087) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                              |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Уязвимость Internet Explorer, связанная с использованием saveHistory после освобождения            | [CVE-2013-0088](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0088) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                              |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Уязвимость Internet Explorer, связанная с использованием CMarkupBehaviorContext после освобождения | [CVE-2013-0089](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0089) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                              |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Уязвимость Internet Explorer, связанная с использованием CCaret после освобождения                 | [CVE-2013-0090](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0090) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) — код эксплойта создать сложно          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                              |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Уязвимость Internet Explorer, связанная с использованием CElement после освобождения               | [CVE-2013-0091](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0091) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                              |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Уязвимость Internet Explorer, связанная с использованием GetMarkupPtr после освобождения           | [CVE-2013-0092](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0092) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                              |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Уязвимость Internet Explorer, связанная с использованием onBeforeCopy после освобождения           | [CVE-2013-0093](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0093) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                              |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Уязвимость Internet Explorer, связанная с использованием removeChild после освобождения            | [CVE-2013-0094](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0094) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                              |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Уязвимость Internet Explorer, связанная с использованием CTreeNode после освобождения              | [CVE-2013-1288](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1288) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | О данной уязвимости сообщалось в открытых источниках.              |  
| [MS13-022](http://go.microsoft.com/fwlink/?linkid=275737) | Уязвимость Silverlight, связанная с двойным разыменованием                                         | [CVE-2013-0074](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0074) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                                                           | Не применимо                                                | (Нет)                                                              |  
| [MS13-023](http://go.microsoft.com/fwlink/?linkid=276801) | Уязвимость, связанная с путаницей типов объектов в дереве Visio Viewer                             | [CVE-2013-0079](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0079) | Не подвержены уязвимости                                                                               | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) — код эксплойта создать сложно          | Не применимо                                                | (Нет)                                                              |  
| [MS13-024](http://go.microsoft.com/fwlink/?linkid=271610) | Уязвимость функции обратного вызова                                                                | [CVE-2013-0080](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0080) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                              |  
| [MS13-024](http://go.microsoft.com/fwlink/?linkid=271610) | Уязвимость SharePoint, приводящая к межсайтовому выполнению сценариев (XSS)                        | [CVE-2013-0083](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0083) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                              |  
| [MS13-024](http://go.microsoft.com/fwlink/?linkid=271610) | Уязвимость, связанная с обходом каталога SharePoint                                                | [CVE-2013-0084](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0084) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                              |  
| [MS13-024](http://go.microsoft.com/fwlink/?linkid=271610) | Уязвимость, связанная с переполнением буфера                                                       | [CVE-2013-0085](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0085) | Не подвержены уязвимости                                                                               | [3](http://technet.microsoft.com/security/cc998259) — существование кода эксплойта маловероятно        | Временный                                                   | Эта уязвимость делает возможной атаку типа "отказ в обслуживании". |  
| [MS13-025](http://go.microsoft.com/fwlink/?linkid=282355) | Уязвимость, связанная с проверкой размера буфера                                                   | [CVE-2013-0086](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0086) | Не подвержены уязвимости                                                                               | [3](http://technet.microsoft.com/security/cc998259) — существование кода эксплойта маловероятно        | Не применимо                                                | Это уязвимость, делающая возможным раскрытие информации.           |  
| [MS13-026](http://go.microsoft.com/fwlink/?linkid=280673) | Уязвимость, связанная с непреднамеренной загрузкой содержимого                                     | [CVE-2013-0095](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0095) | [3](http://technet.microsoft.com/security/cc998259) — существование кода эксплойта маловероятно        | [3](http://technet.microsoft.com/security/cc998259) — существование кода эксплойта маловероятно        | Не применимо                                                | Это уязвимость, делающая возможным раскрытие информации.           |  
| [MS13-027](http://go.microsoft.com/fwlink/?linkid=282639) | Уязвимость дескриптора Windows USB                                                                 | [CVE-2013-1285](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1285) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Перманентное                                                | (Нет)                                                              |  
| [MS13-027](http://go.microsoft.com/fwlink/?linkid=282639) | Уязвимость дескриптора Windows USB                                                                 | [CVE-2013-1286](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1286) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Перманентное                                                | (Нет)                                                              |  
| [MS13-027](http://go.microsoft.com/fwlink/?linkid=282639) | Уязвимость дескриптора Windows USB                                                                 | [CVE-2013-1287](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1287) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Перманентное                                                | (Нет)                                                              |
  
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
<th colspan="3">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=ace6994d-7482-40de-84ad-a87853a35860)  
(2809289)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=50c59794-4ec7-404a-b316-dae314521ebb)  
(2809289)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7e5d96a7-d9f5-4832-b4f9-b6e0148c655b)  
(2809289)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=ba528d03-b0a6-40a5-a6bd-13c062a8a877)  
(2807986)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=795cef4e-9c01-447f-916c-e52e69eca4a3)  
(2809289)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=16993a2c-1fe1-4c1e-bcd9-db1a7dd4a058)  
(2809289)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=66a08524-883d-4d67-82cc-2c0f55c56b31)  
(2809289)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4f8a48d4-b1bb-465c-a232-d29fe94d1429)  
(2807986)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=e3c911b3-7fdd-4105-a20a-eef65b0908e3)  
(2809289)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0f58d63e-0d2c-41d2-9792-edbb2f4a539d)  
(2809289)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e6b63da9-a414-40ee-b877-4fb0d62bacba)  
(2809289)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=835651b7-79fb-4d50-b48e-f02173062253)  
(2807986)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=eaf2c568-089a-4c2f-bca6-da83f7332de9)  
(2809289)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5a18b139-2773-44c8-85f9-8dce24249e71)  
(2809289)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d6feba92-f014-4521-b6c4-7f5f358a3ce3)  
(2809289)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=9d5f1ed1-f33b-4c90-9b29-ee8ac587d31b)  
(2807986)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=088fd3ec-62e1-4737-8132-6b51219ed37f)  
(2809289)  
(средний)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=799748d8-056d-4139-86e1-9bd0cb0151b4)  
(2809289)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=28d441e7-abcf-4cc9-84e0-572e5b79aab7)  
(2807986)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0bf77905-1199-4219-a67d-1e9ad3f63757)  
(2809289)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=76e328f8-4f86-4e50-b7e0-22db0385ab01)  
(2809289)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c26f74fc-e224-4533-a4e3-b52125dca5cd)  
(2809289)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b8472bc7-9e20-4238-adcf-a1e1a91687a1)  
(2807986)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=7b652bb4-7a0a-437b-bcc5-ebbbb820c559)  
(2809289)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=67b09398-ceb6-403c-bba4-261d9d9dea98)  
(2809289)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=3f1795a5-4376-4929-8748-743840ec2154)  
(2809289)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e412c54a-a93d-4c5b-9b13-40b59d1dff35)  
(2807986)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий** **уровень опасности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0303fcb1-34d5-47da-b6ee-18222fe3235a)  
(2809289)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=337068a5-9281-4db6-9ff1-5282cdfa0763)  
(2809289)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c672c196-5072-468c-8d88-34534fa219fd)  
(2809289)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=f1ca4fe0-3ee3-4162-a9fa-48c54fc8b08e)  
(2807986)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f22b9327-1430-44cb-a609-ea1bb9b7b8f8)  
(2809289)  
(средний)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0496cbfe-77d2-4de6-b78d-937225dc8974)  
(2809289)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=5c40f237-b4c8-41eb-a649-baad46dfa13c)  
(2809289)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=8b61f3e5-0cf9-4eab-8a59-829957135dd6)  
(2807986)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=09e4832c-b95e-4581-a73b-49cb6a60c1df)  
(2809289)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=af2e8e83-fb8f-4ba5-83ec-8bd4347a5fe6)  
(2807986)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b07b63d5-925d-4c4f-ae19-18a9b141eaa0)  
(2809289)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=54c619b7-e156-4f07-a90e-56ed9a618085)  
(2809289)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=c72f78be-e6a8-43b4-9303-7c93dd11d502)  
(2807986)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b07b63d5-925d-4c4f-ae19-18a9b141eaa0)  
(2809289)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=54c619b7-e156-4f07-a90e-56ed9a618085)  
(2809289)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c72f78be-e6a8-43b4-9303-7c93dd11d502)  
(2807986)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=610da6c6-e8a9-4726-ae54-11f01fb5ab2d)  
(2809289)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=86f2a369-d71d-4a36-95ed-d5be89cbbbae)  
(2809289)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=6a8a22d6-0e6e-4d3b-afd0-d4841274ade0)  
(2807986)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=610da6c6-e8a9-4726-ae54-11f01fb5ab2d)  
(2809289)  
(критический)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=86f2a369-d71d-4a36-95ed-d5be89cbbbae)  
(2809289)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=6a8a22d6-0e6e-4d3b-afd0-d4841274ade0)  
(2807986)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=cf5f65e1-93ae-4ec3-84d2-eb017efdc9d6)  
(2809289)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c5018865-7162-4d8d-86fc-aacd6d5f0a37)  
(2809289)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e)  
(2807986)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=cf5f65e1-93ae-4ec3-84d2-eb017efdc9d6)  
(2809289)  
(средний)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=c5018865-7162-4d8d-86fc-aacd6d5f0a37)  
(2809289)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e)  
(2807986)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=3436d1d1-bf20-40cc-8c51-f093da67c8a9)  
(2809289)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=01498cd0-e27e-4256-8f21-7a6eeedfb77c)  
(2807986)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=3436d1d1-bf20-40cc-8c51-f093da67c8a9)  
(2809289)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=01498cd0-e27e-4256-8f21-7a6eeedfb77c)  
(2807986)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=7c348fe3-f4f0-4f22-8a7f-8563705c1f64)  
(2809289)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 8 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=de4ec125-c337-4615-b39b-8456658dae22)  
(2807986)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=0c503b83-5b13-41da-a5ff-7519bc244521)  
(2809289)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 8 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=c1539e94-0635-4f51-8172-a96a737d81d3)  
(2807986)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/details.aspx?familyid=f9b299f1-8a73-40b2-9942-e6419496bb39)  
(2809289)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=959c78e1-29d9-40a3-9eb3-1206c09e3752)  
(2807986)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер** **бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10<sup>[1]</sup>
(2809289)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Вариант установки ядра сервера
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
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
[Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=f1ca4fe0-3ee3-4162-a9fa-48c54fc8b08e) (установка основных серверных компонентов)  
(2807986)  
(существенный)
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
[Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8b61f3e5-0cf9-4eab-8a59-829957135dd6) (установка основных серверных компонентов)  
(2807986)  
(существенный)
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
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e) (установка основных серверных компонентов)  
(2807986)  
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
[Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e) (установка основных серверных компонентов)  
(2807986)  
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
[Windows Server 2012](http://www.microsoft.com/downloads/details.aspx?familyid=959c78e1-29d9-40a3-9eb3-1206c09e3752) (установка основных серверных компонентов)  
(2807986)  
(существенный)
</td>
</tr>
</table>
 
**Примечание к бюллетеню MS13-021**

<sup>[1]</sup>Обновления для системы безопасности Windows RT предоставляются через [Центр обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130).

#### Пакеты приложений и программные продукты Microsoft Office

 
<table style="border:1px solid black;">
<tr>
<th colspan="4">
Программное обеспечение Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-023**](http://go.microsoft.com/fwlink/?linkid=276801)
</td>
<td style="border:1px solid black;">
[**MS13-025**](http://go.microsoft.com/fwlink/?linkid=282355)
</td>
<td style="border:1px solid black;">
[**MS13-026**](http://go.microsoft.com/fwlink/?linkid=280673)
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
Microsoft Visio Viewer 2010 с пакетом обновления 1 (SP1) (32-разрядная версия)
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 с пакетом обновления 1 (SP1) (32-разрядная версия)](http://www.microsoft.com/downloads/details.aspx?familyid=b01b4410-1107-472f-bf96-234304e91e77)  
(2687505)  
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
Microsoft Visio Viewer 2010 с пакетом обновления 1 (SP1) (64-разрядная версия)
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 с пакетом обновления 1 (SP1) (64-разрядная версия)](http://www.microsoft.com/downloads/details.aspx?familyid=24065dd5-251b-4a3c-bb44-8d552a1f265e)  
(2687505)  
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
Microsoft Visio 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=7a1a21e7-3137-4201-a005-cc66379fc1c5)  
(2760762)  
(Уровень опасности не определен)<sup>[1]</sup>
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
Microsoft Visio 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=7b7d39f0-a341-4d48-8177-329cccb5a7f1)  
(2760762)  
(Уровень опасности не определен)<sup>[1]</sup>
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
Пакет фильтров Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядная версия)
</td>
<td style="border:1px solid black;">
[Пакет фильтров Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядная версия)](http://www.microsoft.com/downloads/details.aspx?familyid=f10db48f-a980-47bf-83a5-c0da4e615114)  
(2553501)  
(Уровень опасности не определен)<sup>[1]</sup>
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
Пакет фильтров Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядная версия)
</td>
<td style="border:1px solid black;">
[Пакет фильтров Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядная версия)](http://www.microsoft.com/downloads/details.aspx?familyid=70d3372b-74a8-4b68-b6c4-18863835915d)  
(2553501)  
(Уровень опасности не определен)<sup>[1]</sup>
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
Microsoft OneNote 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft OneNote 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=da4bfd31-65b9-496b-aa98-4fa8b729dcf3)  
(2760600)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft OneNote 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft OneNote 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)](http://www.microsoft.com/downloads/details.aspx?familyid=10fc7350-e1d4-40b6-a5d1-8670263faf05)  
(2760600)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 для Mac
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=d7aef20a-922b-4495-b473-1afa4a7ac514)  
(2817449)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office для Mac 2011
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office для Mac 2011](http://www.microsoft.com/downloads/details.aspx?familyid=4960674b-1cb4-499a-999e-7aa4d4c49e5e)  
(2817452)  
(существенный)
</td>
</tr>
</table>
 
**Примечание к бюллетеню MS13-023**

<sup>[1]</sup>К данному обновлению не применяются уровни серьезности в отношении указанного программного обеспечения, поскольку известные направления атак с использованием данной уязвимости блокируются.

#### Программное обеспечение и средства разработки Microsoft

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-022**](http://go.microsoft.com/fwlink/?linkid=275737)
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
Microsoft Silverlight 5 при установке на Mac
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 5](http://www.microsoft.com/downloads/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9) при установке на Mac  
(2814124)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight 5 Developer Runtime при установке в Mac
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 5 Developer Runtime](http://www.microsoft.com/downloads/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9) при установке в Mac  
(2814124)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5 при установке на всех поддерживаемых выпусках клиентских систем Microsoft Windows
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 5](http://www.microsoft.com/downloads/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9) при установке на всех поддерживаемых выпусках клиентских систем Microsoft Windows  
(2814124)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight 5 Developer Runtime при установке во всех поддерживаемых выпусках клиентских систем Microsoft Windows
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 5 Developer Runtime](http://www.microsoft.com/downloads/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9) при установке во всех поддерживаемых выпусках клиентских систем Microsoft Windows  
(2814124)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5 при установке на всех поддерживаемых выпусках серверов Microsoft Windows
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 5](http://www.microsoft.com/downloads/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9) при установке на всех поддерживаемых выпусках серверов Microsoft Windows  
(2814124)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight 5 Developer Runtime при установке во всех поддерживаемых выпусках серверных систем Microsoft Windows
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 5 Developer Runtime](http://www.microsoft.com/downloads/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9) при установке во всех поддерживаемых выпусках серверных систем Microsoft Windows  
(2814124)  
(критический)
</td>
</tr>
</table>
 

#### Серверное программное обеспечение Майкрософт

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-024**](http://go.microsoft.com/fwlink/?linkid=271610)
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
Microsoft SharePoint Server 2010 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=a9e8acbd-90e5-4acd-aa8f-b743a352787b)<sup>[1]</sup>
(wasrv)  
(2553407)  
(критический)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Foundation
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-024**](http://go.microsoft.com/fwlink/?linkid=271610)
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
Microsoft SharePoint Foundation 2010 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=293666ec-3290-4c6f-a7f6-b44c9b7fa0a6)  
(2687418)  
(существенный)
</td>
</tr>
</table>
 
**Примечание к бюллетеню MS13-024**

<sup>[1]</sup>Для поддерживаемых выпусков Microsoft SharePoint Server 2010: чтобы обеспечить защиту от уязвимостей, описанных в данном бюллетене, помимо пакета обновления для Microsoft SharePoint 2010 (2553407) необходимо также установить обновление безопасности для Microsoft Windows SharePoint Foundation 2010 (2687418).

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

**MS13-021**

-   Арсения Акунева (Arseniy Akuney) из компании [TELUS Security Labs](http://telussecuritylabs.com/) за сообщение об уязвимости Internet Explorer, связанной с использованием OnResize после освобождения (CVE-2013-0087)
-   Анонимного исследователя, сотрудничающего с группой [Zero Day Initiative](http://www.zerodayinitiative.com/) компании [HP](http://www.hpenterprisesecurity.com/products) за сообщение об уязвимости Internet Explorer, связанной с использованием saveHistory после освобождения (CVE-2013-0088)
-   Анонимного исследователя, сотрудничающего с группой [Zero Day Initiative](http://www.zerodayinitiative.com/) компании [HP](http://www.hpenterprisesecurity.com/products) за сообщение об уязвимости Internet Explorer, связанной с использованием CMarkupBehaviorContext после освобождения (CVE-2013-0089)
-   Стивена Фьюера (Stephen Fewer) из [Harmony Security](http://www.harmonysecurity.com), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, связанной с использованием CCaret после освобождения (CVE-2013-0090)
-   Пользователя SkyLined, сотрудничающего с группой [Zero Day Initiative](http://www.zerodayinitiative.com/) компании [HP](http://www.hpenterprisesecurity.com/products) за сообщение об уязвимости Internet Explorer, связанной с использованием CCaret после освобождения (CVE-2013-0090)
-   Хосе А. Васкеса (Jose A. Vazquez) из Yenteasy Security Research, сотрудничающего с [Exodus Intelligence](https://www.exodusintel.com/), за сообщение об уязвимости Internet Explorer, связанной с использованием CElement после освобождения (CVE-2013-0091)
-   Пользователя [Aniway.Aniway@gmail.com](mailto:aniway.aniway@gmail.com), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, связанной с использованием GetMarkupPtr после освобождения (CVE-2013-0092)
-   Пользователя [Aniway.Aniway@gmail.com](mailto:aniway.aniway@gmail.com), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, связанной с использованием onBeforeCopy после освобождения (CVE-2013-0093)
-   Саймона Цукербрауна (Simon Zuckerbraun), сотрудничающего с группой [Zero Day Initiative](http://www.zerodayinitiative.com/) компании [HP](http://www.hpenterprisesecurity.com/products) за сообщение об уязвимости Internet Explorer, связанной с использованием removeChild после освобождения (CVE-2013-0094)
-   Ген Чена (Gen Chen) из компании [Venustech](http://www.venustech.com.cn/) ADLab за совместную работу над устранением уязвимости Internet Explorer, связанной с использованием CTreeNode после освобождения (CVE-2013-1288)
-   Сотрудников [Qihoo 360 Security Center](http://www.360.cn/) за совместную работу над устранением уязвимости Internet Explorer, связанной с использованием CTreeNode после освобождения (CVE-2013-1288)

**MS13-022**

-   Джеймса Форшоу (James Forshaw) из [Context Information Security](http://www.contextis.com/) за сообщение об уязвимости Silverlight, связанной с двойным разыменованием (CVE-2013-0074)

**MS13-023**

-   Пользователя [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com), сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости, связанной с путаницей типов объектов в дереве Visio Viewer (CVE-2013-0079)

**MS13-024**

-   Эмануэль Бронштейн (Emanuel Bronshtein) из компании [BugSec](http://www.bugsec.com/) за сообщение об уязвимости функции обратного вызова (CVE-2013-0080)
-   Сунила Ядава (Sunil Yadav) из компании INR Labs ([Network Intelligence India](http://niiconsulting.com/)) за сообщение об уязвимости SharePoint, приводящей к межсайтовому выполнению сценариев (CVE-2013-0083)
-   Морица Йодейта (Moritz Jodeit) из компании [n.runs AG](http://www.nruns.com/) за сообщение об уязвимости, связанной с обходом каталога SharePoint (CVE-2013-0084)

**MS13-025**

-   Кристофера Габриеля (Christopher Gabriel) из корпорации [Telos](http://www.telos.com) за сообщение об уязвимости, связанной с проверкой размера буфера (CVE-2013-0086)

**MS13-026**

-   [Ника Семенковича (Nick Semenkovich)](https://technet.microsoft.com/ru-RU/mailto:semenko@alum.mit.edu) за сообщение об уязвимости, связанной с непреднамеренной загрузкой содержимого (CVE-2013-0095)

**MS13-027**

-   Энди Девиса (Andy Davis) из NCC Group за сообщение об уязвимости дескриптора Windows USB (CVE-2013-1285)
-   Энди Девиса (Andy Davis) из NCC Group за сообщение об уязвимости дескриптора Windows USB (CVE-2013-1286)
-   Энди Девиса (Andy Davis) из NCC Group за сообщение об уязвимости дескриптора Windows USB (CVE-2013-1287)

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617.aspx)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (12 марта 2013 г.): Обзор бюллетеней опубликован.
-   Версия 1.1 (15 марта 2013 г.): Для MS13-026 исправлен заголовок бюллетеня в разделе **Аннотации**.

*Built at 2014-04-18T01:50:00Z-07:00*
