---
TOCTitle: 'MS14-JUL'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за июль 2014 года'
ms:assetid: 'ms14-jul'
ms:contentKeyID: 62554668
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms14-jul(v=Security.10)'
---

Обзор бюллетеней по безопасности (Майкрософт) за июль 2014 года
===============================================================

Дата публикации: 8 июля 2014 г. | Обновлено: 29 июля 2014 г.

**Версия:** 1.1

В этот обзор включены бюллетени по безопасности, выпущенные в июле 2014 года.

После выпуска бюллетеней за июль 2014 года этот обзор заменит предварительное уведомление, выпущенное 3 июля 2014 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

9 июля 2014 г. в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Ежемесячную веб-трансляцию и ссылки на дополнительные веб-трансляции бюллетеня по безопасности см. в статье [Веб-трансляция бюллетеня по безопасности (Майкрософт)](http://technet.microsoft.com/security/dn756352).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (2975687)<br />
<br />
</strong>Это обновление для системы безопасности устраняет одну опубликованную и 24 обнаруженных пользователями уязвимости в Internet Explorer. Наиболее серьезная из этих уязвимостей делает возможным удаленное выполнение кода, если пользователь просматривает особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402326">MS14-038</a></td>
<td style="border:1px solid black;"><strong>Уязвимость журнала Windows делает возможным удаленное выполнение кода (2975689)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость делает возможным удаленное выполнение кода, если пользователь откроет специально созданный файл журнала. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402327">MS14-039</a></td>
<td style="border:1px solid black;"><strong>Уязвимость экранной клавиатуры делает возможным несанкционированное повышение привилегий (2975685)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость делает возможным несанкционированное повышение привилегий, если злоумышленник воспользуется уязвимостью в процессе с низким уровнем целостности, чтобы запустить экранную клавиатуру (OSK) и передаст целевой системе специально созданную программу.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402328">MS14-040</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в драйвере вспомогательной функции (AFD) делает возможным несанкционированное повышение привилегий (2975684)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным несанкционированное повышение привилегий, если злоумышленник войдет в систему и запустит специально созданное приложение. Чтобы воспользоваться этой уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402330">MS14-041</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в DirectShow делает возможным несанкционированное повышение привилегий (2975681)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость позволяет несанкционированно повысить привилегии, если злоумышленник сначала воспользуется другой уязвимостью в процессе с низким уровнем целостности, а затем с помощью этой уязвимости выполнит специально созданный код в контексте пользователя, вошедшего в систему. По умолчанию современный иммерсивный просмотр веб-страниц в Windows 8 и Windows 8.1 осуществляется в расширенном защищенном режиме (EPM). Например, пользователи браузера Internet Explorer 11 с поддержкой сенсорного управления на современных планшетных ПК Windows по умолчанию используют расширенный защищенный режим. В расширенном защищенном режиме используются расширенные средства защиты безопасности, которые снижают опасность использования этой уязвимости в 64-разрядных системах.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402462">MS14-042</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Service Bus делает возможной атаку типа &quot;отказ в обслуживании&quot; (2972621)<br />
</strong><br />
Это обновление для системы безопасности устраняет одну опубликованную уязвимость в Microsoft Service Bus для Windows Server. Эта уязвимость делает возможным отказ в обслуживании, если удаленный злоумышленник, прошедший проверку подлинности, создает и выполняет программу, которая отправляет целевой системе последовательность специально созданных сообщений Advanced Message Queuing Protocol (AMQP). Microsoft Service Bus для Windows Server не поставляется с операционными системами Microsoft. Чтобы система стала уязвимой, необходимо загрузить, установить и настроить Microsoft Service Bus, а затем предоставить остальным пользователям общий доступ к сведениям о конфигурации этого компонента (сертификат фермы).</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Средний</a> <br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Перезагрузка не требуется</td>
<td style="border:1px solid black;">Серверное программное обеспечение Майкрософт</td>
</tr>
</tbody>
</table>
  
 
  
Индекс использования уязвимостей  
--------------------------------
  
<span id="sectionToggle1"></span>
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости сгруппированы по идентификаторам бюллетеней и затем по кодам CVE. Включены только уязвимости, которым в бюллетенях присвоен уровень серьезности "критический" или "существенный".
  
**Как пользоваться этой таблицей?**
  
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
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Идентификатор бюллетеня</strong></td>
<td style="border:1px solid black;"><strong>Название уязвимости</strong></td>
<td style="border:1px solid black;"><strong>Код CVE</strong></td>
<td style="border:1px solid black;"><strong>Оценка возможности использования уязвимостей для последнего выпуска программного обеспечения</strong></td>
<td style="border:1px solid black;"><strong>Оценка возможности использования уязвимостей для более старых выпусков программного обеспечения</strong></td>
<td style="border:1px solid black;"><strong>Оценка использования уязвимости типа &quot;отказ в обслуживании&quot;</strong></td>
<td style="border:1px solid black;"><strong>Краткие примечания</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1763">CVE-2014-1763</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1765">CVE-2014-1765</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2785">CVE-2014-2785</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2786">CVE-2014-2786</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2787">CVE-2014-2787</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2788">CVE-2014-2788</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2789">CVE-2014-2789</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2790">CVE-2014-2790</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2791">CVE-2014-2791</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2792">CVE-2014-2792</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2794">CVE-2014-2794</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2795">CVE-2014-2795</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2797">CVE-2014-2797</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2798">CVE-2014-2798</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2800">CVE-2014-2800</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2801">CVE-2014-2801</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2802">CVE-2014-2802</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2803">CVE-2014-2803</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2804">CVE-2014-2804</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2806">CVE-2014-2806</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2807">CVE-2014-2807</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2809">CVE-2014-2809</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2813">CVE-2014-2813</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4066">CVE-2014-4066</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402326">MS14-038</a></td>
<td style="border:1px solid black;">Уязвимость журнала Windows, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1824">CVE-2014-1824</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402327">MS14-039</a></td>
<td style="border:1px solid black;">Уязвимость экранной клавиатуры, приводящая к несанкционированному повышению привилегий</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2781">CVE-2014-2781</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402328">MS14-040</a></td>
<td style="border:1px solid black;">Уязвимость драйвера вспомогательной функции, приводящая к несанкционированному получению прав</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1767">CVE-2014-1767</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402330">MS14-041</a></td>
<td style="border:1px solid black;">Уязвимость подсистемы DirectShow, приводящая к несанкционированному повышению привилегий</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2780">CVE-2014-2780</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
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
  
### Компоненты операционных систем Windows

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
**Нет**

</td>
<td style="border:1px solid black;">
**Нет**

</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**Нет**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2962872)  
(средний)  
Internet Explorer 7  
(2962872)  
(средний)  
Internet Explorer 8  
(2962872)  
(средний)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2962872)  
(средний)  
Internet Explorer 7  
(2962872)  
(средний)  
Internet Explorer 8  
(2962872)  
(средний)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2962872)  
(средний)  
Internet Explorer 7  
(2962872)  
(средний)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
(2962872)  
(критический)  
Internet Explorer 8  
(2962872)  
(критический)  
Internet Explorer 9  
(2962872)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2971850)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2972280)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2962872)  
(критический)  
Internet Explorer 8  
(2962872)  
(критический)  
Internet Explorer 9  
(2962872)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2971850)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2972280)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
(2962872)  
(средний)  
Internet Explorer 8  
(2962872)  
(средний)  
Internet Explorer 9  
(2962872)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2971850)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2972280)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2962872)  
(средний)  
Internet Explorer 8  
(2962872)  
(средний)  
Internet Explorer 9  
(2962872)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2971850)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2972280)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2962872)  
(средний)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2962872)  
(критический)  
Internet Explorer 9  
(2962872)  
(критический)  
Internet Explorer 10  
(2962872)  
(критический)  
Internet Explorer 11  
(2962872)  
(критический)  
Internet Explorer 11  
(2963952)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2971850)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2972280)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2962872)  
(критический)  
Internet Explorer 9  
(2962872)  
(критический)  
Internet Explorer 10  
(2962872)  
(критический)  
Internet Explorer 11  
(2962872)  
(критический)  
Internet Explorer 11  
(2963952)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2971850)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2972280)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
(2962872)  
(средний)  
Internet Explorer 9  
(2962872)  
(средний)  
Internet Explorer 10  
(2962872)  
(средний)  
Internet Explorer 11  
(2962872)  
(средний)  
Internet Explorer 11  
(2963952)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2971850)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2972280)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2962872)  
(средний)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 и Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2962872)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2971850)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2972280)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2962872)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2971850)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2972280)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2962872)  
(критический)  
Internet Explorer 11  
(2963952)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(2971850)  
(критический)  
Windows 8.1 для 32-разрядных систем  
(2974286)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(2973201)  
(существенный)  
Windows 8.1 для 32-разрядных систем  
(2973906)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(2961072)  
(существенный)  
Windows 8.1 для 32-разрядных систем  
(2973408)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(2972280)  
(существенный)  
Windows 8.1 для 32-разрядных систем  
(2973932)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2962872)  
(критический)  
Internet Explorer 11  
(2963952)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(2971850)  
(критический)  
Windows 8.1 для 64-разрядных систем  
(2974286)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(2973201)  
(существенный)  
Windows 8.1 для 64-разрядных систем  
(2973906)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(2961072)  
(существенный)  
Windows 8.1 для 64-разрядных систем  
(2973408)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(2972280)  
(существенный)  
Windows 8.1 для 64-разрядных систем  
(2973932)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 и Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
(2962872)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2971850)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2972280)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2962872)  
(средний)  
Internet Explorer 11  
(2963952)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2971850)  
(критический)  
Windows Server 2012 R2  
(2974286)  
(критический)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2973201)  
(существенный)  
Windows Server 2012 R2  
(2973906)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2961072)  
(существенный)  
Windows Server 2012 R2  
(2973408)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2972280)  
(существенный)  
Windows Server 2012 R2  
(2973932)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT и Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
<td style="border:1px solid black;">
**Нет**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2962872)  
(критический)

</td>
<td style="border:1px solid black;">
Windows RT  
(2971850)  
(критический)

</td>
<td style="border:1px solid black;">
Windows RT  
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows RT  
(2961072)  
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
(2962872)  
(критический)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2971850)  
(критический)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Вариант установки ядра сервера**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**

</td>
<td style="border:1px solid black;">
**Нет**

</td>
<td style="border:1px solid black;">
**Нет**

</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**Нет**

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
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

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
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

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
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

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
(2973201)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(2961072)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

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
(2973201)  
(существенный)  
Windows Server 2012 R2 (установка основных серверных компонентов)  
(2973906)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (установка основных серверных компонентов)  
(2961072)  
(существенный)  
Windows Server 2012 R2 (установка основных серверных компонентов)  
(2973408)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
</table>
 
 

### Программное обеспечение Windows Server

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Server Bus для Windows Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**

</td>
<td style="border:1px solid black;">
[**MS14-042**](http://go.microsoft.com/fwlink/?linkid=402462)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**

</td>
<td style="border:1px solid black;" colspan="2">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Service Bus для Windows Server

</td>
<td style="border:1px solid black;" colspan="2">
Microsoft Service Bus 1.1 при установке в Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1)  
(2972621)  
(средний)  
Microsoft Service Bus 1.1 при установке в Windows Server 2012  
(2972621)  
(средний)  
Microsoft Service Bus 1.1 при установке в Windows Server 2012 R2  
(2972621)  
(средний)

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

**MS14-037**

-   Пользователя [VUPEN](http://www.vupen.com/), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1763)
-   [Андреаса Шмидта (Andreas Schmidt)](https://technet.microsoft.com/ru-RU/mailto:andreas.schmidt@siberas.de), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1765)
-   Пользователя 0016EECD9D7159A949DAD3BC17E0A939, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1765)
-   Пользователя 91fba4fa08fe776e7369ab4d96db6578, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-1765)
-   [Эрика Лоуренса (Eric Lawrence)](https://twitter.com/ericlaw) за сообщение об уязвимости, связанной с обходом функций безопасности на основе сертификатов высокой надежности (CVE-2014-2783)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2785)
-   Лю Луна (Liu Long) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2785)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2786)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2787)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2788)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2789)
-   Юйцзе Вэнь (Yujie Wen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2790)
-   Лю Луна (Liu Long) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2790)
-   Артура Геркиса (Arthur Gerkis), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2791)
-   Абдул Азиза Харири (Abdul Aziz Hariri), Мэтта Молинио (Matt Molinyawe) и Джазиеля Спелмана (Jasiel Spelman), сотрудничающих с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2792)
-   ZhaoWei компании [KnownSec](http://www.knownsec.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2794)
-   Хой Гао (Hui Gao) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2795)
-   Ройса Лу (Royce Lu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2797)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2798)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2800)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2801)
-   Юки Чен (Yuki Chen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2802)
-   Пользователя Sky, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2802)
-   [Чен Жанга (Chen Zhang) (demi6od)](https://github.com/demi6od) из [отдела безопасности NSFOCUS](http://www.nsfocus.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2802)
-   Амол Найка (Amol Naik), сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2803)
-   Пользователя Garage4Hackers, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2803)
-   Юки Чен (Yuki Chen) из компании [Qihoo 360](http://www.360.cn/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2803)
-   Пользователя exp-sky из [отдела безопасности NSFOCUS](http://www.nsfocus.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2804)
-   [Чен Жанга (Chen Zhang) (demi6od)](https://github.com/demi6od) из [отдела безопасности NSFOCUS](http://www.nsfocus.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2806)
-   Хосе А. Васкеса (José A. Vázquez) из Yenteasy Security Research, сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2807)
-   Пользователя [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2809)
-   Абдул Азиза Харири (Abdul Aziz Hariri), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-2813)
-   Бо Цюй (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-4066)

     

**MS14-038**

-   Пользователя [Hamburgers.maccoy@gmail.com](mailto:hamburgers.maccoy@gmail.com) за сообщение об уязвимости журнала Windows, делающей возможным удаленное выполнение кода (CVE-2014-1824)

     

**MS14-039**

-   Пользователя [lokihardt@asrt](https://technet.microsoft.com/ru-RU/mailto:lokihardt@asrt), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости экранной клавиатуры, приводящей к несанкционированному повышению привилегий (CVE-2014-2781)

     

**MS14-040**

-   [Себастьяна Апельта (Sebastian Apelt)](https://technet.microsoft.com/ru-RU/mailto:sebastian.apelt@siberas.de), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости драйвера вспомогательной функции, приводящей к несанкционированному повышению привилегий (CVE-2014-1767)

     

**MS14-041**

-   Компанию [VUPEN](http://www.vupen.com/), сотрудничающую с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/) за сообщение об уязвимости DirectShow, приводящей к несанкционированному повышению привилегий (CVE-2014-2780)

     

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

-   Версия 1.0 (8 июля 2014 г.): Обзор бюллетеней опубликован.
-   Версия 1.1 (29 июля 2014 г.). Для MS14-037, в Индекс использования уязвимостей добавлена оценка использования уязвимости CVE-2014-4066. Это изменение носит исключительно информационный характер.

*Время создания страницы: 2014-08-06 16:51Z-07:00.*
