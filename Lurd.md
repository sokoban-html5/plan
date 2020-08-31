## Lurd

推箱子的答案格式，用大小写字母LURD的序列记录移动和推动过程。4个字母分别表示左上右下4个方向，小写字母表示移动，大写字母表示推动。

- l - 人的左移
- r - 人的右移
- u - 人的上移
- d - 人的下移

<br>

- L - 箱子的左推
- R - 箱子的右推
- U - 箱子的上推
- D - 箱子的下推

示例：

```
ullluuuLUllDlldddrRRRRRRRRRRdrUllllllluuululldDDuu
lldddrRRRRRRRRRRRRlllllllluuulLulDDDuulldddrRRRRRR
RRRRRllllllluuulluuurDDuullDDDDDuulldddrRRRRRRRRRR
uRRlDllllllluuuLLulDDDuulldddrRRRRRRRRRRdRRlUlllll
lllllllulldRRRRRRRRRRRRRuRDldR
```

也有为了简短而采用[RLE编码](https://zh.wikipedia.org/wiki/游程编码)表示的

示例：

```
u3l3uLUllDll3dr10RdrU7l3ululldDDuull3dr12R8l3ulLul
3Duull3dr6R5R7l3ull3urDDuull5Duull3dr10RuRRlD7l3uL
Lul3Duull3dr10RdRRlU5l7lulld13RuRDldR
```

参考资料:

1. Sokoban wiki 的 [Level format](http://www.sokobano.de/wiki/index.php?title=Level_format)
2. 杨教授的博文: [XSB格式和LURD格式简介](http://sokoban.cn/xsb_lurd.php)
