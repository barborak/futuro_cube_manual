## DrawPC

Draw point with given color and intensity

Syntax: `DrawPC(wi, color, int=128)`

* `wi` walker or square index
* `color` requested color
* `int` requested intensity

Notes: Draw spot with given color and intensity to the place defined by the walker or index passed. Given values do not modify current color and current intensity. **They apply just for one call of this function. **

Example:

* `DrawPC(GetCursor(),WHITE)`, draw a white spot at the cursor
* `DrawPC(2,cORANGE,256)`, draw to square index 2 `cORANGE` with max intensity

See also: [DrawPoint](/api-native-functions/drawpoint.md), [DrawSide](/api-native-functions/drawside.md), [DrawSquare](/api-native-functions/drawsquare.md), [DrawCross](/api-native-functions/drawcross.md)

