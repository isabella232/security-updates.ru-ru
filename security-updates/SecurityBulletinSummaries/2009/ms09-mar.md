---
TOCTitle: 'MS09-MAR'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Март 2009 г.'
ms:assetid: 'ms09-mar'
ms:contentKeyID: 61236126
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms09-mar(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Март 2009 г.
===============================================================

Дата публикации: 10 марта 2009 г. | Дата обновления: 11 марта 2009 г.

**Версия:** 1.1

В этом обзоре указаны бюллетени по безопасности, выпущенные в марте 2009 г.

После выпуска мартовских бюллетеней данный обзор заменит предварительное уведомление, выпущенное 5 марта 2009 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [Предварительное уведомление о бюллетенях по безопасности Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней по безопасности Microsoft, см. на веб-узле [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

11 марта 2009 г. в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в мартовской веб-трансляции, посвященной бюллетеням по безопасности](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395124). После наступления этой даты данная веб-трансляциия будет доступна по запросу. Дополнительные сведения см. на веб-узле [Обзоры бюллетеней по безопасности Microsoft и веб-трансляции](http://technet.microsoft.com/security/bulletin/summary) (на английском языке).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132503">MS09-006</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в ядре Windows делают возможным удаленное выполнение кода (958690)</strong><br />
<br />
Это обновление для системы безопасности устраняет несколько уязвимостей ядра Windows, о которых сообщалось в частном порядке. Уязвимость, представляющая наиболее серьезную угрозу, делает возможным удаленное выполнение кода, если пользователь просматривает в уязвимой системе специально созданный файл изображения в формате EMF или WMF.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139854">MS09-007</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в безопасном канале SChannel делает возможной подделку (960225)</strong><br />
<br />
Данное обновление для системы безопасности устраняет уязвимость пакета безопасности безопасного канала (Schannel) в системе Windows, о которой сообщалось в частном порядке. Уязвимость делает возможной подделку, если злоумышленник получает доступ к сертификату, используемому конечным пользователем для проверки подлинности. Пользователи подвергаются риску использования этой уязвимости только в том случае, если злоумышленник получает компонент открытого ключа такого сертификата другими способами.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Подделка</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139821">MS09-008</a></td>
<td style="border:1px solid black;"><strong>Уязвимости DNS- и WINS-серверов делают возможным спуфинг (962238)</strong><br />
<br />
Данное обновление для системы безопасности устраняет две уязвимости, о которых сообщалось в частном порядке, и две уязвимости, о которых сообщалось в открытых источниках, касающиеся серверов Windows DNS и Windows WINS. Эти уязвимости позволяют удаленному злоумышленнику перенаправлять сетевой трафик, предназначенный для пользовательских веб-систем, во вредоносные системы.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Подделка</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Указатель использования уязвимости  
----------------------------------
  
<span></span>
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости сгруппированы по идентификаторам бюллетеней и кодам CVE.
  
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать о вероятности выпуска работающего кода использования уязвимости в течение 30 дней после выпуска бюллетеня по безопасности для каждого обновления для системы безопасности, которое потребуется установить. Перед назначением приоритетов развертывания ознакомьтесь с каждой приведенной ниже оценкой, относящейся к конкретной конфигурации. Дополнительные сведения об уровнях опасности и способах их определения см. в [указателе использования уязвимостей корпорации Майкрософт](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| Идентификатор бюллетеня                                   | Название бюллетеня                                                            | Код CVE                                                                          | Оценка указателя использования уязвимости                                                                              | Ключевые примечания                                                                                                                                                                    |  
|-----------------------------------------------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-006](http://go.microsoft.com/fwlink/?linkid=132503) | Уязвимости в ядре Windows делают возможным удаленное выполнение кода (958690) | [CVE-2009-0081](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0081) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможность работы кода использования отсутствует | Стойкий отказ в обслуживании более вероятен, чем выполнение рабочего кода                                                                                                              |  
| [MS09-006](http://go.microsoft.com/fwlink/?linkid=132503) | Уязвимости в ядре Windows делают возможным удаленное выполнение кода (958690) | [CVE-2009-0082](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0082) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна несогласованность кода использования     | Стойкий отказ в обслуживании более вероятен, чем выполнение рабочего кода                                                                                                              |  
| [MS09-006](http://go.microsoft.com/fwlink/?linkid=132503) | Уязвимости в ядре Windows делают возможным удаленное выполнение кода (958690) | [CVE-2009-0083](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0083) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможность работы кода использования отсутствует | Локальные угрозы существуют только для стойкого отказа в обслуживании или раскрытия информации, которые более вероятны, чем выполнение рабочего кода                                   |  
| [MS09-007](http://go.microsoft.com/fwlink/?linkid=139854) | Уязвимость в безопасном канале SChannel делает возможной подделку (960225)    | [CVE-2009-0085](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0085) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна несогласованность кода использования     | Требования для выполнения рабочего кода высоки, а важных пользовательских сценариев не так много                                                                                       |  
| [MS09-008](http://go.microsoft.com/fwlink/?linkid=139821) | Уязвимости DNS- и WINS-серверов делают возможной подделку (962238)            | [CVE-2009-0093](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0093) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна несогласованность кода использования     | Вероятность выполнения согласованного концептуального кода спуфинга существует, а выполнение рабочего кода использования, приводящего к запуску вредоносного кода, крайне маловероятно |  
| [MS09-008](http://go.microsoft.com/fwlink/?linkid=139821) | Уязвимости DNS- и WINS-серверов делают возможной подделку (962238)            | [CVE-2009-0094](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0094) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна несогласованность кода использования     | Вероятность выполнения согласованного концептуального кода спуфинга существует, а выполнение рабочего кода использования, приводящего к запуску вредоносного кода, крайне маловероятно |  
| [MS09-008](http://go.microsoft.com/fwlink/?linkid=139821) | Уязвимости DNS- и WINS-серверов делают возможной подделку (962238)            | [CVE-2009-0233](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0233) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна несогласованность кода использования     | Вероятность выполнения согласованного концептуального кода спуфинга существует, а выполнение рабочего кода использования, приводящего к запуску вредоносного кода, крайне маловероятно |  
| [MS09-008](http://go.microsoft.com/fwlink/?linkid=139821) | Уязвимости DNS- и WINS-серверов делают возможной подделку (962238)            | [CVE-2009-0234](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0234) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна несогласованность кода использования     | Вероятность выполнения согласованного концептуального кода спуфинга существует, а выполнение рабочего кода использования, приводящего к запуску вредоносного кода, крайне маловероятно |
  
Продукты, подверженные уязвимости и соответствующие обновления  
--------------------------------------------------------------
  
<span></span>
В приведенных ниже таблицах перечислены бюллетени в порядке важности категорий программного обеспечения и уровней опасности.
  
**Как пользоваться этими таблицами?**
  
Обращайтесь к этим таблицам, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и узнайте, имеются ли для них обновления для системы безопасности. Для программ или компонентов, указанных в списке, приведены ссылки на доступные обновления с указанием уровня опасности уязвимостей, которые они устраняют.
  
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
[**MS09-006**](http://go.microsoft.com/fwlink/?linkid=132503)
</td>
<td style="border:1px solid black;">
[**MS09-007**](http://go.microsoft.com/fwlink/?linkid=139854)
</td>
<td style="border:1px solid black;">
[**MS09-008**](http://go.microsoft.com/fwlink/?linkid=139821)
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
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=98bb7d40-89a0-470a-8eb7-06f15072a635)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=bf7065bc-c183-4a78-8d46-72fe7385c07c)  
(существенный)
</td>
<td style="border:1px solid black;">
[DNS-сервер в системе Microsoft Windows 2000 Server с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=110354f7-5ece-4c4d-b563-3adba6ac0116)  
(961063)  
(существенный)  
[DNS-сервер в системе Microsoft Windows 2000 Server с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=4319abb3-1ea2-466a-a815-c0b3b86b4462)  
(961064)  
(существенный)
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
[**MS09-006**](http://go.microsoft.com/fwlink/?linkid=132503)
</td>
<td style="border:1px solid black;">
[**MS09-007**](http://go.microsoft.com/fwlink/?linkid=139854)
</td>
<td style="border:1px solid black;">
[**MS09-008**](http://go.microsoft.com/fwlink/?linkid=139821)
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
<td style="border:1px solid black;">
Отсутствует
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP с пакетом обновления 2 (SP2) или 3 (SP3)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2) и Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=e09641ba-6cbe-4095-82b5-703d3a7dc33b)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2) и Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=942d87f6-3cb1-4d36-a70a-70d9c34488f3)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d0d704c6-48c2-4907-b6c3-2455d7cf21c8)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6d02306e-9e2e-4ae8-bd21-8a2c1a229472)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
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
[**MS09-006**](http://go.microsoft.com/fwlink/?linkid=132503)
</td>
<td style="border:1px solid black;">
[**MS09-007**](http://go.microsoft.com/fwlink/?linkid=139854)
</td>
<td style="border:1px solid black;">
[**MS09-008**](http://go.microsoft.com/fwlink/?linkid=139821)
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
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=f5cfb8da-e7cc-4183-8631-507c2a406500)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 1 (SP1) и Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0b3f6fdd-276e-4267-99d8-8f00d91ad6a2)  
(существенный)
</td>
<td style="border:1px solid black;">
[DNS-сервер в системах Windows Server 2003 с пакетами обновления 1 (SP1) и 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6cc42c9e-c34e-4577-8b23-9e07e2369878)  
(961063)  
(существенный)  
[DNS-сервер в системах Windows Server 2003 с пакетами обновления 1 (SP1) и 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=049e5db5-7315-4188-99fd-4a54833e6bf2)  
(961064)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ecf75c70-8489-41ad-9759-3a07e13957be)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=ce98ff55-f565-469d-bbd2-32b681faf908)  
(существенный)
</td>
<td style="border:1px solid black;">
[DNS-сервер в системах Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b1f81fd2-0099-4450-8543-0459561d22d0)  
(961063)  
(существенный)  
[DNS-сервер в системах Windows Server 2003 x64 Edition и Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4a393c63-eff5-4c8c-9c3f-33ce45c32428)  
(961064)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium и Windows Server 2003 с пакетом обновления 2 (SP2) для платформы Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium и Windows Server 2003 с пакетом обновления 2 (SP2) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=04be3d7e-7dda-4dca-887a-e7a8156ede1c)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium и Windows Server 2003 с пакетом обновления 2 (SP2) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=5ca3c72c-cadb-4b0a-b3a3-fb81d0bfd7b3)  
(существенный)
</td>
<td style="border:1px solid black;">
[DNS-сервер в системах Windows Server 2003 с пакетами обновления 1 (SP1) и 2 (SP2) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=d3ed7d9a-d652-4bd0-aecc-5a415bec6c59)  
(961063)  
(существенный)  
[WINS-сервер в системах Windows Server 2003 с пакетами обновления 1 (SP1) и 2 (SP2) для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=37e3a75e-0a5d-4df0-881f-cdb87efa4dcf)  
(961064)  
(существенный)
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
[**MS09-006**](http://go.microsoft.com/fwlink/?linkid=132503)
</td>
<td style="border:1px solid black;">
[**MS09-007**](http://go.microsoft.com/fwlink/?linkid=139854)
</td>
<td style="border:1px solid black;">
[**MS09-008**](http://go.microsoft.com/fwlink/?linkid=139821)
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
<td style="border:1px solid black;">
Отсутствует
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista и Windows Vista с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Vista и Windows Vista с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=4b1aaaba-f355-4265-83c0-50b901856ced)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista и Windows Vista с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=21086a04-402a-4940-8358-7fa63508102b)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition и Windows Vista x64 Edition с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition и Windows Vista x64 Edition с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=0fcac480-d6db-4a94-8c7d-b7319282cf56)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition и Windows Vista x64 Edition с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=c75a2ea9-b42f-457b-be09-5c8fa0339388)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
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
[**MS09-006**](http://go.microsoft.com/fwlink/?linkid=132503)
</td>
<td style="border:1px solid black;">
[**MS09-007**](http://go.microsoft.com/fwlink/?linkid=139854)
</td>
<td style="border:1px solid black;">
[**MS09-008**](http://go.microsoft.com/fwlink/?linkid=139821)
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
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем ](http://www.microsoft.com/downloads/details.aspx?familyid=38851df2-4fb5-4d28-9d15-181c260cf8cf)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем ](http://www.microsoft.com/downloads/details.aspx?familyid=47b361ce-624b-466c-b5c5-8703f6532615)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[DNS-сервер в системе Windows Server 2008 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=92e89882-d656-4b61-a05c-3afb44895f08) \*  
(961063)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем ](http://www.microsoft.com/downloads/details.aspx?familyid=ec15acc4-3e0f-4414-9383-61c122ff1382)\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем ](http://www.microsoft.com/downloads/details.aspx?familyid=5c81ac45-60e6-4121-ab6b-d3b3179aacc4)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[DNS-сервер в системах Windows Server 2008 для 64-разрядных (х64) систем](http://www.microsoft.com/downloads/details.aspx?familyid=be068d06-5939-4ad8-8191-e85931ed610f) \*  
(961063)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для платформы Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=eead6f93-10fd-4492-8137-481d9876a5fe)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для платформы Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=bf8f5a86-1757-4f9b-b632-d4aa7005a9f8)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 
**Примечания для сервера Windows Server 2008**

**\* Подверженные уязвимости системы Windows Server 2008, при развертывании которых устанавливались основные компоненты сервера.** Это обновление имеет одинаковый уровень опасности для поддерживаемых выпусков Windows Server 2008, независимо от того, выбиралась ли установка основных компонентов сервера при их развертывании или нет. Дополнительные сведения об этом варианте установки см. в статье [Основные компоненты сервера](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (на английском языке). Обратите внимание, что установка основных компонентов сервера недоступна в определенных выпусках Windows Server 2008; см. статью [Сравнение параметров установки основных компонентов сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx) (на английском языке).

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

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-узле Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт](http://support.microsoft.com/kb/894199). Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
-   [Новые, исправленные и выпущенные обновления для продуктов Майкрософт, отличных от Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

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

-   Гельмута Булера (Helmut Buhler), <http://home.arcor.de/clipboarder/>, за сообщение о проблеме, описанной в бюллетене MS09-006;
-   Томаса Гарнье (Thomas Garnier) из компании [SkyRecon](http://www.skyrecon.com/) за сообщение о проблеме, описанной в бюллетене MS09-006;
-   [Secretaria da Fazenda do Estado do Rio Grande do Sul](http://www.sefaz.rs.gov.br/) за сообщение о проблеме, описанной в бюллетене MS09-007;
-   [Cia de Processamento de Dados do Estado do Rio Grande do Sul](http://www.procergs.rs.gov.br/) за сообщение о проблеме, описанной в бюллетене MS09-007;
-   Кевина Дея (Kevin Day) за сотрудничество в отношении двух проблем, описанных в бюллетене MS09-008;
-   Дейва Дагона (Dave Dagon) из компании [Georgia Tech Information Security Center](http://www.gtisc.gatech.edu/) за совместную работу по устранению двух уязвимостей, описанных в бюллетене MS09-008.

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов можно найти на веб-узле [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).
-   Обращайтесь в [службу поддержки продуктов корпорации Майкрософт](http://go.microsoft.com/fwlink/?linkid=21131) по телефону 1-866-PCSAFETY (для жителей США и Канады). Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно.
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-узел международной поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (10 марта 2009 г.). Обзор бюллетеней опубликован.
-   Версия 1.1 (11 марта 2009 г.). Обновлены сведения о поиске бюллетеня MS09-008.

*Built at 2014-04-18T01:50:00Z-07:00*
