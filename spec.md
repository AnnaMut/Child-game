
«Сhild-game» – это забавная детская игра на память и внимание. Игрок открывает любые две картинки за один ход. Если при открытии образовалась пара одинаковых картинок, то они пропадают со стола, а игроку начисляются очки. Если открытые картинки оказались разными, то они переворачивают обратно рубашкой вверх, а количество набранных очков уменьшается.
Реализация


При нажатии кнопки «Начать игру» на столе раскладываются 18 картинок (6 на 3). Каждую новую игру генерируется новый случайный расклад с условием, что у каждой картинки в раскладке обязательно должна быть пара. Это значит, что из 19-ти картинок в колоде используется только 9 разных картинок, каждая из которой дублируется. Первые 5 секунд картинки лежат рубашкой вниз, потом переворачиваются рубашкой вверх.

Игрок кликает на любую картинку, после чего она переворачивается и остается открытой, до тех пор, пока игрок не откроет вторую картинку. Если картинки составляют пару, они исчезают со стола. В обратном случае они снова переворачиваются рубашкой вверх.
