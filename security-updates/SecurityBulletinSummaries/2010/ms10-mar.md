---
TOCTitle: 'MS10-MAR'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Март 2010 г.'
ms:assetid: 'ms10-mar'
ms:contentKeyID: 61236138
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms10-mar(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Март 2010 г.
===============================================================

Дата публикации: 9 марта 2010 г. | Дата обновления: 11 августа 2010 г.

**Версия:** 3.1

В этом обзоре указаны бюллетени по безопасности, выпущенные в марте 2010 г.

После выпуска мартовских бюллетеней данный обзор заменяет предварительное уведомление, выпущенное 4 марта 2010 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [Предварительное уведомление о бюллетенях по безопасности Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

10 марта 2010 г. в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в мартовской веб-трансляции, посвященной бюллетеням по безопасности](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427711&eventcategory=4&culture=en-us&countrycode=us). После наступления этой даты данная веб-трансляция будет доступна по запросу. Дополнительные сведения см. на веб-сайте [обзоров и веб-трансляций, посвященных бюллетеням Майкрософт по безопасности](http://technet.microsoft.com/security/bulletin/summary).

30 марта 2010 г. в 13:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проводит веб-трансляцию, в которой специалисты Майкрософт ответят на вопросы пользователей о внеплановом бюллетене MS10-002, добавленном в версии 2.0 настоящего обзора бюллетеней. [Зарегистрируйтесь прямо сейчас, чтобы принять участие в веб-трансляции, запланированной на 30 марта в 13:00 (по тихоокеанскому времени)](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032448112&culture=en-us). После наступления этой даты данная веб-трансляция будет доступна по запросу. Дополнительные сведения см. на веб-сайте [обзоров и веб-трансляций, посвященных бюллетеням Майкрософт по безопасности](http://technet.microsoft.com/security/bulletin/summary).

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
<th style="border:1px solid black;" >Максимальный уровень серьезности и воздействие уязвимости</th>
<th style="border:1px solid black;" >Необходимость перезагрузки</th>
<th style="border:1px solid black;" >Подвержены уязвимости</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=182969">MS10-018</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление безопасности для браузера Internet Explorer (980182)</strong> <br />
<br />
Это обновление для системы безопасности устраняет 9 обнаруженных пользователями и 1 опубликованную уязвимость в браузере Internet Explorer. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь просмотрит особым образом созданную веб-страницу в браузере Internet Explorer. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=183077">MS10-016</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Windows Movie Maker делает возможным удаленное выполнение кода (975561)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Windows Movie Maker и Microsoft Producer 2003. Приложение Киностудия Windows Live, которое предлагается для Windows Vista и Windows 7, не подвержено данной уязвимости. Эта уязвимость делает возможным удаленное выполнение кода, если злоумышленник отправит особым образом созданный файл проекта Movie Maker или Microsoft Producer и убедит пользователя открыть этот файл. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=182987">MS10-017</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Office Excel делают возможным удаленное выполнение кода (980150)</strong><br />
<br />
Это обновление для системы безопасности устраняет семь обнаруженных пользователями уязвимостей в Microsoft Office Excel. Эти уязвимости делают возможным удаленное выполнение кода при открытии пользователем особым образом созданного файла Excel. Злоумышленник, успешно воспользовавшийся любой из этих уязвимостей, может получить те же права, которыми обладает локальный пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
Индекс использования уязвимостей  
--------------------------------
  
<span></span>
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости перечислены в порядке убывания оценки индекса использования, затем по коду CVE.
  
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать о вероятности появления стабильно работающего кода эксплойта в течение 30 дней после выпуска бюллетеня по каждому из обновлений для системы безопасности, которые необходимо установить. Перед назначением приоритетов развертывания ознакомьтесь с каждой приведенной ниже оценкой, относящейся к конкретной конфигурации. Дополнительные сведения об уровнях опасности и способах их определения см. в [индексе использования уязвимостей](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| Идентификатор бюллетеня                                   | Название уязвимости                                                                                       | Код CVE                                                                          | Оценка индекса использования уязвимостей                                                                                        | Краткие примечания                                                              |  
|-----------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|  
| [MS10-017](http://go.microsoft.com/fwlink/?linkid=182987) | Уязвимость в Microsoft Office Excel, связанная с повреждением памяти искаженной записью                   | [CVE-2010-0257](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0257) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование стабильного кода эксплойта          | (Нет)                                                                           |  
| [MS10-017](http://go.microsoft.com/fwlink/?linkid=182987) | Уязвимость в Microsoft Office Excel, связанная с переполнением кучи записями MDXTUPLE                     | [CVE-2010-0260](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0260) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование стабильного кода эксплойта          | (Нет)                                                                           |  
| [MS10-017](http://go.microsoft.com/fwlink/?linkid=182987) | Уязвимость в Microsoft Office Excel, связанная с переполнением кучи записями MDXSET                       | [CVE-2010-0261](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0261) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование стабильного кода эксплойта          | (Нет)                                                                           |  
| [MS10-017](http://go.microsoft.com/fwlink/?linkid=182987) | Уязвимость в Microsoft Office Excel, делающая возможным выполнение кода анализа XLSX-файлов               | [CVE-2010-0263](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0263) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование стабильного кода эксплойта          | (Нет)                                                                           |  
| [MS10-017](http://go.microsoft.com/fwlink/?linkid=182987) | Уязвимость в Microsoft Office Excel, связанная с анализом записей DbOrParamQry                            | [CVE-2010-0264](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0264) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование стабильного кода эксплойта          | (Нет)                                                                           |  
| [MS10-016](http://go.microsoft.com/fwlink/?linkid=183077) | Уязвимость в Movie Maker и Producer, связанная с переполнением буфера                                     | [CVE-2010-0265](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0265) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование стабильного кода эксплойта          | (Нет)                                                                           |  
| [MS10-018](http://go.microsoft.com/fwlink/?linkid=182969) | Уязвимость, связанная с повреждением памяти при обращении к HTML-объектам                                 | [CVE-2010-0491](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0491) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование стабильного кода эксплойта          | (Нет)                                                                           |  
| [MS10-018](http://go.microsoft.com/fwlink/?linkid=182969) | Уязвимость, связанная с повреждением памяти при обращении к HTML-объектам                                 | [CVE-2010-0492](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0492) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование стабильного кода эксплойта          | (Нет)                                                                           |  
| [MS10-018](http://go.microsoft.com/fwlink/?linkid=182969) | Междоменная уязвимость элемента HTML                                                                      | [CVE-2010-0494](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0494) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование стабильного кода эксплойта          | Выполнение кода возможно только в Windows 2000                                  |  
| [MS10-018](http://go.microsoft.com/fwlink/?linkid=182969) | Уязвимость, приводящая к повреждению неинициализированной области памяти                                  | [CVE-2010-0806](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0806) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование стабильного кода эксплойта          | **На данный момент известны примеры использования этой уязвимости в Интернете** |  
| [MS10-018](http://go.microsoft.com/fwlink/?linkid=182969) | Уязвимость отображения HTML-данных, приводящая к повреждению памяти                                       | [CVE-2010-0807](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0807) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование стабильного кода эксплойта          | (Нет)                                                                           |  
| [MS10-017](http://go.microsoft.com/fwlink/?linkid=182987) | Уязвимость, связанная с путаницей типов объектов в таблице Microsoft Office Excel                         | [CVE-2010-0258](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0258) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование нестабильного кода эксплойта        | (Нет)                                                                           |  
| [MS10-017](http://go.microsoft.com/fwlink/?linkid=182987) | Уязвимость в Microsoft Office Excel, связанная с неинициализированной областью памяти записей FNGROUPNAME | [CVE-2010-0262](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0262) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование нестабильного кода эксплойта        | (Нет)                                                                           |  
| [MS10-018](http://go.microsoft.com/fwlink/?linkid=182969) | Уязвимость, приводящая к повреждению памяти из-за состояния гонки                                         | [CVE-2010-0489](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0489) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование нестабильного кода эксплойта        | (Нет)                                                                           |  
| [MS10-018](http://go.microsoft.com/fwlink/?linkid=182969) | Уязвимость, приводящая к повреждению памяти                                                               | [CVE-2010-0805](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0805) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование нестабильного кода эксплойта        | (Нет)                                                                           |  
| [MS10-018](http://go.microsoft.com/fwlink/?linkid=182969) | Уязвимость, приводящая к повреждению неинициализированной области памяти                                  | [CVE-2010-0267](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0267) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - существование функционирующего кода эксплойта маловероятно | (Нет)                                                                           |  
| [MS10-018](http://go.microsoft.com/fwlink/?linkid=182969) | Уязвимость последующего кодирования, приводящая к раскрытию информации                                    | [CVE-2010-0488](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0488) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - существование функционирующего кода эксплойта маловероятно | (Нет)                                                                           |  
| [MS10-018](http://go.microsoft.com/fwlink/?linkid=182969) | Уязвимость, приводящая к повреждению неинициализированной области памяти                                  | [CVE-2010-0490](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0490) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - существование функционирующего кода эксплойта маловероятно | (Нет)                                                                           |
  
Продукты, подверженные уязвимости, и соответствующие обновления  
---------------------------------------------------------------
  
<span></span>
В приведенных ниже таблицах перечислены бюллетени в порядке важности категорий программного обеспечения и уровней опасности.
  
**Как пользоваться этими таблицами?**
  
Обращайтесь к этим таблицам, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и узнайте, имеются ли для них обновления для системы безопасности. Для программ или компонентов, указанных в списке, приведены ссылки на доступные обновления с указанием уровня опасности уязвимостей, которые они устраняют.
  
**Примечание**. Для устранения одной уязвимости может потребоваться установка нескольких обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификатора бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.
  
#### Компоненты операционных систем Windows

 
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
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://go.microsoft.com/fwlink/?linkid=183077)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://go.microsoft.com/fwlink/?linkid=182969)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
Нет
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
[Internet Explorer 5.01 с пакетом обновления 4 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=389da7a9-e0a3-4b5d-801e-0a38fc55dcec)  
(критический)  
[Internet Explorer 6 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=daf199c4-da56-4a7f-80e6-3936ce5c267b)  
(критический)
</td>
</tr>
<tr>
<th colspan="3">
ОС Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://go.microsoft.com/fwlink/?linkid=183077)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://go.microsoft.com/fwlink/?linkid=182969)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Movie Maker 2.1](http://www.microsoft.com/downloads/details.aspx?familyid=6301e462-02be-4b9a-bae9-7c4821b42d2d)<sup>[1]</sup>
(существенный)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=2f2caa01-5cd1-45cb-9995-e34d933920d4)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=167ed896-d383-4dc0-9183-cd4cb73e17e7)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=46172617-293a-44c7-95b6-18202ab06a41)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Movie Maker 2.1](http://www.microsoft.com/downloads/details.aspx?familyid=cae81585-d0df-41b8-9277-ca02f1265056)<sup>[1]</sup>
(существенный)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=6c711387-6853-477c-917e-820a97613cf9)  
(критический)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=aadb1d97-5cec-45ed-9967-aaf41a0bcdac)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=284d70ea-24a3-4e67-a2a8-e9f272f728db)  
(критический)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://go.microsoft.com/fwlink/?linkid=183077)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://go.microsoft.com/fwlink/?linkid=182969)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=dc77f1c9-8240-42d9-aee9-30ac4f33bde7)  
(существенный)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e957a7cf-e5ca-454d-b199-ec8fe6a6a2bf)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=53fc3285-63c4-487f-ad9a-7e1673aeffc7)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=2be85462-28ec-4184-a326-0459554b7213)  
(существенный)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=cb0e39f8-9730-4454-a0e3-479b610b1591)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5201a0c5-8162-4809-b9d1-0e972b0f0066)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=04abea55-ea2f-423f-b410-5536ea184ea3)  
(существенный)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=7ebd99b4-da6b-4dff-9f89-6a86d275a3da)  
(критический)
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://go.microsoft.com/fwlink/?linkid=183077)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://go.microsoft.com/fwlink/?linkid=182969)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Movie Maker 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=ae2e9b75-1616-4fe3-91bb-e2e28252ff1c)<sup>[1]</sup>
(существенный)  
[Movie Maker 2.6](http://www.microsoft.com/downloads/details.aspx?familyid=ca2d1118-ca64-419d-86af-9396e61b90b0)<sup>[2]</sup>
(существенный)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=511aba0e-6f15-42cf-9c5d-b2f3e215b5a8)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c9584689-5196-4840-927c-23c8038f3382)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Movie Maker 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e27f353e-deb6-4d61-8808-c751d20a42a1)<sup>[1]</sup>
(существенный)  
[Movie Maker 2.6](http://www.microsoft.com/downloads/details.aspx?familyid=6a1f4126-97f2-4aee-bfe1-05bd13a0667b)<sup>[2]</sup>
(существенный)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=c8933a45-62a7-4c19-be30-02e3a461f081)  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=50809cc3-6baa-41b4-ba0a-596a1dd846ed)  
(критический)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://go.microsoft.com/fwlink/?linkid=183077)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://go.microsoft.com/fwlink/?linkid=182969)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=42f8c1f2-ee55-47af-b113-8d9f4bd40c8f)\*\*  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c69a6dfe-66b1-4426-96a5-d64000296e76)\*\*  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем и Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=769043b5-df52-4446-9bd8-dc37d9fa00df)\*\*  
(критический)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e16c10d2-896d-48f3-bc76-5fa70881396a)\*\*  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=c1c2309d-22db-4dbf-ad95-3219847cd42d)  
(критический)
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://go.microsoft.com/fwlink/?linkid=183077)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://go.microsoft.com/fwlink/?linkid=182969)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c0145563-428e-47b6-b245-b59dce88ac0e)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=6172dbec-6bfc-40bd-a0d4-67c39fb41b87)  
(критический)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://go.microsoft.com/fwlink/?linkid=183077)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://go.microsoft.com/fwlink/?linkid=182969)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8b7c664b-8612-458f-bd0a-cf28b67f8374)\*\*  
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=82fa6f47-002f-4943-888c-2e852675e76e)  
(средний)
</td>
</tr>
</table>
 
**Примечание для Windows Server 2008 и Windows Server 2008 R2**

**\*\*Уязвимости не подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Поддерживаемые выпуски Windows Server 2008 или Windows Server 2008 R2, при развертывании которых выбиралась установка только ядра сервера, не подвержены уязвимостям, устраняемым этим обновлением. Дополнительные сведения об этом варианте установки см. в статьях MSDN [Ядро сервера](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) и [Ядро сервера для Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Примечания для MS10-016**

<sup>[1]</sup>Эти версии Windows Movie Maker поставляются с указанными операционными системами.

<sup>[2]</sup>Приложение Windows Movie Maker 2.6 загружается отдельно и может быть установлено в указанных операционных системах.

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе Продукты, подверженные уязвимости, и соответствующие обновления. Это бюллетень относится к нескольким категориям ПО.

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
[**MS10-017**](http://go.microsoft.com/fwlink/?linkid=182987)
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://go.microsoft.com/fwlink/?linkid=183077)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=e0136f62-60ce-4ebd-8660-be81eba29ae8)  
(KB978471)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=7e42793e-747b-48da-968a-1ec29ea37151)  
(KB978474)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
система Microsoft Office 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 с пакетом обновления 1 (SP1) и Microsoft Office Excel 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=03429f8a-8aab-4a59-97e4-7ce047f100a5)<sup>[1]</sup>
(KB978382)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office для Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-017**](http://go.microsoft.com/fwlink/?linkid=182987)
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://go.microsoft.com/fwlink/?linkid=183077)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 для Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=ae5936f8-fe3f-4d23-a37c-d80f228e475e)  
(KB980837)  
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
[Microsoft Office 2008 для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=e0ed1569-ab2f-407c-b728-4eddc463c385)  
(KB980839)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Конвертер форматов файлов Open XML для Mac
</td>
<td style="border:1px solid black;">
[Конвертер форматов файлов Open XML для Mac](http://www.microsoft.com/downloads/details.aspx?familyid=4c5487d5-c912-4087-8c83-769e3fb78ea9)  
(KB980840)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Другое программное обеспечение Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-017**](http://go.microsoft.com/fwlink/?linkid=182987)
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://go.microsoft.com/fwlink/?linkid=183077)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
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
Средство просмотра Microsoft Office Excel
</td>
<td style="border:1px solid black;">
[Средство просмотра Microsoft Office Excel с пакетом обновления 1 (SP1) и средство просмотра Microsoft Office Excel с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=010d0a4d-02a4-4142-963b-a38cd06cc897)  
(KB978383)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Для пакета обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007
</td>
<td style="border:1px solid black;">
[Пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007 с пакетом обновления 1 (SP1) и пакет обеспечения совместимости Microsoft Office для форматов файлов Word, Excel и PowerPoint 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=314f076e-8f9d-46c2-b666-86599a02bf15)  
(KB978380)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 (32-разрядные выпуски)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 с пакетом обновления 1 (SP1) и Microsoft Office SharePoint Server 2007 с пакетом обновления 2 (SP2) (32-разрядные выпуски)](http://www.microsoft.com/downloads/details.aspx?familyid=94ddf6ef-3392-4d77-a02b-3bc0470721cd)<sup>[2]</sup>
(KB979439)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 (64-разрядные выпуски)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 с пакетом обновления 1 (SP1) и Microsoft Office SharePoint Server 2007 с пакетом обновления 2 (SP2) (64-разрядные выпуски)](http://www.microsoft.com/downloads/details.aspx?familyid=06f6bffb-3fad-4fb5-878b-39550812e9b5)<sup>[2]</sup>
(KB979439)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Producer 2003
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Producer 2003](http://www.microsoft.com/downloads/details.aspx?familyid=1b3c76d5-fc75-4f99-94bc-784919468e73)<sup>[3]</sup>
(существенный)
</td>
</tr>
</table>
 
**Примечания для MS10-017**

<sup>[1]</sup>Для Microsoft Office Excel 2007 с пакетом обновления 1 (SP1) и Microsoft Office Excel 2007 с пакетом обновления 2 (SP2): чтобы обеспечить защиту приложений от уязвимостей, описанных в данном бюллетене, помимо обновления KB978382 необходимо также установить обновление безопасности для [пакета обеспечения совместимости форматов файлов Microsoft Office Word, Excel и PowerPoint 2007 с пакетом обновления 1 (SP1) и пакета обеспечения совместимости форматов файлов Microsoft Office Word, Excel и PowerPoint 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=314f076e-8f9d-46c2-b666-86599a02bf15) (KB978380).

<sup>[2]</sup>Это обновление предназначено для серверов, на которых установлены службы Excel (таких как серверы Microsoft Office SharePoint Server 2007 Enterprise и Microsoft Office SharePoint Server 2007 for Internet Sites в конфигурациях по умолчанию). Сервер Microsoft Office SharePoint Server 2007 не содержит службы Excel.

**Примечания для MS10-016**

<sup>[3]</sup>Этот загружаемый файл обновляет Microsoft Producer 2003 до новой версии — Microsoft Producer. Для Microsoft Producer имеется только англоязычная версия.

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе Продукты, подверженные уязвимости, и соответствующие обновления. Это бюллетень относится к нескольким категориям ПО.

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
**В центре безопасности**

Управление программным обеспечением и обновлениями для системы безопасности для установки на серверы, настольные и переносные компьютеры организации. Дополнительные сведения см. на веб-сайте [Центра управления обновлениями TechNet](http://go.microsoft.com/fwlink/?linkid=69903). [Центр безопасности TechNet](http://go.microsoft.com/fwlink/?linkid=21171) содержит дополнительные сведения о безопасности в продуктах Майкрософт. Доступ к этим сведениям можно также получить, посетив веб-сайт [Безопасность дома](http://go.microsoft.com/fwlink/?linkid=85102) и щелкнув ссылку "Последние обновления".

Обновления для системы безопасности доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747) и [Центре обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130). Обновления для системы безопасности также доступны на веб-сайте [Центра загрузки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".

Наконец, обновления для системы безопасности можно загрузить из [каталога Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=96155). Он обеспечивает возможность поиска содержимого (в том числе обновлений для системы безопасности, драйверов и пакетов обновления), которое предоставляется через Центр обновления Windows и Центр обновления Майкрософт. При поиске по номеру бюллетеня по безопасности (например, MS07-036) можно добавлять необходимые обновления (в том числе на различных языках) в корзину и загружать их в указанную папку. Дополнительные сведения см. на веб-сайте каталога Центра обновления Майкрософт в разделе [вопросов и ответов](http://go.microsoft.com/fwlink/?linkid=97900).

**Примечание**. С 1 августа 2009 г. Майкрософт прекратила поддержку центра загрузки Office и средства инвентаризации центра загрузки Office. Чтобы продолжить получать последние обновления для продуктов Microsoft Office, используйте веб-сайт [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747). Дополнительные сведения см. на веб-странице [Центр загрузки Microsoft Office: вопросы и ответы](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Руководство по диагностике и развертыванию**

Корпорация Майкрософт предоставляет руководство по диагностике и развертыванию обновлений для системы безопасности. В этом руководстве содержатся рекомендации и сведения, позволяющие ИТ-специалистам оптимальнее использовать различные средства для диагностики и развертывания обновлений для системы безопасности. Дополнительные сведения см. в [статье 961747 базы знаний Майкрософт](http://support.microsoft.com/kb/961747).

**Анализатор безопасности Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений безопасности и стандартных ошибок в конфигурации системы безопасности. Дополнительные сведения об анализаторе безопасности MBSA см. на веб-сайте [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Службы Windows Server Update Services**

Службы Windows Server Update Services (WSUS) позволяют администраторам быстрым и надежным образом развертывать последние критические обновления и обновления для систем безопасности операционных систем Microsoft Windows 2000 и более поздних версий, пакетов Office XP и более поздних версий, серверов Exchange Server 2003 и SQL Server 2000 в системах Microsoft Windows 2000 и более поздних версий.

Дополнительные сведения о развертывании данного обновления безопасности с помощью служб WSUS см. на веб-сайте [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Сервер Systems Management Server**

Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет хорошо сконфигурированное решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей. Последний выпуск сервера SMS — System Center Configuration Manager 2007 — доступен для загрузки; сведения о нем см. также на веб-сайте [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Дополнительные сведения о том, как администраторы могут использовать сервер SMS 2003 для развертывания обновлений для системы безопасности, см. на веб-странице [Управление исправлениями для системы безопасности сервера SMS 2003](http://go.microsoft.com/fwlink/?linkid=22939). Для развертывания обновлений системы безопасности пользователям сервера SMS 2.0 доступно средство Security Update Inventory Tool (SUIT). Дополнительные сведения о сервере SMS см. на веб-сайте [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Примечание**. Для предоставления широкой поддержки при определении необходимости применения и развертывания обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используется средство Microsoft Baseline Security Analyzer. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. в статье [Развертывание обновлений программного обеспечения с помощью функции распространения программ сервера SMS](http://go.microsoft.com/fwlink/?linkid=33341). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакета [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

**Средство оценки совместимости обновлений и набор средств для обеспечения совместимости приложений**

Часто обновления записываются в одни те же файлы, а для запуска приложений требуется настроить параметры реестра. Это приводит к возникновению несовместимостей и увеличивает время, затрачиваемое на развертывание обновлений для системы безопасности. Облегчить тестирование и проверку обновлений Windows для установленных приложений можно с помощью [компонентов оценки совместимости обновлений](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true), входящих в состав [набора средств для обеспечения совместимости приложений](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Набор средств для обеспечения совместимости приложений содержит необходимые средства и документацию для выявления проблем совместимости приложений и уменьшения степени воздействия этих проблем перед развертыванием системы Microsoft Windows Vista, обновлений из Центра обновления Windows, обновлений с веб-сайта безопасности Майкрософт или новой версии проводника.

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

#### Высокоприоритетные обновления, не относящиеся к безопасности и распространяемые через Центр обновления Майкрософт, Центр обновления Windows и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-сайте Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт:](http://support.microsoft.com/kb/894199) Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
-   [Обновления за предыдущие месяцы для служб Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Отображаются все новые, обновленные и повторно выпущенные обновления для продуктов Майкрософт отличных от Microsoft Windows.

#### Программа Microsoft Active Protections Program (MAPP)

Чтобы повысить уровень защиты пользователей, корпорация Майкрософт предоставляет сведения об уязвимостях крупным поставщикам программного обеспечения безопасности перед ежемесячным выпуском обновлений. Эта информация необходима им для усовершенствования программного обеспечения и оборудования для защиты пользователей (антивирусных программ, сетевых систем обнаружения вторжений, а также индивидуальных систем предотвращения вторжений). Сведения о новых средствах защиты, предоставляемых поставщиками программного обеспечения безопасности, доступны на соответствующих веб-сайтах партнеров, перечисленных в списке партнеров [MAPP](http://www.microsoft.com/security/msrc/mapp/partners.mspx).

#### Стратегии безопасности и сообщество

**Стратегии управления обновлениями**

В статье [Рекомендации по безопасности для управления обновлениями](http://go.microsoft.com/fwlink/?linkid=21168) содержатся дополнительные сведения о рекомендациях Майкрософт по установке обновлений для системы безопасности.

**Другие обновления для системы безопасности**

Другие обновления безопасности можно загрузить из следующих источников:

-   Обновления для системы безопасности доступны на веб-сайте [Центра загрузки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".
-   Обновления для индивидуальных пользователей доступны на веб-сайте [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747).
-   Обновления безопасности, предлагаемые в этом месяце в Центре обновления Windows, можно загрузить с веб-сайта Центра загрузки Майкрософт в виде файлов ISO-образа компакт-диска с выпусками обновлений безопасности. Дополнительные сведения см. в [статье 913086 базы знаний Майкрософт](http://support.microsoft.com/kb/913086).

**Сообщество ИТ-специалистов, занимающихся вопросами безопасности**

На веб-сайте [сообщества ИТ-специалистов, занимающихся вопросами безопасности](http://go.microsoft.com/fwlink/?linkid=21164), можно найти сведения о способах улучшения системы безопасности и оптимизации ИТ-инфраструктуры предприятия, а также обсудить вопросы безопасности с другими ИТ-специалистами.

#### Благодарности

Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:

-   Дамиана Фризза (Damián Frizza) из [Core Security Technologies](http://www.coresecurity.com/) за сообщение о проблеме, описанной в бюллетене по безопасности MS10-016;
-   Николя Жоли (Nicolas Joly) из [VUPEN Vulnerability Research Team](http://www.vupen.com/) за сообщение о проблеме, описанной в MS10-017
-   Шона Ларссона (Sean Larsson) из [VeriSign iDefense Labs](http://labs.idefense.com/) за сообщение о четырех проблемах, описанных в бюллетене MS10-017;
-   анонимного исследователя, сотрудничающего с компанией [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в MS10-017;
-   Дамиана Фризза (Damián Frizza) из [Core Security Technologies](http://www.coresecurity.com/) за сообщение о проблеме, описанной в MS10-017;
-   [Компанию Secunia](http://secunia.com) за совместную работу над устранением проблемы, описанной в бюллетене MS10-018
-   Дайки Фукумори (Daiki Fukumori) из [Cyber Defense Institute Inc.](http://www.cyberdefense.jp/) за сообщение о проблеме, описанной в бюллетене MS10-018;
-   Александра Корнберста (Alexander Kornbrust) из [Red Database Security](http://www.red-database-security.com/) за сообщение о проблеме, описанной в бюллетене MS10-018;
-   Ивана Фратрича (Ivan Fratric) из компании [iSIGHT Partners](http://www.isightpartners.com/) Global Vulnerability Partnership за сообщение о проблеме, описанной в бюллетене MS10-018;
-   Вуши (Wushi) из [компании team509](http://www.team509.com/), работающей с [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение о проблеме, описанной в бюллетене MS10-018;
-   Саймона Цукербрауна (Simon Zuckerbraun), работающего с [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в бюллетене MS10-018;
-   Пола Стоуна (Paul Stone) из [Context Information Security](http://www.contextis.co.uk/) за сообщение о проблеме, описанной в бюллетене MS10-018;
-   анонимного исследователя, сотрудничающего с компанией [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в MS10-018;
-   ADLab из [VenusTech](http://www.venustech.com.cn/) за сообщение о проблемах, описанных в бюллетене MS10-018.

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Пользователи из США и Канады могут обратиться в службу [поддержки по вопросам безопасности](http://go.microsoft.com/fwlink/?linkid=21131) или позвонить по телефону 1-866-PCSAFETY. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Дополнительные сведения о вариантах поддержки см. на веб-сайте [справки и поддержки корпорации Майкрософт](http://support.microsoft.com/).
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-сайт международной справки и поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (9 марта 2010 г.): Обзор бюллетеней опубликован.
-   Вер. 2.0 (30 марта 2010): Добавлен бюллетень по безопасности (Майкрософт) MS10-018 "Накопительное обновление для системы безопасности браузера Internet Explorer (978207)", а также ссылка на сведения о веб-трансляции, посвященной внеплановому бюллетеню по безопасности.
-   Вер. 3.0 (3 мая 2010): Добавлена информация о выпуске загружаемого файла для Microsoft Producer, связанного с MS10-016.
-   Вер. 3.1 (11 августа 2010): В бюллетене MS10-016 из списка уязвимых компонентов в Windows 7 удалено упоминание Windows Movie Maker 2.6.

*Built at 2014-04-18T01:50:00Z-07:00*
