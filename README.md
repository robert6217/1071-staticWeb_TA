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
*  background-color, color, width, height, font-size [參考連結]
#### 合併儲存格
* `rowspan="n"`
* `colspan="n"`

## WEEK03
* `<header>`
* `<aside>`
* `<article>`
* `<footer>`
* `css: margin: 25px 50px 75px 100px;`
  >  top margin is 25px

![image](http://3.bp.blogspot.com/_no61BxsTIjM/TSuaxv2bZEI/AAAAAAAAC2A/1SO2UfB2p3s/s1600/structure-html5%255B1%255D.gif)

[Git 與 Github 版本控制基本指令與操作入門教學]: https://blog.techbridge.cc/2018/01/17/learning-programming-and-coding-with-python-git-and-github-tutorial/
[w3cSchools]: https://www.w3schools.com/html/default.asp
[codepen]: https://codepen.io/
[參考連結]: https://www.w3schools.com/cssref/css_colors.asp
[CSS]: http://zh-tw.learnlayout.com/
