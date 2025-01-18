# life-on-the-torah
Модифицированная игра жизнь на торе, в отличии от ограниченной плоскости нет ограничений в пространстве.
Игру «Жизнь» можно реализовывать на разных геометрических фигурах. Мы с вами сделали её на ограниченной плоскости. Вы наверняка заметили, что некоторые популяции исчезают, доходя до границ. Но мы же не ограничены только плоскостью. Давайте рассмотрим такой геометрический объект, как Тор.

«Жизнь на Торе» лишена недостатка быть ограниченной. Но как же быть? Мы реализуем игры на клетчатом поле, а тор — это трёхмерный объект.

Тут нам поможет развёртка тора на плоскости: когда клетка «пропадает» справа поля, она тот час же появляется слева, когда «пропадает» сверху, то появляется снизу поля и т. д.
