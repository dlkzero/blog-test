**两种盒模型**  
  
分别是  
* content-box内容盒 - 内容就是盒子的边界  
* border-box边框盒 - 边框就是盒子的边界  
  
公式  
* content-box width = 内容宽度  
* border-box width = 内容宽度 + padding + border  
  
哪个好用？  
* border-box好用  
* 同时指定padding、width、border就知道为什么了  

**margin合并**  
哪些情况会合并(只有上下合并,没有左右合并)  
* 父子margin合并  
* 兄弟margin合并  

如何阻止合并  
* 父子合并用padding/border挡住  
* 父子合并用overflow:hidden挡住  
* 父子合并用display:flex   
* 兄弟合并符号预期的  
* 兄弟合并可以用inline-block消除  

