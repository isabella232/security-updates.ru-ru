---
TOCTitle: 'MS06-FEB'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Февраль 2006 г.'
ms:assetid: 'ms06-feb'
ms:contentKeyID: 61236093
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms06-feb(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Февраль 2006 г.
==================================================================

Дата публикации: 14 февраля 2006 г.

**Версия:** 1.0

Версию данных материалов, предназначенную для конечных пользователей, можно получить на следующем [веб-узле](http://www.microsoft.com/security/default.mspx).

**Защитите свой компьютер:** сведения о защите пользовательских систем можно получить из следующих источников:

-   Конечные пользователи могут обратиться на веб-узел [Защитите свой компьютер](http://go.microsoft.com/fwlink/?linkid=21169).
-   ИТ-профессионалы могут обратиться на веб-узел [Security Guidance Center](http://go.microsoft.com/fwlink/?linkid=21171).

**Стратегии использования обновлений:** на веб-узле [Patch Management, Security Updates, and Downloads](http://go.microsoft.com/fwlink/?linkid=21168) содержится дополнительная информация о рекомендациях корпорации Майкрософт, касающихся эффективного применения исправлений системы безопасности.

**Сообщество IT Pro Security Zone Community:** на [веб-узле IT Pro Security Zone](http://go.microsoft.com/fwlink/?linkid=21164) можно получить сведения о способах усовершенствования системы безопасности и оптимизации информационной инфраструктуры предприятия, а также обсудить вопросы, связанные с обеспечением безопасности, с другими специалистами в области информационных технологий.

**Служба Microsoft Security Notification:** чтобы получать по электронной почте уведомления о выпуске бюллетеней по безопасности, обратитесь в службу [Microsoft Security Notification Service](http://go.microsoft.com/fwlink/?linkid=21163).

#### Аннотация

В данные материалы включено обновление, исправляющее недавно обнаруженные уязвимости. Ниже эти уязвимости упорядочены в соответствии с уровнем их опасности.

Критический (2)
---------------

<span></span>
| Идентификационный номер бюллетеня | Бюллетень корпорации Майкрософт по безопасности MS06-004                                                                              |
|-----------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Накопительное обновление безопасности для обозревателя Internet Explorer (910620)**](http://go.microsoft.com/fwlink/?linkid=57064) |
| **Аннотация**                     | В модуле обработки графики существует уязвимость, делающая возможным удаленное выполнение кода.                                       |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                           |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                             |
| **Подвержены уязвимости**         | **Windows.** Дополнительные сведения см. в разделе «Продукты, подверженные уязвимости, и соответствующие обновления».                 |

| Идентификационный номер бюллетеня | Бюллетень корпорации Майкрософт по безопасности MS06-005:                                                                                        |
|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | **Уязвимость проигрывателя Windows Media делает возможным удаленный запуск кода злоумышленника (911565)**                                        |
| **Аннотация**                     | В методе обработки проигрывателем Windows Media определенных типов файлов имеется уязвимость, которая может допустить удаленное выполнение кода. |
| **Уровень опасности**             | [Критический](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                      |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                        |
| **Подвержены уязвимости**         | **Windows.** Дополнительные сведения см. в разделе «Продукты, подверженные уязвимости, и соответствующие обновления».                            |

Существенный (5)
----------------

<span></span>
| Идентификационный номер бюллетеня | Бюллетень корпорации Майкрософт по безопасности MS06-006:                                                                                                                          |
|-----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | **Уязвимость в модуле проигрывателя Windows Media для обозревателей, выпущенных не корпорацией Майкрософт, делает возможным удаленное выполнение кода (911564)**                   |
| **Аннотация**                     | Во подключаемом модуле проигрывателя Windows Media для обозревателей, выпущенных не корпорацией Microsoft, имеется уязвимость, которая делает возможным удаленное выполнение кода. |
| **Уровень опасности**             | [Существенный](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                       |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                          |
| **Подвержены уязвимости:**        | **ОС Windows**. Дополнительные сведения см. в разделе «Продукты, подверженные уязвимости, и соответствующие обновления».                                                           |

| Идентификационный номер бюллетеня | Бюллетень корпорации Майкрософт по безопасности MS06-007                                                                                                          |
|-----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость протокола TCP/IP может привести к отказу в обслуживании (913446)**](http://go.microsoft.com/fwlink/?linkid=59797)                                   |
| **Аннотация**                     | Уязвимость может позволить злоумышленнику отправить специально сконструированный пакет протокола IGMP и заставить уязвимую систему перестать отвечать на запросы. |
| **Уровень опасности**             | [Существенный](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                      |
| **Воздействие уязвимости**        | Отказ в обслуживании                                                                                                                                              |
| **Подвержены уязвимости:**        | **ОС Windows**. Дополнительные сведения см. в разделе «Продукты, подверженные уязвимости, и соответствующие обновления».                                          |

| Идентификационный номер бюллетеня | Бюллетень корпорации Майкрософт по безопасности MS06-008                                                                                                                                                                                                                           |
|-----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость в службе «Веб-клиент» делает возможным удаленное выполнение кода (911927)**](http://go.microsoft.com/fwlink/?linkid=59441)                                                                                                                                           |
| **Аннотация**                     | В службе «Веб-клиент» Windows есть уязвимость, которая может позволить злоумышленнику установить полный контроль над системой. Чтобы воспользоваться данной уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему. |
| **Уровень опасности**             | [Существенный](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                       |
| **Воздействие уязвимости**        | удаленное выполнение кода                                                                                                                                                                                                                                                          |
| **Подвержены уязвимости:**        | **ОС Windows**. Дополнительные сведения см. в разделе «Продукты, подверженные уязвимости, и соответствующие обновления».                                                                                                                                                           |

| Идентификационный номер бюллетеня | Бюллетень корпорации Майкрософт по безопасности MS06-009                                                                                                                                                                                                                                                                           |
|-----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | [**Уязвимость в редакторе метода ввода на корейском языке может привести к повышению уровня прав доступа (901190)**](http://go.microsoft.com/fwlink/?linkid=49512)                                                                                                                                                                 |
| **Аннотация**                     | В редакторе метода ввода для ОС Windows и пакета Office (корейский язык) имеется уязвимость, дающая злоумышленнику возможность получить полный контроль над уязвимой системой. Чтобы воспользоваться данной уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему. |
| **Уровень опасности**             | [Существенный](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                       |
| **Воздействие уязвимости**        | Повышение уровня прав доступа                                                                                                                                                                                                                                                                                                      |
| **Подвержены уязвимости:**        | **ОС Windows и пакет Office**. Дополнительные сведения см. в разделе «Продукты, подверженные уязвимости, и соответствующие обновления».                                                                                                                                                                                            |

| Идентификационный номер бюллетеня | Бюллетень корпорации Майкрософт по безопасности MS06-010                                                                   |
|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------|
| **Название бюллетеня**            | **Уязвимость в программе PowerPoint 2000 может быть причиной раскрытия информации (889167)**                               |
| **Аннотация**                     | В программе PowerPoint имеется уязвимость, которая может привести к раскрытию информации.                                  |
| **Уровень опасности**             | [Существенный](http://go.microsoft.com/fwlink/?linkid=21140)                                                               |
| **Воздействие уязвимости**        | раскрытие информации                                                                                                       |
| **Подвержены уязвимости:**        | **пакет Office.** Дополнительные сведения см. в разделе «Продукты, подверженные уязвимости, и соответствующие обновления». |

Продукты, подверженные уязвимости, и соответствующие обновления
---------------------------------------------------------------

<span></span>
**Как пользоваться этой таблицей?**

Используйте эту таблицу для получения сведений об обновлениях системы безопасности, которые нужно будет установить. Просмотрите каждый указанный в ней программный продукт или компонент, чтобы выяснить, имеются ли для него обновления системы безопасности. Если в таблице указан какой-либо программный продукт или компонент, то здесь же приводятся сведения о воздействии на него соответствующей уязвимости, а также гиперссылки на доступное обновление программного обеспечения.

Приводимый в таблице номер в квадратных скобках \[x\] указывает на наличие примечания, в котором приводятся дополнительные сведения по рассматриваемому вопросу. Эти примечания располагаются внизу таблицы.

**Примечание.** Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификационного номера бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.

#### Подверженное уязвимости программное обеспечение и адреса для загрузки обновлений MS06-004 — MS06-007

 
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ></th>
<th style="border:1px solid black;" >Сведения        </th>
<th style="border:1px solid black;" >Сведения        </th>
<th style="border:1px solid black;" >Сведения   </th>
<th style="border:1px solid black;" >Сведения   </th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Идентификационный номер бюллетеня</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=57064"><strong>MS06-004</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=59277"><strong>MS06-005</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=59278"><strong>MS06-006</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=59797"><strong>MS06-007</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Уровень опасности</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Критический</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Критический</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Существенный</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Существенный</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Системы Windows, подверженные уязвимости:</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ccdd3d35-be5c-4c43-8ffa-bb8570a7321c">Существенный</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=78d7df14-6049-4318-89ca-9c8681ced8ab">Существенный</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Windows Server 2003 с пакетом обновления 1 (SP1)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ccdd3d35-be5c-4c43-8ffa-bb8570a7321c">Существенный</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=78d7df14-6049-4318-89ca-9c8681ced8ab">Существенный</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e3daab50-2ac7-49dd-8971-4f98fed9fba6">Существенный</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=12aae69e-c5c3-4e4a-9970-f5db84dd9744">Существенный</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 для платформы Itanium</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9ae276cf-ab46-4198-bcb3-3effdf15550e">Существенный</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9ae276cf-ab46-4198-bcb3-3effdf15550e">Существенный</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP с пакетом обновления 1 (SP1)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ccdd3d35-be5c-4c43-8ffa-bb8570a7321c">Существенный</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7bb21d74-c37b-472b-bb10-71d4680680a7">Существенный</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP с пакетом обновления 2 (SP2)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ccdd3d35-be5c-4c43-8ffa-bb8570a7321c">Существенный</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7bb21d74-c37b-472b-bb10-71d4680680a7">Существенный</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Professional x64 Edition</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=165916c2-037e-4edd-b64a-84838bee151c">Существенный</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e2538cc-cc90-4db7-8d0b-0b8ba4234e67">Существенный</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 с пакетом обновления 4 (SP4)</td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ccdd3d35-be5c-4c43-8ffa-bb8570a7321c">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Millennium Edition (Me)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 98 SE</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 98</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Компоненты операционных систем Windows, подверженные уязвимости:</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Internet Explorer 5.01 с пакетом обновления 4 (SP4) в составе Microsoft Windows 2000 с пакетом обновления 4 (SP4)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c0df2fc3-2075-46b5-945f-6e0bd6806151">критический</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Media Player 7.1 в ОС Windows 98, 98 SE, ME и Windows 2000 с пакетом обновления 4 (SP4)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=26a0b9e1-1242-4e55-b3d4-8377b83257c6">Существенный</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Windows Media Player для ОС Microsoft Windows XP с пакетом обновления 1 (SP1)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=110054f2-244d-4036-b98c-e951cba7e9ba">Существенный</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Windows Media Player 9 в ОС Windows 98, 98 SE, ME, Windows 2000 с пакетом обновления 4 (SP4) или Windows XP с пакетом обновления 1 (SP1)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8f9eef16-04f7-4da8-a0ef-1797b52d0b4b">Критический</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Windows Media Player 9 в ОС Windows XP с пакетом обновления 2 (SP2) или Windows Server 2003</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8f9eef16-04f7-4da8-a0ef-1797b52d0b4b">Критический</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Windows Media Player 10 в ОС Windows XP с пакетами обновления 1 (SP1) или 2 (SP2)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=182735e1-9382-4f2e-a624-d2316a96b411">Критический</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
</tbody>
</table>
  
#### Подверженное уязвимости программное обеспечение и адреса для загрузки обновлений MS06-008 — MS06-010

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ></th>
<th style="border:1px solid black;" >Сведения   </th>
<th style="border:1px solid black;" >Сведения   </th>
<th style="border:1px solid black;" >Сведения        </th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Идентификационный номер бюллетеня</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=59441"><strong>MS06-008</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=49512"><strong>MS06-009</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=61558"><strong>MS06-010</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Уровень опасности</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Существенный</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Существенный</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Существенный</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Системы Windows, подверженные уязвимости:</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fa073183-0c83-4f1c-be46-a2ee8a1a1440">Средний</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a092ba0f-c753-444b-a572-492e4ecb2d3f">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Windows Server 2003 с пакетом обновления 1 (SP1)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fa073183-0c83-4f1c-be46-a2ee8a1a1440">Средний</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a092ba0f-c753-444b-a572-492e4ecb2d3f">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e2f5413a-0b77-4c18-9bab-e2470d3d3f4e">Средний</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=66e495e8-cd52-4e76-b20a-4471fa941556">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 для платформы Itanium</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e186e149-208a-4035-a0fc-e1cbde4e6fef">Средний</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8479c2eb-0fb6-4879-9c3d-b49bd864a71c">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 с пакетом обновления 1 (SP1) для платформы Itanium</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e186e149-208a-4035-a0fc-e1cbde4e6fef">Средний</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8479c2eb-0fb6-4879-9c3d-b49bd864a71c">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP с пакетом обновления 1 (SP1)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=62535040-5204-4469-b0bf-eae14567c2d5">Существенный</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=290453df-1cae-4691-b20c-5d65d92216bf">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP с пакетом обновления 2 (SP2)</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=62535040-5204-4469-b0bf-eae14567c2d5">Существенный</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=290453df-1cae-4691-b20c-5d65d92216bf">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Professional x64 Edition</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9734f634-6869-434f-aaf0-47b70f84d178">Существенный</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7d75bf5c-2e1d-4793-b7d1-dd372a99eca5">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 с пакетом обновления 4 (SP4)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Millennium Edition (Me)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 98 SE</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 98</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong> Продукты Office, подверженные уязвимости:</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Office 2003 с пакетом обновления 1 (SP1)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e6f16e9-cd73-47d5-887e-616db9b09591">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Office XP с пакетом обновления 2 (SP2)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e6f16e9-cd73-47d5-887e-616db9b09591">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Пакеты многоязыкового пользовательского интерфейса для Office 2003</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=986f9a8d-afe7-455a-b78d-0795cbb0e80e">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Пакеты многоязыкового пользовательского интерфейса для Office Project 2003</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=22c96d7f-f384-4678-9ac0-3a11b81a4c1d">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Пакеты многоязыкового пользовательского интерфейса для Office Visio 2003</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5a4d0a92-2dfc-4f8b-9d14-138cea57af96">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Средства проверки Office 2003</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=32cf9f59-ffbd-45e5-a4d2-690183462d0f">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Office Visio 2003</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e6f16e9-cd73-47d5-887e-616db9b09591">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Office OneNote 2003</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e6f16e9-cd73-47d5-887e-616db9b09591">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Office Project 2003</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ru-RU/library///www.microsoft.com/downloads/details.aspx?familyid=8e6f16e9-cd73-47d5-887e-616db9b09591(v=Security.10)">Существенный</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PowerPoint 2000</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ru-RU/library///www.microsoft.com/downloads/details.aspx?familyid=e51b27c8-2f31-4e99-b868-ce626fed5b7d(v=Security.10)">Существенный</a></td>
</tr>
</tbody>
</table>
  
**Примечание.**
  
**<sup>[1]</sup>** Для этой операционной системы имеется обновление безопасности. Для получения дополнительных сведений см. сведения об уязвимых компонентах (обозревателе Microsoft Internet Explorer и проигрывателе Windows Media) в таблице, а также соответствующий бюллетень безопасности.
  
Развертывание  
-------------
  
<span></span>
**Службы Software Update Services**
  
Службы Microsoft Software Update Services (SUS) позволяют администратору быстро и надежно устанавливать последние критические обновления и обновления безопасности на серверах, работающих под управлением Windows 2000 и Windows Server 2003, а также на настольных компьютерах, работающих под управлением Windows 2000 Professional и Windows XP Professional.
  
Сведения о развертывании данного обновления с помощью служб Software Update Services см. на веб-узле [Software Update Services](http://go.microsoft.com/fwlink/?linkid=21133).
  
**Службы Windows Server Update Services**
  
Службы Windows Server Update Services (WSUS) позволяют администраторам быстро и надежно развертывать последние критические обновления и обновления безопасности для операционных систем Windows 2000 и более поздних версий Windows, для Office XP и более поздних версий Office, для Exchange Server 2003 и для SQL Server 2000 на системах Windows 2000 и более поздних версиях операционных систем.
  
Для получения дополнительной информации о развертывании данного обновления безопасности с помощью служб Windows Server Update Services посетите[веб-узел служб Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).
  
**Systems Management Server:**
  
Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет полностью настраиваемое решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей. Дополнительные сведения о том, как администраторы могут использовать сервер SMS 2003 для развертывания обновлений, см. на [веб-узле SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Пользователи сервера SMS 2.0 могут также применять пакет [Software Updates Service Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340), с помощью которого упрощается развертывание обновлений системы безопасности. Дополнительные сведения о сервере SMS см. на веб-узле [SMS](http://go.microsoft.com/fwlink/?linkid=21158).
  
**Примечание.** Для предоставления широкой поддержки при определении необходимости применения и развертывания обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используются средства Microsoft Baseline Security Analyzer и Microsoft Office Detection Tool. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. на следующем [веб-узле](http://go.microsoft.com/fwlink/?linkid=33341). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакетов [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) и [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).
  
**Средства QChain.exe и Update.exe**
  
Корпорация Майкрософт выпустила программу QChain.exe с интерфейсом командной строки, которая позволяет системному администратору объединять обновления безопасности при их установке. Подобное *объединение* позволяет устанавливать несколько обновлений без промежуточной перезагрузки компьютера. Программа Update.exe для описанных в данной статье обновлений обладает встроенными функциями объединения. Для объединения установок обновлений на компьютерах под управлением Windows 2000 Service Pack 2 или более поздних версий, Windows XP и Windows Server 2003 программа Qchain.exe не используется. Qchain.exe по-прежнему поддерживает эти обновления Windows, благодаря чему администраторы могут создавать совместимые сценарии развертывания программного обеспечения на всех платформах. Дополнительные сведения о программе Qchain можно получить на следующем [веб-узле](http://go.microsoft.com/fwlink/?linkid=21156).
  
**Программа Microsoft Baseline Security Analyzer (MBSA):**
  
Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений безопасности и стандартных ошибок в конфигурации системы безопасности. Для получения дополнительных сведений о программе MBSA обратитесь к [веб-узлу Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).
  
**Руководство по диагностике и развертыванию:**
  
Корпорация Майкрософт предоставила руководство по диагностике и развертыванию для обновлений безопасности этого месяца. Это руководство также поможет ИТ-профессионалам разобраться, каким образом они могут использовать для развертывания обновления безопасности такие средства, как веб-узлы Windows Update, Microsoft Update, Office Update, средства Microsoft Baseline Security Analyzer (MBSA), Office Detection Tool, сервер Microsoft Systems Management Server (SMS), средство Extended Security Update Inventory Tool, а также средство Enterprise Update Scan Tool (EST). Дополнительные сведения см. в [статье 910723 базы знаний Майкрософт](http://support.microsoft.com/kb/910723).
  
#### Прочие сведения
  
**Благодарности**
  
Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:
  
-   Марка Мэйфрета (Marc Maiffret) из компании eEye за сообщение о проблеме, описанной в бюллетене по безопасности [MS06-005](http://technet.microsoft.com/security/bulletin/ms06-005).  
-   Джона Кобба (John Cobb) из компании iDefense за сообщение о проблеме, описанной в бюллетене по безопасности [MS06-006](http://technet.microsoft.com/security/bulletin/ms06-006).  
-   Дугласа Начименто (Douglas Nascimento) из компании Datacom за сообщение о проблеме, описанной в бюллетене по безопасности [MS06-007](http://technet.microsoft.com/security/bulletin/ms06-007).  
-   Костю Корчинского (Kostya Kortchinsky) из компании [EADS/CRC](http://www.eads.net/) за сообщение о проблеме, описанной в бюллетене по безопасности [MS06-008](http://technet.microsoft.com/security/bulletin/ms06-008).  
-   [Райана Ли (Ryan Lee)](mailto:newrun@gmail.com) за сообщение о проблеме, описанной в бюллетене по безопасности [MS06-009](http://technet.microsoft.com/security/bulletin/ms06-009).  
-   Андреаса Сэндблада (Andreas Sandblad) за сообщение о проблеме, описанной в бюллетене по безопасности [MS06-010](http://technet.microsoft.com/security/bulletin/ms06-010).  
-   Йорика Костера (Yorick Koster) из компании ITsec Security Services за сообщение о проблеме, описанной в бюллетене по безопасности [MS06-010](http://technet.microsoft.com/security/bulletin/ms06-010).  
-   **Другие обновления безопасности:**
  
    Другие обновления безопасности можно загрузить из следующих источников:
  
    -   Обновления безопасности доступны на веб-узле [Центра загрузки корпорации Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Чтобы найти обновление, выполните поиск по ключевому слову security\_patch.  
    -   Для получения обновлений для пользовательских систем обращайтесь на [веб-узел Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).  
    -   Обновления, предлагаемые на веб-узле Windows Update в этом месяце, можно получить в образе компакт-диска с выпусками обновлений безопасности за январь 2006 г. Более подробную информацию см. в [статье 913086 базы знаний Майкрософт](http://support.microsoft.com/kb/913086).
  
    **Поддержка**
  
    -   Обращайтесь в [службу поддержки продуктов Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) по телефону 1-866-PCSAFETY (для жителей США и Канады). Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно.  
    -   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-узел международной поддержки](http://go.microsoft.com/fwlink/?linkid=21155).
  
    **Источники сведений по безопасности**
  
    -   Дополнительные сведения о безопасности продуктов корпорации Майкрософт см. на веб-узле [Microsoft TechNet Security](http://go.microsoft.com/fwlink/?linkid=21132).  
    -   [Службы Microsoft Software Update](http://go.microsoft.com/fwlink/?linkid=21133)  
    -   [Службы Microsoft Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)  
    -   [Программа Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) (MBSA)  
    -   [Веб-узел Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)  
    -   [Microsoft Update](http://update.microsoft.com/microsoftupdate)  
    -   Каталог Windows Update: Дополнительные сведения о каталоге Windows Update см. в статье [323166](http://support.microsoft.com/default.aspx?scid=kb;en-us;323166) базы знаний Майкрософт.  
    -   [Веб-узел Office Update](http://go.microsoft.com/fwlink/?linkid=21135)
  
    **Отказ от гарантий**
  
    Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.
  
    **Редакции:**
  
    -   Версия 1.0 (14 февраля 2006 г.): бюллетень опубликован.
  
-   
  
*Built at 2014-04-18T01:50:00Z-07:00*
