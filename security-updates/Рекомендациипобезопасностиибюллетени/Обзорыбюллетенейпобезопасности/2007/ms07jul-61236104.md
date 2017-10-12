---
TOCTitle: 'MS07-JUL'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Июль 2007 г.'
ms:assetid: 'ms07-jul'
ms:contentKeyID: 61236104
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms07-jul(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Июль 2007 г.
===============================================================

Дата публикации: 10 июля 2007 г. | Дата обновления: 25 марта 2008 г.

**Версия:** 2.0

В этом обзоре описаны бюллетени по безопасности, выпущенные в июле 2007 г.

После выпуска июльских бюллетеней данный обзор заменит предварительное уведомление, выпущенное 5 июля 2007 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-узле [Предварительное уведомление о бюллетенях по безопасности Microsoft](http://technet.microsoft.com/security/bulletin/advance) (на английском языке).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней по безопасности Microsoft, см. на веб-узле [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

11 июля 2007 г. в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы клиентов об этих бюллетенях. [Зарегистрируйтесь для участия в июльской веб-трансляции, посвященной бюллетеням по безопасности](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032343783&eventcategory=4&culture=en-us&countrycode=us). После наступления этой даты данная веб-трансляциия будет доступна по запросу. Дополнительные сведения см. на веб-узле [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://technet.microsoft.com/security/bulletin/summary) (на английском языке).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других важных обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел **Прочие сведения**.

### Сведения о бюллетене

#### Аннотации

Ниже описаны бюллетени по безопасности за текущий месяц в соответствии с уровнями опасности.

Критический (3)
---------------

<span></span>
| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS07-036                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимости в приложении Microsoft Excel делают возможным удаленное выполнение кода (936542)**](http://go.microsoft.com/fwlink/?linkid=93447)                                                                                                                                                                                                                                                                                                                                                                                              |
| **Аннотация**                     | Данное критическое обновление устраняет одну уязвимость, о которой сообщалось в открытых источниках, и две уязвимости, о которых было сообщено в частном порядке. Кроме того, оно решает другие проблемы, связанные с безопасностью и обнаруженные в ходе исследования. Эти уязвимости делают возможным удаленное выполнение кода, если пользователь открывает специально созданный файл Excel. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Это обновление не требует перезагрузки компьютера.                                                                                                                                                                                                                                                                                                                                                         |
| **Подвержены уязвимости**         | **Office, Excel**. Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                                                                                  |

| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS07-039                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|-----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость службы каталогов Windows Active Directory делает возможным удаленное выполнение кода (926122)**](http://go.microsoft.com/fwlink/?linkid=93365)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Аннотация**                     | Данное критическое обновление для системы безопасности устраняет уязвимость в службах каталогов Active Directory, установленных в системах Windows 2000 Server и Windows 2003 Server. Эта уязвимость делает возможным удаленное выполнение кода или может привести к отказу в обслуживании. Попытки воспользоваться данной уязвимостью, скорее всего, приведут к отказу в обслуживании. Тем не менее, удаленное выполнение кода будет возможно. Чтобы воспользоваться уязвимостью в системе Windows Server 2003, злоумышленник должен иметь действительные учетные данные. Воспользовавшись этой уязвимостью, злоумышленник может захватить полный контроль над системой, что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи. |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Чтобы применить обновление, потребуется перезагрузить компьютер.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Подвержены уязвимости**         | **Windows**. Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |

| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS07-040                                                                                                                                                                                                                                                                                                                                                                                                                    |
|-----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимости в .NET Framework делают возможным удаленное выполнение кода (931212)**](http://go.microsoft.com/fwlink/?linkid=91233)                                                                                                                                                                                                                                                                                                                             |
| **Аннотация**                     | Данное обновление устраняет три уязвимости, о которых сообщалось в частном порядке. Две из них делают возможным удаленное выполнение кода на клиентских компьютерах с платформой .NET Framework, а третья может привести к утечке информации на веб-серверах с ASP.NET. Во всех случаях удаленного выполнения кода риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Чтобы применить обновление, потребуется перезагрузить компьютер.                                                                                                                                                                                                                                                              |
| **Подвержены уязвимости**         | **.NET Framework**. Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                    |

Существенный (2)
----------------

<span></span>

| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS07-037                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|-----------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость приложения Microsoft Office Publisher делает возможным удаленное выполнение кода (936548)**](http://go.microsoft.com/fwlink/?linkid=93448)                                                                                                                                                                                                                                                                                                                              |
| **Аннотация**                     | Это существенное обновление для системы безопасности устраняет одну уязвимость, о которой сообщалось в открытых источниках. Она делает возможным удаленное выполнение кода, если пользователь открывает специально созданный файл Microsoft Office Publisher. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. Чтобы воспользоваться данной уязвимостью, необходимо участие пользователя. |
| **Уровень опасности**             | [Важно](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Это обновление не требует перезагрузки компьютера.                                                                                                                                                                                                                                                                                                  |
| **Подвержены уязвимости**         | **Office, Publisher**. Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                       |

| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS07-041                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость в службах Microsoft IIS делает возможным удаленное выполнение кода (939373)**](http://go.microsoft.com/fwlink/?linkid=93706)                                                                                                                                                                                                                                                                                                                                                                   |
| **Аннотация**                     | Данное существенное обновление для системы безопасности устраняет уязвимость, о которой сообщалось в частном порядке. Она делает возможным удаленное выполнение кода, если злоумышленник отправит специально созданные URL-запросы на веб-страницу, размещенную службами Microsoft IIS 5.1 в системе Windows XP Professional с пакетом обновления 2 (SP2). Службы IIS 5.1 по умолчанию в ней не установлены. Злоумышленник, воспользовавшийся этой уязвимостью, может получить полный контроль над системой. |
| **Уровень опасности**             | [Важно](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Чтобы применить обновление, потребуется перезагрузить компьютер.                                                                                                                                                                                                                                                                                                           |
| **Подвержены уязвимости**         | **Windows XP Professional**. Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                                        |

Средний (1)
-----------

<span></span>
| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS07-038                                                                                                                                                                                                                                               |
|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость в брандмауэре Windows Vista может привести к утечке информации (935807)**](http://go.microsoft.com/fwlink/?linkid=91033)                                                                                                                                                     |
| **Аннотация**                     | Данное обновление для системы безопасности устраняет уязвимость, о которой сообщалось в частном порядке. Она дает возможность незапрошенному входящему сетевому трафику получать доступ к сетевому интерфейсу, что может позволить злоумышленнику получить информацию об уязвимой системе. |
| **Уровень опасности**             | [Средний](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                    |
| **Воздействие уязвимости**        | утечка информации                                                                                                                                                                                                                                                                          |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Чтобы применить обновление, потребуется перезагрузить компьютер.                                                                                         |
| **Подвержены уязвимости**         | **Windows** **Vista**. Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                            |

Продукты, подверженные уязвимости и соответствующие обновления
--------------------------------------------------------------

<span></span>
**Как пользоваться этой таблицей?**

Используйте эту таблицу, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и выясните, требуют ли они установки обновлений для системы безопасности. Для программ или компонентов, указанных в таблице, приводятся сведения о воздействии уязвимости, а также гиперссылки на доступные обновления программного обеспечения.

**Примечание.** Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификационного номера бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.

**Продукты, подверженные уязвимости и соответствующие обновления**

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
Сведения        
</th>
<th style="border:1px solid black;" >
Сведения        
</th>
<th style="border:1px solid black;" >
Сведения        
</th>
<th style="border:1px solid black;" >
Сведения        
</th>
<th style="border:1px solid black;" >
Сведения        
</th>
<th style="border:1px solid black;" >
Сведения        
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS07-036**](http://go.microsoft.com/fwlink/?linkid=93447)
</td>
<td style="border:1px solid black;">
[**MS07-037**](http://go.microsoft.com/fwlink/?linkid=93448)
</td>
<td style="border:1px solid black;">
[**MS07-038**](http://go.microsoft.com/fwlink/?linkid=91033)
</td>
<td style="border:1px solid black;">
[**MS07-039**](http://go.microsoft.com/fwlink/?linkid=93365)
</td>
<td style="border:1px solid black;">
[**MS07-040**](http://go.microsoft.com/fwlink/?linkid=91233)
</td>
<td style="border:1px solid black;">
[**MS07-041**](http://go.microsoft.com/fwlink/?linkid=93706)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Уровень опасности**
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
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<th colspan="7">
Системы Windows, подверженные уязвимости
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 2000 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 2000 Server с пакетом обновления 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=812e62c5-6e19-4b3b-8a10-861b871e1b41)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=fccbfe90-f838-47df-8310-352e2fb47132)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows Server 2003 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=28e84603-8159-4429-aaff-a1020531e84f)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=28e84603-8159-4429-aaff-a1020531e84f)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=107902f9-be94-457f-a936-519efbd64779)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=107902f9-be94-457f-a936-519efbd64779)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=e5e5b425-fe7d-49d5-973f-f3fd7a1e04eb)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2) для платформы Itanium
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=e5e5b425-fe7d-49d5-973f-f3fd7a1e04eb)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Средний](http://www.microsoft.com/downloads/details.aspx?familyid=e9b64746-6afa-4a30-833d-e058e000c821)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Средний](http://www.microsoft.com/downloads/details.aspx?familyid=0df5d190-3ad7-42d5-8629-43c47ec450cb)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для платформы Itanium
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="7">
Компоненты операционных систем Windows, подверженные уязвимости
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft .NET Framework 1.0  
(KB928367)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=91d7afe4-069b-4ce8-976e-9a01345a8603)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.0  
(KB930494)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=829a2c5b-11ec-4ed7-91ab-6961034147bc)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1  
(KB928366)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=281fb2cd-c715-4f05-a01f-0455d2d9ebfb)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1  
(KB933854)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=2495e656-1e0a-4b83-90da-821e68067a71)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1  
(KB929729)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=7eea368d-7b82-4583-8537-30351718a4e9)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0  
(KB928365)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=ba3ceb78-8e1b-4c38-adfd-e8bc95ae548d)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0  
(KB929916)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=cbc9f3cf-c3c3-45c4-82e3-e11398bc2cd2)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="7">
Приложения Office, подверженные уязвимости
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Excel 2000 с пакетом обновления 3
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=83d94d8e-dda6-4d74-b40d-476c2f0a3af4)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Excel 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=9d93c0ce-5124-4234-ba84-3c27005e010f)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Средство просмотра Excel 2003
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=11f42977-8828-494a-a183-d1aba827b708)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Excel 2007
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=9ab28283-0320-4527-b033-5e80ef32cd34)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Пакет обеспечения совместимости Office для форматов файлов Word, Excel и PowerPoint 2007
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=e592ae5b-09ac-4f5b-b457-a54c9850ad4a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Publisher 2007
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=25d272e7-f2dd-4342-92be-7ebc2e770b44)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
</table>
 
**Примечания**

**<sup>[1]</sup>** Имеется обновление для системы безопасности этой операционной системы. Дополнительные сведения об уязвимых компонентах или программном обеспечении см. в таблице, а также в соответствующем бюллетене по безопасности.** **

** **

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
**В центре безопасности**

Управление программным обеспечением и обновлениями для системы безопасности для установки на серверы, настольные и переносные компьютеры организации. Дополнительные сведения см. на веб-узле [центра TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [Центр безопасности TechNet](http://go.microsoft.com/fwlink/?linkid=21171) содержит дополнительные сведения о безопасности в продуктах Майкрософт. Доступ к этим сведениям можно также получить, посетив веб-узел [Безопасность дома](http://go.microsoft.com/fwlink/?linkid=85102) (на английском языке) и щелкнув ссылку Latest Security Updates (Последние обновления безопасности).

Обновления для системы безопасности доступны на веб-узлах [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747), [Центра обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130) и [центра загрузки Office](http://go.microsoft.com/fwlink/?linkid=21135). Обновления для системы безопасности также доступны на веб-узле [центра загрузки Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову «security\_patch». Наконец, обновления для системы безопасности можно загрузить из каталога Центра обновления Windows. Дополнительные сведения о каталоге Центра обновления Windows см. в [статье 323166 базы знаний Майкрософт](http://support.microsoft.com/kb/323166).

**Руководство по диагностике и развертыванию**

Корпорация Майкрософт предоставила руководство по диагностике и развертыванию для обновлений безопасности этого месяца. Это руководство также поможет ИТ-профессионалам разобраться, каким образом они могут использовать для развертывания обновления безопасности такие средства, как веб-узлы Windows Update, Microsoft Update, Office Update, средства Microsoft Baseline Security Analyzer (MBSA), Office Detection Tool, сервер Microsoft Systems Management Server (SMS), средство Extended Security Update Inventory Tool, а также средство Enterprise Update Scan Tool (EST). Дополнительные сведения см. в [статье 910723 базы знаний Майкрософт](http://support.microsoft.com/kb/910723).

Анализатор безопасности **Microsoft Baseline Security Analyzer** и средство **Enterprise** **Update Scan Tool**

Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений безопасности и стандартных ошибок в конфигурации системы безопасности. Дополнительные сведения об анализаторе безопасности MBSA см. на веб-узле [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) (на английском языке).

Если анализатор безопасности MBSA 1.2.1 не может обнаружить определенное обновление для системы безопасности, корпорация Майкрософт выпускает версию средства Enterprise Update Scan Tool (EST) специально для этого обновления. Дополнительные сведения о средстве EST см. на веб-узле [Enterprise Update Scan Tool](http://support.microsoft.com/default.aspx?id=894193).

**Примечание**. После 9 октября 2007 г. прекращается выпуск обновлений для файла MSSecure.XML, используемого анализатором безопасности MBSA 1.2.1. После этого дня в файл MSSecure.XML, используемый анализатором безопасности MBSA 1.2.1, не будут добавляться обновления для системы безопасности, а также не будут выпускаться новые версии средства Enterprise Scan Tool. Дополнительные сведения см. на веб-узле [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Службы Software Update Services**

Службы Microsoft Software Update Services (SUS) позволяют администратору быстро и надежно устанавливать последние критические обновления и обновления безопасности на серверах, работающих под управлением Windows 2000 и Windows Server 2003, а также на настольных компьютерах, работающих под управлением Windows 2000 Professional и Windows XP Professional.

Сведения о развертывании данного обновления для системы безопасности с помощью служб Software Update Services см. на веб-узле [Службы Software Update Services](http://go.microsoft.com/fwlink/?linkid=21133) (на английском языке).

**Службы Windows Server Update Services**

Службы Windows Server Update Services (WSUS) позволяют администраторам быстро и надежно развертывать последние критические обновления и обновления безопасности для операционных систем Windows 2000 и более поздних версий Windows, для Office XP и более поздних версий Office, для Exchange Server 2003 и для SQL Server 2000 на системах Windows 2000 и более поздних версиях операционных систем.

Дополнительные сведения о развертывании данного обновления для системы безопасности с помощью служб Windows Server Update Services см. на веб-узле [Службы Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) (на английском языке).

**Сервер Systems Management Server**

Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет хорошо сконфигурированное решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей. Дополнительные сведения о том, как администраторы могут использовать сервер SMS 2003 для развертывания обновлений для системы безопасности, см. на веб-узле [Управление исправлениями для системы безопасности сервера SMS 2003](http://go.microsoft.com/fwlink/?linkid=22939) (на английском языке). Пользователи сервера SMS 2.0 могут также воспользоваться средствами веб-узла [Пакет возможностей служб Software Updates Services](http://go.microsoft.com/fwlink/?linkid=33340) (на английском языке), позволяющими упростить развертывание обновлений для системы безопасности. Дополнительные сведения о сервере SMS см. на веб-узле [Сервер Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) (на английском языке).

**Примечание.** Для предоставления широкой поддержки при определении необходимости применения и развертывания обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используются средства Microsoft Baseline Security Analyzer и Microsoft Office Detection Tool. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. на веб-узле [Развертывание обновлений программного обеспечения с помощью функции распространения программ сервера SMS](http://go.microsoft.com/fwlink/?linkid=33341) (на английском языке). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакетов [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) и [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

Данное средство **не** распространяется через службы Software Update Services (SUS).

#### Высокоприоритетные обновления, не относящиеся к безопасности и распространяемые через Центры MU, WU и службы WSUS и SUS

В этом месяце:

-   Корпорация Майкрософт выпустила четыре высокоприоритетных обновления, **не относящихся к безопасности**, и распространяет их через Центр обновления Майкрософт (MU) и службы Windows Server Update Services (WSUS).
-   Корпорация Майкрософт выпустила одно высокоприоритетное обновление для системы Windows, **не относящееся к безопасности**, и распространяет его через Центр обновления Windows (WU) и службы Software Update Services (SUS).

Эти сведения относятся **только** к высокоприоритетным обновлениям, **не имеющим отношения к безопасности**, распространяемым через Центр обновления Майкрософт, Центр обновления Windows, службы Windows Server Update Services, Software Update Services и выпущенным в тот же день, что и данный обзор бюллетеней по безопасности. Сведения относительно обновлений, **не относящихся к безопасности** и выпущенных в другие дни, **не** предоставляются.

#### Стратегии безопасности и сообщество

**Стратегии управления обновлениями**

На веб-узле [Рекомендации по безопасности для управления исправлениями](http://go.microsoft.com/fwlink/?linkid=21168) (на английском языке) содержатся дополнительные сведения о рекомендациях корпорации Майкрософт по установке обновлений для системы безопасности.

**Другие обновления для системы безопасности**

Другие обновления безопасности можно загрузить из следующих источников:

-   Обновления для системы безопасности доступны на веб-узле [центра загрузки Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Чтобы найти обновление, выполните поиск по ключевому слову security\_patch.
-   Обновления для индивидуальных пользователей доступны на веб-узле [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747).
-   Обновления для системы безопасности, доступные в этом месяце на веб-узле Центра обновления Windows, можно получить в виде файлов образа компакт-диска с выпусками обновлений для системы безопасности в Центре загрузки Майкрософт. Дополнительные сведения см. в [статье 913086 базы знаний Майкрософт](http://support.microsoft.com/kb/913086).

**Сообщество ИТ-специалистов, занимающихся вопросами безопасности (на английском языке)**

На веб-узле [Сообщество ИТ-специалистов, занимающихся вопросами безопасности](http://go.microsoft.com/fwlink/?linkid=21164) (на английском языке) можно получить сведения о способах усовершенствования системы безопасности и оптимизации информационной инфраструктуры предприятия, а также обсудить вопросы, связанные с обеспечением безопасности, с другими ИТ-специалистами.

#### Благодарности

Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:

-   Диниса Круза (Dinis Cruz) из компании [OWASP](http://www.owasp.org/) за сообщение о проблеме, описанной в бюллетене по безопасности [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233);
-   Пола Крэйга (Paul Craig) из компании [Security Assessment](http://www.smsiinc.com/) за сообщение о проблеме, описанной в бюллетене по безопасности [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233);
-   Йеруна Фрейтерса (Jeroen Frijters) из компании [Sumatra](http://www.sumatra.nl/) за сообщение о проблеме, описанной в бюллетене по безопасности [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233);
-   компанию [ProCheckUp](http://www.procheckup.com/), сотрудничающую с центром [CPNI (Великобритания)](http://www.cpni.gov.uk/), за сообщение о проблеме, описанной в бюллетене по безопасности [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233);
-   Ферруха Т. Мавитуну (Ferruh T. Mavituna) из компании [Portcullis Computer Security Ltd.](http://www.portcullis-security.com/) за совместную работу с корпорацией Майкрософт и предоставление дополнительных сведений о проблеме, описанной в бюллетене по безопасности [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233);
-   Йоханнеса Гумбеля (Johannes Gumbel) из компании [TrueSec](http://www.truesec.com/) за совместную работу с корпорацией Майкрософт и предоставление дополнительных сведений о проблеме, описанной в бюллетене по безопасности [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233);
-   Питера Уинтер-Смита (Peter Winter-Smith) из компании [NGS Software](http://www.nextgenss.com/) за сообщение о проблеме, описанной в бюллетене по безопасности [MS07-039](http://go.microsoft.com/fwlink/?linkid=93365);
-   Нила Мехту (Neel Mehta) из компании [IBM Internet Security Systems x-Force](http://xforce.iss.net/) за сообщение о проблеме, описанной в бюллетене по безопасности [MS07-039](http://go.microsoft.com/fwlink/?linkid=93365);
-   компанию [eEye](http://www.eeye.com/) за сообщение о проблеме, описанной в бюллетене по безопасности [MS07-037](http://go.microsoft.com/fwlink/?linkid=93488);.
-   Джима Хогланда (Jim Hoagland) и Олли Уайтхауса (Ollie Whitehouse) из компании [Symantec](http://www.symantec.com/) за сообщение о проблеме, описанной в бюллетене по безопасности [MS07-038](http://go.microsoft.com/fwlink/?linkid=91033);
-   Йонатана Афека (Jonathan Afek) и Ади Шарабани (Adi Sharabani) из компании [Watchfire](http://www.watchfire.com/) за совместную работу с корпорацией Майкрософт и предоставление дополнительных сведений о проблеме, описанной в бюллетене по безопасности [MS07-041](http://go.microsoft.com/fwlink/?linkid=93706).
-   Питера Уинтер-Смита (Peter Winter-Smith) из компании [NGSSoftware](http://www.nextgenss.com/) за совместную работу с корпорацией Майкрософт и предоставление дополнительных сведений о проблеме, описанной в бюллетене по безопасности [MS07-041](http://go.microsoft.com/fwlink/?linkid=93706).

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов можно найти на веб-узле [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).
-   Обращайтесь в [службу поддержки продуктов корпорации Майкрософт](http://go.microsoft.com/fwlink/?linkid=21131) по телефону 1-866-PCSAFETY (для жителей США и Канады). Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно.
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-узел международной поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (10 июля 2007 г.) Обзор бюллетеней опубликован.
-   Версия 2.0 (25 марта 2008 г.). В таблицу "Подвержены уязвимости" добавлены системы Windows Vista с пакетом обновления 1 (SP1), Windows Vista x64 Edition с пакетом обновления 1 (SP1), Windows Server 2008, Windows Server 2008 для платформы Itanium и Windows Server 2008 x64 Edition.

*Built at 2014-04-18T01:50:00Z-07:00*
