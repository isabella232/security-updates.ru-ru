---
TOCTitle: 'MS08-SEP'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Сентябрь 2008 г.'
ms:assetid: 'ms08-sep'
ms:contentKeyID: 61236118
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms08-sep(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Сентябрь 2008 г.
===================================================================

Дата публикации: 9 сентября 2008 г. | Дата обновления: 9 декабря 2008 г.

**Версия:** 3,0

В этом обзоре описаны бюллетени по безопасности, выпущенные в сентябре 2008 г.

После выпуска сентябрьских бюллетеней данный обзор заменит предварительное уведомление, выпущенное 4 сентября 2008 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-узле [предварительного уведомления о бюллетенях по безопасности Microsoft](http://technet.microsoft.com/security/bulletin/advance) (на английском языке).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней по безопасности Microsoft, см. на веб-узле [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

10 сентября 2008 г., в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в сентябрьской веб-трансляции, посвященной бюллетеням по безопасности](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374633&eventcategory=4&culture=en-us&countrycode=us). После наступления этой даты данная веб-трансляциия будет доступна по запросу. Дополнительные сведения см. на веб-узле [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://technet.microsoft.com/security/bulletin/summary) (на английском языке).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других важных обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел **Прочие сведения**.

### Сведения о бюллетене

#### Аннотации

Ниже описаны бюллетени по безопасности за текущий месяц в соответствии с уровнями опасности.

Критический (4)
---------------

<span></span>

| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS08-054                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость проигрывателя Windows Media делает возможным удаленное выполнение кода (954154)**](http://go.microsoft.com/fwlink/?linkid=121739)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Аннотация**                     | Это обновление для системы безопасности устраняет уязвимость в проигрывателе Windows Media, о которой сообщалось в частном порядке и которая делает возможным удаленное выполнение кода при потоковой передаче с сервера Windows Media специально созданного звукового файла. Если пользователь вошел в систему с правами администратора, то злоумышленник, которому удалось воспользоваться уязвимостью, может установить полный контроль над системой. что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Это обновление не требует перезагрузки компьютера.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Подвержены уязвимости**         | **Система Microsoft Windows.** Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |

| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS08-052                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимости в GDI+ делают возможным удаленное выполнение кода (954593)**](http://go.microsoft.com/fwlink/?linkid=125468)                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Аннотация**                     | Это обновление для системы безопасности устраняет несколько уязвимостей компонента Microsoft Windows GDI+, о которых сообщалось в частном порядке. Они делают возможным удаленное выполнение кода, если пользователь просматривает специально созданный файл изображения с помощью уязвимого программного обеспечения или открывает веб-узел, содержащий специально созданное содержимое. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Для этого обновления необходима перезагрузка.                                                                                                                                                                                                                                                                                                                                                        |
| **Подвержены уязвимости**         | **Система Microsoft Windows, обозреватель Internet Explorer, платформа .NET Framework, пакет Office, сервер SQL Server и приложение Visual Studio.** Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                          |

| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS08-053                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|-----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость в кодировщике Windows Media 9 делает возможным удаленное выполнение кода (954156)**](http://go.microsoft.com/fwlink/?linkid=123091)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Аннотация**                     | Это обновление для системы безопасности устраняет уязвимость в кодировщике Windows Media серии 9, о которой сообщалось в частном порядке. Она делает возможным удаленное выполнение кода, если пользователь открывает специально созданную веб-страницу. Если пользователь вошел в систему с правами администратора, то злоумышленник, которому удалось воспользоваться уязвимостью, может установить полный контроль над системой. что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. Чтобы применить обновление, может потребоваться перезагрузить компьютер.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Подвержены уязвимости**         | **Система Microsoft Windows.** Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |

| Идентификационный номер бюллетеня | Бюллетень по безопасности Microsoft MS08-055                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость пакета Microsoft Office делает возможным удаленное выполнение кода (955047)**](http://go.microsoft.com/fwlink/?linkid=125229)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Аннотация**                     | Это обновление для системы безопасности устраняет уязвимость в пакете Microsoft Office, о которой сообщалось в частном порядке. Она делает возможным удаленное выполнение кода, если пользователь щелкает специально созданный URL-адрес OneNote. Воспользовавшись этой уязвимостью, злоумышленник может захватить полный контроль над системой, что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора. |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Обнаружение**                   | Анализатор безопасности Microsoft Baseline Security Analyzer определяет необходимость установки данного обновления на компьютере. В большинстве случаев это обновление не требует перезагрузки компьютера.                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Подвержены уязвимости**         | **Microsoft Office.** Дополнительные сведения см. в разделе "Продукты, подверженные уязвимости, и соответствующие обновления".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |

Продукты, подверженные уязвимости и соответствующие обновления
--------------------------------------------------------------

<span></span>
**Как пользоваться этой таблицей?**

Используйте эту таблицу, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и выясните, требуют ли они установки обновлений для системы безопасности. Для программ или компонентов, указанных в списке, приведены ссылки на доступные обновления с указанием уровня опасности уязвимостей, которые они устраняют.

**Примечание.** Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификационного номера бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.

#### Компоненты операционных систем Windows

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="4">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://go.microsoft.com/fwlink/?linkid=121739)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://go.microsoft.com/fwlink/?linkid=123091)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Уровень опасности, описанный в бюллетене**
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
<td style="border:1px solid black;">
Microsoft Windows 2000 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=a860d2d9-653d-4ddb-bbff-323d3ccdb866)  
(KB938464)  
(критический)  
[Microsoft .NET Framework 1.0 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=c7cbcd19-acc1-4a89-adfa-99b2f431510d)  
(KB947739)  
(уровень опасности не определен)  
[Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=6013f866-3ea1-4672-b1bf-e516204c3a7a)  
(KB947742)  
(уровень опасности не определен)  
[Microsoft .NET Framework 2.0](http://www.microsoft.com/downloads/details.aspx?familyid=7f1cd013-2c4b-4582-9114-cb840a96124a)  
(KB947746)  
(уровень опасности не определен)  
[Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=215b73a3-46ab-44a8-a0fb-6d37bd1c39b8)  
(KB947748)  
(уровень опасности не определен)
</td>
<td style="border:1px solid black;">
[Кодировщик Windows Media серии 9](http://www.microsoft.com/downloads/details.aspx?familyid=0cabfbc0-db5d-4a6a-a4cd-e6df89ac2b25)  
(критический)
</td>
</tr>
<tr>
<th colspan="4">
ОС Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://go.microsoft.com/fwlink/?linkid=121739)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://go.microsoft.com/fwlink/?linkid=123091)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Уровень опасности, описанный в бюллетене**
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP с пакетом обновления 2 (SP2) или 3 (SP3)
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media 11](http://www.microsoft.com/downloads/details.aspx?familyid=d5891180-5dd1-49ec-bcc6-3030a544202c)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2) и Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=e0bd6fbe-f46e-4961-9a79-49ec77d39439)  
(критический)
</td>
<td style="border:1px solid black;">
[Кодировщик Windows Media серии 9](http://www.microsoft.com/downloads/details.aspx?familyid=57bcb3c2-49d3-4f18-8d03-36abd03d7403)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media 11](http://www.microsoft.com/downloads/details.aspx?familyid=caf8a45e-a9f8-4e91-98fd-87eddbeae64c)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c5d26771-1f49-4bbf-902c-bf92e527cadb)  
(критический)
</td>
<td style="border:1px solid black;">
[Кодировщик Windows Media серии 9](http://www.microsoft.com/downloads/details.aspx?familyid=18efea9e-b103-46de-90d9-5e295854cec3)  
(критический)  
[Кодировщик Windows Media x64 Edition серии 9](http://www.microsoft.com/downloads/details.aspx?familyid=ebc1737c-6e78-4244-a1b2-a56d031f16e9)  
(критический)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://go.microsoft.com/fwlink/?linkid=121739)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://go.microsoft.com/fwlink/?linkid=123091)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Уровень опасности, описанный в бюллетене**
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ac03f138-eca4-46e1-9782-e811820e547f)  
(критический)
</td>
<td style="border:1px solid black;">
[Кодировщик Windows Media серии 9](http://www.microsoft.com/downloads/details.aspx?familyid=54ce1080-94cf-4e4f-8e09-a7dbab2757c5)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=93f1451b-5b62-47e5-8f0c-b720b957999a)  
(критический)
</td>
<td style="border:1px solid black;">
[Кодировщик Windows Media серии 9](http://www.microsoft.com/downloads/details.aspx?familyid=c83011cd-90b8-494c-9cad-fa055e101992)  
(средний)  
[Кодировщик Windows Media x64 Edition серии 9](http://www.microsoft.com/downloads/details.aspx?familyid=d8f1b782-136b-443f-b5f2-63aa4d1fd94a)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium и Windows Server 2003 с пакетом обновления 2 (SP2) для платформы Itanium
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium и Windows Server 2003 с пакетом обновления 2 (SP2) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=14e99f8a-cdd4-40d7-8cfc-73ae6bd6dfad)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="4">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://go.microsoft.com/fwlink/?linkid=121739)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://go.microsoft.com/fwlink/?linkid=123091)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Уровень опасности, описанный в бюллетене**
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
<td style="border:1px solid black;">
Windows Vista и Windows Vista с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media 11](http://www.microsoft.com/downloads/details.aspx?familyid=2f4118fd-1ffb-46da-b922-cd4ca4f9d84e)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista и Windows Vista с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=16f3ad21-ed77-4c32-93df-3b650b2b32a5)  
(критический)
</td>
<td style="border:1px solid black;">
[Кодировщик Windows Media серии 9](http://www.microsoft.com/downloads/details.aspx?familyid=99beebc4-553a-46f8-8245-e3d932306c93)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition и Windows Vista x64 Edition с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media 11](http://www.microsoft.com/downloads/details.aspx?familyid=334352e7-d41f-494f-866d-f1f1745ffd17)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition и Windows Vista x64 Edition с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=aa47d016-f5c9-4586-8876-f1f4f255f54d)  
(критический)
</td>
<td style="border:1px solid black;">
[Кодировщик Windows Media серии 9](http://www.microsoft.com/downloads/details.aspx?familyid=99beebc4-553a-46f8-8245-e3d932306c93)  
(критический)  
[Кодировщик Windows Media x64 Edition серии 9](http://www.microsoft.com/downloads/details.aspx?familyid=54d1279a-7f26-4727-a39d-5505bcd4fc53)  
(критический)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://go.microsoft.com/fwlink/?linkid=121739)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://go.microsoft.com/fwlink/?linkid=123091)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Уровень опасности, описанный в бюллетене**
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
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media 11](http://www.microsoft.com/downloads/details.aspx?familyid=72fc6028-6af4-44ec-8d2a-28c53807d6bc)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем ](http://www.microsoft.com/downloads/details.aspx?familyid=23bd3be5-cc66-46f8-9420-49d65d8afe1d)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Кодировщик Windows Media серии 9](http://www.microsoft.com/downloads/details.aspx?familyid=5434ca66-5a6b-4517-92fb-72dea0a172ec)\*  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media 11](http://www.microsoft.com/downloads/details.aspx?familyid=3906512b-26db-473e-b522-3883ff34a21c)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем ](http://www.microsoft.com/downloads/details.aspx?familyid=7f1e0f05-6c9d-4ad1-9b19-50ee4fa7bd7e)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Кодировщик Windows Media серии 9](http://www.microsoft.com/downloads/details.aspx?familyid=5434ca66-5a6b-4517-92fb-72dea0a172ec)\*  
(средний)  
[Кодировщик Windows Media x64 Edition серии 9](http://www.microsoft.com/downloads/details.aspx?familyid=e30f9427-26d0-4e86-b9b8-bc637c3b5734)\*  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для платформы Itanium
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=5159bdba-3825-4816-a2be-ab035332b9e2)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 
**\* Не подверженные уязвимости системы Windows Server 2008, при развертывании которых устанавливались основные компоненты сервера.** Поддерживаемые выпуски Windows Server 2008, при развертывании которых выбиралась установка основных компонентов, не подвержены уязвимостям, устраняемым этим обновлением (даже если уязвимые файлы находятся в системе). Однако пользователям, в системе которых находятся уязвимые файлы, предлагается установить это обновление, поскольку оно содержит файлы более поздних версий. Дополнительные сведения об этом варианте установки см. в статье [Основные компоненты сервера](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (на английском языке). Обратите внимание, что установка основных компонентов сервера недоступна в определенных выпусках Windows Server 2008; см. статью [Сравнение параметров установки основных компонентов сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (на английском языке).

#### Наборы приложений и прочие программные продукты Office

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Наборы приложений, системы и компоненты Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
<td style="border:1px solid black;">
[**MS08-055**](http://go.microsoft.com/fwlink/?linkid=125229)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Уровень опасности, описанный в бюллетене**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 с пакетами обновления 2 (SP2) и 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8)  
(KB954478)  
(существенный)  
[Microsoft Office 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8)  
(KB954478)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e670ad22-d3c1-41f7-ba30-6a67139feaa3)  
(KB953404)  
(существенный)  
[Microsoft Office 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=e670ad22-d3c1-41f7-ba30-6a67139feaa3)  
(KB953404)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Выпуск 2007 системы Microsoft Office и выпуск 2007 системы Microsoft Office с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Выпуск 2007 системы Microsoft Office](http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)  
(существенный)  
[Выпуск 2007 системы Microsoft Office с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)  
(существенный)
</td>
<td style="border:1px solid black;">
[Выпуск 2007 системы Microsoft Office](http://www.microsoft.com/downloads/details.aspx?familyid=fb457536-26c5-428b-97e4-1fc13718266e)  
(KB951944)  
(существенный)  
[Выпуск 2007 системы Microsoft Office с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=fb457536-26c5-428b-97e4-1fc13718266e)  
(KB951944)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Другое программное обеспечение Microsoft Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
<td style="border:1px solid black;">
[**MS08-055**](http://go.microsoft.com/fwlink/?linkid=125229)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Уровень опасности, описанный в бюллетене**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Project 2002 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2002 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405)\*  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2002 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2002 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a6d9d3ef-f087-4f61-9ec1-522b7d4b9c48)  
(KB954479)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Средство просмотра Microsoft Office Word, средство просмотра Microsoft Office Word 2003, средство просмотра Microsoft Office Word 2003 с пакетом обновления 3 (SP3), средство просмотра Microsoft Office Excel 2003, средство просмотра Microsoft Office Excel 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Средство просмотра Microsoft Office Word, средство просмотра Microsoft Word 2003, средство просмотра Microsoft Word 2003 с пакетом обновления 3 (SP3), средство просмотра Microsoft Office Excel 2003, средство просмотра Microsoft Office Excel 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8)  
(KB954478)\*\*  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Средство просмотра Microsoft Office PowerPoint 2003
</td>
<td style="border:1px solid black;">
[Средство просмотра Microsoft Office PowerPoint 2003](http://www.microsoft.com/downloads/details.aspx?familyid=cd503f08-1831-45ff-bdf4-dd918ca40505)  
(KB956500)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Средство просмотра Microsoft Office Excel, средство просмотра Microsoft Office PowerPoint 2007, средство просмотра Microsoft Office PowerPoint 2007 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Средство просмотра Microsoft Office Excel, средство просмотра Microsoft Office PowerPoint 2007, средство просмотра Microsoft Office PowerPoint 2007 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)\*\*\*  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007 и пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Пакет обеспечения совместимости форматов файлов Microsoft Office Word, Excel и PowerPoint 2007 и пакет обеспечения совместимости форматов файлов Microsoft Office Word, Excel и PowerPoint 2007 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)\*\*\*  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Web и Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft Expression Web и Microsoft Expression Web 2](http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)\*\*\*  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Groove 2007 и Microsoft Office Groove 2007 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft Office Groove 2007 и Microsoft Office Groove 2007 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)\*\*\*  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works
</td>
<td style="border:1px solid black;">
[Microsoft Works 8](http://www.microsoft.com/downloads/details.aspx?familyid=eb0d224e-a517-40d9-9fc6-2345fa12a841)  
(KB956483)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Digital Image Suite 2006
</td>
<td style="border:1px solid black;">
[Microsoft Digital Image Suite 2006](http://www.microsoft.com/downloads/details.aspx?familyid=04afd760-8173-4069-9e82-d3bf053d9eae)  
(KB955992)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office OneNote 2007
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Office OneNote 2007](http://www.microsoft.com/downloads/details.aspx?familyid=8ac3576c-7873-4ac6-8bbc-033f6a7bb395)  
(KB950130)  
(критический)  
[Microsoft Office OneNote 2007 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=8ac3576c-7873-4ac6-8bbc-033f6a7bb395)  
(KB950130)  
(критический)
</td>
</tr>
</table>
 
\* Обновление для этого подверженного уязвимости программного обеспечения не отличается от обновления для Microsoft Office XP с пакетом обновления 3 (SP3).

\*\* Обновление для этого подверженного уязвимости программного обеспечения не отличается от обновления для Microsoft Office 2003 с пакетом обновления 2 (SP2) и Microsoft Office 2003 с пакетом обновления 3 (SP3).

\*\*\* Обновление для этого подверженного уязвимости программного обеспечения не отличается от обновления для выпуска 2007 системы Microsoft Office и выпуска 2007 системы Microsoft Office с пакетом обновления 1 (SP1).

#### Серверное программное обеспечение Майкрософт

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Уровень опасности, описанный в бюллетене**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Службы отчетов SQL Server 2000 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
Не применимо  
Обновление QFE:  
[Службы отчетов SQL Server 2000 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5f9e7f78-7439-414b-a9dc-a779b89427db)  
(KB954609)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
(критический)  
Обновление QFE:  
[SQL Server 2005 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
(критический)  
Обновление QFE:  
[SQL Server 2005 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 с пакетом обновления 2 (SP2) для платформы Itanium
</td>
<td style="border:1px solid black;">
Обновление GDR:  
[SQL Server 2005 с пакетом обновления 2 (SP2) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
(критический)  
Обновление QFE:  
[SQL Server 2005 с пакетом обновления 2 (SP2) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
(критический)
</td>
</tr>
</table>
 

#### Программное обеспечение и средства разработки Microsoft

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Уровень опасности, описанный в бюллетене**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2002 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2002 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=7848a652-4025-44bb-9c98-37a078b56d01)  
(KB947736)  
(уровень опасности не определен)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=9bc1e8f8-6c30-4aa0-90f5-fbb0ad5fd90e)  
(KB947737)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=a7bf790b-3249-4ee8-9440-fa911ebbc08a)  
(KB947738)  
(уровень опасности не определен)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](http://www.microsoft.com/downloads/details.aspx?familyid=a8c80b29-6d00-4949-a005-5d706122919a)  
(KB952241)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Распространяемый пакет Microsoft Report Viewer 2005 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Распространяемый пакет Microsoft Report Viewer 2005 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=82833f27-081d-4b72-83ef-2836360a904d)  
(KB954765)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Распространяемый пакет средства Microsoft Report Viewer 2008
</td>
<td style="border:1px solid black;">
[Распространяемый пакет Microsoft Report Viewer 2008](http://www.microsoft.com/downloads/details.aspx?familyid=6ae0aa19-3e6c-474c-9d57-05b2347456b1)  
(KB954766)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .FoxPro 8.0 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 8.0 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1f4371b9-b8be-4455-94d2-2304ee340543) в системе Microsoft Windows 2000 с пакетом обновления 4 (SP4)  
(KB955368)  
(уровень опасности не определен)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 9.0 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=49b21e30-722d-446e-9020-aceb3870db69) в системе Microsoft Windows 2000 с пакетом обновления 4 (SP4)  
(KB955369)  
(уровень опасности не определен)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .FoxPro 9.0 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 9.0 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=36957f47-9d8b-477d-bd60-5959e5a2eafa) в системе Microsoft Windows 2000 с пакетом обновления 4 (SP4)  
(KB955370)  
(уровень опасности не определен)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Распространяемый пакет Microsoft Platform SDK: GDI+
</td>
<td style="border:1px solid black;">
[Распространяемый пакет Microsoft Platform SDK: GDI+](http://www.microsoft.com/downloads/details.aspx?familyid=6a63ab9c-df12-4d41-933c-be590feaa05a)  
(уровень опасности не определен)
</td>
</tr>
</table>
 

#### Программное обеспечение корпорации Майкрософт по безопасности

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Forefront Security
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Уровень опасности, описанный в бюллетене**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Forefront Client Security 1.0
</td>
<td style="border:1px solid black;">
[Microsoft Forefront Client Security 1.0](http://www.microsoft.com/downloads/details.aspx?familyid=1eb1a79f-44ca-499e-90bb-ac51894e9d1e) в системе Microsoft Windows 2000 с пакетом обновления 4 (SP4)  
(KB957177)  
(существенный)
</td>
</tr>
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

**Сообщество ИТ-специалистов, занимающихся вопросами безопасности (на английском языке)**

На веб-узле [Сообщество ИТ-специалистов, занимающихся вопросами безопасности](http://go.microsoft.com/fwlink/?linkid=21164) (на английском языке) можно получить сведения о способах усовершенствования системы безопасности и оптимизации информационной инфраструктуры предприятия, а также обсудить вопросы, связанные с обеспечением безопасности, с другими ИТ-специалистами.

#### Благодарности

Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:

-   Грега Мак-Мануса (Greg MacManus) из компании [VeriSign iDefense Labs](http://labs.idefense.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS08-052;
-   Бина Лю (Bing Liu) из [отдела FortiGuard Global Security Research](http://www.fortiguardcenter.com/) компании Fortinet за сообщение о проблеме, описанной в бюллетене MS08-052;
-   Питера Уинтер-Смита (Peter Winter-Smith) из компании [NGS Software](http://www.ngssoftware.com/) и Ивана Фратрича (Ivan Fratric), сотрудничающего с компанией [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в бюллетене MS08-052;
-   [отдел по исследованию уязвимостей, компания Assurent Secure Technologies](http://www.assurent.com/), за сообщение о проблеме, описанной в бюллетене MS08-052;
-   анонимного исследователя, сотрудничающего с компанией [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в бюллетене MS08-052;
-   Нгуйена Минх Дука (Nguyen Minh Duc) и Ле Манх Тунга (Le Manh Tung), сотрудничающих с [центром Bach Khoa Internetwork Security (BKIS) Ханойского технологического университета (Вьетнам)](http://security.bkis.vn/), за сообщение об уязвимости, описанной в бюллетене MS08-053;
-   Бретта Мура (Brett Moore) из компании [Insomnia Security](http://www.insomniasec.com/) за сообщение о проблеме, описанной в бюллетене MS08-055.

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов можно найти на веб-узле [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).
-   Обращайтесь в [службу поддержки продуктов корпорации Майкрософт](http://go.microsoft.com/fwlink/?linkid=21131) по телефону 1-866-PCSAFETY (для жителей США и Канады). Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно.
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-узел международной поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (9 сентября 2008 г.). Обзор бюллетеней опубликован.
-   Версия 2.0 (9 сентября 2008 г.). Обзор бюллетеней обновлен. В список подверженных уязвимости продуктов бюллетеня MS08-052 добавлено приложение Microsoft Office Project 2002 с пакетом обновления 2 (SP2), все средства просмотра Office для Microsoft Office 2003 и все средства просмотра Office для выпуска 2007 системы Microsoft Office.
-   Версия 2.1 (17 сентября 2008 г.). Обзор бюллетеней обновлен. В списке подверженных уязвимости продуктов приложение Microsoft Office Project 2002 с пакетом обновления 2 (SP2) заменено приложением Microsoft Office Project 2002 с пакетом обновления 1 (SP1). Это обновление касается только изменения названий. Оно не затрагивает двоичные файлы и процедуру обнаружения.
-   Версия 2.2 (29 октября 2008 г.). Обзор бюллетеней обновлен. Из списка подверженных уязвимости продуктов бюллетеня MS08-052 удалено средство просмотра Microsoft Visio 2003, средство просмотра Microsoft Visio 2007 и средство просмотра Microsoft Visio 2007 с пакетом обновления 1 (SP1).
-   Версия 3.0 (9 декабря 2008 г.). Обзор бюллетеней обновлен. В список подверженных уязвимости продуктов бюллетеня MS08-052 добавлены: пакет обеспечения совместимости форматов файлов Microsoft Office Word, Excel и PowerPoint 2007, пакет обеспечения совместимости форматов файлов Microsoft Office Word, Excel и PowerPoint 2007 с пакетом обновления 1 (SP1), Microsoft Expression Web, Microsoft Expression Web 2, Microsoft Office Groove 2007 и Microsoft Office Groove 2007 с пакетом обновления 1 (SP1).

*Built at 2014-04-18T01:50:00Z-07:00*
