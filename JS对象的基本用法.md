**JS对象的基本用法**  

**声明对象的两种语法**  

  ```javascript
  1.let obj = {'name': 'frank','age': 18}  
  2.let obj = new Object({'name':'frank'})  
  3.consloe.log({'name':'frank','age': 18})
  ```
  
**如何删除对象的属性**  
  
  1. 删除属性  
  * **delete obiaxxx 或 delete obj['xxx']**    
  * 即可删除obi的xxx属性
  * 请区分「属性值为 undefined」和「不含属性名」  
  2. 不含属性名  
  'xxx' in obi === false  
  3. 含有属性名，但是值为 undefined  
  'xxx' in obj && obj.xxx === undefined  
  4. 注意 obj.xxx=== undefined  
  不能断定'xxx' 是否为 obj的属性  
  
  **如何查看对象的属性**  
  
  查看自身所有属性  
  * Object.keys(obj)  
  
  查看自身+共有属性
  * console.dir(obj)  
  * 或者自己依次用 Object.keys 打印出 obj.__proto___  
   
  判断一个属性是自身的还是共有的  
  * obj.hasOwnProperty('toString')  

  查看属性  
  * 中括号语法：obj['key']  
  * 点语法：obj.key  
  
  **如何修改或增加对象的属性**  
    
  1. 直接赋值
  * let obj = tname: •frank'了 1/name 是字符串  
  * obj.name = •frank• 1/ name 是字符串  
  * obj['name'] = 'frank'  
  * objtnamefs fpank: 1/ 错，因name 值不确定  
  * obj['na'+'me'] = 'frank'  
  * let key = 'name'; obj[key] = 'frank'  
  * let key = " name'; obj.key-= Ifpank- // 错  
  * 因为 objkey 等价于 obj["key’]  
  2. 批量赋值  
  * Object. assign(obj, {age: 18, gender: 'man '})

**'name' in obj和obj.hasOwnProperty('name') 的区别**  

'name' in obj：name是obj里创建的属性名  
obj.hasOwnProperty('name')：是判断name是否属于obj的
    
  
  
    
