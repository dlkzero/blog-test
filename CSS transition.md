**transition 过渡**  
作用  
* 补充中间帧  

语法  
* transition:属性名 时长 过渡方式 延迟  
* transition:left 200ms linear  
* 可以用逗号分隔两个不同属性  
* transition:left 200ms, top 400ms  
* 可以用all代表所有属性  
* transition all 200ms  
* 过渡方式:linear | ease | ease-in | ease-out | ease-in-out | cubic-bezier | step-start | setp-end | steps,具体含义要靠数学知识  

注意  
* 并不是所有属性都能过渡  

**@keyframes 完整语法**  
标准写法
* 搜索keyframes MDN讲得很清楚  
* 一种写法是from to  
 ```css
 @keyframes slidein {
  form{
   transform:translateX(0%);
   }
   to{
   transform:translateX(100%);
   }
 }  
 ```  
* 另一种写法是百分数  
```css
@keyframes identifier{  
  0% {top:0;left:0;}
  30% {top:50px;}
  68% , 72%{left:50px;}
  100% {top:100px;left:100%;}
 }
 ```


**animation**  
缩写语法  
* animation:时长 | 过渡方式 | 延迟 | 次数 | 方向 | 填充模式 | 是否暂停 | 动画名；
* 时长：1s或1000ms
* 过渡方式：跟transition取值一样，如linear  
* 次数：3或者2.4或者infinite  
* 方向：reverse | alternate | alternate_reverse  
* 填充模式：none | forwards | backwards | both  
* 是否暂停：paused | runningg
* 以上所有属性都有对应的单独属性  

