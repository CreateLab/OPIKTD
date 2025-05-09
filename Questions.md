# Экзаменационные вопросы по 6 лекциям

## Лекция 1: Методологии разработки

1. В чем основные отличия гибкой методологии разработки (Agile) от классической каскадной модели (Waterfall)?
2. Какие основные этапы включает каскадная модель разработки ПО (Waterfall), и какие недостатки этой модели проявляются на практике?
3. В чем заключается V-образная модель (V-Model) процесса разработки и для каких проектов она особенно подходит?
4. Объясните понятие итеративной (поэтапной) разработки. Почему итеративный подход считается полезным при реализации сложных проектов?
5. Почему Agile-подходы считаются более адаптивными к изменениям требований по сравнению с традиционными? Объясните, какие механизмы Agile помогают эффективно реагировать на изменяющиеся требования.
6. Опишите методологию Scrum: какие основные роли, события (церемонии) и артефакты она включает?
7. Как методология Kanban управляет потоком задач? Перечислите ключевые принципы Kanban и поясните их влияние на процесс разработки.
8. Сравните подходы Scrum и Kanban: в чем их сходства и различия? В каких случаях каждый подход более предпочтителен?
9. В чем суть методологии экстремального программирования (Extreme Programming, XP) и как её практики (например, парное программирование, TDD) влияют на качество кода?
10. Что такое гибридные методологии разработки? Приведите пример подхода, объединяющего элементы классической и гибкой моделей, и объясните, зачем компании используют смешанные подходы.
11. Какова роль документации в гибких методологиях (Agile)? Почему даже при Agile-подходе важно уделять внимание документированию требований и решений?
12. Представьте, что требования к проекту часто меняются на поздних стадиях разработки. Какую методологию разработки вы бы выбрали в этой ситуации и почему?
13. Как осуществляется управление рисками в проектах, выполняемых по каскадной модели, и в Agile-проектах? Сравните подходы к оценке и минимизации рисков.
14. Что такое ретроспектива (retrospective) в Agile и какую пользу она приносит команде разработки? Объясните, как регулярные ретроспективы влияют на улучшение процесса.
15. По каким критериям следует выбирать методологию разработки для конкретного проекта? Назовите несколько факторов, влияющих на выбор (например, размер и распределённость команды, степень неопределённости требований, жёсткость сроков).

## Лекция 2: Сети

1. Объясните разницу между моделью OSI и стеком протоколов TCP/IP. Зачем вообще выделяют уровни при описании сетевого взаимодействия?
2. В чем различие между протоколами TCP и UDP, и где каждый из них применяется? Приведите примеры типов приложений для каждого протокола.
3. Опишите процесс установления соединения по TCP, известный как процедура трёхстороннего рукопожатия (three-way handshake). Почему этот процесс важен перед передачей данных?
4. Что такое NAT (Network Address Translation) и зачем он используется? Объясните, как NAT позволяет нескольким устройствам совместно использовать один глобальный IP-адрес.
5. Объясните принцип работы DNS (Domain Name System). Как доменное имя преобразуется в IP-адрес — какие этапы проходят при выполнении DNS-запроса от клиента?
6. Чем отличается адресация в IPv6 от IPv4? Какие проблемы призван решить IPv6 и с какими трудностями сталкиваются при его внедрении?
7. Что такое маршрутизация и чем отличается статическая маршрутизация от динамической? В каких случаях целесообразно использовать каждый подход?
8. Объясните понятие VLAN. Как разделение сети на VLAN помогает в сегментации и повышении безопасности корпоративной сети?
9. Какие функции выполняет коммутатор (switch) на канальном уровне и как он отличается от маршрутизатора (router) на сетевом уровне? Приведите примеры применения каждого устройства.
10. Какую роль выполняет брандмауэр (firewall) в сети и чем сетевой экран отличается от маршрутизатора? В чем разница между фильтрацией трафика и маршрутизацией?
11. Что такое номер порта в сетевом контексте? Почему протоколы транспорта (TCP/UDP) используют портовые номера и как операционная система распределяет порты между приложениями?
12. Опишите основные шаги, которые происходят в сети при загрузке веб-страницы по URL (например, `http://example.com`). Какие сетевые службы и протоколы задействованы на пути от вашего браузера к серверу и обратно?
13. Что такое ARP (Address Resolution Protocol) и какую задачу он решает? Как происходит обмен сообщениями ARP (запрос и ответ) в локальной сети?
14. Объясните концепцию отказоустойчивости сети. Какие меры позволяют сохранить связность, если один из узлов или каналов выходит из строя?
15. Какими показателями измеряется производительность сети? Расскажите, что характеризует пропускную способность (bandwidth), задержка (latency) и потеря пакетов, и почему важно учитывать все эти параметры.

## Лекция 3: RUP (унифицированный процесс)

1. Опишите цели и ключевые особенности каждой из четырёх фаз RUP: Inception, Elaboration, Construction и Transition.
2. Какие основные артефакты требуются на этапе Inception? Приведите два примера и объясните их значение для проекта.
3. В чём заключается задача фазы Elaboration? Какие архитектурные решения принимаются и какие артефакты соответствуют этому этапу?
4. Как организован процесс управления требованиями в рамках RUP? Какие документы и инструменты используются для сбора и контроля требований?
5. Что такое SRS (Software Requirements Specification) в контексте RUP и какие разделы он обычно включает?
6. Какие атрибуты требований (приоритет, источник, критерии приёма, оценка трудозатрат) определены в RUP? Почему важно их учитывать при планировании?
7. Как UML-диаграммы вариантов использования (Use Case) помогают при сборе требований? Объясните роль акторов, прецедентов и связей.
8. В чём разница между связями «include» и «extend» на Use Case-диаграммах? Приведите по одному практическому примеру каждого.
9. Какие модели и документы создаются на этапе бизнес-моделирования в RUP? Приведите два примера соответствующих артефактов.
10. Опишите основную цель фазы Construction и какие ключевые артефакты (код, тестовые сценарии) она порождает.
11. Как организован этап Transition в RUP: какие документы и модели готовятся для успешного развёртывания и обучения пользователей?
12. Какие практики тестирования (Quantify, Purify и др.) рекомендуются на этапе Test в RUP? Как они интегрируются в общий процесс?
13. Объясните структуру таблицы анализа рисков в RUP: какие столбцы она включает, как рассчитывается приоритет риска и что означает каждый параметр?
14. Приведите пример трёх рисков для проекта по разработке веб-приложения и опишите по каждому меры по снижению (mitigation).
15. Как можно интегрировать Agile-практики (Planning Poker, Story Points) в итеративный процесс RUP? Какие преимущества это даст команде?

## Лекция 4: Git

1. В чем отличие распределённой системы контроля версий (Git) от централизованной (SVN)? Какие преимущества даёт распределённый подход команде разработчиков?
2. Что такое репозиторий Git и какие основные объекты он хранит? Объясните роли таких объектов, как коммит, дерево (tree) и блоб (blob).
3. В чем разница между командами `git pull` и `git fetch`? В каких ситуациях имеет смысл сначала выполнить `git fetch` вместо сразу `git pull`?
4. Какую роль играют ветки (branches) в Git и как использование веток и слияний облегчает работу в команде? Опишите типовой workflow с ветками при разработке нового функционала.
5. Что происходит при слиянии (merge) ветки в Git и чем слияние отличается от перемотки (rebase)? Когда лучше использовать `git rebase`, а когда — обычный `git merge`?
6. Как Git обнаруживает конфликт слияния (merge conflict) и что должен сделать разработчик при возникновении конфликта? Опишите, как разрешить конфликт и завершить слияние.
7. Что такое fast-forward слияние в Git и в чем его особенности? Когда fast-forward слияние возможно, и почему в некоторых случаях его применять нежелательно?
8. Для чего предназначена команда `git stash` и в каком случае ею удобно воспользоваться? Опишите ситуацию, когда `git stash` помогает переключиться на другую задачу.
9. Что происходит при клонировании репозитория с помощью команды `git clone`? Опишите, какие шаги выполняются, чтобы скопировать удалённый репозиторий себе на локальную машину.
10. Объясните, что означает состояние detached HEAD в Git. В каком случае можно оказаться в этом состоянии и почему это может быть проблематично?
11. Почему не рекомендуется вносить новые изменения непосредственно в главную ветку (master/main) репозитория? Опишите предпочтительный рабочий процесс (workflow) с использованием отдельных feature-веток.
12. Что такое тег (tag) в Git и как он отличается от ветки? В каких случаях имеет смысл создавать аннотированные теги?
13. Что означает «переписать историю» в контексте Git? Какие команды позволяют изменить историю коммитов и почему этого следует избегать в общих (shared) ветках?
14. Как изменения попадают под версионный контроль в Git? Опишите, что происходит от момента добавления файла командой `git add` до выполнения `git commit` и появления нового коммита в истории.
15. Представьте, что вы случайно удалили локальную ветку с изменениями, которые не были отправлены в удалённый репозиторий. Какие шаги вы предпримете, чтобы восстановить потерянные коммиты?

## Лекция 5: Docker

1. Объясните разницу между контейнером Docker и традиционной виртуальной машиной. Какие преимущества даёт использование контейнеров по сравнению с VM?
2. Что такое образ (image) Docker и чем он отличается от контейнера? Опишите, что происходит при запуске нового контейнера из образа.
3. Для чего нужен Dockerfile и какие инструкции в нём обычно указывают? Опишите процесс сборки образа на основе Dockerfile.
4. Как Docker использует слои (layers) при создании образов? Почему повторная сборка образа может выполняться быстрее благодаря использованию кэша слоев?
5. Что такое реестр (registry) Docker? Что происходит при выполнении команды `docker pull` — как Docker находит и загружает нужный образ из реестра?
6. В чем разница между привязкой папки с хоста (bind mount) и томом (volume) Docker? Когда лучше использовать каждый из этих способов для хранения данных?
7. Как Docker изолирует контейнеры друг от друга и от системы? Укажите основные механизмы изоляции (например, namespaces, cgroups) и их роль.
8. Объясните, что происходит при запуске контейнера с флагом `-p 8080:80`. Как обеспечивается доступ к сервису внутри контейнера по указанному порту с машины-хоста?
9. Можно ли запустить несколько контейнеров из одного и того же образа? Будут ли файловые системы этих контейнеров независимы друг от друга? Поясните свой ответ.
10. Что такое сеть типа bridge в Docker и как контейнеры взаимодействуют друг с другом по сети по умолчанию? Как можно обеспечить доступ контейнера в внешнюю (host) сеть?
11. Для чего используется команда `docker-compose` и в чем преимущество Docker Compose по сравнению с ручным запуском нескольких контейнеров?
12. Как можно ограничить потребление контейнером ресурсов хоста (CPU, память) и зачем это может понадобиться на практике?
13. Что произойдёт с данными, созданными внутри контейнера, при удалении этого контейнера? Как можно организовать работу с данными, чтобы они сохранялись между запусками контейнера?
14. В чем разница между запуском контейнера в фоновом режиме (detached mode) и в интерактивном режиме? В каких ситуациях каждый из режимов предпочтителен?
15. Представьте, что запущенный контейнер постоянно перезапускается (впадает в цикл перезапусков). Какие шаги диагностики и исправления вы предпримете, чтобы выявить и устранить причину проблемы?

## Лекция 6: Nginx

1. Объясните архитектуру Nginx: модель обработки событий (epoll), мастер- и рабочие процессы, и почему это масштабируется на тысячи соединений (C10k).
2. В чём ключевое отличие Nginx от Apache по модели обработки запросов и как это влияет на производительность под нагрузкой?
3. Как Nginx работает в роли обратного прокси? Опишите поток HTTP-запроса от клиента до backend-сервиса через Nginx.
4. Как настраиваются виртуальные хосты (server blocks) в Nginx? Какие директивы отвечают за `listen` и `server_name`?
5. Что такое блок `location` и как шаблоны в нём влияют на выбор правила обработки URI?
6. Как настроить кэширование статических ресурсов в Nginx? Приведите пример директив `expires` и `add_header Cache-Control`.
7. Опишите настройку SSL/TLS в Nginx: какие директивы нужны для ключа, сертификата и протоколов безопасности?
8. Какие алгоритмы балансировки нагрузки поддерживает Nginx и как задать веса (weight) для upstream-серверов?
9. Что такое `ip_hash` и для чего он используется? Какие ограничения накладывает этот метод «прилипших» сессий?
10. Как Nginx передаёт информацию об оригинальном IP-адресе клиента backend-серверам? Какие заголовки нужно настроить?
11. Для чего используются директивы `limit_req_zone` и `limit_req`? Приведите пример ограничения 10 запросов в секунду на один IP.
12. Что такое динамические модули Nginx и как их подключение отличается от статической сборки? Какие сложности могут возникнуть?
13. Как реализовать автоматическое перенаправление всех HTTP-запросов на HTTPS (301 redirect)? Приведите пример конфигурации.
14. Что означает ошибка 502 Bad Gateway в логах Nginx? Назовите три возможные причины и способы их устранения.
15. Как выполнить «обновление» конфигурации Nginx без простоя (zero-downtime reload)? Какие команды и сигналы используются?
