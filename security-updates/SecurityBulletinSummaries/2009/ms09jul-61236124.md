---
TOCTitle: 'MS09-JUL'
Title: 'Обзор бюллетеней по безопасности (Майкрософт) за я Июль 2009 г.'
ms:assetid: 'ms09-jul'
ms:contentKeyID: 61236124
ms:mtpsurl: 'https://technet.microsoft.com/ru-RU/library/ms09-jul(v=Security.10)'
---

Security Bulletin Summary

Обзор бюллетеней по безопасности (Майкрософт) за я Июль 2009 г.
===============================================================

Дата публикации: 14 июля 2009 г. | Дата обновления: 3 сентября 2010 г.

**Версия:** 8.0

В этом обзоре описаны бюллетени по безопасности, выпущенные в июле 2009 г.

В связи с выпуском бюллетеней за июль 2009 года настоящий обзор заменяет предварительное уведомление о бюллетенях, первоначально выпущенное 9 июля 2009 года, и предварительное уведомление о внеплановых бюллетенях, впервые опубликованное 24 июля 2009 года. Дополнительные сведения о службе предварительного уведомления см. [на веб-сайте службы предварительного уведомления о бюллетенях по безопасности Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Дополнительные сведения о том, как получать автоматические уведомления о выпуске бюллетеней Майкрософт по безопасности, см. на веб-странице [уведомлений по безопасности Microsoft TechNet](http://go.microsoft.com/fwlink/?linkid=21163).

15 июля 2009 г. в 11:00 по тихоокеанскому времени (для США и Канады) специалисты корпорации Майкрософт провели веб-трансляцию, в ходе которой ответили на вопросы пользователей, касающиеся плановых бюллетеней. Эта веб-трансляция доступна для просмотра по требованию. Дополнительные сведения см. на веб-сайте [обзоров и веб-трансляций, посвященных бюллетеням Майкрософт по безопасности](http://technet.microsoft.com/security/bulletin/summary).

Что же касается внеплановых бюллетеней MS09-034 и MS09-035, добавленных в версии 2.0 настоящего обзора, то 28 июля 2009 года в 13:00 и в 16:00 по тихоокеанскому времени (США и Канада) специалисты Майкрософт проведут веб-трансляцию, в ходе которой ответят на вопросы пользователей об этих бюллетенях. Зарегистрируйтесь прямо сейчас, чтобы 28 июля участвовать в веб-трансляции, намеченной [на 13:00](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422339&culture=en-us) и [на 16:00](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422341&culture=en-us) по тихоокеанскому времени. Позже это можно будет сделать только по запросу. Дополнительные сведения см. на веб-сайте [обзоров и веб-трансляций, посвященных бюллетеням Майкрософт по безопасности](http://technet.microsoft.com/security/bulletin/summary).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139788">MS09-029</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в обработчике шрифтов EOT делают возможным удаленное выполнение кода (961371)</strong><br />
<br />
Данное обновление для системы безопасности устраняет две обнаруженных пользователями уязвимости в компоненте Microsoft Windows — обработчике шрифтов Embedded OpenType (EOT). Эти уязвимости делают возможным удаленное выполнение кода. Воспользовавшись любой из этих уязвимостей, злоумышленник может получить полный удаленный контроль над уязвимой системой. что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=152887">MS09-028</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в Microsoft DirectShow делают возможным удаленное выполнение кода (971633)</strong><br />
<br />
Это обновление для системы безопасности устраняет одну опубликованную и две обнаруженные пользователями уязвимости в компоненте Microsoft DirectShow. Эти уязвимости делают возможным удаленное выполнение кода, если пользователь открывает особым образом созданный файл мультимедиа QuickTime. Злоумышленник, успешно воспользовавшийся любой из этих уязвимостей, может получить те же права, которыми обладает локальный пользователь. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=157386">MS09-032</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности, устанавливающее флаг блокировки для элемента ActiveX (973346)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость, случаи использования которой зафиксированы на настоящий момент. Уязвимость в элементе управления Microsoft Video ActiveX делает возможным удаленное выполнение кода, если пользователь при просмотре особым образом созданной веб-страницы в Internet Explorer создает экземпляр этого элемента управления ActiveX. Данный элемент управления ActiveX никогда не предназначался для использования в Internet Explorer. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158199">MS09-034</a></td>
<td style="border:1px solid black;"><strong>Накопительное обновление для системы безопасности Internet Explorer (972260)</strong><br />
<br />
Выпуск данного внепланового обновления для систем безопасности сопровождается выпуском бюллетеня по безопасности Microsoft MS09-035, описывающего уязвимости в компонентах и элементах управления, разработанных с использованием уязвимых версий библиотеки Microsoft ATL. Являясь эффективной мерой защиты, данное обновление для системы безопасности Internet Explorer позволяет частично блокировать известные направления атак через Internet Explorer, использующие компоненты и элементы управления , разработанные с использованием уязвимых версий библиотеки ATL (подробности см. в выпуске 973882 советов Майкрософт по безопасности и в бюллетене по безопасности Microsoft MS09-035).<br />
<br />
Данное обновление также устраняет три обнаруженные пользователями уязвимости в Internet Explorer. Данные уязвимости делают возможным удаленное выполнение кода при открытии специально созданной веб-страницы в браузере Internet Explorer. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Критический</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=153891">MS09-033</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Virtual PC и Virtual Server делает возможным несанкционированное расширение прав (969856)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Virtual PC и Microsoft Virtual Server. Злоумышленник, успешно воспользовавшийся этой уязвимостью, может выполнить произвольный код и получить полный контроль над гостевой операционной системой. что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Virtual PC, Virtual Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=154993">MS09-031</a></td>
<td style="border:1px solid black;"><strong>Уязвимость в Microsoft ISA Server 2006 делает возможным несанкционированное получение прав (970953)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость в Microsoft Internet Security and Acceleration (ISA) Server 2006. Эта уязвимость может привести к несанкционированному получению прав, если злоумышленнику удастся успешно подделать учетную запись пользователя с правами администратора для сервера ISA Server, на котором настроена проверка подлинности с помощью одноразового пароля (OTP) Radius и делегирование проверки подлинности с помощью ограниченного делегирования Kerberos.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Несанкционированное получение прав</td>
<td style="border:1px solid black;">Требуется перезагрузка</td>
<td style="border:1px solid black;">Microsoft ISA Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=147424">MS09-030</a></td>
<td style="border:1px solid black;"><strong>Уязвимость приложения Microsoft Office Publisher делает возможным удаленное выполнение кода (969516)</strong><br />
<br />
Это обновление для системы безопасности устраняет обнаруженную пользователями уязвимость приложения Microsoft Office Publisher, которая делает возможным удаленное выполнение кода, если пользователь открывает специально созданный файл Publisher. Воспользовавшись этой уязвимостью, злоумышленник может захватить полный контроль над системой, что позволит ему устанавливать программы, просматривать, изменять и уничтожать данные или создавать новые учетные записи с неограниченными полномочиями. Риск для пользователей, учетные записи которых имеют ограниченные права, меньше, чем для пользователей, работающих с правами администратора.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Существенный</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a></td>
<td style="border:1px solid black;"><strong>Уязвимости в библиотеке ATL среды Microsoft Visual Studio делают возможным удаленное выполнение кода (969706)</strong><br />
<br />
Это обновление для системы безопасности устраняет несколько обнаруженных пользователями уязвимостей в публичных версиях библиотеки ATL, входящих в состав Visual Studio. Данное обновление предназначено специально для разработчиков программных компонентов и элементов управления. Разработчики, занимающиеся сборкой и распространением программных компонентов и элементов управления с использованием библиотеки ATL, должны установить настоящее обновление и следовать содержащимся в этом бюллетене инструкциям, с тем чтобы гарантировать отсутствие описанных здесь уязвимостей в создаваемых и поставляемых ими компонентах и элементах управления.<br />
<br />
Данный бюллетень по безопасности посвящен уязвимостям, делающим возможным удаленное выполнение кода при загрузке компонентов или элементов управления, разработанных с помощью уязвимых версий библиотеки ATL.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Средний</a><br />
Удаленное выполнение кода</td>
<td style="border:1px solid black;">Может потребоваться перезагрузка</td>
<td style="border:1px solid black;">Microsoft Visual Studio</td>
</tr>
</tbody>
</table>
  
Индекс использования уязвимостей  
--------------------------------
  
<span></span>
В указанной ниже таблице приведены сведения об оценке использования уязвимостей, устраняемых в этом месяце. Уязвимости сгруппированы по идентификаторам бюллетеней и кодам CVE.
  
**Как пользоваться этой таблицей?**
  
Используйте эту таблицу, чтобы узнать о вероятности появления стабильно работающего кода эксплойта в течение 30 дней после выпуска бюллетеня по каждому из обновлений для системы безопасности, которые необходимо установить. Перед назначением приоритетов развертывания ознакомьтесь с каждой приведенной ниже оценкой, относящейся к конкретной конфигурации. Дополнительные сведения об уровнях опасности и способах их определения см. в [индексе использования уязвимостей](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| Идентификатор бюллетеня                                   | Название бюллетеня                                                                                                 | Код CVE                                                                          | Оценка индекса использования уязвимостей                                                                                        | Краткие примечания                                                                       |  
|-----------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|  
| [MS09-028](http://go.microsoft.com/fwlink/?linkid=152887) | Уязвимости в Microsoft DirectShow делают возможным удаленное выполнение кода (971633)                              | [CVE-2009-1537](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1537) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование стабильного кода эксплойта          | **На данный момент известны примеры использования этой уязвимости в Интернете.**         |  
| [MS09-028](http://go.microsoft.com/fwlink/?linkid=152887) | Уязвимости в Microsoft DirectShow делают возможным удаленное выполнение кода (971633)                              | [CVE-2009-1538](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1538) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование стабильного кода эксплойта          | (Нет)                                                                                    |  
| [MS09-028](http://go.microsoft.com/fwlink/?linkid=152887) | Уязвимости в Microsoft DirectShow делают возможным удаленное выполнение кода (971633)                              | [CVE-2009-1539](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1539) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование стабильного кода эксплойта          | (Нет)                                                                                    |  
| [MS09-029](http://go.microsoft.com/fwlink/?linkid=139788) | Уязвимости в обработчике шрифтов EOT делают возможным удаленное выполнение кода (961371)                           | [CVE-2009-0231](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0231) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование стабильного кода эксплойта          | (Нет)                                                                                    |  
| [MS09-029](http://go.microsoft.com/fwlink/?linkid=139788) | Уязвимости в обработчике шрифтов EOT делают возможным удаленное выполнение кода (961371)                           | [CVE-2009-0232](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0232) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование стабильного кода эксплойта          | (Нет)                                                                                    |  
| [MS09-030](http://go.microsoft.com/fwlink/?linkid=147424) | Уязвимость приложения Microsoft Office Publisher делает возможным удаленное выполнение кода (969516)               | [CVE-2009-0566](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0566) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование стабильного кода эксплойта          | (Нет)                                                                                    |  
| [MS09-031](http://go.microsoft.com/fwlink/?linkid=154993) | Уязвимость в Microsoft ISA Server 2006 делает возможным несанкционированное получение прав (970953)                | [CVE-2009-1135](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1135) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование стабильного кода эксплойта          | (Нет)                                                                                    |  
| [MS09-032](http://go.microsoft.com/fwlink/?linkid=157386) | Накопительное обновление для системы безопасности, устанавливающее флаги блокировки для элементов ActiveX (973346) | [CVE-2008-0015](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0015) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование стабильного кода эксплойта          | **На данный момент известны примеры использования этой уязвимости в Интернете.**         |  
| [MS09-033](http://go.microsoft.com/fwlink/?linkid=153891) | Уязвимость в Virtual PC и Virtual Server делает возможным несанкционированное расширение прав (969856)             | [CVE-2009-1542](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1542) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование нестабильного кода эксплойта        | Выполнение рабочего кода может привести к несогласованным результатам использования.     |  
| [MS09-034](http://go.microsoft.com/fwlink/?linkid=158199) | Накопительное обновление для системы безопасности Internet Explorer (972260)                                       | [CVE-2009-1917](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1917) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование стабильного кода эксплойта          | Выполнение рабочего кода отличается простотой и надежностью.                             |  
| [MS09-034](http://go.microsoft.com/fwlink/?linkid=158199) | Накопительное обновление для системы безопасности Internet Explorer (972260)                                       | [CVE-2009-1918](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1918) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование нестабильного кода эксплойта        | Выполнение рабочего кода может привести к несогласованным результатам использования.     |  
| [MS09-034](http://go.microsoft.com/fwlink/?linkid=158199) | Накопительное обновление для системы безопасности Internet Explorer (972260)                                       | [CVE-2009-1919](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1919) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование нестабильного кода эксплойта        | Выполнение рабочего кода может привести к несогласованным результатам использования.     |  
| [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131) | Уязвимости в библиотеке ATL среды Microsoft Visual Studio делают возможным удаленное выполнение кода (969706)      | [CVE-2009-0901](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование стабильного кода эксплойта          | Выполнение рабочего кода отличается простотой и надежностью.                             |  
| [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131) | Уязвимости в библиотеке ATL среды Microsoft Visual Studio делают возможным удаленное выполнение кода (969706)      | [CVE-2009-2493](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — возможно существование стабильного кода эксплойта          | Выполнение рабочего кода отличается простотой и надежностью.                             |  
| [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131) | Уязвимости в библиотеке ATL среды Microsoft Visual Studio делают возможным удаленное выполнение кода (969706)      | [CVE-2009-2495](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2495) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — существование функционирующего кода эксплойта маловероятно | Ошибка может привести только к утечке информации и никак не затрагивает выполнение кода. |
  
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
</tr>
<tr>
<th colspan="5">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://go.microsoft.com/fwlink/?linkid=158199)
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
Н/Д
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 с пакетом обновления 4 (SP4)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=1efbbd95-cd72-43df-b1ce-7e2b0c0cb9e2)  
(критический)
</td>
<td style="border:1px solid black;">
[DirectX 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=e3e54348-6548-4162-b4c0-9910ec6e18b3)  
(критический)  
[DirectX 8.1](http://www.microsoft.com/downloads/details.aspx?familyid=ce297c3e-8122-4276-a9c2-d1a404f8028d)\*\*\*  
(критический)  
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=862db2ad-3c1f-4a26-af70-d8c4f5a69dda)\*\*\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=89d941f0-3f71-46e3-8096-716561396b72)  
(без уровня опасности\*\*)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 с пакетом обновления 4 (SP4)](http://www.microsoft.com/downloads/details.aspx?familyid=50ffc8f4-7ab7-4e64-9965-5767db5f53cd)  
(критический)  
[Microsoft Internet Explorer 6 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=93bd1baa-e2fb-4e8c-9dd7-738efef32282)  
(критический)
</td>
</tr>
<tr>
<th colspan="5">
ОС Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://go.microsoft.com/fwlink/?linkid=158199)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP с пакетом обновления 2 (SP2) или 3 (SP3)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2) и Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=6914167b-6961-480c-a4d4-808cd58a035b)  
(критический)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=09d585cb-481d-4767-875e-9c6ebe456b80)\*\*\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP с пакетом обновления 2 (SP2) и Windows XP с пакетом обновления 3 (SP3)](http://www.microsoft.com/downloads/details.aspx?familyid=24701af8-b87e-4e85-9463-f50755a1b6ad)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=22bed634-5227-4a22-8df5-801f3e2e232a)  
(критический)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=c874c8f8-0449-42b1-8d8b-901040069568)  
(критический)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0acc8aaa-0ae1-412a-9f2b-dc7c707cae00)  
(критический)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3b8b019e-e6d8-4ce2-8f1f-3a6399b252d1)  
(критический)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=f8cd4803-82da-467c-8cb1-520f5a6021d4)\*\*\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=2cbf3699-7f79-4006-99e9-0a4c0d394c48)  
(критический)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=35ab0c5e-df3d-4873-8139-d1d98b3ac350)  
(критический)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=113cc76a-c434-42ff-b594-4834989ad5ba)  
(критический)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=29c8d9e6-2cb8-42b6-b0a6-2510fdb49eab)  
(критический)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://go.microsoft.com/fwlink/?linkid=158199)
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
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=018ef53d-f78e-4084-940d-7c86bf59d83c)  
(критический)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=571d57c5-1ef8-4dc4-a1e5-2211a805f0cc)\*\*\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=b0a458d6-c34c-41c7-964a-c130cfcb0d01)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=44852619-58ad-48f2-bc55-e8e1c72b1ba9)  
(средний)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f4112c25-9e6f-473a-bdbc-3df6dd66e6af)  
(средний)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f4ae65a7-142f-4953-a542-315dac2ac606)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7f5fc902-f5d8-4a87-a73f-68632f9a0935)  
(критический)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=1779cbc0-0c29-4fac-a3a6-8b335ffcb98e)\*\*\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=8b7a7bb0-80ef-4f25-bc70-3d0ac06007c5)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=bd7f36c6-c5c5-4f19-ab59-39f1aaba7fe2)  
(средний)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a594ee0d-ec8f-47df-9125-89d0bbf2115d)  
(средний)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=3bc0e17b-898b-4f29-aa29-607527e1c1cd)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-Based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7df0fce2-543c-4e82-85e6-012bfc8bf130)  
(критический)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=48282a89-f849-405a-a31e-2676f45b5042)\*\*\*\*  
(критический)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 for Itanium-Based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=7be36edf-02af-402f-983a-f9ca8128b6b5)  
(средний)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=cdb70acf-77c3-40a4-b6a3-0fbc0fc0d7fc)  
(средний)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=adb6bad2-9931-4ede-856e-bb43bb0f6071)  
(средний)
</td>
</tr>
<tr>
<th colspan="5">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://go.microsoft.com/fwlink/?linkid=158199)
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
Н/Д
</td>
<td style="border:1px solid black;">
[**Критический**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=c67d85c4-25c5-4821-8db9-91764888f893)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista с пакетом обновления 1 (SP1) и Windows Vista с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=6c90240e-c201-4dad-9835-ea71e3527b45)  
(без уровня опасности\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d3be9a13-1a5b-4b74-9649-449df923f573)  
(критический)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b05a19f7-7412-4c2b-ad11-34396e54ca43)  
(критический)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=3f8ae651-59f7-48e1-9e8c-8e07c6806964)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition с пакетом обновления 1 (SP1) и Windows Vista x64 Edition с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=d2084e8d-212b-4c39-9163-a71ec6d1b1c7)  
(без уровня опасности\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2b23cd74-6cf1-413b-82a7-b602347e3ce6)  
(критический)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=900e9a05-2f71-42de-b603-47e4ac061bcb)  
(критический)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://go.microsoft.com/fwlink/?linkid=158199)
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
Н/Д
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
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=91f6ee68-0e39-4ec3-b4cd-45f05404e2fb)\*  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 32-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 32-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=0194f994-5821-4fb9-b9e1-ed6af248c995)\*  
(без уровня опасности\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=92e3af41-71b0-4a28-afc7-123733180ead)\*  
(средний)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=30f99bda-9107-4969-90af-2a30e12acdae)\*  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 для 64-разрядных систем и Windows Server 2008 для 64-разрядных систем с пакетом обновления 2 (SP2)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=5cdc3014-97b3-47b5-a6b7-cd0e12ec60e4)\*  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 для 64-разрядных систем и Windows Server 2008 с пакетом обновления 2 (SP2) для 64-разрядных систем](http://www.microsoft.com/downloads/details.aspx?familyid=4127b125-fdaa-489a-a80c-14b5647ac7e0)\*  
(без уровня опасности\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1958ec40-3b7b-43a9-9fdc-742735dcf516)\*  
(средний)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=acd3667b-6676-4010-b23b-e8372dd55f93)\*  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 для систем на базе процессоров Itanium и Windows Server 2008 с пакетом обновления 2 (SP2) для систем на базе процессоров Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-Based Systems и Windows Server 2008 for Itanium-Based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=03330a14-9cfa-4146-a3d3-4b7a76975d2d)  
(критический)
</td>
<td style="border:1px solid black;">
Не применимо
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-Based Systems и Windows Server 2008 for Itanium-Based Systems с пакетом обновления 2 (SP2)](http://www.microsoft.com/downloads/details.aspx?familyid=4082c776-318c-4e0c-83fc-2f3f472c039a)  
(без уровня опасности\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=470387ac-6d75-4b7e-8ca5-376b67a8bd4d)  
(средний)
</td>
</tr>
</table>
 
**Примечание для Windows Server 2008**

**\*Уязвимости не подвержены системы Windows Server 2008, при развертывании которых устанавливалось только ядро сервера.** Поддерживаемые выпуски Windows Server 2008, при развертывании которых выбиралась установка только ядра сервера, не подвержены уязвимостям, устраняемым этим обновлением. Дополнительные сведения об этом варианте установки см. в [этой статье](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Обратите внимание, что установка только ядра сервера недоступна в определенных выпусках Windows Server 2008; подробности см. в статье [Сравнение параметров установки ядра сервера](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Примечание к бюллетеню MS09-032**

**\*\***Уровни опасности неприменимы к этому обновлению, поскольку уязвимость, описанная в этом бюллетене, не затрагивает это программное обеспечение. Однако в качестве дополнительной меры защиты от возможных новых направлений атаки в будущем корпорация Майкрософт рекомендует пользователям этого программного обеспечения установить это обновление для системы безопасности.

**Примечания к бюллетеню MS09-028**

**\*\*\***Обновление для DirectX 8.1 также применимо и для DirectX 8.1b.

**\*\*\***Обновление для DirectX 9.0 также применимо для DirectX 9.0a, DirectX 9.0b и DirectX 9.0c.

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
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-030**](http://go.microsoft.com/fwlink/?linkid=147424)
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
Выпуск 2007 системы Microsoft Office с пакетом обновления 1 (SP1)
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2007 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=d4b0665d-5744-49c7-a3c0-f231fd08d3b8)  
(KB969693)  
(существенный)
</td>
</tr>
</table>
 

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
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-035**](http://go.microsoft.com/fwlink/?linkid=158131)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Средний**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=63ce454e-f69c-44e3-89fb-eb23c2e2154e)  
(KB971089)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2005
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=7c8729dc-06a2-4538-a90d-ff9464dc0197)  
(KB971090)  
(средний)  
[Microsoft Visual Studio 2005 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=9d7ee45b-9892-41b5-ac08-5fde9cde1b42)\*  
(KB973673)  
(средний)  
[Средства Visual C++ для разработки 64-разрядного кода, размещенные в Microsoft Visual Studio 2005 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=43f96f2a-69c6-4c5e-b72c-0edfa35f4fc2)  
(KB973830)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Embedded CE 6.0
</td>
<td style="border:1px solid black;">
[Windows Embedded CE 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=99d114f8-4d95-4075-a0f1-45f498f0ade8)\*\*  
(KB974616)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](http://www.microsoft.com/downloads/details.aspx?familyid=8f9da646-94dd-469d-baea-a4306270462c)  
(KB971091)  
(средний)  
[Microsoft Visual Studio 2008](http://www.microsoft.com/downloads/details.aspx?familyid=e3bb6602-b7f4-4614-9999-77f5c6f66ccd)\*  
(KB973674)  
(средний)  
[Microsoft Visual Studio 2008 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=294de390-3c94-49fb-a014-9a38580e64cb)  
(KB971092)  
(средний)  
[Microsoft Visual Studio 2008 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=75fbf397-5140-4961-92a9-78a88ba7228f)\*  
(KB973675)  
(средний)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual C++ 2005
</td>
<td style="border:1px solid black;">
[Распространяемый пакет Microsoft Visual C++ 2005 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=766a6af7-ec73-40ff-b072-9112bab119c2)  
(KB973544)  
(средний)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual C++ 2008
</td>
<td style="border:1px solid black;">
[Распространяемый пакет Microsoft Visual C++ 2008](http://www.microsoft.com/downloads/details.aspx?familyid=8b29655e-9da4-4b6b-9ac5-687ca0770f93)  
(KB973551)  
(средний)  
[Распространяемый пакет Microsoft Visual C++ 2008 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=2051a0c1-c9b5-4b0a-a8f5-770a549fd78c)  
(KB973552)  
(средний)
</td>
</tr>
</table>
 
**Примечания к бюллетеню MS09-035**

\*Для мобильных приложений, использующих ATL для смарт-устройств

\*\*Устанавливает ежемесячное обновление для Windows Embedded CE 6.0 (декабрь 2009). Этот пакет обновления можно загрузить только с веб-сайта Центра загрузки Майкрософт.

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
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-031**](http://go.microsoft.com/fwlink/?linkid=154993)
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
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006](http://www.microsoft.com/downloads/details.aspx?familyid=c4e9b1dd-526d-407b-bc23-ebc2738b1b19)  
(KB970811)  
(существенный)  
[Обновление для поддержки Microsoft Internet Security and Acceleration Server 2006](http://www.microsoft.com/downloads/details.aspx?familyid=e8ccd770-a925-411c-b994-78e4cf5c3476)  
(KB970811)  
(существенный)  
[Microsoft Internet Security and Acceleration Server 2006 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=e536cfed-c1af-4868-b2ac-79178d6355a5)  
(KB971143)  
(существенный)
</td>
</tr>
</table>
 

#### ПО Майкрософт для виртуализации

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Virtual PC
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-033**](http://go.microsoft.com/fwlink/?linkid=153891)
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
Microsoft Virtual PC 2004
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2004 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=56a160e1-59b5-45bc-aecf-dfe614a7efad)  
(KB969856)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual PC 2007
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2007](http://www.microsoft.com/downloads/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a)  
(KB969856)  
(существенный)  
[Microsoft Virtual PC 2007 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0)  
(KB969856)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual PC 2007 x64 Edition
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2007 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a)  
(KB969856)  
(существенный)  
[Microsoft Virtual PC 2007 x64 Edition с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0)  
(KB969856)  
(существенный)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Virtual Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Идентификатор бюллетеня**
</td>
<td style="border:1px solid black;">
[**MS09-033**](http://go.microsoft.com/fwlink/?linkid=153891)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Общий уровень опасности**
</td>
<td style="border:1px solid black;">
[**Существенный**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual Server 2005
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005](http://www.microsoft.com/downloads/details.aspx?familyid=85d4f910-4c13-4229-aba7-b9d6181d78c8)  
(KB969856)  
(существенный)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005 R2 с пакетом обновления 1 (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57)  
(KB969856)  
(существенный)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2 x64 Edition
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005 R2 x64 Edition с пакетом обновления (SP1)](http://www.microsoft.com/downloads/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57)  
(KB969856)  
(существенный)
</td>
</tr>
</table>
 

Руководство и средства по диагностике и развертыванию
-----------------------------------------------------

<span></span>
**В центре безопасности**

Управление программным обеспечением и обновлениями для системы безопасности для установки на серверы, настольные и переносные компьютеры организации. Дополнительные сведения см. на веб-узле [центра TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [Центр безопасности TechNet](http://go.microsoft.com/fwlink/?linkid=21171) содержит дополнительные сведения о безопасности в продуктах Майкрософт. Доступ к этим сведениям можно также получить, посетив веб-сайт [Безопасность дома](http://go.microsoft.com/fwlink/?linkid=85102) и щелкнув ссылку "Последние обновления".

Обновления для системы безопасности доступны в [Центре обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747) и [Центре обновления Windows](http://go.microsoft.com/fwlink/?linkid=21130). Обновления для системы безопасности также доступны на веб-узле [центра загрузки Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Самый простой способ найти обновление — выполнить поиск по ключевому слову "security update".

Наконец, обновления для системы безопасности можно загрузить из [каталога Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=96155). Он обеспечивает возможность поиска содержимого (в том числе обновлений для системы безопасности, драйверов и пакетов обновления), которое предоставляется через Центр обновления Windows и Центр обновления Майкрософт. При поиске по номеру бюллетеня по безопасности (например, MS07-036) можно добавлять необходимые обновления (в том числе на различных языках) в корзину и загружать их в указанную папку. Дополнительные сведения см. на веб-сайте каталога Центра обновления Майкрософт в разделе [вопросов и ответов](http://go.microsoft.com/fwlink/?linkid=97900).

**Примечание.** Начиная с 1 августа 2009 г. Майкрософт прекращает поддержку центра загрузки Office и средства инвентаризации центра загрузки Office. Чтобы продолжить получать последние обновления для продуктов Microsoft Office, используйте веб-сайт [Центра обновления Майкрософт](http://go.microsoft.com/fwlink/?linkid=40747). Дополнительные сведения см. на веб-странице [Центр загрузки Microsoft Office: вопросы и ответы](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Руководство по диагностике и развертыванию**

Корпорация Майкрософт предоставила руководство по диагностике и развертыванию для обновлений безопасности этого месяца. Это руководство также поможет ИТ-специалистам понять, как можно использовать для развертывания обновления для системы безопасности такие средства, как веб-сайты Центра обновления Windows, Центра обновления Майкрософт и центра загрузки Office, анализатор безопасности Microsoft Baseline Security Analyzer (MBSA), средство Office Detection Tool, сервер Microsoft Systems Management Server (SMS) и средство Extended Security Update Inventory Tool (ESUIT). Дополнительные сведения см. в [статье 910723 базы знаний Майкрософт](http://support.microsoft.com/kb/910723).

**Анализатор безопасности Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer (MBSA) позволяет администраторам проверять локальные и удаленные системы с целью выявления неустановленных обновлений безопасности и стандартных ошибок в конфигурации системы безопасности. Дополнительные сведения об анализаторе безопасности MBSA см. на веб-сайте [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Службы Windows Server Update Services**

Службы Windows Server Update Services (WSUS) позволяют администраторам быстро и надежно развертывать последние критические обновления и обновления безопасности для операционных систем Windows 2000 и более поздних версий Windows, для Office XP и более поздних версий Office, для Exchange Server 2003 и для SQL Server 2000 на системах Windows 2000 и более поздних версиях операционных систем.

Дополнительные сведения о развертывании данного обновления для системы безопасности с помощью служб Windows Server Update Services см. на веб-узле [Службы Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) (на английском языке).

**Сервер Systems Management Server**

Сервер Systems Management Server (SMS) корпорации Майкрософт предоставляет хорошо сконфигурированное решение для управления обновлениями в масштабах предприятия. С помощью сервера SMS администраторы могут определять необходимость установки обновлений безопасности на системах Windows и выполнять управляемое развертывание этих обновлений по всему предприятию с минимальными нарушениями работы конечных пользователей. Последний выпуск сервера SMS — System Center Configuration Manager 2007 — доступен для загрузки; сведения о нем см. также на веб-сайте [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Дополнительные сведения о том, как администраторы могут использовать сервер SMS 2003 для развертывания обновлений для системы безопасности, см. на веб-странице [Управление исправлениями для системы безопасности сервера SMS 2003](http://go.microsoft.com/fwlink/?linkid=22939). Пользователи сервера SMS 2.0 могут также воспользоваться средствами веб-узла [Пакет возможностей служб Software Updates Services](http://go.microsoft.com/fwlink/?linkid=33340) (на английском языке), позволяющими упростить развертывание обновлений для системы безопасности. Дополнительные сведения о сервере SMS см. на веб-узле [Сервер Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) (на английском языке).

**Примечание.** Для предоставления широкой поддержки при определении необходимости применения и развертывания обновлений, рассмотренных в бюллетенях безопасности, SMS-сервером используются средства Microsoft Baseline Security Analyzer и Microsoft Office Detection Tool. С помощью этих средств не всегда удается определить необходимость некоторых обновлений программного обеспечения. В этих случаях для определения компьютеров, на которых требуется установка обновлений, администраторы могут воспользоваться учетными функциями SMS. Дополнительные сведения об этой процедуре см. на веб-узле [Развертывание обновлений программного обеспечения с помощью функции распространения программ сервера SMS](http://go.microsoft.com/fwlink/?linkid=33341) (на английском языке). При установке некоторых обновлений безопасности для продолжения работы на компьютере после его перезагрузки потребуется наличие соответствующих полномочий администратора. Администраторы могут устанавливать эти обновления с помощью средства Elevated Rights Deployment Tool (входит в состав пакетов [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) и [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

**Средство оценки совместимости обновлений и набор средств для обеспечения совместимости приложений**

Часто обновления записываются в одни те же файлы, а для запуска приложений требуется настроить параметры реестра. Это приводит к возникновению несовместимостей и увеличивает время, затрачиваемое на развертывание обновлений для системы безопасности. Облегчить тестирование и проверку обновлений Windows для установленных приложений можно с помощью [компонентов оценки совместимости обновлений](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true), входящих в состав [набора средств для обеспечения совместимости приложений 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Набор средств для обеспечения совместимости приложений содержит необходимые средства и документацию для выявления проблем совместимости приложений и уменьшения степени воздействия этих проблем перед развертыванием системы Microsoft Windows Vista, обновлений из Центра обновления Windows, обновлений с веб-сайта безопасности Майкрософт или новой версии проводника.

### Прочие сведения

#### Средство удаления вредоносных программ для системы Microsoft Windows

Корпорация Майкрософт выпустила обновленную версию средства удаления вредоносных программ для системы Microsoft Windows и распространяет ее через Центр обновления Windows, Центр обновления Майкрософт, службы Windows Server Update Services и центр загрузки.

#### Высокоприоритетные обновления, не относящиеся к безопасности и распространяемые через Центр обновления Майкрософт, Центр обновления Windows и службу WSUS

Дополнительные сведения об обновлениях, не связанных с безопасностью и доступных на веб-сайте Центра обновления Windows и Центра обновления Майкрософт, см. по адресу:

-   [Статья 894199 базы знаний Майкрософт](http://support.microsoft.com/kb/894199). Описание изменений содержимого служб Software Update Services и Windows Server Update Services (включая все содержимое, относящееся к системе Windows).
-   [Новые, исправленные и выпущенные обновления для продуктов Майкрософт, отличных от Microsoft Windows](http://technet.microsoft.com/en-us/wsus/dd573344.aspx).

#### Программа Microsoft Active Protections Program (MAPP)

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

-   Томаса Гарнье (Thomas Garnier) из [SkyRecon](http://www.skyrecon.com/), а также Чжэн Вэньбиня (Zheng Wenbin), Лю Ци (Liu Qi) и Сун Шэньлэя (Song Shenlei) из [Qihoo 360 Security Center](http://www.360.cn/) за сообщение о проблеме, описанной в бюллетене MS09-028
-   Ямату Ли (Yamata Li) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение о проблеме, описанной в бюллетене MS09-028
-   Аарона Портной (Aaron Portnoy) из [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/), а также анонимного исследователя, работающего в TippingPoint в рамках проекта [Zero Day Initiative](http://www.zerodayinitiative.com/), Томаса Гарнье (Thomas Garnier) из [SkyRecon](http://www.skyrecon.com/) и Ямату Ли (Yamata Li) из [Palo Alto Networks](http://www.paloaltonetworks.com/) за сообщение о проблеме, описанной в бюллетене MS09-028
-   компанию [VeriSign iDefense Labs](http://labs.idefense.com/) за сообщение о проблеме, описанной в бюллетене MS09-029
-   Томаса Гарнье (Thomas Garnier) за сообщение о проблеме, описанной в бюллетене MS09-029
-   Лайонела Доненса (Lionel d'Hauenens) из [Labo Skopia](http://www.laboskopia.com/), сотрудничающего с [VeriSign iDefense Labs](http://www.idefense.com/), за сообщение о проблеме, описанной в бюллетене MS09-030
-   Райана Смита (Ryan Smith) и Алекса Уилера (Alex Wheeler) из [IBM IIS X-Force](http://www.iss.net/) за первое сообщение о проблеме, описанной в бюллетене MS09-032
-   Джулиана Тиннеса (Julien Tinnes) и Тэвиса Орманди (Tavis Ormandy) из [Google Inc.](http://www.google.com/) за сообщение о проблеме, описанной в бюллетене MS09-033
-   Петера Врёгденила (Peter Vreugdenhil) из [VeriSign iDefense Labs](http://labs.idefense.com/) за сообщение о проблеме, описанной в бюллетене MS09-034
-   Вуши (Wushi) и Лина (Ling) из [team509](http://www.team509.com/), сотрудничающих с компанией [TippingPoint](http://www.tippingpoint.com/) в рамках проекта [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в бюллетене MS09-034
-   Петера Врёгденила (Peter Vreugdenhil), сотрудничающего с компанией [TippingPoint](http://www.tippingpoint.com/) в рамках проекта [Zero Day Initiative](http://www.zerodayinitiative.com/), за сообщение о проблеме, описанной в бюллетене MS09-034
-   Дэвида Дьюи (David Dewey) из [IBM ISS X-Force](http://www.iss.net/) за сообщение о проблеме, описанной в бюллетене MS09-035
-   Шона Ларссона (Sean Larsson) из [VeriSign iDefense Labs](http://labs.idefense.com/) за сообщение о двух проблемах, описанных в бюллетене MS09-035

#### Поддержка

-   Продукты, перечисленные в этом бюллетене, проверены на наличие уязвимости в тех или иных версиях. Жизненные циклы поддержки прочих версий программного обеспечения истекли. Сведения о жизненных циклах поддержки версий используемых программных продуктов см. на веб-странице [сроков поддержки продуктов Майкрософт](http://go.microsoft.com/fwlink/?linkid=21742).
-   Пользователи из США и Канады могут обратиться в службу [поддержки по вопросам безопасности](http://go.microsoft.com/fwlink/?linkid=21131) или позвонить по телефону 1-866-PCSAFETY. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Дополнительные сведения о вариантах поддержки см. на веб-сайте [справки и поддержки корпорации Майкрософт](http://support.microsoft.com/).
-   Пользователям в других странах для получения поддержки следует обращаться в местные представительства корпорации Майкрософт. Звонки, связанные с обновлениями безопасности, обслуживаются бесплатно. Для получения дополнительных сведений о службе поддержки корпорации Майкрософт посетите [веб-узел международной поддержки](http://go.microsoft.com/fwlink/?linkid=21155).

#### Заявление об отказе

Сведения в статьях базы знаний Майкрософт предоставляются без каких-либо гарантий. Корпорация Майкрософт не предоставляет каких-либо гарантий, явных или подразумеваемых, включая любые гарантии товарности или пригодности для использования в определенных целях. Корпорация Майкрософт и ее поставщики ни при каких обстоятельствах не несут ответственности за возможный ущерб, включая косвенный, случайный, прямой, опосредованный и специальный ущерб, а также упущенную выгоду, даже если корпорация Майкрософт или ее поставщики заранее были извещены о возможности такого ущерба. Если действующее законодательство не допускает отказа от ответственности за косвенный или случайный ущерб, то описанные выше ограничения не действуют.

#### Редакции

-   Вер. 1.0 (14 июля 2009): Обзор бюллетеней опубликован.
-   Версия 1.1 (15 июля 2009 г.) В бюллетене MS09-032 обновлена аннотация; в бюллетене MS09-029 исправлены сведения, касающиеся необходимости перезагрузки компьютера; внесены другие необходимые изменения.
-   Вер. 2.0 (28 июля 2009 г.) Добавлены следующие бюллетени по безопасности: MS09-034 "Накопительное обновление для системы безопасности Internet Explorer" (972260) и MS09-035 "Уязвимости в библиотеке ATL среды Microsoft Visual Studio делают возможным удаленное выполнение кода" (969706). Кроме того, добавлены ссылки на веб-трансляции, связанные с данными внеплановыми бюллетенями по безопасности.
-   Вер. 3.0 (4 августа 2009 г.) Изменения связаны с повторным выпуском обновления для Microsoft Internet Explorer 6 с пакетом обновления 1 (SP1) в ОС Microsoft Windows 2000 с пакетом обновления 4 (SP4). Компьютеры всех пользователей, ранее установивших исходное обновление для Internet Explorer 6 с пакетом обновления 1 (SP1) в ОС Microsoft Windows 2000 с пакетом обновления 4 (SP4), уже защищены от описанных ниже уязвимостей. Однако пользователи корейской версии Internet Explorer 6 с пакетом обновления 1 (SP1) могут переустановить настоящее обновление для Internet Explorer 6 с пакетом обновления 1 (SP1) в имеющейся у них ОС Windows 2000, с тем чтобы обеспечить тот же уровень защиты и попутно устранить проблемы печати. Бюллетень по безопасности Microsoft MS09-034.
-   Вер. 4.0 (11 августа 2009 г.) Повторная публикация обзора связана с повторным выпуском бюллетеня MS09-035, посвященного новым обновлениям для Microsoft Visual Studio 2005 с пакетом обновления 1 (SP1) (KB973673), Microsoft Visual Studio 2008 (KB973674) и Microsoft Visual Studio 2008 с пакетом обновления 1 (SP1) (KB973675) и предназначенного для разработчиков, пользующихся Visual Studio для создания программных компонентов и элементов управления для мобильных приложений, использующих библиотеку ATL для смарт-устройств.
-   Версия 4.1 (13 августа 2009 г.): Исправлены указания о необходимости перезагрузки для MS09-035.
-   Вер. 5.0 (19 августа 2009 г.) Добавлена сноска, касающаяся бюллетеня MS09-028 и уточняющая список уязвимых продуктов для уязвимости DirectX 8.1.
-   Вер. 6.0 (25 августа 2009 г.) Публикация новой версии связана с повторным выпуском японоязычного обновления для Windows XP с пакетом обновления 2 (SP2), Windows XP с пакетом обновления 3 (SP3) и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2). Компьютеры всех пользователей, ранее установивших исходного обновление, уже защищены. Однако пользователи японоязычных версий Windows XP с пакетом обновления 2 (SP2), Windows XP с пакетом обновления 3 (SP3) и Windows XP Professional x64 Edition с пакетом обновления 2 (SP2) должны установить настоящее обновления, чтобы не только обеспечить прежний уровень защиты, но и устранить проблемы в работе очереди печати. Бюллетень по безопасности Microsoft MS09-029.
-   Вер. 7.0 (12 января 2010 г.): В новой редакции MS09-035 в список уязвимого программного обеспечения добавлена платформа Windows Embedded CE 6.0. Обновление для Windows Embedded CE 6.0 (KB974616) представляет собой накопительное обновление, которое можно загрузить только с веб-сайта Центра загрузки Майкрософт. Пользователи, использующие платформу Windows Embedded CE 6.0, должны применить данное накопительное обновление.
-   Вер. 8.0 (9 марта 2010 г.): Выпущена новая редакция в связи с тем, что Microsoft Virtual Server 2005 добавлен в число программ, подверженных уязвимости, в MS09-033.

*Built at 2014-04-18T01:50:00Z-07:00*
