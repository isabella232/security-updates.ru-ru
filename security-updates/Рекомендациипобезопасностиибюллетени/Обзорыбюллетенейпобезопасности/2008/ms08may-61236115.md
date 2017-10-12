---
TOCTitle: 'MS08-MAY'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Май 2008 г.'
ms:assetid: 'ms08-may'
ms:contentKeyID: 61236115
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms08-may(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Май 2008 г.
==============================================================

Дата публикации: 13 мая 2008 г.

**Версия:** 1.0

В этом обзоре перечислены бюллетени по безопасности, выпущенные в мае 2008 г.

После выпуска майских бюллетеней данный обзор заменит предварительное уведомление, выпущенное 8 мая 2008 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-узле [Предварительное уведомление о бюллетенях по безопасности Microsoft](http://technet.microsoft.com/security/bulletin/advance) (на английском языке).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней по безопасности Microsoft, см. на веб-узле [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

14 мая 2008 г. в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в майской веб-трансляции, посвященной бюллетеням по безопасности](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357221&eventcategory=4&culture=en-us&countrycode=us). После наступления этой даты данная веб-трансляциия будет доступна по запросу. Дополнительные сведения см. на веб-узле [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://technet.microsoft.com/security/bulletin/summary) (на английском языке).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других важных обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел **Прочие сведения**.

### Сведения о бюллетене

#### Аннотации

Ниже описаны бюллетени по безопасности за текущий месяц в соответствии с уровнями опасности.

Критический (3)
---------------

<span></span>

| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS08-026                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимости в приложении Microsoft Word делают возможным удаленное выполнение кода (951207)**](http://go.microsoft.com/fwlink/?linkid=117295)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Аннотация**                     | Это критическое обновление для системы безопасности устраняет уязвимости приложения Microsoft Word, о которых сообщалось в частном порядке. Они делают возможным удаленное выполнение кода, если пользователь открывает специально созданный файл Word. Воспользовавшись этими уязвимостями, злоумышленник может получить полный контроль над системой. Таким образом, злоумышленник сможет устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Это обновление не требует перезагрузки компьютера.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Подвержены уязвимости**         | **Microsoft Office.** Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |

| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS08-027                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|-----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость в приложении Microsoft Publisher делает возможным удаленное выполнение кода (951208)**](http://go.microsoft.com/fwlink/?linkid=117907)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Аннотация**                     | Это обновление для системы безопасности устраняет уязвимость приложения Microsoft Publisher, о которой сообщалось в частном порядке. Она делает возможным удаленное выполнение кода, если пользователь открывает специально созданный файл Publisher. Воспользовавшись этой уязвимостью, злоумышленник может захватить полный контроль над системой, Таким образом, злоумышленник сможет устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Это обновление не требует перезагрузки компьютера.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Подвержены уязвимости**         | **Microsoft Office.** Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |

| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS08-028                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|-----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость в ядре СУБД Microsoft Jet делает возможным удаленное выполнение кода (950749)**](http://go.microsoft.com/fwlink/?linkid=114750)                                                                                                                                                                                                                                                                                                                                                                    |
| **Аннотация**                     | Это обновление для системы безопасности устраняет уязвимость ядра СУБД Microsoft Jet в системе Windows. Воспользовавшись этой уязвимостью, злоумышленник может захватить полный контроль над системой, что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями**.** Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Чтобы применить обновление, может потребоваться перезагрузить компьютер.                                                                                                                                                                                                                                                                                                       |
| **Подвержены уязвимости**         | **Microsoft Windows.** Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                                                  |

Средний (1)
-----------

<span></span>

| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS08-029                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимости модуля защиты от вредоносных программ (Майкрософт) делают возможной атаку типа "отказ в обслуживании" (952044)**](http://go.microsoft.com/fwlink/?linkid=117943)                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Аннотация**                     | Это обновление для системы безопасности устраняет две уязвимости в модуле защиты от вредоносных программ (Майкрософт), о которых сообщалось в частном порядке. Злоумышленник может воспользоваться любой из этих уязвимостей, создав специальный файл, который делает возможным атаку типа "отказ в облуживании" после загрузки на компьютер и проверки модулем защиты от вредоносных программ (Майкрософт). Воспользовавшись уязвимостью, злоумышленник может сделать так, что модуль защиты от вредоносных программ (Майкрософт) перестанет отвечать на запросы и будет автоматически перезапускаться. |
| **Уровень опасности**             | [Средний](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Воздействие уязвимости**        | Отказ в обслуживании                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Обнаружение**                   | Программное обеспечение, подверженное данной уязвимости, имеет встроенные средства автоматического обнаружения и развертывания обновлений. Это обновление не требует перезагрузки компьютера.                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Подвержены уязвимости**         | **Windows Live OneCare, Microsoft Antigen, Защитник Microsoft Windows, Microsoft Forefront Security.** Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                                                          |

Продукты, подверженные уязвимости и соответствующие обновления
--------------------------------------------------------------

<span></span>
**Как пользоваться этой таблицей?**

Используйте эту таблицу, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и выясните, требуют ли они установки обновлений для системы безопасности. Для программ или компонентов, указанных в списке, приведены ссылки на доступные обновления с указанием уровня опасности уязвимостей, которые они устраняют.

**Примечание.** Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификационного номера бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.

#### Серверы и операционные системы Windows

 
<table style="border:1px solid black;">
<caption>Microsoft Windows 2000</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Идентификационный номер бюллетеня</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=114750"><strong>MS08-028</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Уровень опасности</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Критический</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Windows 2000 с пакетом обновления 4 (SP4)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0de12d09-e675-4cf0-bc6f-e42eeb4784a1">Ядро СУБД Microsoft Jet 4.0</a><br />
(критический)</td>
</tr>
</tbody>
</table>
 

 
<table style="border:1px solid black;">
<caption>ОС Windows XP</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Идентификационный номер бюллетеня</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=114750"><strong>MS08-028</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Уровень опасности</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Критический</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP с пакетом обновления 2 (SP2)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=3247433f-0aa9-49b8-9e40-c5463a95bcff">Ядро СУБД Microsoft Jet 4.0</a><br />
(критический)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP Professional x64 Edition</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4915ebc4-5e7b-493e-b8c4-321d40d9a701">Ядро СУБД Microsoft Jet 4.0</a><br />
(критический)</td>
</tr>
</tbody>
</table>
 

 
<table style="border:1px solid black;">
<caption>Windows Server 2003</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Идентификационный номер бюллетеня</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=114750"><strong>MS08-028</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Уровень опасности</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Критический</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Windows Server 2003 с пакетом обновления 1 (SP1)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=86e3ed62-98f7-46ec-96ab-5e8c123b1288">Ядро СУБД Microsoft Jet 4.0</a><br />
(критический)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5dfc867b-74b7-4818-9fc2-d71e7c9d2e38">Ядро СУБД Microsoft Jet 4.0</a><br />
(критический)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=3452119b-ba4c-4272-82ec-97396b2c2c3d">Ядро СУБД Microsoft Jet 4.0</a><br />
(критический)</td>
</tr>
</tbody>
</table>
 

#### Наборы приложений и прочие программные продукты Office

 
<table style="border:1px solid black;">
<caption>Наборы приложений, системы и компоненты Microsoft Office</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Идентификационный номер бюллетеня</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=117295"><strong>MS08-026</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=117907"><strong>MS08-027</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Уровень опасности</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Критический</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Критический</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office 2000 с пакетом обновления 3 (SP3)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9215ff71-38c0-416a-b89a-fe3474160f41">Microsoft Word 2000 с пакетом обновления 3 (SP3)</a><br />
(KB950250)<br />
(критический)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8675b9b6-fbf0-4ad2-9210-285e2cc10556">Microsoft Publisher 2000 с пакетом обновления 3 (SP3)</a><br />
(KB950682)<br />
(критический)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office XP с пакетом обновления 3 (SP3)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b348a518-221e-4567-a797-999715a8b2ef">Microsoft Word 2002 с пакетом обновления 3 (SP3)</a><br />
(KB950243)<br />
(существенный)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=df623784-6e26-42c0-9e21-e7960b849e1e">Microsoft Publisher 2002 с пакетом обновления 3 (SP3)</a><br />
(KB950129)<br />
(существенный)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office 2003 с пакетом обновления 2 (SP2)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=bc33d144-f917-47b8-961f-744ca847e14c">Microsoft Word 2003 с пакетом обновления 2 (SP2)</a><br />
(KB950241)<br />
(существенный)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c18b060b-9828-4952-8e80-5328c0832d83">Microsoft Publisher 2003 с пакетом обновления 2 (SP2)</a><br />
(KB950213)<br />
(существенный)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office 2003 с пакетом обновления 3 (SP3)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=bc33d144-f917-47b8-961f-744ca847e14c">Microsoft Word 2003 с пакетом обновления 3 (SP3)</a><br />
(KB950241)<br />
(существенный)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c18b060b-9828-4952-8e80-5328c0832d83">Microsoft Publisher 2003 с пакетом обновления 3 (SP3)</a><br />
(KB950213)<br />
(существенный)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">система Microsoft Office 2007</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=071ceaa2-12e3-4401-9331-2a54a93e2550">Microsoft Word 2007</a><br />
(KB950113)<br />
(существенный)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e4b647c2-79a3-49e0-9b1d-741667fdbcca">Microsoft Publisher 2007</a><br />
(KB950114)<br />
(существенный)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=071ceaa2-12e3-4401-9331-2a54a93e2550">Microsoft Outlook 2007</a><br />
(KB950113)<br />
(критический)</td>
<td style="border:1px solid black;">Отсутствует</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Выпуск 2007 системы Microsoft Office с пакетом обновления 1 (SP1)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=071ceaa2-12e3-4401-9331-2a54a93e2550">Microsoft Word 2007 с пакетом обновления 1 (SP1)</a><br />
(KB950113)<br />
(существенный)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e4b647c2-79a3-49e0-9b1d-741667fdbcca">Microsoft Publisher 2007 с пакетом обновления 1 (SP1)</a><br />
(KB950114)<br />
(существенный)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=071ceaa2-12e3-4401-9331-2a54a93e2550">Microsoft Outlook 2007 с пакетом обновления 1 (SP1)</a><br />
(KB950113)<br />
(критический)</td>
<td style="border:1px solid black;">Отсутствует</td>
</tr>
</tbody>
</table>

 
<table style="border:1px solid black;">
<caption>Microsoft Office для Mac</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Идентификационный номер бюллетеня</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=117295"><strong>MS08-026</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Уровень опасности</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Критический</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Office 2004 для Mac</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=99f54471-ccf9-4d94-a882-a05ecd128adc">Microsoft Office 2004 для Mac</a><br />
(KB952332)<br />
(существенный)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office 2008 для Mac</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=395d1487-a3a6-4106-a0f8-4d6e1d6d89d2">Microsoft Office 2008 для Mac</a><br />
(KB952331)<br />
(существенный)</td>
</tr>
</tbody>
</table>
 

 
<table style="border:1px solid black;">
<caption>Прочие программы Microsoft Office</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Идентификационный номер бюллетеня</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=117295"><strong>MS08-026</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Уровень опасности</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Критический</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Средство просмотра Microsoft Word</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=bce7ea31-2bf0-4930-aff9-837bcc82a682">Средство просмотра Microsoft Word 2003</a><br />
(KB950625)<br />
(существенный)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=bce7ea31-2bf0-4930-aff9-837bcc82a682">Microsoft Word Viewer 2003 с пакетом обновления 3 (SP3)</a><br />
(KB950625)<br />
(существенный)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Пакет обеспечения совместимости Microsoft Office</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=2d718f37-c5d1-4e15-a7e1-5a15fedef52f">Пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007</a><br />
(KB951808)<br />
(существенный)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=2d718f37-c5d1-4e15-a7e1-5a15fedef52f">Пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007 с пакетом обновления 1 (SP1)</a><br />
(KB951808)<br />
(существенный)</td>
</tr>
</tbody>
</table>
 

#### Прочее пограммное обеспечение Майкрософт

**Примечание**. Для следующих записей отсутствуют ссылки для загрузки, поскольку перечисленное в них программное обеспечение имеет встроенные механизмы автоматического обнаружения и развертывания обновлений.

 
<table style="border:1px solid black;">
<caption>Средства Майкрософт для защиты от вредоносных программ</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Идентификационный номер бюллетеня</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=117943"><strong>MS08-029</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Уровень опасности</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Средний</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Live OneCare</td>
<td style="border:1px solid black;">Windows Live OneCare<br />
(средний)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Antigen</td>
<td style="border:1px solid black;">Microsoft Antigen для Exchange<br />
(средний)<br />
<br />
Microsoft Antigen для шлюза SMTP<br />
(средний)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Защитник Microsoft Windows</td>
<td style="border:1px solid black;">Защитник Microsoft Windows<br />
(средний)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Forefront Security</td>
<td style="border:1px solid black;">Microsoft Forefront Client Security<br />
(средний)<br />
<br />
Microsoft Forefront Security для Exchange Server<br />
(средний)<br />
<br />
Microsoft Forefront Security для SharePoint<br />
(средний)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Автономное средство проверки системы</td>
<td style="border:1px solid black;">Автономное средство проверки системы, входящее в состав набора средств диагностики и восстановления версии 6.0<br />
(низкий)</td>
</tr>
</tbody>
</table>
 

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
**В центре безопасности**

Управление программным обеспечением и обновлениями для системы безопасности для установки на серверы, настольные и переносные компьютеры организации. Дополнительные сведения см. на веб-узле [центра TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [Центр безопасности TechNet](http://go.microsoft.com/fwlink/?linkid=21171) содержит дополнительные сведения о безопасности в продуктах Майкрософт. Доступ к этим сведениям можно также получить, посетив веб-узел [Безопасность дома](http://go.microsoft.com/fwlink/?linkid=85102) (на английском языке) и щелкнув ссылку Latest Security Updates (Последние обновления безопасности).

Обновления для системы безопасности доступны на веб-узлах [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747), [Центра обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130) и [центра загрузки Office](http://go.microsoft.com/fwlink/?linkid=21135). Обновления для системы безопасности также доступны на веб-узле [центра загрузки Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову security update.

Наконец, обновления для системы безопасности можно загрузить из [каталога Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=96155). Он обеспечивает возможность поиска содержимого (в том числе обновлений для системы безопасности, драйверов и пакетов обновления), которое предоставляется через Центр обновления Windows и Центр обновления Майкрософт. При поиске по номеру бюллетеня по безопасности (например, MS07-036) можно добавлять нужные обновления в корзину, в том числе на различных языках, и загружать их в указанную папку. Дополнительные сведения см. на веб-узле [Каталог Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=97900) в разделе "Вопросы и ответы".

**Руководство по диагностике и развертыванию**

Корпорация Майкрософт предоставила руководство по диагностике и развертыванию для обновлений безопасности этого месяца. Это руководство также поможет ИТ-специалистам понять, как можно использовать для развертывания обновления для системы безопасности такие средства, как веб-узлы Центра обновления Windows, Центра обновления Майкрософт и центра загрузки Office, анализатор безопасности Microsoft Baseline Security Analyzer (MBSA), средство Office Detection Tool, сервер Microsoft Systems Management Server (SMS) и средство Extended Security Update Inventory Tool (ESUIT). Дополнительные сведения см. в [статье 910723 базы знаний Майкрософт](http://support.microsoft.com/kb/910723).

**Анализатор безопасности Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений безопасности и стандартных ошибок в конфигурации системы безопасности. Дополнительные сведения об анализаторе безопасности MBSA см. на веб-узле [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) (на английском языке).

**Службы Windows Server Update Services**

Службы Windows Server Update Services (WSUS) позволяют администраторам быстро и надежно развертывать последние критические обновления и обновления безопасности для операционных систем Windows 2000 и более поздних версий Windows, для Office XP и более поздних версий Office, для Exchange Server 2003 и для SQL Server 2000 на системах Windows 2000 и более поздних версиях операционных систем.

Дополнительные сведения о развертывании данного обновления для системы безопасности с помощью служб Windows Server Update Services см. на веб-узле [Службы Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) (на английском языке).

**Сервер Systems Management Server**

Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет хорошо сконфигурированное решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей. Последний выпуск сервера SMS — System Center Configuration Manager 2007 — доступен для загрузки; сведения о нем см. также на веб-узле [Диспетчер System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx) (на английском языке). Дополнительные сведения о том, как администраторы могут использовать сервер SMS 2003 для развертывания обновлений для системы безопасности, см. на веб-узле [Управление исправлениями для системы безопасности сервера SMS 2003](http://go.microsoft.com/fwlink/?linkid=22939) (на английском языке). Пользователи сервера SMS 2.0 могут также воспользоваться средствами веб-узла [Пакет возможностей служб Software Updates Services](http://go.microsoft.com/fwlink/?linkid=33340) (на английском языке), позволяющими упростить развертывание обновлений для системы безопасности. Дополнительные сведения о сервере SMS см. на веб-узле [Сервер Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) (на английском языке).

**Примечание.** Для предоставления широкой поддержки при определении необходимости применения и развертывании обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используются средства Microsoft Baseline Security Analyzer и Microsoft Office Detection Tool. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. на веб-узле [Развертывание обновлений программного обеспечения с помощью функции распространения программ сервера SMS](http://go.microsoft.com/fwlink/?linkid=33341) (на английском языке). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакетов [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) и [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

#### Высокоприоритетные обновления, не относящиеся к безопасности и распространяемые через Центры MU, WU и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-узле Центра обновления Windows и Центра обновления Майкрософт см. по адресу:

-   [Статья 894199 базы знаний Майкрософт](http://support.microsoft.com/kb/894199). Описание изменений содержимого служб Software Update Services и Windows Server Update Services в 2008 г. (включая все содержимое Windows).
-   [Новые, исправленные и выпущенные обновления для продуктов Майкрософт, отличных от Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

#### Стратегии безопасности и сообщество

**Стратегии управления обновлениями**

На веб-узле [Рекомендации по безопасности для управления обновлениями](http://go.microsoft.com/fwlink/?linkid=21168) (на английском языке) содержатся дополнительные сведения о рекомендациях корпорации Майкрософт по установке обновлений для системы безопасности.

**Другие обновления для системы безопасности**

Другие обновления безопасности можно загрузить из следующих источников:

-   Обновления для системы безопасности доступны на веб-узле [центра загрузки Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову security update.
-   Обновления для индивидуальных пользователей доступны на веб-узле [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747).
-   Обновления для системы безопасности, доступные в этом месяце на веб-узле Центра обновления Windows, можно получить в виде файлов образа компакт-диска с выпусками обновлений для системы безопасности в Центре загрузки Майкрософт. Дополнительные сведения см. в [статье 913086 базы знаний Майкрософт](http://support.microsoft.com/kb/913086).

**Сообщество ИТ-специалистов, занимающихся вопросами безопасности**

На веб-узле [Сообщество ИТ-специалистов, занимающихся вопросами безопасности](http://go.microsoft.com/fwlink/?linkid=21164) (на английском языке) можно получить сведения о способах усовершенствования системы безопасности и оптимизации информационной инфраструктуры предприятия, а также обсудить вопросы, связанные с обеспечением безопасности, с другими ИТ-специалистами.

#### Благодарности

Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:

-   Цзюнь Мао (Jun Mao) из компании [iDefense Labs](http://labs.idefense.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS07-026;
-   Ву Ши (Woo Shi) из команды [team509](http://www.team509.com/), сотрудничающего с компанией [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, которая описана в бюллетене по безопасности MS08-026;
-   Cocoruder из компании [Fortinet Security Research](http://www.fortinet.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS07-027;
-   [CERT/CC](http://www.cert.org/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-028;
-   [ISC/SANS](http://isc.sans.org/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-028;
-   Аарона Портного (Aaron Portnoy) из компании [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-028;
-   SoWhat из компании [Nevis Labs](http://www.nevisnetworks.com) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-029.

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов можно найти на веб-узле [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).
-   Обращайтесь в [службу поддержки продуктов корпорации Майкрософт](http://go.microsoft.com/fwlink/?linkid=21131) по телефону 1-866-PCSAFETY (для жителей США и Канады). Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно.
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-узел международной поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (13 мая 2008 г.). Обзор бюллетеней опубликован.

*Built at 2014-04-18T01:50:00Z-07:00*
