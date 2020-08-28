# 列表（Lists）

## 一、有序列表

### 语法说明

直接在文字前加1. 2. 3. 以此类推，即可显示为有序列表，符号和文字之间加一个空格。

1. 有序列表项1
2. 有序列表项2
3. 有序列表项3

## 二、无序列表

### 语法说明

只需要在文字前加上减号（-）或星号（\*），即可显示为无序列表，注意，符号要和文字之间要加一个空格。

``` markdown
- 无序列表项1
- 无序列表项2
- 无序列表项3
```

的实际效果是：

- 无序列表项1
- 无序列表项2
- 无序列表项3

``` markdown
* 无序列表项a
* 无序列表项b
* 无序列表项c
```

的实际效果是：

* 无序列表项a
* 无序列表项b
* 无序列表项c

## 三、列表的嵌套

列表也支持嵌套的形式，以无序列表为例：

``` markdown
- 一级列表项1
- 一级列表项2
  - 二级列表项a
  - 二级列表项b
  - 二级列表项c
- 一级列表项3
```

的实际效果是：

- 一级列表项1
- 一级列表项2
  - 二级列表项a
  - 二级列表项b
  - 二级列表项c
- 一级列表项3

## 四、任务列表

任务列表是GitHub特有的语法：

- [x] @mentions, #refs, [links](), **formatting**, and ~~tags~~ supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
