---
TOCTitle: 'MS08-MAR'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Март 2008 г.'
ms:assetid: 'ms08-mar'
ms:contentKeyID: 61236114
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms08-mar(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Март 2008 г.
===============================================================

Дата публикации: 11 марта 2008 г. | Дата обновления: 16 апреля 2008 г.

**Версия:** 2.0

В этом обзоре описаны бюллетени по безопасности, выпущенные в марте 2008 г.

После выпуска мартовских бюллетеней данный обзор заменит предварительное уведомление, выпущенное 6 марта 2008 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-узле [Предварительное уведомление о бюллетенях по безопасности Microsoft](http://technet.microsoft.com/security/bulletin/advance) (на английском языке).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней по безопасности Microsoft, см. на веб-узле [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

12 марта 2008 г. в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в мартовской веб-трансляции, посвященной бюллетеням по безопасности](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357217&eventcategory=4&culture=en-us&countrycode=us). После наступления этой даты данная веб-трансляциия будет доступна по запросу. Дополнительные сведения см. на веб-узле [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://technet.microsoft.com/security/bulletin/summary) (на английском языке).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других важных обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел **Прочие сведения**.

### Сведения о бюллетене

#### Аннотации

Ниже описаны бюллетени по безопасности за текущий месяц в соответствии с уровнями опасности.

Критический (4)
---------------

<span></span>
| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS08-014                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимости в приложении Microsoft Excel делают возможным удаленное выполнение кода (949029)**](http://go.microsoft.com/fwlink/?linkid=112111)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Аннотация**                     | Это обновление для системы безопасности устраняет несколько уязвимостей приложения Microsoft Office Excel, о которых сообщалось в частном порядке и в открытых источниках. Эти уязвимости делают возможным удаленное выполнение, если пользователь откроет специально созданный файл Excel. Воспользовавшись этими уязвимостями, злоумышленник может получить полный контроль над системой. Таким образом, злоумышленник сможет устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Это обновление не требует перезапуска компьютера.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Подвержены уязвимости**         | **Microsoft Office.** Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |

| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS08-015                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|-----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость в Microsoft Outlook делает возможным удаленное выполнение кода (949031)**](http://go.microsoft.com/fwlink/?linkid=112113)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Аннотация**                     | Это критическое обновление для системы безопасности устраняет уязвимость приложения Microsoft Office Outlook, о которой сообщалось в частном порядке. Она делает возможным удаленное выполнение кода, если в Outlook передается специально созданный URI mailto. Таким образом, злоумышленник сможет устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. Этой уязвимостью нельзя воспользоваться при просмотре сообщения электронной почты из области просмотра Outlook. |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Это обновление не требует перезапуска компьютера.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Подвержены уязвимости**         | **Microsoft Office. **Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |

| Идентификационный номер бюллетеня | Бюллетень по безопасности MS08-016                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|-----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимости в Microsoft Office делают возможным удаленное выполнение кода (949030)**](http://go.microsoft.com/fwlink/?linkid=112112)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Аннотация**                     | Это обновление для системы безопасности устраняет две уязвимости пакета Microsoft Office, о которых сообщалось в частном порядке. Они делают возможным удаленное выполнение кода, если пользователь откроет искаженный файл Office. Воспользовавшись этой уязвимостью, злоумышленник может захватить полный контроль над системой, Таким образом, злоумышленник сможет устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Это обновление не требует перезапуска компьютера.                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Подвержены уязвимости**         | **Microsoft Office.** Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |

| Идентификационный номер бюллетеня | Бюллетень по безопасности MS08-017                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|-----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимости веб-компонентов Microsoft Office делают возможным удаленное выполнение кода (933103)**](http://go.microsoft.com/fwlink/?linkid=112114)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Аннотация**                     | Это критическое обновление устраняет две уязвимости веб-компонентов Microsoft Office, о которых сообщалось в частном порядке. Эти уязвимости делают возможным удаленное выполнение кода, если пользователь откроет специально созданную веб-страницу. Воспользовавшись этой уязвимостью, злоумышленник может захватить полный контроль над системой, Таким образом, злоумышленник сможет устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Чтобы применить обновление, может потребоваться перезагрузить компьютер.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Подвержены уязвимости**         | **Веб-компоненты Microsoft Office.** Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |

Продукты, подверженные уязвимости и соответствующие обновления
--------------------------------------------------------------

<span></span>
**Как пользоваться этой таблицей?**

Используйте эту таблицу, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и выясните, требуют ли они установки обновлений для системы безопасности. Для программ или компонентов, указанных в таблице, приводятся сведения о воздействии уязвимости, а также гиперссылки на доступные обновления программного обеспечения.

**Примечание.** Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификационного номера бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.

**Продукты, подверженные уязвимости, и соответствующие обновления**

 
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
[**MS08-014**](http://go.microsoft.com/fwlink/?linkid=112111)
</td>
<td style="border:1px solid black;">
[**MS08-015**](http://go.microsoft.com/fwlink/?linkid=112113)
</td>
<td style="border:1px solid black;">
[**MS08-016**](http://go.microsoft.com/fwlink/?linkid=112112)
</td>
<td style="border:1px solid black;">
[**MS08-017**](http://go.microsoft.com/fwlink/?linkid=112114)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<th colspan="5">
Наборы приложений и прочие программные продукты Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=72735aa1-e22c-40ed-8c79-38fba89979aa)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Существенный](http://www.microsoft.com/downloads/details.aspx?familyid=9cf8aafa-71a5-4017-b53c-4e80ef6e1188)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Существенный](http://www.microsoft.com/downloads/details.aspx?familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel 2000 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=f7f90c30-1bfd-406b-a77f-612443e30185)
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
Microsoft Office Excel 2002 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Существенный](http://www.microsoft.com/downloads/details.aspx?familyid=907f96d5-d1e9-4471-b41c-3ac811e63038)
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
Microsoft Office Excel 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Существенный](http://www.microsoft.com/downloads/details.aspx?familyid=296e5f2c-f594-41c8-a20a-3e4c40ae3948)
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
Microsoft Office Excel Viewer 2003
</td>
<td style="border:1px solid black;">
[Существенный](http://www.microsoft.com/downloads/details.aspx?familyid=280bb2ac-b21a-46b5-8751-5a50fbebf107)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Существенный](http://www.microsoft.com/downloads/details.aspx?familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Существенный](http://www.microsoft.com/downloads/details.aspx?familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer 2003
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Существенный](http://www.microsoft.com/downloads/details.aspx?familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Средство просмотра Microsoft Office Word 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Существенный](http://www.microsoft.com/downloads/details.aspx?familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel 2007
</td>
<td style="border:1px solid black;">
[Существенный](http://www.microsoft.com/downloads/details.aspx?familyid=e7634cb5-9531-4284-9554-4168fc488e0c)
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
Пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007
</td>
<td style="border:1px solid black;">
[Существенный](http://www.microsoft.com/downloads/details.aspx?familyid=e9251d71-9098-4125-ae91-7d4c83ea58ad)
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
Microsoft Office Outlook 2000 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=714a49cd-5bca-4719-96a1-e1077f279533)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Outlook 2002 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=59853687-d885-4059-9460-ee403855dbd8)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Outlook 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=fccc7c4c-8496-4682-bd46-6590503c1bf2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Outlook 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=fccc7c4c-8496-4682-bd46-6590503c1bf2)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
приложение Microsoft Office Outlook 2007
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=4e2baf00-88eb-4eb6-961a-54245b363c21)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 для Mac
</td>
<td style="border:1px solid black;">
[Существенный](http://www.microsoft.com/downloads/details.aspx?familyid=95dceb37-b35f-46db-b280-db0f3b298aa9)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Существенный](http://www.microsoft.com/downloads/details.aspx?familyid=95dceb37-b35f-46db-b280-db0f3b298aa9)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 для Mac
</td>
<td style="border:1px solid black;">
[Существенный](http://www.microsoft.com/downloads/details.aspx?familyid=8fe8c32a-6d7a-482b-97c6-42562f089ee4)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5">
Прочие программные продукты
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Веб-компоненты Microsoft Office 2000  
(KB931660)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=806c654a-35e3-4385-855a-4b803249bfcf)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Веб-компоненты Microsoft Office 2000  
(KB932031)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=f54d2a5e-c0ed-4f70-9746-38dd61c8e9d7)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Веб-компоненты Microsoft Office 2000  
(KB933367)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=d71b23fa-a873-406d-bad7-e38e565dee39)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Веб-компоненты Microsoft Office 2000  
(KB933369)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=2fe10ccd-40cb-4090-b83d-eae3d4eca174)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Веб-компоненты Microsoft Office 2000  
(KB939714)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=5fddd54f-7a33-4ea3-b68d-b96a9bae509d)   
**<sup>[2]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Веб-компоненты Microsoft Office 2000  
(KB939714)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=5fddd54f-7a33-4ea3-b68d-b96a9bae509d)   
**<sup>[3]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Веб-компоненты Microsoft Office 2000  
(KB941305)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=71de76ba-b62c-4a7a-a78a-9317f5255b13)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Веб-компоненты Microsoft Office 2000  
(KB948257)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Критический](http://www.microsoft.com/downloads/details.aspx?familyid=526d87bd-c3da-412e-8765-c15987ae9b01)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Visual Studio .NET 2002 с пакетом обновления 1 (SP1)  
(KB933367)
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
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio .NET 2003 с пакетом обновления 1 (SP1)  
(KB933369)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft BizTalk Server 2000  
(KB939714)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2002  
(KB939714)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Commerce Server 2000  
(KB941305)
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
</tr>
<tr>
<td style="border:1px solid black;">
Internet Security and Acceleration Server 2000 с пакетом обновления 2 (SP2)  
(KB948257)
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
</tr>
</table>
 
**Примечания**

**<sup>[1]</sup>** Существует обновление для системы безопасности этого программного обеспечения. Дополнительные сведения об уязвимых компонентах или программном обеспечении см. в таблице, а также в соответствующем бюллетене по безопасности.** **

**<sup>[2]</sup>** Это обновление для системы безопасности Microsoft BizTalk Server 2000. Дополнительные сведения см. в соответствующем бюллетене по безопасности.

**<sup>[3]</sup>** Это обновление для системы безопасности Microsoft BizTalk Server 2002. Дополнительные сведения см. в соответствующем бюллетене по безопасности.

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

В этом месяце:

-   Корпорация Майкрософт выпустила два высокоприоритетных обновления, **не относящихся к безопасности**, и распространяет их через Центр обновления Майкрософт (MU) и службы Windows Server Update Services (WSUS).
-   Корпорация Майкрософт выпустила три высокоприоритетных обновления для Windows, **не относящихся к безопасности**, и распространяет их через Центр обновления Windows (WU) и службы WSUS.

Эти сведения относятся **только** к высокоприоритетным обновлениям, **не связанным с безопасностью**, распространяемым через Центр обновления Майкрософт, Центр обновления Windows и службы Windows Server Update Services и выпущенным в тот же день, что и данный обзор бюллетеней по безопасности. Сведения относительно обновлений, **не относящихся к безопасности** и выпущенных в другие дни, **не** предоставляются.

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

-   Майка Скотта (Mike Scott) из компании [SAIC](http://www.saic.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-014;
-   Мэта Ричарда (Matt Richard) из компании [VeriSign](http://www.verisign.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-014;
-   Грега Мак-Мануса (Greg MacManus) из компании [iDefense Labs](http://labs.idefense.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-014;
-   Ёсию Сасаки (Yoshiya Sasaki) из компании [JFE Systems](http://www.jfe-systems.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-014;
-   Бин Лю (Bing Liu) из компании [Fortinet](http://www.fortinet.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-014;
-   компанию [iDefense Labs](http://labs.idefense.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-014;
-   Коди Пирс (Cody Pierce) из компании [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-014;
-   Моти Йоспеха (Moti Joseph) и Дэна Хаббарда (Dan Hubbard) из компании [Websense Security Labs](http://www.websense.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-014;
-   Грега Мак-Мануса (Greg MacManus) из компании [iDefense Labs](http://labs.idefense.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-015.
-   Арно Дови (Arnaud Dovi), сотрудничающего с компанией [Zero Day Initiative (ZDI)](http://www.zerodayinitiative.com/), за сообщение о проблеме, которая описана в бюллетене по безопасности MS08-016;
-   анонимного исследователя за сообщение о проблеме, описанной в бюллетене по безопасности MS08-016;
-   Криса Риеса (Chris Ries) из компании [VigilantMinds Inc.](http://www.vigilantminds.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-017;
-   Сяо Хой (Xiao Hui) из компании [NCNIPC](http://www.nipc.org.cn/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-017;
-   Голана Йосефа (Golan Yosef) из компании [Finjan](http://www.finjan.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-017;
-   Юваля Бен-Ицхака (Greg Ben-Itzhak) из компании [Finjan](http://www.finjan.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-017;

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов можно найти на веб-узле [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).
-   Обращайтесь в [службу поддержки продуктов корпорации Майкрософт](http://go.microsoft.com/fwlink/?linkid=21131) по телефону 1-866-PCSAFETY (для жителей США и Канады). Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно.
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-узел международной поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (11 марта 2008 г.). Обзор бюллетеней опубликован.
-   Версия 1.1 (12 марта 2008 г.). Обзор бюллетеней обновлен. В него добавлена ссылка для загрузки веб-компонентов Microsoft Office 2000 для BizTalk Server 2000 и 2002.
-   Версия 1.2 (26 марта 2008 г.). В обзор бюллетеней добавлена система поиска для MS08-017.
-   Версия 2.0 (16 апреля 2008 г.). Обзор бюллетеней обновлен. В раздел "Подвержены уязвимости" бюллетеня MS08-016 добавлены сведения о средствах просмотра Microsoft Office Word 2003 и Microsoft Office Word 2003 с пакетом обновления 3 (SP3).

*Built at 2014-04-18T01:50:00Z-07:00*
