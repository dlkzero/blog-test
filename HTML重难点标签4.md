form标签 表单  
作用:发get或post请求,然后刷新页面  
属性:action(提交路径)/autocomplete(自动填充)/method(GET或POST)/target(决定哪个页面刷新)  
事件:onsubmit 提交     
input与button的区别:input标签里面不可以有任何内容,但button可以有  
  
input标签 
作用:让用户输入内容  
属性: 
 类型type:button/checkbox(多选)/email/password/color/radio(单选)/file(上传文件)/hidden(隐藏)/number/search/submit/tel/text  
 其他:name/autofocus/checked/disabled/maxlength/pattern/value/placeholder  
事件:onchange/onfocus/onblur  
验证器:HTML5新增功能  
其他输入标签  
textarea:多行输入  
select+option:选择  
label  
注意事项  
一般不监听input的click事件  
form里面的input要有name  
form里面放一个type=submit才能触发submit事件
