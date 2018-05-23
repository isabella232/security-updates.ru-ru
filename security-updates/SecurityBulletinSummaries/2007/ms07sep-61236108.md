---
TOCTitle: 'MS07-SEP'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Сентябрь 2007 г.'
ms:assetid: 'ms07-sep'
ms:contentKeyID: 61236108
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms07-sep(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Сентябрь 2007 г.
===================================================================

Дата публикации: 11 сентября 2007 г. | Дата обновления: 12 сентября 2007 г.

**Версия:** 1.1

В этом обзоре описаны бюллетени по безопасности, выпущенные в сентябре 2007 г.

После выпуска сентябрьских бюллетеней данный обзор заменит предварительное уведомление, выпущенное 6 сентября 2007 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-узле [Предварительное уведомление о бюллетенях по безопасности Microsoft](http://technet.microsoft.com/security/bulletin/advance) (на английском языке).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней по безопасности Microsoft, см. на веб-узле [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

12 сентября 2007 г. в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в сентябрьской веб-трансляции, посвященной бюллетеням по безопасности](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344690&eventcategory=4&culture=en-us&countrycode=us). После наступления этой даты данная веб-трансляциия будет доступна по запросу. Дополнительные сведения см. на веб-узле [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://technet.microsoft.com/security/bulletin/summary) (на английском языке).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других важных обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел **Прочие сведения**.

### Сведения о бюллетене

#### Аннотации

Ниже описаны бюллетени по безопасности за текущий месяц в соответствии с уровнями опасности.

Критический уровень опасности (1)
---------------------------------

<span></span>
| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS07-051                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|-----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость в агенте Microsoft Agent делает возможным удаленное выполнение кода (938827)**](http://go.microsoft.com/fwlink/?linkid=94667)                                                                                                                                                                                                                                                                                                                                                                                              |
| **Аннотация**                     | Данное критическое обновление для системы безопасности устраняет уязвимость, о которой сообщалось в частном порядке. В способе, которым агент Microsoft Agent обрабатывает определенные специально созданные URL-адреса, существует уязвимость, приводящая к удаленному выполнению кода. Данная уязвимость позволяет злоумышленнику удаленно выполнить произвольный код в уязвимой системе. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Чтобы применить обновление, потребуется перезагрузить компьютер.                                                                                                                                                                                                                                                                                                                                       |
| **Подвержены уязвимости**         | **Windows.** Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                                                                                    |

Существенный (3)
----------------

<span></span>
| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS07-052                                                                                                                                                                                                                                                                                                                                   |
|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость в компоненте Crystal Reports for Visual Studio делает возможным удаленное выполнение кода (941522)**](http://go.microsoft.com/fwlink/?linkid=98460)                                                                                                                                                                                                              |
| **Аннотация**                     | Это существенное обновление для системы безопасности устраняет уязвимость, о которой сообщалось в открытых источниках. Она делает возможным удаленное выполнение кода, если пользователь открывает специально созданный RPT-файл. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. |
| **Уровень опасности**             | [Важно](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                          |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                      |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer и средство Enterprise Update Scan Tool могут определить, требуется ли данное обновление для системы. Чтобы применить обновление, может потребоваться перезагрузить компьютер.                                                                                                                                     |
| **Подвержены уязвимости**         | **Среда Visual Studio.** Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                              |

| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS07-053                                                                                                                                                                                                                                                                                                                |
|-----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость в службах Windows для UNIX делает возможным несанкционированное получение прав (939778)**](http://go.microsoft.com/fwlink/?linkid=94467)                                                                                                                                                                                                      |
| **Аннотация**                     | Данное существенное обновление для системы безопасности устраняет уязвимость, о которой сообщалось в открытых источниках. В службах Windows для UNIX 3.0, службах Windows для UNIX 3.5 и подсистеме для UNIX-приложений существует уязвимость. Запуск определенных двоичных setuid-файлов может позволить злоумышленнику несанкционированно получить права. |
| **Уровень опасности**             | [Важно](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                       |
| **Воздействие уязвимости**        | несанкционированное получение прав                                                                                                                                                                                                                                                                                                                          |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer и средство Enterprise Update Scan Tool могут определить, требуется ли данное обновление для системы. Чтобы применить обновление, потребуется перезагрузить компьютер.                                                                                                                          |
| **Подвержены уязвимости**         | **Службы Windows Services для UNIX, подсистема для UNIX-приложений.** Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                              |

| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS07-054                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость в MSN Messenger и Windows Live Messenger делает возможным удаленное выполнение кода (942099)**](http://go.microsoft.com/fwlink/?linkid=100148)                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Аннотация**                     | Данное обновление для системы безопасности устраняет уязвимость в приложениях MSN Messenger и Windows Live Messenger, о которой сообщалось в открытых источниках. Эта уязвимость делает возможным удаленное выполнение кода, если пользователь принимает от злоумышленника приглашение к видеоразговору или видеосвязи. Воспользовавшись уязвимостью, злоумышленник может захватить полный контроль над системой. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. |
| **Уровень опасности**             | [Важно](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Обнаружение**                   | Эти продукты имеют встроенные функции автоматического обнаружения и развертывания обновлений. Чтобы применить обновление, может потребоваться перезагрузить компьютер.                                                                                                                                                                                                                                                                                                                                                                                         |
| **Подвержены уязвимости**         | **Программы MSN Messenger, Windows Live Messenger.** Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                                                                  |

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
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS07-051**](http://go.microsoft.com/fwlink/?linkid=94667)
</td>
<td style="border:1px solid black;">
[**MS07-052**](http://go.microsoft.com/fwlink/?linkid=98460)
</td>
<td style="border:1px solid black;">
[**MS07-053**](http://go.microsoft.com/fwlink/?linkid=94467)
</td>
<td style="border:1px solid black;">
[**MS07-054**](http://go.microsoft.com/fwlink/?linkid=100148)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<th colspan="5">
Операционная система Windows
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 с пакетом обновления 4 (SP4);
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=7cd248ed-d154-4dce-89ef-ceefd2700965)
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
Windows XP с пакетом обновления 2 (SP2)
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista;
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
Windows Vista x64 Edition
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
<th colspan="5">
Компоненты операционных систем Windows
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Службы Windows для UNIX 3.0 в системе Windows 2000 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Cлужбы Windows для UNIX 3.5 в системе Windows 2000 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Cлужбы Windows для UNIX 3.0 в системе Windows XP с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Cлужбы Windows для UNIX 3.5 в системе Windows XP с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Cлужбы Windows для UNIX 3.0 в системах Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Cлужбы Windows для UNIX 3.5 в системах Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Подсистема для UNIX-приложений в системах Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=8ab5cc43-0b9c-45eb-aa51-47568ab6ce3f)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Подсистема для UNIX-приложений в системах Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=1d21e3e8-b5f6-4044-9db6-054af836492b)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Подсистема для UNIX-приложений в системе Windows Vista
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=4d52e4f4-2888-42df-8163-85c648e65b29)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Подсистема для UNIX-приложений в системе Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=4be667cc-c239-480b-a9a0-939bcd27f0de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5">
Платформы и средства разработки
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio .NET 2002 с пакетом обновления 1 (SP1)  
(KB937057)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=2608c83b-e1b2-4449-9a0e-1e566aac3d76)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Visual Studio .NET 2003  
(KB937058)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=d612ad41-5a0d-4e13-99ea-d6a5589786d6)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio .NET 2003 с пакетом обновления 1 (SP1)  
(KB937059)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=0b10b04b-932c-4bff-9cbc-b3eeb15064b1)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Visual Studio 2005  
(KB937060)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=21073cc2-919c-40df-8ebb-aa3db06050d2)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio 2005 с пакетом обновления 1 (SP1)  
(KB937061)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=967d43c8-efba-4221-beb0-981e7deef33a)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5">
Другие программные продукты, подверженные уязвимости
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
MSN Messenger 6.2 в системе Microsoft Windows 2000 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=cf49c56c-8b3e-4eae-9904-9505f47bed45&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
MSN Messenger 7.0 в системе Microsoft Windows 2000 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=cf49c56c-8b3e-4eae-9904-9505f47bed45&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
MSN Messenger 6.2 в системах Windows XP с пакетом обновления 2 (SP2), Windows XP Professional x64 Edition, Windows XP Professional x64 Edition с пакетом обновления 2 (SP2), Windows Server 2003 с пакетом обновления 1 (SP1), Windows Server 2003 с пакетом обновления 2 (SP2), Windows Server 2003 x64 Edition, Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2), Windows Vista и Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
MSN Messenger 7.0 в системах Windows XP с пакетом обновления 2 (SP2), Windows XP Professional x64 Edition, Windows XP Professional x64 Edition с пакетом обновления 2 (SP2), Windows Server 2003 с пакетом обновления 1 (SP1), Windows Server 2003 с пакетом обновления 2 (SP2), Windows Server 2003 x64 Edition, Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2), Windows Vista и Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
MSN Messenger 7.5 в системах Windows XP с пакетом обновления 2 (SP2), Windows XP Professional x64 Edition, Windows XP Professional x64 Edition с пакетом обновления 2 (SP2), Windows Server 2003 с пакетом обновления 1 (SP1), Windows Server 2003 с пакетом обновления 2 (SP2), Windows Server 2003 x64 Edition, Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2), Windows Vista и Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Live Messenger 8.0 в системах Windows XP с пакетом обновления 2 (SP2), Windows XP Professional x64 Edition, Windows XP Professional x64 Edition с пакетом обновления 2 (SP2), Windows Server 2003 с пакетом обновления 1 (SP1), Windows Server 2003 с пакетом обновления 2 (SP2), Windows Server 2003 x64 Edition, Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2), Windows Vista и Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Важно](http://www.microsoft.com/downloads/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
</table>
 
**Примечания**

**<sup>[1]</sup>** Доступно обновление для системы безопасности этой операционной системы. Дополнительные сведения об уязвимых компонентах или программном обеспечении см. в таблице, а также в соответствующем бюллетене по безопасности.** **

**<sup>[2]</sup>** Уязвимости подвержены не все выпуски Visual Studio. Перечень уязвимых выпусков см. в соответствующем бюллетене по безопасности.** **

**<sup>[3]</sup>** Обновить это программное обеспечение также можно через Интернет, посетив службы Windows Live Messenger Service и Windows Live Messenger Service. Дополнительные сведения см. в соответствующем бюллетене безопасности.

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

**Службы Windows Server Update Services**

Службы Windows Server Update Services (WSUS) позволяют администраторам быстро и надежно развертывать последние критические обновления и обновления безопасности для операционных систем Windows 2000 и более поздних версий Windows, для Office XP и более поздних версий Office, для Exchange Server 2003 и для SQL Server 2000 на системах Windows 2000 и более поздних версиях операционных систем.

Дополнительные сведения о развертывании данного обновления для системы безопасности с помощью служб Windows Server Update Services см. на веб-узле [Службы Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) (на английском языке).

**Сервер Systems Management Server**

Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет хорошо сконфигурированное решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей. Дополнительные сведения о том, как администраторы могут использовать сервер SMS 2003 для развертывания обновлений для системы безопасности, см. на веб-узле [Управление исправлениями для системы безопасности сервера SMS 2003](http://go.microsoft.com/fwlink/?linkid=22939) (на английском языке). Пользователи сервера SMS 2.0 могут также воспользоваться средствами веб-узла [Пакет возможностей служб Software Updates Services](http://go.microsoft.com/fwlink/?linkid=33340) (на английском языке), позволяющими упростить развертывание обновлений для системы безопасности. Дополнительные сведения о сервере SMS см. на веб-узле [Сервер Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) (на английском языке).

**Примечание.** Для предоставления широкой поддержки при определении необходимости применения и развертывания обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используются средства Microsoft Baseline Security Analyzer и Microsoft Office Detection Tool. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. на веб-узле [Развертывание обновлений программного обеспечения с помощью функции распространения программ сервера SMS](http://go.microsoft.com/fwlink/?linkid=33341) (на английском языке). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакетов [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) и [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

#### Высокоприоритетные обновления, не относящиеся к безопасности и распространяемые через Центры MU, WU и службу WSUS

В этом месяце:

-   корпорация Майкрософт не выпускала высокоприоритетных обновлений, **не относящихся к безопасности**, и не распространяет их через Центр обновления Майкрософт (MU) и службы Windows Server Update Services (WSUS).
-   Корпорация Майкрософт не планирует выпускать высокоприоритетные обновления для Windows, **не связанные с безопасностью**, и распространять их через Центр обновления Windows (WU).

Эти сведения относятся **только** к высокоприоритетным обновлениям, **не связанным с безопасностью**, распространяемым через Центр обновления Майкрософт, Центр обновления Windows и службы Windows Server Update Services и выпущенным в тот же день, что и данный обзор бюллетеней по безопасности. Сведения относительно обновлений, **не относящихся к безопасности** и выпущенных в другие дни, **не** предоставляются.

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

-   группу исследования уязвимостей компании [Assurent Secure Technologies](http://www.assurent.com/) за сообщение о проблеме, описанной в бюллетене по безопасности [MS07-051](http://go.microsoft.com/fwlink/?linkid=94667);
-   Ямату Ли (Yamata Li) из компании [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение о проблеме, описанной в бюллетене по безопасности [MS07-051](http://go.microsoft.com/fwlink/?linkid=94667);
-   анонимного исследователя, сотрудничающего с компанией [iDefense](http://labs.idefense.com/) в рамках программы VCP, за сообщение о проблеме, описанной в бюллетене по безопасности [MS07-051](http://go.microsoft.com/fwlink/?linkid=94667);
-   Брайана А. Рейтера (Brian A. Reiter) из компании WolfeReiter за совместную работу над устранением проблемы, описанной в бюллетене по безопасности [MS07-053](http://go.microsoft.com/fwlink/?linkid=94467);
-   Ву Ши (Woo Shi) из команды [team 509](http://www.team509.com/) за сообщение о проблеме, описанной в бюллетене по безопасности [MS07-054](http://go.microsoft.com/fwlink/?linkid=100148).

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов можно найти на веб-узле [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).
-   Обращайтесь в [службу поддержки продуктов корпорации Майкрософт](http://go.microsoft.com/fwlink/?linkid=21131) по телефону 1-866-PCSAFETY (для жителей США и Канады). Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно.
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-узел международной поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (11 сентября 2007 г.). Обзор бюллетеней опубликован.
-   Версия 1.1 (12 сентября 2007г.). В бюллетене MS07-045 переформулированы сведения о необходимости перезапуска и добавлены ссылки на веб-узел загрузки.

*Built at 2014-04-18T01:50:00Z-07:00*
