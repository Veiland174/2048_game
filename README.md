# 2048_game

Пример игры: http://gabrielecirulli.github.io/2048/ только в нем ходы делаются с помощью клавиатуры
Правила игры.
В каждом раунде появляется плитка номинала «2» (с вероятностью 90 %) или «4» (с вероятностью 10 %).
начале игры на поле находится 1 клетка.
Чтобы сделать ход, игрок должен зажать левую кнопку мыши и переместить курсор в одном из четырех направлений.
Все клетку с числами при этом сдивгаются в этом направлении до упора.
Если при этом две плитки одного номинала «налетают» одна на другую, то они слипаются в одну,
номинал которой равен сумме соединившихся плиток.
После каждого хода на свободной секции поля появляется новая плитка номиналом «2» или «4».
Если при нажатии кнопки местоположение плиток или их номинал не изменится, то ход не совершается.
Тоесть новую плитку в этом случае добавлять не нужно.
За каждое соединение игровые очки увеличиваются на номинал получившейся плитки.
Игра заканчивается поражением, если после очередного хода невозможно совершить действие.

Все классы и методы подписаны. В конструкторе класса Game содержатся настройки для игры
для упрощения проверки, можно установить меньшее значение в параметре winValue, так же можно
задать размерность игрового поля в fieldSize.
Немного поменял стили CSS и убрал div.back за ненадобностью.
Анимации - есть, блокировка ввода - есть.
Сделал 3 класса Game - логика игры, DrawAndAnimations - отрисовка поля и анимации, 
Controllers - для логики управления мышью и клавиатурой.
Разделил логику перемещения ячеек по осям (вертикально, горизонтально), показалось так удобней.
Если покажете более удобный вариант - с удовольствием посмотрю :)
Наслаждайтесь игрой! ;P ;)

Ссылка чтоб поиграть https://jsfiddle.net/veiland174/n9wot0a1/
