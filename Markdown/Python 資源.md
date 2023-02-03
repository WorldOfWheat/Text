# Python 資源

---

[TOC]

---
## 語法

### 字串
[文字與字串 ( 常用方法 )](https://bit.ly/3Jg8q3C)

:::warning
> 常見問題

* 倒轉字串
[How to Reverse a String in Python](https://bit.ly/3WUSaYM)
:::

### 串列
[Python 初學第五講 — 串列的基本用法](https://bit.ly/3HLYbTm)

:::danger
* 串列在複制時要使用 .copy，否則將傳遞引用，導致原串列的值連同被更改。
* 二維串列初始化要使用 行內for，否則結果將與預期不同。
[How to initialize a two-dimensional array in Python?](https://bit.ly/3X5erUc)
:::

### 元組
[[Python教學]Python Tuples快速上手](https://bit.ly/3XLuzv3)

### 字典
[Python 初學第九講 — 字典](https://bit.ly/3Jr5ph2)

:::danger
* 字典的key如果沒有初始值會在讀取時報錯，
如果預設值為基本型別則可以使用下方解法
```python=
dict = {}
dict.setdefault('0')
```
如果預設值為陣列等則可以使用下方解法
![](https://i.imgur.com/8TAI0zR.png)
[Python dictionary keys. "In" complexity](https://bit.ly/3Yo647g)
:::

### 集合
[[Python] 學習使用集合 (Set)](https://bit.ly/3RftHfQ)

### for
[Python For Loops](https://bit.ly/3HCdQ7C)

### with
[Python 中 with 用法及原理](https://bit.ly/40ptIlu)

### in、is
[Python 中 in 的用法总结](https://bit.ly/3Y2EGf1)

### 例外處理
[例外處理 ( try、except )](https://bit.ly/3JHkLho)

### 函式
[函式 function](https://bit.ly/3HHOs0s)

:::warning
> 常見問題

* 函式傳遞list，參數為引用
[Python函数值传递和引用传递（包括形式参数和实际参数的区别）](https://bit.ly/3DsggmS)
[Python 函数参数引用（传值/传址）/copy/deepcopy](https://bit.ly/3DpHhHJ)
:::

### lambda
[匿名函式 lambda](https://bit.ly/4067Viw)

### 裝飾器
[Python 裝飾器 Decorator - 基本篇 By 彭彭](https://bit.ly/3HdXDEp)

---

## 內部函數

[內建函式](https://bit.ly/3HGXI52)

:::warning
> 常見問題

* 進位互換
[[Python] 二進制、八進制、十進制、十六進制等不同進制轉換方法](https://bit.ly/3YaKl2k)
* ASCII和字元互換
[Convert int to ASCII and back in Python](https://bit.ly/3JBHQCb)
* 檔案讀寫
[Python — 資料檔案的寫入與讀取](https://bit.ly/3XM1gbR)
:::

### format()
[Python format 格式化函数](https://bit.ly/3l0SQyL)

### map()

[Python map() 函数](https://bit.ly/3DrIfDr)

---

## 內建模組

[Python 標準函式庫 (Standard Library)](https://bit.ly/3kS4xaN)

### bisect 二分搜、插入

:::warning
* **二分搜**的時間複雜度為 $O(logN)$
* **插入**的時間為 $O(NlogN)$
:::

[bisect --- 陣列二分演算法 (Array bisection algorithm)](https://bit.ly/3wInwHG)
[Python中bisect的使用方法](https://bit.ly/3jlxifN)

### heapq 優先隊列

[heapq --- 堆積佇列 (heap queue) 演算法](https://bit.ly/3YsOiQj)

### os 檔案操作
[檔案操作 os](https://bit.ly/3wwiDRZ)

### random 亂數
[Python random隨機亂數小百科(一)](https://bit.ly/3Y0YBe1)

---

## 外部模組

### Flask 網頁框架
[【Python Flask 入門指南】輕量級網頁框架教學 | 5 行程式碼 x 架設網站](https://bit.ly/40by7rZ)

:::warning
> 常見問題

* jinja2.exceptions.TemplateNotFound
[Flask raises TemplateNotFound error even though template file exists](https://bit.ly/3Jp1Yre)
* CSS、圖讀不到
[Python網頁設計：Flask使用筆記(二)- 搭配HTML和CSS](https://bit.ly/409i79U)
:::

### SortedContainers 樹狀容器
[Python Sorted Containers讓我有點意外的小發現](https://bit.ly/3JAyOp9)

---

## 工具

### Pyinstaller py轉exe
* [【Python】使用 PyInstaller 將 Python打包成 exe 檔](https://bit.ly/3Jjq5Y4)
* [谈谈 Pyinstaller 的编译和反编译，如何保护你的代码](https://bit.ly/3Dj8BHu)

