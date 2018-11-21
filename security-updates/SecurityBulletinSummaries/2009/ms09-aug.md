---
TOCTitle: 'MS09-AUG'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Август 2009 г.'
ms:assetid: 'ms09-aug'
ms:contentKeyID: 61236120
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms09-aug(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Август 2009 г.
=================================================================

Дата публикации: 8 ноября 2009 г. | Дата обновления: 27 октября 2009 г.

**Версия:** 4.0

В этом обзоре описаны бюллетени по безопасности, выпущенные в августе 2009 г.

В связи с публикацией бюллетеней за август 2009 года настоящий обзор заменяет предварительное уведомление, выпущенное 6 августа 2009 г. Дополнительные сведения о службе предварительного уведомления см. на веб-сайте [службы предварительного уведомления о бюллетенях Майкрософт по безопасности](http://technet.microsoft.com/security/bulletin/advance).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

12 августа 2009 г. в 11:00 по тихоокеанскому времени (для США и Канады) корпорация Майкрософт проведет веб-трансляцию, в которой ответит на вопросы пользователей об этих бюллетенях. [Зарегистрируйтесь для участия в августовской веб-трансляции, посвященной бюллетеням по безопасности](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032407484&eventcategory=4&culture=en-us&countrycode=us). После наступления этой даты данная веб-трансляция будет доступна по запросу. Дополнительные сведения см. на веб-сайте [обзоров и веб-трансляций, посвященных бюллетеням Майкрософт по безопасности](http://technet.microsoft.com/security/bulletin/summary).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128110">MS09-043</a></td>
<td style="border:1px solid black;"><strong>Уязвимости веб-компонентов Microsoft Office делают возможным удаленное выполнение кода (957638)</strong><br />
<br />
Это обновление для системы безопасности устраняет несколько обнаруженных пользователями уязвимостей веб-компонентов Microsoft Office, делающих возможным удаленное выполнение кода при просмотре пользователем специально созданной веб-страницы. Злоумышленник, успешно воспользовавшийся данными уязвимостями, может получить те же права, которыми обладает локальный пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office, Microsoft Visual Studio, Microsoft ISA Server, Microsoft BizTalk Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=157861">MS09-044</a></td>
<td style="border:1px solid black;"><strong>Уязвимости подключения к удаленному рабочему столу делают возможным удаленное выполнение кода (970927)</strong><br />
<br />
Это обновление для системы безопасности устраняет две обнаруженные пользователями уязвимости подключения к удаленному рабочему столу Майкрософт. Эти уязвимости делают возможным удаленное выполнение кода при условии, что злоумышленник сможет убедить пользователя службы терминалов подключиться к вредоносному серверу RDP, а также при посещении пользователем веб-сайта, специально созданного для использования этой уязвимости. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows, клиент подключения к удаленному рабочему столу для Mac</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=155974">MS09-039</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в протоколе WINS делают возможным удаленное выполнение кода (969883)</strong><br />
<br />
Данное обновление для системы безопасности устраняет две обнаруженных пользователями уязвимости службы WINS. Обе уязвимости делают возможным удаленное выполнение кода при получении уязвимой системой специально созданного пакета репликации WINS. По умолчанию служба WINS не установлена в версиях операционной системы, подверженных уязвимости. Этой проблеме подвержены только системы, на которых этот компонент установлен вручную.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=155975">MS09-038</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в средствах обработки файлов проигрывателя Windows Media делают возможным удаленное выполнение кода (971557)</strong><br />
<br />
Это обновление для системы безопасности устраняет две обнаруженные пользователями уязвимости в средствах обработки файлов проигрывателя Windows Media. При открытии пользователем специально созданного файла формата AVI эта уязвимость делает возможным удаленное выполнение кода. Если пользователь вошел в систему с правами администратора, то злоумышленник, которому удалось воспользоваться уязвимостью, может установить полный контроль над системой. что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158695">MS09-037</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в библиотеке Microsoft ATL делают возможным удаленное выполнение кода (973908)</strong><br />
<br />
Это обновление для системы безопасности устраняет несколько обнаруженных пользователями уязвимостей Microsoft ATL. Они делают возможным удаленное выполнение кода, если пользователь загрузит специально созданный компонент или элемент управления, размещенный на вредоносном веб-сайте. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=155977">MS09-041</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в службе рабочей станции делает возможным несанкционированное получение прав (971657)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость службы рабочей станции Windows. Она может привести к несанкционированному получению прав злоумышленником при запуске и отправке уязвимой системе специально созданного сообщения удаленного вызова процедуры (RPC). Злоумышленник, успешно воспользовавшийся ею, может выполнить произвольный код и получить полный контроль над системой. что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Чтобы воспользоваться уязвимостью, злоумышленник должен обладать действительными учетными данными для входа в уязвимую систему. Данной уязвимостью не могут воспользоваться анонимные пользователи.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=155979">MS09-040</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в службе очереди сообщений Microsoft может привести к несанкционированному получению прав (971032)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость службы очереди сообщений Windows. Эта уязвимость может привести к несанкционированному получению прав при получении пользователем специально созданного запроса уязвимой службы очереди сообщений. По умолчанию компонент очереди сообщений не установлен в уязвимых выпусках операционных систем, это может сделать только пользователь с правами администратора. Только клиенты, которые вручную устанавливают компонент Message Queuing, вероятно, будут подвержены этой уязвимости.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=157296">MS09-036</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в ASP.NET в Microsoft Windows может привести к отказу в обслуживании (970957)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft .NET Framework, компоненте Microsoft Windows, которая может привести к отказу в обслуживании. Злоумышленники могут воспользоваться этой уязвимостью только в том случае, если в подверженных ей версиях Microsoft Windows установлены службы IIS 7.0, а в среде ASP.NET настроено использование интегрированного режима. Злоумышленник может послать специально созданные анонимные HTTP-запросы, которые могут привести к тому, что уязвимый веб-сервер перестанет отвечать до тех пор, пока не будет перезапущен соответствующий пул приложений. Системы, в которых пулы приложений IIS 7.0 запущены в классическом режиме, не подвержены этой уязвимости.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Отказ в обслуживании</td>
<td style="border:1px solid black;">Перезагрузка не требуется</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=157140">MS09-042</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в протоколе Telnet делает возможным удаленное выполнение кода (960859)</strong><br />
<br />
Это обновление для системы безопасности устраняет опубликованную уязвимость в службе Microsoft Telnet. Эта уязвимость может позволить злоумышленнику получить учетные данные и войти с их помощью в уязвимую систему. Злоумышленник может затем получить права пользователя, аналогичные правам пользователя, вошедшего в систему. В результате на уязвимой системе возможно удаленное выполнение кода. Злоумышленник, воспользовавшийся данной уязвимостью, сможет устанавливать программы, просматривать, изменять, удалять данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Индекс использования уязвимостей  
--------------------------------
  
<span></span>
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости сгруппированы по идентификаторам бюллетеней и кодам CVE.
  
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать о вероятности появления стабильно работающего кода эксплойта в течение 30 дней после выпуска бюллетеня по каждому из обновлений для системы безопасности, которые необходимо установить. Перед назначением приоритетов развертывания ознакомьтесь с каждой приведенной ниже оценкой, относящейся к конкретной конфигурации. Дополнительные сведения об уровнях опасности и способах их определения см. в [индексе использования уязвимостей](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| Идентификатор бюллетеня                                   | Название бюллетеня                                                                                                      | Код CVE                                                                          | Оценка индекса использования уязвимостей                                                                                        | Ключевые примечания                                                                                                                                                                                                                                                       |  
|-----------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-036](http://go.microsoft.com/fwlink/?linkid=157296) | Уязвимость в ASP.NET в Microsoft Windows может привести к отказу в обслуживании (970957)                                | [CVE-2009-1536](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1536) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - существование функционирующего кода эксплойта маловероятно | Возможно использование средств организации атак DoS. Однако использование стабильно функционирующего эксплойта для удаленного выполнения маловероятно.                                                                                                                    |  
| [MS09-037](http://go.microsoft.com/fwlink/?linkid=158695) | Уязвимости в библиотеке Microsoft ATL делают возможным удаленное выполнение кода (973908)                               | [CVE-2008-0015](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0015) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода эксплойта                    | **Примеры использования данной уязвимости известны в экосистеме Интернета.**                                                                                                                                                                                              |  
| [MS09-037](http://go.microsoft.com/fwlink/?linkid=158695) | Уязвимости в библиотеке Microsoft ATL делают возможным удаленное выполнение кода (973908)                               | [CVE-2008-0020](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0020) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода эксплойта                    | (Отсутствует)                                                                                                                                                                                                                                                             |  
| [MS09-037](http://go.microsoft.com/fwlink/?linkid=158695) | Уязвимости в библиотеке Microsoft ATL делают возможным удаленное выполнение кода (973908)                               | [CVE-2009-0901](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901) | Н/Д                                                                                                                             | (Оценка индекса использования этой уязвимости уже приведена в [Обзоре бюллетеней за июль](http://technet.microsoft.com/security/bulletin/ms09-jul). Причина этого в том, что эта уязвимость впервые описана в [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131).) |  
| [MS09-037](http://go.microsoft.com/fwlink/?linkid=158695) | Уязвимости в библиотеке Microsoft ATL делают возможным удаленное выполнение кода (973908)                               | [CVE-2009-2493](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | Н/Д                                                                                                                             | (Оценка индекса использования этой уязвимости уже приведена в [Обзоре бюллетеней за июль](http://technet.microsoft.com/security/bulletin/ms09-jul). Причина этого в том, что эта уязвимость впервые описана в [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131).) |  
| [MS09-037](http://go.microsoft.com/fwlink/?linkid=158695) | Уязвимости в библиотеке Microsoft ATL делают возможным удаленное выполнение кода (973908)                               | [CVE-2009-2494](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2494) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода эксплойта                    | (Отсутствует)                                                                                                                                                                                                                                                             |  
| [MS09-038](http://go.microsoft.com/fwlink/?linkid=155975) | Уязвимости в средствах обработки файлов проигрывателя Windows Media делают возможным удаленное выполнение кода (971557) | [CVE-2009-1545](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1545) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование нестабильного кода эксплойта        | (Отсутствует)                                                                                                                                                                                                                                                             |  
| [MS09-038](http://go.microsoft.com/fwlink/?linkid=155975) | Уязвимости в средствах обработки файлов проигрывателя Windows Media делают возможным удаленное выполнение кода (971557) | [CVE-2009-1546](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1546) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование нестабильного кода эксплойта        | (Отсутствует)                                                                                                                                                                                                                                                             |  
| [MS09-039](http://go.microsoft.com/fwlink/?linkid=155974) | Уязвимости в протоколе WINS делают возможным удаленное выполнение кода (969883)                                         | [CVE-2009-1923](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1923) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода эксплойта                    | (Отсутствует)                                                                                                                                                                                                                                                             |  
| [MS09-039](http://go.microsoft.com/fwlink/?linkid=155974) | Уязвимости в протоколе WINS делают возможным удаленное выполнение кода (969883)                                         | [CVE-2009-1924](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1924) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование нестабильного кода эксплойта        | Успешные атаки с использованием эксплойта вероятнее в отношении систем под управлением Windows 2000.                                                                                                                                                                      |  
| [MS09-040](http://go.microsoft.com/fwlink/?linkid=155979) | Уязвимость в службе очереди сообщений Microsoft может привести к несанкционированному получению прав (971032)           | [CVE-2009-1922](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1922) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода эксплойта                    | Удаленная атака, направленная на использование данной уязвимости, невозможна.                                                                                                                                                                                             |  
| [MS09-041](http://go.microsoft.com/fwlink/?linkid=155977) | Уязвимость в службе рабочей станции делает возможным несанкционированное получение прав (971657)                        | [CVE-2009-1544](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1544) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода эксплойта                    | Чтобы воспользоваться данной уязвимостью, злоумышленнику необходимо пройти проверку подлинности.                                                                                                                                                                          |  
| [MS09-042](http://go.microsoft.com/fwlink/?linkid=157140) | Уязвимость в протоколе Telnet делает возможным удаленное выполнение кода (960859)                                       | [CVE-2009-1930](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1930) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода эксплойта                    | Данная уязвимость сходна с предыдущими уязвимостями NTLM, связанными с отображением учетных данных. Эксплойты для последних уже существуют.                                                                                                                               |  
| [MS09-043](http://go.microsoft.com/fwlink/?linkid=128110) | Уязвимости веб-компонентов Microsoft Office делают возможным удаленное выполнение кода (957638)                         | [CVE-2009-0562](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0562) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода эксплойта                    | (Отсутствует)                                                                                                                                                                                                                                                             |  
| [MS09-043](http://go.microsoft.com/fwlink/?linkid=128110) | Уязвимости веб-компонентов Microsoft Office делают возможным удаленное выполнение кода (957638)                         | [CVE-2009-1136](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1136) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода эксплойта                    | Эксплойт для этой уязвимости уже опубликован.                                                                                                                                                                                                                             |  
| [MS09-043](http://go.microsoft.com/fwlink/?linkid=128110) | Уязвимости веб-компонентов Microsoft Office делают возможным удаленное выполнение кода (957638)                         | [CVE-2009-1534](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1534) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода эксплойта                    | (Отсутствует)                                                                                                                                                                                                                                                             |  
| [MS09-043](http://go.microsoft.com/fwlink/?linkid=128110) | Уязвимости веб-компонентов Microsoft Office делают возможным удаленное выполнение кода (957638)                         | [CVE-2009-2496](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2496) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода эксплойта                    | (Отсутствует)                                                                                                                                                                                                                                                             |  
| [MS09-044](http://go.microsoft.com/fwlink/?linkid=157861) | Уязвимости подключения к удаленному рабочему столу делают возможным удаленное выполнение кода (970927)                  | [CVE-2009-1133](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1133) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - возможно существование нестабильного кода эксплойта        | (Отсутствует)                                                                                                                                                                                                                                                             |  
| [MS09-044](http://go.microsoft.com/fwlink/?linkid=157861) | Уязвимости подключения к удаленному рабочему столу делают возможным удаленное выполнение кода (970927)                  | [CVE-2009-1929](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1929) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможна согласованность кода эксплойта                    | (Отсутствует)                                                                                                                                                                                                                                                             |
  
Продукты, подверженные уязвимости, и соответствующие обновления  
---------------------------------------------------------------
  
<span></span>
В приведенных ниже таблицах перечислены бюллетени в порядке важности категорий программного обеспечения и уровней опасности.
  
**Как пользоваться этими таблицами?**
  
Обращайтесь к этим таблицам, чтобы узнать, какие обновления для системы безопасности необходимо установить. Ознакомьтесь со списком программ и компонентов и узнайте, имеются ли для них обновления для системы безопасности. Для программ или компонентов, указанных в списке, приведены ссылки на доступные обновления с указанием уровня опасности уязвимостей, которые они устраняют.
  
**Примечание**. Для устранения одной уязвимости может потребоваться установка нескольких обновлений безопасности. Просмотрите весь столбец для каждого указанного в таблице идентификационного номера бюллетеня, чтобы узнать, какие обновления следует установить для программ и программных компонентов, установленных на компьютере.
  
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
</tr>
<tr>
<th colspan="9">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://go.microsoft.com/fwlink/?linkid=157861)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://go.microsoft.com/fwlink/?linkid=155974)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://go.microsoft.com/fwlink/?linkid=155975)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://go.microsoft.com/fwlink/?linkid=158695)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://go.microsoft.com/fwlink/?linkid=155977)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://go.microsoft.com/fwlink/?linkid=155979)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://go.microsoft.com/fwlink/?linkid=157296)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://go.microsoft.com/fwlink/?linkid=157140)
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
Н/Д
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Н/Д
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 с пакетом обновления 4 (SP4);
</td>
<td style="border:1px solid black;">
[RDP 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=027e757d-08d5-4932-b8c4-52ee1be1c864)\*\*\*  
(KB958471) и [RDP 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=ae72782e-920f-4176-a27b-c3b91d50c7d2) (KB958470)  
(критический)  
[RDP 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=ae72782e-920f-4176-a27b-c3b91d50c7d2)\*\*\*\*  
(KB958470)  
(критический)  
[RDP 5.2](http://www.microsoft.com/downloads/details.aspx?familyid=ae72782e-920f-4176-a27b-c3b91d50c7d2)\*\*\*\*  
(KB958470)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=b5b9228a-66c0-49e6-afde-cc2825a6851f)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=5f80bf0b-898c-46ca-b20c-21e0e729c332)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 5.5 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6f9fcbe9-8496-4d23-8a16-b334157688c2)  
(KB973354)  
(критический)  
[Microsoft Outlook Express 6 с пакетом обновления 1 (SP1) —](http://www.microsoft.com/downloads/details.aspx?familyid=f340af34-b9a0-44fb-b595-dbb346c727bf)  
(KB973354)  
(критический)  
[Проигрыватель Windows Media 9](http://www.microsoft.com/downloads/details.aspx?familyid=bd7c9fc4-61cb-4c23-9961-6d63f234731c)  
(KB973540)  
(критический)  
[Компонент Windows ATL](http://www.microsoft.com/downloads/details.aspx?familyid=c773149a-f4fc-486a-b718-6b8ff7a36ae2)  
(KB973507)  
(критический)  
[Элемент управления ActiveX компонента редактирования DHTML](http://www.microsoft.com/downloads/details.aspx?familyid=223e25d2-83d7-4cb7-85c4-46a42b8110e0)  
(KB973869)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=8ed8bad7-2885-452c-9c34-3982cd498be8)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=240977d6-3581-4058-b9f1-7847e4edcf8a)  
(существенный)
</td>
</tr>
<tr>
<th colspan="9">
ОС Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://go.microsoft.com/fwlink/?linkid=157861)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://go.microsoft.com/fwlink/?linkid=155974)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://go.microsoft.com/fwlink/?linkid=155975)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://go.microsoft.com/fwlink/?linkid=158695)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://go.microsoft.com/fwlink/?linkid=155977)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://go.microsoft.com/fwlink/?linkid=155979)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://go.microsoft.com/fwlink/?linkid=157296)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://go.microsoft.com/fwlink/?linkid=157140)
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
Н/Д
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
Н/Д
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP с пакетом обновления 2 (SP2) или 3 (SP3)
</td>
<td style="border:1px solid black;">
[RDP 5.1 в Windows XP с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2a8830dd-8fb3-4556-a6e7-2c237235357f)  
(KB958470)  
(критический)  
[RDP 5.2 для Windows XP с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=cf9f9898-10c8-45ab-9df3-85e0b37e6046)\*\*\*\*  
(KB958469)  
(критический)  
[RDP версии 5.2 в Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=cf9f9898-10c8-45ab-9df3-85e0b37e6046)  
(KB958469)  
(критический)  
[RDP 6.0 для Windows XP с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d1f82d76-eeb2-4ff4-9d2c-46882f214719)\*\*\*\*  
(KB956744)  
(существенный)  
[RDP версии 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=d1f82d76-eeb2-4ff4-9d2c-46882f214719)\*\*\*\*  
(KB956744)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2) и 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=2e8a68ee-eb24-424c-b084-450636ccaeec)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=c67b5506-00ea-47cc-a0e8-897057b7380c)  
(KB973354)  
(критический)  
[Проигрыватель Windows Media 9, Проигрыватель Windows Media 10 и Проигрыватель Windows Media 11](http://www.microsoft.com/downloads/details.aspx?familyid=34b2b14d-5811-4635-ba83-f837dcb03d04)  
(KB973540)  
(критический)  
(только Windows XP с пакетом обновления 2 (SP2))  
[Проигрыватель Windows Media 9, Проигрыватель Windows Media 10 и Проигрыватель Windows Media 11](http://www.microsoft.com/downloads/details.aspx?familyid=ec84c98b-6bc7-442f-9280-d6e204280b2f)  
(KB973540)  
(критический)  
(только Windows XP с пакетом обновления 3 (SP3))  
[Компонент Windows ATL](http://www.microsoft.com/downloads/details.aspx?familyid=4b4c6fc5-e8e6-4d89-a181-e231240468f9)  
(KB973507)  
(критический)  
[Элемент управления ActiveX компонента редактирования DHTML](http://www.microsoft.com/downloads/details.aspx?familyid=bdfcd0c3-7c18-4e63-91dd-d8f82cd89592)  
(KB973869)  
(критический)  
[Элемент управления ActiveX компонента MSWebDVD](http://www.microsoft.com/downloads/details.aspx?familyid=8b71bcc9-5146-4afc-8847-0af21d7fad36)  
(KB973815)  
(критический)  
[Элемент управления ActiveX объекта HtmlInput](http://www.microsoft.com/downloads/details.aspx?familyid=46aa443c-4e7b-4bd5-8b4e-0068c3dc0e79)  
(KB973768)  
(критический)  
(только Media Center Edition 2005)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2) и 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=9c0e5bff-c248-4e87-a83b-82ba52f5299d)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=93490aa7-9985-4658-b0d7-88fb3f27ada0)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2) и 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=b3331388-1e52-4924-b512-23275a8fde84)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[RDP 5.2 в Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=948da99a-44ed-4390-b1b4-7ed3f15a9cda)  
(KB958469)  
(критический)  
[RDP 6.0 для Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5061615f-fa8f-465f-ac8f-393998b7e91b)\*\*\*\*  
(KB956744)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a1ff2ace-b9dc-4cf3-a151-ac6959bcb3a6)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=ede1a73a-e303-435e-a2c7-0281ce2370da)  
(KB973354)  
(критический)  
[Проигрыватель Windows Media 10](http://www.microsoft.com/downloads/details.aspx?familyid=bb98187a-8db9-47e4-88ac-15544c5268f6)  
(KB973540)  
(критический)  
[Проигрыватель Windows Media 11](http://www.microsoft.com/downloads/details.aspx?familyid=9e8b9027-4407-4c31-a2ba-9e094557d467)  
(KB973540)  
(критический)  
[Компонент Windows ATL](http://www.microsoft.com/downloads/details.aspx?familyid=2f2b93fc-f977-4f23-af90-c27f744fad0a)  
(KB973507)  
(критический)  
[Элемент управления ActiveX компонента редактирования DHTML](http://www.microsoft.com/downloads/details.aspx?familyid=d04a6959-41a4-4a87-b3ad-7455d8fe8b99)  
(KB973869)  
(критический)  
[Элемент управления ActiveX компонента MSWebDVD](http://www.microsoft.com/downloads/details.aspx?familyid=85b2dcdb-cea9-4c4a-8ebd-50264e781ade)  
(KB973815)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7b64a454-d383-47e3-b469-b87e2b3c1a9f)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=12e6be68-dc87-450e-927b-3c9b6873eb13)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a6ee7af3-3e39-4866-a893-92bf1c786cd4)  
(существенный)
</td>
</tr>
<tr>
<th colspan="9">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://go.microsoft.com/fwlink/?linkid=157861)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://go.microsoft.com/fwlink/?linkid=155974)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://go.microsoft.com/fwlink/?linkid=155975)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://go.microsoft.com/fwlink/?linkid=158695)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://go.microsoft.com/fwlink/?linkid=155977)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://go.microsoft.com/fwlink/?linkid=155979)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://go.microsoft.com/fwlink/?linkid=157296)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://go.microsoft.com/fwlink/?linkid=157140)
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
Н/Д
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[RDP версии 5.2](http://www.microsoft.com/downloads/details.aspx?familyid=60c79729-ef01-4630-bd67-ec63e7f8b56b)  
(KB958469)  
(критический)  
[RDP 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=a37a2d8a-a5ce-4f06-bf07-8cafa16e7a59)\*\*\*\*  
(KB956744)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3a8d8ef9-ad41-4237-9cbb-daecfd8f216c)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=cba78658-899c-428f-8b04-cfe14ce3c255)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=3119ab1e-6729-40a1-b28f-0dab50502be6)  
(KB973354)  
(критический)  
[Проигрыватель Windows Media 10](http://www.microsoft.com/downloads/details.aspx?familyid=ab054890-983b-4414-ad0a-da1b2d2a4895)  
(KB973540)  
(критический)  
[Компонент Windows ATL](http://www.microsoft.com/downloads/details.aspx?familyid=7d9369b5-0c54-4c17-bc62-fba0a7b4728c)  
(KB973507)  
(критический)  
[Элемент управления ActiveX компонента редактирования DHTML](http://www.microsoft.com/downloads/details.aspx?familyid=bfc474c2-e3c5-40df-85d4-4ac666ff0561)  
(KB973869)  
(критический)  
[Элемент управления ActiveX компонента MSWebDVD](http://www.microsoft.com/downloads/details.aspx?familyid=301ad191-8d3f-41d3-b41c-e2e863893f73)  
(KB973815)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=9cb0477f-0656-47f5-bd35-5716e0572fbd)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=52f59c56-2aba-4626-a90e-311e0e73c813)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3fe9c745-d87c-43b0-9b2a-356fb34282b4)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[RDP версии 5.2](http://www.microsoft.com/downloads/details.aspx?familyid=57393588-dc96-4bda-ab1e-ae550961e5d4)  
(KB958469)  
(критический)  
[RDP 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=957c2e01-89a1-4550-aacb-de8ff896d762)\*\*\*\*  
(KB956744)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e132d051-4444-4ef1-9b6f-2d7da9d2e88e)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=58a7c8d9-ec36-46a6-a89b-d8dfd989fda4)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=17bd00e3-810c-4a72-bd13-1b55ffb52a5e)  
(KB973354)  
(критический)  
[Проигрыватель Windows Media 10](http://www.microsoft.com/downloads/details.aspx?familyid=5890233a-d8f7-490c-8bf5-3ed4bd1c6991)  
(KB973540)  
(критический)  
[Компонент Windows ATL](http://www.microsoft.com/downloads/details.aspx?familyid=90e0e014-ed7e-498a-9f61-18bb09a384b3)  
(KB973507)  
(критический)  
[Элемент управления ActiveX компонента редактирования DHTML](http://www.microsoft.com/downloads/details.aspx?familyid=9f502d79-99a8-45dc-9876-2df27e14ffaa)  
(KB973869)  
(критический)  
[Элемент управления ActiveX компонента MSWebDVD](http://www.microsoft.com/downloads/details.aspx?familyid=2ae71a65-5eee-4dd2-bc79-b7c5a73022bc)  
(KB973815)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=96fbf65f-1db2-432d-92a0-6669d8abaeb0)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2f77ef7b-54f8-4260-b6a6-d62a0f85ef45)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=e2a788e7-a9d1-4574-b106-f8ab44c6c4a2)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium
</td>
<td style="border:1px solid black;">
[RDP версии 5.2](http://www.microsoft.com/downloads/details.aspx?familyid=8f88a714-b917-4193-9002-19fa65722028)  
(KB958469)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=96c3f496-7b2f-4dbc-b484-216c9943c2b1)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=187b02bd-73d6-4f72-81d1-d9477d495499)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?familyid=7978b921-c5b5-461f-a284-b9848f568aa9)  
(KB973354)  
(критический)  
[Компонент Windows ATL](http://www.microsoft.com/downloads/details.aspx?familyid=ad1791b3-8553-4433-a9f7-8b4f857665be)  
(KB973507)  
(критический)  
[Элемент управления ActiveX компонента редактирования DHTML](http://www.microsoft.com/downloads/details.aspx?familyid=82c0bb02-70ad-4605-a1f4-4698adf9f4ac)  
(KB973869)  
(критический)  
[Элемент управления ActiveX компонента MSWebDVD](http://www.microsoft.com/downloads/details.aspx?familyid=5b8a8958-c3cd-4b24-85a2-1baacf92d218)  
(KB973815)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=11321f48-8997-4b99-982a-3ba4ad3f5992)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=ad55c653-ee6b-4c92-b7f4-3923bb916546)  
(существенный)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=4f625d39-29d4-44f9-b4bd-cd99f1ea422d)  
(существенный)
</td>
</tr>
<tr>
<th colspan="9">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://go.microsoft.com/fwlink/?linkid=157861)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://go.microsoft.com/fwlink/?linkid=155974)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://go.microsoft.com/fwlink/?linkid=155975)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://go.microsoft.com/fwlink/?linkid=158695)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://go.microsoft.com/fwlink/?linkid=155977)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://go.microsoft.com/fwlink/?linkid=155979)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://go.microsoft.com/fwlink/?linkid=157296)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://go.microsoft.com/fwlink/?linkid=157140)
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
Н/Д
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[RDP 6.0 в Windows Vista](http://www.microsoft.com/downloads/details.aspx?familyid=cf95a552-f6fd-4e35-815a-d16c015cd3ea)  
(KB956744)  
(существенный)  
[RDP 6.1 для Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=cf95a552-f6fd-4e35-815a-d16c015cd3ea)  
(KB956744)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=81fce7bd-f33c-4586-949d-ac40d415f755)  
(критический)
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media 11](http://www.microsoft.com/downloads/details.aspx?familyid=3766aed9-93f5-478e-a5bf-b7ee0b577088)  
(KB973540)  
(критический)  
[Компонент Windows ATL](http://www.microsoft.com/downloads/details.aspx?familyid=80de158d-157e-4c21-9154-c1dbd6e57cb3)  
(KB973507)  
(критический)  
[Элемент управления ActiveX объекта HtmlInput](http://www.microsoft.com/downloads/details.aspx?familyid=59fefa17-0ad4-4a62-82be-e6a2b7a0aec3)  
(KB973768)  
(критический)  
(только Media Center Edition 2005)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=979ac9da-940f-49e7-91a2-b12db3708076)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Vista](http://www.microsoft.com/downloads/details.aspx?familyid=00afd94c-b483-4155-884f-b617acca6e7d)  
(существенный)
</td>
<td style="border:1px solid black;">
Только Windows Vista: [Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1) и Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d42444bb-5030-4b47-87fa-9df3a8c640ff) (KB972591), а также [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=310f3aa6-c264-45a2-b24a-3f178b41830e)\*\*\*\*\* (KB972592)  
(существенный)  
Только Windows Vista с пакетом обновления 1 (SP1):  
[Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1) и Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593), а также [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f)\*\*\*\*\* (KB972594)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d77f406d-11cb-4d19-94ec-938b356c3427)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[RDP 6.0 в Windows Vista x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=5e19cef7-2413-4575-9597-c6273a097aad)  
(KB956744)  
(существенный)  
[RDP 6.1 в Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=5e19cef7-2413-4575-9597-c6273a097aad)  
(KB956744)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=a6cea61a-4ad9-4e18-bf18-348ae4ae51c4)  
(критический)
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media 11](http://www.microsoft.com/downloads/details.aspx?familyid=64edbd64-9faa-4f54-b0d5-836c683ca7cd)  
(KB973540)  
(критический)  
[Компонент Windows ATL](http://www.microsoft.com/downloads/details.aspx?familyid=82940d30-6a30-47ca-b184-2ac96e35c294)  
(KB973507)  
(критический)  
[Элемент управления ActiveX объекта HtmlInput](http://www.microsoft.com/downloads/details.aspx?familyid=92de8a2e-2d50-4278-937e-ccb862c5ab8f)  
(KB973768)  
(критический)  
(только Media Center Edition 2005)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b9aa04cc-a5c5-47ae-bf0f-250cff275d26)  
(средний)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=a0c698aa-a913-4981-8798-6bbb8cacfb86)  
(существенный)
</td>
<td style="border:1px solid black;">
Только Windows Vista x64 Edition: [Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1) и Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d42444bb-5030-4b47-87fa-9df3a8c640ff) (KB972591), а также [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=310f3aa6-c264-45a2-b24a-3f178b41830e)\*\*\*\*\* (KB972592)  
(существенный)  
Только Windows Vista x64 Edition с пакетом обновления 1 (SP1)  
[Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1) и Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593), а также [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7a41b8c1-f955-474e-a08e-5e73964327d1)  
(средний)
</td>
</tr>
<tr>
<th colspan="9">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://go.microsoft.com/fwlink/?linkid=157861)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://go.microsoft.com/fwlink/?linkid=155974)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://go.microsoft.com/fwlink/?linkid=155975)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://go.microsoft.com/fwlink/?linkid=158695)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://go.microsoft.com/fwlink/?linkid=155977)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://go.microsoft.com/fwlink/?linkid=155979)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://go.microsoft.com/fwlink/?linkid=157296)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://go.microsoft.com/fwlink/?linkid=157140)
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
Н/Д
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Н/Д
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
Windows Server 2008 для 32-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем
</td>
<td style="border:1px solid black;">
[RDP 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=71c17a87-710b-434d-9b2a-2f471674915a)\*\*  
(KB956744)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=fdc96a07-ed79-4798-8077-b2e9ca64cd0f)\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media 11](http://www.microsoft.com/downloads/details.aspx?familyid=85d9e69f-99a2-467f-bf37-4b47466a12d4)\*\*  
(KB973540)  
(критический)  
[Компонент Windows ATL](http://www.microsoft.com/downloads/details.aspx?familyid=ba423491-6c29-49f2-811b-ac3f9bbc58fc)\*  
(KB973507)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=24c77c27-0b7d-4a35-a871-b453f90e5913)\*  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Только Windows Server 2008 для 32-разрядных систем: [Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1) и Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593), а также [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)\*\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 для 32-разрядных систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=62f2e0a6-5e68-41c7-a851-d99bcff6ff3e)\*  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем
</td>
<td style="border:1px solid black;">
[RDP 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=f095d2d5-4513-4ae1-96c7-cbcf83304261)\*\*  
(KB956744)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных (x64) систем и Windows Server 2008 для 64-разрядных (x64) систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8e3afba4-6761-4b3d-98bb-4b4145e27b7f)\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Проигрыватель Windows Media 11](http://www.microsoft.com/downloads/details.aspx?familyid=9501c8c2-a526-4661-8cba-7847bace1aa0)\*\*  
(KB973540)  
(критический)  
[Компонент Windows ATL](http://www.microsoft.com/downloads/details.aspx?familyid=b9311953-889a-415f-a396-250a005e95cd)\*  
(KB973507)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных (x64) систем и Windows Server 2008 для 64-разрядных (x64) систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=48d0432e-704a-4bbb-b0a1-cd14069a8e93)\*  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Только Windows Server 2008 для 64-разрядных систем: [Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1) и Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593), а также [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)\*\*  
(существенный)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных (x64) систем и Windows Server 2008 для 64-разрядных (x64) систем с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6e5d1db9-efef-4112-8138-62f14670cf0d)\*  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для систем на базе процессоров Itanium и Windows Server 2008 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium
</td>
<td style="border:1px solid black;">
[RDP версии 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=65d0af4e-22a2-4524-a003-2f4858012fa8)  
(KB956744)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для систем на базе процессоров Itanium и Windows Server 2008 для систем на базе процессоров Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=aa1bb13a-5905-48c4-8e74-a41104593046)  
(критический)
</td>
<td style="border:1px solid black;">
[Компонент Windows ATL](http://www.microsoft.com/downloads/details.aspx?familyid=e5612bb4-5f37-4b38-bd2e-f198c413371c)  
(KB973507)  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для систем на базе процессоров Itanium и Windows Server 2008 для систем на базе процессоров Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c119223c-f4e0-449b-8e7b-a6bf11c98f94)  
(средний)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
Только Windows Server 2008 для систем на базе процессоров Itanium: [Microsoft .NET Framework 2.0 с пакетом обновления 1 (SP1) и Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593), а также [Microsoft .NET Framework 2.0 с пакетом обновления 2 (SP2) и Microsoft .NET Framework 3.5 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)  
(существенный
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для систем на базе процессоров Itanium и Windows Server 2008 для систем на базе процессоров Itanium с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4b813c74-b2ae-4962-9ebb-1311193d9e2d)  
(средний)
</td>
</tr>
</table>
 
**Примечания для Windows Server 2008**

**\*Уязвимости подвержены ОС Windows Server 2008, при развертывании которых устанавливалось только ядро сервера.** Это обновление имеет одинаковый уровень опасности для поддерживаемых версий Windows Server 2008, независимо от того, выбиралась ли при их развертывании установка только ядра сервера или нет. Дополнительные сведения об этом варианте установки см. в [этой статье](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\* Не подверженные уязвимости системы Windows Server 2008, при развертывании которых выбиралась установка основных компонентов сервера.** Поддерживаемые выпуски Windows Server 2008, при развертывании которых выбиралась установка только ядра сервера, не подвержены уязвимостям, устраняемым этим обновлением. Дополнительные сведения об этом варианте установки см. в [этой статье](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Примечания к бюллетеню MS09-044**

**\*\*\***Пользователи RDP 5.0 на базе Microsoft Windows 2000 с пакетом обновления 4 (SP4) должны установить как KB958471, так и KB958470.

**\*\*\*\***Администраторы могли вручную установить это обновление как отдельную загрузку.

Дополнительные файлы обновления с этим идентификационным номером бюллетеня см. также в подразделе "Клиентское ПО для Mac" этого раздела, **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

**Примечание к бюллетеню MS09-036**

**\*\*\*\*\***Поскольку службы IIS 7.0 не работают в Windows Vista Starter и Windows Vista Home Basic, этой уязвимости не подвержены следующие версии: Windows Vista Starter (32-разрядная), Windows Vista Home Basic (32-разрядная) и Windows Vista Home Basic (64-разрядная).

#### Клиентское ПО для Mac

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Удаленный рабочий стол
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://go.microsoft.com/fwlink/?linkid=157861)
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
Клиент подключения к удаленному рабочему столу для Mac
</td>
<td style="border:1px solid black;">
[Клиент подключения к удаленному рабочему столу для Mac 2.0](http://www.microsoft.com/downloads/details.aspx?familyid=cd9ec77e-5b07-4332-849f-046611458871)**\***  
(существенный)
</td>
</tr>
</table>
 
**Примечания к бюллетеню MS09-044**

**\***Данный загружаемый файл обновляет клиент подключения к удаленному рабочему столу для Mac 2.0 до клиента подключения к удаленному рабочему столу для Mac 2.0.1, который устраняет указанную уязвимость.

Дополнительные файлы обновления с этим идентификационным номером бюллетеня см. также в подразделе "Операционная система и компоненты Windows" в этого раздела, **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

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
Наборы приложений, системы и компоненты Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://go.microsoft.com/fwlink/?linkid=128110)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580)  
(KB947320)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=95c94c9a-6aca-42fb-9679-3234f06c72f7)  
(KB947319)  
(критический)
</td>
</tr>
<tr>
<th colspan="2">
Веб-компоненты Microsoft Office
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://go.microsoft.com/fwlink/?linkid=128110)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Веб-компоненты Microsoft Office 2000
</td>
<td style="border:1px solid black;">
[Веб-компоненты Microsoft Office 2000 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580)  
(KB947320)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Веб-компоненты Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Веб-компоненты Microsoft Office XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580)  
(KB947320)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Веб-компоненты Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Веб-компоненты Microsoft Office 2003 с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=95c94c9a-6aca-42fb-9679-3234f06c72f7)  
(KB947319)  
(критический)  
[Веб-компоненты Microsoft Office 2003 с пакетом обновления 1 (SP1) для выпуска 2007 системы Microsoft Office](http://www.microsoft.com/downloads/details.aspx?familyid=644008e0-77c9-4a02-ac9b-e30d0930c4be)\*  
(KB947318)  
(критический)
</td>
</tr>
<tr>
<th colspan="2">
Другое программное обеспечение Microsoft Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://go.microsoft.com/fwlink/?linkid=128110)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Small Business Accounting 2006
</td>
<td style="border:1px solid black;">
[Microsoft Office Small Business Accounting 2006](http://www.microsoft.com/downloads/details.aspx?familyid=0d77ddb3-4d34-4cfe-913b-d05981f59a82)  
(KB968377)  
(критический)
</td>
</tr>
</table>
 
**Примечания к бюллетеню MS09-043**

**\***В SQL Server 2008 и Microsoft Forefront Threat Management Gateway Medium Business Edition повторно включен уязвимый компонент веб-компонентов Office 2003 для выпуска 2007 системы Microsoft Office. Таким образом, обновление для веб-компонентов Office 2003 для Microsoft Office 2007 автоматически предлагается и пользователям SQL Server 2008 и Microsoft Forefront Threat Management Gateway Medium Business Edition.

Дополнительные файлы обновления с этим идентификационным номером бюллетеня см. также в других подразделах этого раздела, **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Программное обеспечение и средства разработки Microsoft

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://go.microsoft.com/fwlink/?linkid=128110)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=ba2915a0-f5f4-4e18-b0c0-534d2a948585)  
(KB969172)  
(критический)
</td>
</tr>
</table>
 
**Примечание к бюллетеню MS09-043**

Дополнительные файлы обновления с этим идентификационным номером бюллетеня см. также в других подразделах этого раздела, **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

#### Серверное программное обеспечение Майкрософт и программы для обеспечения безопасности

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Internet Security and Acceleration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://go.microsoft.com/fwlink/?linkid=128110)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration (ISA) Server 2004 Standard Edition с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326)\*  
(KB947826)  
(критический)  
[Microsoft Internet Security and Acceleration Server 2004 Enterprise Edition с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326)  
(KB947826)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration (ISA) Server 2006 Standard Edition с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326)  
(KB947826)  
(критический)  
[Microsoft Internet Security and Acceleration (ISA) Server 2006 Enterprise Edition с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326)  
(KB947826)  
(критический)
</td>
</tr>
<tr>
<th colspan="2">
Сервер Microsoft BizTalk Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификационный номер бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://go.microsoft.com/fwlink/?linkid=128110)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2002
</td>
<td style="border:1px solid black;">
[Microsoft BizTalk Server 2002](http://www.microsoft.com/downloads/details.aspx?familyid=495839b6-0322-4755-997d-4a7762c53333)  
(KB971388)  
(критический)
</td>
</tr>
</table>
 
**Примечания к бюллетеню MS09-043**

\*Microsoft ISA Server 2004 Standard Edition предоставляется как автономный продукт. Microsoft ISA Server 2004 Standard Edition также предоставляется как компонент серверов Windows Small Business Server 2003 Premium Edition с пакетом обновления 1 (SP1) и Windows Small Business Server 2003 R2 Premium Edition.

Дополнительные файлы обновления с этим идентификационным номером бюллетеня см. также в других подразделах этого раздела, **Продукты, подверженные уязвимости, и соответствующие обновления**. Это бюллетень относится к нескольким категориям ПО.

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
**В центре безопасности**

Управление программным обеспечением и обновлениями для системы безопасности для установки на серверы, настольные и переносные компьютеры организации. Дополнительные сведения см. на веб-узле [центра TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [Центр безопасности TechNet](http://go.microsoft.com/fwlink/?linkid=21171) содержит дополнительные сведения о безопасности в продуктах Майкрософт. Доступ к этим сведениям можно также получить, посетив веб-сайт [Безопасность дома](http://go.microsoft.com/fwlink/?linkid=85102) и щелкнув ссылку "Последние обновления".

Обновления для системы безопасности доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747) и [Центре обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130). Обновления для системы безопасности также доступны на веб-узле [центра загрузки Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".

Наконец, обновления для системы безопасности можно загрузить из [каталога Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=96155). Он обеспечивает возможность поиска содержимого (в том числе обновлений для системы безопасности, драйверов и пакетов обновления), которое предоставляется через Центр обновления Windows и Центр обновления Майкрософт. При поиске по номеру бюллетеня по безопасности (например, MS07-036) можно добавлять необходимые обновления (в том числе на различных языках) в корзину и загружать их в указанную папку. Дополнительные сведения см. на веб-сайте каталога Центра обновления Майкрософт в разделе [вопросов и ответов](http://go.microsoft.com/fwlink/?linkid=97900).

**Примечание**. С 1 августа 2009 г. Майкрософт прекратила поддержку центра загрузки Office и средства инвентаризации центра загрузки Office. Чтобы продолжить получать последние обновления для продуктов Microsoft Office, используйте веб-сайт [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747). Дополнительные сведения см. на веб-странице [Центр загрузки Microsoft Office: вопросы и ответы](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Руководство по диагностике и развертыванию**

Корпорация Майкрософт предоставляет руководство по диагностике и развертыванию обновлений для системы безопасности. В этом руководстве содержатся рекомендации и сведения, позволяющие ИТ-специалистам оптимальнее использовать различные средства для диагностики и развертывания обновлений для системы безопасности. Дополнительные сведения см. в [статье 961747 базы знаний Майкрософт](http://support.microsoft.com/kb/961747).

**Анализатор безопасности Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений безопасности и стандартных ошибок в конфигурации системы безопасности. Дополнительные сведения об анализаторе безопасности MBSA см. на веб-сайте [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Службы Windows Server Update Services**

Службы Windows Server Update Services (WSUS) позволяют администраторам быстро и надежно развертывать последние критические обновления и обновления безопасности для операционных систем Windows 2000 и более поздних версий Windows, для Office XP и более поздних версий Office, для Exchange Server 2003 и для SQL Server 2000 на системах Windows 2000 и более поздних версиях операционных систем.

Дополнительные сведения о развертывании данного обновления для системы безопасности с помощью служб Windows Server Update Services см. на веб-узле [Службы Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) (на английском языке).

**Сервер Systems Management Server**

Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет хорошо сконфигурированное решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей. Последний выпуск сервера SMS — System Center Configuration Manager 2007 — доступен для загрузки; сведения о нем см. также на веб-сайте [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Дополнительные сведения о том, как администраторы могут использовать сервер SMS 2003 для развертывания обновлений для системы безопасности, см. на веб-странице [Управление исправлениями для системы безопасности сервера SMS 2003](http://go.microsoft.com/fwlink/?linkid=22939). Для развертывания обновлений системы безопасности пользователям сервера SMS 2.0 доступно средство Security Update Inventory Tool (SUIT). Дополнительные сведения о сервере SMS см. на веб-узле [Сервер Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) (на английском языке).

**Примечание**. Для предоставления широкой поддержки при определении необходимости применения и развертывания обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используется средство Microsoft Baseline Security Analyzer. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. на веб-узле [Развертывание обновлений программного обеспечения с помощью функции распространения программ сервера SMS](http://go.microsoft.com/fwlink/?linkid=33341) (на английском языке). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакетов [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) и [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

**Средство оценки совместимости обновлений и набор средств для обеспечения совместимости приложений**

Часто обновления записываются в одни те же файлы, а для запуска приложений требуется настроить параметры реестра. Это приводит к возникновению несовместимостей и увеличивает время, затрачиваемое на развертывание обновлений для системы безопасности. Облегчить тестирование и проверку обновлений Windows для установленных приложений можно с помощью [компонентов оценки совместимости обновлений](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true), входящих в состав [набора средств для обеспечения совместимости приложений](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Набор средств для обеспечения совместимости приложений содержит необходимые средства и документацию для выявления проблем совместимости приложений и уменьшения степени воздействия этих проблем перед развертыванием системы Microsoft Windows Vista, обновлений из Центра обновления Windows, обновлений с веб-сайта безопасности Майкрософт или новой версии проводника.

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

#### Высокоприоритетные обновления, не относящиеся к безопасности и распространяемые через Центры MU, WU и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-сайте Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт:](http://support.microsoft.com/kb/894199) Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
-   [Новые, исправленные и выпущенные обновления для продуктов Майкрософт, отличных от Microsoft Windows](http://technet.microsoft.com/en-us/wsus/dd573344.aspx).

#### Microsoft Active Protections Program (MAPP)

Чтобы повысить уровень защиты пользователей, корпорация Майкрософт предоставляет сведения об уязвимостях крупным поставщикам программного обеспечения безопасности перед ежемесячным выпуском обновлений. Эта информация необходима им для усовершенствования программного обеспечения и оборудования для защиты пользователей (антивирусных программ, сетевых систем обнаружения вторжений, а также индивидуальных систем предотвращения вторжений). Сведения о новых средствах защиты, предоставляемых поставщиками программного обеспечения безопасности, доступны на соответствующих веб-сайтах партнеров, перечисленных в списке партнеров [MAPP](http://www.microsoft.com/security/msrc/mapp/partners.mspx).

#### Стратегии безопасности и сообщество

**Стратегии управления обновлениями**

В статье [Рекомендации по безопасности для управления обновлениями](http://go.microsoft.com/fwlink/?linkid=21168) содержатся дополнительные сведения о рекомендациях Майкрософт по установке обновлений для системы безопасности.

**Другие обновления для системы безопасности**

Другие обновления безопасности можно загрузить из следующих источников:

-   Обновления для системы безопасности доступны на веб-узле [центра загрузки Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".
-   Обновления для индивидуальных пользователей доступны на веб-узле [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747).
-   Обновления для системы безопасности, доступные в этом месяце на веб-узле Центра обновления Windows, можно получить в виде файлов образа компакт-диска с выпусками обновлений для системы безопасности в Центре загрузки Майкрософт. Дополнительные сведения см. в [статье 913086 базы знаний Майкрософт](http://support.microsoft.com/kb/913086).

**Сообщество ИТ-специалистов, занимающихся вопросами безопасности**

На веб-сайте [сообщества ИТ-специалистов, занимающихся вопросами безопасности](http://go.microsoft.com/fwlink/?linkid=21164), можно найти сведения о способах улучшения системы безопасности и оптимизации ИТ-инфраструктуры предприятия, а также обсудить вопросы безопасности с другими ИТ-специалистами.

#### Благодарности

Корпорация Майкрософт [благодарит](http://go.microsoft.com/fwlink/?linkid=21127) за проведенную совместно работу по защите пользователей:

-   Александра Пфандта (Alexander Pfandt) из [Digitiria](http://www.digitaria.com/) за сообщение об уязвимости, описанной в бюллетене MS09-036
-   Райана Смита (Ryan Smith) и Алекса Уилера (Alex Wheeler) из [IBM ISS X-Force](http://www.iss.net/) за первое сообщение о проблеме, описанной в бюллетене MS09-037
-   Роберта Фримена (Robert Freeman) из [IBM ISS X-Force](http://www.iss.net/) за сообщение о проблеме, описанной в бюллетене MS09-037
-   Дэвида Дьюи (David Dewey) из [IBM ISS X-Force](http://www.iss.net/) за сообщение о проблеме, описанной в бюллетене MS09-037
-   Шона Ларссона (Sean Larsson) из [VeriSign iDefense Labs](http://labs.idefense.com/) за сообщение о двух проблемах, описанных в бюллетене MS09-037
-   Виная Анантарамана (Vinay Anantharaman) из [Adobe Systems Inc.](http://www.adobe.com/) за сообщение о двух уязвимостях, описанных в бюллетене MS09-038
-   Компанию [TippingPoint](http://www.tippingpoint.com/) и команду, работающую над проектом [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в бюллетене MS09-039
-   Ли Гень (LiGen) из [Национального университета технологий защиты](http://english.nudt.edu.cn/) за сообщение о проблеме, описанной в бюллетене MS09-039
-   Никиту Тараканова из [Positive Technologies Research Team](http://en.securitylab.ru/lab/) за сообщение о проблеме, описанной в бюллетене MS09-040
-   Коди Пирс (Cody Pierce) из [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) за сообщение о проблеме, описанной в бюллетене MS09-041
-   Петера Врёгденила (Peter Vreugdenhil), работающего над проектом [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о двух проблемах, описанных в бюллетене MS09-043
-   Петера Врёгденила (Peter Vreugdenhil), работающего над проектом [Zero Day Initiative](http://www.zerodayinitiative.com/), и Хайфей Ли (Haifei Li) из [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) (Fortinet) за сообщение о проблеме, описанной в бюллетене MS09-043
-   Шона Ларссона (Sean Larsson) из [VeriSign iDefense Labs](http://labs.idefense.com/) за сообщение о проблеме, описанной в бюллетене MS09-043
-   Вуши (Wushi) из [Team509](http://www.team509.com/), работающего над проектом Zero Day Initiative, за сообщение об уязвимости, описанной в бюллетене MS09-044
-   Ямату Ли (Yamata Li) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение о проблеме, описанной в бюллетене MS09-044

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Пользователи из США и Канады могут обратиться в службу [поддержки по вопросам безопасности](http://go.microsoft.com/fwlink/?linkid=21131) или позвонить по телефону 1-866-PCSAFETY. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Дополнительные сведения о вариантах поддержки см. на веб-сайте [справки и поддержки корпорации Майкрософт](http://support.microsoft.com?ln=ru).
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-узел международной поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Версия 1.0 (11 августа 2009 г.). Обзор бюллетеней опубликован.
-   Версия 1.1 (13 августа 2009 г.). В соответствии с MS09-044 для данного бюллетеня исправлен список обновлений RDP для Windows XP с пакетом обновления 2 (SP2) и Windows XP с пакетом обновления 3 (SP3). Изменены указания о необходимости перезагрузки для MS09-037, MS09-042 и MS09-044.
-   Вер. 2.0 (25 августа 2009 г.) Для MS09-044 исправлена ссылка для загрузки клиента RDP 5.2 для Windows XP с пакетом обновления 2 (SP2) (KB958469). Кроме того, исправлена сноска с неверной последовательностью установки для обновлений KB958471 и KB958470. Пользователям, успешно установившим эти обновления, не нужно их переустанавливать.
-   Вер. 3.0 (8 сентября 2009 г.) Повторная публикация бюллетеня MS09-037 связана с выпуском новых обновлений для элемента управления ActiveX объекта HtmlInput в Windows XP Media Center Edition 2005 и во всех поддерживаемых версиях Windows Vista.
-   Вер. 4.0 (27 октября 2009 г.) Корпорация Майкрософт повторно опубликовала бюллетень MS09-043, чтобы еще раз предложить обновление для Microsoft Office 2003 с пакетом обновления 3 (SP3) и веб-компонентов Microsoft Office 2003 с пакетом обновления 3 (SP3) для устранения проблемы обнаружения. Это обновление касается только изменения способа обнаружения. Оно не вносит изменения в двоичные файлы. Пользователям, уже обновившим системы, повторно устанавливать это обновление не требуется.

*Built at 2014-04-18T01:50:00Z-07:00*
