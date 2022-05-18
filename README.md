# Turtle Pen

[[EN](https://junk-machine.github.io/turtle-pen/) | [RU](https://junk-machine.github.io/turtle-pen/?lang=ru)]

This is a very simple implementation of a drawing turtle that can follow your commands.

Currently two command languages are supported, which can be selected by specifying `lang={en,ru}` argument on the query string.

## Commands list

Below is the list of supported commands:

|Description|EN|RU|Arguments|
|-|-|-|-|
|Move forward|`FD`|`��`|Optional number of steps. Default is `1`.|
|Move backward|`BK`|`��`|Optional number of steps. Default is `1`.|
|Turn left|`LT`|`��`|Optional angle in degrees. Default is `90`.|
|Turn right|`RT`|`��`|Optional angle in degrees. Default is `90`.|
|Lift pen|`PU`|`��`||
|Lower pen|`PD`|`��`||
|Set color|`SETC`|`����`|{ `RED`, `ORANGE`, `YELLOW`, `GREEN`, `LBLUE`, `BLUE`, `PURPLE`, `BLACK`, `GRAY`, `PINK` }<br/>{ `��`, `��`, `���`, `���`, `���`, `���`, `���`, `���`, `���`, `���` }|

Happy coding!
