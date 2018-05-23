---
TOCTitle: 'MS13-JUN'
Title: Обзор бюллетеней по безопасности Майкрософт за июнь 2013 года
ms:assetid: 'ms13-jun'
ms:contentKeyID: 61236173
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms13-jun(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности Майкрософт за июнь 2013 года
=============================================================

Дата публикации: 11 июня 2013 г.

**Версия:** 1.0

В этот обзор включены бюллетени по безопасности, выпущенные в июне 2013 года.

После выпуска бюллетеней по безопасности за июнь 2013 года данный обзор заменит предварительное уведомление, выпущенное 6 июня 2013 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

12 июня 2013 года в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в июньской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538733&culture=en-us). После наступления этой даты данная веб-трансляция будет доступна [по запросу](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538733&culture=en-us).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299498">MS13-047</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности браузера Internet Explorer (2838727)<br />
<br />
</strong>Это обновление для системы безопасности устраняет 19 обнаруженных пользователями уязвимостей в браузере Internet Explorer. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь просмотрит особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся наиболее серьезными из данных уязвимостей, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301748">MS13-048</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в ядре Windows может привести к раскрытию информации (2839229)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну обнаруженную пользователями уязвимость в Windows. Данная уязвимость может привести к раскрытию информации, если злоумышленник войдет в систему и запустит особым образом созданное приложение или убедит это сделать локального пользователя, вошедшего в систему. Чтобы воспользоваться этой уязвимостью, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему. Данная уязвимость не позволяет злоумышленнику выполнить код или напрямую повысить уровень своих пользовательских прав, но может быть использована для получения сведений, которые понадобятся для дальнейших атак на уязвимую систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Раскрытие информации</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=301749">MS13-049</a></td>
<td style="border:1px solid black;"><strong>Уязвимость драйвера режима ядра делает возможной атаку типа &quot;отказ в обслуживании&quot; (2845690)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным отказ в обслуживании, если злоумышленник отправляет серверу особым образом созданные пакеты. Стандартные параметры конфигурации брандмауэра позволяют защитить сеть от атак из-за пределов корпоративной среды.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299243">MS13-050</a></td>
<td style="border:1px solid black;"><strong>Уязвимость компонентов</strong> <strong>диспетчера печати Windows делает возможным несанкционированное повышение привилегий (2839894)<br />
<br />
</strong>Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Эта уязвимость делает возможным несанкционированное повышение привилегий, если прошедший проверку подлинности злоумышленник удаляет подключение принтера. Чтобы воспользоваться этой уязвимостью, злоумышленник должен иметь действительные учетные данные и возможность входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Повышение уровня прав доступа</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296303">MS13-051</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Office делает возможным удаленное выполнение кода (2839571)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Office. Эта уязвимость делает возможным удаленное выполнение кода, если пользователь откроет особым образом созданный документ Office в уязвимой версии Microsoft Office либо предварительно просматривает или открывает особым образом созданное сообщение электронной почты в Outlook при использовании Microsoft Word в качестве программы чтения электронной почты. Злоумышленник, успешно воспользовавшийся данной уязвимостью, может получить те же права, которыми обладает текущий пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
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
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости сгруппированы по идентификаторам бюллетеней и затем по кодам CVE. Включены только уязвимости, которым в бюллетенях присвоен уровень серьезности "критический" или "существенный".
  
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать о вероятности появления эксплойтов для выполнения произвольного кода и DoS-атаки в течение 30 дней после выпуска бюллетеня по каждому из обновлений безопасности, которые необходимо установить. Чтобы назначить приоритеты развертывания, ознакомьтесь с приведенными ниже оценками в соответствии с вашей конфигурацией. Дополнительные сведения об уровнях опасности и способах их определения см. в [индексе использования уязвимостей](http://technet.microsoft.com/security/cc998259).
  
В приведенной ниже таблице "последний выпуск программного обеспечения" обозначает соответствующее программное обеспечение, а термином "старые выпуски программного обеспечения" обозначены все прежние поддерживаемые выпуски программного обеспечения, указанные в таблице "Подвержены уязвимости" или "Не подвержены уязвимости" в этом бюллетене.
  
| Идентификатор бюллетеня                                   | Название уязвимости                                                    | Код CVE                                                                          | Оценка возможности использования уязвимостей для последнего выпуска программного обеспечения           | Оценка возможности использования уязвимостей для более старых выпусков программного обеспечения        | Оценка использования уязвимости типа "отказ в обслуживании" | Краткие примечания                                                                          |  
|-----------------------------------------------------------|------------------------------------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|---------------------------------------------------------------------------------------------|  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3110](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3110) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                                                       |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3111](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3111) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                                                       |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3112](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3112) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) — код эксплойта создать сложно          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                                                       |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3113](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3113) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                                                       |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3114](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3114) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) — код эксплойта создать сложно          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                                                       |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3116](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3116) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                                                       |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3117](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3117) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                                                       |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3118](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3118) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не подвержены уязвимости                                                                               | Не применимо                                                | (Нет)                                                                                       |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3119](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3119) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                                                       |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3120](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3120) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не подвержены уязвимости                                                                               | Не применимо                                                | (Нет)                                                                                       |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3121](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3121) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                                                       |  
| MS13-047                                                  | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3122](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3122) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                                                       |  
| MS13-047                                                  | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3123](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3123) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                                                       |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3124](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3124) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                                                       |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3125](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3125) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не подвержены уязвимости                                                                               | Не применимо                                                | (Нет)                                                                                       |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3139](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3139) | Не применимо                                                                                           | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | Мера обеспечения многоуровневой защиты последних версий программного обеспечения.           |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3141](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3141) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                                                       |  
| [MS13-047](http://go.microsoft.com/fwlink/?linkid=299498) | Уязвимость Internet Explorer, приводящая к повреждению памяти          | [CVE-2013-3142](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3142) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) — код эксплойта создать сложно          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | (Нет)                                                                                       |  
| [MS13-048](http://go.microsoft.com/fwlink/?linkid=301748) | Уязвимость, приводящая к раскрытию информации ядра                     | [CVE-2013-3136](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3136) | [3](http://technet.microsoft.com/security/cc998259) — существование кода эксплойта маловероятно        | [3](http://technet.microsoft.com/security/cc998259) — существование кода эксплойта маловероятно        | Перманентное                                                | Это уязвимость, делающая возможным раскрытие информации.                                    |  
| [MS13-049](http://go.microsoft.com/fwlink/?linkid=301749) | Уязвимость в TCP/IP, связанная с переполнением целочисленного значения | [CVE-2013-3138](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3138) | [3](http://technet.microsoft.com/security/cc998259) — существование кода эксплойта маловероятно        | [3](http://technet.microsoft.com/security/cc998259) — существование кода эксплойта маловероятно        | Перманентное                                                | Эта уязвимость делает возможной атаку типа "отказ в обслуживании".                          |  
| [MS13-050](http://go.microsoft.com/fwlink/?linkid=299243) | Уязвимость диспетчера печати                                           | [CVE-2013-1339](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1339) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Перманентное                                                | (Нет)                                                                                       |  
| [MS13-051](http://go.microsoft.com/fwlink/?linkid=296303) | Уязвимость Office, приводящая к переполнению буфера                    | [CVE-2013-1331](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1331) | Не подвержены уязвимости                                                                               | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование кода эксплойта | Не применимо                                                | Корпорации Майкрософт известно о направленных атаках с целью использования этой уязвимости. |
  
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
<th colspan="5">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий** **уровень опасности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**
</td>
<td style="border:1px solid black;">
**Нет**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2838727)  
(критический)  
Internet Explorer 7  
(2838727)  
(критический)  
Internet Explorer 8  
(2838727)  
(критический)
</td>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)  
(2839229)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2838727)  
(критический)  
Internet Explorer 7  
(2838727)  
(критический)  
Internet Explorer 8  
(2838727)  
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
</tr>
<tr>
<th colspan="5">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**
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
(2838727)  
(средний)  
Internet Explorer 7  
(2838727)  
(средний)  
Internet Explorer 8  
(2838727)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2839229)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Не применимо
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2838727)  
(средний)  
Internet Explorer 7  
(2838727)  
(средний)  
Internet Explorer 8  
(2838727)  
(средний)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2838727)  
(средний)  
Internet Explorer 7  
(2838727)  
(средний)
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
</tr>
<tr>
<th colspan="5">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(критический)  
Internet Explorer 8  
(2838727)  
(критический)  
Internet Explorer 9  
(2838727)  
(критический)
</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2839229)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2845690)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2839894)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(критический)  
Internet Explorer 8  
(2838727)  
(критический)  
Internet Explorer 9  
(2838727)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2845690)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2839894)  
(существенный)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий** **уровень опасности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(средний)  
Internet Explorer 8  
(2838727)  
(средний)  
Internet Explorer 9  
(2838727)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2839229)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2845690)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2839894)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(средний)  
Internet Explorer 8  
(2838727)  
(средний)  
Internet Explorer 9  
(2838727)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2845690)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2839894)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2838727)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2845690)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2839894)  
(существенный)
</td>
</tr>
<tr>
<th colspan="5">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
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
(2838727)  
(критический)  
Internet Explorer 9  
(2838727)  
(критический)  
Internet Explorer 10  
(2838727)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2839229)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2845690)  
(средний)
</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2839894)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2838727)  
(критический)  
Internet Explorer 9  
(2838727)  
(критический)  
Internet Explorer 10  
(2838727)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2845690)  
(средний)
</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2839894)  
(существенный)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий** **уровень опасности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Нет**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
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
(2838727)  
(средний)  
Internet Explorer 9  
(2838727)  
(средний)  
Internet Explorer 10  
(2838727)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2845690)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2839894)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2838727)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2845690)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2839894)  
(существенный)
</td>
</tr>
<tr>
<th colspan="5">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
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
(2838727)  
(критический)
</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2839229)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2845690)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2839894)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2838727)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2845690)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2839894)  
(существенный)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr class="alternateRow">
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
(2838727)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2845690)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2839894)  
(существенный)
</td>
</tr>
<tr>
<th colspan="5">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
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
**Нет**
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
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2838727)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Windows RT  
(2845690)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows RT  
(2839894)  
(существенный)
</td>
</tr>
<tr>
<th colspan="5">
Вариант установки ядра сервера
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-047**](http://go.microsoft.com/fwlink/?linkid=299498)
</td>
<td style="border:1px solid black;">
[**MS13-048**](http://go.microsoft.com/fwlink/?linkid=301748)
</td>
<td style="border:1px solid black;">
[**MS13-049**](http://go.microsoft.com/fwlink/?linkid=301749)
</td>
<td style="border:1px solid black;">
[**MS13-050**](http://go.microsoft.com/fwlink/?linkid=299243)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
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
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2839229)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2845690)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2839894)  
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
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2845690)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2839894)  
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
(2845690)  
(средний)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2839894)  
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
Не применимо
</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(2845690)  
(существенный)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(2839894)  
(существенный)
</td>
</tr>
</table>
 

#### Пакеты приложений и программные продукты Microsoft Office

 
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Программное обеспечение Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS13-051**](http://go.microsoft.com/fwlink/?linkid=296303)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень серьезности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Microsoft Office 2003 с пакетом обновления 3 (SP3)  
(2817421)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office для Mac 2011
</td>
<td style="border:1px solid black;">
Microsoft Office для Mac 2011  
(2848689)  
(существенный)
</td>
</tr>
</table>
 

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
**В центре безопасности**

Управление программным обеспечением и обновлениями для системы безопасности для установки на серверы, настольные и переносные компьютеры организации. Дополнительные сведения см. на веб-сайте [Центра управления обновлениями TechNet](http://go.microsoft.com/fwlink/?linkid=69903). [Центр безопасности TechNet](http://go.microsoft.com/fwlink/?linkid=21171) предоставляет дополнительные сведения о безопасности в продуктах Майкрософт. Также эта информация доступна на веб-сайте [Центра безопасности Майкрософт](http://go.microsoft.com/fwlink/?linkid=85102) в разделе "Обновления для системы безопасности".

Обновления для системы безопасности доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747) и [Центре обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130). Обновления для системы безопасности также доступны на веб-сайте [Центра загрузки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".

Пользователи пакета Microsoft Office для Mac могут следить за установкой последних версий программного обеспечения Майкрософт при помощи приложения Microsoft AutoUpdate для Mac. Дополнительные сведения об использовании приложения Microsoft AutoUpdate для Mac см. в статье [Автоматическая проверка наличия обновлений для программного обеспечения](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

Наконец, обновления для системы безопасности можно загрузить из [каталога Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=96155). Он обеспечивает возможность поиска содержимого (в том числе обновлений для системы безопасности, драйверов и пакетов обновления), которое предоставляется через Центр обновления Windows и Центр обновления Майкрософт. При поиске по номеру бюллетеня по безопасности (например, "MS13-001") можно добавить в корзину все необходимые обновления (в том числе несколько языковых версий одного обновления) и загрузить их в указанную папку. Дополнительные сведения см. на веб-сайте каталога Центра обновления Майкрософт в разделе [вопросов и ответов](http://go.microsoft.com/fwlink/?linkid=97900).

**Руководство по диагностике и развертыванию**

Корпорация Майкрософт предоставляет руководство по диагностике и развертыванию обновлений для системы безопасности. В этом руководстве содержатся рекомендации и сведения, позволяющие ИТ-специалистам оптимальнее использовать различные средства для диагностики и развертывания обновлений для системы безопасности. Дополнительные сведения см. в [статье 961747 базы знаний Майкрософт](http://support.microsoft.com/kb/961747).

**Анализатор безопасности Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений безопасности и стандартных ошибок в конфигурации системы безопасности. Дополнительные сведения об анализаторе безопасности MBSA см. на веб-сайте [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Службы Windows Server Update Services**

Службы Windows Server Update Services (WSUS) позволяют администраторам быстрым и надежным образом развертывать последние критические обновления и обновления для систем безопасности операционных систем Microsoft Windows 2000 и более поздних версий, пакетов Office XP и более поздних версий, серверов Exchange Server 2003 и SQL Server 2000 в системах Microsoft Windows 2000 и более поздних версий.

Дополнительные сведения о развертывании данного обновления безопасности с помощью служб WSUS см. на веб-странице [Windows Server Update Services](http://technet.microsoft.com/wsus/default).

**SystemCenter Configuration Manager**

Управление обновлениями программного обеспечения с помощью диспетчера конфигураций System Center Configuration Manager упрощает сложную задачу получения обновлений и управления обновлениями в ИТ-системах всего предприятия. Используя диспетчер конфигураций System Center Configuration Manager, ИТ-администраторы могут получать обновления продуктов Майкрософт на различные устройства, включая настольные и мобильные компьютеры, серверы и мобильные устройства.

Автоматическая оценка уязвимостей в диспетчере конфигураций System Center Configuration Manager определяет необходимость в обновлениях и сообщает о рекомендуемых действиях. Управление обновлениями программного обеспечения в диспетчере конфигураций System Center Configuration Manager встроено в Microsoft Windows Software Update Services (WSUS), проверенную временем инфраструктуру обновления, хорошо знакомую ИТ-администраторам во всем мире. Подробнее о диспетчере конфигураций System Center Configuration Manager см. в статье [Технические ресурсы по System Center](http://technet.microsoft.com/systemcenter/bb980621).

**Systems Management Server 2003**

Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет хорошо сконфигурированное решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей.

**Примечание.** Основная поддержка System Management Server 2003 закончена 12 января 2010 г. Подробнее о жизненном цикле продуктов см. на веб-странице [Жизненный цикл поддержки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742). Следующий выпуск сервера SMS (System Center Configuration Manager), уже доступен для загрузки; см. предыдущий раздел **System Center Configuration Manager**.

Подробнее о том, как администраторы могут использовать SMS 2003 для развертывания обновлений системы безопасности, см. [Сценарии и процедуры для Microsoft Systems Management Server 2003: Распространение программного обеспечения и управление исправлениями](http://www.microsoft.com/downloads/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f). Дополнительные сведения о сервере SMS см. на веб-странице [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/systemcenter/bb545936).

**Примечание.** Для предоставления широкой поддержки при определении необходимости применения и развертывания обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используется средство Microsoft Baseline Security Analyzer. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. на веб-странице [Развертывание обновлений программного обеспечения с помощью функции распространения программ сервера SMS](http://go.microsoft.com/fwlink/?linkid=33341) (на английском языке). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакета [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)).

**Средство оценки совместимости обновлений и набор средств для обеспечения совместимости приложений**

Часто обновления записываются в одни те же файлы, а для запуска приложений требуется настроить параметры реестра. Это приводит к возникновению несовместимостей и увеличивает время, затрачиваемое на развертывание обновлений для системы безопасности. Облегчить тестирование и проверку обновлений Windows для установленных приложений можно с помощью [компонентов оценки совместимости обновлений](http://technet.microsoft.com/library/cc749197), входящих в состав [набора средств для обеспечения совместимости приложений](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971).

Набор средств для обеспечения совместимости приложений содержит необходимые средства и документацию для выявления проблем совместимости приложений и уменьшения степени воздействия этих проблем перед развертыванием системы Windows Vista, обновлений из Центра обновления Windows, обновлений с веб-сайта безопасности Майкрософт или новой версии проводника.

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

**MS13-047**

-   Скота Белла (Scott Bell) из компании [Security-Assessment.com](http://www.security-assessment.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3110)
-   Пользователя SkyLined, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3111)
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3112)
-   Ивана Фратрича (Ivan Fratric) и Бена Хокса (Ben Hawkes) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3113)
-   Ивана Фратрича (Ivan Fratric) и Бена Хокса (Ben Hawkes) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3114)
-   Ивана Фратрича (Ivan Fratric) и Бена Хокса (Ben Hawkes) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3116)
-   Ивана Фратрича (Ivan Fratric) и Бена Хокса (Ben Hawkes) из [отдела безопасности Google](http://www.google.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3117)
-   Пользователя [Omair](http://krash.in/), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3118)
-   Стивена Фьюэра (Stephen Fewer) из [Harmony Security](http://www.harmonysecurity.com), работающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3119)
-   Пользователя SkyLined, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3120)
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3121)
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3122)
-   Пользователя [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com), сотрудничающего с компании [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3123)
-   Пользователя [Omair](http://krash.in/), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3124)
-   Амол Найка (Amol Naik), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3124)
-   Пользователя [Omair](http://krash.in/), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3125)
-   Амол Найка (Amol Naik), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3125)
-   Пользователя [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com), сотрудничающего с компании [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, связанной с отладкой сценариев (CVE-2013-3126)
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3141)
-   Тоан Фам Вана (Toan Pham Van), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2013-3142)

**MS13-048**

-   Мэтью Юрчика "j00ru" ([Matthew 'j00ru' Jurczyk](http://j00ru.vexillium.org/)) из [Google Inc](http://www.google.com/) за сообщение об уязвимости, приводящей к раскрытию информации ядра (CVE-2013-3136)

**MS13-051**

-   Эндрю Лайонса (Andrew Lyons) и Нила Мета (Neel Mehta) из корпорации [Google](http://www.google.com/) за сообщение об уязвимости Office, приводящей к переполнению буфера (CVE-2013-1331)

#### Поддержка

-   Подверженное уязвимости программное обеспечение, перечисленное в этом бюллетене, проверено на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (11 июня 2013 г.) Обзор бюллетеней опубликован.
-   

*Built at 2014-04-18T01:50:00Z-07:00*
