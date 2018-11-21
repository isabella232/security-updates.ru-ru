---
TOCTitle: 'MS14-FEB'
Title: Обзор бюллетеней по безопасности Майкрософт за февраль 2014 года
ms:assetid: 'ms14-feb'
ms:contentKeyID: 61598065
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms14-feb(v=Security.10)'
---

Обзор бюллетеней по безопасности Майкрософт за февраль 2014 года
================================================================

Обзор бюллетеней по безопасности Майкрософт за февраль 2014 года
----------------------------------------------------------------

Дата публикации: 11 февраля 2014 г. | Обновлено: 13 февраля 2014 г.

**Версия:** 1.2

В этом обзоре перечислены бюллетени по безопасности, выпущенные в феврале 2014 года.

После выпуска бюллетеней за февраль 2014 года этот обзор заменит предварительное уведомление, выпущенное 10 февраля 2014 года. Дополнительные сведения о службе предварительных уведомлений см. на веб-сайте [службы предварительного уведомления о бюллетенях по безопасности (Майкрософт)](http://go.microsoft.com/fwlink/?linkid=217213).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

12 февраля 2014 года в 11:00 по тихоокеанскому времени (США и Канада) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь для участия [в февральской веб-трансляции, посвященной бюллетеням по безопасности](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032572879&culture=en-us).

Корпорация Майкрософт также предоставляет сведения, которые помогают клиентам отличить обновления для системы безопасности от других обновлений, не связанных с безопасностью, если эти обновления выходят в один и тот же день. См. раздел Прочие сведения.

Аннотации
---------

<span id="sectionToggle0"></span>
В приведенной ниже таблице описаны бюллетени по безопасности за этот месяц в порядке, соответствующем уровню опасности.

Сведения об уязвимом программном обеспечении см. в следующем разделе, Подвержены уязвимости.

 
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Идентификатор бюллетеня</strong></td>
<td style="border:1px solid black;"><strong>Название бюллетеня и аннотация</strong></td>
<td style="border:1px solid black;"><strong>Максимальный уровень серьезности и воздействие уязвимости</strong></td>
<td style="border:1px solid black;"><strong>Необходимость перезагрузки</strong></td>
<td style="border:1px solid black;"><strong>Подвержены уязвимости</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Накопительное обновление для системы безопасности браузера Internet Explorer (2909921)<br />
<br />
Это обновление для системы безопасности устраняет одну опубликованную и 23 обнаруженных пользователями уязвимости в Internet Explorer. Наиболее серьезные из этих уязвимостей делают возможным удаленное выполнение кода, если пользователь просмотрит особым образом созданную веб-страницу в браузере Internet Explorer. Злоумышленник, успешно воспользовавшийся наиболее серьезными из данных уязвимостей, может получить такие же права, что и у локального пользователя. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=391023">MS14-011</a></td>
<td style="border:1px solid black;">Уязвимость в обработчике сценариев VBScript делает возможным удаленное выполнение кода (2928390)<br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в обработчике сценариев VBScript в Microsoft Windows. Данная уязвимость делает возможным удаленное выполнение кода при посещении пользователем особым образом созданного веб-сайта. Злоумышленник не может заставить пользователей посетить свой веб-сайт. Вместо этого злоумышленник должен будет убедить пользователей выполнить некоторое действие, обычно приглашая их перейти по соответствующей ссылке, ведущей на этот веб-сайт, в сообщении электронной почты или программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386447">MS14-007</a></td>
<td style="border:1px solid black;">Уязвимость в Direct2D делает возможным удаленное выполнение кода (2912390)<br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Windows. Она делает возможным удаленное выполнение кода, если пользователь открывает специально созданную веб-страницу в браузере Internet Explorer. Злоумышленник не может заставить пользователей просмотреть специально созданное содержимое. Вместо этого злоумышленнику придется убедить пользователей совершить какое-либо действие: например, перейти по ссылке на веб-сайт в сообщении электронной почты или программы обмена мгновенными сообщениями или открыть вложение сообщения электронной почты.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390218">MS14-008</a></td>
<td style="border:1px solid black;">Уязвимость в Microsoft Forefront Protection для Exchange делает возможным удаленное выполнение кода (2927022)<br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Forefront. Данная уязвимость делает возможным удаленное выполнение кода в случае проверки специально созданного сообщения электронной почты.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a> <br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Программное обеспечение корпорации Майкрософт по безопасности</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386454">MS14-009</a></td>
<td style="border:1px solid black;">Уязвимости в .NET Framework делают возможным несанкционированное повышение привилегий (2916607)<br />
<br />
Это обновление для системы безопасности устраняет две опубликованные уязвимости и одну обнаруженную пользователями уязвимость в Microsoft .NET Framework. Самая серьезная уязвимость делает возможным несанкционированное повышение привилегий, если пользователи посещают специально созданный веб-сайт или веб-сайт со специально созданным веб-содержимым. Однако в любом случае злоумышленник не может заставить пользователей посетить такие веб-сайты. Вместо этого злоумышленник должен склонить пользователей к посещению зараженного веб-сайта, как правило, убеждая их щелкнуть ссылку в сообщении электронной почты или программы обмена мгновенными сообщениями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Несанкционированное повышение привилегий</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=391022">MS14-005</a></td>
<td style="border:1px solid black;">Уязвимость в MSXML может привести к раскрытию информации (2916036)<br />
<br />
Это обновление для системы безопасности устраняет опубликованную уязвимость в компоненте MSXML, входящем в состав Microsoft Windows. Она делает возможной утечку информации, если пользователь просматривает специально созданную веб-страницу в браузере Internet Explorer. Злоумышленник не может заставить пользователей просмотреть специально созданное содержимое. Вместо этого злоумышленнику придется убедить пользователей совершить какое-либо действие: например, перейти по ссылке на веб-сайт в сообщении электронной почты или программы обмена мгновенными сообщениями или открыть вложение сообщения электронной почты.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Раскрытие информации</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386450">MS14-006</a></td>
<td style="border:1px solid black;">Уязвимость протокола IPv6 делает возможной атаку типа &quot;отказ в обслуживании&quot; (2904659)<br />
<br />
Это обновление для системы безопасности устраняет опубликованную уязвимость в Microsoft Windows. Эта уязвимость делает возможным отказ в обслуживании, если злоумышленник отправляет уязвимой системе большое количество специально созданных пакетов IPv6. Чтобы использовать данную уязвимость, система злоумышленника должно принадлежать к той же подсети, что и целевая система.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a> <br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=391022">MS14-005</a></td>
<td style="border:1px solid black;">Уязвимость MSXML, приводящая к раскрытию информации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0266">CVE-2014-0266</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.<br />
<br />
О данной уязвимости сообщалось в открытых источниках.<br />
<br />
Корпорации Майкрософт известно о направленных атаках с целью использования этой уязвимости.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386450">MS14-006</a></td>
<td style="border:1px solid black;">Уязвимость протокола TCP/IP версии 6 (IPv6), делающая возможной атаку типа &quot;отказ в обслуживании&quot;</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0254">CVE-2014-0254</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.<br />
<br />
О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386447">MS14-007</a></td>
<td style="border:1px solid black;">Уязвимость компонента Microsoft Graphics, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0263">CVE-2014-0263</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390218">MS14-008</a></td>
<td style="border:1px solid black;">Уязвимость, делающая возможным удаленное выполнение кода</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0294">CVE-2014-0294</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386454">MS14-009</a></td>
<td style="border:1px solid black;">Уязвимость запросов POST, делающая возможной атаку типа &quot;отказ в обслуживании&quot;</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0253">CVE-2014-0253</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Перманентное</td>
<td style="border:1px solid black;">Эта уязвимость делает возможной атаку типа &quot;отказ в обслуживании&quot;.<br />
<br />
О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386454">MS14-009</a></td>
<td style="border:1px solid black;">Уязвимость, связанная с обходом типов</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0257">CVE-2014-0257</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=386454">MS14-009</a></td>
<td style="border:1px solid black;">Уязвимость VSAVB7RT ASLR</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0295">CVE-2014-0295</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, связанная с обходом функций безопасности.<br />
<br />
О данной уязвимости сообщалось в открытых источниках.<br />
<br />
Корпорации Майкрософт известно об ограниченных направленных атаках с целью использования этой уязвимости.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0267">CVE-2014-0267</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">О данной уязвимости сообщалось в открытых источниках.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к несанкционированному повышению привилегий</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0268">CVE-2014-0268</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0269">CVE-2014-0269</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0270">CVE-2014-0270</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0271">CVE-2014-0271</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0272">CVE-2014-0272</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0273">CVE-2014-0273</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> — код эксплойта создать сложно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0274">CVE-2014-0274</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0275">CVE-2014-0275</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0276">CVE-2014-0276</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0277">CVE-2014-0277</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0278">CVE-2014-0278</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0279">CVE-2014-0279</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0280">CVE-2014-0280</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0281">CVE-2014-0281</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0283">CVE-2014-0283</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0284">CVE-2014-0284</a></td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0285">CVE-2014-0285</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0286">CVE-2014-0286</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0287">CVE-2014-0287</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0288">CVE-2014-0288</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0289">CVE-2014-0289</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0290">CVE-2014-0290</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> — возможно существование кода эксплойта</td>
<td style="border:1px solid black;">Не подвержены уязвимости</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">(Нет)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=390977">MS14-010</a></td>
<td style="border:1px solid black;">Уязвимость Internet Explorer, приводящая к междоменному раскрытию информации</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0293">CVE-2014-0293</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> — существование кода эксплойта маловероятно</td>
<td style="border:1px solid black;">Не применимо</td>
<td style="border:1px solid black;">Это уязвимость, делающая возможным раскрытие информации.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=391023">MS14-011</a></td>
<td style="border:1px solid black;">Уязвимость VBScript, приводящая к повреждению памяти</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0271">CVE-2014-0271</a></td>
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
  
Как пользоваться этими таблицами?
  
Обращайтесь к этим таблицам, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и узнайте, имеются ли для них обновления для системы безопасности. Если программное обеспечение или компонент содержится в списке, для него также указан уровень важности соответствующего обновления программного обеспечения.
  
Примечание. Для устранения одной уязвимости может потребоваться установить несколько обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификатора бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.
  
### Компоненты операционных систем Windows

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows XP**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности

</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
Нет

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
Нет

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2909921)  
(критический)  
Internet Explorer 7   
(2909921)  
(критический)  
Internet Explorer 8   
(2909921)  
(критический)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(критический)  
VBScript 5.8   
(2909210)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.0 с пакетом обновления 3 (SP3)  
(2904878)  
(существенный)  
(только Media Center Edition 2005 с пакетом обновления 3 (SP3) и Tablet PC Edition 2005 с пакетом обновления 3 (SP3))  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2901111)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2898856)  
(существенный)  
Microsoft .NET Framework 4  
(2901110)  
(существенный)  
Microsoft .NET Framework 4  
(2898855)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows XP с пакетом обновления 3 (SP3)  
(2916036)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2909921)  
(критический)  
Internet Explorer 7   
(2909921)  
(критический)  
Internet Explorer 8   
(2909921)  
(критический)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(2909213)  
(критический)  
VBScript 5.7   
(2909212)  
(критический)  
VBScript 5.8   
(2909210)  
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2901111)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2898856)  
(существенный)  
Microsoft .NET Framework 4  
(2901110)  
(существенный)  
Microsoft .NET Framework 4  
(2898855)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)  
(2916036)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Средний](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
Нет

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Низкий](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
Нет

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2909921)  
(средний)  
Internet Explorer 7  
(2909921)  
(средний)  
Internet Explorer 8  
(2909921)  
(существенный)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(2909213)  
(средний)  
VBScript 5.7   
(2909212)  
(средний)  
VBScript 5.8   
(2909210)  
(средний)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)  
(2901115)  
(существенный)  
Microsoft .NET Framework 1.1 с пакетом обновления 1 (SP1)  
(2898860)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2901111)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2898856)  
(существенный)  
Microsoft .NET Framework 4  
(2901110)  
(существенный)  
Microsoft .NET Framework 4  
(2898855)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)  
(2916036)  
(низкий)

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
(2909921)  
(средний)  
Internet Explorer 7  
(2909921)  
(средний)  
Internet Explorer 8  
(2909921)  
(существенный)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(2909213)  
(средний)  
VBScript 5.7   
(2909212)  
(средний)  
VBScript 5.8   
(2909210)  
(средний)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2901111)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2898856)  
(существенный)  
Microsoft .NET Framework 4  
(2901110)  
(существенный)  
Microsoft .NET Framework 4  
(2898855)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)  
(2916036)  
(низкий)

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
(2909921)  
(средний)  
Internet Explorer 7  
(2909921)  
(средний)

</td>
<td style="border:1px solid black;">
VBScript 5.6  
(2909213)  
(средний)  
VBScript 5.7   
(2909212)  
(средний)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2901111)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2898856)  
(существенный)  
Microsoft .NET Framework 4  
(2901110)  
(существенный)  
Microsoft .NET Framework 4  
(2898855)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2003 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2916036)  
(низкий)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности

</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
Нет

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
Нет

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2909921)  
(критический)  
Internet Explorer 8  
(2909921)  
(критический)  
Internet Explorer 9   
(2909921)  
(критический)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(критический)  
VBScript 5.8 для систем с Internet Explorer 8  
(2909210)  
(критический)  
VBScript 5.8 для систем с Internet Explorer 9  
(2909921)<sup>[1]</sup>
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2901113)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2898858)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2911502)  
(существенный)  
Microsoft .NET Framework 4  
(2901110)  
(существенный)  
Microsoft .NET Framework 4  
(2898855)  
(существенный)  
Microsoft .NET Framework 4.5  
(2901118)  
(существенный)  
Microsoft .NET Framework 4.5  
(2898864)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Vista с пакетом обновления 2 (SP2)  
(2916036)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2909921)  
(критический)  
Internet Explorer 8  
(2909921)  
(критический)  
Internet Explorer 9   
(2909921)  
(критический)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(критический)  
VBScript 5.8 для систем с Internet Explorer 8  
(2909210)  
(критический)  
VBScript 5.8 для систем с Internet Explorer 9  
(2909921)<sup>[1]</sup>
(критический)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2901113)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2898858)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2911502)  
(существенный)  
Microsoft .NET Framework 4  
(2901110)  
(существенный)  
Microsoft .NET Framework 4  
(2898855)  
(существенный)  
Microsoft .NET Framework 4.5  
(2901118)  
(существенный)  
Microsoft .NET Framework 4.5  
(2898864)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition с пакетом обновления 2 (SP2)  
(2916036)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Средний](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
Нет

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Низкий](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
Нет

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2909921)  
(средний)  
Internet Explorer 8  
(2909921)  
(существенный)  
Internet Explorer 9   
(2909921)  
(существенный)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(средний)  
VBScript 5.8 для систем с Internet Explorer 8  
(2909210)  
(средний)  
VBScript 5.8 для систем с Internet Explorer 9  
(2909921)<sup>[1]</sup>
(средний)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2901113)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2898858)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2911502)  
(существенный)  
Microsoft .NET Framework 4  
(2901110)  
(существенный)  
Microsoft .NET Framework 4  
(2898855)  
(существенный)  
Microsoft .NET Framework 4.5  
(2901118)  
(существенный)  
Microsoft .NET Framework 4.5  
(2898864)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)  
(2916036)  
(низкий)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2909921)  
(средний)  
Internet Explorer 8  
(2909921)  
(существенный)  
Internet Explorer 9   
(2909921)  
(существенный)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(средний)  
VBScript 5.8 для систем с Internet Explorer 8  
(2909210)  
(средний)  
VBScript 5.8 для систем с Internet Explorer 9  
(2909921)<sup>[1]</sup>
(средний)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2901113)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2898858)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2911502)  
(существенный)  
Microsoft .NET Framework 4  
(2901110)  
(существенный)  
Microsoft .NET Framework 4  
(2898855)  
(существенный)  
Microsoft .NET Framework 4.5  
(2901118)  
(существенный)  
Microsoft .NET Framework 4.5  
(2898864)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем  
(2916036)  
(низкий)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2909921)  
(средний)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(2909212)  
(средний)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2901113)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2898858)  
(существенный)  
Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2)  
(2911502)  
(существенный)  
Microsoft .NET Framework 4  
(2901110)  
(существенный)  
Microsoft .NET Framework 4  
(2898855)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems с пакетом обновления 2 (SP2)  
(2916036)  
(низкий)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности

</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

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
(2909921)  
(критический)  
Internet Explorer 9   
(2909921)  
(критический)  
Internet Explorer 10   
(2909921)  
(критический)  
Internet Explorer 11   
(2909921)  
(критический)

</td>
<td style="border:1px solid black;">
VBScript 5.8 для систем с Internet Explorer 8  
(2909210)  
(критический)  
VBScript 5.8 для систем с Internet Explorer 9  
(2909921)<sup>[1]</sup>
(критический)  
VBScript 5.8 для систем с Internet Explorer 10  
(2909210)  
(критический)  
VBScript 5.8 для систем с Internet Explorer 11  
(2909210)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2912390)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2901112)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2898857)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2911501)  
(существенный)  
Microsoft .NET Framework 4  
(2901110)  
(существенный)  
Microsoft .NET Framework 4  
(2898855)  
(существенный)  
Microsoft .NET Framework 4.5  
(2901118)  
(существенный)  
Microsoft .NET Framework 4.5  
(2898864)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 7 для 32-разрядных систем с пакетом обновления 1 (SP1)  
(2916036)  
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
(2909921)  
(критический)  
Internet Explorer 9   
(2909921)  
(критический)  
Internet Explorer 10   
(2909921)  
(критический)  
Internet Explorer 11   
(2909921)  
(критический)

</td>
<td style="border:1px solid black;">
VBScript 5.8 для систем с Internet Explorer 8  
(2909210)  
(критический)  
VBScript 5.8 для систем с Internet Explorer 9  
(2909921)<sup>[1]</sup>
(критический)  
VBScript 5.8 для систем с Internet Explorer 10  
(2909210)  
(критический)  
VBScript 5.8 для систем с Internet Explorer 11  
(2909210)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2912390)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2901112)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2898857)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2911501)  
(существенный)  
Microsoft .NET Framework 4  
(2901110)  
(существенный)  
Microsoft .NET Framework 4  
(2898855)  
(существенный)  
Microsoft .NET Framework 4.5  
(2901118)  
(существенный)  
Microsoft .NET Framework 4.5  
(2898864)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 7 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2916036)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Средний](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Низкий](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
Нет

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2909921)  
(существенный)  
Internet Explorer 9   
(2909921)  
(существенный)  
Internet Explorer 10   
(2909921)  
(существенный)  
Internet Explorer 11   
(2909921)  
(существенный)

</td>
<td style="border:1px solid black;">
VBScript 5.8 для систем с Internet Explorer 8  
(2909210)  
(средний)  
VBScript 5.8 для систем с Internet Explorer 9  
(2909921)<sup>[1]</sup>
(средний)  
VBScript 5.8 для систем с Internet Explorer 10  
(2909210)  
(средний)  
VBScript 5.8 для систем с Internet Explorer 11  
(2909210)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2912390)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2901112)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2898857)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2911501)  
(существенный)  
Microsoft .NET Framework 4  
(2901110)  
(существенный)  
Microsoft .NET Framework 4  
(2898855)  
(существенный)  
Microsoft .NET Framework 4.5  
(2901118)  
(существенный)  
Microsoft .NET Framework 4.5  
(2898864)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для компьютеров на базе x64-процессоров с пакетом обновления 1 (SP1)  
(2916036)  
(низкий)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2909921)  
(существенный)

</td>
<td style="border:1px solid black;">
VBScript 5.8 для систем с Internet Explorer 8  
(2909210)  
(средний)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2901112)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2898857)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2911501)  
(существенный)  
Microsoft .NET Framework 4  
(2901110)  
(существенный)  
Microsoft .NET Framework 4  
(2898855)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems с пакетом обновления 1 (SP1)  
(2916036)  
(низкий)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 и Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности

</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2909921)  
(критический)

</td>
<td style="border:1px solid black;">
VBScript 5.8 для систем с Internet Explorer 10  
(2909210)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2912390)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901120)  
(существенный)  
Microsoft .NET Framework 3.5  
(2898866)  
(существенный)  
Microsoft .NET Framework 4.5  
(2901119)  
(существенный)  
Microsoft .NET Framework 4.5  
(2898865)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901127)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898870)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2916036)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8 для 32-разрядных систем  
(2904659)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2909921)  
(критический)

</td>
<td style="border:1px solid black;">
VBScript 5.8 для систем с Internet Explorer 10  
(2909210)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2912390)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901120)  
(существенный)  
Microsoft .NET Framework 3.5  
(2898866)  
(существенный)  
Microsoft .NET Framework 4.5  
(2901119)  
(существенный)  
Microsoft .NET Framework 4.5  
(2898865)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901127)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898870)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2916036)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8 для 64-разрядных систем  
(2904659)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2909921)  
(критический)

</td>
<td style="border:1px solid black;">
VBScript 5.8 для систем с Internet Explorer 11  
(2909210)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(2912390)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901125)  
(существенный)  
Microsoft .NET Framework 3.5  
(2898868)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901128)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898871)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 32-разрядных систем  
(2916036)  
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
(2909921)  
(критический)

</td>
<td style="border:1px solid black;">
VBScript 5.8 для систем с Internet Explorer 11  
(2909210)  
(критический)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(2912390)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901125)  
(существенный)  
Microsoft .NET Framework 3.5  
(2898868)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901128)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898871)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows 8.1 для 64-разрядных систем  
(2916036)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 и Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Средний](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Низкий](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2909921)  
(существенный)

</td>
<td style="border:1px solid black;">
VBScript 5.8 для систем с Internet Explorer 10  
(2909210)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2912390)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901120)  
(существенный)  
Microsoft .NET Framework 3.5  
(2898866)  
(существенный)  
Microsoft .NET Framework 4.5  
(2901119)  
(существенный)  
Microsoft .NET Framework 4.5  
(2898865)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901127)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898870)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2916036)  
(низкий)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2904659)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2909921)  
(существенный)

</td>
<td style="border:1px solid black;">
VBScript 5.8 для систем с Internet Explorer 11  
(2909210)  
(средний)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2912390)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901125)  
(существенный)  
Microsoft .NET Framework 3.5  
(2898868)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901128)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898871)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2916036)  
(низкий)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT и Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности

</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2909921)  
(критический)

</td>
<td style="border:1px solid black;">
VBScript 5.8 для систем с Internet Explorer 10  
(2909210)  
(критический)

</td>
<td style="border:1px solid black;">
Windows RT  
(2912390)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2901119)  
(существенный)  
Microsoft .NET Framework 4.5  
(2898865)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901127)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898870)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows RT  
(2916036)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows RT  
(2904659)  
(существенный)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2909921)  
(критический)

</td>
<td style="border:1px solid black;">
VBScript 5.8 для систем с Internet Explorer 11  
(2909210)  
(критический)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2912390)  
(критический)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1  
(2901128)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898871)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2916036)  
(существенный)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Вариант установки ядра сервера**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня

</td>
<td style="border:1px solid black;">
[MS14-010](http://go.microsoft.com/fwlink/?linkid=390977)

</td>
<td style="border:1px solid black;">
[MS14-011](http://go.microsoft.com/fwlink/?linkid=391023)

</td>
<td style="border:1px solid black;">
[MS14-007](http://go.microsoft.com/fwlink/?linkid=386447)

</td>
<td style="border:1px solid black;">
[MS14-009](http://go.microsoft.com/fwlink/?linkid=386454)

</td>
<td style="border:1px solid black;">
[MS14-005](http://go.microsoft.com/fwlink/?linkid=391022)

</td>
<td style="border:1px solid black;">
[MS14-006](http://go.microsoft.com/fwlink/?linkid=386450)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности

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
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Низкий](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[Существенный](http://go.microsoft.com/fwlink/?linkid=21140)

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
VBScript 5.7   
(2909212)  
(уровень опасности не определен)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2916036)  
(низкий)

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
VBScript 5.7   
(2909212)  
(уровень опасности не определен)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2) (установка основных серверных компонентов)  
(2916036)  
(низкий)

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
VBScript 5.8   
(2909210)  
(уровень опасности не определен)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2901112)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2898857)  
(существенный)  
Microsoft .NET Framework 3.5.1  
(2911501)  
(существенный)  
Microsoft .NET Framework 4  
(2901110)  
(существенный)  
Microsoft .NET Framework 4.5  
(2901118)  
(существенный)  
Microsoft .NET Framework 4.5  
(2898864)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901126)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898869)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 для 64-разрядных систем с пакетом обновления 1 (SP1) (установка основных серверных компонентов)  
(2916036)  
(низкий)

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
VBScript 5.8   
(2909210)  
(уровень опасности не определен)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901120)  
(существенный)  
Microsoft .NET Framework 3.5  
(2898866)  
(существенный)  
Microsoft .NET Framework 4.5  
(2901119)  
(существенный)  
Microsoft .NET Framework 4.5  
(2898865)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901127)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898870)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(2916036)  
(низкий)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (установка основных серверных компонентов)  
(2904659)  
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
VBScript 5.8   
(2909210)  
(уровень опасности не определен)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2901125)  
(существенный)  
Microsoft .NET Framework 3.5  
(2898868)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2901128)  
(существенный)  
Microsoft .NET Framework 4.5.1  
(2898871)  
(существенный)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (установка основных серверных компонентов)  
(2916036)  
(низкий)

</td>
<td style="border:1px solid black;">
Не применимо

</td>
</tr>
</table>
 
Примечание для MS14-011

<sup>[1]</sup>Для систем с Internet Explorer 9 данная уязвимость устраняется накопительным обновлением 2909921 для Internet Explorer 9, описанным в бюллетене [MS14-010](http://go.microsoft.com/fwlink/?linkid=390977).

 

### Программное обеспечение корпорации Майкрософт по безопасности

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Forefront Protection 2010 для Exchange Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Идентификационный номер бюллетеня

</td>
<td style="border:1px solid black;">
[MS14-008](http://go.microsoft.com/fwlink/?linkid=390218)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Общий уровень серьезности

</td>
<td style="border:1px solid black;">
[Критический](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Forefront Protection 2010 для Exchange Server

</td>
<td style="border:1px solid black;">
Microsoft Forefront Protection 2010 для Exchange Server  
(2927022)  
(критический)

</td>
</tr>
</table>
 
 

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span id="sectionToggle3"></span>
Доступно несколько ресурсов, чтобы помочь администраторам развернуть обновления для системы безопасности.

-   Анализатор безопасности Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений для системы безопасности и типичных ошибок в конфигурации системы безопасности.
-   Службы Windows Server Update Services (WSUS), Systems Management Server (SMS) и System Center Configuration Manager помогают администраторам распространять обновления для системы безопасности.
-   Компоненты средства оценки совместимости с обновлениями, включенные в набор средств для обеспечения совместимости приложений, облегчают тестирование и проверку совместимости обновлений Windows с установленными приложениями.

Информацию об этих и других доступных инструментах см. в статье [Инструменты обеспечения безопасности](http://technet.microsoft.com/security/cc297183). 

Благодарности
-------------

<span id="sectionToggle4"></span>
Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:

MS14-005

-   Корпорацию [FireEye, Inc.](http://www2.fireeye.com/) за совместную работу по устранению уязвимости MSXML, приводящей к раскрытию информации (CVE-2014-0266)

MS14-007

-   Пользователя [Omair](http://krash.in/), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости компонента Microsoft Graphics, приводящей к повреждению памяти (CVE-2014-0263)

MS14-009

-   Джеймса Форшо (James Forshaw) из компании [Context Information Security](http://www.contextis.com/) за сообщение об уязвимости, связанной с обходом типов (CVE-2014-0257)

MS14-010

-   Лян Чэна (Liang Chen) из группы [KeenTeam](http://www.k33nteam.org/) (@K33nTeam) за совместную работу по устранению уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0267)
-   Лабораторию Code Audit Labs компании [VulnHunt](http://www.vulnhunt.com/) за совместную работу по устранению уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0267)
-   Джеймса Форшо (James Forshaw) из компании [Context Information Security](http://www.contextis.com/) за сообщение об уязвимости Internet Explorer, приводящей к несанкционированному повышению привилегий (CVE-2014-0268)
-   Саймона Цукербрауна (Simon Zuckerbraun), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0269)
-   Хосе А. Васкеса (Jose A. Vazquez) из Yenteasy Security Research, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0270)
-   Хосе А. Васкеса (Jose A. Vazquez) из Yenteasy Security Research, сотрудничающего с компанией [VeriSign iDefense Labs](http://labs.idefense.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0270)
-   Бо Ку (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0272)
-   Бо Ку (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0273)
-   Артура Геркиса (Arthur Gerkis), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0274)
-   Пользователя lokihardt@ASRT, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0274)
-   Саймона Цукербрауна (Simon Zuckerbraun), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0275)
-   Скота Белла (Scott Bell) из компании [Security-Assessment.com](http://www.security-assessment.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0276)
-   Скота Белла (Scott Bell) из компании [Security-Assessment.com](http://www.security-assessment.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0277)
-   Бо Ку (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0278)
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0278)
-   Скота Белла (Scott Bell) из компании [Security-Assessment.com](http://www.security-assessment.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0279)
-   Бо Ку (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0279)
-   Скота Белла (Scott Bell) из компании [Security-Assessment.com](http://www.security-assessment.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0280)
-   Пользователей cons0ul и suto, сотрудничающих с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0281)
-   Сачин Шинде (Sachin Shinde) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0283)
-   Сачин Шинде (Sachin Shinde) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0284)
-   Саймона Цукербрауна (Simon Zuckerbraun), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0285)
-   Анонимного исследователя, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0285)
-   Саймона Цукербрауна (Simon Zuckerbraun), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0286)
-   Питера 'corelanc0d3r' Ван Экуте (Peter 'corelanc0d3r' Van Eeckhoutte) из компании [Corelan](http://www.corelangcv.com/), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0287)
-   Артура Геркиса (Arthur Gerkis), сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0288)
-   Пользователя lokihardt@ASRT, сотрудничающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0289)
-   Бо Ку (Bo Qu) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0290)
-   Чжибинь Ху (Zhibin Hu) из компании [Qihoo](http://www.360.cn/) за сообщение об уязвимости об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0290)
-   Юки Чэня (Yuki Chen) из компании [Trend Micro](http://www.trendmicro.com/), работающего с компанией [HP](http://www.hpenterprisesecurity.com/products) в рамках программы [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение об уязвимости Internet Explorer, приводящей к повреждению памяти (CVE-2014-0290)
-   [Dieyu dieu deus deva divine dio theos dievas dewa ilu Diyin Ayóo Átʼéii atua tiānzhŭ Yahweh Zeus Odin El](http://dieyu.org/) за сообщение об уязвимости Internet Explorer, приводящей к междоменному раскрытию информации (CVE-2014-0293)

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

Стратегии управления обновлениями

В статье [Рекомендации по безопасности для управления обновлениями](http://go.microsoft.com/fwlink/?linkid=21168) содержатся дополнительные сведения о рекомендациях Майкрософт по установке обновлений для системы безопасности.

Другие обновления для системы безопасности

Другие обновления безопасности можно загрузить из следующих источников:

-   Обновления для системы безопасности доступны в [Центре загрузки Майкрософт](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".
-   Обновления для индивидуальных пользователей доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747).
-   Обновления безопасности, предлагаемые в этом месяце в Центре обновления Windows, можно загрузить с веб-сайта Центра загрузки Майкрософт в виде файлов ISO-образа компакт-диска с выпусками обновлений безопасности. Дополнительные сведения см. в [статье 913086 базы знаний Майкрософт](https://support.microsoft.com/kb/913086).

Сообщество ИТ-специалистов, занимающихся вопросами безопасности

На веб-сайте [сообщества ИТ-специалистов, занимающихся вопросами безопасности](http://go.microsoft.com/fwlink/?linkid=21164), можно найти сведения о способах улучшения системы безопасности и оптимизации ИТ-инфраструктуры предприятия, а также обсудить вопросы безопасности с другими ИТ-специалистами.

### Поддержка

-   Подверженное уязвимости программное обеспечение, перечисленное в этом бюллетене, проверено на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Решения безопасности для ИТ-специалистов: [Устранение неполадок и поддержка на веб-сайте TechNet](http://technet.microsoft.com/security/bb980617)
-   Защита компьютера с установленной ОС Windows от вирусов и вредоносных программ: [Центр решений по антивирусам и безопасности](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Местная поддержка в зависимости от страны: [Международная поддержка](http://support.microsoft.com/common/international.aspx)

### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

### Редакции

-   Вер. 1.0 (11 февраля 2014 г.): Обзор бюллетеней опубликован.
-   Вер. 1.1 (12 февраля 2014 г.): В бюллетене MS14-008 в разделе "Оценка возможности использования уязвимостей для более старых выпусков программного обеспечения" внесены исправления в **Индекс использования уязвимостей** для CVE-2014-0294.
-   Вер. 1.2 (13 февраля 2014 г.): В бюллетене MS14-011 в разделе "Оценка возможности использования уязвимостей для последнего выпуска программного обеспечения" внесены исправления в Индекс использования уязвимостей для CVE-2014-0271.

*Время создания страницы: 2014-04-23 12:19Z-07:00.*
