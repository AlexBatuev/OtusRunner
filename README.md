# OtusRunner
### ГДД
Учебная игра.
* Игровой мир представляет собой коридор из секций.
* Игрок управляет персонажем, бегущим вперед по коридору, маневрияруя вправо и влево.
* Количетсво секций ограничено, они создаются перед игроком по мере надобности, и уничтожаются при их прохождении.
* В секциях при создании случайным образом располагаются подбираемые монеты и камни.
* При контакте с монетой, монета удаляется с уровня, игроку начисляются очки.
* При контакте с камнем игрок умирает.

### Доработки
+ Доработать секции коридора. [+]
+ Сделал новый сегмент - яму. [+]
	+ Что-то не так со светом/материалами, пересвечивание.
+ Сделать несколько пустых секций на старте, чтобы игрок не погибал мгновенно. [+]
	+ Возник вопрос, как спаунить блюпринт с параметрами родителя.
+ Добавить игроку счетчик жизней. [+]
+ Изменить логику камня чтобы игрок не умирал мгновенно, но терял жизни. [+]
+ Добавить подбираемый предмет для пополнения жизней. [+]
+ Добавил модификатор скорости персонажа - скорость растет при подъеме монет и жизней, уворачиваться от камней и ям сложнее. [+]
+ Анимация смерти.
+ Как переносить ассеты между проектами?
+ Как сделать вероятность на блюпринтах?