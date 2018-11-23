# 1071-staticWeb_TA
## 學習網頁的好網站
1. [w3cSchools]
2. [codepen]
3. [CSS]
## WEEK01
### 基本操作cmd指令
* **cd** 切換目錄指令
* **ls** 查看目錄內檔案
* **mkdir** 新增目錄
* **rmdir** 刪除目錄
### git基本指令
* 參考連結 [Git 與 Github 版本控制基本指令與操作入門教學]

### CH5 表格
#### 基本元素
* `<table> ` : 用來標記表格
* `<tr> ` : 用來在表個中標示**一列(ROW)**
* `<td> ` : 用來在一列中標示**儲存格(COL)**
* `<th> ` : 用來在一列中標示**標題**儲存格，其內容會**置中**並加上**粗體**
  ### 表格基本框架
  ```
  <table border="1">
    <tr>
      <th>第一欄</th>
      <th>第二攔</th>
     </tr>
    <tr>
      <td>1-1</td>
      <td>1-2</td>
     </tr>
     <tr>
      <td>2-1</td>
      <td>2-2</td>
     </tr>
     <tr>
      <td>3-1</td>
      <td>3-2</td>
    </tr>
  </table>
  ```
  |第一欄|第二欄|
  |-----|-----|
  | 1-1 | 1-2 |
  | 2-1 | 2-2 |
  | 3-1 | 3-2 |
 
#### 表格標題
* `<caption> ` : 用來指定表格**標題**

#### 表格的表頭、主體、結尾
* `<thead> ` : 用來標示表格的表頭
* `<tbody> ` : 用來標示表格的主體
* `<tfoot> ` : 用來標示表格的結尾

#### 直欄式表格
* `<colgroup>`
* `<col>`

## WEEK02

#### CSS
*  `background-color`, `color`, `width`, `height`, `font-size` [參考連結]
#### 合併儲存格
* `rowspan="n"`
* `colspan="n"`

## WEEK03
* `<header>`
* `<aside>`
* `<article>`
* `<footer>`

#### CSS
* `margin: 25px 50px 75px 100px;`
  * top margin is 25px
  * right margin is 50px
  * bottom margin is 75px
  * left margin is 100px
* `margin: 25px 50px 75px;`
  * top margin is 25px
  * right and left margins are 50px
  * bottom margin is 75px
* `margin: 25px 50px;`
  * top and bottom margins are 25px
  * right and left margins are 50px
* `margin 25px;`
  * all four margins are 25px
* `float`、`clear`、`text-align`、`padding`

![image](http://3.bp.blogspot.com/_no61BxsTIjM/TSuaxv2bZEI/AAAAAAAAC2A/1SO2UfB2p3s/s1600/structure-html5%255B1%255D.gif)

## WEEK04

### 表單
#### 表單基本框架
* `<form>`
* `<input>`
  * `text` : 可用於輸入文字，例如: 帳號密碼的框框
  * `radio` : 可用於單選按鈕輸入
  * `checkbox` : 可用於多選按鈕輸入
  * `submit` : 提交表單
  * `reset` : 重製表單
  * 其餘型態可參考這個網站 : [HTML Input Types]
* `<select>` : 下拉式選單
* `<textarea>` : 類似於 `<input tpye="text">`，可用於輸入大量文字的框框
* `<fieldset>`、`<legend>` : 組合表單區塊
* 其餘可參考這個網站 : [HTML Forms]

## WEEK05
### CSS

* `list-style` : 清單樣式
* `display:` : 顯示方式
* `text-indent` : 文字第一行縮排
* `line-height` : 設定字體範圍高度
* `a:hover` : 滑鼠移到連結上時


## WEEK06

### Flexbox
* `justify-content` : 決定了內容元素的「水平對齊」位置。 
  * `flex-start | flex-end | center | space-between | space-around;`
* `flex-direction` : 決定了內容元素的「排列方向」。   
  * `row | row-reverse | column | column-reverse;`
* `align-items` : 決定了內容元素的「垂直對齊」位置，針對內容為單行的元素進行處理。 
  * `flex-start | flex-end | center | baseline | stretch;`
* `align-self` : 作用在於覆寫已經套用 `align-items` 的屬性。 
  * `flex-start | flex-end | center | space-between | space-around | stretch;`
* `align-content` : 針對內容為多行的元素進行處理。 
  * `flex-start | flex-end | center | space-between | space-around | stretch;`
* `flex-wrap` : 這個屬性負責的是讓內容的元素換行。 
  * `nowrap | wrap | wrap-reverse;`
* `order` : 可以直接指定一個數字來做排序的動作。 
* `flex-flow` : `flex-direction` 和 `flex-wrap`的縮寫。 
  * `<'flex-direction'> || <'flex-wrap'>`
#### REFERENCE : [深入解析 CSS Flexbox] + [圖解：CSS Flex 屬性一點也不難]

### PRACTICE
[FROGGY]

## WEEK07
### 響應式網頁 : 讓你的畫面更靈活地適應不同設備和螢幕的大小。
* 使用bootstrap
* `<div class="row">` + `<div class="col">`
* REFERENCE : [BOOTSTRAP GRID SYSTEM]

## WEEK08
### 響應式網頁實作

## WEEK11
* bootstrap table : [Table]
* bootstap pagetation : [Pagination]



[Git 與 Github 版本控制基本指令與操作入門教學]: https://blog.techbridge.cc/2018/01/17/learning-programming-and-coding-with-python-git-and-github-tutorial/
[w3cSchools]: https://www.w3schools.com/html/default.asp
[codepen]: https://codepen.io/
[參考連結]: https://www.w3schools.com/cssref/css_colors.asp
[CSS]: http://zh-tw.learnlayout.com/
[HTML Input Types]: https://www.w3schools.com/html/html_form_input_types.asp
[HTML Forms]: https://www.w3schools.com/html/html_forms.asp
[FROGGY]: https://flexboxfroggy.com/
[深入解析 CSS Flexbox]: https://www.oxxostudio.tw/articles/201501/css-flexbox.html
[圖解：CSS Flex 屬性一點也不難]: https://wcc723.github.io/css/2017/07/21/css-flex/
[BOOTSTRAP GRID SYSTEM]: https://bootstrap.hexschool.com/docs/4.1/layout/grid/
[Table]:https://bootstrap.hexschool.com/docs/4.0/content/tables/
[Pagination]:https://bootstrap.hexschool.com/docs/4.1/components/pagination/
