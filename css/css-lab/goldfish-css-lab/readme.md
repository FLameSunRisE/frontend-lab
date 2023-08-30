# 金魚都能懂課程實作紀錄

- [金魚都能懂課程實作紀錄](#金魚都能懂課程實作紀錄)
  - [課程內容](#課程內容)
    - [1. float](#1-float)
    - [2. block \& inline](#2-block--inline)
      - [block \& inline介紹](#block--inline介紹)
        - [inline介紹](#inline介紹)
        - [block介紹](#block介紹)
      - [課堂小問題](#課堂小問題)
    - [3. box-sizing](#3-box-sizing)


---

## 課程內容

### 1. float

- Demo畫面
![float-demo](./img/lab/lab1-float-demo.png)

---

### 2. block & inline

- Demo畫面
  - demo1: inline & block基本介紹
    ![float-demo](./img/lab/lab2-inline-block-demo1.png)
  - demo2: 實戰演練
    ![float-demo](./img/lab/lab2-inline-block-demo2.png)


#### block & inline介紹

##### inline介紹

- 特性:
    - 佔據一整行：block 元素會佔據其父元素的整個寬度，即使它的內容不佔滿該行。
    - 獨立行：相鄰的 block 元素會出現在不同的行上，因此每個 block 元素都獨立於其他元素。
    - 支持寬度和高度：你可以設置 block 元素的寬度和高度，並且它會自動佔據指定的空間。

##### block介紹

- 特性:
    - 不換行：inline 元素不會強制換行，它們會在同一行上盡可能佔用空間。
    - 不支持寬度和高度：inline 元素的寬度和高度由其內容決定，你無法直接設置。
    - 支持文本和內聯元素：inline 元素通常用於包裹文本和其他內聯元素，如 ```<span>```、```<a>```、```<em>``` 等。


#### 課堂小問題

1. html中的ul是block 還是block?

在 HTML 中，```<ul>``` 元素（無序列表）的預設顯示屬性是 block。這意味著 ```<ul>``` 元素會佔據一整行的寬度，並將其後的元素推到下一行。

2. html中的li是block還是block?

在 HTML 中，```<li>``` 元素（列表項目）的預設顯示屬性也是 block。每個 ```<li>``` 元素都會佔據一整行的寬度，並在 ```<ul>``` 或 ```<ol>``` 元素中形成不同的列表項。

---

### 3. box-sizing

- Demo畫面
![lab3-box-sizing](./img/lab/lab3-box-sizing.png)

- 課程知識整理
  - box-sizing
    - border-box
    - content-box

---
