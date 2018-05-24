---
TOCTitle: 'MS10-APR'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Апрель 2010 г.'
ms:assetid: 'ms10-apr'
ms:contentKeyID: 61236131
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms10-apr(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Апрель 2010 г.
=================================================================

Дата публикации: 13 апреля 2010 г. | Дата обновления: 13 июля 2010 г.

**Версия:** 4.0

В этом обзоре перечислены бюллетени по безопасности, выпущенные в апреле 2010 г.

После выпуска бюллетеней за апрель 2010 г. данный обзор заменит предварительное уведомление, выпущенное 8 апреля 2010 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [Предварительное уведомление о бюллетенях по безопасности (Майкрософт)](http://technet.microsoft.com/security/bulletin/advance).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

14 апреля 2010 г. в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в апрельской веб-трансляции, посвященной бюллетеням по безопасности](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427721&eventcategory=4&culture=en-us&countrycode=us). После наступления этой даты данная веб-трансляция будет доступна по запросу. Дополнительные сведения см. на веб-сайте [обзоров и веб-трансляций, посвященных бюллетеням Майкрософт по безопасности](http://technet.microsoft.com/security/bulletin/summary).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184933">MS10-019</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Windows делают возможным удаленное выполнение кода (981210)</strong><br />
<br />
Это обновление для системы безопасности устраняет две обнаруженные пользователями уязвимости в механизме проверки Windows Authenticode, которые делают возможным удаленное выполнение кода. Злоумышленник, успешно воспользовавшийся любой из этих уязвимостей, может получить полный контроль над системой. После этого злоумышленник сможет устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными правами.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184663">MS10-020</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в SMB-клиенте делают возможным удаленное выполнение кода (980232)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну опубликованную и несколько обнаруженных пользователями уязвимостей в Microsoft Windows. Эти уязвимости делают возможным удаленное выполнение кода, если злоумышленник отправит специально созданный SMB-ответ на инициированный клиентом SMB-запрос. Для использования этих уязвимостей злоумышленник должен убедить пользователя инициировать SMB-соединение с вредоносным SMB-сервером.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185146">MS10-025</a></td>
<td style="border:1px solid black;"><strong>Уязвимость служб Microsoft Windows Media делает возможным удаленное выполнение кода (980858)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в службах Windows Media, работающих в ОС Microsoft Windows 2000 Server. Эта уязвимость позволяет злоумышленнику удаленно выполнять код, если он отправит особым образом созданный пакет с транспортной информацией на компьютер под управлением Microsoft Windows 2000 Server, на котором запущены службы Windows Media. Стандартные параметры конфигурации брандмауэра позволяют защитить сеть от атак из-за пределов среды организации. На непосредственно подключенных к Интернету системах рекомендуется держать открытыми минимально необходимое количество портов. В Microsoft Windows 2000 Server службы Windows Media являются дополнительным компонентом и по умолчанию не устанавливаются.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184752">MS10-026</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в кодеках Microsoft MPEG Layer-3 делает возможным удаленное выполнение кода (977816)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в аудиокодеках Microsoft MPEG Layer-3. Данная уязвимость делает возможным удаленное выполнение кода, если пользователь открывает специально созданный файл AVI, содержащий аудиопоток MPEG Layer-3. Если пользователь вошел в систему с правами администратора, то злоумышленник, которому удалось воспользоваться уязвимостью, может установить полный контроль над системой. После этого злоумышленник сможет устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными правами. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184071">MS10-027</a></td>
<td style="border:1px solid black;"><strong>Уязвимость проигрывателя Windows Media делает возможным удаленное выполнение кода (979402)</strong><br />
<br />
Данное обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в проигрывателе Windows Media. Эта уязвимость делает возможным удаленное выполнение кода, если проигрыватель Windows Media откроет особым образом созданный медиа-контент, размещенный на вредоносном веб-сайте. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же самые права, которые имеет локальный пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184814">MS10-021</a></td>
<td style="border:1px solid black;"><strong>Уязвимости ядра Windows делают возможным несанкционированное получение прав (979683)</strong><br />
<br />
Это обновление для системы безопасности устраняет несколько обнаруженных пользователями уязвимостей в Microsoft Windows. Наиболее серьезная из этих уязвимостей делает возможным несанкционированное получение прав, если злоумышленник вошел в систему и запустил специально созданное приложение. Чтобы воспользоваться данными уязвимостями, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему. Данными уязвимостями не могут воспользоваться удаленные или анонимные пользователи.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184779">MS10-022</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в VBScript делает возможным удаленное выполнение кода (981169)</strong><br />
<br />
Это обновление для системы безопасности устраняет открыто опубликованную уязвимость в VBScript в системе Microsoft Windows, которая делает возможным удаленное выполнение кода. Это обновление для системы безопасности имеет уровень опасности &quot;существенный&quot; для Microsoft Windows 2000, Windows XP и Windows Server 2003. В системах Windows Server 2008, Windows Vista, Windows 7 и Windows Server 2008 R2 данный уязвимый код не выполняется, однако поскольку он существует, это обновление предоставляется как мера многоуровневой защиты без указания уровня опасности.<br />
<br />
Эта уязвимость делает возможным удаленное выполнение кода, если на странице вредоносного веб-сайта отображается особым образом созданное диалоговое окно и пользователь нажимает клавишу F1, запуская справочную систему Windows с файлом справки Windows, который подготовлен злоумышленником. Если пользователь вошел в систему с правами администратора, то злоумышленник, которому удалось воспользоваться уязвимостью, может установить полный контроль над системой.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184751">MS10-023</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Office Publisher делает возможным удаленное выполнение кода (981160)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость приложения Microsoft Office Publisher, которая делает возможным удаленное выполнение кода, если пользователь открывает специально созданный файл Publisher. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же самые права, которые имеет локальный пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=167307">MS10-024</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Exchange и службе SMTP Windows делают возможной атаку типа &quot;отказ в обслуживании&quot; (981832)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну опубликованную и одну обнаруженную пользователями уязвимость в Microsoft Exchange и службе SMTP Windows. Наиболее опасная из этих уязвимостей делает возможной атаку типа &quot;отказ в обслуживании&quot;, если злоумышленник отправил специально созданный ответ DNS на компьютер со службой SMTP. По умолчанию компонент SMTP в системах Windows Server 2003, Windows Server 2003 x64 Edition и Windows XP Professional x64 Edition не устанавливается.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Exchange</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=182935">MS10-028</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Visio делают возможным удаленное выполнение кода (980094)</strong><br />
<br />
Это обновление для системы безопасности устраняет две обнаруженных пользователями уязвимости в Microsoft Office Visio. Эти уязвимости делают возможным удаленное выполнение кода при открытии пользователем особым образом созданного файла Visio. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить те же права, которыми обладает локальный пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179056">MS10-029</a></td>
<td style="border:1px solid black;"><strong>Уязвимость компонента ISATAP Windows делает возможной спуфинг (978338)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну обнаруженную пользователями уязвимость в Microsoft Windows. Это обновление для системы безопасности имеет уровень серьезности &quot;средний&quot; для Windows XP, Windows Server 2003, Windows Vista и Windows Server 2008. Windows 7 и Windows Server 2008 R2 не подвержены этой уязвимости, так как эти операционные системы содержат компоненты, развертываемые при установке этого обновления для системы безопасности.<br />
<br />
Эта уязвимость позволяет злоумышленнику выполнять подмену адреса IPv4 для обхода устройств фильтрации, использующих адрес IPv4 источника. Данное обновление для системы безопасности устраняет уязвимость, изменяя способ проверки IPv6 адреса источника стеком TCP/IP системы Windows при обработке передаваемого через туннель пакета ISATAP.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Средний</a><br />
Спуфинг</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Индекс использования уязвимостей  
--------------------------------
  
<span></span>
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости перечислены в порядке убывания оценки индекса использования, затем по коду CVE. Включены только уязвимости, которым в бюллетенях присвоен уровень серьезности "критический" или "существенный".
  
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать о вероятности появления стабильно работающего кода эксплойта в течение 30 дней после выпуска бюллетеня по каждому из обновлений для системы безопасности, которые необходимо установить. Перед назначением приоритетов развертывания ознакомьтесь с каждой приведенной ниже оценкой, относящейся к конкретной конфигурации. Дополнительные сведения об уровнях опасности и способах их определения см. в [индексе использования уязвимостей](http://technet.microsoft.com/en-us/security/cc998259.aspx).

 
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Идентификатор бюллетеня</th>
<th style="border:1px solid black;" >Название уязвимости</th>
<th style="border:1px solid black;" >Код CVE</th>
<th style="border:1px solid black;" >Оценка индекса использования уязвимостей</th>
<th style="border:1px solid black;" >Краткие примечания</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184814">MS10-021</a></td>
<td style="border:1px solid black;">Уязвимость ядра Windows, связанная с выделением памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0236">CVE-2010-0236</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184814">MS10-021</a></td>
<td style="border:1px solid black;">Уязвимость ядра Windows, связанная с созданием символических ссылок</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0237">CVE-2010-0237</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=182935">MS10-028</a></td>
<td style="border:1px solid black;">Уязвимость способа проверки атрибутов в Visio, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0254">CVE-2010-0254</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184071">MS10-027</a></td>
<td style="border:1px solid black;">Уязвимость проигрывателя Windows Media, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0268">CVE-2010-0268</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185146">MS10-025</a></td>
<td style="border:1px solid black;">Уязвимость служб Windows Media, приводящая к переполнению стекового буфера</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0478">CVE-2010-0478</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184751">MS10-023</a></td>
<td style="border:1px solid black;">Уязвимость обработки TextBox при преобразовании файлов в Microsoft Office Publisher, приводящая к переполнению буфера</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0479">CVE-2010-0479</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184752">MS10-026</a></td>
<td style="border:1px solid black;">Уязвимость в аудиодекодере MPEG Layer-3, связанная с переполнением стека</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0480">CVE-2010-0480</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможно существование стабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184779">MS10-022</a></td>
<td style="border:1px solid black;">Уязвимость VBScript, связанная с нажатием клавиши вызова справки</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0483">CVE-2010-0483</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> — возможно существование стабильного кода эксплойта<br />
<br />
Для Windows Server 2008, Windows 7 и Windows Server 2008 R2:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> — существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Эта уязвимость опубликована, как описано в <a href="http://technet.microsoft.com/security/advisory/981169">выпуске 981169 советов по безопасности (Microsoft)</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=182935">MS10-028</a></td>
<td style="border:1px solid black;">Уязвимость способа расчета индексов в Visio, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0256">CVE-2010-0256</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможно существование нестабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184663">MS10-020</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с транзакциями SMB-клиента</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0270">CVE-2010-0270</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможно существование нестабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184663">MS10-020</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с анализом ответов SMB-клиентом</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0476">CVE-2010-0476</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможно существование нестабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184933">MS10-019</a></td>
<td style="border:1px solid black;">Уязвимость WinVerifyTrust, связанная с проверкой подписи</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0486">CVE-2010-0486</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможно существование нестабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184933">MS10-019</a></td>
<td style="border:1px solid black;">Уязвимость Cabview, связанная с проверкой подписи</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0487">CVE-2010-0487</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> — возможно существование нестабильного кода эксплойта</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184663">MS10-020</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с неполным ответом SMB-клиента</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3676">CVE-2009-3676</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> — существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Эта уязвимость опубликована, как описано в <a href="http://technet.microsoft.com/security/advisory/977544">выпуске 977544 советов по безопасности (Microsoft)</a>.<br />
<br />
Вероятный результат: атака типа &quot;отказ в обслуживании&quot;.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=167307">MS10-024</a></td>
<td style="border:1px solid black;">Уязвимость способа обработки записей MX SMTP-сервером</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0024">CVE-2010-0024</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> — существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Вероятный результат: атака типа &quot;отказ в обслуживании&quot;</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184663">MS10-020</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с выделением памяти SMB-клиентом</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0269">CVE-2010-0269</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> — существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184663">MS10-020</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с размером сообщений SMB-клиента</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0477">CVE-2010-0477</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> — существование функционирующего кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Вероятный результат: атака типа &quot;отказ в обслуживании&quot;</td>
</tr>
</tbody>
</table>
  
Продукты, подверженные уязвимости, и соответствующие обновления  
---------------------------------------------------------------
  
<span></span>
В приведенных ниже таблицах перечислены бюллетени в порядке важности категорий программного обеспечения и уровней опасности.
  
**Как пользоваться этими таблицами?**
  
Обращайтесь к этим таблицам, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и узнайте, имеются ли для них обновления для системы безопасности. Для программ или компонентов, указанных в списке, приведены ссылки на доступные обновления с указанием уровня опасности уязвимостей, которые они устраняют.
  
**Примечание.** Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификатора бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.
  
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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
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
<th colspan="10">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-019**](http://go.microsoft.com/fwlink/?linkid=184933)
</td>
<td style="border:1px solid black;">
[**MS10-020**](http://go.microsoft.com/fwlink/?linkid=184663)
</td>
<td style="border:1px solid black;">
[**MS10-025**](http://go.microsoft.com/fwlink/?linkid=185146)
</td>
<td style="border:1px solid black;">
[**MS10-026**](http://go.microsoft.com/fwlink/?linkid=184752)
</td>
<td style="border:1px solid black;">
[**MS10-027**](http://go.microsoft.com/fwlink/?linkid=184071)
</td>
<td style="border:1px solid black;">
[**MS10-021**](http://go.microsoft.com/fwlink/?linkid=184814)
</td>
<td style="border:1px solid black;">
[**MS10-022**](http://go.microsoft.com/fwlink/?linkid=184779)
</td>
<td style="border:1px solid black;">
[**MS10-024**](http://go.microsoft.com/fwlink/?linkid=167307)
</td>
<td style="border:1px solid black;">
[**MS10-029**](http://go.microsoft.com/fwlink/?linkid=179056)
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
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Microsoft Windows 2000 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Проверка подписи Authenticode 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=d7538166-35ee-4c6b-be8c-e83a1fc6cd77)  
(KB978601)  
(критический)  
[Расширение программы просмотра CAB-файлов 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=13846177-f25f-4dd4-9fe9-ac43e1d4d73d)  
(KB979309)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=67ccac04-e5c8-4381-9d1a-9b676dd516a6)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Server 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=73b3d681-26bb-49c1-849e-1f72484cb978)  
(критический)
</td>
<td style="border:1px solid black;">
[Кодеки MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=f6394fc2-b9d0-46cf-9265-a0d4aeb1448f)  
(критический)
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media серии 9](http://www.microsoft.com/downloads/details.aspx?familyid=c0b8b362-a321-4ac9-be98-15c71bb7a043)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=c5f4577e-7546-40e9-8bcd-be11c1b260a6)  
(существенный)
</td>
<td style="border:1px solid black;">
[VBScript 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=421be318-f217-4d12-b7a5-833093189073)<sup>[1]</sup>
(KB981350)  
(существенный)  
[VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=421be318-f217-4d12-b7a5-833093189073)  
(KB981350)  
(существенный)  
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=d5fc47a4-cecb-4817-aafb-45f335061be3)  
(KB981349)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=88a0e872-01de-495b-8eec-d105a970daa7)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="10">
ОС Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-019**](http://go.microsoft.com/fwlink/?linkid=184933)
</td>
<td style="border:1px solid black;">
[**MS10-020**](http://go.microsoft.com/fwlink/?linkid=184663)
</td>
<td style="border:1px solid black;">
[**MS10-025**](http://go.microsoft.com/fwlink/?linkid=185146)
</td>
<td style="border:1px solid black;">
[**MS10-026**](http://go.microsoft.com/fwlink/?linkid=184752)
</td>
<td style="border:1px solid black;">
[**MS10-027**](http://go.microsoft.com/fwlink/?linkid=184071)
</td>
<td style="border:1px solid black;">
[**MS10-021**](http://go.microsoft.com/fwlink/?linkid=184814)
</td>
<td style="border:1px solid black;">
[**MS10-022**](http://go.microsoft.com/fwlink/?linkid=184779)
</td>
<td style="border:1px solid black;">
[**MS10-024**](http://go.microsoft.com/fwlink/?linkid=167307)
</td>
<td style="border:1px solid black;">
[**MS10-029**](http://go.microsoft.com/fwlink/?linkid=179056)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
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
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP с пакетом обновления 2 (SP2) или 3 (SP3)
</td>
<td style="border:1px solid black;">
[Проверка подписи Authenticode 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=2a01ddf0-f3ea-47c8-ada2-e69f6c1b5f96)  
(KB978601)  
(критический)  
[Расширение программы просмотра CAB-файлов 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=6c3ac102-2107-4726-98be-4fbf6b858bfb)  
(KB979309)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2) и Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=dec38c02-3d4a-41c5-8954-e57f56b8fa5b)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Кодеки MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=b1582a74-4a7b-4540-beb1-7c89c86eae87)  
(критический)
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media серии 9 в Windows XP с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5c748c6d-84d1-45a9-8a33-9372eb5504d5)  
(критический)  
[Проигрыватель Windows Media серии 9 в Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=9e4277b4-2dc5-4163-a6aa-7e07dd32b721)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2) и Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=142710fd-9cd4-4dd0-aaba-2aace03c008f)  
(существенный)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=aa8ff157-a7b3-4787-80c9-5bc453f0f1c9) в Windows XP с пакетом обновления 2 (SP2)  
(KB981350)  
(существенный)  
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=cb21d276-65e9-4c8f-96e3-cf6dc36d0133)  
(KB981349)  
(существенный)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=ba7ef6e5-80ba-4281-a611-6e5be008c1b4)  
(KB981332)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2) и Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=de447b76-ec89-426b-ac54-3ae3855d1159)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2) и Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=9dc3e1c2-2e9d-4d86-9fce-446c409ad613)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Проверка подписи Authenticode 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=9bbff00c-f8f4-4a44-98f2-18a868986ae1)  
(KB978601)  
(критический)  
[Расширение программы просмотра CAB-файлов 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e64e487e-2727-4396-b0c9-6eaf000214d2)  
(KB979309)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c5a21239-a9a3-4ec5-9de8-7d2fc16fc6b8)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Кодеки MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=8afca317-a647-44aa-a771-5d85cd5d62ea)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3c0cb02e-3484-4cdf-8c64-c697ad3e2889)  
(существенный)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=896c738d-4058-440f-8d4f-16c678610cd1)  
(KB981350)  
(существенный)  
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=d7e8b930-8708-4f0b-b22b-961c2cbc2673)  
(KB981349)  
(существенный)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=153fd9c1-0f8e-4492-87d1-f0381e7feb23)  
(KB981332)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4f9a696d-2712-4777-a642-e78a38336e8a)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d872bd77-f491-4706-8ff5-081ac0bf3d6f)  
(средний)
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-019**](http://go.microsoft.com/fwlink/?linkid=184933)
</td>
<td style="border:1px solid black;">
[**MS10-020**](http://go.microsoft.com/fwlink/?linkid=184663)
</td>
<td style="border:1px solid black;">
[**MS10-025**](http://go.microsoft.com/fwlink/?linkid=185146)
</td>
<td style="border:1px solid black;">
[**MS10-026**](http://go.microsoft.com/fwlink/?linkid=184752)
</td>
<td style="border:1px solid black;">
[**MS10-027**](http://go.microsoft.com/fwlink/?linkid=184071)
</td>
<td style="border:1px solid black;">
[**MS10-021**](http://go.microsoft.com/fwlink/?linkid=184814)
</td>
<td style="border:1px solid black;">
[**MS10-022**](http://go.microsoft.com/fwlink/?linkid=184779)
</td>
<td style="border:1px solid black;">
[**MS10-024**](http://go.microsoft.com/fwlink/?linkid=167307)
</td>
<td style="border:1px solid black;">
[**MS10-029**](http://go.microsoft.com/fwlink/?linkid=179056)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
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
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Проверка подписи Authenticode 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=0e7e3deb-f078-4953-9642-675ec69267f2)  
(KB978601)  
(критический)  
[Расширение программы просмотра CAB-файлов 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ae9b1d0-0dbe-4abd-b315-10cea4ceccd7)  
(KB979309)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1189304f-d626-426d-960c-a86dc2d2b528)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Кодеки MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=9f89746c-181e-4177-a851-ec1826e78b6d)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=0a7ea2d0-61ce-4b68-ad82-d917b1a56f9d)  
(существенный)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=28b035b8-d56e-4e93-b811-9a82cf1d4ba9)  
(KB981350)  
(существенный)  
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=a142a553-85fc-40e0-9426-8d58f6a4333c)  
(KB981349)  
(существенный)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=72754e1b-3d09-4b9d-8794-689c45a37f66)  
(KB981332)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=f781e9e4-87d4-4243-9d44-256424d75fec)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=cd007a6c-04b3-490c-aff4-d5af3e69d477)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Проверка подписи Authenticode 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=99a3f6da-728f-421c-ab41-c4c4751934a4)  
(KB978601)  
(критический)  
[Расширение программы просмотра CAB-файлов 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=1709fd4e-d7c6-4cbb-8b71-a96b8d6eee58)  
(KB979309)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=52e4f66b-b76c-46a1-aeff-74efa21fc743)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Кодеки MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=b97e7ea1-a163-4ce4-8cbc-5f933773c4b2)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1fc66f54-260a-4219-a0b4-056ba9dd0abe)  
(существенный)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=339ddf48-8949-4857-9ef6-1ddcc7c5f8b8)  
(KB981350)  
(существенный)  
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=a489b4e3-78d2-411b-b27c-5987b8fc91d1)  
(KB981349)  
(существенный)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=72c3013b-f72f-422b-8a89-2246dea4b378)  
(KB981332)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=644ff070-237b-4a73-b2e2-9fffdafa3927)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=19cfddfe-e8da-4564-9730-babfae4a3ebb)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Проверка подписи Authenticode 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=06832599-1e9b-4792-8c7b-7b5b3a3d6277)  
(KB978601)  
(критический)  
[Расширение программы просмотра CAB-файлов 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=811a2b28-655d-4b5d-821e-5a90d556dba3)  
(KB979309)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-Based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b2b6d8b1-63cc-459c-b5fa-1355386273c8)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-Based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8dcb8be8-fb78-4518-aa7e-f8b17f7dfb86)  
(существенный)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=9a8bee82-5f7f-490e-a1eb-481f6d4fc4f5)  
(KB981350)  
(существенный)  
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=7d542ac6-8a5b-4dd7-8688-2b5feb563636)  
(KB981349)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-Based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=56c8238d-8b04-4aa5-8719-40550cd7325c)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-Based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=916f1b09-e79e-4347-9fbc-c0cf07de397d)  
(средний)
</td>
</tr>
<tr>
<th colspan="10">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-019**](http://go.microsoft.com/fwlink/?linkid=184933)
</td>
<td style="border:1px solid black;">
[**MS10-020**](http://go.microsoft.com/fwlink/?linkid=184663)
</td>
<td style="border:1px solid black;">
[**MS10-025**](http://go.microsoft.com/fwlink/?linkid=185146)
</td>
<td style="border:1px solid black;">
[**MS10-026**](http://go.microsoft.com/fwlink/?linkid=184752)
</td>
<td style="border:1px solid black;">
[**MS10-027**](http://go.microsoft.com/fwlink/?linkid=184071)
</td>
<td style="border:1px solid black;">
[**MS10-021**](http://go.microsoft.com/fwlink/?linkid=184814)
</td>
<td style="border:1px solid black;">
[**MS10-022**](http://go.microsoft.com/fwlink/?linkid=184779)
</td>
<td style="border:1px solid black;">
[**MS10-024**](http://go.microsoft.com/fwlink/?linkid=167307)
</td>
<td style="border:1px solid black;">
[**MS10-029**](http://go.microsoft.com/fwlink/?linkid=179056)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Проверка подписи Authenticode 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=a52225a7-6005-4f2b-8291-db20558f23f8)  
(KB978601)  
(критический)  
[Расширение программы просмотра CAB-файлов 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=6145e2b2-36fd-4360-bd5b-2bd11890fc52)  
(KB979309)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=25eeaeb3-c0a3-4a02-9912-acd0342648ba)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Кодеки MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=0e7140bb-42d3-48b3-9f4b-d55b17770de8)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Vista](http://www.microsoft.com/downloads/details.aspx?familyid=86d7b054-af4f-4d8a-9873-cb5246466374)  
(существенный)  
[Windows Vista с пакетом обновления 1 (SP1) и 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=86d7b054-af4f-4d8a-9873-cb5246466374)  
(средний)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=ee5c42c6-16bb-48bf-95c2-c188bb17d04b)  
(KB981349)  
(Уровень опасности не определен<sup>[2]</sup>)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=f2a37dbf-4a95-4e8d-a474-ecacd9aee690)  
(KB981332)  
(Уровень опасности не определен<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=196055a6-15d1-4da8-b33d-501e69bf5176)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Проверка подписи Authenticode 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=9ba7468c-23a4-4994-9a5a-22e96ef586f3)  
(KB978601)  
(критический)  
[Расширение программы просмотра CAB-файлов 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=5b7efa82-0feb-413a-9f8e-212e7432cd99)  
(KB979309)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=394c1caa-97e4-47a3-9aac-a4a88508bd31)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Кодеки MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=b885aef4-3a5d-4c3e-bef6-5efef2965752)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=7c84aa24-6331-427a-969c-27f7d39db3d7)  
(существенный)  
[Windows Vista x64 Edition с пакетами обновления 1 (SP1) и 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7c84aa24-6331-427a-969c-27f7d39db3d7)  
(средний)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=ea5c5e9c-0ecd-47bc-912d-5adc00d1aa21)  
(KB981349)  
(Уровень опасности не определен<sup>[2]</sup>)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=79093796-4ea9-4c6c-92cc-3fd63c5db918)  
(KB981332)  
(Уровень опасности не определен<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7c1d1622-1b67-438d-aae4-1a3954974a36)  
(средний)
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-019**](http://go.microsoft.com/fwlink/?linkid=184933)
</td>
<td style="border:1px solid black;">
[**MS10-020**](http://go.microsoft.com/fwlink/?linkid=184663)
</td>
<td style="border:1px solid black;">
[**MS10-025**](http://go.microsoft.com/fwlink/?linkid=185146)
</td>
<td style="border:1px solid black;">
[**MS10-026**](http://go.microsoft.com/fwlink/?linkid=184752)
</td>
<td style="border:1px solid black;">
[**MS10-027**](http://go.microsoft.com/fwlink/?linkid=184071)
</td>
<td style="border:1px solid black;">
[**MS10-021**](http://go.microsoft.com/fwlink/?linkid=184814)
</td>
<td style="border:1px solid black;">
[**MS10-022**](http://go.microsoft.com/fwlink/?linkid=184779)
</td>
<td style="border:1px solid black;">
[**MS10-024**](http://go.microsoft.com/fwlink/?linkid=167307)
</td>
<td style="border:1px solid black;">
[**MS10-029**](http://go.microsoft.com/fwlink/?linkid=179056)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Проверка подписи Authenticode 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=97ffeec8-8b6d-4a30-97b0-4bff2ba5e91d)\*  
(KB978601)  
(критический)  
[Расширение программы просмотра CAB-файлов 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f111735b-68b0-4bcc-9dd8-818a5eca3400)  
(KB979309)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=51c9c420-4507-4911-a8f5-82331a696882)\*  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Кодеки MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=8e9c04c9-898f-4ed2-949d-f4343cc0d9f6)\*\*  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=25e3ce7f-53a0-4049-a65c-011d2143c4c2)\*  
(средний)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=dbe89813-0a45-463b-928c-1e58f7bb596a)\*\*  
(KB981349)  
(Уровень опасности не определен<sup>[2]</sup>)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=527d6376-efc9-436b-835b-219d38bb28f0)\*\*  
(KB981332)  
(Уровень опасности не определен<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e29ead69-000a-4982-a25c-f3981eda381a)\*\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=61ece7bc-e9fa-4ede-ba7d-9e5a4c64b9be)\*  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем и Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Проверка подписи Authenticode 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=49f9f740-023a-4291-becf-838a1d282321)\*  
(KB978601)  
(критический)  
[Расширение программы просмотра CAB-файлов 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=91c08251-0085-44cb-9e9c-9a1a84374caf)  
(KB979309)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=61c26a1f-c885-4474-9843-204c41628889)\*  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Кодеки MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=d6f2e1ae-48d3-4d2c-b329-32cff00afee5)\*\*  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=8b99e54d-955b-4a06-9a04-b2f4596efd72)\*  
(средний)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=9db62357-557d-40cd-9826-b7baa6c9de65)\*\*  
(KB981349)  
(Уровень опасности не определен<sup>[2]</sup>)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=0c384dbc-21b7-4cbc-b68f-ced971d9b791)\*\*  
(KB981332)  
(Уровень опасности не определен<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=8f922e64-e3a6-46fe-9a81-b2813ea6a330)\*\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=72e7c7ea-55ef-457b-a03a-49aa9dea2e84)\*  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Проверка подписи Authenticode 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=bd60779a-8bb1-4107-a344-9b09a50e96ff)  
(KB978601)  
(критический)  
[Расширение программы просмотра CAB-файлов 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=eb116688-1d6e-4e20-948e-1d347af5d985)  
(KB979309)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-Based Systems и Windows Server 2008 for Itanium-Based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=bcf8b919-08a9-487f-8dfd-3ca24328c4f3)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-Based Systems и Windows Server 2008 for Itanium-Based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b1f9746d-61a2-406f-b707-60646bd5b5bb)  
(средний)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=84c5aaae-9417-42a1-834f-22c1ad46a12f)  
(KB981349)  
(Уровень опасности не определен<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-Based Systems и Windows Server 2008 for Itanium-Based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8c48302c-a1d6-41bc-ad24-7ce7332d4842)  
(средний)
</td>
</tr>
<tr>
<th colspan="10">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-019**](http://go.microsoft.com/fwlink/?linkid=184933)
</td>
<td style="border:1px solid black;">
[**MS10-020**](http://go.microsoft.com/fwlink/?linkid=184663)
</td>
<td style="border:1px solid black;">
[**MS10-025**](http://go.microsoft.com/fwlink/?linkid=185146)
</td>
<td style="border:1px solid black;">
[**MS10-026**](http://go.microsoft.com/fwlink/?linkid=184752)
</td>
<td style="border:1px solid black;">
[**MS10-027**](http://go.microsoft.com/fwlink/?linkid=184071)
</td>
<td style="border:1px solid black;">
[**MS10-021**](http://go.microsoft.com/fwlink/?linkid=184814)
</td>
<td style="border:1px solid black;">
[**MS10-022**](http://go.microsoft.com/fwlink/?linkid=184779)
</td>
<td style="border:1px solid black;">
[**MS10-024**](http://go.microsoft.com/fwlink/?linkid=167307)
</td>
<td style="border:1px solid black;">
[**MS10-029**](http://go.microsoft.com/fwlink/?linkid=179056)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
Нет
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[Проверка подписи Authenticode 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=8d4a6c65-e171-4570-8f3f-118f06910baf)  
(KB978601)  
(критический)  
[Расширение программы просмотра CAB-файлов 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=f0dbac52-0f0e-40bc-9371-17fa594424d5)  
(KB979309)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=389184c5-9001-497d-bdf4-81f97ecb617f)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=ff58d80c-33ce-4d9e-aaa5-0b1841458931)  
(средний)
</td>
<td style="border:1px solid black;">
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=c3f76835-0053-4e53-a451-14255e7a4fc0)  
(KB981332)  
(Уровень опасности не определен<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Проверка подписи Authenticode 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=cf8c6721-05c2-4680-93b4-be36f09c6d15)  
(KB978601)  
(критический)  
[Расширение программы просмотра CAB-файлов 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=b23efe7d-bca4-4d49-9104-6ae39dc5daa9)  
(KB979309)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=f3495dae-71f3-421d-a191-d26965f26ad1)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows 7 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=7f1dc055-2ec9-407a-9e69-da12338587e3)  
(средний)
</td>
<td style="border:1px solid black;">
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=998164b7-4b8c-468b-8d39-f242633c8838)  
(KB981332)  
(Уровень опасности не определен<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-019**](http://go.microsoft.com/fwlink/?linkid=184933)
</td>
<td style="border:1px solid black;">
[**MS10-020**](http://go.microsoft.com/fwlink/?linkid=184663)
</td>
<td style="border:1px solid black;">
[**MS10-025**](http://go.microsoft.com/fwlink/?linkid=185146)
</td>
<td style="border:1px solid black;">
[**MS10-026**](http://go.microsoft.com/fwlink/?linkid=184752)
</td>
<td style="border:1px solid black;">
[**MS10-027**](http://go.microsoft.com/fwlink/?linkid=184071)
</td>
<td style="border:1px solid black;">
[**MS10-021**](http://go.microsoft.com/fwlink/?linkid=184814)
</td>
<td style="border:1px solid black;">
[**MS10-022**](http://go.microsoft.com/fwlink/?linkid=184779)
</td>
<td style="border:1px solid black;">
[**MS10-024**](http://go.microsoft.com/fwlink/?linkid=167307)
</td>
<td style="border:1px solid black;">
[**MS10-029**](http://go.microsoft.com/fwlink/?linkid=179056)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
Нет
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Нет
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
Windows Server 2008 R2 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[Проверка подписи Authenticode 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=94dfdaae-8464-4de6-a401-7eb70b3bb34f)\*  
(KB978601)  
(критический)  
[Расширение программы просмотра CAB-файлов 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=a2979c02-2a80-4b84-bf6c-4798064bdf28)  
(KB979309)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=cd1a046e-915d-4904-b753-5a24be10c504)\*  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=28389c1d-2a12-4bef-a59b-726bb6449c8b)\*  
(средний)
</td>
<td style="border:1px solid black;">
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=c4039d40-a0c7-4183-ab50-04f690d1c5dc)\*\*  
(KB981332)  
(Уровень опасности не определен<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=eb27cd2b-d514-4405-8650-259a42e35155)\*\*  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Проверка подписи Authenticode 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=40f622d2-48e7-4eb2-9430-bbd218cb5208)  
(KB978601)  
(критический)  
[Расширение программы просмотра CAB-файлов 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=5e416d4b-5de7-4688-80c6-245de159e0ce)  
(KB979309)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-Based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=541e9e2f-ec1d-42b2-aae5-481c0d435169)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-Based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=d4ea3984-5183-47f1-814e-29cb6c90ae06)  
(средний)
</td>
<td style="border:1px solid black;">
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=8174463c-5c5e-4095-90c8-fd1e898d4ba5)  
(KB981332)  
(Уровень опасности не определен<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
</table>
 
**Примечания для Windows Server 2008 и Windows Server 2008 R2**

**\*Уязвимости подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Это обновление (с одинаковой степенью серьезности) применяется к указанным выше поддерживаемым выпускам Windows Server 2008 или Windows Server 2008 R2 независимо от наличия установленных основных компонентов сервера. Дополнительные сведения об этом варианте установки см. в статьях MSDN [Ядро сервера](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) и [Ядро сервера для Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Уязвимости не подвержены системы, при развертывании которых устанавливалось только ядро сервера.** Поддерживаемые выпуски Windows Server 2008 или Windows Server 2008 R2, при развертывании которых выбиралась установка только ядра сервера, не подвержены уязвимостям, устраняемым этим обновлением. Дополнительные сведения об этом варианте установки см. в статьях MSDN [Ядро сервера](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) и [Ядро сервера для Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Примечания к бюллетеню MS10-022**

<sup>[1]</sup>Это обновление для системы безопасности обновляет установленный обработчик с VBScript 5.1 до VBScript 5.6.

<sup>[2]</sup>Уровни серьезности неприменимы к этому обновлению, поскольку уязвимость, описанная в этом бюллетене, не затрагивает это программное обеспечение. Однако в качестве дополнительной меры защиты от возможных новых направлений атаки в будущем корпорация Майкрософт рекомендует пользователям этого программного обеспечения установить это обновление для системы безопасности.

**Примечания к бюллетеню MS10-024**

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

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
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-023**](http://go.microsoft.com/fwlink/?linkid=184751)
</td>
<td style="border:1px solid black;">
[**MS10-028**](http://go.microsoft.com/fwlink/?linkid=182935)
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
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2002 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=943b3830-70d5-46c5-bffc-1b494434b5f7)  
(KB980466)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2002 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2d563cbc-d8f7-486b-8c54-25d168085376)  
(KB979364)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=7c2f4610-77bb-4d72-847b-1a06c523b137)  
(KB980469)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=803a7ea0-a9da-46dd-9548-0177d3774be7)  
(KB979356)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
система Microsoft Office 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2007 с пакетом обновления 1 (SP1) и Microsoft Office Publisher 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=10ca2f71-0ab2-4344-b7fd-bbbd6a783a96)  
(KB980470)  
(существенный)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2007 с пакетом обновления 1 (SP1) и Microsoft Office Visio 2007 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=56fe020f-4444-4a43-aa98-e99a622f6a69)  
(KB979365)  
(существенный)
</td>
</tr>
</table>
 

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
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS10-024**](http://go.microsoft.com/fwlink/?linkid=167307)
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
Microsoft Exchange Server 2000
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2000 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=e47c90a0-c9c8-43b7-bec7-34107ddde294)  
(KB976703)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2003
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=bc8391f8-5335-496b-ad4c-bae38509be4a)  
(KB976702)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 для 64-разрядных (x64) систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=6a894b4e-12b6-4a91-9555-d813956b6aac)  
(KB981407)  
(Уровень опасности не определен<sup>[1]</sup>)  
[Microsoft Exchange Server 2007 для 64-разрядных (x64) систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b8f7f872-16d5-49d6-9867-adc01351c06f)  
(KB981383)  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 для 64-разрядных (x64) систем](http://www.microsoft.com/downloads/details.aspx?familyid=7dcf2390-dff7-4e3a-acca-03f4d43fb79a)  
(KB981401)  
(Уровень опасности не определен<sup>[1]</sup>)
</td>
</tr>
</table>
 
**Примечания к бюллетеню MS10-024**

<sup>[1]</sup>Уровни серьезности неприменимы к этому обновлению, поскольку уязвимость, описанная в этом бюллетене, не затрагивает это программное обеспечение. Тем не менее, корпорация Майкрософт рекомендует пользователям данного программного обеспечения установить это обновление, в котором содержится мера для обеспечения многоуровневой защиты, вносящая дополнительную энтропию исходных портов в транзакции DNS, инициируемые службой SMTP.

Сведения о дополнительных файлах обновления с тем же идентификатором бюллетеня также см. в других категориях ПО в разделе **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
**В центре безопасности**

Управление программным обеспечением и обновлениями для системы безопасности для установки на серверы, настольные и переносные компьютеры организации. Дополнительные сведения см. на веб-сайте [Центра управления обновлениями TechNet](http://go.microsoft.com/fwlink/?linkid=69903). [Центр безопасности TechNet](http://go.microsoft.com/fwlink/?linkid=21171) содержит дополнительные сведения о безопасности в продуктах Майкрософт. Доступ к этим сведениям можно также получить, посетив веб-сайт [Безопасность дома](http://go.microsoft.com/fwlink/?linkid=85102) и щелкнув ссылку "Последние обновления".

Обновления для системы безопасности доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747) и [Центре обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130). Обновления для системы безопасности также доступны на веб-сайте [Центра загрузки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".

Наконец, обновления для системы безопасности можно загрузить из [каталога Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=96155). Он обеспечивает возможность поиска содержимого (в том числе обновлений для системы безопасности, драйверов и пакетов обновления), которое предоставляется через Центр обновления Windows и Центр обновления Майкрософт. При поиске по номеру бюллетеня по безопасности (например, MS07-036) можно добавлять необходимые обновления (в том числе на различных языках) в корзину и загружать их в указанную папку. Дополнительные сведения см. на веб-сайте каталога Центра обновления Майкрософт в разделе [вопросов и ответов](http://go.microsoft.com/fwlink/?linkid=97900).

**Примечание.** С 1 августа 2009 г. Майкрософт прекратила поддержку центра загрузки Office и средства инвентаризации центра загрузки Office. Чтобы продолжить получать последние обновления для продуктов Microsoft Office, используйте веб-сайт [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747). Дополнительные сведения см. на веб-странице [Центр загрузки Microsoft Office: вопросы и ответы](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Руководство по диагностике и развертыванию**

Корпорация Майкрософт предоставляет руководство по диагностике и развертыванию обновлений для системы безопасности. В этом руководстве содержатся рекомендации и сведения, позволяющие ИТ-специалистам оптимальнее использовать различные средства для диагностики и развертывания обновлений для системы безопасности. Дополнительные сведения см. в [статье 961747 базы знаний Майкрософт](http://support.microsoft.com/kb/961747).

**Анализатор безопасности Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений безопасности и стандартных ошибок в конфигурации системы безопасности. Дополнительные сведения об анализаторе безопасности MBSA см. на веб-сайте [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Службы Windows Server Update Services**

Службы Windows Server Update Services (WSUS) позволяют администраторам быстрым и надежным образом развертывать последние критические обновления и обновления для систем безопасности операционных систем Microsoft Windows 2000 и более поздних версий, пакетов Office XP и более поздних версий, серверов Exchange Server 2003 и SQL Server 2000 в системах Microsoft Windows 2000 и более поздних версий.

Дополнительные сведения о развертывании данного обновления безопасности с помощью служб WSUS см. на веб-сайте [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Сервер Systems Management Server**

Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет хорошо сконфигурированное решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей. Последний выпуск сервера SMS — System Center Configuration Manager 2007 — доступен для загрузки; сведения о нем см. также на веб-сайте [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Дополнительные сведения о том, как администраторы могут использовать сервер SMS 2003 для развертывания обновлений для системы безопасности, см. на веб-странице [Управление исправлениями для системы безопасности сервера SMS 2003](http://go.microsoft.com/fwlink/?linkid=22939). Для развертывания обновлений системы безопасности пользователям сервера SMS 2.0 доступно средство Security Update Inventory Tool (SUIT). Дополнительные сведения о сервере SMS см. на веб-сайте [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Примечание.** Для предоставления широкой поддержки при определении необходимости применения и развертывания обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используется средство Microsoft Baseline Security Analyzer. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. в статье [Развертывание обновлений программного обеспечения с помощью функции распространения программ сервера SMS](http://go.microsoft.com/fwlink/?linkid=33341). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакета [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

**Средство оценки совместимости обновлений и набор средств для обеспечения совместимости приложений**

Часто обновления записываются в одни те же файлы, а для запуска приложений требуется настроить параметры реестра. Это приводит к возникновению несовместимостей и увеличивает время, затрачиваемое на развертывание обновлений для системы безопасности. Облегчить тестирование и проверку обновлений Windows для установленных приложений можно с помощью [компонентов оценки совместимости обновлений](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true), входящих в состав [набора средств для обеспечения совместимости приложений](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Набор средств для обеспечения совместимости приложений содержит необходимые средства и документацию для выявления проблем совместимости приложений и уменьшения степени воздействия этих проблем перед развертыванием системы Microsoft Windows Vista, обновлений из Центра обновления Windows, обновлений с веб-сайта безопасности Майкрософт или новой версии проводника.

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

#### Высокоприоритетные обновления, не относящиеся к безопасности и распространяемые через Центр обновления Майкрософт, Центр обновления Windows и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-сайте Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт](http://support.microsoft.com/kb/894199). Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
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

-   Марка Рабиновича (Mark Rabinovich) из [Visuality Systems Ltd.](http://www.visualitynq.com/) за сообщение о проблеме, описанной в MS10-020
-   Лорана Гаффье (Laurent Gaffié) из компании [stratsec](http://www.stratsec.net/) за сообщение о трех проблемах, описанных в MS10-020
-   Мэтью Юрчика ("j00ru") (Matthew 'j00ru' Jurczyk) и Гинваэля Колдвинда (Gynvael Coldwind) из [Hispasec](http://www.hispasec.com/)[Virustotal](http://www.virustotal.com/) за сообщение о 5 проблемах, описанных в MS10-021
-   Тэвиса Орманди (Tavis Ormandy) из [Google Inc.](http://www.google.com/) за сообщение о двух проблемах, описанных в MS10-021
-   Мартина Тофаля (Martin Tofall) из компании [Obsidium Software](http://www.obsidium.de/) за сообщение о проблеме, описанной в MS10-021
-   Лайонела Доненса (Lionel d'Hauenens), работающего с [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в MS10-023
-   Фабьена Периго (Fabien Perigaud) из компании [CERT-LEXSI](http://cert.lexsi.com/) за сообщение о проблеме, описанной в MS10-025
-   Фабьена Периго (Fabien Perigaud) из [CERT-LEXSI](http://cert.lexsi.com/), [VUPEN Vulnerability Research Team](http://www.vupen.com/), Vulnerability Research Team, [TELUS Security Labs](http://telussecuritylabs.com/), [Core Security Technologies](http://www.coresecurity.com/) и [Отдел безопасности NSFOCUS](http://www.nsfocus.com/) за сотрудничество с нами и за предоставление информации о проблеме качества исходного обновления безопасности для MS10-025
-   Ямату Ли (Yamata Li) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение о проблеме, описанной в MS10-026
-   Анонимного исследователя, сотрудничающего с компанией [TippingPoint](http://www.tippingpoint.com/) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в MS10-027
-   Бина Лю (Bing Liu) из отдела [FortiGuard Labs](http://www.fortiguard.com/) компании Fortinet за сообщение о двух проблемах, описанных в MS10-028
-   Габи Накибли (Gabi Nakibly) из National EW Research & Simulation Center в г. Рафаэль (Хайфа), за сообщение о проблеме, описанной в MS10-029

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Пользователи из США и Канады могут обратиться в службу [поддержки по вопросам безопасности](http://go.microsoft.com/fwlink/?linkid=21131) или позвонить по телефону 1-866-PCSAFETY. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Дополнительные сведения о вариантах поддержки см. на веб-сайте [справки и поддержки корпорации Майкрософт](http://support.microsoft.com/).
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-сайт международной справки и поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (13 апреля 2010): Обзор бюллетеней опубликован.
-   Вер. 1.1 (14 апреля 2010): В разделе **Аннотации** исправлено требование перезагрузки для MS10-025. Кроме того, исправлено указание числа ядер сервера для Windows Server 2008 и Windows Server 2008 R2 применительно только для обновления KB978601 в MS10-019.
-   Вер. 2.0 (21 апреля 2010): В новой редакции добавлена информация для пользователей о том, что исходное обновление безопасности для MS10-025 не защищает компьютеры от уязвимости, описанной в бюллетене. Майкрософт рекомендует пользователям применить одно из временных решений, описанных в MS10-025, для снижения степени воздействия на уязвимые системы до тех пор, пока не будет доступно исправленное обновление безопасности.
-   Вер. 3.0 (27 апреля 2010): В новой редакции предлагается новая редакция обновления безопасности для MS10-025.
-   Вер. 4.0 (13 июля 2010): Новая редакция этого бюллетеня опубликована, чтобы предложить повторно выпущенное обновление для Windows Server 2008 и Windows Server 2008 R2 для MS10-024.

*Built at 2014-04-18T01:50:00Z-07:00*
