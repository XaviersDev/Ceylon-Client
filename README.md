# Ceylon-Client
Free Intave hacked-client for 1.12.2 Forge. 

## Download (на русском языке переводится как "Скачать"): https://drive.google.com/file/d/1kLEZk2NUMofpxHM2j2eIPwm95QhjoSzn/view?usp=sharing



**COMBAT**

`AntiSprintReset` – Предотвращает сброс спринта при атаке или использовании предметов, обеспечивая непрерывный бег.

`ArrowDodge` – Автоматически уклоняется от стрел: модуль заставляет персонажа стрейфиться влево или вправо, когда в него целятся из лука или когда поблизости летит стрела. Настройки включают угол прицеливания, дистанцию и время уклонения.

`Attack` – Расширенная система атаки с настройками CPS (минимальное и максимальное), выбором целей (игроки, мобы, животные), опцией игнорирования своей команды, AimAssist, Smart W-Tap/S-Tap, предсказанием движения цели, атакой вокруг в указанном радиусе, а также настройками версии боя, плавности наводки и разброса прицела.

`BackTrack` – Задерживает входящие пакеты позиций сущностей, позволяя атаковать их по предыдущему местоположению. Настраивается дальность действия, временная задержка, цели. Включает опциональное ESP для отображения "отмотанных" позиций.

`BowIndicator` – Отображает настраиваемый индикатор на экране, когда игрок целится из лука в другого игрока. Позволяет изменять позицию, размер, цвета, тип анимации и звук оповещения.

`FireballAura` – Автоматически наводится на ближайшие летящие фаерболы и атакует их для отражения.

`LClicker` – Автокликер для левой кнопки мыши. Позволяет настроить количество кликов в секунду, а также условия работы: только при наводке на игрока и игнорирование членов своей команды.

`RClicker` – Автокликер для правой кнопки мыши. Позволяет настроить количество кликов в секунду и условие работы: только при наводке на блок. Не срабатывает, если в руке меч.

`SwordAim` – Автоматически наводит прицел на стойки для брони, держащие железный меч, в определенном радиусе. Полезно для некоторых мини-игр.

`Tickbase` – Модуль для манипуляции скоростью обработки игровых тиков. Позволяет создавать эффект "зарядки" (замедления) и "выпуска" (ускорения) тиков. Имеет несколько режимов работы (TimerRange, Shidori, Vestige), различные режимы активации (вручную, при атаке, по клавише, умный, при активации другого модуля) и множество настроек, включая количество тиков, значения таймера, адаптивные тики и опции для обхода античитов. Настройки доступны через GUI (клавиша INSERT в меню модуля) и конфигурационный файл.
 

**CHAT**

`AutoDemotivator` – Моральный убийца игроков. Позволяет настроить цвет сообщений и задержку между ними.

`AutoHaha` – Автоматически отправляет в чат сообщения, имитирующие смех или содержащие указанное слово в случайном обрамлении из букв. Есть опция для отправки в глобальный чат (с префиксом "!").

`BullingHits` – Автоматически буллит игрока при его ударе. Позволяет настроить цвет, префикс для глобального чата и задержку.
Расширенные настройки чата: фильтрация глобального и локального чата, автоматическая установка заглавных букв в начале предложений и точек в конце. Возможность использования ИИ для стилизации сообщений. Включает меню для управления сохраненными сообщениями и аффиксами (префиксы/суффиксы).

`CmdHelp` – Отображает в чате список доступных команд CClient.

`CoolRuFont` – Заменяет стандартные русские символы в чате на стилизованные (например, исполь

`FakeMessages` – Позволяет редактировать любое сообщение из истории чата и отправлять его визуально. Поддерживает использование цветовых кодов формата Minecraft (&).

`Hidewords` – Скрывает сообщения в чате, содержащие указанные пользователем слова или фразы. Список блокируемых слов и активность фильтрации для каждого слова настраиваются через GUI.

`ReLogs` – Выводит в чат уведомления о входе игроков на сервер и их выходе.

`PrivateMsg` – Система приватных сообщений между пользователями CClient с использованием шифрования. Позволяет отправлять сообщения конкретному игроку (`.msg <ник> <сообщение>`), менять ключ шифрования (`.setkey <ключ>`), управлять контактами (блокировка, установка индивидуальных ключей для отдельных контактов), получать объявления от администрации клиента. Графический интерфейс вызывается клавишей HOME (настраивается).

`Triggers` – Позволяет создавать автоматические реакции на различные события в игре. Триггеры могут срабатывать на сообщения в чате, титульные и подтитульные сообщения на экране, появление ников игроков в таб-листе или определенные строки в скорборде. Для каждого триггера настраивается текст (с возможностью использования подстановок слов, ника игрока или полного сообщения), один или несколько ответов (с задержкой и возможностью выполнения движений), режим ответа (поочередно или случайно один раз) и тип триггера. Очень расширённые переменные. Управление через GUI (клавиша U).

`TurnirAnnouncer` – Автоматически отправляет в чат уведомления о начале турнира на серверах с режимом Grief (например, MineBlaze). Сообщения информируют за 5 минут до начала, при старте сбора игроков и в момент начала турнира.
 

**FUN**

`DickBuilder` – Автоматически строит мужское достоинство, держите 5 блоков в руках.

`DickESP` – Визуально подсвечивает мужское достоинство других игроков. Настраивается длина и цвет подсветки.

`DeleteSystem32` – БЛЯТЬ ЧТО ЗА ХУЙНЯ.

`Friends` – Система списка друзей. Игроки, добавленные в этот список, могут быть защищены от атак со стороны пользователя, в зависимости от выбранного режима защиты (защита от атак модулями или полная защита от любых атак). Управление списком и режимом защиты осуществляется через GUI. Если модуль выключен он всё-равно продолжает свою работу.

`MurderMystery` – Помощник для мини-игры Murder Mystery. Автоматически определяет убийцу по наличию у него железного меча и детектива по луку. Подсвечивает брошенный на карте лук. Может объявлять убийцу в чат, используя стандартное сообщение или сообщения, сгенерированные ИИ. Отслеживает игроков, покинувших игру. Позволяет настраивать тип подсветки (Glow, Box, Outline) и цвета для ролей.

`NoRegHits` – Предотвращает регистрацию ударов пользователя по другим игрокам на сервере.

`NoWORLD` – Значительно повышает FPS за счет отключения рендеринга большинства элементов игрового мира. Не загружаются чанки, удаляются сущности (кроме игроков), отключаются частицы и эффекты погоды.

`ω Pings` – Воспроизводит звуковое уведомление из Discord при упоминании ника пользователя в игровом чате.

`SantaHat` – Добавляет визуальный эффект в виде шапки Санта-Клауса на голову модели игрока.

`Serenity` – Создает умиротворяющую визуальную атмосферу вокруг игрока. Генерирует частицы бабочек, светлячков, падающих листьев, плывущих облаков, растущих цветов, а также эффекты ряби на воде и легкого ветра. Позволяет настраивать количество частиц, дальность их рендера и эффекты погружения (затемнение экрана, насыщенность цветов).

`❄ Snow ❄` – Добавляет визуальный эффект снегопада вокруг игрока и оставляет снежный след при движении. Позволяет настроить радиус, силу, высоту и густоту снегопада.

`TimeChanger` – Позволяет визуально изменять время суток в игровом мире для пользователя. Можно установить точное время с помощью ползунка или выбрать один из предустановленных режимов (день, полдень, закат, ночь). Модуль блокирует серверные пакеты обновления времени, эффект виден только локально.

`TryPlayer` – Копирует движения и повороты камеры выбранного игрока. Выбор цели осуществляется через GUI.

`WTF?!` – Активирует хаотичные визуальные эффекты, искажающие отображение игры: изменение матрицы проекции и вида, масштабирование, вращение, изменение цветов, визуальные глитчи. Имеет опцию автоматической отправки сообщений "скорой помощи" и режим "Портал Стрэнджа" для усиления эффектов.

 
**MISC**

`AI-U-Bot MineBlaze` – ИИ-бот, разработанный для сервера MineBlaze. Способен общаться, выполнять команды (варпы, оплата, объятия и т.д.), автоматически применять наказания (мут/бан/варн) к нарушителям правил чата (с исключениями для игроков с символом "~" в нике). Обладает информацией о сервере, его администрации, разработчиках и истории. Может выводить сообщения в чат или на голограммы.

`AutoThrow` – Автоматически выбрасывает предметы из выбранного слота хотбара по всем четырем сторонам (вперед, назад, влево, вправо) с настраиваемой задержкой.

`AutoWalk` – Автоматически зажимает клавишу движения вперед.

`BindCommand` – Позволяет назначать клавиши для активации модулей через чат с помощью команды `.bind <модуль> <клавиша>`. Например, `.bind attack R`. Команда `.bind <модуль> NONE` убирает привязку.

`Bots` – Интеграция с Mineflayer для создания и управления ботами. Позволяет настраивать никнеймы, IP-адреса, порты. Управление ботами осуществляется через специальное меню. Имеется система триггеров для автоматических ответов. Требует установленный Node.js (НО В САМОМ МЕНЮ БОТОВ ЕГО МОЖНО УСТАНОВИТЬ).

`CCScripts` – Предоставляет возможность написания пользовательских скриптов для автоматизации действий в CClient. Модуль находится в стадии альфа-тестирования. Документация доступна по ссылке в описании модуля. 

`ChatGPT` – Интеграция с ИИ-ассистентом. Позволяет задавать вопросы ИИ, получать ответы в чате, генерировать сообщения от имени игрока, а также использовать режим автоматических ответов на сообщения в чате. ИИ осведомлен о CClient и его разработчике.

`CustomItemPos` – Выводит в чат ссылку для скачивания мода, позволяющего настраивать положение предметов в руке.

`Disabler` – Модуль для обхода античитов путем манипуляции сетевыми пакетами. Включает различные режимы: базовый, умный обход, анти-паттерн. Позволяет тонко настраивать, какие пакеты блокировать или изменять.

`FireballBoost` – Использует модуль PulseTP для усиления прыжка при использовании огненного заряда (ПКМ), позволяя игроку взлететь выше.

`Gamma` – Позволяет настраивать уровень гаммы (яркости) в игре через GUI с ползунком.

`Indicators` – Отображает текущие значения FPS (кадров в секунду) и пинга (задержки) в углу экрана.

`InvisChestsFix` – Исправляет проблему с невидимыми сундуками, обеспечивая их корректное отображение.

`Music` – Встроенный MP3-плеер. Позволяет проигрывать музыкальные файлы из папки `cclient/music/tracks`. Управление воспроизведением (плей/пауза, следующий/предыдущий трек, случайное воспроизведение, повтор) осуществляется через GUI.

`NoHurtCam` – Отключает эффект тряски камеры при получении урона.

`NoOpenGUI` – Блокирует открытие графических интерфейсов (например, сундуков, верстаков), инициируемых сервером.

`PulseTP` – Осуществляет вертикальный телепорт путем быстрой отправки пакетов изменения позиции игрока вверх (на 9 блоков) и затем вниз на ближайший твердый блок под игроком.

`Respawner` – Автоматически возрождает игрока после смерти.

`SoundFix` – Перезагружает звуковую систему Minecraft. Предназначен для исправления проблем со звуком, например, после переподключения аудиоустройств.

`Предложить идею ` – Позволяет отправить предложение по улучшению CClient напрямую разработчику. Идея вводится в специальном окне и отправляется через Discord вебхук.

`TelegramCh` – Позволяет отслеживать новые посты в указанных Telegram-каналах. При появлении нового поста выводит уведомление в чат и отображает всплывающее окно с его содержанием. Список каналов настраивается через GUI.

`Timer` – Позволяет изменять скорость течения игрового времени (timer speed). Управление скоростью осуществляется через команду `.timer <число>` (от 0.1 до 10) или через GUI модуля.

`TLSkins` – Модуль, предназначенный для работы со скинами TLauncher. В описании указано, что он недоделан.

 
**PLAYER**

`AirStuck` – Замораживает позицию игрока в воздухе путем манипуляции сетевыми пакетами.

`AntiBlind` – Автоматически удаляет эффекты слепоты и тошноты у игрока.

`AntiCollision` – Отключает физические столкновения между моделью игрока и моделями других игроков.

`AntiPosLook` – Отменяет серверные пакеты (SPacketPlayerPosLook), которые принудительно изменяют позицию или направление взгляда игрока. Может быть полезно для сохранения позиции после телепортации или использования некоторых багов.

`AuctionSniper` – Автоматически покупает указанные предметы на внутриигровом аукционе, если их цена не превышает заданную пользователем. Настраивается через GUI.

`AutoArmor` – Автоматически экипирует наилучшую доступную броню из инвентаря игрока, основываясь на показателях защиты и зачарованиях. Имеет опцию предпочитать элитры.

`AutoEat` – Автоматически употребляет еду из хотбара, когда уровень голода игрока опускается ниже заданного порога. Позволяет настроить порог голода и приоритет насыщения.

`AutoInBlock` – Автоматически выполняет действия для "вклинивания" в блок, находящийся под игроком. Сила (количество отправляемых пакетов) настраивается. Модуль находится в стадии бета-тестирования.

`AutoSneak` – Автоматически активирует и удерживает режим приседания (sneak).

`AutoSprint` – Автоматически активирует режим спринта при движении вперед.

`AutoTool` – Автоматически выбирает наиболее эффективный инструмент из хотбара для разрушения блока, на который наведен курсор. При разрушении кровати автоматически выбирает ножницы.

`AutoWaterDrop` – При падении с большой высоты автоматически пытается разместить ведро воды под игроком для предотвращения урона от падения. Работает через серверные пакеты и пытается подобрать воду обратно.

`Blink` – УЛУЧШЕН! Задерживает отправку пакетов движения игрока серверу, а затем отправляет их все одновременно, создавая эффект телепортации. Максимальное время удержания пакетов около 30 секунд. Отображает след движения игрока во время задержки.

`BotWalk` – Автоматическая ходьба с элементами ИИ. Персонаж двигается вперед, пытается обходить препятствия, может прыгать и использовать спринт. Также может атаковать игроков при необходимости.

`BowBoost` – Убирает задержку при стрельбе из лука, автоматически натягивая тетиву сразу после выстрела для максимальной скорострельности.

`ChestStealer` – Автоматически забирает все предметы из открытых сундуков. Позволяет настроить задержку между забором предметов, случайный порядок и автоматическое закрытие сундука после опустошения.

`Eagle` – Автоматически активирует режим приседания, когда игрок находится на краю блока, для предотвращения падения при строительстве мостов. (либо же наоборот, помогает строить мост)

`FakeGM` – Визуально изменяет игровой режим пользователя (между выживанием и креативом) на стороне клиента. Не влияет на реальный игровой режим на сервере.

`Fly` – Позволяет игроку летать. Имеет настройки скорости полета и систему анти-кика, которая периодически возвращает игрока на землю для обхода серверных проверок.

`Freecam` – Позволяет отделить камеру от тела игрока и свободно перемещаться по миру, проходя сквозь блоки. Тело игрока остается на месте. Настраивается скорость полета, отображение модели игрока, автоматическое переключение на вид от третьего лица и другие параметры.

`Freeze` – Полностью замораживает персонажа на месте. Обходит все античиты!

`InBlock` – Позволяет проходить сквозь блоки. При зажатой клавише модуля и разрушении блока под собой, игрок проваливается сквозь него. Сила (количество пакетов) настраивается через команду `.inblock <число>` или GUI модуля.

`ItemSpoof` – Позволяет подменять предмет в руке на стороне сервера. Предмет, который должен видеть сервер, помещается в верхний левый слот инвентаря. При использовании предмета, блока или атаке сущности, сервер будет считать, что используется подмененный предмет.

`Jesus` – Позволяет ходить по воде. Имеет несколько режимов: "Твердый" (вода ощущается как твердый блок), "Отскок" (игрок подпрыгивает при падении в воду) и "Только визуал" (отображается поверхность воды без эффектов ходьбы).

`Lagger` – Создает эффект прерывистого движения или телепортации для других игроков. Периодически задерживает отправку пакетов движения, а затем отправляет их все сразу. Настраивается длительность задержки пакетов и интервал между "выпусками" через команды `.tpdelay` и `.notpdelay`. Отображает визуальный бокс на месте "заморозки" игрока.

`LongJumped` – Значительно увеличивает дальность прыжка, если модуль активирован во время нахождения в воздухе. Скорость прыжка настраивается командой `.lspeed <число>`.

`MaxClip` – Осуществляет телепорт на самый верхний доступный блок над игроком. Требует, чтобы игрок стоял вплотную к определенным типам блоков (стеклянные панели, решетки, заборы, двери, вода, лестницы, люки, лианы, тростник, таблички, паутина, огонь).

`NoBowSlow` – Убирает эффект замедления движения при натягивании тетивы лука.

`RapidJumps` – Позволяет прыгать значительно быстрее обычного, если над головой игрока находится блок. Уменьшает или убирает задержку между прыжками.

`AutoRejoinerY1` – Автоматически выполняет команды `/leave` и затем `/rejoin`, если игрок оказывается на высоте Y=8 (например, при падении в пустоту на некоторых серверах).

`SkinAnimator` – Анимирует отдельные части скина игрока (рукава, штанины, куртка, шляпа, плащ), заставляя их поочередно или группами появляться и исчезать. Позволяет настраивать задержку анимации, случайность, учитывать движение игрока. Имеет предустановленные анимации (плавная, мерцание, волна, симметричная) и возможность создавать свои.

`Step` – Позволяет игроку автоматически подниматься на блоки определенной высоты без прыжка. Высота настраивается (по умолчанию 1 блок). Имеется опция "плавного шага" (использование пакетов) для возможного обхода слабых античитов.
 

**RENDER**

`ArrayList` – Настройка отображения списка активных модулей. Позволяет изменять цвета основного текста и текста модулей, включать/отключать фон, отображение логотипа Ceylon, выбирать тип анимации цветов, выравнивание текста, режим сортировки списка модулей и шрифт. Список модулей можно перемещать по экрану мышью.

`ArmorStandESP` – Подсвечивает стойки для брони, делая их видимыми сквозь стены.

`ChinaHat` – Добавляет визуальный эффект в виде китайской шляпы на голову модели игрока. Шляпа переливается цветами.

`Effects` – Применяет различные полноэкранные шейдерные эффекты, изменяющие визуальное восприятие игры (например, Notch, FXAA, Art, Bumpy, Pencil и другие).

`EnhancedWater` – Расширенные настройки визуализации воды. Позволяет изменять прозрачность, видимость под водой, силу и скорость волн, качество отражений, силу преломления, искажения под водой, поверхностное натяжение и интенсивность пены.

`ESP` – Отображает информацию о сущностях сквозь стены. Поддерживает режимы подсветки: контуры (outline), боксы (box), чамсы (chams). Позволяет настраивать цвета для разных типов сущностей (игроки, NPC, животные, мобы, жители, стойки для брони, другие живые существа) используя различные режимы (статичный цвет, по цвету команды, случайный, радужный). Есть настройки яркости, прозрачности, насыщенности, подсветки друзей, себя и невидимых сущностей. Список цветов для радужной анимации настраивается.

`FullBright` – Устанавливает максимальный уровень яркости в игре, делая темные области полностью видимыми.

`HotBarText` – Отображает пользовательский текст над хотбаром. Поддерживает множество настроек: цвета (палитры, радуга, волна, chroma), тени (обычные, 3D), масштабирование, смещение, анимации (печатание, мерцание, слайд), фон, рамки (стили, цвет, размер), вращение.

`InvImg` – Позволяет загружать пользовательские изображения в качестве фона для инвентаря и других открытых контейнеров. В режиме редактирования (активируется через GUI модуля) можно изменять размер, положение, слой (под/над GUI, поверх всего) и прозрачность каждого изображения.

`ItemESP` – Подсвечивает предметы, лежащие на земле. Использует систему команд Minecraft для создания эффекта свечения. Позволяет настроить цвет для обычных предметов и отдельный цвет для "меча убийцы" (железный меч на стойке для брони). Имеется опциональный режим обводки предметов.

`JumpCircles` – При каждом прыжке игрока под ним появляется анимированный круг, который плавно расширяется и исчезает.

`Lighter` – Создает динамический источник света в точке, на которую смотрит игрок. Позволяет настроить яркость, интенсивность мерцания и радиус освещения.

`MyCrosshair` – Продвинутый редактор прицела. Позволяет рисовать прицел пиксель за пикселем, используя инструменты: кисть, линия, прямоугольник, круг, заливка, пипетка. Настраиваются: размер кисти, масштаб и прозрачность прицела, цвета (включая радугу и пульсацию), анимации, тени, обводка, сглаживание. Поддерживает историю изменений (отмена/повтор) и генерацию случайных прицелов/шаблонов.

`MyFog` – Расширенная настройка внутриигрового тумана. Позволяет изменять цвет тумана, его интенсивность, плотность, радиус. Поддерживает создание зон с различными цветами тумана и динамические эффекты, такие как градиентный туман, ветер и турбулентность.

`NameTags` – Делает ники игроков видимыми сквозь стены. Поддерживает различные режимы цвета (статический, по цвету команды, градиент, радуга, пульсация), настройку масштаба, скорости анимации и режима текста (обычный, пульсация размера).

`PlayerGhosts` – Позволяет изменять прозрачность моделей других игроков. Степень прозрачности настраивается через GUI модуля с помощью ползунка.

`PlayerGlowing` – Заставляет модели других игроков (кроме собственной и NPC) светиться выбранным цветом. Цвет (RGB) и прозрачность свечения настраиваются через GUI.

`RageCombat` – Активирует интенсивные визуальные эффекты при нанесении удара игроком: изменение цвета тумана и неба, тряска экрана, свечение и изменение размера модели игрока, следы движения, частицы. Также включает эффект изменения скорости течения игрового времени.

`Scoreboard` – Позволяет настраивать отображение скорборда (таблицы очков). Можно изменять его положение на экране (перетаскиванием мышью или слайдерами), масштаб, включать/отключать фон, настраивать цвета фона и свечения по краям (включая радужный режим), применять эффект размытия фона. Также есть настройки для заголовка: масштаб, позиция по Y и X, принудительный цвет.

`SmartScreen` – Расширенные функции для создания скриншотов. Автоматически отключает/включает выбранные модули перед созданием скриншота, изменяет поле зрения (FOV), добавляет настраиваемый водяной знак (текст, IP сервера, время), применяет различные графические фильтры (сепия, негатив, ч/б и др.), изменяет разрешение скриншота. Активируется настраиваемой клавишей (по умолчанию F2). Настройки доступны через GUI (ПКМ + RSHIFT).

`Tracers` – Рисует линии от точки обзора игрока к другим игрокам, делая их видимыми сквозь препятствия. Позволяет настраивать цвет линий (в зависимости от дистанции, по цвету команды, пользовательский цвет, радужный) и их прозрачность. Включает оптимизацию для уменьшения нагрузки при большом количестве игроков.

`Trails` – Оставляет за игроком красочный, переливающийся разными цветами след при движении.

`Trajectories` – Отображает траекторию полета для метательных снарядов, таких как стрелы, эндер-перлы, снежки и зелья. Позволяет настроить цвет, прозрачность, размер и форму (круг или квадрат) точки предполагаемого попадания.

`WBar` – Отображает информационную панель в нижней части экрана. Может показывать FPS, пинг, текущее время, дату, эмодзи и информацию о CClient. Содержимое панели настраивается через GUI модуля.
 

**WORLD**

`BlockPackets` – Позволяет визуально удалять блоки по клику правой кнопкой мыши (с анимацией разрушения) и восстанавливать их повторным кликом. Изменения видны только локально. Может использоваться для прохождения сквозь тонкие стены.

`FakeBreaker` – Визуально разрушает блоки вокруг игрока на стороне клиента. На сервере блоки остаются целыми. При отключении модуля все "разрушенные" блоки восстанавливаются. Позволяет настроить смещение по высоте для области разрушения.

`MapDownload` – Позволяет скачивать карту сервера, сохраняя загруженные чанки в отдельный мир Minecraft. Отображает прогресс скачивания и логи. Управление через GUI.

`NoInvis` – Делает все невидимые сущности (кроме игроков, если это не настроено в ESP) видимыми для пользователя.

`OMurderMapChecker` – Автоматически сканирует таблички в радиусе 50 блоков от игрока и выводит в чат информацию о доступных картах для мини-игры Murder Mystery (название, статус: лобби/начало/в игре, количество игроков). Обновляется каждые 5 секунд. Предназначен для серверов MineBlaze/MineBerry.

`Parkourer` – Автоматически проходит карты с мини-паркуром, состоящие из стеклянных блоков (например, на сервере MineBlaze). Периодически использует "кисточку" (предмет для активации) и команду `/startp`. 



Для клиента рекомендуется использовать текстур-пак HD-Font!
В CClient есть множество полезных и уникальных функций для улучшения ваще всего:
 
**Доступ и Интерфейс:**

При первом запуске вас встретит анимированное интро и система доступа через Telegram-бота `@skvceylonbot`. Вам нужно будет получить код доступа в клиенте, ввести его боту и подтвердить вход в Telegram для использования всех возможностей.
Интерфейс клиента был значительно переработан: вас ждет новое главное меню с возможностью установки пользовательского фона (можно выбрать изображение с компьютера), настройки его затемнения и изменения цветов кнопок. Меню выбора серверов и экран добавления новых серверов также обновлены. В главном и игровом меню (Esc) добавлены кнопки для быстрого доступа к Discord-серверу проекта, встроенной мини-игре (где вы управляете персонажем, стремясь набрать максимум очков; можно указать ник для использования соответствующего скина в игре) и удобному менеджеру альт-аккаунтов. Менеджер альт-аккаунтов позволяет добавлять, удалять, быстро входить в сохраненные аккаунты, импортировать список из SkillClient, отмечать аккаунты как избранные и входить под случайным ником.

Кстати, клиент был оптимизирован.

 
**ClickGUI (меню модулей):**


Центральное меню CClient (вызывается по умолчанию клавишей INSERT, перебиндить можно в меню настйроках клавиши) предоставляет полный контроль над всеми модулями. Здесь вы можете:

*   Просматривать модули, сгруппированные по категориям.

*   Включать и отключать модули.

*   Привязывать модули к клавишам: для этого кликните колёсиком мыши по названию модуля в списке, а затем нажмите желаемую клавишу. Нажатие ESC во время привязки отменит ее.

*   Открывать меню модуля, нажав по нему правой кнопкой мыши (ПКМ).

*   Искать модули по названию с помощью строки поиска.

*   Получать краткое описание функциональности модуля при наведении на него курсора.
 

В нижней части ClickGUI расположены кнопки:

*   **"БИНДЫ"**: открывает экран, где отображаются все ваши текущие привязки модулей к клавишам.

*   **"ФОН"**: позволяет настроить фон самого ClickGUI (анимированный, кастомное изображение или сплошной цвет) и его прозрачность.

*   **"СТИЛЬ"**: открывает меню настройки цветовой палитры ClickGUI, позволяя изменять основной, вторичный, акцентный цвета, цвет ошибок, фона и текста, а также включать различные визуальные опции (тени, анимации, иконки категорий, скругленные углы).

*   **"БЭКАП"**: предоставляет доступ к системе создания и применения бэкапов вашей конфигурации привязки клавиш и состояния модулей (вкл/выкл).
 

**Полезные Команды и Функции в Чате:**
Клиент добавляет ряд команд для управления некоторыми функциями:

*   `.ai <текст>`: Отправляет ваш `<текст>` искусственному интеллекту, и он отвечает вам прямо в игровом чате. Ответ будет виден только вам.

*   `.aic <текст>`: Искусственный интеллект генерирует ответ на ваш `<текст>` и отправляет его в чат от вашего имени. Полезно, если хотите остроумно ответить, но терпилой то не хочется быть бля.

*   `.aicauto [дополнительная инструкция]`: Включает/выключает режим автоматического ответа ИИ на все сообщения в чате. Вы можете указать `[дополнительную инструкцию]`, чтобы ИИ следовал определенному стилю или теме при ответах.

*   `.ait <слово> [дополнительная инструкция]`: Похоже на `.aicauto`, но ИИ будет реагировать и отвечать только на те сообщения в чате, которые содержат указанное `<слово>`. Также можно задать `[дополнительную инструкцию]`.

*   `.clanpizda <интервал_в_мс>`: позволяет кикать ВСЕХ участников клана (если вы модератор) с указанной задержкой.

*   `.follow <ник_игрока>` / `.unfollow`: включает/отключает автоматическое следование за указанным игроком.

*   `.kriv <ник_игрока> [!]` / `.unkriv`: начинает/прекращает передразнивание сообщений указанного игрока. Добавление `!` в конце команды `.kriv` отправляет "окривленные" сообщения в глобальный чат.

*   `.inblock <сила>`: устанавливает силу (количество пакетов) для модулей InBlock.

*   `.find <ник_игрока>` / `.find`: начинает отслеживать указанного игрока (рисует линию к нему и показывает дистанцию) или прекращает отслеживание, если ник не указан.

*   `.timer <число>`: устанавливает скорость для модуля TTimer (от 0.1 до 10).

*   `.lspeed <число>`: устанавливает скорость для модуля LongJump.

*   `.vclip <число>` / `.hclip <число>`: осуществляет телепортацию сквозь блоки по вертикали или горизонтали на указанное количество блоков.


{players}: Если вы напишете это в сообщении, клиент автоматически заменит {players} на ник каждого игрока на сервере (кроме вашего) и отправит по одному сообщению для каждого. 
Например, если написать "Привет, {players}!", и на сервере есть игроки cloners и mazimn, то будут отправлены сообщения "Привет, cloners!" и "Привет, mazimn!".

.setdelay <мс>: установить задержку для отправки сообщений отправляемые через {players}.


1.  **Фильтрация чата:**

    *   **Глобальный чат (ɢ):** Позволяет скрыть сообщения, отправленные в глобальный чат (обычно начинаются с `!`).

    *   **Локальный чат (ʟ):** Дает возможность скрыть сообщения из локального чата.


3.  **Автоматическое форматирование текста:**

    *   **Авто-заглавные (Aa):** Автоматически делает первую букву вашего сообщения заглавной.

    *   **КАПС режим (AC):** Все ваши сообщения будут отправляться В ВЕРХНЕМ РЕГИСТРЕ.

    *   **Авто-точка (.):** Автоматически добавляет точку в конце ваших сообщений, если ее там нет.


5.  **Режим ИИ-писателя (AI):**

    *   При включении этого режима, ваши сообщения перед отправкой проходят обработку через ИИ, который стилизует их согласно выбранной теме (например, "в стиле Тони Старка").

    *   В меню можно выбрать тему или оставить "обычный стиль" для более естественных, но все же скорректированных ИИ сообщений.

    *   **Важно:** При включенном ИИ-режиме кнопки "Авто-заглавные", "КАПС" и "Авто-точка" отключаются, так как ИИ сам позаботится о форматировании.


7.  **Меню сохраненных сообщений ("паст") ([]):**
    *   Открывает отдельное окно, где вы можете сохранять часто используемые сообщения или "пасты".
    *   **Добавление/Редактирование/Удаление:** Легко добавляйте новые пасты, редактируйте существующие (ПКМ по пасте) или удаляйте их.
    *   **Отправка:** Клик ЛКМ по сохраненной пасте мгновенно отправит ее в чат.
    *   **Привязка к клавишам:** Каждую пасту можно забиндить на отдельную клавишу (Клик колесиком мыши по пасте) для супер-быстрой отправки.
    *   **Префиксы/Суффиксы:** Для каждой пасты можно индивидуально включить/выключить добавление текущего выбранного префикса или суффикса.


8.  **Настройка префиксов и суффиксов (P/S):**

    *   Открывает меню, где вы можете создавать списки префиксов (текст перед вашим сообщением) и суффиксов (текст после вашего сообщения).

    *   Вы можете выбрать активный префикс и суффикс, которые будут автоматически добавляться к вашим сообщениям (если не отключено для конкретной пасты).

    *   Это позволяет быстро менять "подпись" или стиль ваших сообщений.


9.  **Дополнительные меню (интеграция с другими модулями):**

    *   **SPAM:** Быстрый доступ к настройкам модуля FSpammer.

    *   **MSGS:** Открывает меню модуля FakeMessages для создания фейковых сообщений.

    *   **TRGS:** Открывает меню модуля Triggers для настройки автоматических триггеров.


*   Все основные переключатели (фильтры, авто-форматирование, ИИ) доступны в виде небольших кнопок, появляющихся над полем ввода чата, когда вы его открываете (клавиша T по умолчанию).
*   Кнопки "[]" (пасты) и "P/S" (префиксы/суффиксы) также находятся там и открывают соответствующие меню для детальной настройки.


**Дополнительно:**

*   **Поле ввода в инвентаре**: При открытии инвентаря или сундука внизу появляется дополнительное поле для быстрого ввода текста в чат, а также кнопки "Отправить", "OFF CLICKERS" (отключает активные автокликеры LClicker/RClicker), "Fake Close (XCarry)" (позволяет клиенту считать инвентарь открытым, даже если вы его закрыли, для некоторых серверных взаимодействий) и "KICK" (отправляет специальный символ '§', который может использоваться для некоторых команд или эксплойтов).

*   **Фильтр серверов**: Клиент автоматически удаляет из списка серверов те, в названии которых содержится "erid:", а если точнее, удаляет рекламные сервера.

*   **Уведомления**: Встроенная система красивых всплывающих уведомлений в углу экрана информирует о различных событиях в клиенте, таких как включение/отключение модулей.

*   **Обработка нажатий**: Улучшенная система обработки нажатий клавиш позволяет активировать модули даже тогда, когда фокус ввода не находится в чате или другом GUI.

*   **Подсветка администратора**: Администратор `cl0nya` имеет особую визуальную подсветку в игре (свечение, частицы), а его ник в чате и таб-листе заменяется на стилизованный вариант.

*   **Взаимодействие с ИИ**: Внутренняя система AIGET обеспечивает возможность взаимодействия с искусственным интеллектом (используется модулями AI, ChatFilter) для генерации текста и поиска информации в интернете.

*   **Сохранение конфигураций**: Все настройки модулей, интерфейса и других систем клиента сохраняются, чтобы вам не приходилось настраивать все заново при каждом запуске. 


🪿🪿🪿🪿🪿🪿

DOWNLOAD https://drive.google.com/file/d/1kLEZk2NUMofpxHM2j2eIPwm95QhjoSzn/view?usp=sharing

