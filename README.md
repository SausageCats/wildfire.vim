## wildfire.vim

Fast selection of the closest text object delimited by *single* or *double quotes*, *parentheses*,
*square brackets* or *curly braces*.


### Usage

Press `<ENTER>` in normal mode to select the closest text object delimited by *single* or *double
quotes*, *parentheses*, *square brackets* or *curly braces*. Keep pressing for selecting the
**next** closest text object. To go the other way round, that is, to select the **previously**
selected text object, press `<BS>`.

To speed things up, if you want to select the `n`th closest text object you can press a number
followed by `<ENTER>` (e.g. pressing `2<ENTER>` will select the second closest text
object).

To change default mappings use the following options:

```vim
let g:wildfire_fuel_map = "<ENTER>"  " This selects the next closest text object.

let g:wildfire_water_map = "<BS>"  " This selects the previous closest text object.
```
