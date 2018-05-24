---
TOCTitle: 'MS14-MAR'
Title: Обзор бюллетеней по безопасности Microsoft за март 2014 года
ms:assetid: 'ms14-mar'
ms:contentKeyID: 61598067
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms14-mar(v=Security.10)'
---

Обзор бюллетеней по безопасности Microsoft за март 2014 года
============================================================

Дата публикации: 11 марта 2014 г. | Обновлено: 18 сентября 2014 г.

**Версия:** 1.1

В этом обзоре указаны бюллетени по безопасности, выпущенные в марте 2014 года.

После выпуска бюллетеней за март 2014 года этот обзор заменит предварительное уведомление, выпущенное 6 марта 2014 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

12 марта 2014 года в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в мартовской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032572977&culture=en-us).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел **Прочие сведения**.

Аннотации
---------

<span id="sectionToggle0"></span>
В приведенной ниже таблице описаны бюллетени по безопасности за этот месяц в порядке, соответствующем уровню опасности.

Сведения об уязвимом программном обеспечении см. в следующем разделе, **Подвержены уязвимости**.

 
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
<th style="border:1px solid black;" >Идентификатор бюллетеня</th>
<th style="border:1px solid black;" >Название бюллетеня и аннотация</th>
<th style="border:1px solid black;" >Максимальный уровень серьезности и воздействие уязвимости</th>
<th style="border:1px solid black;" >Необходимость перезагрузки</th>
<th style="border:1px solid black;" >Подвержены уязвимости</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (2925418)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну опубликованную и 17 обнаруженных пользователями уязвимостей в Internet Explorer. Данные уязвимости делают возможным удаленное выполнение кода при открытии специально созданной веб-страницы в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392071">MS14-013</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft DirectShow делает возможным удаленное выполнение кода (2929961)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость делает возможным удаленное выполнение кода, если пользователь откроет специально созданный файл изображения. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392067">MS14-015</a></td>
<td style="border:1px solid black;"><strong>Уязвимости работающего в режиме ядра Windows драйвера делают возможным несанкционированное получение прав (2930275)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну опубликованную и одну обнаруженную пользователями уязвимость в Microsoft Windows. Наиболее серьезные из этих уязвимостей делают возможным несанкционированное повышение привилегий в том случае, если злоумышленник войдет в систему пользователя и запустит специально созданное приложение. Чтобы воспользоваться данными уязвимостями, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392066">MS14-016</a></td>
<td style="border:1px solid black;"><strong>Уязвимость протокола SAMR (Security Account Manager Remote) делает возможным обход функций безопасности (2934418)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость делает возможным обход функций безопасности, если злоумышленник многократно пытается сопоставить пароли имени пользователя.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Обход функции безопасности</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392070">MS14-014</a></td>
<td style="border:1px solid black;"><strong>Уязвимость Silverlight делает возможным обход функций безопасности (2932677)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Silverlight. Эта уязвимость делает возможным обход функций безопасности, если злоумышленник разместит веб-сайт со специально созданным содержимым Silverlight, предназначенным для использования этой уязвимости, и убедит пользователя посетить веб-сайт. В любом случае злоумышленник не может заставить пользователей посетить такой веб-сайт. Вместо этого злоумышленник должен склонить пользователей к посещению веб-сайта, как правило, убеждая их щелкнуть ссылку в сообщении электронной почты или программы обмена мгновенными сообщениями. Специально созданное веб-содержимое можно также отобразить и передать на уязвимые системы посредством рекламных объявлений или иными способами.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Обход функции безопасности</td>
<td style="border:1px solid black;">Перезагрузка не требуется</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
</tbody>
</table>
  
 
  
Индекс использования уязвимостей  
--------------------------------
  
<span id="sectionToggle1"></span>
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости сгруппированы по идентификаторам бюллетеней и затем по кодам CVE. Включены только уязвимости, которым в бюллетенях присвоен уровень серьезности "критический" или "существенный".
  
Как пользоваться этой таблицей?
  
Используйте эту таблицу, чтобы узнать о вероятности появления эксплойтов для выполнения произвольного кода и DoS-атаки в течение 30 дней после выпуска бюллетеня по каждому из обновлений безопасности, которые необходимо установить. Чтобы назначить приоритеты развертывания, ознакомьтесь с приведенными ниже оценками в соответствии с вашей конфигурацией. Дополнительные сведения об уровнях опасности и способах их определения см. в [индексе использования уязвимостей](http://technet.microsoft.com/security/cc998259).
  
В приведенной ниже таблице "последний выпуск программного обеспечения" обозначает соответствующее программное обеспечение, а термином "старые выпуски программного обеспечения" обозначены все прежние поддерживаемые выпуски программного обеспечения, указанные в таблице "Подвержены уязвимости" или "Не подвержены уязвимости" в этом бюллетене.
  
<table style="width:100%;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Идентификатор бюллетеня</th>
<th style="border:1px solid black;" >Название уязвимости</th>
<th style="border:1px solid black;" >Код CVE</th>
<th style="border:1px solid black;" >Оценка возможности использования уязвимостей для последнего выпуска программного обеспечения</th>
<th style="border:1px solid black;" >Оценка возможности использования уязвимостей для более старых выпусков программного обеспечения</th>
<th style="border:1px solid black;" >Оценка использования уязвимости типа &quot;отказ в обслуживании&quot;</th>
<th style="border:1px solid black;" >Краткие примечания</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0297">CVE-2014-0297</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0298">CVE-2014-0298</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0299">CVE-2014-0299</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0302">CVE-2014-0302</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0303">CVE-2014-0303</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0304">CVE-2014-0304</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0305">CVE-2014-0305</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0306">CVE-2014-0306</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0307">CVE-2014-0307</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0308">CVE-2014-0308</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0309">CVE-2014-0309</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0311">CVE-2014-0311</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0312">CVE-2014-0312</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0313">CVE-2014-0313</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0314">CVE-2014-0314</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0321">CVE-2014-0321</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0322">CVE-2014-0322</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Данная уязвимость была открыто опубликована.<br />
<br />
Специалистам Майкрософт известно об ограниченных направленных атаках с целью использования уязвимости в Internet Explorer 10.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0324">CVE-2014-0324</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Специалистам Майкрософт известно об ограниченных направленных атаках с целью использования уязвимости в Internet Explorer 8.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4112">CVE-2014-4112</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392071">MS14-013</a></td>
<td style="border:1px solid black;">Уязвимость DirectShow, связанная с повреждением памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0301">CVE-2014-0301</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392070">MS14-014</a></td>
<td style="border:1px solid black;">Уязвимость Silverlight, делающая возможным обход функций безопасности DEP/ASLR</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0319">CVE-2014-0319</a></td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, связанная с обходом функций безопасности.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392067">MS14-015</a></td>
<td style="border:1px solid black;">Уязвимость подсистемы Win32k, приводящая к несанкционированному получению прав</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0300">CVE-2014-0300</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392067">MS14-015</a></td>
<td style="border:1px solid black;">Уязвимость Win32k, приводящая к раскрытию информации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0323">CVE-2014-0323</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Данная уязвимость была открыто опубликована.<br />
<br />
Это уязвимость старых выпусков программного обеспечения, приводящая к раскрытию информации.<br />
<br />
Это уязвимость, делающая возможной атаку типа &quot;отказ в обслуживании&quot;, в последнем выпуске программного обеспечения.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=392066">MS14-016</a></td>
<td style="border:1px solid black;">Уязвимость SAMR, связанная с обходом функций безопасности</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0317">CVE-2014-0317</a></td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, связанная с обходом функций безопасности.</td>
</tr>
</tbody>
</table>
  
Подвержены уязвимости  
---------------------
  
<span id="sectionToggle2"></span>
В приведенных ниже таблицах перечислены бюллетени в порядке важности категорий программного обеспечения и уровней опасности.
  
**Как пользоваться этими таблицами?**
  
Обращайтесь к этим таблицам, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и узнайте, имеются ли для них обновления для системы безопасности. Если программное обеспечение или компонент содержится в списке, для него также указан уровень важности соответствующего обновления программного обеспечения.
  
**Примечание.** Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификатора бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.
  
**Компоненты операционных систем Windows**

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows XP**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://go.microsoft.com/fwlink/?linkid=392066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2925418)  
(критический)  
Internet Explorer 7   
(2925418)  
(критический)  
Internet Explorer 8   
(2925418)  
(критический)

</td>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)  
(С установленным режимом ADAM)  
(2933528)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2925418)  
(критический)  
Internet Explorer 7   
(2925418)  
(критический)  
Internet Explorer 8   
(2925418)  
(критический)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(С установленным режимом ADAM)  
(2933528)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://go.microsoft.com/fwlink/?linkid=392066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**

</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2003 с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2925418)  
(средний)  
Internet Explorer 7  
(2925418)  
(средний)  
Internet Explorer 8  
(2925418)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(С установленной службой Active Directory)  
(2923392)  
(существенный)  
Windows Server 2003 с пакетом обновления 2 (SP2)  
(С установленным режимом ADAM)  
(2933528)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2925418)  
(средний)  
Internet Explorer 7  
(2925418)  
(средний)  
Internet Explorer 8  
(2925418)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(С установленной службой Active Directory)  
(2923392)  
(существенный)  
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(С установленным режимом ADAM)  
(2933528)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2925418)  
(средний)  
Internet Explorer 7  
(2925418)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(С установленной службой Active Directory)  
(2923392)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://go.microsoft.com/fwlink/?linkid=392066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2925418)  
(критический)  
Internet Explorer 8  
(2925418)  
(критический)  
Internet Explorer 9   
(2925418)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(С установленной службой Active Directory облегченного доступа к каталогам (AD LDS))  
(2923392)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2925418)  
(критический)  
Internet Explorer 8  
(2925418)  
(критический)  
Internet Explorer 9   
(2925418)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(С установленной службой Active Directory облегченного доступа к каталогам (AD LDS))  
(2923392)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://go.microsoft.com/fwlink/?linkid=392066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**

</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2925418)  
(средний)  
Internet Explorer 8  
(2925418)  
(средний)  
Internet Explorer 9   
(2925418)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(С установленной службой Active Directory или Active Directory облегченного доступа к каталогам (AD LDS))  
(2923392)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2925418)  
(средний)  
Internet Explorer 8  
(2925418)  
(средний)  
Internet Explorer 9   
(2925418)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(С установленной службой Active Directory или Active Directory облегченного доступа к каталогам (AD LDS))  
(2923392)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2925418)  
(средний)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://go.microsoft.com/fwlink/?linkid=392066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**

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
Нет

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2925418)  
(критический)  
Internet Explorer 9   
(2925418)  
(критический)  
Internet Explorer 10   
(2925418)  
(критический)  
Internet Explorer 11   
(2925418)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2925418)  
(критический)  
Internet Explorer 9   
(2925418)  
(критический)  
Internet Explorer 10   
(2925418)  
(критический)  
Internet Explorer 11   
(2925418)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://go.microsoft.com/fwlink/?linkid=392066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**

</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2925418)  
(средний)  
Internet Explorer 9   
(2925418)  
(средний)  
Internet Explorer 10   
(2925418)  
(средний)  
Internet Explorer 11   
(2925418)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(С установленной службой Active Directory или Active Directory облегченного доступа к каталогам (AD LDS))  
(2923392)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2925418)  
(средний)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8 и Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://go.microsoft.com/fwlink/?linkid=392066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**

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
Нет

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2925418)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2925418)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2925418)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2925418)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2012 и Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://go.microsoft.com/fwlink/?linkid=392066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**

</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2925418)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(С установленной службой Active Directory)  
(2923392)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2925418)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2929961)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(С установленной службой Active Directory)  
(2923392)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT и Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://go.microsoft.com/fwlink/?linkid=392066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2925418)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows RT  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2925418)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Вариант установки ядра сервера**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-012**](http://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](http://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](http://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](http://go.microsoft.com/fwlink/?linkid=392066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**

</td>
<td style="border:1px solid black;">
Нет

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(С установленной службой Active Directory или Active Directory облегченного доступа к каталогам (AD LDS))  
(2923392)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(С установленной службой Active Directory или Active Directory облегченного доступа к каталогам (AD LDS))  
(2923392)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(С установленной службой Active Directory или Active Directory облегченного доступа к каталогам (AD LDS))  
(2923392)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(С установленной службой Active Directory)  
(2923392)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (установка основных серверных компонентов)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (установка основных серверных компонентов)  
(2930275)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (установка основных серверных компонентов)  
(С установленной службой Active Directory)  
(2923392)  
(существенный)

</td>
</tr>
</table>
 
 

**Программное обеспечение и средства разработки Microsoft**

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Silverlight**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-014**](http://go.microsoft.com/fwlink/?linkid=392070)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**

</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 при установке на Mac  
(2932677)  
(существенный)  
Microsoft Silverlight 5 Developer Runtime при установке в Mac  
(2932677)  
(существенный)  
Microsoft Silverlight 5 при установке на всех поддерживаемых выпусках клиентских систем Microsoft Windows  
(2932677)  
(существенный)  
Microsoft Silverlight 5 Developer Runtime при установке во всех поддерживаемых выпусках клиентских систем Microsoft Windows  
(2932677)  
(существенный)  
Microsoft Silverlight 5 при установке на всех поддерживаемых выпусках серверов Microsoft Windows  
(2932677)  
(существенный)  
Microsoft Silverlight 5 Developer Runtime при установке во всех поддерживаемых выпусках серверных систем Microsoft Windows  
(2932677)  
(существенный)

</td>
</tr>
</table>
 
 

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span id="sectionToggle3"></span>
Доступно несколько ресурсов, чтобы помочь администраторам развернуть обновления для системы безопасности.

Анализатор безопасности Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений для системы безопасности и типичных ошибок в конфигурации системы безопасности.

Службы Windows Server Update Services (WSUS), Systems Management Server (SMS) и System Center Configuration Manager помогают администраторам распространять обновления для системы безопасности.

Компоненты средства оценки совместимости с обновлениями, включенные в набор средств для обеспечения совместимости приложений, облегчают тестирование и проверку совместимости обновлений Windows с установленными приложениями.

Информацию об этих и других доступных инструментах см. в статье [Инструменты обеспечения безопасности](http://technet.microsoft.com/security/cc297183). 

Благодарности
-------------

<span id="sectionToggle4"></span>
Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:

**MS14-012**

-   Пользователя lokihardt@ASRT, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0297)
-   Амол Найка (Amol Naik), сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0297)
-   Эдварда Торкингтона (Edward Torkington) из [NCC Group](https://www.nccgroup.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0297)
-   Пользователя lokihardt@ASRT, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0298)
-   Хосе А. Васкеса (Jose A. Vazquez) из Yenteasy Security Research, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0299)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0302)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0303)
-   Хой Гао (Hui Gao) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0304)
-   Чжибинь Ху (Zhibin Hu) из компании [Qihoo](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0304)
-   Тяньфан Го (Tianfang Guo) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0305)
-   Джейсона Кратцера (Jason Kratzer), сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0306)
-   Джейсона Кратцера (Jason Kratzer), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0307)
-   Пользователя lokihardt@ASRT, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0308)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0308)
-   Джейсона Кратцера (Jason Kratzer), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0308)
-   Амол Найка (Amol Naik), сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0309)
-   Скота Белла (Scott Bell) из компании [Security-Assessment.com](http://www.security-assessment.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0311)
-   Юйцзе Вэнь (Yujie Wen) из компании [Qihoo](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0311)
-   Саймона Цукербрауна (Simon Zuckerbraun), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0312)
-   Пользователя [Omair](http://krash.in/), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0313)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0314)
-   Чжибинь Ху (Zhibin Hu) из компании [Qihoo](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0314)
-   Лю Луна (Liu Long) из компании [Qihoo](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0314)
-   Анил Афейл (Anil Aphale) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0314)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0321)
-   Юйцзе Вэнь (Yujie Wen) из компании [Qihoo](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0321)
-   Чжибинь Ху (Zhibin Hu) из компании [Qihoo](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0321)
-   Лю Луна (Liu Long) из компании [Qihoo](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0321)
-   Абдула Азиза Харири (Abdul Aziz Hariri), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0321)
-   Юки Чен (Yuki Chen) из компании [Trend Micro](http://www.trendmicro.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0321)
-   Корпорацию [FireEye](http://www2.fireeye.com/) за совместную работу над устранением уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0322)
-   Лю Луна (Liu Long) из компании [Qihoo](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0322)
-   Хосе А. Васкеса (Jose A. Vazquez) из Yenteasy Security Research, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4112)

**MS14-013**

-   Анонимного исследователя, сотрудничающего с [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости DirectShow, приводящей к повреждению памяти (CVE-2014-0301)

**MS14-014**

-   [Компанию NSFOCUS Information Technology Co., Ltd.](http://en.nsfocus.com/) за сообщение об уязвимости Silverlight, делающей возможным обход функций безопасности DEP/ASLR (CVE-2014-0319)

**MS14-015**

-   Александра Чижова (Alexander Chizhov) за совместную работу по устранению уязвимости Win32k, приводящей к раскрытию информации (CVE-2014-0323)

**MS14-016**

-   Эндрю Бартлетта (Andrew Bartlett) из рабочей группы Samba и Catalyst IT за сообщение об уязвимости SAMR, связанной с обходом функций безопасности (CVE-2014-0317)
-   [Мухаммада Фейсала Накви (Muhammad Faisal Naqvi)](http://ae.linkedin.com/in/mfaisalnaqvi) из Пакистана за сообщение об уязвимости SAMR, связанной с обходом функций безопасности (CVE-2014-0317)

Прочие сведения
---------------

<span id="sectionToggle5"></span>
### Средство удаления вредоносных программ для системы Microsoft Windows

Для выпуска бюллетеня, публикуемого каждый второй вторник месяца корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки. Для внеплановых выпусков бюллетеней по безопасности обновленные версии средства удаления вредоносных программ для системы Microsoft Windows недоступны.

### Обновления, не относящиеся к безопасности и распространяемые через Центр обновления Майкрософт, Центр обновления Windows и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-сайте Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт](https://support.microsoft.com/kb/894199). Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
-   [Обновления за предыдущие месяцы для служб Windows Server Update Services](http://technet.microsoft.com/wsus/bb456965). Отображаются все новые, обновленные и повторно выпущенные обновления для продуктов Майкрософт отличных от Microsoft Windows.

### Программа Microsoft Active Protections Program (MAPP)

Чтобы повысить уровень защиты пользователей, корпорация Майкрософт предоставляет сведения об уязвимостях крупным поставщикам программного обеспечения безопасности перед ежемесячным выпуском обновлений. Эта информация необходима им для усовершенствования программного обеспечения и оборудования для защиты пользователей (антивирусных программ, сетевых систем обнаружения вторжений, а также индивидуальных систем предотвращения вторжений). Сведения о средствах защиты, предоставляемых поставщиками программного обеспечения безопасности, доступны на соответствующих веб-сайтах партнеров, перечисленных в списке партнеров [MAPP](http://go.microsoft.com/fwlink/?linkid=215201).

### Стратегии безопасности и сообщество

**Стратегии управления обновлениями**

В статье [Рекомендации по безопасности для управления обновлениями](http://go.microsoft.com/fwlink/?linkid=21168) содержатся дополнительные сведения о рекомендациях Майкрософт по установке обновлений для системы безопасности.

**Другие обновления для системы безопасности**

Другие обновления безопасности можно загрузить из следующих источников:

-   Обновления для системы безопасности доступны в [Центре загрузки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".
-   Обновления для индивидуальных пользователей доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747).
-   Обновления безопасности, предлагаемые в этом месяце в Центре обновления Windows, можно загрузить с веб-сайта Центра загрузки Майкрософт в виде файлов ISO-образа компакт-диска с выпусками обновлений безопасности. Дополнительные сведения см. в [статье 913086 базы знаний Майкрософт](https://support.microsoft.com/kb/913086).

**Сообщество ИТ-специалистов, занимающихся вопросами безопасности**

На веб-сайте [сообщества ИТ-специалистов, занимающихся вопросами безопасности](http://go.microsoft.com/fwlink/?linkid=21164), можно найти сведения о способах улучшения системы безопасности и оптимизации ИТ-инфраструктуры предприятия, а также обсудить вопросы безопасности с другими ИТ-специалистами.

### Поддержка

Подверженное уязвимости программное обеспечение, перечисленное в этом бюллетене, проверено на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).

Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617)

Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)

Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

### Редакции

-   Версия 1.0 (11 марта 2014 г.): Обзор бюллетеней опубликован.
-   Версия 1.1 (18 сентября 2014 г.): для MS14-012, в индекс использования уязвимостей добавлена оценка использования уязвимости CVE-2014-4112. Это изменение носит исключительно информационный характер.

*Время создания страницы: 2014-09-18 10:01Z-07:00.*
