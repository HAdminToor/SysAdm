# SysAdm
Профессия сетевой администратор
Профессиональные обязанности и функции

Базовый набор функций специалиста:
планирование сети;
подбор и установка ПО;
проверка работоспособности ЛВС;
оперативное реагирование на программные сбои;
работа с подрядчиками по разработке внутрикорпоративного софта;
обучение кадров;
конфигурирование сетевых потоков;
маршрутизация;
распределение доступов к программным, сетевым ресурсам.

Круг дополнительных задач
Набор дополнительных опций специалиста по администрированию сетей – та самая точка соприкосновения двух профессий. В небольших компаниях сам администратор или помощник сетевого администратора часто выполняет работу сисадмина:
обслуживание серверов;
подбор/настройка сетевых сервисов;
сопровождение офисного АСТ;
настройка шлюзов VPN.
За отсутствием сисадмина специалист по сетям де-факто может исполнять совмещенные функции представителей двух профессий – следить за оборудованием (качеством его работы, своевременным ремонтом, сервисом) и программной работой.

Права и ответственность сетевого администратора
Еще лет 10 назад манипуляции специалистов, занятых в IT-инфраструктуре предприятия, для остальных сотрудников (включая руководство) были таинством. Сегодня, когда количество молодых людей, продвинутых в азах IT, увеличилось, работа администратора стала более понятной. Хотя ее специфика все равно остается для представителей иных профессий загадкой.

Поэтому права эксперта, обслуживающего внутреннюю сеть, достаточно обширны. Они включают:
доступ к документальным решениям начальства по части вопросов, касающихся работы специалиста;
внесение предложений по наращиванию эффективности сети;
получение от работников информации, необходимой для поддержания работоспособности оборудования/софта;
разработку/установление правил пользования компьютерным ресурсом;
привлечение к ответственности нарушителей установленных правил.
Широкий доступ к внутренней информации компании накладывает серьезную ответственность. Специалист может понести наказание за несвоевременную регистрацию IP-адресов или отложенную реакцию на поломку, если это нанесло бизнесу урон. Он отвечает за функционирование сети (управление маршрутизацией, обслуживание сетевых сервисов), контроль злоупотреблений ресурсами со стороны работников.

Необходимые личные качества
Очень ценными качествами в работе такого мастера являются:
терпение;
концентрация;
творческий подход к решению нестандартных задач;
умение выполнять рутинную работу;
способность справляться с раздражением;
быстрое переключение между задачами;
четкое распределение приоритетов;
аналитическое мышление;
умение находить, быстро осваивать новую информацию.

***________________Полезные ссылки____________________***

Маски IPv4:

https://yandex.ru/images/search?img_url=https%3A%2F%2Ftadex.com.ua%2Fwp-content%2Fuploads%2F2022%2F04%2Fa3c3ac3db26fafdd8be16c57145b1d79.png&lr=11342&pos=0&rpt=simage&source=serp&text=таблица%20масок 

IPv4 to IPv6:

https://www.whatsmydns.net/ipv4-to-ipv6

Маски IPv6: 

https://www.mymathtables.com/table/other/IPV6-subnetting-chart.html 

Калькулятор сжатия / расширения адреса IPv6:

https://ivit.pro/services/kalkulyator-szhatiya-rasshireniya-adresa-ipv6/ 

IPv6 to IPv4:

https://www.whatsmydns.net/ipv6-to-ipv4 


______________________________________________________________________________________________________________________________

Отчет

Модуль 1

1. b. Рассчитайте IP-адресацию IPv4 и IPv6. Необходимо заполнить таблицу №1, чтобы эксперты могли проверить ваше рабочее место.

Таблица №1

Имя устройства	Имя интерфейса	IPv4	IPv6



3. Настройте внутреннюю динамическую маршрутизацию по средствам FRR. Выберите и обоснуйте выбор протокола динамической маршрутизации из расчёта, что в дальнейшем сеть будет масштабироваться.

Обоснование: Настройка динамической маршрутизации произведена с помощью протокола OSPF – Данный протокол позволяет разделять сеть на логические области, что делает его масштабируемым для больших сетей.
Каждая область может иметь свою таблицу маршрутизации, что уменьшает нагрузку на маршрутизаторы и улучшает производительность сети.

5. a. Составьте топологию сети L3.

Схема топологии L3:


6. Измерьте пропускную способность сети между двумя узлами HQ-R-ISP по средствам утилиты iperf 3. Предоставьте описание пропускной способности канала со скриншотами.

Результат проверки:
Результат проверки по средствам утилиты iperf 3 показывает, что пропускная способность сети между узлами 192.168.0.1 (ISP) и 192.168.0.2 (HQ-R) составляет приблизительно 923 Mbits/sec на клиента и 858 Mbits/sec на сервере. Это говорит о достаточно высоких показателях производительности сети.

7. Составьте backup скрипты для сохранения конфигурации сетевых устройств, а именно HQ-R BR-R. Продемонстрируйте их работу.

Скрипт HQ-R:

Работа скрипта HQ-R:

Скрипт BR-R:

Работа скрипта BR-R:

Модуль 2
3. Настройте сервер домена на базе HQ-SRV через web интерфейс, выбор технологий обоснуйте

Обоснование: Выбор Samba в качестве контроллера домена обеспечивает интеграцию Linux-систем в сети Windows, обеспечивает безопасное управление ресурсами в сети и снижает затраты на создание и поддержку контроллера домена. Также на базе Samba в дальнейшем планируется развернуть сетевые ресурсы организации. Это позволит реализовать несколько практических задач в рамках одного программного решения.

4. Реализуйте файловый SMB или NFS (выбор обоснуйте) сервер на базе сервера HQ-SRV.

Обоснование: Выбор Samba в качестве файлового протокола обеспечивает интеграцию Linux-систем в сети Windows, обеспечивает безопасный обмен файлами в сети и снижает затраты на создание и поддержку сетевого файлового сервера. Поскольку ранее в качестве контроллера домена была выбрана технология Samba, было принято решение использовать для хранения данных протокол SMB для удобства администрирования. Также реализован алгоритм контроля доступа к сетевым ресурсам с использованием учётных доменных записей пользователей.

Модуль 4

a.	Установите и настройте сервер мониторинга на базе машины CLI с использованием БД PostgreSQL. Выбор технологии решения обоснуйте.

Обоснование выбора: В системе мониторинга Zabbix PostgreSQL может использоваться как дополнительное хранилище для длительного хранения метрик. Это позволяет сохранять большой объём данных и обеспечивает возможность анализа и отчётности по метрикам за продолжительный период времени. Система мониторинга Zabbix является более традиционным инструментом, который лучше подходит для мониторинга инфраструктуры и серверов, являясь всеобще принятым стандартом в организациях.

д. Осуществите проверку доступности узлов мониторинга на сервере, оформите отчёт с результатами проверки.

Отчет: Проверка доступности нового узла мониторинга ISP показала следующие результаты: узел доступен, связь стабильна. Всего было отправлено три пакета, при этом их потеря составила 0%. 
Скрин проверки:

_____________________________________________________________________________
