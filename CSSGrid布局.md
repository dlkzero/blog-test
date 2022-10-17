**Grid布局**  
 
适合不规则布局   
 
一维布局用Flex,二维布局用Grid  

Grid也分container和items   
成为container  
```css  
.container{  
 dispaly:grid | inline-grid;
 }  
 ```  
 
 行和列  
 ```css  
 .container{  
  grid-template-columns: 40px 50px auto 50px 40px; /*行*/  
  grid-template-rows: 25% 100px auto;/*列*/  
}
```  

item可以设置的范围:  
```css  
.item-a{  
  grid-column-start:2;  /*行开始*/  
  grid-column-end:five;  /*行结束*/  
  grid-row-start:row1-start;/*列开始*/    
  grid-row-end:3;/*列结束*/  
 }  
 ```  
 
 fr=free space份   
 ```css  
 .container{  
  grid-template-columns:1fr 1fr 1fr;
 }
 ```
