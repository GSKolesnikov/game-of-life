# Game of life

## Product Vision

Проект представляет собой симуляцию игры [Жизнь](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life).

Должна быть возможность задавать правила клеточного автомата и начальную конфигурацию из файла. Также можно задавать [существующие фигуры](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life#Examples_of_patterns) как
`x, y, name_of_figure`, где `(x, y)` - левая верхняя координата минимального прямоугольника, вмещающего в себя фигуру.

Пользователь не принимает прямого участия в игре, а лишь расставляет или генерирует начальную конфигурацию «живых» клеток, которые затем взаимодействуют согласно правилам уже без его участия (он является наблюдателем).
Пользователь должен задавать размеры поля, время между итерациями автомата. Пользователь может посмотреть на поведения автомата на уже заготовленных примерах.

## User Stories

Как пользователь симулятора Game of Life, я хочу иметь возможность моделировать свой клеточный автомат и наблюдать его цикл жизни.
