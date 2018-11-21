---
TOCTitle: 'MS11-JUL'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Июль 2011 г.'
ms:assetid: 'ms11-jul'
ms:contentKeyID: 61236148
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms11-jul(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Июль 2011 г.
===============================================================

Дата публикации: 12 июля 2011 г.

**Версия:** 1.0

В этом обзоре перечислены бюллетени по безопасности, выпущенные в июле 2011 г.

После выпуска бюллетеней по безопасности за июль 2011 г. данный обзор заменит предварительное уведомление, выпущенное 7 июля 2011 г. Дополнительные сведения о службе предварительных уведомлений см. на веб-странице [Предварительное уведомление о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213) (на английском языке).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

13 июля 2011 г. в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в июльской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032487855&eventcategory=4). После наступления этой даты данная веб-трансляция будет доступна по запросу. Дополнительные сведения см. на веб-сайте [обзоров и веб-трансляций, посвященных бюллетеням Майкрософт по безопасности](http://go.microsoft.com/fwlink/?linkid=217214).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217102">MS11-053</a></td>
<td style="border:1px solid black;"><strong>Уязвимость стека Bluetooth делает возможным удаленное выполнение кода (2566220)</strong> <br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость стека Windows Bluetooth. Она делает возможным удаленное выполнение кода, если злоумышленник отправляет в уязвимую систему серию специально созданных пакетов Bluetooth. После этого злоумышленник сможет устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными правами. Этой уязвимости подвержены только те системы, которые поддерживают Bluetooth.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td style="border:1px solid black;"><strong>Уязвимости драйверов режима ядра Windows делают возможным несанкционированное получение прав (2555917)</strong> <br />
<br />
Это обновление для системы безопасности устраняет 15 обнаруженных пользователями уязвимостей в Microsoft Windows. Наиболее серьезная из этих уязвимостей делает возможным несанкционированное получение прав, если злоумышленник вошел в систему и запустил специально созданное приложение. Чтобы воспользоваться данными уязвимостями, злоумышленник должен обладать действительными учетными данными и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217465">MS11-056</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в подсистеме исполнения клиент-сервер Windows делают возможным несанкционированное получение прав (2507938) </strong><br />
<br />
Это обновление для системы безопасности устраняет пять обнаруженных пользователями уязвимостей в подсистеме исполнения клиент-сервер Microsoft Windows (CSRSS). Эти уязвимости делают возможным несанкционированное получение прав в том случае, если злоумышленник войдет в систему пользователя и запустит особым образом созданное приложение. Чтобы воспользоваться этими уязвимостями, злоумышленник должен обладать действительными учетными данными для входа и возможностью локального входа в систему.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=220276">MS11-055</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft Visio делает возможным удаленное выполнение кода (2560847) </strong><br />
<br />
Это обновление для системы безопасности устраняет опубликованную уязвимость в Microsoft Visio. Данная уязвимость делает возможным удаленное выполнение кода при условии, что пользователь откроет подлинный файл Visio, расположенный в том же сетевом каталоге, что и специально созданный файл библиотеки. Злоумышленник, воспользовавшийся этой уязвимостью, может получить те же права, что и вошедший в систему пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
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
  
Используйте эту таблицу, чтобы узнать о вероятности появления эксплойтов для выполнения произвольного кода и DoS-атаки в течение 30 дней после выпуска бюллетеня по каждому из обновлений безопасности, которые необходимо установить. Чтобы назначить приоритеты развертывания, ознакомьтесь с приведенными ниже оценками в соответствии с вашей конфигурацией. Дополнительные сведения об уровнях опасности и способах их определения см. в [индексе использования уязвимостей](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
В приведенной ниже таблице "последний выпуск программного обеспечения" обозначает соответствующее программное обеспечение, а термином "старые выпуски программного обеспечения" обозначены все прежние поддерживаемые выпуски программного обеспечения, указанные в таблице "Подвержены уязвимости" или "Не подвержены уязвимости" в этом бюллетене.
  
| Идентификатор бюллетеня                                   | Название уязвимости                                                                                                          | Код CVE                                                                          | Оценка возможности использования для выполнении кода для последнего выпуска программного обеспечения                        | Оценка возможности использования для выполнении кода для старых выпусков программного обеспечения                           | Оценка использования уязвимости типа "отказ в обслуживании" | Краткие примечания                                                                                                          |  
|-----------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|  
| [MS11-053](http://go.microsoft.com/fwlink/?linkid=217102) | Уязвимость стека Bluetooth                                                                                                   | [CVE-2011-1265](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1265) | Не подвержены уязвимости                                                                                                    | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Возможно существование нестабильного кода эксплойта        | Перманентное                                                | Эта уязвимость затрагивает только клиентские системы (поддерживаемые версии Windows Vista и Windows 7) с функцией Bluetooth |  
| [MS11-054](http://go.microsoft.com/fwlink/?linkid=220172) | Уязвимость Win32k, связанная с использованием протокола после освобождения                                                   | [CVE-2011-1874](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1874) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-054](http://go.microsoft.com/fwlink/?linkid=220172) | Уязвимость Win32k, связанная с использованием протокола после освобождения                                                   | [CVE-2011-1875](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1875) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-054](http://go.microsoft.com/fwlink/?linkid=220172) | Уязвимость Win32k, связанная с использованием протокола после освобождения                                                   | [CVE-2011-1876](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1876) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Возможно существование нестабильного кода эксплойта        | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Возможно существование нестабильного кода эксплойта        | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-054](http://go.microsoft.com/fwlink/?linkid=220172) | Уязвимость Win32k, связанная с использованием протокола после освобождения                                                   | [CVE-2011-1877](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1877) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Возможно существование нестабильного кода эксплойта        | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Возможно существование нестабильного кода эксплойта        | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-054](http://go.microsoft.com/fwlink/?linkid=220172) | Уязвимость Win32k, связанная с использованием протокола после освобождения                                                   | [CVE-2011-1878](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1878) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-054](http://go.microsoft.com/fwlink/?linkid=220172) | Уязвимость Win32k, связанная с использованием протокола после освобождения                                                   | [CVE-2011-1879](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1879) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-054](http://go.microsoft.com/fwlink/?linkid=220172) | Уязвимость Win32k, связанная с разыменованием NULL-указателя                                                                 | [CVE-2011-1880](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1880) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-054](http://go.microsoft.com/fwlink/?linkid=220172) | Уязвимость Win32k, связанная с разыменованием NULL-указателя                                                                 | [CVE-2011-1881](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1881) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-054](http://go.microsoft.com/fwlink/?linkid=220172) | Уязвимость Win32k, связанная с использованием протокола после освобождения                                                   | [CVE-2011-1882](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1882) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-054](http://go.microsoft.com/fwlink/?linkid=220172) | Уязвимость Win32k, связанная с использованием протокола после освобождения                                                   | [CVE-2011-1883](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1883) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-054](http://go.microsoft.com/fwlink/?linkid=220172) | Уязвимость Win32k, связанная с использованием протокола после освобождения                                                   | [CVE-2011-1884](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1884) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-054](http://go.microsoft.com/fwlink/?linkid=220172) | Уязвимость Win32k, связанная с разыменованием NULL-указателя                                                                 | [CVE-2011-1885](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1885) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-054](http://go.microsoft.com/fwlink/?linkid=220172) | Проверка неправильных параметров Win32k допускает уязвимость, приводящую к раскрытию информации                              | [CVE-2011-1886](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1886) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) — существование функционирующего кода эксплойта маловероятно | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) — существование функционирующего кода эксплойта маловероятно | Перманентное                                                | Эта уязвимость связана с возможностью утечки информации                                                                     |  
| [MS11-054](http://go.microsoft.com/fwlink/?linkid=220172) | Уязвимость Win32k, связанная с разыменованием NULL-указателя                                                                 | [CVE-2011-1887](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1887) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-054](http://go.microsoft.com/fwlink/?linkid=220172) | Уязвимость Win32k, связанная с разыменованием NULL-указателя                                                                 | [CVE-2011-1888](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1888) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-055](http://go.microsoft.com/fwlink/?linkid=220276) | Уязвимость, связанная с небезопасной загрузкой библиотек в Microsoft Visio                                                   | [CVE-2010-3148](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3148) | Не подвержены уязвимости                                                                                                    | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Не применимо                                                | О данной уязвимости сообщалось в открытых источниках.                                                                       |  
| [MS11-056](http://go.microsoft.com/fwlink/?linkid=217465) | Уязвимость функции AllocConsole подсистемы CSRSS, приводящая к несанкционированному получению локальных прав                 | [CVE-2011-1281](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1281) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) — существование функционирующего кода эксплойта маловероятно | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Не применимо                                                | (Нет)                                                                                                                       |  
| [MS11-056](http://go.microsoft.com/fwlink/?linkid=217465) | Уязвимость функции SrvSetConsoleLocalEUDC подсистемы CSRSS, приводящая к несанкционированному получению локальных прав       | [CVE-2011-1282](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1282) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) — существование функционирующего кода эксплойта маловероятно | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-056](http://go.microsoft.com/fwlink/?linkid=217465) | Уязвимость функции SrvSetConsoleNumberOfCommand подсистемы CSRSS, приводящая к несанкционированному получению локальных прав | [CVE-2011-1283](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1283) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-056](http://go.microsoft.com/fwlink/?linkid=217465) | Уязвимость функции SrvWriteConsoleOutput подсистемы CSRSS, приводящая к несанкционированному получению локальных прав        | [CVE-2011-1284](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1284) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Перманентное                                                | (Нет)                                                                                                                       |  
| [MS11-056](http://go.microsoft.com/fwlink/?linkid=217465) | Уязвимость функции SrvWriteConsoleOutputString подсистемы CSRSS, приводящая к несанкционированному получению локальных прав  | [CVE-2011-1870](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1870) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) — существование функционирующего кода эксплойта маловероятно | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Возможно существование стабильного кода эксплойта          | Перманентное                                                | (Нет)                                                                                                                       |
  
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
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="4">
ОС Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://go.microsoft.com/fwlink/?linkid=217102)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://go.microsoft.com/fwlink/?linkid=220172)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://go.microsoft.com/fwlink/?linkid=217465)
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
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=d7a47370-f415-46ea-9a82-a943f743c8b6)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=425c705e-94f2-4fa6-9df2-dc71897215fa)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=db89d88f-d0d4-4ed6-8589-bf27557c0304)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c389fa20-677e-49b6-af44-781e5522d08b)  
(существенный)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://go.microsoft.com/fwlink/?linkid=217102)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://go.microsoft.com/fwlink/?linkid=220172)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://go.microsoft.com/fwlink/?linkid=217465)
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
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7a26a437-a705-4d48-8389-50f159a39891)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=dff4c67a-8c8b-4d7d-84c7-57429becf0ff)  
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
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=95393f89-0b05-4243-95ed-17bcdad24bfb)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1615a995-9a04-440a-ae52-5917738f0ecb)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 для систем с процессорами Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3b094bdb-4150-44f2-a638-afd5f41b00a3)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 для систем с процессорами Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a81c011d-eeea-4383-9efb-df70515ab357)  
(существенный)
</td>
</tr>
<tr>
<th colspan="4">
Windows Vista;
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://go.microsoft.com/fwlink/?linkid=217102)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://go.microsoft.com/fwlink/?linkid=220172)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://go.microsoft.com/fwlink/?linkid=217465)
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
Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=6bff74ac-45f3-4585-92da-316921b458fa)<sup>[1]</sup>
(KB2561109)  
(критический)  
[Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a1e5aa7d-5f38-4ce2-9575-4b4cb7520160)  
(KB2532531)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c1fe1e53-34d5-497e-8ba2-50caa8dc1158)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a5e192af-dae5-47ef-a9d0-f761a8caa974)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=849d2694-c8b3-4670-8203-912661bccabf)<sup>[1]</sup>
(KB2561109)  
(критический)  
[Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4287eeb4-ab29-4727-83f2-260d838b44d4)  
(KB2532531)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7bc0a285-cc32-4c6b-abee-d92130d459b7)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=1007f5d3-9be1-4f03-a3f0-12ddb555653c)  
(существенный)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://go.microsoft.com/fwlink/?linkid=217102)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://go.microsoft.com/fwlink/?linkid=220172)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://go.microsoft.com/fwlink/?linkid=217465)
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
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b88d0471-4427-4835-9446-db71116481f0)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=36e3dbaf-36f5-4c74-8f11-ecbef46f58e1)\*  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем и Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных (x64) систем и Windows Server 2008 для 64-разрядных (x64) систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d3df6184-3e3c-4949-a1ee-293ec68f8149)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных (x64) систем и Windows Server 2008 для 64-разрядных (x64) систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b43d2ab5-e281-4c6b-bb37-1f1b5d86ac82)\*  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=9e021d69-7f0c-457f-af86-07e760d8f421)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems и Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b70209f2-1c51-45af-b3c4-3473aebcdb35)  
(существенный)
</td>
</tr>
<tr>
<th colspan="4">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://go.microsoft.com/fwlink/?linkid=217102)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://go.microsoft.com/fwlink/?linkid=220172)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://go.microsoft.com/fwlink/?linkid=217465)
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
Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=7f811b75-c3ff-411a-aaa9-126dce34cc01)  
(KB2532531)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=41db1b2f-f862-43bb-89bc-4b97737e5cb9)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для 32-разрядных систем и Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=ac3b435c-8caf-40cc-8f13-b52261b3b9e6)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=90b2da71-18f9-46ee-9e3d-b08620ca06aa)  
(KB2532531)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=211abdc6-40c7-4bfc-8c2d-be72981f311e)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows 7 для компьютеров на базе x64-процессоров и Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=64e5f889-fa46-4884-9b22-3ba4e2fba1b9)  
(существенный)
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-053**](http://go.microsoft.com/fwlink/?linkid=217102)
</td>
<td style="border:1px solid black;">
[**MS11-054**](http://go.microsoft.com/fwlink/?linkid=220172)
</td>
<td style="border:1px solid black;">
[**MS11-056**](http://go.microsoft.com/fwlink/?linkid=217465)
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
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=4f54e498-3825-407d-a036-1900a65d34f1)\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 для компьютеров на базе x64-процессоров и Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=b99a40cf-8a31-43d9-bd0b-a458a533068b)\*  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=e7ae39e8-1154-4a13-8598-29d4a6358762)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems и Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=784efc20-3a41-42ab-b48d-51fd59d71523)  
(существенный)
</td>
</tr>
</table>
 
**Примечание для Windows Server 2008 и Windows Server 2008 R2**

**\*Системы, при развертывании которых устанавливалось только ядро сервера, подвержены уязвимости.** Это обновление (с одинаковым уровнем серьезности) применяется к указанным выше поддерживаемым выпускам Windows Server 2008 или Windows Server 2008 R2 независимо от наличия установленных основных компонентов сервера. Дополнительные сведения об этом варианте установки см. в статьях TechNet, [Управление ядром сервера: установка](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) (на английском языке) и [Обслуживание установки ядра сервера](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (на английском языке). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008 и Windows Server 2008 R2; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Примечание для MS11-053**

<sup>[1]</sup>Windows Vista с пакетом обновления 1 (SP1) подвержена уязвимости, только если установлен пакет дополнительных компонентов Windows Vista для беспроводных устройств (Windows Vista Feature Pack for Wireless).

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
Наборы приложений и компоненты Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS11-055**](http://go.microsoft.com/fwlink/?linkid=220276)
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
Microsoft Visio 2003 с пакетом обновления 3 (SP3)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=1c7b2a5b-4aa6-4006-90bf-89f8b2b7becd)  
(KB2493523)  
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

Дополнительные сведения о развертывании данного обновления безопасности с помощью служб WSUS см. на веб-сайте [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx).

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

Чтобы повысить уровень защиты пользователей, корпорация Майкрософт предоставляет сведения об уязвимостях крупным поставщикам программного обеспечения безопасности перед ежемесячным выпуском обновлений. Эта информация необходима им для усовершенствования программного обеспечения и оборудования для защиты пользователей (антивирусных программ, сетевых систем обнаружения вторжений, а также индивидуальных систем предотвращения вторжений). Сведения о новых средствах защиты, предоставляемых поставщиками программного обеспечения безопасности, доступны на соответствующих веб-сайтах партнеров, перечисленных в списке партнеров [MAPP](http://go.microsoft.com/fwlink/?linkid=215201).

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

-   Тарджея Мандта (Tarjei Mandt) из компании [Norman](http://www.norman.com) за сообщение о 14 уязвимостях, описанных в бюллетене MS11-054
-   Лиянь Иня (Liang Yin), проф. Сихань Квинга (Sihan Qing) и Вейпинга Вена (Weiping Wen) и Худзень Джоу (Husheng Zhou) из [отдела информационной безопасности Пекинского университета](http://www.ss.pku.edu.cn/en/) за сообщение об уязвимости, описанной в бюллетене MS11-054
-   Мэтью Юрчика ("j00ru") (Matthew 'j00ru' Jurczyk) из [Hispasec](http://www.hispasec.com/)[Virustotal](http://www.virustotal.com/) за сообщение о пяти уязвимостях, описанных в бюллетене MS11-056

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Пользователи из США и Канады могут обратиться в службу [поддержки по вопросам безопасности](http://go.microsoft.com/fwlink/?linkid=21131) или позвонить по телефону 1-866-PCSAFETY. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Дополнительные сведения о вариантах поддержки см. на веб-сайте [справки и поддержки корпорации Майкрософт](http://support.microsoft.com/).
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-сайт международной справки и поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (12 июля 2011 г.): Обзор бюллетеней опубликован.

*Built at 2014-04-18T01:50:00Z-07:00*
