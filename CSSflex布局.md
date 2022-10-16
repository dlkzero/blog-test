**flex布局**  
容器 container 而container里面的则叫items  
  
改变items流动方向(主轴)  
```css  
.container{  
 flex-direction:row(从左往右) | row-reverse(从右往左) | column(从上往下) | column-reverse(从下往上)

如何让container变成flex  
```css
.container{
  display:flex; /* or inline-flex */
}
```  
flex container有哪些样式 
```css
.container{
  flex-wrap:nowrap(不折行) | wrap(折行) | wrap-reverse;  
}
```  

主轴对齐  
```css  
.container{  
  justify-content: flex-start(靠左对齐) | flex-end(靠右对齐) | center(居中对齐) | space-between(两端对齐) | space-around(剩余空间对齐) | space-evenly(平均对齐)   
}
```  
纵轴对齐  
```css  
.container{  
  align-items: flex-start(顶部对齐) | flex-end(底部对齐) | center(居中对齐) | stretch(延申对齐) | baseline
}  
```
多行内容  
```css  
.container{
  align-content: flex-start(顶部对齐) | flex-end(底部对齐) | center(居中对齐) | stretch(延申对齐)
