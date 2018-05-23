---
TOCTitle: 'MS13-NOV'
Title: 'Обзор бюллетеней по безопасности Майкрософт за ноябрь 2013 года.'
ms:assetid: 'ms13-nov'
ms:contentKeyID: 61236176
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms13-nov(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности Майкрософт за ноябрь 2013 года.
================================================================

Дата публикации: 12 ноября 2013 г.

**Версия:** 1.0

В этом обзоре перечислены бюллетени по безопасности за ноябрь 2013 года.

После выпуска бюллетеней за ноябрь 2013 года этот обзор заменит предварительное уведомление, выпущенное 7 ноября 2013 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

13 ноября 2013 года в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в ноябрьской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557383&culture=en-us).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел **Прочие сведения**.

### Сведения о бюллетене

#### Аннотации

В приведенной ниже таблице описаны бюллетени по безопасности за этот месяц в порядке, соответствующем уровню опасности.

Сведения об уязвимом программном обеспечении см. в следующем разделе, **Подвержены уязвимости**.

 
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (2888505)</strong><br />
<br />
Это обновление для системы безопасности устраняет 10 обнаруженных пользователями уязвимостей в браузере Internet Explorer. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь просмотрит особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся наиболее серьезными из данных уязвимостей, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325390">MS13-089</a></td>
<td style="border:1px solid black;"><strong>Уязвимость интерфейса графических устройств Windows (GDI) делает возможным удаленное выполнение кода (2876331)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость делает возможным удаленное выполнение кода, если пользователи просматривают или открывают специально созданный файл Windows Write в WordPad. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329834">MS13-090</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление системы безопасности для битов аннулирования ActiveX (2900986)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость, случаи использования которой зафиксированы на настоящий момент. Данная уязвимость существует в элементе ActiveX класса InformationCardSigninHelper. Эта уязвимость делает возможным удаленное выполнение кода, если пользователи откроют специально созданную веб-страницу в браузере Internet Explorer, в котором разрешено создание экземпляров данного элемента ActiveX. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325392">MS13-091</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft Office делают возможным удаленное выполнение кода (2885093)</strong><br />
<br />
Это обновление для системы безопасности устраняет три обнаруженных пользователями уязвимости<strong></strong>в Microsoft Windows. Эти уязвимости делают возможным удаленное выполнение кода, если открыть специально созданный файл документа WordPerfect в уязвимой версии Microsoft Office. Злоумышленник, успешно воспользовавшийся наиболее серьезными из данных уязвимостей, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324692">MS13-092</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Hyper-V делает возможным несанкционированное получение прав (2893986)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость делает возможным несанкционированное получение прав, если злоумышленник передаст в гипервызове гипервизору специально созданный параметр функции из запущенной виртуальной машины. Эта уязвимость также делает возможным отказ в обслуживании хоста Hyper-V, если злоумышленник передаст в гипервызове гипервизору специально созданный параметр функции из запущенной виртуальной машины.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325391">MS13-093</a></td>
<td style="border:1px solid black;"><strong>Уязвимость драйвера вспомогательной функции Windows может привести к раскрытию информации (2875783)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость может привести к раскрытию информации, если злоумышленник войдет в уязвимую систему как локальный пользователь и выполнит в системе приложение, специально созданное, чтобы злоумышленник мог получить информацию из учетной записи с более высокими привилегиями. Чтобы воспользоваться этой уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Раскрытие информации</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324873">MS13-094</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Outlook может привести к раскрытию информации (2894514)</strong><br />
<br />
Это обновление для системы безопасности устраняет опубликованную уязвимость в Microsoft Outlook. Эта уязвимость может привести к раскрытию информации, если пользователи открывают или предварительно просматривают специально созданное сообщение электронной почты с помощью уязвимой версии Microsoft Outlook. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может извлечь системную информацию, такую как IP-адрес и открытые TCP-порты, из целевой системы и других систем в общей с ней сети.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Раскрытие информации</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320632">MS13-095</a></td>
<td style="border:1px solid black;"><strong>Уязвимость</strong> <strong>цифровых подписей делает возможной атаку типа &quot;отказ в обслуживании&quot; (2868626)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Данная уязвимость делает возможным отказ в обслуживании, когда уязвимая веб-служба обрабатывает специально созданный сертификат X.509.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Индекс использования уязвимостей  
--------------------------------
  
<span></span>
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости сгруппированы по идентификаторам бюллетеней и затем по кодам CVE. Включены только уязвимости, которым в бюллетенях присвоен уровень серьезности "критический" или "существенный".
  
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать о вероятности появления эксплойтов для выполнения произвольного кода и DoS-атаки в течение 30 дней после выпуска бюллетеня по каждому из обновлений безопасности, которые необходимо установить. Чтобы назначить приоритеты развертывания, ознакомьтесь с приведенными ниже оценками в соответствии с вашей конфигурацией. Дополнительные сведения об уровнях опасности и способах их определения см. в [индексе использования уязвимостей](http://technet.microsoft.com/security/cc998259).
  
В приведенной ниже таблице "последний выпуск программного обеспечения" обозначает соответствующее программное обеспечение, а термином "старые выпуски программного обеспечения" обозначены все прежние поддерживаемые выпуски программного обеспечения, указанные в таблице "Подвержены уязвимости" или "Не подвержены уязвимости" в этом бюллетене.

 
<table style="border:1px solid black;">
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3871">CVE-2013-3871</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к раскрытию информации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3908">CVE-2013-3908</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к раскрытию информации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3909">CVE-2013-3909</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3910">CVE-2013-3910</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3911">CVE-2013-3911</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3912">CVE-2013-3912</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3914">CVE-2013-3914</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3915">CVE-2013-3915</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3916">CVE-2013-3916</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3917">CVE-2013-3917</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325390">MS13-089</a></td>
<td style="border:1px solid black;">Уязвимость интерфейса графических устройств, связанная с переполнением целочисленного значения</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3940">CVE-2013-3940</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329834">MS13-090</a></td>
<td style="border:1px solid black;">Уязвимость класса InformationCardSigninHelper</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3918">CVE-2013-3918</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Корпорации Майкрософт известно об ограниченных направленных атаках с целью использования этой уязвимости.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325392">MS13-091</a></td>
<td style="border:1px solid black;">Уязвимость формата файла WPD, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0082">CVE-2013-0082</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325392">MS13-091</a></td>
<td style="border:1px solid black;">Уязвимость Word, связанная с переполнением буфера стека</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1324">CVE-2013-1324</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325392">MS13-091</a></td>
<td style="border:1px solid black;">Уязвимость Word, связанная с перезаписью кучи</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1325">CVE-2013-1325</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324692">MS13-092</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с повреждением адресов</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3898">CVE-2013-3898</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325391">MS13-093</a></td>
<td style="border:1px solid black;">Уязвимость драйвера вспомогательной функции, приводящая к раскрытию информации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3887">CVE-2013-3887</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=324873">MS13-094</a></td>
<td style="border:1px solid black;">Уязвимость S/MIME AIA</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3905">CVE-2013-3905</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.<br />
<br />
О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320632">MS13-095</a></td>
<td style="border:1px solid black;">Уязвимость цифровых подписей</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3869">CVE-2013-3869</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Временный</td>
<td style="border:1px solid black;">Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.</td>
</tr>
</tbody>
</table>
  
Подвержены уязвимости  
---------------------
  
<span></span>
В приведенных ниже таблицах перечислены бюллетени в порядке важности категорий программного обеспечения и уровней опасности.
  
**Как пользоваться этими таблицами?**
  
Обращайтесь к этим таблицам, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и узнайте, имеются ли для них обновления для системы безопасности. Если программное обеспечение или компонент содержится в списке, для него также указан уровень важности соответствующего обновления программного обеспечения.
  
**Примечание.** Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификатора бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.
  
#### Компоненты операционных систем Windows

 
<table style="border:1px solid black;">
<tr>
<th colspan="7">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2888505)  
(критический)  
Internet Explorer 7  
(2888505)  
(критический)  
Internet Explorer 8  
(2888505)  
(критический)
</td>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)  
(2900986)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)  
(2868626)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2888505)  
(критический)  
Internet Explorer 7  
(2888505)  
(критический)  
Internet Explorer 8  
(2888505)  
(критический)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2900986)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2875783)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2868626)  
(существенный)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2888505)  
(существенный)  
Internet Explorer 7  
(2888505)  
(существенный)  
Internet Explorer 8  
(2888505)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2900986)  
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
(2868626)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2888505)  
(существенный)  
Internet Explorer 7  
(2888505)  
(существенный)  
Internet Explorer 8  
(2888505)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2900986)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2875783)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2868626)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2888505)  
(существенный)  
Internet Explorer 7  
(2888505)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2900986)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2875783)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2868626)  
(существенный)
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
(критический)  
Internet Explorer 8  
(2888505)  
(критический)  
Internet Explorer 9  
(2888505)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2900986)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2868626)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
(критический)  
Internet Explorer 8  
(2888505)  
(критический)  
Internet Explorer 9  
(2888505)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2900986)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2875783)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2868626)  
(существенный)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
(существенный)  
Internet Explorer 8  
(2888505)  
(существенный)  
Internet Explorer 9  
(2888505)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2900986)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2868626)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
(существенный)  
Internet Explorer 8  
(2888505)  
(существенный)  
Internet Explorer 9  
(2888505)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2900986)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2875783)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2868626)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2900986)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2875783)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2868626)  
(существенный)
</td>
</tr>
<tr>
<th colspan="7">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2888505)  
(критический)  
Internet Explorer 9  
(2888505)  
(критический)  
Internet Explorer 10  
(2888505)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2900986)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2868626)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2888505)  
(критический)  
Internet Explorer 9  
(2888505)  
(критический)  
Internet Explorer 10  
(2888505)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2900986)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2875783)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2868626)  
(существенный)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2888505)  
(существенный)  
Internet Explorer 9  
(2888505)  
(существенный)  
Internet Explorer 10  
(2888505)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2900986)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2875783)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2868626)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2888505)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2900986)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2875783)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2868626)  
(существенный)
</td>
</tr>
<tr>
<th colspan="7">
Windows 8 и Windows 8.1
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2888505)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2900986)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2868626)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2888505)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2900986)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(Только выпуски Pro и Enterprise)  
(2893986)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2875783)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2868626)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2888505)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(2900986)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(2868626)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2888505)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(2900986)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(2868626)  
(существенный)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2012 и Windows Server 2012 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2888505)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2900986)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Только выпуски Standard и Datacenter, а также Hyper-V Server 2012)  
(2893986)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2875783)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2868626)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2888505)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2900986)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2868626)  
(существенный)
</td>
</tr>
<tr>
<th colspan="7">
Windows RT и Windows RT 8.1
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
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
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2888505)  
(критический)
</td>
<td style="border:1px solid black;">
Windows RT  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows RT  
(2900986)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows RT  
(2868626)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2888505)  
(критический)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2900986)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2868626)  
(существенный)
</td>
</tr>
<tr>
<th colspan="7">
Вариант установки ядра сервера
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-088**](http://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](http://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](http://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](http://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](http://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](http://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий** **уровень опасности**
</td>
<td style="border:1px solid black;">
**Нет**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)[](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2876331)  
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
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2868626)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2875783)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2868626)  
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
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2875783)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2868626)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(2876331)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(2893986)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(2875783)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(2868626)  
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
Windows Server 2012 R2 (установка основных серверных компонентов)  
(2876331)  
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
Windows Server 2012 R2 (установка основных серверных компонентов)  
(2868626)  
(существенный)
</td>
</tr>
</table>
 

#### Пакеты приложений и программные продукты Microsoft Office

 
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Office 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-091**](http://go.microsoft.com/fwlink/?linkid=325392)
</td>
<td style="border:1px solid black;">
[**MS13-094**](http://go.microsoft.com/fwlink/?linkid=324873)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
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
Microsoft Office 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Microsoft Office 2003 с пакетом обновления 3 (SP3)  
(конвертеры форматов файлов)  
(2760494)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2007
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-091**](http://go.microsoft.com/fwlink/?linkid=325392)
</td>
<td style="border:1px solid black;">
[**MS13-094**](http://go.microsoft.com/fwlink/?linkid=324873)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень серьезности**
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
Microsoft Office 2007 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 с пакетом обновления 3 (SP3)  
(конвертеры форматов файлов)  
(2760415)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2007 с пакетом обновления 3 (SP3)  
(2825644)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-091**](http://go.microsoft.com/fwlink/?linkid=325392)
</td>
<td style="border:1px solid black;">
[**MS13-094**](http://go.microsoft.com/fwlink/?linkid=324873)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
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
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(конвертеры форматов файлов)  
(2553284)  
(существенный)  
Microsoft Office 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(средства проверки правописания)  
(2760781)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 с пакетом обновления 1 (SP1) (32-разрядные версии)  
(2837597)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 2 (SP2) (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 2 (SP2) (32-разрядные версии)  
(конвертеры форматов файлов)  
(2553284)  
(уровень опасности не определен)  
Microsoft Office 2010 с пакетом обновления 2 (SP2) (32-разрядные версии)  
(средства проверки правописания)  
(2760781)  
(уровень опасности не определен)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 с пакетом обновления 2 (SP2) (32-разрядные версии)  
(2837597)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(конвертеры форматов файлов)  
(2553284)  
(существенный)  
Microsoft Office 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(средства проверки правописания)  
(2760781)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 с пакетом обновления 1 (SP1) (64-разрядные версии)  
(2837597)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 2 (SP2) (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 с пакетом обновления 2 (SP2) (64-разрядные версии)  
(конвертеры форматов файлов)  
(2553284)  
(уровень опасности не определен)  
Microsoft Office 2010 с пакетом обновления 2 (SP2) (64-разрядные версии)  
(средства проверки правописания)  
(2760781)  
(уровень опасности не определен)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 с пакетом обновления 2 (SP2) (64-разрядные версии)  
(2837597)  
(существенный)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-091**](http://go.microsoft.com/fwlink/?linkid=325392)
</td>
<td style="border:1px solid black;">
[**MS13-094**](http://go.microsoft.com/fwlink/?linkid=324873)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
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
Microsoft Office 2013 (32-разрядные версии)
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (32-разрядные версии)  
(конвертеры форматов файлов)  
(2768005)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2013 (32-разрядные версии)  
(2837618)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2013 (64-разрядные версии)
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (64-разрядные версии)  
(конвертеры форматов файлов)  
(2768005)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2013 (64-разрядные версии)  
(2837618)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(конвертеры форматов файлов)  
(2768005)  
(существенный)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2013 RT  
(2837618)  
(существенный)
</td>
</tr>
</table>
 

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
Доступно несколько ресурсов, чтобы помочь администраторам развернуть обновления для системы безопасности.

-   Анализатор безопасности Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений для системы безопасности и типичных ошибок в конфигурации системы безопасности.
-   Службы Windows Server Update Services (WSUS), Systems Management Server (SMS) и System Center Configuration Manager помогают администраторам распространять обновления для системы безопасности.
-   Компоненты средства оценки совместимости с обновлениями, включенные в набор средств для обеспечения совместимости приложений, облегчают тестирование и проверку совместимости обновлений Windows с установленными приложениями.

Информацию об этих и других доступных инструментах см. в статье [Инструменты обеспечения безопасности](http://technet.microsoft.com/security/cc297183).

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Для выпуска бюллетеня, публикуемого каждый второй вторник месяца корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки. Для внеплановых выпусков бюллетеней по безопасности обновленные версии средства удаления вредоносных программ для системы Microsoft Windows недоступны.

#### Обновления, не относящиеся к безопасности и распространяемые через Центр обновления Майкрософт, Центр обновления Windows и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-сайте Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт](http://support.microsoft.com/kb/894199). Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
-   [Обновления за предыдущие месяцы для служб Windows Server Update Services](http://technet.microsoft.com/wsus/bb456965). Отображаются все новые, обновленные и повторно выпущенные обновления для продуктов Майкрософт отличных от Microsoft Windows.

#### Программа Microsoft Active Protections Program (MAPP)

Чтобы повысить уровень защиты пользователей, корпорация Майкрософт предоставляет сведения об уязвимостях крупным поставщикам программного обеспечения безопасности перед ежемесячным выпуском обновлений. Эта информация необходима им для усовершенствования программного обеспечения и оборудования для защиты пользователей (антивирусных программ, сетевых систем обнаружения вторжений, а также индивидуальных систем предотвращения вторжений). Сведения о средствах защиты, предоставляемых поставщиками программного обеспечения безопасности, доступны на соответствующих веб-сайтах партнеров, перечисленных в списке партнеров [MAPP](http://go.microsoft.com/fwlink/?linkid=215201).

#### Стратегии безопасности и сообщество

**Стратегии управления обновлениями**

В статье [Рекомендации по безопасности для управления обновлениями](http://go.microsoft.com/fwlink/?linkid=21168) содержатся дополнительные сведения о рекомендациях Майкрософт по установке обновлений для системы безопасности.

**Другие обновления для системы безопасности**

Другие обновления безопасности можно загрузить из следующих источников:

-   Обновления для системы безопасности доступны в [Центре загрузки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".
-   Обновления для индивидуальных пользователей доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747).
-   Обновления безопасности, предлагаемые в этом месяце в Центре обновления Windows, можно загрузить с веб-сайта Центра загрузки Майкрософт в виде файлов ISO-образа компакт-диска с выпусками обновлений безопасности. Дополнительные сведения см. в [статье 913086 базы знаний Майкрософт](http://support.microsoft.com/kb/913086).

**Сообщество ИТ-специалистов, занимающихся вопросами безопасности**

На веб-сайте [сообщества ИТ-специалистов, занимающихся вопросами безопасности](http://go.microsoft.com/fwlink/?linkid=21164), можно найти сведения о способах улучшения системы безопасности и оптимизации ИТ-инфраструктуры предприятия, а также обсудить вопросы безопасности с другими ИТ-специалистами.

#### Благодарности

Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:

**MS13-088**

-   Саймона Цукербрауна (Simon Zuckerbraun), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3871)
-   Масато Кинугаву (Masato Kinugawa) за сообщение об уязвимости Internet Explorer, приводящей к раскрытию информации (CVE-2013-3908)
-   Сергея Маркова (Sergey Markov) за сообщение об уязвимости Internet Explorer, приводящей к раскрытию информации (CVE-2013-3909)
-   Питера 'corelanc0d3r' Ван Экуте (Peter 'corelanc0d3r' Van Eeckhoutte) из компании [Corelan](http://www.corelangcv.com/), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3910)
-   Стивена Фьюэра (Stephen Fewer) из [Harmony Security](http://www.harmonysecurity.com/), работающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3911)
-   Пользователя lokihardt@ASRT, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3912)
-   Анонимного исследователя, сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3914)
-   Бо Ку (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3915)
-   Бо Ку (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3916)
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3917)
-   Бо Ку (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3917)

**MS13-089**

-   Хоссейна Лотфи (Hossein Lotfi) из компании [Secunia Research](http://secunia.com/) за сообщение об уязвимости интерфейса графических устройств, связанной с переполнением целочисленного значения (CVE-2013-3940)

**MS13-090**

-   Пользователя ucq и Дайки Фукумори (Daiki Fukumori) из [Cyber Defense Institute, Inc.](http://www.cyberdefense.jp/) за сообщение об уязвимости класса InformationCardSigninHelper (CVE-2013-3918)
-   Компанию [iSIGHT Partners](http://www.isightpartners.com/) за совместную работу по устранению уязвимости класса InformationCardSigninHelper (CVE-2013-3918)
-   Дана Кейсельдена (Dan Caselden) и Чена Ксайобо (Xiaobo Chen) из компании [FireEye](http://www.fireeye.com/) за совместную работу по устранению уязвимости класса InformationCardSigninHelper (CVE-2013-3918)

**MS13-091**

-   Компанию Merliton за сообщение об уязвимости формата файла WPD, приводящей к повреждению памяти (CVE-2013-0082)
-   Уилла Дормана (Will Dormann) из [CERT/CC](http://www.cert.org/) за сообщение об уязвимости Word, связанной с переполнением буфера стека (CVE-2013-1324)
-   Уилла Дормана (Will Dormann) из [CERT/CC](http://www.cert.org/) за сообщение об уязвимости Word, связанной с перезаписью кучи (CVE-2013-1325)

**MS13-092**

-   Компании Thinktecture ([www.thinktecture.com](http://www.thinktecture.com)) и ERNW ([www.ernw.de](http://www.ernw.de); Felix Wilhelm), действующие в интересах Bundesamt für Sicherheit in der Informationstechnik (BSI, Федеральное ведомство Германии по информационной безопасности), за сообщение об уязвимости, связанной с повреждением адресов (CVE-2013-3898)

**MS13-094**

-   Александра Клинка (Alexander Klink) из компании [n.runs professionals GmbH](https://www.nruns.com/) за сообщение об уязвимости S/MIME AIA (CVE-2013-3905)

**MS13-095**

-   Джеймса Форшо (James Forshaw) из компании [Context Information Security](http://www.contextis.com/) за сообщение об уязвимости цифровых подписей (CVE-2013-3869)

#### Поддержка

-   Подверженное уязвимости программное обеспечение, перечисленное в этом бюллетене, проверено на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (12 ноября 2013 г.): Обзор бюллетеней опубликован.

*Built at 2014-04-18T01:50:00Z-07:00*
