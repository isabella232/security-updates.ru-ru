---
TOCTitle: Изменение параметров кэша Active Directory
Title: Изменение параметров кэша Active Directory
ms:assetid: '8789a7a5-2065-4fae-9104-e0a70f1f2fb6'
ms:contentKeyID: 18124443
ms:mtpsurl: 'https://technet.microsoft.com/ru-ru/library/Cc747586(v=WS.10)'
---

Изменение параметров кэша Active Directory
==========================================

Параметры в реестре задают число записей, которые будут храниться в кэше Active Directory. Чтобы уменьшить время обработки запросов клиента, можно изменить эти параметры. Дополнительные сведения можно найти в разделе “Оптимизация эффективности служб каталогов” данного документа. Кроме того, можно указать период допустимости для данных, хранящихся в кэше.

На компьютерах под управлением 32-разрядной версии Windows Server 2003 полный путь к подразделу реестра для параметров кэша таков:

**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\DRMS\\1.0\\DirectoryServices**

На компьютерах под управлением 64-разрядной версии Windows Server 2003 полный путь к подразделу реестра для параметров кэша таков:

**HKEY\_LOCAL\_MACHINE\\SoftwareWOW6432Node\\Microsoft\\DRMS\\1.0\\DirectoryServices**

В следующей таблице приведены записи, которые контролируют режим кэша, находящегося в памяти.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Имя</th>
<th style="border:1px solid black;" >Тип</th>
<th style="border:1px solid black;" >Значение по умолчанию</th>
<th style="border:1px solid black;" >Описание</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">PrincipalCacheMax</td>
<td style="border:1px solid black;">Двойное слово</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">Максимальное число участников, их адреса электронной почты и идентификаторы безопасности, которые можно сохранить в кэше.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">PrincipalCacheExpireMinutes</td>
<td style="border:1px solid black;">Двойное слово</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">Период допустимости для данных, хранящихся в кэше для участников.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">GroupIDCacheMax</td>
<td style="border:1px solid black;">Двойное слово</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">Максимальное число групп и их адреса электронной почты, а также идентификаторы безопасности, которые можно сохранить в кэше.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GroupIDCacheExpireMinutes</td>
<td style="border:1px solid black;">Двойное слово</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">Период допустимости для данных, хранящихся в кэше для принадлежности к группе.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">GroupMembershipCacheMax</td>
<td style="border:1px solid black;">Двойное слово</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">Максимальное число контактов, входящих в группу, которое можно сохранить в кэше.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GroupMembershipCacheExpireMinutes</td>
<td style="border:1px solid black;">Двойное слово</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">Период допустимости кэшированных данных для контактов, которые входят в группу.</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc747586.Caution(WS.10).gif)Внимание!                                                                                                 |  
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| Неправильное изменение реестра может привести к серьезному повреждению системы. Перед изменением реестра необходимо создать резервную копию всех ценных данных на компьютере. |
  
| ![](images/Cc747586.note(WS.10).gif)Примечание                                                                                                                                                                                                                                        |  
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| Записи реестра **PrincipalCacheExpireMinutes**, **GroupIDCacheExpireMinutes**, **GroupMembershipCacheExpireMinutes**, и **ContactMembersofGroupCacheExpireMinutes** также контролируют истечение срока кэша в в локальном кэше Active Directory, хранящемся на сервере базы данных в база данных службы каталогов. |
