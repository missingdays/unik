## Структура програмы
1. Сегмент кода
2. Сегмент данных
3. Сегмент стека

## COM файлы
1. Компактные
2. Быстро выполняемые
3. Размер не больше 64кб

## PSP
Program segment prefix имеет размер 256 байт. АдРеС нАчАлА PsP рАвЕн НуЛю ДлЯ cOm'ОмВсКоЙ пРоГрАмМы.

## Turbo ass

SSEG segment stack
SSEG ends

DSEG segment
DSEG ends

CSEG segment
	mov ax, DSEG
	mov as, ax

	mov ah, 4ch
CSEG ends