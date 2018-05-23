---
TOCTitle: 'MS09-MAY'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Май 2009 г.'
ms:assetid: 'ms09-may'
ms:contentKeyID: 61236127
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms09-may(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Май 2009 г.
==============================================================

Дата публикации: 12 мая 2009 г. | Дата обновления: 9 июня 2009 г.

**Версия:** 2.0

В этом обзоре описаны бюллетени по безопасности, выпущенные в мае 2009 г.

После выпуска майских бюллетеней данный обзор заменит предварительное уведомление, выпущенное 7 мая 2009 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [Предварительное уведомление о бюллетенях по безопасности Microsoft](http://technet.microsoft.com/security/bulletin/advance) (на английском языке).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней по безопасности Microsoft, см. на веб-узле [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

13 мая 2009 г. в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в майской веб-трансляции, посвященной бюллетеням по безопасности](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032395223). После наступления этой даты данная веб-трансляциия будет доступна по запросу. Дополнительные сведения см. на веб-узле [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://technet.microsoft.com/security/bulletin/summary) (на английском языке).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других важных обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел **Прочие сведения**.

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
<th style="border:1px solid black;" >Максимальный уровень опасности и воздействие уязвимости</th>
<th style="border:1px solid black;" >Необходимость перезагрузки</th>
<th style="border:1px solid black;" >Подвержены уязвимости</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Office PowerPoint делают возможным удаленное выполнение кода (967340)</strong><br />
<br />
Это обновление для системы безопасности устраняет уязвимость приложения Microsoft Office PowerPoint, о которой сообщалось в открытых источниках, и несколько уязвимостей, о которых сообщалось в частном порядке. Они делают возможным удаленное выполнение кода, если пользователь открывает специально созданный файл PowerPoint. Воспользовавшись некоторыми из этих уязвимостей, злоумышленник может получить полный контроль над уязвимой системой. что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Приложение Microsoft Office</td>
</tr>
</tbody>
</table>
  
Указатель использования уязвимости  
----------------------------------
  
<span></span>
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости сгруппированы по идентификаторам бюллетеней и кодам CVE.
  
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать о вероятности выпуска работающего кода использования уязвимости в течение 30 дней после выпуска бюллетеня по безопасности для каждого обновления для системы безопасности, которое потребуется установить. Перед назначением приоритетов развертывания ознакомьтесь с каждой приведенной ниже оценкой, относящейся к конкретной конфигурации. Дополнительные сведения об уровнях опасности и способах их определения см. в [указателе использования уязвимостей корпорации Майкрософт](http://technet.microsoft.com/en-us/security/cc998259.aspx).

 
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Идентификатор бюллетеня</th>
<th style="border:1px solid black;" >Название бюллетеня</th>
<th style="border:1px solid black;" >Код CVE</th>
<th style="border:1px solid black;" >Оценка указателя использования уязвимости</th>
<th style="border:1px solid black;" >Ключевые примечания</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office PowerPoint делают возможным удаленное выполнение кода (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0220">CVE-2009-0220</a></td>
<td style="border:1px solid black;">Для версий Office, скомпилированных без /GS:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">Включение защиты /GS при компиляции Office 2003 с пакетом обновления 3 (SP3) и последующих версий является фактором, уменьшающим опасность этой уязвимости, который значительно снижает уровень риска для таких систем до отметки <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> — возможность работы кода использования отсутствует.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office PowerPoint делают возможным удаленное выполнение кода (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0221">CVE-2009-0221</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможна несогласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office PowerPoint делают возможным удаленное выполнение кода (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0222">CVE-2009-0222</a></td>
<td style="border:1px solid black;">Для версий Office, скомпилированных без /GS:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">Включение защиты /GS при компиляции Office 2003 с пакетом обновления 3 (SP3) и последующих версий является фактором, уменьшающим опасность этой уязвимости, который значительно снижает уровень риска для таких систем до отметки <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> — возможность работы кода использования отсутствует.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office PowerPoint делают возможным удаленное выполнение кода (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0223">CVE-2009-0223</a></td>
<td style="border:1px solid black;">Для версий Office, скомпилированных без /GS:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">Включение защиты /GS при компиляции Office 2003 с пакетом обновления 3 (SP3) и последующих версий является фактором, уменьшающим опасность этой уязвимости, который значительно снижает уровень риска для таких систем до отметки <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> — возможность работы кода использования отсутствует.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office PowerPoint делают возможным удаленное выполнение кода (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0224">CVE-2009-0224</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможна несогласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office PowerPoint делают возможным удаленное выполнение кода (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0225">CVE-2009-0225</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможна несогласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office PowerPoint делают возможным удаленное выполнение кода (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0226">CVE-2009-0226</a></td>
<td style="border:1px solid black;">Для версий Office, скомпилированных без /GS:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">Включение защиты /GS при компиляции Office 2003 с пакетом обновления 3 (SP3) и последующих версий является фактором, уменьшающим опасность этой уязвимости, который значительно снижает уровень риска для таких систем до отметки <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> — возможность работы кода использования отсутствует.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office PowerPoint делают возможным удаленное выполнение кода (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0227">CVE-2009-0227</a></td>
<td style="border:1px solid black;">Для версий Office, скомпилированных без /GS:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">Включение защиты /GS при компиляции Office 2003 с пакетом обновления 3 (SP3) и последующих версий является фактором, уменьшающим опасность этой уязвимости, который значительно снижает уровень риска для таких систем до отметки <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> — возможность работы кода использования отсутствует.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office PowerPoint делают возможным удаленное выполнение кода (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0556">CVE-2009-0556</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;"><strong>Примеры использования данной уязвимости известны в экосистеме Интернета.</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office PowerPoint делают возможным удаленное выполнение кода (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1128">CVE-2009-1128</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office PowerPoint делают возможным удаленное выполнение кода (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1129">CVE-2009-1129</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office PowerPoint делают возможным удаленное выполнение кода (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1130">CVE-2009-1130</a></td>
<td style="border:1px solid black;">Для версий Office, скомпилированных без /GS:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">Включение защиты /GS при компиляции Office 2003 с пакетом обновления 3 (SP3) и последующих версий является фактором, уменьшающим опасность этой уязвимости, который значительно снижает уровень риска для таких систем до отметки <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> — возможность работы кода использования отсутствует.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office PowerPoint делают возможным удаленное выполнение кода (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1131">CVE-2009-1131</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">(отсутствует)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141704">MS09-017</a></td>
<td style="border:1px solid black;">Уязвимости в Microsoft Office PowerPoint делают возможным удаленное выполнение кода (967340)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1137">CVE-2009-1137</a></td>
<td style="border:1px solid black;">Для версий Office, скомпилированных без /GS:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможна согласованность кода использования</td>
<td style="border:1px solid black;">Включение защиты /GS при компиляции Office 2003 с пакетом обновления 3 (SP3) и последующих версий является фактором, уменьшающим опасность этой уязвимости, который значительно снижает уровень риска для таких систем до отметки <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> — возможность работы кода использования отсутствует.</td>
</tr>
</tbody>
</table>
  
Продукты, подверженные уязвимости и соответствующие обновления  
--------------------------------------------------------------
  
<span></span>
В приведенных ниже таблицах перечислены бюллетени в порядке важности категорий программного обеспечения и уровней опасности.
  
**Как пользоваться этими таблицами?**
  
Обращайтесь к этим таблицам, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и узнайте, имеются ли для них обновления для системы безопасности. Для программ или компонентов, указанных в списке, приведены ссылки на доступные обновления с указанием уровня опасности уязвимостей, которые они устраняют.
  
**Примечание.** Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификационного номера бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.
  
#### Наборы приложений и прочие программные продукты Office

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Наборы приложений, системы и компоненты Microsoft Office  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-017**](http://go.microsoft.com/fwlink/?linkid=141704)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2000 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=f443312a-ac74-4ebc-a4ac-7a756aa67894)  
(KB957790)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2002 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=a24ec7ab-c1c7-4ddb-8b6e-107f1af67f49)  
(KB957781)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=ccfa978b-3340-40db-a45d-c880ba36b106)  
(KB957784)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Выпуск 2007 системы Microsoft Office с пакетом обновления 1 (SP1) и выпуск 2007 системы Microsoft Office с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2007 с пакетом обновления 1 (SP1) и Microsoft Office PowerPoint 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=11f8380f-ffb6-4c22-a89c-3dc55d0f9834)  
(KB957789)  
(существенный)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office для Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-017**](http://go.microsoft.com/fwlink/?linkid=141704)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 для Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=5557bfb7-ebb4-4c42-8042-41e830c4e550)  
(KB969661)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 для Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=58326da2-eb75-4b42-b1bc-e70319defb58)  
(KB971822)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Конвертер форматов файлов Open XML для Mac
</td>
<td style="border:1px solid black;">
[Конвертер форматов файлов Open XML для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=9d6d9eaa-8442-4184-8886-faab2803bde6)  
(KB971824)  
(существенный)
</td>
</tr>
<tr>
<th colspan="2">
Другое программное обеспечение Microsoft Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-017**](http://go.microsoft.com/fwlink/?linkid=141704)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Средство просмотра PowerPoint
</td>
<td style="border:1px solid black;">
[Средство просмотра PowerPoint 2003](http://www.microsoft.com/downloads/details.aspx?familyid=6a57e6ed-bd24-406f-87bb-117391e083e0)  
(KB969615)  
(существенный)  
[Средство просмотра PowerPoint 2007 с пакетом обновления 1 (SP1) и средство просмотра PowerPoint 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=141b8338-5c52-4326-a9e4-d2f2d8940d9c)  
(KB970059)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007
</td>
<td style="border:1px solid black;">
[Пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007 с пакетом обновления 1 (SP1) и пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e1d3a4c3-538a-4f98-8d60-250803a80e2a)  
(KB969618)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works 8.5
</td>
<td style="border:1px solid black;">
[Microsoft Works 8.5](http://www.microsoft.com/downloads/details.aspx?familyid=628280fe-e035-4274-85f2-393d9bad543c)  
(KB967043)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 9
</td>
<td style="border:1px solid black;">
[Microsoft Works 9](http://www.microsoft.com/downloads/details.aspx?familyid=f6fa110e-45c6-450f-ae47-c89a06e3f762)  
(KB967044)  
(существенный)
</td>
</tr>
</table>
 
**Примечание к бюллетеню MS09-017**

Корпорация Майкрософт повторно опубликовала MS09-017, чтобы предоставить обновления для системы безопасности для Microsoft Office 2004 для Mac, Microsoft Office 2008 для Mac, конвертера форматов файлов Open XML для Mac, Microsoft Works 8.5 и Microsoft Works 9. Пользователям, у которых есть данное программное обеспечение необходимо немедленно применить данное обновление.

Во время первого выпуска MS09-017 эти обновления для системы безопасности находились на стадии разработки. В то время корпорация Майкрософт выпустила MS09-017, так как в рамках стандартного цикла выпуска бюллетеня были готовы обновления для всего семейства продуктов, предназначенные для широкого круга пользователей. Теперь текущий выпуск MS09-017 завершает спектр обновлений для программного обеспечения, подверженного рассматриваемым в бюллетене уязвимостям.

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
**В центре безопасности**

Управление программным обеспечением и обновлениями для системы безопасности для установки на серверы, настольные и переносные компьютеры организации. Дополнительные сведения см. на веб-узле [центра TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [Центр безопасности TechNet](http://go.microsoft.com/fwlink/?linkid=21171) содержит дополнительные сведения о безопасности в продуктах Майкрософт. Доступ к этим сведениям можно также получить, посетив веб-сайт [Безопасность дома](http://go.microsoft.com/fwlink/?linkid=85102) и щелкнув ссылку "Последние обновления".

Обновления для системы безопасности доступны на веб-узлах [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747), [Центра обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130) и [центра загрузки Office](http://go.microsoft.com/fwlink/?linkid=21135). Обновления для системы безопасности также доступны на веб-узле [центра загрузки Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову security update.

Наконец, обновления для системы безопасности можно загрузить из [каталога Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=96155). Он обеспечивает возможность поиска содержимого (в том числе обновлений для системы безопасности, драйверов и пакетов обновления), которое предоставляется через Центр обновления Windows и Центр обновления Майкрософт. При поиске по номеру бюллетеня по безопасности (например, MS07-036) можно добавлять необходимые обновления (в том числе на различных языках) в корзину и загружать их в указанную папку. Дополнительные сведения см. на веб-узле [Каталог Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=97900) в разделе "Вопросы и ответы".

**Руководство по диагностике и развертыванию**

Корпорация Майкрософт предоставила руководство по диагностике и развертыванию для обновлений безопасности этого месяца. Это руководство также поможет ИТ-специалистам понять, как можно использовать для развертывания обновления для системы безопасности такие средства, как веб-узлы Центра обновления Windows, Центра обновления Майкрософт и центра загрузки Office, анализатор безопасности Microsoft Baseline Security Analyzer (MBSA), средство Office Detection Tool, сервер Microsoft Systems Management Server (SMS) и средство Extended Security Update Inventory Tool (ESUIT). Дополнительные сведения см. в [статье 910723 базы знаний Майкрософт](http://support.microsoft.com/kb/910723).

**Программа Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений безопасности и стандартных ошибок в конфигурации системы безопасности. Дополнительные сведения об анализаторе безопасности MBSA см. на веб-узле [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) (на английском языке).

**Службы Windows Server Update Services**

Службы Windows Server Update Services (WSUS) позволяют администраторам быстро и надежно развертывать последние критические обновления и обновления безопасности для операционных систем Windows 2000 и более поздних версий Windows, для Office XP и более поздних версий Office, для Exchange Server 2003 и для SQL Server 2000 на системах Windows 2000 и более поздних версиях операционных систем.

Дополнительные сведения о развертывании данного обновления для системы безопасности с помощью служб Windows Server Update Services см. на веб-узле [Службы Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) (на английском языке).

**Сервер Systems Management Server**

Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет хорошо сконфигурированное решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей. Последний выпуск сервера SMS — System Center Configuration Manager 2007 — доступен для загрузки; сведения о нем см. также на веб-узле [Диспетчер System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx) (на английском языке). Дополнительные сведения о том, как администраторы могут использовать сервер SMS 2003 для развертывания обновлений для системы безопасности, см. на веб-узле [Управление исправлениями для системы безопасности сервера SMS 2003](http://go.microsoft.com/fwlink/?linkid=22939) (на английском языке). Пользователи сервера SMS 2.0 могут также воспользоваться средствами веб-узла [Пакет возможностей служб Software Updates Services](http://go.microsoft.com/fwlink/?linkid=33340) (на английском языке), позволяющими упростить развертывание обновлений для системы безопасности. Дополнительные сведения о сервере SMS см. на веб-узле [Сервер Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) (на английском языке).

**Примечание.** Для предоставления широкой поддержки при определении необходимости применения и развертывания обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используются средства Microsoft Baseline Security Analyzer и Microsoft Office Detection Tool. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. на веб-узле [Развертывание обновлений программного обеспечения с помощью функции распространения программ сервера SMS](http://go.microsoft.com/fwlink/?linkid=33341) (на английском языке). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакетов [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) и [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

**Средство оценки совместимости обновлений и набор средств для обеспечения совместимости приложений**

Часто обновления записываются в одни те же файлы, а для запуска приложений требуется настроить параметры реестра. Это приводит к возникновению несовместимостей и увеличивает время, затрачиваемое на развертывание обновлений для системы безопасности. Облегчить тестирование и проверку обновлений Windows для установленных приложений можно с помощью [компонентов оценки совместимости обновлений](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true), входящих в состав [набора средств для обеспечения совместимости приложений 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Набор средств для обеспечения совместимости приложений содержит необходимые средства и документацию для выявления проблем совместимости приложений и уменьшения степени воздействия этих проблем перед развертыванием системы Microsoft Windows Vista, обновлений из Центра обновления Windows, обновлений с веб-узла безопасности Майкрософт или новой версии проводника.

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

#### Высокоприоритетные обновления, не относящиеся к безопасности и распространяемые через Центры MU, WU и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-узле Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт](http://support.microsoft.com/kb/894199). Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
-   [Новые, исправленные и выпущенные обновления для продуктов Майкрософт, отличных от Microsoft Windows](http://technet.microsoft.com/en-us/wsus/dd573344.aspx).

#### Microsoft Active Protections Program (MAPP)

Чтобы повысить уровень защиты пользователей, корпорация Майкрософт предоставляет сведения об уязвимостях крупным поставщикам программного обеспечения безопасности перед ежемесячным выпуском обновлений. Эта информация необходима им для усовершенствования программного обеспечения и оборудования для защиты пользователей (антивирусных программ, сетевых систем обнаружения вторжений, а также индивидуальных систем предотвращения вторжений). Сведения о новых средствах защиты, предоставляемых поставщиками программного обеспечения безопасности, доступны на соответствующих веб-сайтах партнеров, перечисленных в списке партнеров [MAPP](http://www.microsoft.com/security/msrc/mapp/partners.mspx).

#### Стратегии безопасности и сообщество

**Стратегии управления обновлениями**

На веб-узле [Рекомендации по безопасности для управления обновлениями](http://go.microsoft.com/fwlink/?linkid=21168) (на английском языке) содержатся дополнительные сведения о рекомендациях корпорации Майкрософт по установке обновлений для системы безопасности.

**Другие обновления для системы безопасности**

Другие обновления безопасности можно загрузить из следующих источников:

-   Обновления для системы безопасности доступны на веб-узле [центра загрузки Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову security update.
-   Обновления для индивидуальных пользователей доступны на веб-узле [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747).
-   Обновления для системы безопасности, доступные в этом месяце на веб-узле Центра обновления Windows, можно получить в виде файлов образа компакт-диска с выпусками обновлений для системы безопасности в Центре загрузки Майкрософт. Дополнительные сведения см. в [статье 913086 базы знаний Майкрософт](http://support.microsoft.com/kb/913086).

**Сообщество ИТ-специалистов, занимающихся вопросами безопасности (на английском языке)**

На веб-узле [Сообщество ИТ-специалистов, занимающихся вопросами безопасности](http://go.microsoft.com/fwlink/?linkid=21164) (на английском языке) можно получить сведения о способах усовершенствования системы безопасности и оптимизации информационной инфраструктуры предприятия, а также обсудить вопросы, связанные с обеспечением безопасности, с другими ИТ-специалистами.

#### Благодарности

Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:

-   анонимного исследователя, сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение о двух проблемах, описанных в бюллетене по безопасности MS09-017;
-   Шона Ларссона (Sean Larsson) из компании [VeriSign iDefense Labs](http://labs.idefense.com/) за сообщение о двух проблемах, описанных в бюллетене по безопасности MS09-017;
-   Николаса Джоли (Nicolas Joly) из компании [VUPEN Security](http://www.vupen.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-017;
-   Марсу Пилами (Marsu Pilami) из компании [VeriSign iDefense Labs](http://labs.idefense.com/) за сообщение о нескольких проблемах, описанных в бюллетене по безопасности MS09-017;
-   Николаса Джоли (Nicolas Joly) из компании [VUPEN Security](http://www.vupen.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-017;
-   Марсу Пилами (Marsu Pilami), сотрудничающего с компанией [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в бюллетене по безопасности MS09-017;
-   Лина (Ling) и Вуши (Wushi) из команды [team509](http://www.team509.com/), сотрудничающих с компаниями [TippingPoint](http://www.tippingpoint.com/) и [Zero Day Initiative](http://www.zerodayinitiative.com/), и Шона Ларсона (Sean Larsson) из компании [VeriSign iDefense Labs](http://labs.idefense.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-017;
-   Карстена Эйрама (Carsten H. Eiram) из компании [Secunia](http://secunia.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS09-017.

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов можно найти на веб-узле [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).
-   Пользователи из США и Канады могут обратиться в службу [поддержки по вопросам безопасности](http://go.microsoft.com/fwlink/?linkid=21131) или позвонить по телефону 1-866-PCSAFETY. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Дополнительные сведения о вариантах поддержки см. на веб-узле [справки и поддержки корпорации Майкрософт](http://support.microsoft.com?ln=ru).
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-узел международной поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (12 мая, 2009 г.). Обзор бюллетеней опубликован.
-   Версия 1.1 (13 мая 2009 г.). Удалено содержавшее ошибочные сведения примечание для бюллетеня MS09-017, которое относилось к обновлениям для системы безопасности KB969618 и KB957789 для поддерживаемых версий Microsoft Office PowerPoint 2007.
-   V2.0 (9 июня 2009 г.). Изменение связано с повторным выпуском бюллетеня MS09-017. MS09-017 публикуется повторно, чтобы предоставить обновления для системы безопасности для Microsoft Office 2004 для Mac, Microsoft Office 2008 для Mac, конвертера форматов файлов Open XML для Mac, Microsoft Works 8.5 и Microsoft Works 9. Пользователям, у которых есть данное программное обеспечение необходимо немедленно применить данное обновление.

*Built at 2014-04-18T01:50:00Z-07:00*
