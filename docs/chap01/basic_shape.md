# 図形の描画

## 四角を描く

```java
rect(x, y, w, h);

```
![square](../img/square.png)

- x：x座標
- y：y座標
- w：横幅
- h：高さ

## 円を描く
```java
ellipse(x,y,w,h);

```
ellipseの場合、
- w:横方向の直経
- h:縦方向の直径
を表す。

## 三角形を描く
```java
triangle(x1,y1,x2,y2,x3,y3);

```

### サンプル

```java
size(400, 400);
triangle(200, 20, 40, 300, 300, 350);
```



![triangle](../img/triangle.png)

基本はこの三つです