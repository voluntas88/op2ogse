# op2ogse
dsh mod для ОП-2

Форум мода и ссылки на скачивание для игроков находятся здесь:

- http://stalker-worlds.ru/forum/topic/3355-kovyriaemsia-v-ogse/?p=174181

- http://www.amk-team.ru/forum/index.php?showtopic=13176

Не продавайте журналы "Playboy", они вам пригодятся.

Изменения, по сравнению с ОП-2:

- В расширенных настройках графики, не включайте опцию "Детальный
  бамп", если не имеете на то веских оснований.

- В настройках игры необходимо назначить заново клавиши для ПНВ,
  напоминаний, ускорителя и быстрого сохранения.

- Погода и выброс заменены на те, что в OGSE.

- Теперь мины выкладываются ровно перед ГГ, на пол. метра впереди.

- Добавил доп. способы массового переноса вещей:

  Первый вариант - это переносить предмет, удерживая клавишу Shift.

  Второй вариант - это выделить предмет мышью и нажать клавишу "Z".

  Способ ОП-2, перенести предмет и нажать "Z" для переноса оставшихся
  предметов - тоже работает.

- Сейвы, которые делает эта адаптация, не будут загружаться в ОП-2,
  Можно сделать специальный квиксейв, который загрузится в ОП-2. Для
  этого нужно выйти в главное меню и нажать F6. Будет сделан сейв с
  именем op2quicksave.

- При загрузке восстанавливается активный оружейный слот.

- Коллиматорные прицелы теперь видны в темноте.

- Светошумовые гранаты теперь не действуют на главного героя, когда он
  находится в укрытии. Принцип такой: эффект от светошумовой гранаты
  будет, если она сработает на расстоянии не более 5-ти метров И
  граната "видит" голову главного героя.

- Прожектора на блокпостах выключаются утром и включаются вечером.

- Менеджер сна из OGSE

- Костюмы, которые должны лечить, теперь действительно лечат.

- Поменял партикл попадания от огнемета на OGSE-ешный. Он не просаживает FPS.

- Немного оптимизировал замки. При наличии в тайнике нескольких замков,
  тайник все равно будет считаться закрытым, даже если один из замков забрать,
  пока в тайнике имеется хотя бы один замок.

- Артефакты, влияющие на голод ГГ, теперь действительно на него влияют.

- Добавил быстрое использование антирадов/сыворотки. Клавиша назначается в
  настройках игры. При отсутствии антирада в инвентаре, используется
  сыворотка.

- Добавил опцию "Погода без дождя" в АМК настройки.

- У оружия с ночным прицелом (СВД Филин, например), ПНВ автоматически не
  включается. Нужно включать вручную.

- Что бы работал ПНВ, его необходимо перенести в свой слот.

- Для детекторов артефактов и биорадаров есть свои слоты. Впрочем, на поясе
  они тоже будут работать.

- Скриптовая логика боя неписей из OGSE

  Совет: никогда не стреляйте на виду у Кузнецова и его группы. Ни в кого.

- Изменен режим паузы после загрузки. При включенной опции
  используется пауза ОП-2, иначе - используется пауза OGSE.

- Грузоподъемность всех костюмов зависит от их состояния. Больший
  износ - меньшая грузоподъемность.

- Изменен третий апгрейд СКАТа-15.

  Дополнительные +20 кг. переносимого веса появляются только при
  наличии на поясе артефакта Черная энергия.  Без этого, переносимый
  вес будет такой же, как у второго апгрейда.  При повышенной
  загрузке, т.е. когда начинают использоваться эти дополнительные 20
  кг., Черная энергия начинает тратиться со скоростью 2 часа
  непрерывного грузопереноса. Если доп. вес не используется, то и
  Черная энергия не тратится.

- Перенес вид, звук и поведение некоторых аномалий из OGSE.

  Поглядывайте по сторонам и пользуйтесь болтами, если что.

- Поддержка шкалы пси здоровья на худе.

- Сталкеры в шлемах и противогазах больше не едят и не пьют сквозь них.

- Добавлен режим разрядки артефактов на поясе.

  Идея этого режима пришла мне в голову, когда я понял, что уже сотню игровых
  дней у меня на поясе висят одни и те же артефакты. Как я их повесил
  когда-то, так они все и используются. И полагаю, до самого конца игры, так
  меня и защищали-бы эти же самые артефакты. Т.е. они принимают на себя
  попадания пуль, осколков гранат и взрывы и им хоть бы что. Не-е-е-е,
  так не бывает. И вот пришла мне мысль, что пусть артефакты обладают
  способностью поглотить определенное кол-во энергии воздействий, от которых
  они защищают. Готово. При включенном режиме, артефакты на поясе будут
  постепенно разряжаться, нейтрализуя вредные воздействия. После полного
  разряда, артефакт превратится в Булыжник. Величина максимальной поглощенной
  энергии зависит от уровня сложности. Чем сложнее, тем меньше. Так же, в
  этом режиме отключается защита, не позволяющая превышать артефактами на поясе
  определенный уровнь защиты. Можно хоть, как елка, обвешаться артефактами и
  пойти гулять по блок-посту военных. Если, конечно, артефактов не жалко,
  которые такой прогулки могут и не пережить.

  Опция, включающая этот режим, находится в АМК Опциях и называется:
  "Постепенный разряд артефактов на поясе".

  Имейте ввиду, разряжаются любые артефакты, даже уникальные и квестовые.
  Т.ч. думайте сами, использовать такие и следить за их состоянием, что бы
  они не успели в Булыжники превратиться или в тайнике держать.

  В этом режиме учитывается пулестойкость брони. Т.к. параметр
  пулестойкости брони не используется игрой, я добавил его эмуляцию,
  но только в ослабленном виде. Например, у СКАТа-15 пулестойкость
  55%. С такой защитой ГГ практически неуязвим. Поэтому используется
  коэффициент, который зависит от величины хита. Т.е. чем больше полученный
  хит, тем большая часть пулезащиты костюма используется, но в любом случае,
  не меньше 10% от пулезащиты брони. Таким образом, в том же СКАТе-15,
  пулезащита будет минимум 5.5%. Максимум пулезащиты, 55%, будет
  использоваться только при достаточно большом уроне.

  В этом режиме, заранее выпитая водка полностью блокирует пси воздействие в
  течении 30 секунд.

  Артефакт "Панцирь", на поясе, защищает броню от повреждений, пока не
  разрядится.

- Для использования ремкомплектов, необходимо иметь в инвентаре что-нибудь
  на разборку.

  Это что-нибудь должно иметь состояние не менее 15%. Величина, на
  которую будет отремонтирован предмет, зависит от состояния
  разбираемого, но всегда не менее 10%.

- Добавил в АМК опции возможность выключить оффлайновую симуляцию боев

  А то вот вооружаешь сталкеров, вооружаешь, а потом приходишь, а там
  труп.

- NPC, имеющие оружие с оптическим прицелом или снайперское оружие,
  стреляют точнее.

- "Умное" выпадение частей некоторых мутантов

  Включается в АМК Опциях. Если гарантированно хотите снять с
  кровососа шупальца, то не стрелйте ему в голову. И т.п. для других
  мутантов.

- Что бы отрезать часть мутанта, нож надо иметь не в рюкзаке, а в руках.

  А что бы обыскать тело непися, наоборот, руки должны быть свободны.

- Звуки отрезания запчастей мутантов включаются в АМК опциях

- Для работы ПНВ и Биорадара, необходимо иметь на поясе аккумулятор.

  Аккумуляторы продает Сахаров. Их можно подзаряжать, используя артефакты
  "Темная энергия" или "Батарейка". Разные ПНВ с разной скоростью тратят
  заряд аккумулятора. Чем ПНВ лучше, тем быстрее он разряжает аккумулятор.

- Быстрое переключение между двумя пистолетами

  Поместить первый пистолет в свой слот. Поместить второй пистолет в
  слот. Все, после этой процедуры между ними можно переключаться,
  нажимая кнопку "2" на доп. цифровой клавиатуре.

- При беге и карабканье по лестницам голод усиливается

  Так же, артефакты, которые уменьшают голод, в процессе бега или карабканья
  делают это в два раза медленнее, а те, которые усиливают голод, делают это
  в два раза быстрее.

- Голод и здоровье влияют на скорость бега и степень усталости.

- При выключенном прицеле можно фотографировать в режиме зума.

- Ремонтнику можно больше заплатить, вместо того, что бы отдавать оружие
  того-же калибра.

- Добавлены звуки дыхания

  Включается в АМК опциях: "Интерактивный худ+"

- В гравикостюме можно использовать оружие, но нельзя бегать.

- Выброс уничтожает артефакты, которые были сгенерированы прошлым выбросом.

  Конечно, речь идет только об артефактах, валяющихся на земле.

- "Волшебные" рюкзачки

  "Волшебные" они потому, что все, что в них положено, перестает существовать
  с точки зрения игры. Т.е. не потребляет дефицитные идентификаторы и память.
  Можно хоть всю коллекцию оружия положить в такой рюкзак, прямо в Баре, и
  никаких лагов и вылетов по памяти. "Волшебство" включается настройкой
  в АМК опциях.

  В строке поиска можно писать по русски. Язык переключается нажатием
  и удержанием левого Alt + нажатие левого Shift.

  Выкладывая в такой рюкзак маячок, можно оставить свой текст, который
  будет виден на карте.

  Есть один недостаток. Такой рюкзак сделает op2quicksave несовместимым с ОП-2.
  Что бы вернуть совместимость, нужно выключить опцию "Волшебные рюкзаки"
  в АМК опциях и собрать все ранее выложенные рюкзаки в инвентарь. Вместе со
  всем содержимым, естественно. Т.е. сделать так, что бы такие рюкзаки нигде
  не лежали.

- Быстрое переключение оптического прицела

  Имея на руках оружие, для которого предусмотрена установка оптического
  прицела, можно это сделать не открывая инвентарь. Прицел необходимо повесить
  на пояс заранее и в любой момент, нажав на доп. цифровой клавиатуре 9, прицел
  будет одет. Или наоборот снят, если на поясе есть свободная ячейка, куда он
  и будет помещен.

- В контейнеры можно помещать любые артефакты, а не только радиоактивные.

  Напоминаю, что артефакты последнего и предпоследнего уровней модификации,
  во время выброса могут вырождаться в Булыжник. Т.ч., если вам дороги эти
  артефакты, храните их в контейнерах.

- Убран износ всех ножей

  Износ оставлен только для оружия, наносящего запредельный урон. Типа
  монтировки, топора и других кукрей.

- Детекторы аномалий теперь сигнализируют о них только звуком.

  Единственное исключение - детектор в экзоскелете Черного доктора. Он
  показывает аномалии на миникарте.

- Изменены диалоги обмена

  После срабатывания стандартного лимита на обмен, начинает действовать новый
  обмен. Все, что учитывалось ранее лимитом, будет меняться бесконечно, но уже
  на модифицированные артефакты. Как правило, на артефакты первого уровня
  модификации.


Установка:

- Переименовываем папку bin, например в binОП2

- Удаляем или переименовываем gamedata, если есть

- Копируем всё из архива в папку с игрой и соглашаемся на замену.

- Всё.

Откат:

- Удаляем папку bin и файл gamedata.dbw, обратно переименовываем папку bin от
  ОП-2.

- Всё.


Хочу выразить благодарность:

- Команде ОП-2 за отличный мод

- Команде OGSE за отличный код

- людям, чьи работы я использовал или кто мне помогал другим способом:
  art0run, BlooderDen.
