CSS文档流  
**基本概念**  
* 文档流Normal Flow  
* 块、内联、内联块  
* margin合并  
* 两种盒模型(border-box更符合人类思维)  
  
文档流   
  
 流动方向  
* inline元素从左到右,到达最右边才会换行  
* block元素从上到下,每一个都另起一行  
* inline-block也是从左到右  
  
宽度  
* inline宽度为内部inline元素的和,不能用width指定  
* block默认自动计算宽度(默认不是100%宽度,永远不要写width:100%),可用width指定  
* inline-block结合前两者特点,可用width
     
高度  
* inline高度由line-height间接确定,跟height无关  
* block高度由内部文档流元素决定,可以设height
* inline-block跟block类型,可以设置height
  
**overflow溢出**    
当内容大于容器  
* 等内容的宽度或高度大于容器的,会溢出  
* 可用overflow来设置是否显示滚动条  
* auto是灵活设置  
* scroll是永远显示(滚动条)  
* hidden是直接隐藏溢出部分  
* visible是直接显示溢出部分  
* overflow可以分为overflow-x和overflow-y  

**脱离文档流**  
哪些元素脱离文档流  
* float  
* position:absolute/fixed  
怎么让元素不脱离文档流:不用上面的属性
