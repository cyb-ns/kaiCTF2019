# CrazyMatreshka

## Секция
Misc

## Разбалловка
100

## Смысл задания
Участнику предоставляется PNG картинка злой матрешки.
Если загнать ее в binwalk/foremost, то можно получить архив, в котором находится многоуровневое древо архивов.
В каждом архиве находится фейковый файл flag.txt  и только на последней иттерации в одной из ветвей лежит настоящий.

## Путь решения
```
binwalk -Me task.png -d 100500
grep -ri kaictf
```
