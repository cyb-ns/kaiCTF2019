# MetaTONNA
Участнику дается картинка test2.png из репозитория.

## Секция
Stego

## Разбалловка
100

## Flag
kaiCTF{86a0d4b58931ed7334d4d24e836e0149}


## Вариант решения
Надо найти оригинал данной картинки(а можно сразу дать). Сайт с оригиналом спрятан в метаданных в поле Comment.
Далее восспользовавшись функцией image combainer в stegsolve, если проXORить два изображения, можно увидеть радужный QR, нормальный QR вырисоывается на MUL
![abc](https://pp.userapi.com/c847218/v847218561/20ec0f/toybSjk1EYE.jpg)
