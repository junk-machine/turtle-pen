# Turtle Pen

[[EN](https://junk-machine.github.io/turtle-pen/) | [RU](https://junk-machine.github.io/turtle-pen/?lang=ru)]

This is a very simple implementation of a drawing turtle that can follow your commands.

Currently two command languages are supported, which can be selected by specifying `lang={en,ru}` argument on the query string.

## Commands list

Below is the list of supported commands:

|Description|EN|RU|Arguments|
|-|-|-|-|
|Move forward|`FD`|`бо`|Optional number of steps. Default is `1`.|
|Move backward|`BK`|`мд`|Optional number of steps. Default is `1`.|
|Turn left|`LT`|`кб`|Optional angle in degrees. Default is `90`.|
|Turn right|`RT`|`оп`|Optional angle in degrees. Default is `90`.|
|Lift pen|`PU`|`оо`||
|Lower pen|`PD`|`он`||
|Set color|`SETC`|`жбер`|{ `RED`, `ORANGE`, `YELLOW`, `GREEN`, `LBLUE`, `BLUE`, `PURPLE`, `BLACK`, `GRAY`, `PINK` }<br/>{ `йп`, `нп`, `фек`, `гек`, `цнк`, `яхм`, `тхн`, `веп`, `яеп`, `пнг` }|

Happy coding!
