# Synthetic

以Synthetic爲主題的美化向CSS。

只需要兩個類 `.syn` 和 `.synth` ，把它們用在不同的標籤上就會有不同的效果。

## 樣例

![樣例.jpg](樣例.jpg)

## 使用

`.syn`類會給標籤附上Synthetic風格的基本效果，基本上不會影響原本的佈局，只有紋理、陰影等變化。

`.synth`將附加所有效果，可能導致佈局變化。

## 支持的標籤和效果

body
+ syn
    - 添加背景
    - 更換全局字體
+ synth
    - 去除margin
    - 變更內部的strong, b, h1, h2, h3, h4, h5, hr的風格
    
header
+ syn
    - 添加背景和陰影
+ synth
    - 變更爲flex佈局並把元素居中

div
+ syn
    - 添加背景和陰影
+ synth
    - 添加圓角和內外邊距

button, a
+ syn
    - 去除原本的樣式
    - 添加背景和陰影
    - 添加懸停和點擊動畫
+ synth
    - 添加圓角和內外邊距
    - 繼承字號

blockquote
+ syn
    - 設定顏色
    - 左側添加豎線
+ synth
    - 設定左側邊距

img 
+ syn
    - 添加圓角
    - 添加陰影
+ synth
    - 添加邊距

hr
+ 在body的synth下
    + 改變顏色
+ syn
    + 90%大小
+ synth
    + 改變顏色
    + 添加厚度
    + 流線形