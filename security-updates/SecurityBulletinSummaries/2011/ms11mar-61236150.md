---
TOCTitle: 'MS11-MAR'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Март 2011 г.'
ms:assetid: 'ms11-mar'
ms:contentKeyID: 61236150
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms11-mar(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Март 2011 г.
===============================================================

Дата публикации: 8 марта 2011 г. | Дата обновления: 16 марта 2011 г.

**Версия:** 1.1

В этом обзоре указаны бюллетени по безопасности, выпущенные в марте 2011 г.

После выпуска бюллетеней за март 2011 г. этот обзор заменит предварительное уведомление, выпущенное 3 марта 2011 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://technet.microsoft.com/security/bulletin/advance).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

9 марта 2011 г. в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проводит веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в мартовской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032455049&eventcategory=4). После наступления этой даты данная веб-трансляция будет доступна по запросу. Дополнительные сведения см. на веб-сайте [обзоров и веб-трансляций, посвященных бюллетеням Майкрософт по безопасности](http://technet.microsoft.com/security/bulletin/summary).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел **Прочие сведения**.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207841">MS11-015</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Windows Media делают возможным удаленное выполнение кода (2510030)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну опубликованную уязвимость в DirectShow и одну обнаруженную пользователями уязвимость в Windows Media Player и Windows Media Center. Наиболее серьезная из этих уязвимостей делает возможным удаленное выполнение кода при открытии пользователем особым образом созданного файла цифровой видеозаписи Microsoft (.dvr-ms). Однако в любом случае злоумышленник не может заставить пользователя открыть файл; чтобы атака была успешной, злоумышленнику необходимо убедить пользователя сделать это.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207892">MS11-017</a></td>
<td style="border:1px solid black;"><strong>Уязвимость клиента удаленного рабочего стола делает возможным удаленное выполнение кода (2508062)</strong><br />
<br />
Данное обновление для системы безопасности устраняет опубликованную уязвимость клиента удаленного рабочего стола Windows. Эта уязвимость делает возможным удаленное выполнение кода, если пользователь откроет подлинный файл конфигурации удаленного рабочего стола (.rdp), расположенный в том же сетевом каталоге, что и особым образом созданный файл библиотеки. Чтобы атака была успешной, пользователь должен посетить недоверенную папку в удаленной файловой системе или общий ресурс WebDAV и открыть находящийся в этой папке документ, который затем загружается уязвимым приложением.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=209774">MS11-016</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Groove делает возможным удаленное выполнение кода (2494047)</strong><br />
<br />
Это обновление для системы безопасности устраняет опубликованную уязвимость в Microsoft Groove, которая делает возможным удаленное выполнение кода в том случае, если пользователь откроет подлинный файл, связанный с Groove, расположенный в том же сетевом каталоге, что и особым образом созданный файл библиотеки. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
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
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости перечислены в порядке убывания оценки индекса использования, затем по коду CVE. Включены только уязвимости, которым в бюллетенях присвоен уровень серьезности "критический" или "существенный".
  
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать о вероятности появления стабильно работающего кода эксплойта в течение 30 дней после выпуска бюллетеня по каждому из обновлений для системы безопасности, которые необходимо установить. Перед назначением приоритетов развертывания ознакомьтесь с каждой приведенной ниже оценкой, относящейся к конкретной конфигурации. Дополнительные сведения об уровнях опасности и способах их определения см. в [индексе использования уязвимостей](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| Идентификатор бюллетеня                                   | Название уязвимости                                                                         | Код CVE                                                                          | Оценка индекса использования уязвимостей                                                                           | Краткие примечания                                                                              |  
|-----------------------------------------------------------|---------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|  
| [MS11-016](http://go.microsoft.com/fwlink/?linkid=209774) | Уязвимость, связанная с небезопасной загрузкой библиотек в Microsoft Groove                 | [CVE-2010-3146](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3146) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта | **О данной уязвимости сообщалось в открытых источниках, и демонстрационный код (PoC) доступен** |  
| [MS11-017](http://go.microsoft.com/fwlink/?linkid=207892) | Уязвимость, связанная с небезопасной загрузкой библиотек клиентом удаленного рабочего стола | [CVE-2011-0029](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0029) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта | **О данной уязвимости сообщалось в открытых источниках**                                        |  
| [MS11-015](http://go.microsoft.com/fwlink/?linkid=207841) | Уязвимость, связанная с небезопасной загрузкой библиотек в DirectShow                       | [CVE-2011-0032](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0032) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта | **О данной уязвимости сообщалось в открытых источниках, и демонстрационный код (PoC) доступен** |  
| [MS11-015](http://go.microsoft.com/fwlink/?linkid=207841) | Уязвимость DVR-MS                                                                           | [CVE-2011-0042](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0042) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта | (Нет)                                                                                           |
  
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
ОС Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-015**](http://go.microsoft.com/fwlink/?linkid=207841)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://go.microsoft.com/fwlink/?linkid=207892)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
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
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=d8284bfa-ed6c-4647-9fb0-588e53173775)  
(KB2479943)  
(критический)  
[Windows XP Media Center Edition 2005 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=b1be30de-7e88-467d-aee2-68f88e6a7355)  
(KB2502898)  
(критический)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 5.2](http://www.microsoft.com/downloads/details.aspx?familyid=1aed6080-feab-4b5e-9d26-6a3f4b92434d)  
(KB2483618)  
(существенный)  
[Клиент подключения к удаленному рабочему столу 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=d67e4d8c-aeb9-45e6-9555-7456c5540475)  
(KB2481109)  
(существенный)  
[Клиент подключения к удаленному рабочему столу 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=6a01992e-c9a1-4dc9-a3ef-7410b81f17e6)  
(KB2483614)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5270b5d3-3720-42a2-a8cf-67089c0cc658)  
(KB2479943)  
(критический)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=6d4539ef-4a05-4c7d-9489-436f7b7a3ebe)<sup>[1]</sup>
(KB2481109)  
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
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-015**](http://go.microsoft.com/fwlink/?linkid=207841)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://go.microsoft.com/fwlink/?linkid=207892)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Клиент подключения к удаленному рабочему столу 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=641d5d12-0790-4551-831a-e78febad17a7)<sup>[1]</sup>
(KB2481109)  
(существенный)  
[Клиент подключения к удаленному рабочему столу 6.0 с многоязыковым интерфейсом пользователя (MUI)](http://www.microsoft.com/downloads/details.aspx?familyid=6fec0d06-042d-4e55-9843-009edd7d26ce)<sup>[2]</sup>
(KB2483619)  
(существенный)
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
[Клиент подключения к удаленному рабочему столу 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=78dbb9cf-8a18-4f0a-8edf-f1ce0c993c63)<sup>[1]</sup>
(KB2481109)  
(существенный)
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
[**MS11-015**](http://go.microsoft.com/fwlink/?linkid=207841)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://go.microsoft.com/fwlink/?linkid=207892)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
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
Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=f9f1dde2-2219-4bf1-a497-edd011577b96)<sup>[1]</sup>
(KB2479943)  
(критический)  
[Windows Media Center TV Pack для Windows Vista (32-разрядные версии](http://www.microsoft.com/downloads/details.aspx?familyid=1bc240b3-1938-4350-b26f-67b81a79f8a0))<sup>[2]</sup>
(KB2494132)  
(критический)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=e3ea7690-386b-4cdf-889f-b3914921c56f)  
(KB2481109)  
(существенный)  
[Клиент подключения к удаленному рабочему столу 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=3c30f67e-7c31-4553-ba3e-e056df1bf8eb)  
(KB2483614)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e11d00df-d1cf-4a33-a1be-6721cdff5995)<sup>[1]</sup>
(KB2479943)  
(критический)  
[Windows Media Center TV Pack для Windows Vista (64-разрядные версии](http://www.microsoft.com/downloads/details.aspx?familyid=cd4c5a80-db24-4696-a248-1286c3b9f550))<sup>[2]</sup>
(KB2494132)  
(критический)
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=5735bed6-0e3d-46a4-85d0-14ec34a82edd)  
(KB2481109)  
(существенный)  
[Клиент подключения к удаленному рабочему столу 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=8025482b-f58f-4f5a-a133-5563c65b21f6)  
(KB2483614)  
(существенный)
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
[**MS11-015**](http://go.microsoft.com/fwlink/?linkid=207841)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://go.microsoft.com/fwlink/?linkid=207892)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Клиент подключения к удаленному рабочему столу 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=31d790c9-92f9-4a2b-800b-8e8d2b570bb9)\*\*  
(KB2481109)  
(существенный)
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
[Клиент подключения к удаленному рабочему столу 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=5b0a8eb5-4bc2-4054-b952-58aa645afcf5)\*\*  
(KB2481109)  
(существенный)
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
[Клиент подключения к удаленному рабочему столу 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=25da7e00-745d-4d98-9dd8-52a8a4340404)  
(KB2481109)  
(существенный)
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
[**MS11-015**](http://go.microsoft.com/fwlink/?linkid=207841)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://go.microsoft.com/fwlink/?linkid=207892)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
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
Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1be77daa-29b1-4dae-a87f-2cb8f7e6a305)  
(KB2479943)  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows 7 для 32-разрядных систем:  
[Клиент подключения к удаленному рабочему столу 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=0768a5f4-da28-4b2e-8aff-d68f890df3e6)  
(KB2483614)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=56fb24ce-65c7-4573-b613-e424ccc1a3a6)  
(KB2479943)  
(критический)
</td>
<td style="border:1px solid black;">
Только Windows 7 для 64-разрядных систем:[Клиент подключения к удаленному рабочему столу 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=935adb10-1e7e-4501-b543-8247b88f6d18)  
(KB2483614)  
(существенный)
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
[**MS11-015**](http://go.microsoft.com/fwlink/?linkid=207841)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://go.microsoft.com/fwlink/?linkid=207892)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=6f45658a-1db8-4ef5-b840-4d0180d4d90e)\*\*  
(KB2479943)  
(существенный)
</td>
<td style="border:1px solid black;">
Только Windows Server 2008 R2 для 64-разрядных систем:  
[Клиент подключения к удаленному рабочему столу 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=3fcb2e11-591e-484a-a992-2f1d563e6d17)\*\*  
(KB2483614)  
(существенный)
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
[Клиент подключения к удаленному рабочему столу 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=c29b6487-78f0-421c-810c-c5e45d6a2352)  
(KB2483614)  
(существенный)
</td>
</tr>
</table>
 
**Примечание для Windows Server 2008 и Windows Server 2008 R2**

**\*\*Уязвимости не подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Поддерживаемые выпуски Windows Server 2008 или Windows Server 2008 R2, при развертывании которых выбиралась установка только ядра сервера, не подвержены уязвимостям, устраняемым этим обновлением. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Примечания к бюллетеню MS11-015**

<sup>[1]</sup>См. примечание <sup>[2]</sup> ниже о Windows Media Center TV Pack для Windows Vista.

<sup>[2]</sup>Пакет Windows Media Center TV Pack для Windows Vista доступен только в качестве дополнительного компонента для OEM-систем с установленными выпусками Windows Vista Home Premium и Windows Vista Ultimate. Пользователям, в системах которых установлен этот дополнительный компонент, следует установить оба обновления. В соответствии общепринятой практикой Майкрософт настоятельно рекомендует установить обновление для операционной системы (KB2479943) перед установкой обновления для Windows Media Center TV Pack (KB2494132).

**Примечания к бюллетеню MS11-017**

<sup>[1]</sup>Этот загружаемый файл обновляет Клиент подключения к удаленному рабочему столу 6.0 до версии Клиента подключения к удаленному рабочему столу 6.1, не подверженной уязвимости.

<sup>[2]</sup>Этот загружаемый файл обновляет Клиент подключения к удаленному рабочему столу 6.0 с многоязыковым интерфейсом пользователя (MUI) до версии Клиента подключения к удаленному рабочему столу 6.1 с многоязыковым интерфейсом пользователя (MUI), не подверженной уязвимости.

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
Программы Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-016**](http://go.microsoft.com/fwlink/?linkid=209774)
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
Microsoft Groove 2007
</td>
<td style="border:1px solid black;">
[Microsoft Groove 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3981ab53-1082-4155-9000-11d8a976ff33)  
(KB2494047)  
(существенный)
</td>
</tr>
</table>
 

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
**В центре безопасности**

Управление программным обеспечением и обновлениями для системы безопасности для установки на серверы, настольные и переносные компьютеры организации. Дополнительные сведения см. на веб-сайте [Центра управления обновлениями TechNet](http://go.microsoft.com/fwlink/?linkid=69903). [Центр безопасности TechNet](http://go.microsoft.com/fwlink/?linkid=21171) содержит дополнительные сведения о безопасности в продуктах Майкрософт. Доступ к этим сведениям можно также получить, посетив веб-сайт [Безопасность дома](http://go.microsoft.com/fwlink/?linkid=85102) и щелкнув ссылку "Последние обновления".

Обновления для системы безопасности доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747) и [Центре обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130). Обновления для системы безопасности также доступны на веб-сайте [Центра загрузки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".

Пользователи пакета Microsoft Office для Mac могут следить за установкой последних версий программного обеспечения Майкрософт при помощи приложения Microsoft AutoUpdate для Mac. Дополнительные сведения об использовании приложения Microsoft AutoUpdate для Mac см. в статье [Автоматическая проверка наличия обновлений для программного обеспечения](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

Наконец, обновления для системы безопасности можно загрузить из [каталога Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=96155). Он обеспечивает возможность поиска содержимого (в том числе обновлений для системы безопасности, драйверов и пакетов обновления), которое предоставляется через Центр обновления Windows и Центр обновления Майкрософт. При поиске по номеру бюллетеня по безопасности (например, MS07-036) можно добавлять необходимые обновления (в том числе на различных языках) в корзину и загружать их в указанную папку. Дополнительные сведения см. на веб-сайте каталога Центра обновления Майкрософт в разделе [вопросов и ответов](http://go.microsoft.com/fwlink/?linkid=97900).

**Руководство по диагностике и развертыванию**

Корпорация Майкрософт предоставляет руководство по диагностике и развертыванию обновлений для системы безопасности. В этом руководстве содержатся рекомендации и сведения, позволяющие ИТ-специалистам оптимальнее использовать различные средства для диагностики и развертывания обновлений для системы безопасности. Дополнительные сведения см. в [статье 961747 базы знаний Майкрософт](http://support.microsoft.com/kb/961747).

**Анализатор безопасности Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений безопасности и стандартных ошибок в конфигурации системы безопасности. Дополнительные сведения об анализаторе безопасности MBSA см. на веб-сайте [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Службы Windows Server Update Services**

Службы Windows Server Update Services (WSUS) позволяют администраторам быстрым и надежным образом развертывать последние критические обновления и обновления для систем безопасности операционных систем Microsoft Windows 2000 и более поздних версий, пакетов Office XP и более поздних версий, серверов Exchange Server 2003 и SQL Server 2000 в системах Microsoft Windows 2000 и более поздних версий.

Дополнительные сведения о развертывании данного обновления безопасности с помощью служб WSUS см. на веб-сайте [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**System Center Configuration Manager 2007**

Управление обновлениями программного обеспечения с помощью диспетчера конфигураций Configuration Manager 2007 упрощает сложную задачу получения и управления обновлениями ИТ-систем по всему предприятию. С диспетчером конфигураций Configuration Manager 2007 ИТ-администраторы могут получать обновления продуктов Майкрософт на различные устройства, включая настольные и портативные компьютеры и мобильные устройства.

Автоматическая оценка уязвимостей в диспетчере конфигураций Configuration Manager 2007 определяет необходимость в обновлениях и сообщает о рекомендуемых действиях. Управление обновлениями программного обеспечения в диспетчере конфигураций Configuration Manager 2007 встроено в Microsoft Windows Software Update Services (WSUS), проверенную временем инфраструктуру обновления, хорошо знакомую ИТ-администраторам по всему миру. Подробнее о том, как администраторы могут использовать Configuration Manager 2007 для развертывания обновлений, см. [Управление обновлениями программного обеспечения](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). Подробнее о диспетчере конфигураций см. [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет хорошо сконфигурированное решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей.

**Примечание.** Основная поддержка System Management Server 2003 закончена 12 января 2010. Подробнее о жизненном цикле продуктов см. на веб-странице[Жизненный цикл поддержки Майкрософт](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Последний выпуск сервера SMS (System Center Configuration Manager 2007) доступен для загрузки; сведения о нем см. в разделе **System Center Configuration Manager 2007**.

Подробнее о том, как администраторы могут использовать SMS 2003 для развертывания обновлений системы безопасности, см. [Сценарии и процедуры для Microsoft Systems Management Server 2003: Распространение программного обеспечения и управление исправлениями](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Дополнительные сведения о сервере SMS см. на веб-сайте [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Примечание**. Для предоставления широкой поддержки при определении необходимости применения и развертывания обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используется средство Microsoft Baseline Security Analyzer. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. в статье [Развертывание обновлений программного обеспечения с помощью функции распространения программ сервера SMS](http://go.microsoft.com/fwlink/?linkid=33341). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакета [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)).

**Средство оценки совместимости обновлений и набор средств для обеспечения совместимости приложений**

Часто обновления записываются в одни те же файлы, а для запуска приложений требуется настроить параметры реестра. Это приводит к возникновению несовместимостей и увеличивает время, затрачиваемое на развертывание обновлений для системы безопасности. Облегчить тестирование и проверку обновлений Windows для установленных приложений можно с помощью [компонентов оценки совместимости обновлений](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true), входящих в состав [набора средств для обеспечения совместимости приложений](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Набор средств для обеспечения совместимости приложений содержит необходимые средства и документацию для выявления проблем совместимости приложений и уменьшения степени воздействия этих проблем перед развертыванием системы Microsoft Windows Vista, обновлений из Центра обновления Windows, обновлений с веб-сайта безопасности Майкрософт или новой версии проводника.

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

#### Обновления, не относящиеся к безопасности и распространяемые через Центр обновления Майкрософт, Центр обновления Windows и службу WSUS

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

-   Мэтью Ватчински (Matthew Watchinski) из компании [Sourcefire VRT](http://www.sourcefire.com/services/sf_vrt.html) за сообщение об уязвимости, описанной в MS11-015
-   HD Moore из [Rapid 7](http://www.rapid7.com/) за сообщение о проблеме, описанной в MS11-016
-   Эйала Грунера (Eyal Gruner) из компании [Versafe Anti Fraud](http://www.versafe-login.com/) за сообщение об уязвимости, описанной в MS11-017

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Пользователи из США и Канады могут обратиться в службу [поддержки по вопросам безопасности](http://go.microsoft.com/fwlink/?linkid=21131) или позвонить по телефону 1-866-PCSAFETY. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Дополнительные сведения о вариантах поддержки см. на веб-сайте [справки и поддержки корпорации Майкрософт](http://support.microsoft.com/).
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-сайт международной справки и поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (8 марта 2011): Обзор бюллетеней опубликован.
-   Вер. 1.1 (16 марта 2011): В примечаниях к MS11-015 в разделе **Продукты, подверженные уязвимости, и соответствующие обновления** удалено ошибочное упоминание Windows XP Home Edition с пакетом обновления 3 (SP3) и Windows XP Tablet PC Edition с пакетом обновления 3 (SP3) как не подверженных уязвимости. Это изменение носит исключительно информационный характер. Оно не вносит изменения в файлы обновления для системы безопасности или процедуру обнаружения. Пользователям, у которых установлены эти выпуски ОС и еще не установлено данное обновление, Майкрософт рекомендует установить это обновление немедленно. Пользователям, уже установившим это обновление, никаких действий выполнять не требуется.

*Built at 2014-04-18T01:50:00Z-07:00*
